#### Test 575312435db8e90_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/GoogleHttpClient( 5610): GMS http client unavailable, use old client
--------- beginning of system
I/ActivityManager(  940): Killing 5381:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  940): failed to open /acct/uid_10014/pid_5381/cgroup.procs: No such file or directory
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4333): Classify the device as Phone.
I/CheckinTask( 4333): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 4333): Checking schedule, now: 1454412268815 next: 1454939517809
I/CheckinService( 4333): active receiver: disabled
I/ActivityManager(  940): Killing 5407:com.lge.email/u0a21 (adj 15): empty #11
D/CheckinService( 4333): Recording last checkin time for package unspecified as 1454412268851
W/libprocessgroup(  940): failed to open /acct/uid_10021/pid_5407/cgroup.procs: No such file or directory
I/ActivityManager(  940): Killing 5099:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
I/ActivityManager(  940): Killing 5432:com.google.android.partnersetup/u0a9 (adj 15): empty #12
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  940): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5669 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup(  940): failed to open /acct/uid_10009/pid_5432/cgroup.procs: No such file or directory
I/UpdateIcingCorporaServi( 1941): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
W/libprocessgroup(  940): failed to open /acct/uid_10006/pid_5099/cgroup.procs: No such file or directory
W/ActivityManager(  940): Scheduling restart of crashed service com.google.android.gms/.droidguard.DroidGuardService in 1000ms
D/AndroidRuntime( 5649): 
D/AndroidRuntime( 5649): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5649): CheckJNI is OFF
I/UpdateIcingCorporaServi( 1941): UpdateCorporaTask done [took 88 ms] updated apps [took 88 ms] 
D/AndroidRuntime( 5649): Calling main entry com.android.commands.am.Am
I/ActivityManager(  940): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  940): setTaskToReturnTo : TaskRecord{2e7ff4d9 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  940): setTaskToReturnTo : TaskRecord{2e7ff4d9 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  940): AppWindowTokenEx init.. 
D/ContextHelper(  940): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  940): Focus left window: Window{38f100ac u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5649): Shutting down VM
D/SplitWindow(  940): check instance of lgWin Window{3e46029b u0 Starting com.test.thalitest}
I/ActivityManager(  940): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5705 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/Finsky  ( 5669): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1941): Closing mic
I/MicrophoneInputStream( 1941): mic_close com.google.android.apps.gsa.speech.audio.u@167e85a7
V/AudioRecord( 1941): stop()
D/AudioRecord( 1941): AudioRecord->stop()
V/AudioFlinger(  287): RecordHandle::stop()
V/AudioFlinger(  287): RecordThread::stop
I/WindowStateAnimator(  940): Starting window displayed
I/SystemUI[Framework](  940): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
V/AudioFlinger(  287): Record stopped OK
D/PhoneStatusBar( 1384): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
V/AudioPolicyManager(  287): stopInput() input 17
V/AudioPolicyService(  287): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  287): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  287): AudioCommandThread() waking up
W/PhoneWindowManagerEx(  940): Call!!!getLGSystemUiVisibility. =0x0
V/AudioPolicyService(  287): AudioCommandThread() processing release audio patch
D/StatusBarManagerServiceEx(  940): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  940): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  940): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@22f494ba,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  940): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/AudioFlinger::PatchPanel(  287): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  287): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  287): ThreadBase::setParameters() routing=0
V/AudioFlinger(  287): sendConfigEvent_l() num events 1 event 2
I/[SystemUI]NavigationThemeResource( 1384): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1384):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1384): , Keyguard show=false, IME shown=false, Panel expanded=false
V/AudioFlinger(  287): processConfigEvents_l() remaining events 1
V/AudioFlinger(  287): processConfigEvents_l() DONE thread 0xb384e000
D/BarTransitions( 1384): draw background and invalidate : color = 8000000
D/audio_hw_primary(  287): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
D/BarTransitions( 1384): draw background and invalidate : color = a090909
,V/audio_hw_primary(  287): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  287): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  287): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  287): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  287): disable_audio_route: exit
E/audio_hw_primary(  287): disable_snd_device: enter 144
D/hardware_info(  287): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  287): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  287): stop_input_stream: exit: status(0)
V/audio_hw_primary(  287): in_standby: exit:  status(0)
V/AudioFlinger(  287): RecordThread: loop stopping
V/AudioPolicyService(  287): AudioCommandThread() going to sleep
V/AudioPolicyManager(  287): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  287): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  287): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  287): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  287): AudioCommandThread() waking up
V/AudioPolicyService(  287): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  287): AudioCommandThread() going to sleep
V/AudioPolicyService(  287): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  287): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  287): AudioCommandThread() waking up
V/AudioPolicyService(  287): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  287): setParameters(): io 17, keyvalue hotword_active=0, calling pid 287
V/AudioFlinger(  287): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  287): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  287): RecordThread: loop starting
V/AudioFlinger(  287): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  287): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  287): in_set_parameters: exit: status(0)
V/AudioFlinger(  287): processConfigEvents_l() DONE thread 0xb384e000
V/AudioFlinger(  287): RecordThread: loop stopping
V/AudioPolicyService(  287): AudioCommandThread() going to sleep
V/AudioRecord( 1941): stop()
V/AudioRecord( 1941): stop()
V/AudioRecord( 1941): stop()
V/AudioFlinger(  287): releasing 16 from 1941 for -1
V/AudioFlinger(  287):  decremented refcount to 0
V/AudioFlinger(  287): purging stale effects
V/AudioFlinger(  287): RecordHandle::stop()
V/AudioFlinger(  287): RecordThread::stop
V/AudioPolicyManager(  287): releaseInput() 17
V/AudioPolicyManager(  287): closeInput(17)
V/AudioFlinger(  287): closeInput() 17
V/AudioSystem(  287): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  940): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1743): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  287): ThreadBase::exit
V/AudioFlinger(  287): RecordThread: loop starting
V/AudioFlinger(  287): RecordThread 0xb384e000 exiting
D/audio_hw_primary(  287): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  287): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  287): in_standby: exit:  status(0)
V/AudioPolicyService(  287): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  287): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  287): AudioCommandThread() waking up
V/AudioPolicyService(  287): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  287): AudioCommandThread() going to sleep
V/AudioPolicyManager(  287): releaseInput() exit
V/AudioFlinger(  287): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  287): removeClient_l() pid 1941, calling pid 287
V/AudioSystem( 1941): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1990): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2049): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3170): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1384): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 1941): Hotword detection finished
I/HotwordRecognitionRnr( 1941): Stopping hotword detection.
D/ContextHelper( 5705): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/WebViewFactory( 5705): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/Finsky  ( 5669): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
I/LibraryLoader( 5705): Time to load native libraries: 5 ms (timestamps 3351-3356)
I/LibraryLoader( 5705): Expected native library version number "",actual native library version number ""
I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
W/Settings( 5669): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5669): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5669): com.android.vending: cancel(-1050172287) by com.android.vending
V/WebViewChromiumFactoryProvider( 5705): Binding Chromium to main looper Looper (main, tid 1) {108a260e}
I/ActivityManager(  940): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5755 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/LibraryLoader( 5705): Expected native library version number "",actual native library version number ""
I/chromium( 5705): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5705): Initializing chromium process, singleProcess=true
W/art     ( 5705): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5705): ApplicationContext is null in ApplicationStatus
V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 5669): com.android.vending: cancel(1003285959) by com.android.vending
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@5c50c07 on behalf of 5669
D/Ads     ( 5669): Skipping gmscore version check
D/Finsky  ( 5669): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5669): [1] Libraries$2.run: Finished loading 1 libraries.
D/PackageBroadcastService( 4333): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 4333): Loading module com.google.android.gms.games from APK com.google.android.play.games
W/ResourcesManager( 5755): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5755): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 5669): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/chromium( 5705): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
D/ChimeraModuleLdr( 4333): Loading module APK com.google.android.play.games
E/libEGL  ( 5705): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5705): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5705): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5705): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5705): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5705): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5705): Remote Branch: 
I/Adreno-EGL( 5705): Local Patches: 
I/Adreno-EGL( 5705): Reconstruct Branch: 
D/Finsky  ( 5669): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/Finsky  ( 5669): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/MultiDex( 5755): VM with version 2.1.0 has multidex support
I/MultiDex( 5755): install
I/MultiDex( 5755): VM has multidex support, MultiDex support library is disabled.
V/AudioPolicyService(  287): registerClient() client 0xb57e9580, uid 10316
D/BluetoothManagerService(  940): Message: 20
D/BluetoothManagerService(  940): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@23c4d3b9:true
D/BluetoothAdapterService(549885210)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ab7ce40
V/JNIHelp ( 5755): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5755): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5755): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16676ca0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5755): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5755): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5755): com.google.android.gms: cancel(39789) by com.google.android.gms
W/art     ( 5705): Attempt to remove local handle scope entry from IRT, ignoring
,I/art     ( 5755): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5755): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/AwContents( 5705): onDetachedFromWindow called when already detached. Ignoring
D/SystemWebViewEngine( 5705): CordovaWebView is running on device made by: LGE
,W/art     ( 5705): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5705): Attempt to remove local handle scope entry from IRT, ignoring
,D/ChimeraCfgMgr( 4333): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4333): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4333): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/Icing   ( 4333): Storage manager: low false usage 1.74MB avail 2.37GB capacity 4.06GB
,D/AsyncTaskServiceImpl( 4333): Submit a task: k
,D/ChimeraCfgMgr( 4333): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 4333): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/Activity( 5705): Activity.onPostResume() called 
,D/OpenGLRenderer( 5705): Render dirty regions requested: true
I/OpenGLRenderer( 5705): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5705): Enabling debug mode 0
D/k       ( 4333): Processing package: com.test.thalitest
D/GassUtils( 4333): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 4333): Found info for package com.test.thalitest in db.
,D/Atlas   ( 5705): Validating map...
D/SplitWindow(  940): check instance of lgWin Window{3ad1b64f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/chromium( 5705): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/NativeLibraryUtils( 5755): Install completed successfully. count=14 extracted=0
I/ActivityManager(  940): Killing 5452:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/InputDispatcher(  940): Focus entered window: Window{3ad1b64f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/libprocessgroup(  940): failed to open /acct/uid_10011/pid_5452/cgroup.procs: No such file or directory
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
,W/InputMethodManagerService(  940): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
E/MDM     ( 1733): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 4333): Restart initialization of location
I/ActivityManager(  940): Displayed com.test.thalitest/.MainActivity: +1s336ms
I/Timeline(  940): Timeline: Activity_windows_visible id: ActivityRecord{1eb8e9e u0 com.test.thalitest/.MainActivity t222} time:84238
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/Timeline( 5705): Timeline: Activity_idle id: android.os.BinderProxy@23b8bc35 time:84262
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  940): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5829 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/BaseAppContext( 4333): Using Auth Proxy for data requests.
W/BaseAppContext( 4333): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 4333): cleanUpNonGplusAccounts done.
W/BindingManager( 5705): Cannot call determinedVisibility() - never saw a connection for the pid: 5705
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,W/BaseAppContext( 4333): Using Auth Proxy for data requests.
,W/BaseAppContext( 4333): Using Auth Proxy for data requests.
,W/BaseAppContext( 4333): Using Auth Proxy for data requests.
W/BaseAppContext( 4333): Using Auth Proxy for data requests.
W/BaseAppContext( 4333): Using Auth Proxy for data requests.
,W/IcingInternalCorpora( 4333): getNumBytesRead when not calculated.
,D/JsMessageQueue( 5705): Set native->JS mode to OnlineEventsBridgeMode
,W/ActivityManager(  940): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Icing   ( 4333): updateResources: need to parse f{com.google.android.gms}
,I/Gmail   ( 5829): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 5829): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/art     ( 4333): Background partial concurrent mark sweep GC freed 19217(1279KB) AllocSpace objects, 7(112KB) LOS objects, 39% free, 13MB/23MB, paused 8.480ms total 115.275ms
,D/jxcore_app_log( 5705): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426127360
,W/ActivityManager(  940): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5829): getAccountsCursor
,W/ActivityManager(  940): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
E/Gmail   ( 5829): Error finding the version of the Email provider.....
E/Gmail   ( 5829): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5829): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5829): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5829): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5829): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5829): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5829): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5829): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5829): We do not support migrating this version of the Email provider.
,I/chromium( 5705): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/ActivityManager(  940): Killing 5473:com.android.gallery3d/u0a23 (adj 15): empty #11
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5829): Observing account changes for notifications
D/ChimeraCfgMgr( 4333): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4333): Module APK com.google.android.play.games already loaded
,W/libprocessgroup(  940): failed to open /acct/uid_10023/pid_5473/cgroup.procs: No such file or directory
,W/ActivityManager(  940): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
I/art     ( 5705): CheckpointMarkThreadRoots callback created = 0x9c11eab0
,I/art     ( 5610): Explicit concurrent mark sweep GC freed 7921(399KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 842us total 49.375ms
,I/art     ( 5705): CheckpointMarkThreadRoots callback created = 0x9c11ea80
V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@12fa7134 on behalf of 4333
I/CheckinService( 4333): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  940): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5887 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 436us total 23.345ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 21.512ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 348us total 25.069ms
,D/InitAlarmsService( 3827): Clearing and rescheduling alarms.
I/ActivityManager(  940): Process com.android.contacts (pid 5492) has died
,I/ActivityManager(  940): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5904 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@25583b5d on behalf of 4333
I/Gmail   ( 5829): notifyAccountChanged
I/Gmail   ( 5829): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/art     (  940): Explicit concurrent mark sweep GC freed 30325(1447KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.462ms total 187.628ms
I/ActivityManager(  940): Process com.lge.lockscreensettings (pid 5514) has died
I/Gmail   ( 5829): getAccountsCursor
,V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
I/Gmail   ( 5829): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@f95ccd2 on behalf of 4333
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 5904): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/Icing   ( 4333): Internal init done: storage state 0
,I/Gmail   ( 5829): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5829): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/CalendarProvider2( 5904): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@22b4b40d
I/Icing   ( 4333): Post-init done
,D/CalendarProvider2( 5904): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5904): Created com.android.providers.calendar.CalendarAlarmManager@108a260e(com.android.providers.calendar.CalendarProvider2@22b4b40d)
,D/CalendarProvider2( 5904): Scheduling check of next Alarm
,D/PhoneMonitor( 5887): Register our PhoneStateListener
D/CalendarProvider2( 5904): SCHEDULE_ALARM_REMOVE
,I/Gmail   ( 5829): getAccountsCursor
,I/CheckinService( 4333): Checkin interval check for package: unspecified last checkin: 1454412268851 min interval config: 0 actual interval: 4164
D/PhoneMonitor( 5887): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5887): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5887): [parse] Load xml
,V/TelephonyAutoProfiling( 5887): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5887): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,I/CheckinService( 4333): Checking schedule, now: 1454412273045 next: 1454412298809
I/CheckinService( 4333): active receiver: disabled
D/PhoneMonitor( 5887): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/art     ( 1733): Explicit concurrent mark sweep GC freed 35354(2MB) AllocSpace objects, 24(384KB) LOS objects, 39% free, 13MB/22MB, paused 2.787ms total 141.513ms
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 5705): Background sticky concurrent mark sweep GC freed 30095(3MB) AllocSpace objects, 11(2MB) LOS objects, 29% free, 13MB/19MB, paused 5.499ms total 62.366ms
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  940): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5932 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5932): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/ActivityManager(  940): Process com.google.android.apps.docs (pid 5550) has died
,I/Babel_SMS( 5932): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5932): MmsConfig.loadMmsSettings
,I/ActivityManager(  940): Process com.android.calendar (pid 3827) has died
I/Babel_SMS( 5932): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5932): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5932): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5932): MmsConfig.loadFromResources
E/Babel_SMS( 5932): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5932): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5932): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5932): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5932): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5932): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5932): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5932): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5932): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5932): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5932): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5932): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5932): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5932): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5932): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5932): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5932): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5932): found sensor: Motion Accel, handle=46
,W/art     ( 5932): Suspending all threads took: 8.595ms
,W/Settings( 5932): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 5932): CheckpointMarkThreadRoots callback created = 0xb042d4d0
I/Babel_Crash( 5932): startup - clean
I/art     ( 5932): CheckpointMarkThreadRoots callback created = 0xb042d4b0
,I/Babel   ( 5932): deleted: false for 0
,I/ActivityManager(  940): Process com.lge.eula (pid 5531) has died
W/AudioCapabilities( 5932): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5932): Unsupported mime audio/adpcm
W/AudioCapabilities( 5932): Unsupported mime audio/g726
W/AudioCapabilities( 5932): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5932): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 5932): Unsupported mime video/mjpg
W/VideoCapabilities( 5932): Unsupported mime video/theora
W/AudioCapabilities( 5932): Unsupported mime audio/evrc
,W/AudioCapabilities( 5932): Unsupported mime audio/qcelp
W/VideoCapabilities( 5932): Unrecognized profile 2130706433 for video/avc
I/CalendarProvider2( 5904): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5904): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
W/AudioCapabilities( 5932): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5932): Unsupported mime audio/qcelp
W/AudioCapabilities( 5932): Unsupported mime audio/evrc
,W/VideoCapabilities( 5932): Unsupported mime video/mp4v-esdp
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/VideoCapabilities( 5932): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 5932): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5932): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5932): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5932): Unrecognized profile 2130706433 for video/avc
,W/jxcore-log( 5705): Initializing JXcore engine
,W/jxcore-log( 5705): JXcore engine is ready
I/Icing   ( 4333): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/vclib   ( 5932): onServiceConnected
W/Babel   ( 5932): Attempted to change video mute state without an active call.
,W/art     ( 5932): Suspending all threads took: 5.322ms
,W/Thread-668( 5869): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6396]" dev="sockfs" ino=6396 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-668( 5869): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-668( 5869): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6462]" dev="sockfs" ino=6462 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-668( 5869): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-668( 5869): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-668( 5869): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26869]" dev="sockfs" ino=26869 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/ResourcesManager( 5932): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5932): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/jxcore-log( 5705): Starting JXcore engine
,D/Icing   ( 4333): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 4333): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  940): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5963 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AudioManager( 5217): getMode name:com.lge.qremote
,V/JNIHelp ( 5932): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AudioManager( 5217): getMode name:com.lge.qremote
,I/AudioManager( 5217): getMode name:com.lge.qremote
D/UEI.SmartControl( 5963): Quickset Services start...
,I/AudioManager( 5217): getMode name:com.lge.qremote
I/UEI.SmartControl( 5963): Manufacture = LGE
I/AudioManager( 5217): getMode name:com.lge.qremote
E/lowmemorykiller(  246): Error writing /proc/5669/oom_score_adj; errno=22
,E/MDM     ( 1733): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/UEI.SmartControl( 5963): File observer start...
E/UEI.SmartControl( 5963): IR Port is disabled: false
D/UEI.SmartControl( 5963): Starting file observer...
D/UEI.SmartControl( 5963): Extracting JNI libs...
D/UEI.SmartControl( 5963): --- this system supports 32-bit or 64-bit only
W/System  ( 5932): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5932): Installed default security provider GmsCore_OpenSSL
W/jxcore-log( 5705): Platform android
W/jxcore-log( 5705): 
,W/jxcore-log( 5705): Process ARCH arm
W/jxcore-log( 5705): 
I/ActivityManager(  940): Process com.android.vending (pid 5669) has died
,D/LocationInitializer( 4333): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 5932): com.google.android.talk: cancel(10436) by com.google.android.talk
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,I/AudioManager( 5217): getMode name:com.lge.qremote
I/AudioManager( 5217): getMode name:com.lge.qremote
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
I/NotificationManager( 5932): com.google.android.talk: cancel(8) by com.google.android.talk
,I/ActivityManager(  940): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5990 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/UEI.SmartControl( 5963): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5963): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5963): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/AppUp4:AppBoxCP( 5990): onCreate
W/AppUp4:DB( 5990):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 5990):  setFingerPrint start
I/AppUp4:DB( 5990):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5990):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5990):  SDK version = 0
I/AppUp4:DB( 5990):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5990): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 5990): onReceive
I/AppUp4:CustModeStarterReceiver( 5990): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
I/UEI.SmartControl( 5963): --- Selecting new region: 2
I/UEI.SmartControl( 5963): -- Running on KitKat(19) and above! JNI will be used.
,D/AppUp4:CustFacade( 5990): Context : android.app.ReceiverRestrictedContext@f5a0110
D/AppUp4:CustFacade( 5990): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5990): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 5990): begin check event
I/AppUp4:CustModeStarterReceiver( 5990): Event For Nothing, skip.
V/AlarmManager(  940): RTC_WAKEUP set : Alarm{2931297e type 0 when 1454412274866 com.google.android.googlequicksearchbox} when 1454412274866
D/UEI.SmartControl( 5963): Platform has CIR...
,D/UEI.SmartControl( 5963): NO CIR support, need to check package...
I/UEI.SmartControl( 5963): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5963): QS Service created
E/UEI.SmartControl( 5963): QS start get config
,I/ActivityManager(  940): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6013 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/UEI.SmartControl( 5963): Loading JNI Libs...
,D/UEI.SmartControl( 5963):  configuring local db...
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 6013): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6013): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6013): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/jxcore-log( 5705): JXcore Cordova bridge is ready!
I/jxcore-log( 5705): 
W/jxcore-log( 5705): JXcore engine is started
,I/AppConfig( 6013): Total System Memory = 906309632
,I/GalleryUtils( 6013): Application Heap = 96 MB
I/AppConfig( 6013): App Tier : NOT_DEF
D/SystemHelper( 6013): region [EU], country [EU], operator [OPEN], sub-operator []
,D/UEI.SmartControl( 5963):  ---- Has DB8: true
,D/UEI.SmartControl( 5963): QS start statue = true Error code = 0
,D/UEI.SmartControl( 5963): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5963): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5963): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5963): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5963): IrrcClient ++ 
D/irrcClient( 5963): getIrrcService ++ 
D/irrcClient( 5963): getIrrcService -- 
D/irrcClient( 5963): IrrcClient -- 
W/irrc_jni( 5963): IRRCPlayer_nativeInit -- 
,I/ActivityManager(  940): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6034 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
D/UEI.SmartControl( 5963): Services init done
I/UEI.SmartControl( 5963): Device manager: loading config....
D/UEI.SmartControl( 5963): QS Service init finished
,D/UEI.SmartControl( 5963): QS Service version name: 0.1.73
D/UEI.SmartControl( 5963): QS Service version code: 1073
D/UEI.SmartControl( 5963): Service requested: Control
D/UEI.SmartControl( 5963): Config is loaded...
I/jxcore-log( 5705): Toggling radios to true
I/jxcore-log( 5705): 
,D/BluetoothAdapter( 5705): enable(): BT is already enabled..!
D/WifiServiceImplEx(  940): setWifiEnabled: true pid=5705, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  940): setWifiEnabled: true pid=5705, uid=10316
D/WifiServiceImplEx(  940): disconnect pid=5705, uid=10316, packageName=com.test.thalitest
D/UEI.SmartControl( 5963): Request IControl service: devices are loaded...
D/WifiServiceImplEx(  940): reconnect pid=5705, uid=10316, packageName=com.test.thalitest
I/jxcore-log( 5705): Radios toggled
I/jxcore-log( 5705): 
D/UEI.SmartControl( 5963):  ----- QS SDK is ready!!!
I/jxcore-log( 5705): My device name is: LGE-LG-D722
I/jxcore-log( 5705): 
,I/UEI.SmartControl( 5963): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5963): Internal service binding...
I/wpa_supplicant( 2765): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
W/ResourcesManager( 6034): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/wpa_supplicant( 2765): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  940): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  940): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
D/WfdsMonitor( 1803): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/UEI.SmartControl( 5963): -----IControl: 11
,W/ResourcesManager( 6034): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6034): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5963): Caller: com.lge.qremote
W/ResourcesManager( 6034): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5963): ------------ IControl registerCallback...
I/UEI.SmartControl( 5963): Registering callback...
W/ResourcesManager( 6034): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5963): -----IControl: 19
D/UEI.SmartControl( 5963): Caller: com.lge.qremote
I/UEI.SmartControl( 5963): Registering Services Ready callback...
I/UEI.SmartControl( 5963): Notify client services are ready...
D/UEI.SmartControl( 5963): -----IControl: 8
,D/LGWifiP2pService(  940): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  940): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/UEI.SmartControl( 5963): Caller: com.lge.qremote
D/DhcpStateMachine(  940): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  280): Clearing all IP addresses on wlan0
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 7
I/ActivityManager(  940): Killing 5314:com.lge.bnr/1000 (adj 15): empty #11
V/NativeCrypto( 1733): Read error: ssl=0xaaf12000: I/O error during system call, Connection timed out
,V/NativeCrypto( 1733): SSL shutdown failed: ssl=0xaaf12000: I/O error during system call, Broken pipe
D/libc-netbsd(  940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  940): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  940): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/ConnectivityService(  940): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,D/libc-netbsd(  940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  940): ValidatedState{ when=-6ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  940): DefaultState{ when=-16ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  940): Forcing reevaluation
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
,W/libprocessgroup(  940): failed to open /acct/uid_1000/pid_5314/cgroup.procs: No such file or directory
,D/WifiHS20(  940): hidePasspointNotification off =false
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  940): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1384): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 12:24:35.615 DNS addrs= 0.0.0.0, 0.0.0.0, 
,I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/DhcpStateMachine(  940): StoppedState
,I/ActivityManager(  940): Process com.google.android.gm (pid 5829) has died
E/WifiStateMachine(  940): Start Disconnecting Watchdog 1
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 12:24:35.675 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiHS20(  940): hidePasspointNotification off =false
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  940): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/LGWifiP2pService(  940): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  940): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2765): wlan0: CTRL-EVENT-SCAN-STARTED 
,D/DhcpStateMachine(  940): StoppedState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  280): Clearing all IP addresses on wlan0
,D/ConnectivityService(  940): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  940): disableDataServiceNotify
D/DSQN    (  940): stop dsqn bin
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  940): hidePasspointNotification off =false
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 12:24:35.706 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  940): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at null
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1384): Remote
I/[SystemUI]StatusBar.NetworkController( 1384): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1384): Remote
D/WifiNetworkAgent(  940): NetworkAgent: NetworkAgent channel lost
I/[SystemUI]StatusBar.NetworkController( 1384): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1384): Remote
I/SystemConfig( 6034): BUILD Country: EU
I/SystemConfig( 6034): BUILD Operator: OPEN
D/ConnectivityService(  940): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  940):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  940):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  940): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  940): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1384): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  940): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  940): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  940): Disconnected - quitting
,D/WifiHS20(  940): hidePasspointNotification off =false
D/CSLegacyTypeTracker(  940): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  940): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  940): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 12:24:35.742 DNS addrs= 0.0.0.0, 0.0.0.0, 
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  940): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1384): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  940): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  940): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  940): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/Tethering(  940): MasterInitialState.processMessage what=3
V/NetworkPolicy(  940): [LG_RESTRICTED] !!!isConnected  type  :1
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 12:24:35.748 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/QCNEJ   ( 1840): |CORE| No family connected
D/ConnectivityService(  940): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
V/NetworkPolicy(  940): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  940): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1840): |CORE| No family connected
I/QCNEJ   ( 1840): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  940): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  940): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1384): Remote
D/WifiServerServiceExt(  940): SUPPLICANT_STATE_CHANGED_ACTION
D/TelephonyNetworkFactory-1( 1743): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiServerServiceExt(  940): setSupplicantStateDISCONNECTED
I/[SystemUI]StatusBar.NetworkController( 1384): mWifiConnected = false, mWifiLevel = 0
D/TelephonyNetworkFactory-1( 1743):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/NetworkManagementService(  940): Removing idletimer
D/WIFI    (  940): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  940):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt(  940): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  940): setSupplicantStateSCANNING
,I/QCNEJ   ( 1840): |CORE| sendDefaultNwMsg: default = -1
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1384): Remote
W/Settings(  940): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/ConnectivityService(  940): EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
D/TelephonyIcons( 1384): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1384): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyIcons( 1384): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1384): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  940): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6061 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6034): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6034): existFile = false
,I/SystemConfig( 6034): canReadFile = false
I/SystemConfig( 6034): systemFeature RCS result false
D/SystemConfig( 6034): refreshRcsSupport() :false
,I/LockScreenSettings( 6061): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6061): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6061): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6061): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6061): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6061): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  940): Killing 5755:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
I/UpdateIcingCorporaServi( 1941): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1941): UpdateCorporaTask done [took 60 ms] updated apps [took 60 ms] 
,I/ActivityManager(  940): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6084 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup(  940): failed to open /acct/uid_10006/pid_5755/cgroup.procs: No such file or directory
,I/ActivityManager(  940): Process com.lge.qremote (pid 5217) has died
,D/Finsky  ( 6084): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6084): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6084): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6084): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6084): com.android.vending: cancel(-1050172287) by com.android.vending
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2765): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/Finsky  ( 6084): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6084): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 6084): Skipping gmscore version check
V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@39c61a3 on behalf of 6084
D/LocSvc_java(  940): onReceive
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 12:24:36.858 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1384): mWifiConnected = false, mWifiLevel = 0
D/WifiOffDelayIfNotUsed(  940): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/PackageBroadcastService( 4333): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/Finsky  ( 6084): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1384): Remote
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2765): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/ActivityManager(  940): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6139 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/PackageBroadcastService( 4333): Null package name or gms related package.  Ignoreing.
,W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  940): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  940): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  940): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  940): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  940): setSupplicantStateASSOCIATED
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  940): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  940): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  940): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  940): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 12:24:36.956 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1384): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 12:24:36.958 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 12:24:36.96 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1384): Remote
I/[SystemUI]StatusBar.NetworkController( 1384): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1384): Remote
I/[SystemUI]StatusBar.NetworkController( 1384): mWifiConnected = false, mWifiLevel = 0
D/Finsky  ( 6084): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/Icing   ( 4333): updateResources: need to parse f{com.google.android.gms}
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1384): Remote
,W/ResourcesManager( 6139): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/wpa_supplicant( 2765): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2765): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 4
,D/WifiServerServiceExt(  940): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  940): setSupplicantStateGROUP_HANDSHAKE
I/WifiServiceExtension(  940): setVHTCapabilityType  : false
D/BluetoothManagerService(  940): Message: 20
,I/WifiServerServiceExt(  940): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  940): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  940): setSecurityType  : 2
,D/BluetoothAdapterService(549885210)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ab7ce40
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 12:24:37.123 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  940): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  940): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1384): mWifiConnected = false, mWifiLevel = 0
D/BluetoothAdapterService(549885210)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ab7ce40
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 12:24:37.127 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1384): Remote
I/[SystemUI]StatusBar.NetworkController( 1384): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1384): Remote
,D/ConnectivityService(  940): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  940): Got NetworkAgent Messenger
D/ConnectivityService(  940): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  940): NetworkAgent connected
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
E/WifiConfigStore(  940): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  940): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  280): Setting iface cfg
E/WifiStateMachine(  940): Start Dhcp Watchdog 2
D/DhcpStateMachine(  940): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  940): WaitBeforeStartState
,V/AlarmManager(  940): ELAPSED_WAKEUP set : Alarm{3844a024 type 2 when 90456 com.google.android.gms} when 90456
D/ConnectivityService(  940): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
V/LGMDMManager( 6139): Create singleton instance
,E/WifiStateMachine(  940): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  940): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  940): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@119eeec9 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  940): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@119eeec9 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  940): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,V/LgDhcpStateMachineHelper(  940): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  940): DHCP Start wake lock is acquired.
D/CommandListener(  280): Setting iface cfg
I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  280): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  940): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  940): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  940): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  940): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  940): setSupplicantStateCOMPLETED
,I/AudioManager( 6139): getMode name:com.lge.qremote
,D/ConnectivityService(  940): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  940): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  940): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/art     (  940): Explicit concurrent mark sweep GC freed 50347(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.482ms total 210.604ms
D/BluetoothManagerService(  940): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a3b1b8e:true
,D/ConnectivityService(  940): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  940): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  940): ignoring duplicate network state non-change
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  940): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1384): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 12:24:37.312 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1384): Remote
D/ConnectivityService(  940): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/[SystemUI]StatusBar.NetworkController( 1384): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  940): Adding iface wlan0 to network 101
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 12:24:37.32 DNS addrs= 192.168.1.1, 0.0.0.0, 
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  940): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1384): Remote
E/WifiStateMachine(  940): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,D/WifiHS20(  940): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1384): mWifiConnected = true, mWifiLevel = 2
E/ConnectivityService(  940): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  940): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 12:24:37.344 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService(  940): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  940): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  940): [PASSPOINT] passpointNotification: hs20AP list is checked
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
,D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
E/Netd    (  280): netlink response contains error (File exists)
D/ConnectivityService(  940): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  940): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  940): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  940): Setting Dns servers for network 101 to [/192.168.1.1]
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1384): Remote
D/libc-netbsd(  940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 12:24:37.352 DNS addrs= 192.168.1.1, 0.0.0.0, 
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  940): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  940): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  940): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  940): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  940): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  940):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  940):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  940):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  940): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  940):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  940):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  940): Connected
D/ConnectivityService(  940): currentScore = 0, newScore = 20
D/ConnectivityService(  940):    accepting network in place of null
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  940): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  940): sending new Min Network Score(20): NetworkRequest, [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/WIFI    (  940): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  940):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1743): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  940): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  940): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/TelephonyNetworkFactory-1( 1743):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  940): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  940): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  940): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  940): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
D/UEI.SmartControl( 5963): -----IControl: 11
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  940): [LWD] Start DNSResolver start to wait
,D/ConnectivityService(  940): validation of new default Network = false
D/ConnectivityService(  940): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  940): enableDataServiceNotify 
D/DSQN    (  940): start dsqn bin
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/UEI.SmartControl( 5963): Caller: com.lge.qremote
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/UEI.SmartControl( 5963): ------------ IControl registerCallback...
I/UEI.SmartControl( 5963): Registering callback...
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  940): [LWD] wait 500ms before dns check
D/Tethering(  940): MasterInitialState.processMessage what=3
I/[SystemUI]StatusBar.NetworkController( 1384): mWifiConnected = true, mWifiLevel = 2
,W/QCNEJ   ( 1840): |CORE| No family connected
I/QCNEJ   ( 1840): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1840): |CORE| sendDefaultNwMsg: default = 1
D/UEI.SmartControl( 5963): -----IControl: 19
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1384): Remote
D/UEI.SmartControl( 5963): Caller: com.lge.qremote
I/UEI.SmartControl( 5963): Registering Services Ready callback...
I/UEI.SmartControl( 5963): Notify client services are ready...
D/UEI.SmartControl( 5963): -----IControl: 8
D/UEI.SmartControl( 5963): Caller: com.lge.qremote
,D/ConnectivityService(  940): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  940):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  940):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  940): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1384): CM callback handler got msg 524290
I/DSQN    ( 6170): DSQN samuel.seo ver 141203
E/DSQN    ( 6170): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6170): created command queue thread
I/DSQN    ( 6170): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6170): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,V/NetworkPolicy(  940): [LG_RESTRICTED] checkMobilePolicy_type()
D/TelephonyIcons( 1384): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1384): updateLGTelephonySignalStrength : !hasService()
V/SetupWizard( 5887): Connected to Gservices successfully
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/ActivityManager(  940): Killing 5904:com.android.providers.calendar/u0a14 (adj 15): empty #11
D/DhcpStateMachine(  940): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  940): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  940): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6174): version 5.5.6 starting
E/dhcpcd  ( 6174): get_duid: Read-only file system
,W/libprocessgroup(  940): failed to open /acct/uid_10014/pid_5904/cgroup.procs: No such file or directory
,I/dhcpcd  ( 6174): wlan0: rebinding lease of 192.168.1.134
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
E/MDM     ( 1733): [122] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 4333): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  940): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6187 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1733): No location to return for getLastLocation()
,W/FusedLocationProvider( 1733): location=null
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out( 1733): propertyValue:false
W/ActivityManager(  940): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  940): [LWD] DNSResolver start dns
D/libc-netbsd(  940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 6170): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6170): restart monitoring
D/libc-netbsd(  940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/LGDataListener(  280): argv[0]=dsqncommand
D/LGDataListener(  280): argv[1]=wlan0
D/LGDataListener(  280): argv[2]=1
D/LGDataListener(  280): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 6170): dsqn report finish
D/DSQN    (  940): DSQM DsqnNotification wlan0  1
D/DSQN    (  940): start to monitor internet connection
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out(  940): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  940): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  940): Checking http://clients3.google.com/generate_204 on "NG700"
V/AlarmManager(  940): ELAPSED_WAKEUP set : Alarm{1bce17cb type 2 when 91191 com.android.providers.calendar} when 91191
D/libc-netbsd(  940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  940): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 11:24:37 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454412277958], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454412277943]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  940): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  940): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  940): Validated
D/ConnectivityService(  940): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  940): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  940):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  940):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  940):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  940): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/WifiDataContinuityService(  940): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  940): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  940):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  940):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  940): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  940): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  940): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
I/WifiServerServiceExt(  940): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyNetworkFactory-1( 1743): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  940): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  940):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1743):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityManager.CallbackHandler( 1384): CM callback handler got msg 524290
D/TelephonyIcons( 1384): null signal icon name: drawable/stat_sys_signal_null
,I/Gmail   ( 6187): getAccountsCursor
I/[SystemUI]LGNetworkController( 1384): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 6187): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  940): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  940): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 6187): Observing account changes for notifications
,W/ActivityManager(  940): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 6187): Error finding the version of the Email provider.....
E/Gmail   ( 6187): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6187): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6187): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6187): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6187): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6187): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6187): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6187): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 6187): We do not support migrating this version of the Email provider.
I/Gmail   ( 6187): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  940): Killing 5990:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/Icing   ( 4333): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
W/libprocessgroup(  940): failed to open /acct/uid_10011/pid_5990/cgroup.procs: No such file or directory
,I/Icing   ( 4333): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/ConnectivityService(  940): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/Gmail   ( 6187): notifyAccountChanged
,I/Gmail   ( 6187): getAccountsCursor
I/Gmail   ( 6187): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6187): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager(  940): Process com.android.contacts (pid 6034) has died
I/Gmail   ( 6187): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6187): calculateUnknownSyncRationalesAndPurgeInBackground: running
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  940): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6234 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 311us total 23.164ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 22.607ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 311us total 22.986ms
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6234): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Gmail   ( 6187): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CalendarApplication( 6234): CalendarApplication.onCreate()
,D/ConnectivityService(  940): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/ConnectivityService(  940): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  940): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  940): onReceive
D/LocSvc_java(  940): got connectivity action
,D/GpsLocationProvider(  940): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  940): broadcast - no network connections
D/LocSvc_java(  940): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  940): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  940): onReceive
D/LocSvc_java(  940): got connectivity action
D/LocSvc_java(  940): broadcast - no network connections
D/LocSvc_java(  940): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  940): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  940): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  940): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  940): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  940): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  940): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  940): ignore wifi update if we are not in OPENING or CLOSING
D/PreferenceKeysParser( 6234): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6234): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@e83c1d3, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@f5a0110, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@18058409, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@108a260e, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1f3ea82f, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@28461e3c, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@217957c5, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@20c6951a, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2217984b, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@974e228, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@369cab41, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3228e8e6, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@1a456e27, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@3049f8d4, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@2147ba7d, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@aad72, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1d90c5c3, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2ab7ce40, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@369a8179, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2fd22ebe, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@baffb1f, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@316b8e6c, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@23b8bc35, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@4fe78ca, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@1f632a3b, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@38b92558, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.Pre,ferenceKey$KeyData@a45e6b1, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@9f35796, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@35502f17, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@24473f04, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@28a13ced, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@39855722, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@249ea5b3, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@97b4770, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@9e1bae9, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3545c36e, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@553ea0f, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2ca56a9c, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@39921ca5, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@148ea87a, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@6f182b, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@24ec9488, lg_
D/GpsLocationProvider(  940): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  940): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GeneralPreferenceUtils( 6234): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6234): [init]
,I/Config  ( 6234): LGCalendar ver.4.40.17
I/Config  ( 6234): start check model
I/Config  ( 6234): start check native_ca
I/Config  ( 6234): Config Operator=OPEN, Country=EU
D/Config  ( 6234): [setDefaultValuesToPref]
D/Config  ( 6234): [parseProfiles]
D/ProfilesParser( 6234): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6234): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6234): [updateProfiletoCountryInfo]
D/GeneralPreference( 6234): [checkAndMigrateOldPreference]
D/AlertReceiver( 6234): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6234): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6234): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 6234): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6234): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6234): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6234): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6234): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6234): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6234): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6234): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6234): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6234): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6234): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 6234): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6234): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6234): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6234): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 6234): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
,I/AlertUtils( 6234): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/[SystemUI]QPairHandler( 1384): onReceive = android.intent.action.PACKAGE_CHANGED
I/AlertUtils( 6234): set default noti to content://media/internal/audio/media/38
I/[SystemUI]QSlideListController( 1384): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/InitNotificationRingtoneService( 6234): End InitializeAlertRingtoneService.onHandleIntent
I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/InputReader(  940): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
W/[SystemUI]QSlideLoader( 1384): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1384): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1384): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1384): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1384): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1384): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1384): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1384): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1384): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1384): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1384): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1384): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1384): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
D/administrator(  940): Handling package changes for user 0
,I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/HolidayIntentService( 6234): onHandleIntent
,I/Netd    (  280): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  940): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  940): identical MTU - not setting
I/dhcpcd  ( 6174): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
D/Nat464Xlat(  940): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  940): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  940):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  940):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-66 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 12:24:39.043 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  940): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  940): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  940): enableDataServiceNotify 
D/DSQN    (  940): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1384): CM callback handler got msg 524295
D/HolidayDataLoader( 6234): readJsonAsset : holiday.json
I/dhcpcd  ( 6174): wlan0: leased 192.168.1.134 for 86400 seconds
D/DSQN    (  940): dsqn is running restart
,I/DSQN    ( 6261): DSQN samuel.seo ver 141203
,E/DSQN    ( 6261): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6261): created command queue thread
I/DSQN    ( 6261): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6261): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/AlertService( 6234): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6234): [updateWidgets] 
,D/MonthWidgetProvider( 6234): [onReceive]
D/CalendarWidgetProvider( 6234): [onReceive]
D/CalendarWidgetProvider( 6234): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6234): [onCreate] mContext.getPackageName() = com.android.calendar
,I/ActivityManager(  940): Process com.android.gallery3d (pid 6013) has died
,D/WeekWidgetProvider( 6234): [onReceive]
D/CalendarWidgetProvider( 6234): [onReceive]
D/CalendarWidgetProvider( 6234): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6234): [onCreate] mContext.getPackageName() = com.android.calendar
E/lowmemorykiller(  246): Error writing /proc/5582/oom_score_adj; errno=22
I/AudioManager( 6139): getMode name:com.lge.qremote
E/HolidayIntentService( 6234): onHandleIntent:holiday data empty
,I/ActivityManager(  940): Process com.google.android.apps.plus (pid 5582) has died
,D/UEI.SmartControl( 5963): Service.onTrimMemory: 10
I/BackgroundMemoryTrimmer( 1941): Trimming objects from memory, since app is in the background.
,E/UEI.SmartControl( 5963): Setup service releasing memory...
,I/PhoneApp( 1743): onTrimMemory: 10
,I/PhoneApp( 1743): trim memory
,I/ActivityManager(  940): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6283 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/NotificationService(  940): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  940): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  940): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/art     ( 5963): Explicit concurrent mark sweep GC freed 11056(772KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 7MB/9MB, paused 370us total 114.988ms
,I/art     ( 5963): WaitForGcToComplete blocked for 44.885ms for cause HomogeneousSpaceCompact
W/ResourcesManager(  940): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/libc-netbsd(  940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/DhcpStateMachine(  940): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  940): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  940): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  940): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  940): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  940): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  940): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  940): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  940): RunningState
I/ActivityManager(  940): Process com.lge.lockscreensettings (pid 6061) has died
,E/lowmemorykiller(  246): Error opening /proc/6187/oom_score_adj; errno=2
I/BackupManagerService(  940): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/ActivityManager(  940): Process com.google.android.gm (pid 6187) has died
,I/BackgroundMemoryTrimmer( 1941): Trimming objects from memory, since app is in the background.
D/UEI.SmartControl( 5963): Service.onTrimMemory: 80
E/UEI.SmartControl( 5963): Setup service releasing memory...
I/PhoneApp( 1743): onTrimMemory: 10
I/PhoneApp( 1743): trim memory
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
V/BackupManagerService(  940): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  940): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@184c41a4
W/ResourceType(  940): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/ResourcesManager( 6283): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6283): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6283): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6283): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6283): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/ActivityManager(  940): Process com.google.android.talk (pid 5932) has died
I/BackgroundMemoryTrimmer( 1941): Trimming objects from memory, since app is in the background.
,D/UEI.SmartControl( 5963): Service.onTrimMemory: 80
E/UEI.SmartControl( 5963): Setup service releasing memory...
I/PhoneApp( 1743): onTrimMemory: 10
I/PhoneApp( 1743): trim memory
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/IndexDatabaseHelper( 6283): Using schema version: 115
,I/IndexDatabaseHelper( 6283): Index is fine
D/UEI.SmartControl( 5963): Service.onTrimMemory: 80
E/UEI.SmartControl( 5963): Setup service releasing memory...
,D/LocationProviderProxy(  940): applying state to connected service
,I/art     (  940): Explicit concurrent mark sweep GC freed 53505(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.499ms total 178.875ms
,I/ThermalEngine(  299): Sensor:pa_therm0:32000 mC
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-62 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 12:24:40.203 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/WiFiOffLoadBroadcast( 6283): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6283): MCCMNC not supported: null
D/UEI.SmartControl( 5963): Internal timer expired: 1
,V/WifiInternetCheck(  940): Single check msg out of sync, ignoring.
,I/ActivityManager(  940): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6307 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/ConnectivityService(  940): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  940): Process com.android.vending (pid 6084) has died
,D/UEI.SmartControl( 5963): Service.onTrimMemory: 60
E/UEI.SmartControl( 5963): Setup service releasing memory...
I/PhoneApp( 1743): onTrimMemory: 10
I/PhoneApp( 1743): trim memory
D/GpsLocationProvider(  940): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1384): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  940): onReceive
D/LocSvc_java(  940): got connectivity action
D/LocSvc_java(  940): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  940): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  940): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  940): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  940): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  940): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/PCSuite ( 6307): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6307): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6307): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  940): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6330 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6330): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6330): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6330): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6330): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6330): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6330): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6330): MmsConfig.loadFromResources
,E/Babel_SMS( 6330): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6330): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6330): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6330): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6330): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6330): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6330): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6330): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6330): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6330): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6330): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6330): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6330): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6330): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6330): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6330): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6330): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6330): found sensor: Motion Accel, handle=46
,W/Settings( 6330): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6330): startup - clean
I/art     ( 6330): CheckpointMarkThreadRoots callback created = 0xb042d550
,I/Babel   ( 6330): deleted: false for 0
,I/art     ( 6330): CheckpointMarkThreadRoots callback created = 0xb042d530
,V/WiFiOffLoadBroadcast( 6283): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6283): MCCMNC not supported: null
I/PCSuite ( 6307): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6307): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6307): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6330): Unsupported mime audio/x-lg-flac
V/WiFiOffLoadBroadcast( 6283): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/AudioCapabilities( 6330): Unsupported mime audio/adpcm
W/AudioCapabilities( 6330): Unsupported mime audio/g726
D/WiFiOffLoadBroadcast( 6283): MCCMNC not supported: null
W/AudioCapabilities( 6330): Unsupported mime audio/x-ms-wma
I/PCSuite ( 6307): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6307): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6307): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/AudioCapabilities( 6330): Unsupported mime audio/wma-voice
V/WiFiOffLoadBroadcast( 6283): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/VideoCapabilities( 6330): Unsupported mime video/mjpg
D/WiFiOffLoadBroadcast( 6283): MCCMNC not supported: null
I/PCSuite ( 6307): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6307): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6307): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/VideoCapabilities( 6330): Unsupported mime video/theora
V/WiFiOffLoadBroadcast( 6283): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6283): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6283): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6283): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6283): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6283): MCCMNC not supported: null
W/AudioCapabilities( 6330): Unsupported mime audio/evrc
,V/WiFiOffLoadBroadcast( 6283): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/AudioCapabilities( 6330): Unsupported mime audio/qcelp
W/VideoCapabilities( 6330): Unrecognized profile 2130706433 for video/avc
D/WiFiOffLoadBroadcast( 6283): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6283): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
W/AudioCapabilities( 6330): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6330): Unsupported mime audio/qcelp
W/AudioCapabilities( 6330): Unsupported mime audio/evrc
D/WiFiOffLoadBroadcast( 6283): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6283): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6283): MCCMNC not supported: null
W/VideoCapabilities( 6330): Unsupported mime video/mp4v-esdp
,V/WiFiOffLoadBroadcast( 6283): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6283): MCCMNC not supported: null
I/VideoCapabilities( 6330): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6330): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6330): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6330): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  940): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=6364 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  940): RTC_WAKEUP set : Alarm{3c649a70 type 0 when 1454412281348 com.android.vending} when 1454412281348
W/VideoCapabilities( 6330): Unrecognized profile 2130706433 for video/avc
,V/WiFiOffLoadBroadcast( 6283): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/vclib   ( 6330): onServiceConnected
D/WiFiOffLoadBroadcast( 6283): MCCMNC not supported: null
W/Babel   ( 6330): Attempted to change video mute state without an active call.
,I/NotificationManager( 6330): com.google.android.talk: cancel(10436) by com.google.android.talk
V/WiFiOffLoadBroadcast( 6283): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6283): MCCMNC not supported: null
D/libc-netbsd(  940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/WiFiOffLoadBroadcast( 6283): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6283): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6283): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6283): MCCMNC not supported: null
I/PCSuite ( 6307): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6307): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6283): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6283): MCCMNC not supported: null
,I/PCSuite ( 6307): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6307): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
I/AudioManager( 6139): getMode name:com.lge.qremote
,I/AudioManager( 6139): getMode name:com.lge.qremote
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,I/System.out(  940): propertyValue:false
D/libc-netbsd(  940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  940): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  940): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  280): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  280): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out(  940): propertyValue:false
I/ActivityManager(  940): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6392 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DSQN    ( 6261): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6261): restart monitoring
I/DSQN    ( 6261): dsqn report finish
D/LGDataListener(  280): argv[0]=dsqncommand
D/LGDataListener(  280): argv[1]=wlan0
D/LGDataListener(  280): argv[2]=1
D/LGDataListener(  280): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  940): DSQM DsqnNotification wlan0  1
D/DSQN    (  940): start to monitor internet connection
D/Finsky  ( 6364): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,V/WifiInternetCheck(  940): isHttpConnectionAvailable - We got a valid response : 204
,W/ActivityManager(  940): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/Finsky  ( 6364): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 6364): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6364): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6364): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Finsky  ( 6364): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/Gmail   ( 6392): getAccountsCursor
,D/Finsky  ( 6364): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6364): [1] Libraries$2.run: Finished loading 1 libraries.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Ads     ( 6364): Skipping gmscore version check
V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@16676ca0 on behalf of 6364
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 6392): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/Finsky  ( 6364): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6364): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/NotificationManager(  940): android: cancelAsUser(2) by android
,I/ActivityManager(  940): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6445 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  940): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  940): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  940): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6392): Observing account changes for notifications
,E/Gmail   ( 6392): Error finding the version of the Email provider.....
E/Gmail   ( 6392): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6392): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6392): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6392): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6392): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6392): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6392): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6392): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6392): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6392): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 6445): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/libc-netbsd( 6364): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6364): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6364): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6364): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  280): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 95601316687; DSPS: 3231281; Offset : -3014704949
D/CalendarProvider2( 6445): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@22b4b40d
,D/CalendarProvider2( 6445): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6445): Created com.android.providers.calendar.CalendarAlarmManager@108a260e(com.android.providers.calendar.CalendarProvider2@22b4b40d)
D/CalendarProviderBroadcastReceiver( 6445): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6445): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6445): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6445): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6445): [getOrCreateCalendarAlarmManager]
D/CalendarProvider2( 6445): [IntentService] Release Lock
,D/CalendarProvider2( 6445): CalendarProviderIntentService.onDestroy()
I/Gmail   ( 6392): notifyAccountChanged
I/Gmail   ( 6392): getAccountsCursor
I/Gmail   ( 6392): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6392): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6392): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 6364): propertyValue:false
D/libc-netbsd( 6364): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6364): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Gmail   ( 6392): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager(  940): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6478 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 6392): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MusicStore( 6478): Database version: 120
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6478): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6478): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6478): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6478): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6478): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6478): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6478): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6478): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16eb09fb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6478): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6478): GMSCore installation verified
I/ConfigStore( 6478): Config Database version: 1
,D/libc-netbsd( 6364): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6364): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     (  940): Explicit concurrent mark sweep GC freed 28469(1391KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.271ms total 157.064ms
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  940): android: cancelAsUser(2) by android
,I/MediaRouter( 6478): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/MusicLeanback( 6478): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 6478): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6478): type=WIFI subType= reason=null isConnected=true
,I/qtaguid ( 6364): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6364): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6364): untagSocket(41) failed with errno -22
D/Finsky  ( 6364): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
I/ActivityManager(  940): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6515 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6478): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6478): Using platform SSLCertificateSocketFactory
I/ActivityManager(  940): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6534 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,E/lowmemorykiller(  246): Error opening /proc/6283/oom_score_adj; errno=2
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  940): Process com.android.settings (pid 6283) has died
,W/ResourcesManager( 6515): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6515): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6515): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/NotificationManager(  940): android: cancelAsUser(2) by android
,W/ResourcesManager( 6534): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6534): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/NotificationManager( 6478): com.google.android.music: cancel(1061) by com.google.android.music
I/MultiDex( 6534): VM with version 2.1.0 has multidex support
I/MultiDex( 6534): install
,I/MultiDex( 6534): VM has multidex support, MultiDex support library is disabled.
,I/qtaguid ( 6364): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6364): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6364): untagSocket(41) failed with errno -22
I/ActivityManager(  940): Process com.lge.qremote (pid 6139) has died
,D/UEI.SmartControl( 5963): Service.onUnbind: IControl
D/UEI.SmartControl( 5963): Service.onDestroy
D/UEI.SmartControl( 5963): Shutdown IRRCPlayer... 
D/AlertService( 6234): Beginning updateAlertNotification
,W/irrc_jni( 5963): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5963): ~IrrcClient ++ 
D/irrcClient( 5963): ~IrrcClient -- 
W/irrc_jni( 5963): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5963): Blaster closed
D/UEI.SmartControl( 5963): Blaster closed
D/UEI.SmartControl( 5963): Shut down QS...
D/UEI.SmartControl( 5963): Stopped file observer...
I/LGEmail ( 6515): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/UEI.SmartControl( 5963): QS lib stop result = true
,D/UEI.SmartControl( 5963): QS shutdown complete
V/JNIHelp ( 6534): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/LGEmail ( 6515): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/AlertService( 6234): No fired or scheduled alerts
,I/NotificationManager( 6234): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6234): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6234): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6234): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6234): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6234): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6234): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6234): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6234): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6234): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6234): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6234): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6234): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6234): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6234): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6234): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6234): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6234): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6234): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6234): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6234): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6234): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,W/ActivityThread( 6534): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6534): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16676ca0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6534): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6534): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6534): com.google.android.gms: cancel(39789) by com.google.android.gms
D/AlarmScheduler( 6234): No events found starting within 1 week.
I/art     ( 6364): CheckpointMarkThreadRoots callback created = 0xb0583420
I/art     ( 6364): CheckpointMarkThreadRoots callback created = 0xb05833e0
D/ChimeraCfgMgr( 6534): Reading stored module config
,D/ChimeraCfgMgr( 6534): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/ActivityManager(  940): Process com.android.calendar (pid 6234) has died
,D/NativeLibraryUtils( 6534): Install completed successfully. count=14 extracted=0
,D/eas_req ( 6515): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/jxcore-log( 5705): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5705): 
,I/ActivityManager(  940): Process com.lge.sync (pid 6307) has died
,D/CAR.SERVICE( 6534): Connecting to CarCallService...
,I/art     ( 6534): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6534): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  940): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6563 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/CAR.SERVICE( 6534): com.google.android.projection.gearhead isn't installed.
,I/ActivityManager(  940): Process com.google.android.setupwizard (pid 5887) has died
,I/HubEmail( 6515): JNI_OnLoad()
I/HubEmail( 6515): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6515): registerNatives()
I/HubEmail( 6515): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6515): registerNativeMethods()
I/HubEmail( 6515): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6515): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
D/CAR.TEL.Service( 6534): Creating a new CarCallService.
,W/Settings( 6515): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/CAR.TEL.PhoneAdapter( 6534): Creating a new PhoneAdapter instance
,W/ActivityManager(  940): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6534): setListener: com.google.android.gms.car.dn@156f9bef
W/ActivityManager(  940): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6534): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6534): Starting CarCallService with initial phone null
I/NotificationManager( 6534): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/LGDMClient( 6563): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6563): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6563): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6563): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/ActivityManager(  940): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6586 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/CAR.SERVICE( 6534): Package validated; name: com.android.vending
D/LGDMClient( 6563): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6563): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 23.158ms
D/LGDMClient( 6563): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 20.871ms
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 24.878ms
,I/LGDMClient( 6563): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ThermalEngine(  299): Sensor:pa_therm0:32000 mC
I/ActivityManager(  940): Process com.uei.lg.quicksetsdk.lite (pid 5963) has died
,W/ContextImpl( 6563): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6563): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6563): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 6563): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6563): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6563): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,V/AlarmManager(  940): RTC_WAKEUP set : Alarm{2afa6976 type 0 when 1454412285178 com.android.vending} when 1454412285178
I/NotificationManager( 6364): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6364): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/AppUp4:AppBoxCP( 6586): onCreate
,W/AppUp4:DB( 6586):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6586):  setFingerPrint start
I/AppUp4:DB( 6586):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6586):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6586):  SDK version = 0
I/AppUp4:DB( 6586):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6586): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6586): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6586): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6586): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6586): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6586): onReceive
I/AppUp4:CustModeStarterReceiver( 6586): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6586): Context : android.app.ReceiverRestrictedContext@1f3ea82f
D/AppUp4:CustFacade( 6586): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6586): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6586): begin check event
I/AppUp4:CustModeStarterReceiver( 6586): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 6586): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6586): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6586): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6586): handleAsyncCustNotification do not startCustService
I/LgeMiscReceiver( 3170): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3170): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3170): networkInfo.isConnected() = false
I/ActivityManager(  940): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6612 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/Finsky  ( 6364): [755] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6364): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/PhoneMonitor( 6612): Register our PhoneStateListener
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  940): android: cancelAsUser(2) by android
,D/MobileConnectivityChangeReceiver( 6612): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6612): onReceive CONNECTIVITY_CHANGE networkType=1
V/AlarmManager(  940): RTC_WAKEUP set : Alarm{1775a381 type 0 when 1454412285602 com.google.android.googlequicksearchbox} when 1454412285602
,V/DownloadManager( 3216): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/CheckinService( 4333): Checkin interval check for package: unspecified last checkin: 1454412268851 min interval config: 0 actual interval: 16775
V/DownloadManager( 3216): DownloadService onCreate
I/DownloadManager( 3216): in removeSpuriousFiles
V/DownloadManager( 3216): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@30e23059 on behalf of 3216
D/PhoneMonitor( 6612): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,I/DownloadManager( 3216): in trimDatabase
V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@38dfe41e on behalf of 3216
I/NotificationManager( 3216): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/TelephonyAutoProfiling( 6612): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6612): [parse] Load xml
V/TelephonyAutoProfiling( 6612): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6612): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6612): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  940): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6636 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,I/ActivityManager(  940): Process com.google.android.talk (pid 6330) has died
V/DownloadManager( 3216): DownloadService onStartCommand
I/CheckinService( 4333): Checking schedule, now: 1454412285783 next: 1454412298809
I/CheckinService( 4333): active receiver: disabled
V/DownloadManager( 3216): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@2b7c7915 on behalf of 3216
,V/DownloadManager( 3216): DownloadService onDestroy
,D/WeatherAncestor( 2743): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:24:45
D/UpdateThreadPoolManager( 2743): 2 : This is isUpdating : false
D/WeatherAncestor( 2743): connectivity changed - connection : true
D/Weather_cast( 2743): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2743): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:24:45
D/WeatherService( 2743): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/jxcore-log( 5705): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5705): 
,I/qtaguid ( 6364): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6364): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6364): untagSocket(41) failed with errno -22
I/ActivityManager(  940): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6657 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  940): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2743): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2743): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2743): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/jxcore-log( 5705): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5705): 
I/jxcore-log( 5705): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 5705): 
I/jxcore-log( 5705): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5705): 
,W/ResourcesManager( 6657): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6364): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6364): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6364): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 6657): CheckpointMarkThreadRoots callback created = 0xb042d380
,I/ActivityManager(  940): Process com.google.android.music:main (pid 6478) has died
D/Finsky  ( 6364): [1] DailyHygiene.access$600: Logging device features
,I/art     ( 6657): CheckpointMarkThreadRoots callback created = 0xb042d350
V/AlarmManager(  940): RTC_WAKEUP set : Alarm{108c4075 type 0 when 1454412286433 com.android.vending} when 1454412286433
I/Babel_SMS( 6657): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6657): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6657): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6657): MmsConfig.loadFromDatabase
D/DeviceConnectionService( 1733): client connected with version: 8296000
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
,E/Babel_SMS( 6657): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6657): MmsConfig.loadFromResources
E/Babel_SMS( 6657): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6657): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6657): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6657): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6657): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6657): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6657): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6657): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6657): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6657): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6657): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6657): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6657): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6657): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6657): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6657): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6657): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6657): found sensor: Motion Accel, handle=46
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/Settings( 6657): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6657): startup - clean
,I/Babel   ( 6657): deleted: false for 0
,D/Finsky  ( 6364): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6364): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  940): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6685 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  940): Killing 6445:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  940): failed to open /acct/uid_10014/pid_6445/cgroup.procs: No such file or directory
,W/AudioCapabilities( 6657): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6657): Unsupported mime audio/adpcm
W/AudioCapabilities( 6657): Unsupported mime audio/g726
W/AudioCapabilities( 6657): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6657): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6657): Unsupported mime video/mjpg
W/VideoCapabilities( 6657): Unsupported mime video/theora
W/AudioCapabilities( 6657): Unsupported mime audio/evrc
,W/AudioCapabilities( 6657): Unsupported mime audio/qcelp
W/VideoCapabilities( 6657): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6657): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6657): Unsupported mime audio/qcelp
W/AudioCapabilities( 6657): Unsupported mime audio/evrc
W/VideoCapabilities( 6657): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6657): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6657): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6657): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6657): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6657): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6657): onServiceConnected
,W/Babel   ( 6657): Attempted to change video mute state without an active call.
I/NotificationManager( 6657): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6657): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6657): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6657): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6657): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  280): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 6657): propertyValue:false
I/Babel   ( 6657): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  940): Killing 6392:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  940): failed to open /acct/uid_10053/pid_6392/cgroup.procs: No such file or directory
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6685): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6685): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6685): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6685): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6685): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6685):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6685):   adb logcat -s GAv4
,W/GAv4    ( 6685): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6685): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6685): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6685): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6685): Time to load native libraries: 1 ms (timestamps 825-826)
I/LibraryLoader( 6685): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6685): Binding Chromium to main looper Looper (main, tid 1) {32ff3dd0}
,I/LibraryLoader( 6685): Expected native library version number "",actual native library version number ""
I/chromium( 6685): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6685): Initializing chromium process, singleProcess=true
,W/art     ( 6685): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6685): ApplicationContext is null in ApplicationStatus
W/chromium( 6685): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6685): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6685): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/ActivityManager(  940): Process com.lge.email (pid 6515) has died
,I/Adreno-EGL( 6685): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6685): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6685): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6685): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6685): Remote Branch: 
I/Adreno-EGL( 6685): Local Patches: 
I/Adreno-EGL( 6685): Reconstruct Branch: 
,I/NSApplication( 6685): Starting up...
,V/AudioPolicyService(  287): registerClient() client 0xb551ccc0, uid 10079
W/AudioManagerAndroid( 6685): Requires BLUETOOTH permission
I/ActivityManager(  940): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6752 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  940): Explicit concurrent mark sweep GC freed 18654(842KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.421ms total 142.216ms
,I/ActivityManager(  940): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6775 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  940): Killing 6563:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  940): failed to open /acct/uid_1000/pid_6563/cgroup.procs: No such file or directory
,W/ResourcesManager( 6775): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  940): Killing 6586:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  940): failed to open /acct/uid_10011/pid_6586/cgroup.procs: No such file or directory
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  940): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
D/charger_monitor(  492): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
,I/ActivityManager(  940): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6809 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  940): battery changed pluggedType: 2
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,I/MusicStore( 6809): Database version: 120
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6809): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6809): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6809): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6809): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6809): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6809): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/rmt_storage(  278): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  278): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  278): wakelock acquired: 1, error no: 42
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
W/ActivityThread( 6809): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6809): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16eb09fb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6809): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6809): GMSCore installation verified
,I/ConfigStore( 6809): Config Database version: 1
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
,I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  278): 
I/rmt_storage(  278): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,I/MediaRouter( 6809): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6809): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6809): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6809): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  940): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6837 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6809): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6809): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  940): Killing 6612:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/ResourcesManager( 6837): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6837): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ThermalEngine(  299): Sensor:pa_therm0:32000 mC
W/libprocessgroup(  940): failed to open /acct/uid_10038/pid_6612/cgroup.procs: No such file or directory
,I/NotificationManager( 6809): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6837): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6837): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/CAR.SERVICE( 6534): mConnectedToCar = false, abort
,E/ActivityThread( 6534): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@386304f7 that was originally bound here
E/ActivityThread( 6534): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@386304f7 that was originally bound here
E/ActivityThread( 6534): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6534): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6534): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6534): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6534): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6534): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6534): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6534): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6534): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6534): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6534): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6534): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6534): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6534): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6534): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6534): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6534): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6534): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6534): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6534): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6534): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6534): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6534): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6534): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@75b90ce that was originally bound here
E/ActivityThread( 6534): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@75b90ce that was originally bound here
E/ActivityThread( 6534): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6534): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6534): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6534): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6534): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6534): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6534): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6534): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6534): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6534): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6534): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6534): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6534): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6534): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6534): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6534): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6534): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6534): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6534): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6534): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6534): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6534): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  940): Unbind failed: could not find connection for android.os.BinderProxy@22b1401b
,D/eas_req ( 6837): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  940): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6863 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6837): JNI_OnLoad()
I/HubEmail( 6837): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6837): registerNatives()
I/HubEmail( 6837): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6837): registerNativeMethods()
I/HubEmail( 6837): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6837): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  940): Killing 6636:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  940): failed to open /acct/uid_10051/pid_6636/cgroup.procs: No such file or directory
W/Settings( 6837): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 6863): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6863): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6863): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6863): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6863): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6863): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/ActivityManager(  940): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6881 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/LGDMClient( 6863): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6863): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  940): Process com.android.vending (pid 6364) has died
W/ContextImpl( 6863): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6863): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6863): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6863): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6863): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6863): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/AppUp4:AppBoxCP( 6881): onCreate
,W/AppUp4:DB( 6881):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6881):  setFingerPrint start
I/AppUp4:DB( 6881):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6881):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6881):  SDK version = 0
I/AppUp4:DB( 6881):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6881): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6881): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6881): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6881): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6881): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6881): onReceive
I/AppUp4:CustModeStarterReceiver( 6881): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6881): Context : android.app.ReceiverRestrictedContext@1f3ea82f
D/AppUp4:CustFacade( 6881): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6881): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6881): begin check event
I/AppUp4:CustModeStarterReceiver( 6881): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6881): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 6881): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6881): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6881): handleAsyncCustNotification do not startCustService
I/ActivityManager(  940): Killing 6534:com.google.android.gms:car/u0a6 (adj 15): empty #11
I/LgeMiscReceiver( 3170): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3170): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3170): networkInfo.isConnected() = false
W/libprocessgroup(  940): failed to open /acct/uid_10006/pid_6534/cgroup.procs: No such file or directory
I/ActivityManager(  940): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6919 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 22.735ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.902ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 21.387ms
,D/PhoneMonitor( 6919): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6919): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6919): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  940): Killing 6657:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  940): failed to open /acct/uid_10061/pid_6657/cgroup.procs: No such file or directory
,V/DownloadManager( 3216): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3216): DownloadService onCreate
I/NotificationManager( 3216): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3216): in removeSpuriousFiles
,V/DownloadManager( 3216): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@140a621b on behalf of 3216
I/DownloadManager( 3216): in trimDatabase
V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@16389191 on behalf of 3216
,D/PhoneMonitor( 6919): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/ActivityManager(  940): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6942 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/TelephonyAutoProfiling( 6919): [loadFeatureFromXml] *** start feature loading from xml
,V/DownloadManager( 3216): DownloadService onStartCommand
D/TelephonyAutoProfiling( 6919): [parse] Load xml
V/TelephonyAutoProfiling( 6919): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6919): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3216): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 4333): Checkin interval check for package: unspecified last checkin: 1454412268851 min interval config: 0 actual interval: 22658
,D/PhoneMonitor( 6919): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@386304f7 on behalf of 3216
,I/CheckinService( 4333): Checking schedule, now: 1454412291539 next: 1454412298809
I/CheckinService( 4333): active receiver: disabled
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/DownloadManager( 3216): DownloadService onDestroy
I/ActivityManager(  940): Killing 6685:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,E/libprocessgroup(  940): failed to kill 1 processes for processgroup 6685
D/WeatherAncestor( 2743): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:24:51
,D/UpdateThreadPoolManager( 2743): 2 : This is isUpdating : false
D/WeatherAncestor( 2743): connectivity changed - connection : true
D/Weather_cast( 2743): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2743): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:24:51
D/WeatherService( 2743): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  940): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6967 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  940): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2743): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2743): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2743): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6967): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6967): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6967): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6967): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6967): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6967): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6967): MmsConfig.loadFromResources
E/Babel_SMS( 6967): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6967): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6967): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6967): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6967): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6967): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6967): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6967): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6967): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6967): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6967): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6967): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6967): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6967): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6967): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6967): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6967): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6967): found sensor: Motion Accel, handle=46
,W/Settings( 6967): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6967): startup - clean
I/Babel   ( 6967): deleted: false for 0
,I/art     ( 6967): CheckpointMarkThreadRoots callback created = 0xb042d550
,I/art     ( 6967): CheckpointMarkThreadRoots callback created = 0xb042d530
,I/ActivityManager(  940): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7000 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6967): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6967): Unsupported mime audio/adpcm
W/AudioCapabilities( 6967): Unsupported mime audio/g726
W/AudioCapabilities( 6967): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6967): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6967): Unsupported mime video/mjpg
W/VideoCapabilities( 6967): Unsupported mime video/theora
,W/AudioCapabilities( 6967): Unsupported mime audio/evrc
,W/AudioCapabilities( 6967): Unsupported mime audio/qcelp
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/VideoCapabilities( 6967): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6967): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6967): Unsupported mime audio/qcelp
W/AudioCapabilities( 6967): Unsupported mime audio/evrc
,W/VideoCapabilities( 6967): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6967): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6967): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6967): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6967): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6967): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6967): onServiceConnected
W/Babel   ( 6967): Attempted to change video mute state without an active call.
,D/libc-netbsd( 6967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  280): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 6967): propertyValue:false
I/NotificationManager( 6967): com.google.android.talk: cancel(10436) by com.google.android.talk
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7000): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7000): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7000): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7000):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7000):   adb logcat -s GAv4
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7000): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7000): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7000): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7000): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7000): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 6967): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  940): Killing 6752:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  940): failed to open /acct/uid_10048/pid_6752/cgroup.procs: No such file or directory
,I/WebViewFactory( 7000): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7000): Time to load native libraries: 2 ms (timestamps 6459-6461)
,I/LibraryLoader( 7000): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7000): Binding Chromium to main looper Looper (main, tid 1) {32ff3dd0}
I/LibraryLoader( 7000): Expected native library version number "",actual native library version number ""
I/chromium( 7000): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7000): Initializing chromium process, singleProcess=true
W/art     ( 7000): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7000): ApplicationContext is null in ApplicationStatus
,W/chromium( 7000): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7000): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7000): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7000): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7000): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7000): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7000): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7000): Remote Branch: 
I/Adreno-EGL( 7000): Local Patches: 
I/Adreno-EGL( 7000): Reconstruct Branch: 
,I/ActivityManager(  940): Process com.google.android.music:main (pid 6809) has died
,I/NSApplication( 7000): Starting up...
,V/AudioPolicyService(  287): registerClient() client 0xb4027080, uid 10079
W/AudioManagerAndroid( 7000): Requires BLUETOOTH permission
I/ActivityManager(  940): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7064 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  940): Killing 6837:com.lge.email/u0a21 (adj 15): empty #11
,I/art     ( 6775): CheckpointMarkThreadRoots callback created = 0xb042de10
I/art     ( 6775): CheckpointMarkThreadRoots callback created = 0xb042de00
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  940): failed to open /acct/uid_10021/pid_6837/cgroup.procs: No such file or directory
,I/AppUp4:CustModeStarterReceiver( 6881): onReceive
I/AppUp4:CustModeStarterReceiver( 6881): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6881): Context : android.app.ReceiverRestrictedContext@1f3ea82f
D/AppUp4:CustFacade( 6881): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6881): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6881): begin check event
I/AppUp4:CustModeStarterReceiver( 6881): Event For Nothing, skip.
I/ActivityManager(  940): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7085 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/NotificationManager( 6967): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6967): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6967): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6967): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     (  940): Explicit concurrent mark sweep GC freed 24684(1240KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.266ms total 153.949ms
,W/System  ( 6967): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6967): Installed default security provider GmsCore_OpenSSL
W/ResourcesManager( 7085): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7085): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7085): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 7085): Total System Memory = 906309632
,I/GalleryUtils( 7085): Application Heap = 96 MB
I/AppConfig( 7085): App Tier : NOT_DEF
D/SystemHelper( 7085): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  940): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7111 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 7111): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7111): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7111): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7111): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7111): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7111): BUILD Country: EU
I/SystemConfig( 7111): BUILD Operator: OPEN
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  940): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7136 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  940): Killing 6863:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  940): failed to open /acct/uid_1000/pid_6863/cgroup.procs: No such file or directory
,I/SystemConfig( 7111): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7111): existFile = false
I/SystemConfig( 7111): canReadFile = false
I/SystemConfig( 7111): systemFeature RCS result false
D/SystemConfig( 7111): refreshRcsSupport() :false
I/LockScreenSettings( 7136): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7136): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7136): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7136): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7136): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7136): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/UpdateIcingCorporaServi( 1941): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1941): UpdateCorporaTask done [took 50 ms] updated apps [took 50 ms] 
,I/ActivityManager(  940): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7168 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  940): Killing 6919:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  940): failed to open /acct/uid_10038/pid_6919/cgroup.procs: No such file or directory
,I/ThermalEngine(  299): Sensor:pa_therm0:32000 mC
,D/Finsky  ( 7168): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7168): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7168): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7168): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7168): com.android.vending: cancel(-1050172287) by com.android.vending
I/jxcore-log( 5705): Test app app.js loaded
I/jxcore-log( 5705): 
,V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5705): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5705): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5705): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5705): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5705): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5705): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5705): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5705): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5705): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5705): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19a9f141 added. We now have 1 listener(s)
D/BluetoothAdapterService(549885210)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ab7ce40
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@17c3b5cd on behalf of 7168
D/Ads     ( 7168): Skipping gmscore version check
,I/jxcore-log( 5705): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5705): 
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/chromium( 5705): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/ActivityManager(  940): Process com.google.android.apps.magazines (pid 7000) has died
,D/Finsky  ( 7168): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7168): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7168): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 4333): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ActivityManager(  940): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7227 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/PackageBroadcastService( 4333): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 7168): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/Icing   ( 4333): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 7227): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  940): Message: 20
D/BluetoothManagerService(  940): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@293dcdc6:true
,D/BluetoothAdapterService(549885210)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ab7ce40
D/BluetoothAdapterService(549885210)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2ab7ce40
I/AudioManager( 7227): getMode name:com.lge.qremote
,I/AudioManager( 7227): getMode name:com.lge.qremote
,I/ActivityManager(  940): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7251 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  940): Process com.android.chrome (pid 7064) has died
,I/MusicStore( 7251): Database version: 120
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7251): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7251): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7251): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7251): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7251): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7251): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7251): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7251): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16eb09fb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7251): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7251): GMSCore installation verified
,I/ConfigStore( 7251): Config Database version: 1
,I/MediaRouter( 7251): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7251): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7251): type=WIFI subType= reason=null isConnected=true
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/NetworkMonitor( 7251): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  940): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7285 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 24.272ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 21.175ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 21.165ms
,W/ResourcesManager( 7285): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7285): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7285): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/GHttpClientFactory( 7251): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7251): Using platform SSLCertificateSocketFactory
,I/NotificationManager( 7251): com.google.android.music: cancel(1061) by com.google.android.music
,I/LGEmail ( 7285): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 7285): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/Icing   ( 4333): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/eas_req ( 7285): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
I/Icing   ( 4333): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  940): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7318 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/HubEmail( 7285): JNI_OnLoad()
I/HubEmail( 7285): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7285): registerNatives()
I/HubEmail( 7285): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7285): registerNativeMethods()
I/HubEmail( 7285): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7285): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  940): Killing 6942:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  940): failed to open /acct/uid_10051/pid_6942/cgroup.procs: No such file or directory
W/Settings( 7285): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 7318): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7318): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7318): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7318): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/NetworkStateForAutoUpdateMonitor( 6881): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6881): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6881): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6881): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6881): onReceive
,I/AppUp4:CustModeStarterReceiver( 6881): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6881): Context : android.app.ReceiverRestrictedContext@1f3ea82f
D/AppUp4:CustFacade( 6881): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6881): isSimDevice : true
D/LGDMClient( 7318): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustModeStarterReceiver( 6881): begin check event
I/AppUp4:CustModeStarterReceiver( 6881): Event For GoodConnectivity, noConnectivity : false, but skip! 
D/LGDMClient( 7318): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LgeMiscReceiver( 3170): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3170): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3170): networkInfo.isConnected() = true
D/PhoneState( 3170): setPdpRejectCasuse : false
D/LGDMClient( 7318): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7318): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  940): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7343 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,W/ContextImpl( 7318): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7318): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7318): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7318): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7318): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7318): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  940): Killing 7085:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  940): failed to open /acct/uid_10023/pid_7085/cgroup.procs: No such file or directory
,D/PhoneMonitor( 7343): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7343): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7343): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  940): Killing 7111:com.android.contacts/u0a18 (adj 15): empty #11
D/PhoneMonitor( 7343): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7343): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7343): [parse] Load xml
V/TelephonyAutoProfiling( 7343): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7343): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7343): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  940): failed to open /acct/uid_10018/pid_7111/cgroup.procs: No such file or directory
V/DownloadManager( 3216): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3216): DownloadService onCreate
I/NotificationManager( 3216): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3216): in removeSpuriousFiles
V/DownloadManager( 3216): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@29470e82 on behalf of 3216
,I/DownloadManager( 3216): in trimDatabase
V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@32ff3dd0 on behalf of 3216
I/ActivityManager(  940): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7371 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3216): DownloadService onStartCommand
V/DownloadManager( 3216): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@75b90ce on behalf of 3216
I/CheckinService( 4333): Checkin interval check for package: unspecified last checkin: 1454412268851 min interval config: 0 actual interval: 28611
,I/CheckinService( 4333): Checking schedule, now: 1454412297484 next: 1454412298809
I/CheckinService( 4333): active receiver: disabled
,V/DownloadManager( 3216): DownloadService onDestroy
,I/ActivityManager(  940): Killing 7136:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  940): failed to open /acct/uid_10069/pid_7136/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2743): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:24:57
D/UpdateThreadPoolManager( 2743): 2 : This is isUpdating : false
D/WeatherAncestor( 2743): connectivity changed - connection : true
D/Weather_cast( 2743): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2743): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:24:57
D/WeatherService( 2743): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  940): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2743): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2743): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2743): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  940): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7395 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  940): Explicit concurrent mark sweep GC freed 18770(852KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.425ms total 141.463ms
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7395): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7395): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 7395): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7395):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7395):   adb logcat -s GAv4
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7395): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7395): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,W/GAv4    ( 7395): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7395): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7395): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 7395): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7395): Time to load native libraries: 1 ms (timestamps 1469-1470)
I/LibraryLoader( 7395): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7395): Binding Chromium to main looper Looper (main, tid 1) {32ff3dd0}
I/LibraryLoader( 7395): Expected native library version number "",actual native library version number ""
I/chromium( 7395): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7395): Initializing chromium process, singleProcess=true
,W/art     ( 7395): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7395): ApplicationContext is null in ApplicationStatus
W/chromium( 7395): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7395): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7395): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7395): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7395): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7395): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7395): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7395): Remote Branch: 
I/Adreno-EGL( 7395): Local Patches: 
I/Adreno-EGL( 7395): Reconstruct Branch: 
V/AudioPolicyService(  287): registerClient() client 0xb551cbc0, uid 10079
,W/AudioManagerAndroid( 7395): Requires BLUETOOTH permission
I/NSApplication( 7395): Starting up...
,I/ActivityManager(  940): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7454 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  940): Killing 6775:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  940): failed to open /acct/uid_10086/pid_6775/cgroup.procs: No such file or directory
,I/ActivityManager(  940): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7473 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  940): Killing 7168:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  940): failed to open /acct/uid_10036/pid_7168/cgroup.procs: No such file or directory
,W/ResourcesManager( 7473): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  940): Killing 7251:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  940): failed to open /acct/uid_10081/pid_7251/cgroup.procs: No such file or directory
,I/AudioManager( 7227): getMode name:com.lge.qremote
,I/AudioManager( 7227): getMode name:com.lge.qremote
I/ActivityManager(  940): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7497 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  940): Killing 7285:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  940): failed to open /acct/uid_10021/pid_7285/cgroup.procs: No such file or directory
,W/ActivityManager(  940): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7497): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 7497): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  940): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  940): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  940): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 7497): Observing account changes for notifications
,E/Gmail   ( 7497): Error finding the version of the Email provider.....
E/Gmail   ( 7497): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7497): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7497): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7497): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7497): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7497): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7497): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7497): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7497): We do not support migrating this version of the Email provider.
I/Gmail   ( 7497): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  940): Killing 6881:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  940): failed to open /acct/uid_10011/pid_6881/cgroup.procs: No such file or directory
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/MDM     ( 1733): [150] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 4333): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  940): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver: pid=7549 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
I/Gmail   ( 7497): notifyAccountChanged
,I/Gmail   ( 7497): getAccountsCursor
I/Gmail   ( 7497): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7497): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7497): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7497): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7497): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7549): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7549): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,V/AlarmManager(  940): RTC_WAKEUP set : Alarm{ce3613d type 0 when 1454412298809 com.google.android.gms} when 1454412298809
W/Settings( 7549): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7549): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7549): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@2be266fc on behalf of 7549
D/Finsky  ( 7549): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7549): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 7549): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 7549): Skipping gmscore version check
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/Finsky  ( 7549): [944] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7549): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  940): android: cancelAsUser(2) by android
,I/ActivityManager(  940): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7598 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7227): Create singleton instance
,I/[SystemUI]TimeTickManager( 1384): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1384): called onTimeUpdated()
I/[SystemUI]Clock( 1384): called onTimeUpdated()
,D/libc-netbsd( 7549): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7549): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7549): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7549): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  280): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
I/LgeClockWidgetControlView( 1384): called onTimeUpdated()
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
I/[SystemUI]DateView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
,D/WeatherService( 2743): 2 : TimeTick Intent has been received, Time(hour:min:sec) 12:25:0
D/WeatherService( 2743): 2 : TimeTick Intent And Screen On
D/WeatherService( 2743): 2 : SDK version : 21
I/ThermalEngine(  299): Sensor:pa_therm0:32000 mC
W/ActivityManager(  940): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2743): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2743): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2743): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2743): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2743): 2 : This is isUpdating : false
D/WeatherService( 2743): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2743): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2743): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2743): 2 : Fixed theme : optimus
,D/WeatherReflect( 2743): 2 : Map key string is -2
,D/lim     ( 2743): 2 : time = 12:25
,I/WeatherReflect( 2743): Model Name : LG-D722
D/WeatherTheme( 2743): 2 : Different view - status_min_formatted : 24 != 25
D/WeatherTheme( 2743): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2743): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2743): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2743): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2743): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2743): currentPackage=com.lge.sizechangable.weather.theme.optimus
,D/UEI.SmartControl( 7598): Quickset Services start...
,I/UEI.SmartControl( 7598): Manufacture = LGE
D/UEI.SmartControl( 7598): File observer start...
,I/AudioManager( 7227): getMode name:com.lge.qremote
E/UEI.SmartControl( 7598): IR Port is disabled: false
D/UEI.SmartControl( 7598): Starting file observer...
D/UEI.SmartControl( 7598): Extracting JNI libs...
D/UEI.SmartControl( 7598): --- this system supports 32-bit or 64-bit only
D/Weather4x2_optimus( 2743): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2743): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2743): forecast size is 0
D/Theme   ( 2743): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2743): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2743): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2743): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2743): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2743): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/Theme   ( 2743): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2743): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2743): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2743): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2743): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2743): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2743): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2743): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2743): setTouchIntent, appWidgetId: 2
V/AlarmManager(  940): RTC_WAKEUP set : Alarm{283a73 type 0 when 1454412300208 com.android.vending} when 1454412300208
D/Theme_WeatherAncestor_optimus( 2743): url is : null
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
,D/Theme   ( 2743): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2743): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2743): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2743): 2 : update view, appWidgetId: 2
I/System.out( 7549): propertyValue:false
D/WeatherService( 2743): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 12:25:0
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 7598): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7598): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7598): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/art     (  940): Explicit concurrent mark sweep GC freed 23057(1036KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.625ms total 175.443ms
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/CheckinService( 4333): Checkin interval check for package: unspecified last checkin: 1454412268851 min interval config: 0 actual interval: 31602
,I/CheckinService( 4333): Checking schedule, now: 1454412300467 next: 1454412298809
I/CheckinService( 4333): active receiver: enabled
,I/UEI.SmartControl( 7598): --- Selecting new region: 2
,I/UEI.SmartControl( 7598): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7598): Platform has CIR...
D/UEI.SmartControl( 7598): NO CIR support, need to check package...
,I/UEI.SmartControl( 7598): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7598): QS Service created
W/ContextImpl( 3625): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
I/CheckinService( 4333): Preparing to send checkin request
,I/EventLogService( 4333): Accumulating logs since 1454412258087
,I/CheckinRequestBuilder( 4333): Checkin reason type: 8 attempt count: 1
,E/UEI.SmartControl( 7598): QS start get config
E/ActivityThread( 4333): Failed to find provider info for com.google.android.wearable.settings
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,D/UEI.SmartControl( 7598): Loading JNI Libs...
,D/UEI.SmartControl( 7598):  configuring local db...
I/art     ( 5610): Explicit concurrent mark sweep GC freed 2935(118KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 869us total 41.864ms
,D/Finsky  ( 7549): [940] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7549): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/UEI.SmartControl( 7598):  ---- Has DB8: true
,D/UEI.SmartControl( 7598): QS start statue = true Error code = 0
D/UEI.SmartControl( 7598): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7598): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7598): IRRCDataComm has AudioManager!!!!.
,I/ActivityManager(  940): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7641 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/irrc_jni( 7598): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 7598): IrrcClient ++ 
,D/irrcClient( 7598): getIrrcService ++ 
D/irrcClient( 7598): getIrrcService -- 
D/irrcClient( 7598): IrrcClient -- 
W/irrc_jni( 7598): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7598): Services init done
D/UEI.SmartControl( 7598): QS Service init finished
I/UEI.SmartControl( 7598): Device manager: loading config....
D/UEI.SmartControl( 7598): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7598): QS Service version code: 1073
D/UEI.SmartControl( 7598): Service requested: Control
D/UEI.SmartControl( 7598): Config is loaded...
D/UEI.SmartControl( 7598):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7598): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7598): Request IControl service: devices are loaded...
D/UEI.SmartControl( 7598): Internal service binding...
D/UEI.SmartControl( 7598): -----IControl: 11
D/UEI.SmartControl( 7598): Caller: com.lge.qremote
D/UEI.SmartControl( 7598): ------------ IControl registerCallback...
I/UEI.SmartControl( 7598): Registering callback...
D/UEI.SmartControl( 7598): -----IControl: 19
,D/UEI.SmartControl( 7598): Caller: com.lge.qremote
I/UEI.SmartControl( 7598): Registering Services Ready callback...
I/UEI.SmartControl( 7598): Notify client services are ready...
D/UEI.SmartControl( 7598): -----IControl: 8
D/UEI.SmartControl( 7598): Caller: com.lge.qremote
I/AudioManager( 7227): getMode name:com.lge.qremote
,W/ResourcesManager( 7641): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7641): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  940): Killing 7318:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  940): failed to open /acct/uid_1000/pid_7318/cgroup.procs: No such file or directory
,I/AudioManager( 7227): getMode name:com.lge.qremote
I/AudioManager( 7227): getMode name:com.lge.qremote
I/MultiDex( 7641): VM with version 2.1.0 has multidex support
,I/MultiDex( 7641): install
I/MultiDex( 7641): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 7641): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7641): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7641): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@16676ca0: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7641): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 7641): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7641): com.google.android.gms: cancel(39789) by com.google.android.gms
E/MDM     ( 1733): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4333): Restart initialization of location
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,I/art     ( 7641): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7641): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 34227(2MB) AllocSpace objects, 32(512KB) LOS objects, 40% free, 13MB/22MB, paused 1.855ms total 125.534ms
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,D/NativeLibraryUtils( 7641): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  287): Instantiating CDM.
I/WVCdm   (  287): CdmEngine::OpenSession
I/WVCdm   (  287): Level3 Library Dec 11 2014 16:13:16
,W/WVCdm   (  287): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  287): Properties::GetOEMCryptoPath: null. applies level3
,W/WVCdm   (  287): L1 library not specified. Falling Back to L3
I/WVCdm   (  287): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  287): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  287): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  287): CdmEngine::GenerateKeyRequest
D/WVCdm   (  287): PrepareKeyRequest: nonce=2659612837
I/art     ( 7641): CheckpointMarkThreadRoots callback created = 0xb04cbec0
,I/art     ( 7641): CheckpointMarkThreadRoots callback created = 0xb04cbeb0
,I/WVCdm   (  287): CdmEngine::OpenSession
,I/ActivityManager(  940): Killing 7371:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  940): failed to open /acct/uid_10051/pid_7371/cgroup.procs: No such file or directory
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  940): tsOffsetIs: Apps: 115602187409; DSPS: 3886669; Offset : -3014687365
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/WVCdm   (  287): CdmEngine::CloseSession
,I/WVCdm   (  287): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  287): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  287): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  287): CdmEngine::GenerateKeyRequest
D/WVCdm   (  287): PrepareKeyRequest: nonce=3025628113
I/MusicWidget( 2706): mDelayedStopHandler : unbind
,I/MusicBrowser( 2049): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2049): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2049): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2049): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2049): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2049): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2049): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2049): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  940):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@316b8e6ccom.lge.music.MediaPlaybackService$6@23b8bc35
,D/MusicBrowser( 2049): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2049): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2049): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2049): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2049): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@2217984b
I/MusicBrowser( 2049): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2049): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2049): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2049): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2049): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2049): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2049): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2049): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2049): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2049): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2049): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2049): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2049): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2049): reset
,V/MediaPlayer[Native]( 2049): setListener
V/MediaPlayer[Native]( 2049): disconnect
V/MediaPlayer[Native]( 2049): destructor
,V/AudioFlinger(  287): releasing 19 from 2049 for -1
V/AudioFlinger(  287):  decremented refcount to 0
V/AudioFlinger(  287): purging stale effects
V/MediaPlayer[Native]( 2049): disconnect
D/MusicBrowser( 2049): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
,I/SmartShareClient( 2049): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2049): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2049): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2049): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2049): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2049): [SmartShareManagerClient] unregisterListener: 83785930
W/SmartShareClient( 2049): [SmartShareManagerClient] unregisterListener invalid listener: 83785930
I/SmartShareClient( 2049): [SmartShareManagerClient] terminate service: 2049/MediaPlaybackService/403014665
E/HomeCloudIF( 2049): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2049): [SmartShareManagerClient] unbindService context:android.app.Application@1f632a3b
V/CloudHub( 2049): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2049): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2049): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2049): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2049): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  940): Killing 6967:com.google.android.talk/u0a61 (adj 15): empty #11
I/CloudHub( 2049): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29985
,W/libprocessgroup(  940): failed to open /acct/uid_10061/pid_6967/cgroup.procs: No such file or directory
,I/GAV2    ( 7497): Thread[GAThread,5,main]: No campaign data found.
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  299): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/WVCdm   (  287): CdmEngine::CloseSession
,I/WVCdm   (  287): L3 Terminate.
I/dex2oat ( 7707): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=40 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/UEI.SmartControl( 7598): Internal timer expired: 1
,I/dex2oat ( 7707): dex2oat took 196.887ms (threads: 4)
,I/Adreno-EGL( 7641): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7641): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7641): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7641): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7641): Remote Branch: 
I/Adreno-EGL( 7641): Local Patches: 
I/Adreno-EGL( 7641): Reconstruct Branch: 
,I/Adreno-EGL( 7641): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7641): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7641): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7641): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7641): Remote Branch: 
I/Adreno-EGL( 7641): Local Patches: 
I/Adreno-EGL( 7641): Reconstruct Branch: 
,I/Adreno-EGL( 7641): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7641): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7641): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7641): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7641): Remote Branch: 
I/Adreno-EGL( 7641): Local Patches: 
I/Adreno-EGL( 7641): Reconstruct Branch: 
,I/CheckinRequestBuilder( 4333): Classify the device as Phone.
,D/libc-netbsd( 4333): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4333): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4333): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4333): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 4333): propertyValue:false
D/libc-netbsd( 4333): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4333): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4333): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4333): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4333): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4333): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4333): Sending checkin request (9770 bytes)
,I/CheckinRequestBuilder( 4333): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4333): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 4333): Classify the device as Phone.
,I/CheckinTask( 4333): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4333): Checking schedule, now: 1454412307589 next: 1454939556580
I/CheckinService( 4333): active receiver: disabled
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/CheckinService( 4333): Recording last checkin time for package unspecified as 1454412307619
,I/ActivityManager(  940): Killing 7395:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  940): failed to open /acct/uid_10079/pid_7395/cgroup.procs: No such file or directory
,V/SetupWizard( 7343): Connected to Gservices successfully
I/ActivityManager(  940): Killing 7454:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  940): failed to open /acct/uid_10048/pid_7454/cgroup.procs: No such file or directory
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  299): Sensor:pa_therm0:32000 mC
,I/[SystemUI]QPairHandler( 1384): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  940): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  940): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7741 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 303us total 25.245ms
,I/[SystemUI]QSlideListController( 1384): onReceive = android.intent.action.PACKAGE_CHANGED
D/administrator(  940): Handling package changes for user 0
W/[SystemUI]QSlideLoader( 1384): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1384): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1384): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1384): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1384): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1384): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1384): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1384): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1384): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1384): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1384): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1384): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1384): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/art     (  310): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 30.059ms
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 359us total 23.711ms
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,W/ResourcesManager( 7741): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/NotificationService(  940): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  940): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  940): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  940): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
V/BackupManagerService(  940): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/BackupManagerService(  940): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@211fb050
,W/ResourcesManager(  940): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Babel_SMS( 7741): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7741): MmsConfig.loadMmsSettings
,I/ActivityManager(  940): Process com.google.android.apps.plus (pid 7473) has died
I/Babel_SMS( 7741): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7741): MmsConfig.loadFromDatabase
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
,E/Babel_SMS( 7741): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7741): MmsConfig.loadFromResources
E/Babel_SMS( 7741): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7741): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7741): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7741): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7741): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7741): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7741): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7741): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7741): found sensor: LGE Rotation Vector Sensor, handle=36
,D/SensorManager( 7741): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7741): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7741): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7741): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7741): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7741): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7741): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7741): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7741): found sensor: Motion Accel, handle=46
W/ResourceType(  940): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/Settings( 7741): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7741): startup - clean
I/art     ( 7741): CheckpointMarkThreadRoots callback created = 0xb042d8c0
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/Babel   ( 7741): deleted: false for 0
I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/art     ( 7741): CheckpointMarkThreadRoots callback created = 0xb042d890
D/LocationProviderProxy(  940): applying state to connected service
,W/AudioCapabilities( 7741): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7741): Unsupported mime audio/adpcm
W/AudioCapabilities( 7741): Unsupported mime audio/g726
W/AudioCapabilities( 7741): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 7741): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7741): Unsupported mime video/mjpg
W/VideoCapabilities( 7741): Unsupported mime video/theora
I/ActivityManager(  940): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7779 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/AudioCapabilities( 7741): Unsupported mime audio/evrc
,W/AudioCapabilities( 7741): Unsupported mime audio/qcelp
W/VideoCapabilities( 7741): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7741): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7741): Unsupported mime audio/qcelp
W/AudioCapabilities( 7741): Unsupported mime audio/evrc
,W/VideoCapabilities( 7741): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7741): Unsupported profile 4 for video/mp4v-es
,I/AppUp4:AppBoxCP( 7779): onCreate
W/VideoCapabilities( 7741): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7741): Unrecognized profile 2130706433 for video/avc
W/AppUp4:DB( 7779):  [AppBoxDatabaseHelper] construct
,W/VideoCapabilities( 7741): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7741): Unrecognized profile 2130706433 for video/avc
,I/AppUp4:DB( 7779):  setFingerPrint start
I/AppUp4:DB( 7779):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7779):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7779):  SDK version = 0
I/AppUp4:DB( 7779):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7779): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7779): onReceive
I/AppUp4:CustModeStarterReceiver( 7779): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7779): Context : android.app.ReceiverRestrictedContext@f5a0110
D/AppUp4:CustFacade( 7779): isCustomizationCompleted : false
I/ActivityManager(  940): Process com.android.vending (pid 7549) has died
,D/AppUp4:CustFacade( 7779): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7779): begin check event
I/AppUp4:CustModeStarterReceiver( 7779): Event For Nothing, skip.
I/vclib   ( 7741): onServiceConnected
W/Babel   ( 7741): Attempted to change video mute state without an active call.
I/NotificationManager( 7741): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7741): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7741): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  940): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7801 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,V/JNIHelp ( 7741): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 7801): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7801): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7801): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/System  ( 7741): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7741): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 7741): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AppConfig( 7801): Total System Memory = 906309632
,I/GalleryUtils( 7801): Application Heap = 96 MB
,I/AppConfig( 7801): App Tier : NOT_DEF
D/SystemHelper( 7801): region [EU], country [EU], operator [OPEN], sub-operator []
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
,I/ActivityManager(  940): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7825 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  940): Process com.google.android.gm (pid 7497) has died
,W/ResourcesManager( 7825): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7825): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7825): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7825): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7825): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/art     (  940): Explicit concurrent mark sweep GC freed 25013(1283KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.625ms total 164.265ms
,I/SystemConfig( 7825): BUILD Country: EU
,I/SystemConfig( 7825): BUILD Operator: OPEN
,I/SystemConfig( 7825): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 7825): existFile = false
I/SystemConfig( 7825): canReadFile = false
I/SystemConfig( 7825): systemFeature RCS result false
D/SystemConfig( 7825): refreshRcsSupport() :false
,I/ActivityManager(  940): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7848 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/LockScreenSettings( 7848): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7848): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7848): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7848): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7848): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7848): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  940): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7865 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  940): Killing 2049:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  287): 2049 died, releasing its sessions
V/AudioFlinger(  287):  pid 1743 @ 0
,V/AudioFlinger(  287):  pid 3170 @ 1
V/AudioFlinger(  287):  pid 3170 @ 2
,W/libprocessgroup(  940): failed to open /acct/uid_10028/pid_2049/cgroup.procs: No such file or directory
W/ResourcesManager( 7865): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1941): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  940): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7895 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1941): UpdateCorporaTask done [took 54 ms] updated apps [took 54 ms] 
I/ActivityManager(  940): Killing 7598:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/System.err( 7227): android.os.DeadObjectException
W/System.err( 7227): 	at android.os.BinderProxy.transactNative(Native Method)
,W/System.err( 7227): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7227): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7227): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7227): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7227): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7227): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7227): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7227): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7227): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7227): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7227): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7227): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7227): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7227): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7227): android.os.DeadObjectException
W/System.err( 7227): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7227): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7227): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7227): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7227): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7227): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7227): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7227): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7227): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7227): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7227): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7227): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7227): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7227): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7227): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  940): failed to open /acct/uid_10089/pid_7598/cgroup.procs: No such file or directory
W/ActivityManager(  940): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  940): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7917 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7917): Quickset Services start...
,I/UEI.SmartControl( 7917): Manufacture = LGE
D/UEI.SmartControl( 7917): File observer start...
E/UEI.SmartControl( 7917): IR Port is disabled: false
D/UEI.SmartControl( 7917): Starting file observer...
D/UEI.SmartControl( 7917): Extracting JNI libs...
D/UEI.SmartControl( 7917): --- this system supports 32-bit or 64-bit only
D/Finsky  ( 7895): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 7917): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7917): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7917): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/Finsky  ( 7895): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/UEI.SmartControl( 7917): --- Selecting new region: 2
I/UEI.SmartControl( 7917): -- Running on KitKat(19) and above! JNI will be used.
W/Settings( 7895): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/UEI.SmartControl( 7917): Platform has CIR...
D/UEI.SmartControl( 7917): NO CIR support, need to check package...
I/UEI.SmartControl( 7917): Model: LG-D722 uses JNI
,W/Settings( 7895): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/UEI.SmartControl( 7917): QS Service created
I/NotificationManager( 7895): com.android.vending: cancel(-1050172287) by com.android.vending
E/UEI.SmartControl( 7917): QS start get config
,V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@daed185 on behalf of 7895
D/Finsky  ( 7895): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7895): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7895): Skipping gmscore version check
,D/UEI.SmartControl( 7917): Loading JNI Libs...
,D/UEI.SmartControl( 7917):  configuring local db...
I/ActivityManager(  940): Killing 7227:com.lge.qremote/u0a106 (adj 15): empty #11
D/Finsky  ( 7895): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/libprocessgroup(  940): failed to open /acct/uid_10106/pid_7227/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 4333): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4333): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7895): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 4333): updateResources: need to parse f{com.google.android.gms}
,D/UEI.SmartControl( 7917):  ---- Has DB8: true
,D/UEI.SmartControl( 7917): QS start statue = true Error code = 0
D/UEI.SmartControl( 7917): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7917): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 7917): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7917): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7917): IrrcClient ++ 
D/irrcClient( 7917): getIrrcService ++ 
,D/irrcClient( 7917): getIrrcService -- 
D/irrcClient( 7917): IrrcClient -- 
W/irrc_jni( 7917): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7917): Services init done
I/UEI.SmartControl( 7917): Device manager: loading config....
D/UEI.SmartControl( 7917): QS Service init finished
,D/UEI.SmartControl( 7917): Config is loaded...
D/UEI.SmartControl( 7917): QS Service version name: 0.1.73
D/UEI.SmartControl( 7917): QS Service version code: 1073
D/UEI.SmartControl( 7917): Service requested: Control
D/UEI.SmartControl( 7917): Service.onUnbind: IControl
D/UEI.SmartControl( 7917): Service.onDestroy
D/UEI.SmartControl( 7917): Shutdown IRRCPlayer... 
W/irrc_jni( 7917): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7917): ~IrrcClient ++ 
D/irrcClient( 7917): ~IrrcClient -- 
W/irrc_jni( 7917): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7917): Blaster closed
D/UEI.SmartControl( 7917): Blaster closed
D/UEI.SmartControl( 7917): Shut down QS...
D/UEI.SmartControl( 7917): Stopped file observer...
I/UEI.SmartControl( 7917): QS lib stop result = true
D/UEI.SmartControl( 7917): QS shutdown complete
D/UEI.SmartControl( 7917): QS Service created
,E/UEI.SmartControl( 7917): QS start get config
,I/UEI.SmartControl( 7917): Notify AllClients services are ready: 11
,D/UEI.SmartControl( 7917):  configuring local db...
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  940): battery changed pluggedType: 2
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
D/charger_monitor(  492): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/UEI.SmartControl( 7917):  ---- Has DB8: true
,D/UEI.SmartControl( 7917): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7917): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7917): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 7917): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7917): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7917): IrrcClient ++ 
D/irrcClient( 7917): getIrrcService ++ 
D/irrcClient( 7917): getIrrcService -- 
D/irrcClient( 7917): IrrcClient -- 
W/irrc_jni( 7917): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7917): Services init done
I/UEI.SmartControl( 7917): Device manager: loading config....
D/UEI.SmartControl( 7917): QS Service init finished
D/UEI.SmartControl( 7917): QS Service version name: 0.1.73
D/UEI.SmartControl( 7917): QS Service version code: 1073
D/UEI.SmartControl( 7917): Service requested: Control
,D/UEI.SmartControl( 7917): Config is loaded...
D/UEI.SmartControl( 7917): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7917):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7917): Notify AllClients services are ready: 0
E/ActivityThread( 7917): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@20c6951a that was originally bound here
E/ActivityThread( 7917): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@20c6951a that was originally bound here
E/ActivityThread( 7917): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 7917): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 7917): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 7917): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 7917): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7917): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 7917): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 7917): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 7917): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 7917): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 7917): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 7917): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7917): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 7917): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 7917): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7917): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7917): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 7917): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 7917): Internal service binding...
I/Icing   ( 4333): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/UEI.SmartControl( 7917): Internal timer expired: 2
,W/System.err( 7917): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@20c6951a
W/System.err( 7917): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
I/Icing   ( 4333): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
W/System.err( 7917): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7917): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7917): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7917): 	at com.uei.control.Service.a(Unknown Source)
W/System.err( 7917): 	at com.uei.control.l.run(Unknown Source)
W/System.err( 7917): 	at java.util.Timer$TimerImpl.run(Timer.java:284)
E/UEI.SmartControl( 7917): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@20c6951a
I/ActivityManager(  940): Killing 7343:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  940): failed to open /acct/uid_10038/pid_7343/cgroup.procs: No such file or directory
,I/ThermalEngine(  299): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  940): Killing 7641:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  940): failed to open /acct/uid_10006/pid_7641/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,E/UEI.SmartControl( 7917): file observer is disposed!
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 7917): Internal timer expired: 3
,D/UEI.SmartControl( 7917): Service.onUnbind: IControl
D/UEI.SmartControl( 7917): Service.onDestroy
W/System.err( 7917): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1a456e27
W/System.err( 7917): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7917): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7917): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7917): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7917): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7917): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7917): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7917): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7917): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7917): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7917): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7917): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7917): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7917): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7917): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7917): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1a456e27
D/UEI.SmartControl( 7917): Shutdown IRRCPlayer... 
W/irrc_jni( 7917): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7917): ~IrrcClient ++ 
D/irrcClient( 7917): ~IrrcClient -- 
W/irrc_jni( 7917): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7917): Blaster closed
D/UEI.SmartControl( 7917): Blaster closed
D/UEI.SmartControl( 7917): Shut down QS...
I/UEI.SmartControl( 7917): QS lib stop result = true
D/UEI.SmartControl( 7917): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  299): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 135602864381; DSPS: 4542052; Offset : -3014711984
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  299): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ThermalEngine(  299): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  940): ELAPSED_WAKEUP set : Alarm{2a5444ca type 2 when 146379 com.google.android.gms} when 146379
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1733): Vacuum at: now=1454412333354 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  299): Sensor:pa_therm0:32000 mC
,I/PowerManagerService(  940): ALS enabled for SRE
,D/PowerManagerServiceEx(  940): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29239 ms ago)
D/qdlights(  940): set_light_backlight: 253
,D/qdlights(  940): set_light_backlight: 250
D/qdlights(  940): set_light_backlight: 246
,D/qdlights(  940): set_light_backlight: 243
,D/qdlights(  940): set_light_backlight: 240
,D/qdlights(  940): set_light_backlight: 236
,D/qdlights(  940): set_light_backlight: 233
,D/qdlights(  940): set_light_backlight: 230
,D/qdlights(  940): set_light_backlight: 226
,D/qdlights(  940): set_light_backlight: 223
,D/qdlights(  940): set_light_backlight: 220
,D/qdlights(  940): set_light_backlight: 216
,D/qdlights(  940): set_light_backlight: 213
,D/qdlights(  940): set_light_backlight: 210
,D/qdlights(  940): set_light_backlight: 206
,D/qdlights(  940): set_light_backlight: 203
,D/qdlights(  940): set_light_backlight: 200
,D/qdlights(  940): set_light_backlight: 196
,D/qdlights(  940): set_light_backlight: 193
,D/qdlights(  940): set_light_backlight: 190
,D/qdlights(  940): set_light_backlight: 186
,D/qdlights(  940): set_light_backlight: 183
,D/qdlights(  940): set_light_backlight: 180
,D/qdlights(  940): set_light_backlight: 176
,D/qdlights(  940): set_light_backlight: 173
,D/qdlights(  940): set_light_backlight: 170
,D/qdlights(  940): set_light_backlight: 166
,D/qdlights(  940): set_light_backlight: 163
,D/qdlights(  940): set_light_backlight: 160
,D/qdlights(  940): set_light_backlight: 156
,D/qdlights(  940): set_light_backlight: 153
,D/qdlights(  940): set_light_backlight: 150
,D/qdlights(  940): set_light_backlight: 146
,D/qdlights(  940): set_light_backlight: 143
,D/qdlights(  940): set_light_backlight: 140
,D/qdlights(  940): set_light_backlight: 136
,D/qdlights(  940): set_light_backlight: 133
,D/qdlights(  940): set_light_backlight: 130
,D/qdlights(  940): set_light_backlight: 126
,D/qdlights(  940): set_light_backlight: 123
,D/qdlights(  940): set_light_backlight: 120
,D/qdlights(  940): set_light_backlight: 116
,D/qdlights(  940): set_light_backlight: 113
,D/qdlights(  940): set_light_backlight: 110
,D/qdlights(  940): set_light_backlight: 106
,D/qdlights(  940): set_light_backlight: 103
,D/qdlights(  940): set_light_backlight: 100
,D/qdlights(  940): set_light_backlight: 96
,D/qdlights(  940): set_light_backlight: 93
,D/qdlights(  940): set_light_backlight: 90
,D/qdlights(  940): set_light_backlight: 86
,D/qdlights(  940): set_light_backlight: 83
,D/qdlights(  940): set_light_backlight: 80
,D/qdlights(  940): set_light_backlight: 76
,D/qdlights(  940): set_light_backlight: 73
,D/qdlights(  940): set_light_backlight: 70
,D/qdlights(  940): set_light_backlight: 66
,D/qdlights(  940): set_light_backlight: 63
,D/qdlights(  940): set_light_backlight: 60
,D/qdlights(  940): set_light_backlight: 56
,D/qdlights(  940): set_light_backlight: 53
,D/qdlights(  940): set_light_backlight: 50
,D/qdlights(  940): set_light_backlight: 46
,D/qdlights(  940): set_light_backlight: 43
,D/qdlights(  940): set_light_backlight: 40
,D/qdlights(  940): set_light_backlight: 36
,D/qdlights(  940): set_light_backlight: 33
,D/qdlights(  940): set_light_backlight: 30
,D/qdlights(  940): set_light_backlight: 26
,D/qdlights(  940): set_light_backlight: 23
,D/qdlights(  940): set_light_backlight: 20
,D/qdlights(  940): set_light_backlight: 16
,D/qdlights(  940): set_light_backlight: 13
,D/qdlights(  940): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  299): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 155603539164; DSPS: 5197434; Offset : -3014708849
,I/PowerManagerService(  940): ALS enabled for SRE
D/PowerManagerServiceEx(  940): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36233 ms ago)
I/PowerManagerService(  940): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  940): ALS enabled for SRE
D/PowerManagerServiceEx(  940): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36247 ms ago)
,W/ContextImpl(  940): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  940): Sleeping (uid 1000)...
D/LPWGController(  940): [updateScreenState] screen on = false
D/LPWGController(  940): disable proximity sensor
,D/LPWGController(  940): enable proximity sensor
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/SensorManager(  940): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@8ee01b3] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  940): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
,D/sensors_hal_SAM(  940): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  940): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  940): activate: handle is 48, enable
V/sensors_hal_Ctx(  940): activate sensors is 1400000000000
D/sensors_hal_Thresh(  940): enable: handle=48
I/sensors_hal_SAM(  940): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  940): waitForResponse: timeout=1000
V/sensors_hal_SAM(  940): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  940): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  940): enable: Received response: 0
D/PowerManagerServiceEx(  940): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36302 ms ago)
I/Adreno-EGL(  940): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  940): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  940): Build Date: 03/02/15 Mon
I/Adreno-EGL(  940): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  940): Remote Branch: 
I/Adreno-EGL(  940): Local Patches: 
I/Adreno-EGL(  940): Reconstruct Branch: 
,D/PermissionCache(  249): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1041 us)
,I/Sensors (  434): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  940): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  940): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  940): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  940): processInd: handle 48, count=1
V/sensors_hal_Thresh(  940): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  940): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  940): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  940): poll: count: 256
I/sensors_hal_Ctx(  940): poll: released wakelock sensor_ind
D/sensors_hal_Util(  940): waitForResponse: timeout=0
D/LPWGController(  940): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  940): current mode = 1  value = 1 1
I/LPWGController(  940): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  940): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  940): set_light_backlight: 0
,I/SensorManager(  940): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  940): activate: handle is 46, disable
V/sensors_hal_Ctx(  940): activate sensors is 1000000000000
D/sensors_hal_LP2(  940): enable: handle=46
D/sensors_hal_LP2(  940): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  940): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
I/DisplayManagerService(  940): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/sensors_hal_SAM(  940): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  940): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,V/ActivityManager(  940): Display changed displayId=0
,D/DSDPConnection( 1743): Display #0 changed.
,D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
D/SurfaceControl(  940): Excessive delay in setPowerMode(): 192ms
,I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  940): Got set_interactive hint
D/KeyguardViewMediator( 1384): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1384): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1333): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1333): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1333): handleNotifyScreenOFF
D/KeyguardViewMediator( 1384): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1384): handleNotifyScreenOff
,D/ScreenTurnOffBySensor( 1384): unregisterProximitySensor
,D/StatusBarWindowView( 1384): onScreenTurnedOff why = 3
,D/WifiServerServiceExt(  940): sendKtScanInterval  mRtspPlay : false
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1384): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/WifiServerServiceExt(  940): set CMD_KT_SCAN_INTERVAL
,V/AudioFlinger(  287): setParameters(): io 0, keyvalue screen_state=on, calling pid 940
D/audio_hw_primary(  287): adev_set_parameters: enter: screen_state=on
V/voice   (  287): voice_set_parameters: enter: screen_state=on
V/compress_voip(  287): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  287): voice_extn_compress_voip_set_parameters: exit
V/voice   (  287): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  287): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  287): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  287): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  287): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  287): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  287): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  287): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
,D/GpsLocationProvider(  940): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:true
I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
D/LNfcService( 1786): action : android.intent.action.SCREEN_ON
,D/LEDService( 1803): stopPatternFlashing()
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1803): lockStatus = 0
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): updateLightsLocked : turn off led
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
,D/LEDHandler( 1803): RESTART MSG
D/NfcServiceNXP( 1786): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1786): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1786): isRequireNfcCRouting() return true
D/LNfcService( 1786): isHCERoutingtoHost() return : true
,D/NfcService( 1786): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): newParams.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): screenState= 3
D/NfcService( 1786): Discovery configuration equal, not updating.
D/SplitWindow(  940): check instance of lgWin Window{14f1cf6e u0 SearchPanel}
,D/InputDispatcher(  940): Window went away: Window{10332fc0 u0 SearchPanel}
,I/[SystemUI]Clock( 1384): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1384): time changed, timezoneChanged : false
,D/Ulp_jni (  940): JNI:system_update. Event-0
,V/PhoneApp( 1743): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2743): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:25:44
,D/WeatherService( 2743): 2 : ACTION screen on
D/WeatherService( 2743): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2743): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2743): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:25:44
,W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  940): ACTION_SCREEN_ON
D/AppCleanupService( 4123): android.intent.action.SCREEN_ON
,V/AudioFlinger(  287): setParameters(): io 0, keyvalue screen_state=off, calling pid 940
,D/audio_hw_primary(  287): adev_set_parameters: enter: screen_state=off
V/voice   (  287): voice_set_parameters: enter: screen_state=off
V/compress_voip(  287): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  287): voice_extn_compress_voip_set_parameters: exit
V/voice   (  287): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  287): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  287): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  287): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  287): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  287): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  287): adev_set_parameters: exit with code(0)
D/WifiController(  940): CMD_SCREEN_OFF 
D/WifiController(  940): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  940): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:false
,I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1803): clear
D/LNfcService( 1786): action : android.intent.action.SCREEN_OFF
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/NfcServiceNXP( 1786): mScreenState : 1, mInProvisionMode : false
I/LEDService( 1803): updateLightsLocked : turn on led
E/LEDService( 1803): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1803): Can't handle this request of patternId:0
D/LEDHandler( 1803): RESTART MSG
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,I/Sensors (  434): sns_pwr.c(301):releasing wakelock
I/[LGHome]EVENT( 1878): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1743): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2743): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:25:44
D/WeatherService( 2743): 2 : ACTION screen off
D/WeatherService( 2743): 2 : TimeTick Receiver Unregister
,D/WeatherService( 2743): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:25:44
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  940): ACTION_SCREEN_OFF
D/AppCleanupService( 4123): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4123): AppUsageStatsSaveTask
,E/NxpNfcJni( 1786): getReconnectState = 0x0
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
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
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1384): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  940): ELAPSED_WAKEUP set : Alarm{353d060f type 2 when 162116 com.android.systemui} when 162116
,D/PhoneUtils( 1743): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1743): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1743): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1743): getCallState : 0
,D/PhoneUtils( 1743): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1743): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1743): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1384): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1384): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1384): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1384): called onTimeUpdated()
I/[SystemUI]Clock( 1384): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 175604215146; DSPS: 5852816; Offset : -3014704019
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  940): acquireWakeLockInternal: lock=24008348, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=940
,V/AlarmManager(  940): ELAPSED_WAKEUP set : Alarm{130698a5 type 2 when 184732 android} when 184732
D/PowerManagerServiceEx(  940): releaseWakeLockInternal: lock=24008348 [*alarm*], flags=0x0
,I/ClearcutLoggerApiImpl( 1733): disconnect managed GoogleApiClient
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  940): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
V/AlarmManager(  940): ELAPSED_WAKEUP set : Alarm{10ef747a type 2 when 188077 com.google.android.gms} when 188077
,I/PhenotypeConfigurator( 1733): Scheduling Phenotype for one-off execution 11546 seconds from now (1454412375179),
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
D/GetConfigurationSnapshotOperation( 1733): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1733): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1733): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  940): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  280): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  280): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  280): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  280): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  280): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  280): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  280): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  940): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  940): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  940): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  940): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  940): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  940): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 195604936232; DSPS: 6508200; Offset : -3014715486
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 215605699297; DSPS: 7163585; Offset : -3014715412
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1384): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1384): called onTimeUpdated()
I/[SystemUI]Clock( 1384): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 235606372623; DSPS: 7818967; Offset : -3014713083
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  940): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 255607095376; DSPS: 8474350; Offset : -3014692702
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  940): battery changed pluggedType: 2
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  940): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 275607774691; DSPS: 9129733; Offset : -3014714796
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1384): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1384): called onTimeUpdated()
I/[SystemUI]Clock( 1384): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 295608501454; DSPS: 9785116; Offset : -3014690224
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  940): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 315609252853; DSPS: 10440501; Offset : -3014701738
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 335609918678; DSPS: 11095883; Offset : -3014707509
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/LocationManagerService(  940): remove 258bcc8b
D/LocationManagerService(  940): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  940): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  940): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  940): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  940): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  299): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1384): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1384): called onTimeUpdated()
I/[SystemUI]Clock( 1384): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 355610902161; DSPS: 11751275; Offset : -3014700171
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  940): battery changed pluggedType: 2
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 375611709497; DSPS: 12406662; Offset : -3014717097
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 395612438084; DSPS: 13062045; Offset : -3014690414
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  940): acquireWakeLockInternal: lock=24008348, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=940
,D/PowerManagerServiceEx(  940): releaseWakeLockInternal: lock=24008348 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1384): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1384): called onTimeUpdated()
I/[SystemUI]Clock( 1384): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 415613114847; DSPS: 13717428; Offset : -3014716389
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  940): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  940): battery changed pluggedType: 2
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  940): battery changed pluggedType: 2
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 435613841245; DSPS: 14372811; Offset : -3014690879
,D/PowerManagerServiceEx(  940): acquireWakeLockInternal: lock=24008348, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=940
,V/AlarmManager(  940): RTC_WAKEUP set : Alarm{184df02a type 0 when 1454412624758 com.google.android.gms} when 1454412624758
I/ActivityManager(  940): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8137 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/EventLogService( 4333): Aggregate from 1454412300516 (log), 1454410824573 (data)
,I/DigitalAppWidgetProvider( 8137): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8137): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@f5a0110
,D/PowerManagerServiceEx(  940): releaseWakeLockInternal: lock=24008348 [*alarm*], flags=0x0
I/ActivityManager(  940): Killing 7779:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  940): failed to open /acct/uid_10011/pid_7779/cgroup.procs: No such file or directory
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 455614790404; DSPS: 15028203; Offset : -3014720210
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1384): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1384): called onTimeUpdated()
I/[SystemUI]Clock( 1384): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 475615455344; DSPS: 15683584; Offset : -3014694629
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  940): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 495616210076; DSPS: 16338969; Offset : -3014702367
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 515616964391; DSPS: 16994354; Offset : -3014711304
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1384): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1384): called onTimeUpdated()
I/[SystemUI]Clock( 1384): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 535617649279; DSPS: 17649736; Offset : -3014698142
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  940): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 555618396460; DSPS: 18305121; Offset : -3014713380
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 575619073743; DSPS: 18960503; Offset : -3014707248
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1384): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1384): called onTimeUpdated()
I/[SystemUI]Clock( 1384): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 595619736704; DSPS: 19615885; Offset : -3014715856
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  940): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 615620453156; DSPS: 20271268; Offset : -3014703001
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 635621221534; DSPS: 20926653; Offset : -3014696261
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1384): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1384): called onTimeUpdated()
I/[SystemUI]Clock( 1384): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 655621938140; DSPS: 21582037; Offset : -3014711504
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  940): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 675622690841; DSPS: 22237421; Offset : -3014691590
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 695623436823; DSPS: 22892806; Offset : -3014708677
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1384): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1384): called onTimeUpdated()
I/[SystemUI]Clock( 1384): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 715624175044; DSPS: 23548190; Offset : -3014702305
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 735624922589; DSPS: 24203575; Offset : -3014718220
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 755625657685; DSPS: 24858958; Offset : -3014684951
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1384): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1384): called onTimeUpdated()
I/[SystemUI]Clock( 1384): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 775626532522; DSPS: 25514347; Offset : -3014694680
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  940): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 795627282774; DSPS: 26169732; Offset : -3014707628
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 815627949277; DSPS: 26825114; Offset : -3014712824
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1384): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1384): called onTimeUpdated()
I/[SystemUI]Clock( 1384): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 835628604478; DSPS: 27480495; Offset : -3014698389
,I/ThermalEngine(  299): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 855629361761; DSPS: 28135880; Offset : -3014703836
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 875630309254; DSPS: 28791271; Offset : -3014702414
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1384): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1384): called onTimeUpdated()
I/[SystemUI]Clock( 1384): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 895630775445; DSPS: 29446646; Offset : -3014694221
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  940): battery changed pluggedType: 2
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 915631537833; DSPS: 30102031; Offset : -3014694799
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 935632201576; DSPS: 30757413; Offset : -3014702026
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  940): acquireWakeLockInternal: lock=24008348, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=940
,V/AlarmManager(  940): ELAPSED_WAKEUP set : Alarm{1c32a0f7 type 2 when 952286 com.android.bluetooth} when 952286
D/PowerManagerServiceEx(  940): releaseWakeLockInternal: lock=24008348 [*alarm*], flags=0x0
,W/bt-smp  ( 1990): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1990): Plain text(LSB ~ MSB) = 8a 2c 4e 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1990): Encrypted text(LSB ~ MSB) = 64 d9 c1 e4 34 a1 33 7b 38 65 37 bc 4c c9 e3 f4 
W/bt-btm  ( 1990): Stopping oneshot timer
,I/[SystemUI]TimeTickManager( 1384): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1384): called onTimeUpdated()
I/[SystemUI]Clock( 1384): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 955632931880; DSPS: 31412797; Offset : -3014704457
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  940): battery changed pluggedType: 2
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 975633689893; DSPS: 32068182; Offset : -3014709252
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  940): acquireWakeLockInternal: lock=24008348, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=940
,V/AlarmManager(  940): ELAPSED_WAKEUP set : Alarm{24a3fb64 type 2 when 991380 com.google.android.gms} when 991380
D/PowerManagerServiceEx(  940): releaseWakeLockInternal: lock=24008348 [*alarm*], flags=0x0
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 995634360511; DSPS: 32723564; Offset : -3014710386
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1384): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1384): called onTimeUpdated()
I/[SystemUI]Clock( 1384): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 1015635125190; DSPS: 33378949; Offset : -3014708203
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  940): battery changed pluggedType: 2
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 1035635872266; DSPS: 34034333; Offset : -3014693810
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 1055636531165; DSPS: 34689715; Offset : -3014706194
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1384): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1384): called onTimeUpdated()
I/[SystemUI]Clock( 1384): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 1075637276886; DSPS: 35345099; Offset : -3014692946
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 1095638057295; DSPS: 36000485; Offset : -3014706125
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 1115638713798; DSPS: 36655867; Offset : -3014720775
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1384): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1384): called onTimeUpdated()
I/[SystemUI]Clock( 1384): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 1135639446498; DSPS: 37311251; Offset : -3014721876
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 1155640420606; DSPS: 37966642; Offset : -3014692250
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 1175641058203; DSPS: 38622023; Offset : -3014695914
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1384): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1384): called onTimeUpdated()
I/[SystemUI]Clock( 1384): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 1195641879705; DSPS: 39277410; Offset : -3014698126
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1384): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1384): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1384): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  940): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  940): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  940): battery changed pluggedType: 2
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 1215642641000; DSPS: 39932795; Offset : -3014699953
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/UsageStatsService(  940): User[0] Flushing usage stats to disk
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 1235643309221; DSPS: 40588177; Offset : -3014704602
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1384): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1384): called onTimeUpdated()
I/[SystemUI]Clock( 1384): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
I/[SystemUI]DateView( 1384): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1384): handleTimeUpdate
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 1255644043015; DSPS: 41243561; Offset : -3014701590
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1384): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1384): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1384): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1384): On Skip Timer : true
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 1275644793477; DSPS: 41898946; Offset : -3014714510
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),I/ThermalEngine(  299): Sensor:pa_therm0:28000 mC
D/AndroidRuntime( 8269): 
D/AndroidRuntime( 8269): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8269): CheckJNI is OFF
D/AndroidRuntime( 8269): Calling main entry com.android.commands.pm.Pm
I/art     (  940): Explicit concurrent mark sweep GC freed 73944(3MB) AllocSpace objects, 11(176KB) LOS objects, 33% free, 23MB/35MB, paused 2.746ms total 163.825ms
I/ActivityManager(  940): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  940): Killing 5705:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
W/PackageSettings(  940): Skipping PackageSetting{17fcdd69 com.example.hello/10317} due to missing metadata
I/WindowState(  940): WIN DEATH: Window{3ad1b64f u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  940): Focus left window: Window{3ad1b64f u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  940): Window went away: Window{3ad1b64f u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  940):   Force finishing activity ActivityRecord{1eb8e9e u0 com.test.thalitest/.MainActivity t222}
V/ActivityManager(  940): Display changed displayId=0
D/DSDPConnection( 1743): Display #0 changed.
W/ActivityManager(  940): Spurious death for ProcessRecord{23c2b1cd 5705:com.test.thalitest/u0a316}, curProc for 5705: null
I/ActivityManager(  940): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/[LGHome]EVENT( 1878): [Launcher.java:5203:onStart()]onStart
I/[LGHome]EVENT( 1878): [Launcher.java:776:onResume()]onResume
D/KeyguardModel( 1384): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
W/System.err( 3625): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  940): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  940): tsOffsetIs: Apps: 1295645412010; DSPS: 42554326; Offset : -3014706172
I/InputReader(  940): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  940): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8296 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1878): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
W/System.err( 3625): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
D/administrator(  940): Handling package changes for user 0
W/System.err( 3625): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3625): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3625): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3625): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3625): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3625): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3625): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3625): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3625): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3625): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/art     ( 1941): Explicit concurrent mark sweep GC freed 21803(1261KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 12MB/21MB, paused 3.908ms total 148.448ms
I/[SystemUI]QSlideListController( 1384): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1878): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1878): [Launcher.java:929:onResume()]onResume end
I/Activity( 1878): Activity.onPostResume() called 
D/KeyguardModel( 1384): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1384): createShortcutInfo...
D/KeyguardModel( 1384): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1384): createShortcutInfo...
W/ResourcesManager( 1384): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1384): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
I/art     ( 4333): Explicit concurrent mark sweep GC freed 21275(1264KB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 14MB/18MB, paused 900us total 208.013ms
W/ResourceType( 1384): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1384): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
D/KeyguardModel( 1384): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1384): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1878): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1878): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1384): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1384): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourcesManager( 8296): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8296): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/SQLiteConnectionPool( 4333): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
W/ResourcesManager( 8296): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 1384): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1384): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1384): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1384): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1384): createShortcutInfo...
W/ResourceType( 1384): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1384): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/SystemUI[Framework](  940): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/KeyguardModel( 1384): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1384): createShortcutInfo...
W/PhoneWindowManagerEx(  940): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  940): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  940): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  940): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@22f494ba,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  940): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  940): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  940): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  940): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  940): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  940): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@22f494ba,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  940): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/InputDispatcher(  940): Focus entered window: Window{38f100ac u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1384): handleShortcutListChanged...
D/KeyguardModel( 1384): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1384): createShortcutInfo...
D/KeyguardModel( 1384): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1384): createShortcutInfo...
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
W/ResourceType( 1384): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1384): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1384): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1384): createShortcutInfo...
W/ResourceType( 1384): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1384): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1384): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1384): createShortcutInfo...
W/ResourceType( 1384): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1384): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1384): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1384): createShortcutInfo...
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1384): handleShortcutListChanged...
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1878): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  940): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  940): Got RemoteException sending setActive(false) notification to pid 5705 uid 10316
I/NotificationService(  940): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
I/LGEmail ( 8296): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/BackupManagerService(  940): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  940): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
D/PhoneStatusBar( 1384): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
D/TaskPersister(  940): removeObsoleteFile: deleting file=222_task.xml
I/[SystemUI]NavigationThemeResource( 1384): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1384):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1384): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/art     (  940): Explicit concurrent mark sweep GC freed 11041(852KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 4.838ms total 331.103ms
D/LGEmail ( 8296): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/Timeline(  940): Timeline: Activity_windows_visible id: ActivityRecord{83e2706 u0 com.lge.launcher2/.Launcher t221} time:1296020
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/AndroidRuntime( 8269): Shutting down VM
W/IInputConnectionWrapper( 1878): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1607): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
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
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
I/PackageChangeReceiver( 8296): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager(  940): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8328 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  940): Killing 7741:com.google.android.talk/u0a61 (adj 15): empty #11
I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
W/libprocessgroup(  940): failed to open /acct/uid_10061/pid_7741/cgroup.procs: No such file or directory
E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/AppUp4:AppBoxCP( 8328): onCreate
W/AppUp4:DB( 8328):  [AppBoxDatabaseHelper] construct
E/SQLiteDatabase( 8328): Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
E/SQLiteDatabase( 8328): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 8328): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 8328): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/SQLiteDatabase( 8328): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/SQLiteDatabase( 8328): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/SQLiteDatabase( 8328): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/SQLiteDatabase( 8328): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 8328): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/SQLiteDatabase( 8328): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/SQLiteDatabase( 8328): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/SQLiteDatabase( 8328): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/SQLiteDatabase( 8328): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/SQLiteDatabase( 8328): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 8328): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 8328): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/SQLiteDatabase( 8328): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/SQLiteDatabase( 8328): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/SQLiteDatabase( 8328): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/SQLiteDatabase( 8328): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/SQLiteDatabase( 8328): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/SQLiteDatabase( 8328): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/SQLiteDatabase( 8328): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/SQLiteDatabase( 8328): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 8328): 	at android.os.Looper.loop(Looper.java:135)
E/SQLiteDatabase( 8328): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/SQLiteDatabase( 8328): 	at java.lang.reflect.Method.invoke(Native Method)
E/SQLiteDatabase( 8328): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/SQLiteDatabase( 8328): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/SQLiteDatabase( 8328): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/AndroidRuntime( 8328): Shutting down VM
--------- beginning of crash
E/AndroidRuntime( 8328): FATAL EXCEPTION: main
E/AndroidRuntime( 8328): Process: com.lge.appbox.client, PID: 8328
E/AndroidRuntime( 8328): java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8328): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
E/AndroidRuntime( 8328): 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
E/AndroidRuntime( 8328): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
E/AndroidRuntime( 8328): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/AndroidRuntime( 8328): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/AndroidRuntime( 8328): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 8328): 	at android.os.Looper.loop(Looper.java:135)
E/AndroidRuntime( 8328): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/AndroidRuntime( 8328): 	at java.lang.reflect.Method.invoke(Native Method)
E/AndroidRuntime( 8328): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/AndroidRuntime( 8328): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/AndroidRuntime( 8328): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/AndroidRuntime( 8328): Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 8328): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 8328): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
E/AndroidRuntime( 8328): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
E/AndroidRuntime( 8328): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
E/AndroidRuntime( 8328): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
E/AndroidRuntime( 8328): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/AndroidRuntime( 8328): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
E/AndroidRuntime( 8328): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
E/AndroidRuntime( 8328): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
E/AndroidRuntime( 8328): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
E/AndroidRuntime( 8328): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
E/AndroidRuntime( 8328): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/AndroidRuntime( 8328): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/AndroidRuntime( 8328): 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
E/AndroidRuntime( 8328): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
E/AndroidRuntime( 8328): 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
E/AndroidRuntime( 8328): 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
E/AndroidRuntime( 8328): 	... 11 more
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
E/DropBoxManagerService(  940): Can't write: system_app_crash
E/DropBoxManagerService(  940): java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  940): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/DropBoxManagerService(  940): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/DropBoxManagerService(  940): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
E/DropBoxManagerService(  940): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  940): 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
E/DropBoxManagerService(  940): 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12621)
E/DropBoxManagerService(  940): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  940): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  940): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/DropBoxManagerService(  940): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  940): 	... 5 more
I/ActivityManager(  940): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8352 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/Process ( 8328): Sending signal. PID: 8328 SIG: 9

```
