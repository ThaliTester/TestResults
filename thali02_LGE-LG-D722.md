#### Test 5753124305d96c2_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
I/ActivityManager(  870): Killing 5229:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10009/pid_5229/cgroup.procs: No such file or directory
,I/ActivityManager(  870): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5467 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
--------- beginning of main
I/UpdateIcingCorporaServi( 1940): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/UpdateIcingCorporaServi( 1940): UpdateCorporaTask done [took 167 ms] updated apps [took 167 ms] 
D/Finsky  ( 5467): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/AndroidRuntime( 5484): 
D/AndroidRuntime( 5484): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5484): CheckJNI is OFF
D/Finsky  ( 5467): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 5467): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5467): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5467): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3193): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
D/AndroidRuntime( 5484): Calling main entry com.android.commands.am.Am
V/DownloadManager( 3193): created cursor android.database.sqlite.SQLiteCursor@1b44aa37 on behalf of 5467
I/NotificationManager( 5467): com.android.vending: cancel(1003285959) by com.android.vending
I/ActivityManager(  870): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  870): setTaskToReturnTo : TaskRecord{13ee5f83 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  870): setTaskToReturnTo : TaskRecord{13ee5f83 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  870): AppWindowTokenEx init.. 
D/ContextHelper(  870): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  870): Focus left window: Window{2f2bb11c u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5484): Shutting down VM
I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
D/Ads     ( 5467): Skipping gmscore version check
D/Finsky  ( 5467): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5467): [1] Libraries$2.run: Finished loading 1 libraries.
D/SplitWindow(  870): check instance of lgWin Window{26bb98a u0 Starting com.test.thalitest}
D/Finsky  ( 5467): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  870): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5521 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/Finsky  ( 5467): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  870): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5539 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
D/Finsky  ( 5467): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/ActivityManager(  870): Killing 5251:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
W/ResourcesManager( 5521): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5521): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/HotwordDetector( 1940): Closing mic
I/MicrophoneInputStream( 1940): mic_close com.google.android.apps.gsa.speech.audio.u@b42abd7
V/AudioRecord( 1940): stop()
D/AudioRecord( 1940): AudioRecord->stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioFlinger(  279): Record stopped OK
V/AudioPolicyManager(  279): stopInput() input 16
V/AudioPolicyService(  279): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  279): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  279): ThreadBase::setParameters() routing=0
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb3826000
D/audio_hw_primary(  279): in_standby: enter: stream (0xb546e600) usecase(7: audio-record)
,I/WindowStateAnimator(  870): Starting window displayed
I/SystemUI[Framework](  870): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  870): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  870): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  870): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  870): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@334a1603,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  870): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/libprocessgroup(  870): failed to open /acct/uid_10011/pid_5251/cgroup.procs: No such file or directory
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
V/audio_hw_primary(  279): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  279): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  279): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  279): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  279): disable_audio_route: exit
E/audio_hw_primary(  279): disable_snd_device: enter 144
D/hardware_info(  279): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  279): disable_snd_device: snd_device(144: lg-vr-handset-mic)
D/BarTransitions( 1374): draw background and invalidate : color = 1c000000
D/BarTransitions( 1374): draw background and invalidate : color = 18171717
V/audio_hw_primary(  279): stop_input_stream: exit: status(0)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyManager(  279): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  279): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  279): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  279): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyService(  279): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  279): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  279): setParameters(): io 16, keyvalue hotword_active=0, calling pid 279
V/AudioFlinger(  279): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  279): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  279): in_set_parameters: exit: status(0)
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb3826000
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
I/MultiDex( 5521): VM with version 2.1.0 has multidex support
I/MultiDex( 5521): install
I/MultiDex( 5521): VM has multidex support, MultiDex support library is disabled.
V/AudioRecord( 1940): stop()
V/AudioRecord( 1940): stop()
V/AudioRecord( 1940): stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioPolicyManager(  279): releaseInput() 16
V/AudioPolicyManager(  279): closeInput(16)
V/AudioFlinger(  279): releasing 15 from 1940 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/AudioFlinger(  279): closeInput() 16
V/AudioSystem(  279): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem(  870): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1374): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  279): ThreadBase::exit
V/AudioSystem( 1966): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioFlinger(  279): RecordThread 0xb3826000 exiting
V/AudioSystem( 1745): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1940): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 3146): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 2678): ioConfigChanged() event 4, ioHandle 16
D/audio_hw_primary(  279): adev_close_input_stream: enter:stream_handle(0xb546e600)
D/audio_hw_primary(  279): in_standby: enter: stream (0xb546e600) usecase(7: audio-record)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioPolicyService(  279): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  279): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  279): releaseInput() exit
V/AudioFlinger(  279): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  279): removeClient_l() pid 1940, calling pid 279
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1940): Stopping hotword detection.
I/HotwordRecognitionRnr( 1940): Hotword detection finished
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ContextHelper( 5539): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/WebViewFactory( 5539): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
V/JNIHelp ( 5521): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/LibraryLoader( 5539): Time to load native libraries: 6 ms (timestamps 2558-2564)
I/LibraryLoader( 5539): Expected native library version number "",actual native library version number ""
W/ActivityThread( 5521): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5521): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@31f39017: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5521): Installed default security provider GmsCore_OpenSSL
V/WebViewChromiumFactoryProvider( 5539): Binding Chromium to main looper Looper (main, tid 1) {e77985f}
I/NotificationManager( 5521): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5521): com.google.android.gms: cancel(39789) by com.google.android.gms
I/LibraryLoader( 5539): Expected native library version number "",actual native library version number ""
I/chromium( 5539): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5539): Initializing chromium process, singleProcess=true
W/art     ( 5539): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5539): ApplicationContext is null in ApplicationStatus
D/PackageBroadcastService( 5521): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 5521): Reading stored module config
W/chromium( 5539): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
D/ChimeraCfgMgr( 5521): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5521): Loading module APK com.google.android.play.games
E/libEGL  ( 5539): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,E/libEGL  ( 5539): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5539): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5539): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5539): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5539): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5539): Remote Branch: 
I/Adreno-EGL( 5539): Local Patches: 
I/Adreno-EGL( 5539): Reconstruct Branch: 
V/AudioPolicyService(  279): registerClient() client 0xb551c720, uid 10316
,D/BluetoothManagerService(  870): Message: 20
D/BluetoothManagerService(  870): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@169824d5:true
D/BluetoothAdapterService(86465403)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2cf59629
D/NativeLibraryUtils( 5521): Install completed successfully. count=14 extracted=0
,I/art     ( 5521): CheckpointMarkThreadRoots callback created = 0xaaef9c50
,W/art     ( 5539): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 5539): onDetachedFromWindow called when already detached. Ignoring
,I/art     ( 5521): CheckpointMarkThreadRoots callback created = 0xaaef9c30
,D/SystemWebViewEngine( 5539): CordovaWebView is running on device made by: LGE
W/art     ( 5539): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5539): Attempt to remove local handle scope entry from IRT, ignoring
,I/Activity( 5539): Activity.onPostResume() called 
,D/OpenGLRenderer( 5539): Render dirty regions requested: true
I/OpenGLRenderer( 5539): Initialized EGL, version 1.4
D/OpenGLRenderer( 5539): Enabling debug mode 0
,D/Atlas   ( 5539): Validating map...
,D/ChimeraCfgMgr( 5521): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5521): Module APK com.google.android.play.games already loaded
D/SplitWindow(  870): check instance of lgWin Window{108a3c9a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/chromium( 5539): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/ChimeraCfgMgr( 5521): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 5521): Submit a task: k
,D/ChimeraCfgMgr( 5521): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/InputDispatcher(  870): Focus entered window: Window{108a3c9a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/ChimeraCfgMgr( 5521): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 5521): Processing package: com.test.thalitest
,D/GassUtils( 5521): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5521): Found info for package com.test.thalitest in db.
,D/WearableService( 1731): callingUid 10006, callindPid: 1731
I/ActivityManager(  870): Displayed com.test.thalitest/.MainActivity: +1s336ms
,I/Timeline(  870): Timeline: Activity_windows_visible id: ActivityRecord{3feac500 u0 com.test.thalitest/.MainActivity t222} time:83354
W/InputMethodManagerService(  870): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
E/MDM     ( 1731): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/Timeline( 5539): Timeline: Activity_idle id: android.os.BinderProxy@2933e6ba time:83382
,I/Icing   ( 5521): Storage manager: low false usage 1.76MB avail 2.37GB capacity 4.06GB
,D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/PeopleDatabaseHelper( 5521): cleanUpNonGplusAccounts done.
D/LocationInitializer( 5521): Restart initialization of location
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  870): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5622 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/BindingManager( 5539): Cannot call determinedVisibility() - never saw a connection for the pid: 5539
,W/BaseAppContext( 5521): Using Auth Proxy for data requests.
,I/art     ( 5521): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5521): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
E/BaseAppContext( 5521): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 5521): Using Auth Proxy for data requests.
I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/art     ( 3905): Explicit concurrent mark sweep GC freed 3395(130KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.540ms total 46.728ms
,W/BaseAppContext( 5521): Using Auth Proxy for data requests.
,D/JsMessageQueue( 5539): Set native->JS mode to OnlineEventsBridgeMode
,W/BaseAppContext( 5521): Using Auth Proxy for data requests.
,W/BaseAppContext( 5521): Using Auth Proxy for data requests.
W/BaseAppContext( 5521): Using Auth Proxy for data requests.
W/IcingInternalCorpora( 5521): getNumBytesRead when not calculated.
,W/BaseAppContext( 5521): Using Auth Proxy for data requests.
,W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
,W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5622): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 5521): Background sticky concurrent mark sweep GC freed 16323(1481KB) AllocSpace objects, 14(224KB) LOS objects, 11% free, 12MB/14MB, paused 7.951ms total 91.699ms
,W/GAV2    ( 5622): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/jxcore_app_log( 5539): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426123264
I/Icing   ( 5521): updateResources: need to parse f{com.google.android.gms}
,W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/chromium( 5539): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
D/InitAlarmsService( 3753): Clearing and rescheduling alarms.
,D/CalendarProvider2( 5395): Scheduling check of next Alarm
D/CalendarProvider2( 5395): SCHEDULE_ALARM_REMOVE
W/ActivityManager(  870): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/art     ( 5539): CheckpointMarkThreadRoots callback created = 0x9c1853f0
E/Gmail   ( 5622): Error finding the version of the Email provider.....
E/Gmail   ( 5622): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5622): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5622): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5622): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5622): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5622): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5622): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5622): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5622): We do not support migrating this version of the Email provider.
,I/Gmail   ( 5622): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 5539): CheckpointMarkThreadRoots callback created = 0x9c1853c0
,I/ActivityManager(  870): Killing 3753:com.android.calendar/u0a13 (adj 15): empty #11
I/art     ( 5539): Background partial concurrent mark sweep GC freed 7611(590KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 11MB/19MB, paused 6.917ms total 55.881ms
,I/Gmail   ( 5622): Observing account changes for notifications
,D/ChimeraCfgMgr( 5521): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5521): Module APK com.google.android.play.games already loaded
,W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/libprocessgroup(  870): failed to open /acct/uid_10013/pid_3753/cgroup.procs: No such file or directory
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 5521): Background sticky concurrent mark sweep GC freed 11986(913KB) AllocSpace objects, 10(160KB) LOS objects, 6% free, 13MB/14MB, paused 21.203ms total 138.661ms
,I/ActivityManager(  870): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5691 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  301): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 315us total 22.915ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 21.097ms
,I/art     (  870): Explicit concurrent mark sweep GC freed 23403(1104KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 7.042ms total 242.151ms
V/DownloadManager( 3193): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
V/DownloadManager( 3193): created cursor android.database.sqlite.SQLiteCursor@25a36ba4 on behalf of 5521
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 21.330ms
W/InstanceID/Rpc( 5521): Found 10006
,I/art     ( 3193): Explicit concurrent mark sweep GC freed 5940(338KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 8MB/13MB, paused 755us total 46.143ms
I/Gmail   ( 5622): notifyAccountChanged
I/Gmail   ( 5622): getAccountsCursor
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5622): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5622): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Icing   ( 5521): Internal init done: storage state 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/Gmail   ( 5622): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5622): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/NotificationManager( 5521): com.google.android.gms: cancel(10436) by com.google.android.gms
,V/DownloadManager( 3193): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3193): created cursor android.database.sqlite.SQLiteCursor@3638fd0d on behalf of 5521
,I/art     ( 5521): Background sticky concurrent mark sweep GC freed 7966(565KB) AllocSpace objects, 5(80KB) LOS objects, 6% free, 13MB/14MB, paused 15.073ms total 63.591ms
I/Icing   ( 5521): Post-init done
,D/PhoneMonitor( 5691): Register our PhoneStateListener
V/DownloadManager( 3193): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3193): created cursor android.database.sqlite.SQLiteCursor@386be4c2 on behalf of 5521
I/ActivityManager(  870): Killing 5270:com.android.gallery3d/u0a23 (adj 15): empty #11
,D/PhoneMonitor( 5691): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5691): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5691): [parse] Load xml
V/TelephonyAutoProfiling( 5691): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5691): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5691): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  870): failed to open /acct/uid_10023/pid_5270/cgroup.procs: No such file or directory
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 5521): Checkin interval check for package: unspecified last checkin: 1454422510624 min interval config: 0 actual interval: 6728
,I/CheckinService( 5521): Disabling old GoogleServicesFramework version
,I/Gmail   ( 5622): getAccountsCursor
,I/CheckinService( 5521): Checking schedule, now: 1454422517431 next: 1454422540590
I/CheckinService( 5521): active receiver: disabled
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CalendarProvider2( 5395): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/ActivityManager(  870): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5721 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ContentResolver( 5395): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  870): Killing 5289:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10018/pid_5289/cgroup.procs: No such file or directory
,W/ResourcesManager( 5721): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5721): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5721): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5721): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5721): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5721): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5721): MmsConfig.loadFromResources
E/Babel_SMS( 5721): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5721): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/SensorManager( 5721): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5721): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5721): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5721): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5721): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5721): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5721): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5721): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5721): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5721): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5721): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5721): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5721): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5721): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5721): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5721): found sensor: Motion Accel, handle=46
,W/Settings( 5721): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5721): startup - clean
I/Babel   ( 5721): deleted: false for 0
,I/art     ( 5721): CheckpointMarkThreadRoots callback created = 0xb042d8a0
I/art     ( 5721): CheckpointMarkThreadRoots callback created = 0xb042d880
I/ActivityManager(  870): Process com.lge.bnr (pid 5353) has died
,W/jxcore-log( 5539): Initializing JXcore engine
,W/jxcore-log( 5539): JXcore engine is ready
I/Icing   ( 5521): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,W/Thread-672( 5667): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7405]" dev="sockfs" ino=7405 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-672( 5667): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-672( 5667): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7502]" dev="sockfs" ino=7502 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-672( 5667): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
,W/Thread-672( 5667): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-672( 5667): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26224]" dev="sockfs" ino=26224 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/jxcore-log( 5539): Starting JXcore engine
,W/AudioCapabilities( 5721): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5721): Unsupported mime audio/adpcm
W/AudioCapabilities( 5721): Unsupported mime audio/g726
W/AudioCapabilities( 5721): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5721): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5721): Unsupported mime video/mjpg
W/VideoCapabilities( 5721): Unsupported mime video/theora
,I/ActivityManager(  870): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5749 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Icing   ( 5521): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 5521): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/AudioManager( 5077): getMode name:com.lge.qremote
,W/AudioCapabilities( 5721): Unsupported mime audio/evrc
W/AudioCapabilities( 5721): Unsupported mime audio/qcelp
W/VideoCapabilities( 5721): Unrecognized profile 2130706433 for video/avc
,W/jxcore-log( 5539): Platform android
W/jxcore-log( 5539): 
W/jxcore-log( 5539): Process ARCH arm
W/jxcore-log( 5539): 
,I/AudioManager( 5077): getMode name:com.lge.qremote
I/AudioManager( 5077): getMode name:com.lge.qremote
,W/AudioCapabilities( 5721): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5721): Unsupported mime audio/qcelp
W/AudioCapabilities( 5721): Unsupported mime audio/evrc
W/VideoCapabilities( 5721): Unsupported mime video/mp4v-esdp
D/UEI.SmartControl( 5749): Quickset Services start...
I/AudioManager( 5077): getMode name:com.lge.qremote
I/UEI.SmartControl( 5749): Manufacture = LGE
D/UEI.SmartControl( 5749): File observer start...
,E/UEI.SmartControl( 5749): IR Port is disabled: false
D/UEI.SmartControl( 5749): Starting file observer...
D/UEI.SmartControl( 5749): Extracting JNI libs...
D/UEI.SmartControl( 5749): --- this system supports 32-bit or 64-bit only
I/AudioManager( 5077): getMode name:com.lge.qremote
I/VideoCapabilities( 5721): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5721): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5721): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5721): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  870): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=5767 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
W/VideoCapabilities( 5721): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5721): onServiceConnected
W/Babel   ( 5721): Attempted to change video mute state without an active call.
,I/NotificationManager( 5721): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/DigitalAppWidgetProvider( 5767): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 5767): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@17550cb9
I/ActivityManager(  870): Killing 5315:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,D/UEI.SmartControl( 5749): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5749): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5749): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 5749): --- Selecting new region: 2
,I/UEI.SmartControl( 5749): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5749): Platform has CIR...
D/UEI.SmartControl( 5749): NO CIR support, need to check package...
I/UEI.SmartControl( 5749): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5749): QS Service created
W/libprocessgroup(  870): failed to open /acct/uid_10069/pid_5315/cgroup.procs: No such file or directory
,E/MDM     ( 1731): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/ActivityManager(  870): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager(  870): RTC_WAKEUP set : Alarm{19cffcc8 type 0 when 1454336068932 com.android.providers.contacts} when 1454336068932
V/AlarmManager(  870): ELAPSED_WAKEUP set : Alarm{2743c161 type 2 when 59481 com.google.android.talk} when 59481
,V/AlarmManager(  870): RTC_WAKEUP set : Alarm{125cc147 type 0 when 1454422519059 com.google.android.googlequicksearchbox} when 1454422519059
D/LocationInitializer( 5521): Restart initialization of location
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/UEI.SmartControl( 5749): QS start get config
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
,I/AudioManager( 5077): getMode name:com.lge.qremote
W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
D/UEI.SmartControl( 5749): Loading JNI Libs...
D/UEI.SmartControl( 5749):  configuring local db...
,W/ResourcesManager( 5721): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5721): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/jxcore-log( 5539): JXcore Cordova bridge is ready!
I/jxcore-log( 5539): 
W/jxcore-log( 5539): JXcore engine is started
,I/ActivityManager(  870): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5797 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 5721): com.google.android.talk: cancel(8) by com.google.android.talk
V/JNIHelp ( 5721): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 5797): onCreate
,W/AppUp4:DB( 5797):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5797):  setFingerPrint start
I/AppUp4:DB( 5797):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5797):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5797):  SDK version = 0
I/AppUp4:DB( 5797):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5797): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 5797): onReceive
I/AppUp4:CustModeStarterReceiver( 5797): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 5797): Context : android.app.ReceiverRestrictedContext@17550cb9
D/AppUp4:CustFacade( 5797): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5797): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 5797): begin check event
I/AppUp4:CustModeStarterReceiver( 5797): Event For Nothing, skip.
W/System  ( 5721): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5721): Installed default security provider GmsCore_OpenSSL
I/jxcore-log( 5539): Toggling radios to true
I/jxcore-log( 5539): 
,D/BluetoothAdapter( 5539): enable(): BT is already enabled..!
,I/ActivityManager(  870): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5818 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/WifiServiceImplEx(  870): setWifiEnabled: true pid=5539, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  870): setWifiEnabled: true pid=5539, uid=10316
D/UEI.SmartControl( 5749):  ---- Has DB8: true
,D/WifiServiceImplEx(  870): disconnect pid=5539, uid=10316, packageName=com.test.thalitest
D/UEI.SmartControl( 5749): QS start statue = true Error code = 0
D/WifiServiceImplEx(  870): reconnect pid=5539, uid=10316, packageName=com.test.thalitest
D/UEI.SmartControl( 5749): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 5749): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
I/jxcore-log( 5539): Radios toggled
I/jxcore-log( 5539): 
I/jxcore-log( 5539): My device name is: LGE-LG-D722
I/jxcore-log( 5539): 
D/UEI.SmartControl( 5749): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5749): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5749): IrrcClient ++ 
D/irrcClient( 5749): getIrrcService ++ 
,I/wpa_supplicant( 2832): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/irrcClient( 5749): getIrrcService -- 
D/irrcClient( 5749): IrrcClient -- 
W/irrc_jni( 5749): IRRCPlayer_nativeInit -- 
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
D/UEI.SmartControl( 5749): Services init done
I/wpa_supplicant( 2832): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
D/UEI.SmartControl( 5749): QS Service init finished
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
D/UEI.SmartControl( 5749): QS Service version name: 0.1.73
D/UEI.SmartControl( 5749): QS Service version code: 1073
D/UEI.SmartControl( 5749): Service requested: Control
,I/UEI.SmartControl( 5749): Device manager: loading config....
E/WifiStateMachine(  870): WifiStateMachine: Leaving Connected state
D/WfdsMonitor( 1802): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
D/UEI.SmartControl( 5749): Config is loaded...
E/WifiConfigStore(  870): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LGWifiP2pService(  870): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  275): Clearing all IP addresses on wlan0
D/DhcpStateMachine(  870): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 7
D/UEI.SmartControl( 5749): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 5749): Internal service binding...
D/UEI.SmartControl( 5749): -----IControl: 11
D/UEI.SmartControl( 5749):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 5749): Caller: com.lge.qremote
I/UEI.SmartControl( 5749): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5749): ------------ IControl registerCallback...
I/UEI.SmartControl( 5749): Registering callback...
,V/NativeCrypto( 1731): Read error: ssl=0xb0458c00: I/O error during system call, Connection timed out
W/ResourcesManager( 5818): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5818): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5818): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/UEI.SmartControl( 5749): -----IControl: 19
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/UEI.SmartControl( 5749): Caller: com.lge.qremote
I/UEI.SmartControl( 5749): Registering Services Ready callback...
I/UEI.SmartControl( 5749): Notify client services are ready...
,V/NativeCrypto( 1731): SSL shutdown failed: ssl=0xb0458c00: I/O error during system call, Broken pipe
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 7
D/UEI.SmartControl( 5749): -----IControl: 8
D/ConnectivityService(  870): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  870): ignoring duplicate network state non-change
D/WifiHS20(  870): hidePasspointNotification off =false
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/ConnectivityService(  870): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/UEI.SmartControl( 5749): Caller: com.lge.qremote
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 15:15:19.637 DNS addrs= 0.0.0.0, 0.0.0.0, 
,D/WifiHS20(  870): hidePasspointNotification off =false
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine(  870): Start Disconnecting Watchdog 1
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/wpa_supplicant( 2832): wlan0: CTRL-EVENT-SCAN-STARTED 
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 15:15:19.648 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LGWifiP2pService(  870): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/ActivityManager(  870): Killing 5370:com.google.android.apps.docs/u0a58 (adj 15): empty #11
,D/ConnectivityService(  870): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): ValidatedState{ when=-3ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): DefaultState{ when=-12ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): Forcing reevaluation
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/CommandListener(  275): Clearing all IP addresses on wlan0
,D/ConnectivityService(  870): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  870): disableDataServiceNotify
D/DSQN    (  870): stop dsqn bin
I/ActivityManager(  870): Killing 5336:com.lge.eula/1000 (adj 15): empty #12
,D/ConnectivityService(  870): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/ConnectivityService(  870):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  870):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/DhcpStateMachine(  870): StoppedState
D/DhcpStateMachine(  870): StoppedState{ when=-137ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  870): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  870): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): Disconnected - quitting
D/CSLegacyTypeTracker(  870): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  870): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  870): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,W/libprocessgroup(  870): failed to open /acct/uid_10058/pid_5370/cgroup.procs: No such file or directory
,W/libprocessgroup(  870): failed to open /acct/uid_1000/pid_5336/cgroup.procs: No such file or directory
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
D/ConnectivityService(  870): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  870): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  870): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  870): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  870): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 15:15:19.92 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/QCNEJ   ( 1838): |CORE| No family connected
W/QCNEJ   ( 1838): |CORE| No family connected
I/QCNEJ   ( 1838): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/WifiHS20(  870): hidePasspointNotification off =false
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/NetworkManagementService(  870): Removing idletimer
D/Tethering(  870): MasterInitialState.processMessage what=3
D/Tethering(  870): MasterInitialState.processMessage what=3
D/TelephonyNetworkFactory-1( 1745): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/QCNEJ   ( 1838): |CORE| sendDefaultNwMsg: default = -1
D/WifiNetworkAgent(  870): NetworkAgent: NetworkAgent channel lost
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/TelephonyNetworkFactory-1( 1745):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/NetworkPolicy(  870): [LG_RESTRICTED] !!!isConnected  type  :1
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
V/NetworkPolicy(  870): [LG_RESTRICTED] !!!isConnected  type  :1
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
,W/Settings(  870): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/AppConfig( 5818): Total System Memory = 906309632
I/GalleryUtils( 5818): Application Heap = 96 MB
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 15:15:19.94 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiHS20(  870): hidePasspointNotification off =false
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 15:15:19.943 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WIFI    (  870): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  870):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
D/WifiServerServiceExt(  870): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  870): setSupplicantStateDISCONNECTED
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/AppConfig( 5818): App Tier : NOT_DEF
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiServerServiceExt(  870): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  870): setSupplicantStateSCANNING
D/SystemHelper( 5818): region [EU], country [EU], operator [OPEN], sub-operator []
,D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/ActivityManager(  870): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5844 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  870): Killing 5425:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10086/pid_5425/cgroup.procs: No such file or directory
,W/ResourcesManager( 5844): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5844): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5844): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5844): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5844): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 5844): BUILD Country: EU
I/SystemConfig( 5844): BUILD Operator: OPEN
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/ActivityManager(  870): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5873 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  870): Killing 5467:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10036/pid_5467/cgroup.procs: No such file or directory
I/SystemConfig( 5844): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5844): existFile = false
I/SystemConfig( 5844): canReadFile = false
I/SystemConfig( 5844): systemFeature RCS result false
D/SystemConfig( 5844): refreshRcsSupport() :false
I/LockScreenSettings( 5873): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 5873): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 5873): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5873): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5873): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5873): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  870): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5894 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  870): Killing 5395:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2832): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
W/libprocessgroup(  870): failed to open /acct/uid_10014/pid_5395/cgroup.procs: No such file or directory
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/InputReader(  870): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 15:15:20.826 DNS addrs= 0.0.0.0, 0.0.0.0, 
,W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2832): wlan0: Associated with c0:ff:d4:d3:aa:48
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 15:15:20.836 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshVie,ws 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 15:15:20.864 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 15:15:20.866 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/ResourcesManager( 5894): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/wpa_supplicant( 2832): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
,I/wpa_supplicant( 2832): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/WifiServiceExtension(  870): setVHTCapabilityType  : false
,D/administrator(  870): Handling package changes for user 0
I/WifiServerServiceExt(  870): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  870): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,I/WifiServiceExtension(  870): setSecurityType  : 2
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 15:15:20.934 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-02 15:15:20.938 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/ConnectivityService(  870): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  870): Got NetworkAgent Messenger
,D/ConnectivityService(  870): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  870): NetworkAgent connected
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
E/WifiConfigStore(  870): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  870): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  275): Setting iface cfg
E/WifiStateMachine(  870): Start Dhcp Watchdog 2
D/DhcpStateMachine(  870): StoppedState{ when=-4ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  870): WaitBeforeStartState
,I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/ConnectivityService(  870): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,I/NotificationService(  870): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  870): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  870): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  870): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/LocSvc_java(  870): onReceive
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  870): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  870): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  870): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  870): setSupplicantStateASSOCIATED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  870): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  870): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt(  870): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  870): setSupplicantStateGROUP_HANDSHAKE
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiServerServiceExt(  870): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  870): setSupplicantStateCOMPLETED
D/WifiServerServiceExt(  870): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  870): setSupplicantStateCOMPLETED
,E/WifiStateMachine(  870): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  870): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  870): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3f552db8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3f552db8 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  870): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/BackupManagerService(  870): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/LgDhcpStateMachineHelper(  870): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  870): DHCP Start wake lock is acquired.
V/BackupManagerService(  870): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2c5850a6
D/CommandListener(  275): Setting iface cfg
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  275): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  870): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,D/ConnectivityService(  870): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  870): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  870): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  870): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,E/WifiStateMachine(  870): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  870): ignoring duplicate network state non-change
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 15:15:21.136 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 15:15:21.143 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
D/ConnectivityService(  870): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = false, mWifiLevel = 0
D/ConnectivityService(  870): Adding iface wlan0 to network 101
E/WifiStateMachine(  870): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 15:15:21.156 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1838): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 15:15:21.16 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1838): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_si,gnal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 2
D/WifiHS20(  870): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  870): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
I/[SystemUI]StatusBar.NetworkController( 1374): mWifiConnected = true, mWifiLevel = 2
E/ConnectivityService(  870): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  870): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  870): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at null
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1374): Remote
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  275): netlink response contains error (File exists)
D/ConnectivityService(  870): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/ConnectivityService(  870): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  870): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  870): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  870): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
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
D/WIFI    (  870): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  870):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
E/ConnectivityService(  870): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  870): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  870): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory-1( 1745): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1745):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  870): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  870): [e] list.add(nai) empty : false size: 1
D/Tethering(  870): MasterInitialState.processMessage what=3
D/ConnectivityService(  870): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
W/QCNEJ   ( 1838): |CORE| No family connected
,I/QCNEJ   ( 1838): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1838): |CORE| sendDefaultNwMsg: default = 1
D/ConnectivityService(  870): validation of new default Network = false
D/ConnectivityService(  870): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  870): enableDataServiceNotify 
D/DSQN    (  870): start dsqn bin
D/ConnectivityService(  870): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  870):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  870):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  870): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): [LWD] Start DNSResolver start to wait
I/DSQN    ( 5922): DSQN samuel.seo ver 141203
E/DSQN    ( 5922): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5922): created command queue thread
I/DSQN    ( 5922): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5922): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): [LWD] wait 500ms before dns check
,I/CheckinService( 5521): Checkin interval check for package: unspecified last checkin: 1454422510624 min interval config: 0 actual interval: 10632
,V/NetworkPolicy(  870): [LG_RESTRICTED] checkMobilePolicy_type()
D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/CheckinService( 5521): Checking schedule, now: 1454422521284 next: 1454422540590
I/CheckinService( 5521): active receiver: disabled
,D/DhcpStateMachine(  870): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  870): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  870): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 5929): version 5.5.6 starting
E/dhcpcd  ( 5929): get_duid: Read-only file system
,I/GAV2    ( 5622): Thread[GAThread,5,main]: No campaign data found.
I/art     ( 5521): Background sticky concurrent mark sweep GC freed 2043(132KB) AllocSpace objects, 2(32KB) LOS objects, 1% free, 14MB/14MB, paused 18.415ms total 74.585ms
,I/GAv4-SVC( 5521): Google Analytics 8.4.89 is starting up.
,V/AlarmManager(  870): ELAPSED_WAKEUP set : Alarm{18ac7fdf type 2 when 89665 com.android.providers.calendar} when 89665
,I/dhcpcd  ( 5929): wlan0: rebinding lease of 192.168.1.134
,I/art     ( 5521): Background partial concurrent mark sweep GC freed 21090(1259KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 13MB/21MB, paused 4.471ms total 118.029ms
I/UpdateIcingCorporaServi( 1940): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/ResourcesManager(  870): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  870): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5945 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
I/art     (  870): Explicit concurrent mark sweep GC freed 64047(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.867ms total 315.253ms
,I/UpdateIcingCorporaServi( 1940): UpdateCorporaTask done [took 107 ms] updated apps [took 107 ms] 
I/ActivityManager(  870): Process com.google.android.gm (pid 5622) has died
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): [LWD] DNSResolver start dns
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
,I/System.out(  870): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 5922): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 5922): restart monitoring
D/LGDataListener(  275): argv[0]=dsqncommand
D/LGDataListener(  275): argv[1]=wlan0
D/LGDataListener(  275): argv[2]=1
D/LGDataListener(  275): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  870): DSQM DsqnNotification wlan0  1
D/DSQN    (  870): start to monitor internet connection
I/DSQN    ( 5922): dsqn report finish
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 02 Feb 2016 14:15:21 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454422521850], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454422521830]}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1802): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  870): Validated
D/ConnectivityService(  870): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  870): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  870):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiDataContinuityService(  870): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
D/ConnectivityService(  870):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  870):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  870): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  870): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  870):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  870):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  870): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  870): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  870): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1745): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/WifiServerServiceExt(  870): set CMD_CAPTIVE_CHECK_COMPLETED
D/WIFI    (  870): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1745):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WIFI    (  870):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/ResourceType(  870): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,D/TelephonyIcons( 1374): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1374): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1731): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  870): applying state to connected service
,D/Finsky  ( 5945): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,V/AlarmManager(  870): ELAPSED_WAKEUP set : Alarm{14dacbd5 type 2 when 90311 com.google.android.gms} when 90311
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ConnectivityService(  870): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  870): Process com.lge.qremote (pid 5077) has died
,D/Finsky  ( 5945): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5945): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5945): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5945): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Finsky  ( 5945): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5945): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 5945): Skipping gmscore version check
,V/DownloadManager( 3193): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3193): created cursor android.database.sqlite.SQLiteCursor@15afb2d3 on behalf of 5945
D/PackageBroadcastService( 5521): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 5945): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  870): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  870): identical MTU - not setting
D/Nat464Xlat(  870): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  870): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  870):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  870):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  870): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  870): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  870): enableDataServiceNotify 
D/DSQN    (  870): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1374): CM callback handler got msg 524295
I/ActivityManager(  870): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5991 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/DSQN    (  870): dsqn is running restart
I/PackageBroadcastService( 5521): Null package name or gms related package.  Ignoreing.
I/DSQN    ( 5997): DSQN samuel.seo ver 141203
E/DSQN    ( 5997): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5997): created command queue thread
,I/DSQN    ( 5997): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5997): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-65 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 15:15:22.589 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/Icing   ( 5521): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 5945): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ResourcesManager( 5991): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  870): Message: 20
D/BluetoothManagerService(  870): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@33e668a8:true
,D/BluetoothAdapterService(86465403)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2cf59629
,D/BluetoothAdapterService(86465403)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2cf59629
V/LGMDMManager( 5991): Create singleton instance
,I/dhcpcd  ( 5929): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 5929): wlan0: leased 192.168.1.134 for 86400 seconds
I/AudioManager( 5991): getMode name:com.lge.qremote
,D/ConnectivityService(  870): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  870): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  870): onReceive
D/LocSvc_java(  870): got connectivity action
,D/LocSvc_java(  870): broadcast - no network connections
D/LocSvc_java(  870): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  870): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  870): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  870): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  870): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  870): onReceive
D/LocSvc_java(  870): got connectivity action
D/LocSvc_java(  870): broadcast - no network connections
D/LocSvc_java(  870): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  870): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  870): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  870): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  870): ignore wifi update if we are not in OPENING or CLOSING
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/GpsLocationProvider(  870): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  870): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  870): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  870): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/UEI.SmartControl( 5749): -----IControl: 11
,D/UEI.SmartControl( 5749): Caller: com.lge.qremote
D/UEI.SmartControl( 5749): ------------ IControl registerCallback...
I/UEI.SmartControl( 5749): Registering callback...
D/UEI.SmartControl( 5749): -----IControl: 19
D/UEI.SmartControl( 5749): Caller: com.lge.qremote
I/UEI.SmartControl( 5749): Registering Services Ready callback...
I/UEI.SmartControl( 5749): Notify client services are ready...
I/AudioManager( 5991): getMode name:com.lge.qremote
D/UEI.SmartControl( 5749): -----IControl: 8
,D/UEI.SmartControl( 5749): Caller: com.lge.qremote
V/SetupWizard( 5691): Connected to Gservices successfully
,I/ActivityManager(  870): Killing 5767:com.lge.clock/u0a10 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10010/pid_5767/cgroup.procs: No such file or directory
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/LocationInitializer( 5521): Restart initialization of location
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1731): [119] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
,I/System.out( 1731): propertyValue:false
I/ActivityManager(  870): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6048 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  301): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 20.990ms
,I/DSQN    ( 5997): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5997): restart monitoring
D/LGDataListener(  275): argv[0]=dsqncommand
D/LGDataListener(  275): argv[1]=wlan0
D/LGDataListener(  275): argv[2]=1
D/LGDataListener(  275): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5997): dsqn report finish
D/DSQN    (  870): DSQM DsqnNotification wlan0  1
D/DSQN    (  870): start to monitor internet connection
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  870): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  870): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  870): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  870): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  870): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  870): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  870): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  870): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  870): RunningState
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 30.311ms
W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 20.997ms
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6048): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6048): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  870): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 6048): Observing account changes for notifications
,W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 6048): Error finding the version of the Email provider.....
E/Gmail   ( 6048): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6048): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6048): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6048): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6048): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6048): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6048): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6048): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6048): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6048): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  870): Killing 5797:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/Icing   ( 5521): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,W/libprocessgroup(  870): failed to open /acct/uid_10011/pid_5797/cgroup.procs: No such file or directory
,I/Icing   ( 5521): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/QCNEJ   ( 1838): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1838): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-63 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-02 15:15:24.026 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  870): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6099 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/WifiInternetCheck(  870): Single check msg out of sync, ignoring.
,W/ResourcesManager( 6099): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ConnectivityService(  870): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/GpsLocationProvider(  870): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1374): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  870): onReceive
D/LocSvc_java(  870): got connectivity action
D/LocSvc_java(  870): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  870): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  870): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  870): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  870): ignore wifi update if we are not in OPENING or CLOSING
,I/Gmail   ( 6048): notifyAccountChanged
D/GpsLocationProvider(  870): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
I/Gmail   ( 6048): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6048): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/CalendarApplication( 6099): CalendarApplication.onCreate()
,I/Gmail   ( 6048): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/PreferenceKeysParser( 6099): [debug_displayParseInfos] preference keys.size() = 44
I/Gmail   ( 6048): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PreferenceKeysParser( 6099): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@33647e80, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@17550cb9, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@292cf8fe, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@e77985f, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@11d302ac, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1eb0bb75, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1bdba70a, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@5275b7b, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2bc39d98, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@37de99f1, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1e1529d6, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@33463457, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@b20fb44, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2431e42d, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@4920d62, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@2e0fbef3, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@bd487b0, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2cf59629, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@5079dae, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@18dd574f, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@1cf26edc, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@b286be5, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@2933e6ba, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@942196b, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@28a59cc8, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@ef8e161, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@26a9b486, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@10e6e147, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@edbbd74, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@301329d, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@275c9312, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@9264ae3, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@1eb13ce0, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@7435b99, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@eecce5e, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3c68b23f, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3a9d470c, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@1fe51855, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@8b3726a, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@940335b, lg_preferences_alerts_vibratetype=com.androi,d.calendar.adaptation.PreferenceKey$KeyData@135dc7f8, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@33abe4d1, lg_p
I/Gmail   ( 6048): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/art     ( 3905): Explicit concurrent mark sweep GC freed 3296(133KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 459us total 61.654ms
I/NotificationManager( 1940): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,D/GeneralPreferenceUtils( 6099): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
,D/Config  ( 6099): [init]
I/Config  ( 6099): LGCalendar ver.4.40.17
I/Config  ( 6099): start check model
I/Config  ( 6099): start check native_ca
I/Config  ( 6099): Config Operator=OPEN, Country=EU
,D/Config  ( 6099): [setDefaultValuesToPref]
D/Config  ( 6099): [parseProfiles]
D/ProfilesParser( 6099): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6099): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6099): [updateProfiletoCountryInfo]
D/GeneralPreference( 6099): [checkAndMigrateOldPreference]
D/AlertReceiver( 6099): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/art     ( 1731): Explicit concurrent mark sweep GC freed 32597(1986KB) AllocSpace objects, 15(240KB) LOS objects, 40% free, 13MB/22MB, paused 2.261ms total 134.501ms
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  870): Process com.android.contacts (pid 5844) has died
,I/Gmail   ( 6048): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 5749): Internal timer expired: 1
I/InitNotificationRingtoneService( 6099): Start InitializeAlertRingtoneService.onHandleIntent
,W/HolidayIntentService( 6099): onHandleIntent
,D/HolidayDataLoader( 6099): readJsonAsset : holiday.json
I/AlertUtils( 6099): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,E/AgendaWidgetManager( 6099): [updateWidgets] 
,D/MonthWidgetProvider( 6099): [onReceive]
D/CalendarWidgetProvider( 6099): [onReceive]
D/CalendarWidgetProvider( 6099): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/AlertService( 6099): 0 Action = android.intent.action.PROVIDER_CHANGED
D/CalendarTypeController( 6099): [onCreate] mContext.getPackageName() = com.android.calendar
I/AlertUtils( 6099): [getCalendarNotiSoundURIFromCursor] getCount()= 21
D/WeekWidgetProvider( 6099): [onReceive]
D/CalendarWidgetProvider( 6099): [onReceive]
D/CalendarWidgetProvider( 6099): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,E/HolidayIntentService( 6099): onHandleIntent:holiday data empty
,I/art     (  870): Explicit concurrent mark sweep GC freed 50038(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.152ms total 164.825ms
,I/AlertUtils( 6099): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
D/CalendarTypeController( 6099): [onCreate] mContext.getPackageName() = com.android.calendar
,I/AlertUtils( 6099): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6099): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6099): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 6099): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6099): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6099): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6099): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6099): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6099): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6099): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6099): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/ActivityManager(  870): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6130 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/AlertUtils( 6099): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 6099): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6099): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6099): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6099): set default noti to content://media/internal/audio/media/38
,W/ResourcesManager( 5721): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5721): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/InitNotificationRingtoneService( 6099): End InitializeAlertRingtoneService.onHandleIntent
,V/AlarmManager(  870): RTC_WAKEUP set : Alarm{19cc9626 type 0 when 1454422525016 com.android.vending} when 1454422525016
,D/Finsky  ( 5945): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  870): android: cancelAsUser(2) by android
,D/libc-netbsd( 5945): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5945): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5945): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5945): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
W/ResourcesManager( 6130): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6130): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6130): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6130): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6130): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
,I/System.out( 5945): propertyValue:false
D/libc-netbsd( 5945): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5945): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5945): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5945): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/IndexDatabaseHelper( 6130): Using schema version: 115
I/IndexDatabaseHelper( 6130): Index is fine
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out(  870): propertyValue:false
,D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  870): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  870): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out(  870): propertyValue:false
,V/WifiInternetCheck(  870): isHttpConnectionAvailable - We got a valid response : 204
V/WiFiOffLoadBroadcast( 6130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/ActivityManager(  870): Process com.android.gallery3d (pid 5818) has died
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  870): android: cancelAsUser(2) by android
,D/WiFiOffLoadBroadcast( 6130): MCCMNC not supported: null
I/ActivityManager(  870): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6160 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/qtaguid ( 5945): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5945): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5945): untagSocket(41) failed with errno -22
D/Finsky  ( 5945): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/PCSuite ( 6160): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6160): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6160): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  870): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6181 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  870): android: cancelAsUser(2) by android
,V/WiFiOffLoadBroadcast( 6130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6130): MCCMNC not supported: null
I/PCSuite ( 6160): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6160): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6160): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/AudioManager( 5991): getMode name:com.lge.qremote
V/WiFiOffLoadBroadcast( 6130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/ResourcesManager( 6181): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6181): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/WiFiOffLoadBroadcast( 6130): MCCMNC not supported: null
I/PCSuite ( 6160): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6160): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6160): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6130): MCCMNC not supported: null
I/PCSuite ( 6160): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6160): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6160): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6130): MCCMNC not supported: null
I/ActivityManager(  870): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6210 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 5721): com.google.android.talk: cancel(8) by com.google.android.talk
,I/MultiDex( 6181): VM with version 2.1.0 has multidex support
I/MultiDex( 6181): install
I/MultiDex( 6181): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6181): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AppUp4:AppBoxCP( 6210): onCreate
W/AppUp4:DB( 6210):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6210):  setFingerPrint start
I/AppUp4:DB( 6210):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6210):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6210):  SDK version = 0
,I/AppUp4:DB( 6210):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6210): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6210): onReceive
I/AppUp4:CustModeStarterReceiver( 6210): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6210): Context : android.app.ReceiverRestrictedContext@17550cb9
D/AppUp4:CustFacade( 6210): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6210): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6210): begin check event
I/AppUp4:CustModeStarterReceiver( 6210): Event For Nothing, skip.
,I/qtaguid ( 5945): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5945): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5945): untagSocket(41) failed with errno -22
W/ActivityThread( 6181): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6181): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a055d09: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6181): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  870): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6232 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/NotificationManager( 6181): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6181): com.google.android.gms: cancel(39789) by com.google.android.gms
,D/ChimeraCfgMgr( 6181): Reading stored module config
,W/ResourcesManager( 6232): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6232): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6232): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/ChimeraCfgMgr( 6181): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/AppConfig( 6232): Total System Memory = 906309632
I/GalleryUtils( 6232): Application Heap = 96 MB
,I/AppConfig( 6232): App Tier : NOT_DEF
D/SystemHelper( 6232): region [EU], country [EU], operator [OPEN], sub-operator []
D/CAR.SERVICE( 6181): Connecting to CarCallService...
,D/NativeLibraryUtils( 6181): Install completed successfully. count=14 extracted=0
,I/art     ( 6181): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6181): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5945): CheckpointMarkThreadRoots callback created = 0xb05687d0
,I/ActivityManager(  870): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6255 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/art     ( 5945): CheckpointMarkThreadRoots callback created = 0xb05687a0
,D/CAR.SERVICE( 6181): com.google.android.projection.gearhead isn't installed.
,I/ActivityManager(  870): Process com.google.android.gm (pid 6048) has died
,D/CAR.TEL.Service( 6181): Creating a new CarCallService.
,W/ResourcesManager( 6255): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6255): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6255): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6255): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6255): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/CAR.TEL.PhoneAdapter( 6181): Creating a new PhoneAdapter instance
,W/ActivityManager(  870): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6181): setListener: com.google.android.gms.car.dn@3f213b6c
W/ActivityManager(  870): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6181): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6181): Starting CarCallService with initial phone null
I/NotificationManager( 6181): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6181): Package validated; name: com.android.vending
,I/SystemConfig( 6255): BUILD Country: EU
,I/SystemConfig( 6255): BUILD Operator: OPEN
I/NotificationManager( 5945): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 5945): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/LockScreenSettings( 5873): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5873): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5873): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5873): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5873): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/SystemConfig( 6255): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6255): existFile = false
I/SystemConfig( 6255): canReadFile = false
I/SystemConfig( 6255): systemFeature RCS result false
D/SystemConfig( 6255): refreshRcsSupport() :false
I/ActivityManager(  870): Killing 5691:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1940): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/UpdateIcingCorporaServi( 1940): UpdateCorporaTask done [took 36 ms] updated apps [took 36 ms] 
,W/libprocessgroup(  870): failed to open /acct/uid_10038/pid_5691/cgroup.procs: No such file or directory
,V/WiFiOffLoadBroadcast( 6130): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/PackageBroadcastService( 5521): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/WiFiOffLoadBroadcast( 6130): Not supported operator for automatic switch
I/PackageBroadcastService( 5521): Null package name or gms related package.  Ignoreing.
V/WiFiOffLoadBroadcast( 6130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6130): MCCMNC not supported: null
I/Icing   ( 5521): updateResources: need to parse f{com.google.android.gms}
V/WiFiOffLoadBroadcast( 6130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6130): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6130): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6130): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6130): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6130): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6130): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6130): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6130): MCCMNC not supported: null
I/PCSuite ( 6160): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6160): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6130): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6130): MCCMNC not supported: null
,I/PCSuite ( 6160): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6160): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 95582779499; DSPS: 3223433; Offset : -2799314272
,I/ActivityManager(  870): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6289 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6289): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6289): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@380153b2
,D/CalendarProvider2( 6289): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6289): Created com.android.providers.calendar.CalendarAlarmManager@e77985f(com.android.providers.calendar.CalendarProvider2@380153b2)
D/CalendarProviderBroadcastReceiver( 6289): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6289): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6289): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6289): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6289): [getOrCreateCalendarAlarmManager]
I/ActivityManager(  870): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6308 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  870): android: cancelAsUser(2) by android
D/CalendarProvider2( 6289): [IntentService] Release Lock
,D/CalendarProvider2( 6289): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  870): Killing 6210:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10011/pid_6210/cgroup.procs: No such file or directory
D/PhoneMonitor( 6308): Register our PhoneStateListener
,I/ActivityManager(  870): Killing 6232:com.android.gallery3d/u0a23 (adj 15): empty #11
,D/PhoneMonitor( 6308): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6308): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6308): [parse] Load xml
,V/TelephonyAutoProfiling( 6308): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6308): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6308): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/qtaguid ( 5945): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5945): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5945): untagSocket(41) failed with errno -22
W/libprocessgroup(  870): failed to open /acct/uid_10023/pid_6232/cgroup.procs: No such file or directory
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 5521): Checkin interval check for package: unspecified last checkin: 1454422510624 min interval config: 0 actual interval: 17457
I/ActivityManager(  870): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6331 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 5521): Checking schedule, now: 1454422528119 next: 1454422540590
I/CheckinService( 5521): active receiver: disabled
,W/ResourcesManager( 5945): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5945): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Icing   ( 5521): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
W/ResourcesManager( 5945): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Icing   ( 5521): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/jxcore-log( 5539): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5539): 
,I/art     (  870): Explicit concurrent mark sweep GC freed 18478(884KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.048ms total 143.329ms
,I/MusicStore( 6331): Database version: 120
,I/ActivityManager(  870): Process com.google.android.apps.plus (pid 5894) has died
,D/Finsky  ( 5945): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager(  870): RTC_WAKEUP set : Alarm{89ceced type 0 when 1454422528652 com.android.vending} when 1454422528652
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,D/WearableService( 1731): callingUid 10006, callindPid: 1731
W/ContextImpl( 6331): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/DeviceConnectionService( 1731): client connected with version: 8296000
D/Finsky  ( 5945): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5945): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  870): Killing 6255:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10018/pid_6255/cgroup.procs: No such file or directory
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6331): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6331): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6331): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6331): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6331): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6331): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6331): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f295188: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6331): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6331): GMSCore installation verified
I/ConfigStore( 6331): Config Database version: 1
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/AlarmManager(  870): RTC_WAKEUP set : Alarm{17598e21 type 0 when 1454422529228 com.google.android.googlequicksearchbox} when 1454422529228
,I/MediaRouter( 6331): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6331): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6331): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  870): Killing 5873:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10069/pid_5873/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6331): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  870): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6390 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 24.608ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.370ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 23.227ms
,I/GHttpClientFactory( 6331): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6331): Using platform SSLCertificateSocketFactory
I/jxcore-log( 5539): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5539): 
,D/AlertService( 6099): Beginning updateAlertNotification
,D/AlertService( 6099): No fired or scheduled alerts
,I/NotificationManager( 6099): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6331): com.google.android.music: cancel(1061) by com.google.android.music
I/NotificationManager( 6099): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6099): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6099): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6099): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6099): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6099): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6099): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6099): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6099): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6099): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6099): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6099): com.android.calendar: cancel(12) by com.android.calendar
W/ResourcesManager( 6390): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6390): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6390): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/NotificationManager( 6099): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6099): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6099): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6099): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6099): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6099): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6099): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6099): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6099): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/ActivityManager(  870): Killing 6130:com.android.settings/1000 (adj 15): empty #11
I/jxcore-log( 5539): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5539): 
,I/jxcore-log( 5539): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
I/jxcore-log( 5539): 
I/jxcore-log( 5539): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5539): 
,W/libprocessgroup(  870): failed to open /acct/uid_1000/pid_6130/cgroup.procs: No such file or directory
,D/AlarmScheduler( 6099): No events found starting within 1 week.
I/LGEmail ( 6390): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6390): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ActivityManager(  870): Killing 6099:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10013/pid_6099/cgroup.procs: No such file or directory
,D/eas_req ( 6390): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  870): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6424 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/HubEmail( 6390): JNI_OnLoad()
I/HubEmail( 6390): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6390): registerNatives()
I/HubEmail( 6390): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6390): registerNativeMethods()
I/HubEmail( 6390): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6390): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  870): Killing 5749:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5991): android.os.DeadObjectException
,W/System.err( 5991): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5991): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5991): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5991): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5991): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5991): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5991): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5991): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5991): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5991): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5991): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5991): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5991): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5991): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5991): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5991): android.os.DeadObjectException
W/System.err( 5991): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5991): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5991): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5991): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5991): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5991): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5991): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5991): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5991): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5991): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5991): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5991): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5991): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5991): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5991): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  870): failed to open /acct/uid_10089/pid_5749/cgroup.procs: No such file or directory
W/ActivityManager(  870): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ThermalEngine(  292): Sensor:pa_therm0:34000 mC
W/Settings( 6390): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  870): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6446 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LGDMClient( 6424): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6424): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6424): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6424): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6424): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6424): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/UEI.SmartControl( 6446): Quickset Services start...
,D/LGDMClient( 6424): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/UEI.SmartControl( 6446): Manufacture = LGE
D/UEI.SmartControl( 6446): File observer start...
I/ActivityManager(  870): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6469 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
E/UEI.SmartControl( 6446): IR Port is disabled: false
D/UEI.SmartControl( 6446): Starting file observer...
D/UEI.SmartControl( 6446): Extracting JNI libs...
D/UEI.SmartControl( 6446): --- this system supports 32-bit or 64-bit only
,I/LGDMClient( 6424): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 6424): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6424): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6424): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6424): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6424): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6424): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  870): Killing 6160:com.lge.sync/1000 (adj 15): empty #11
,I/AppUp4:AppBoxCP( 6469): onCreate
,W/AppUp4:DB( 6469):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6469):  setFingerPrint start
I/AppUp4:DB( 6469):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
D/UEI.SmartControl( 6446): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6446): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 6446): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/AppUp4:DB( 6469):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6469):  SDK version = 0
I/AppUp4:DB( 6469):  beforefinger == newfinger no write in DB
I/UEI.SmartControl( 6446): --- Selecting new region: 2
I/UEI.SmartControl( 6446): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6446): Platform has CIR...
,D/UEI.SmartControl( 6446): NO CIR support, need to check package...
I/UEI.SmartControl( 6446): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6446): QS Service created
W/libprocessgroup(  870): failed to open /acct/uid_1000/pid_6160/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6469): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6469): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6469): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6469): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6469): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6469): onReceive
I/AppUp4:CustModeStarterReceiver( 6469): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6469): Context : android.app.ReceiverRestrictedContext@11d302ac
D/AppUp4:CustFacade( 6469): isCustomizationCompleted : false
E/UEI.SmartControl( 6446): QS start get config
D/AppUp4:CustFacade( 6469): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6469): begin check event
I/AppUp4:CustModeStarterReceiver( 6469): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6469): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6469): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6469): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6469): handleAsyncCustNotification do not startCustService
I/ActivityManager(  870): Killing 5991:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 6446): Loading JNI Libs...
,D/UEI.SmartControl( 6446):  configuring local db...
W/libprocessgroup(  870): failed to open /acct/uid_10106/pid_5991/cgroup.procs: No such file or directory
,I/ActivityManager(  870): Killing 5721:com.google.android.talk/u0a61 (adj 15): empty #11
I/LgeMiscReceiver( 3146): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3146): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3146): networkInfo.isConnected() = false
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  870): failed to open /acct/uid_10061/pid_5721/cgroup.procs: No such file or directory
,D/MobileConnectivityChangeReceiver( 6308): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6308): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 3193): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3193): DownloadService onCreate
I/DownloadManager( 3193): in removeSpuriousFiles
V/DownloadManager( 3193): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3193): created cursor android.database.sqlite.SQLiteCursor@267d9e10 on behalf of 3193
I/NotificationManager( 3193): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/UEI.SmartControl( 6446):  ---- Has DB8: true
I/DownloadManager( 3193): in trimDatabase
,V/DownloadManager( 3193): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3193): created cursor android.database.sqlite.SQLiteCursor@3a055d09 on behalf of 3193
D/UEI.SmartControl( 6446): QS start statue = true Error code = 0
D/UEI.SmartControl( 6446): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6446): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6446): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6446): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6446): IrrcClient ++ 
D/irrcClient( 6446): getIrrcService ++ 
D/irrcClient( 6446): getIrrcService -- 
D/irrcClient( 6446): IrrcClient -- 
W/irrc_jni( 6446): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6446): Services init done
I/ActivityManager(  870): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6502 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3193): DownloadService onStartCommand
I/UEI.SmartControl( 6446): Device manager: loading config....
V/DownloadManager( 3193): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,D/UEI.SmartControl( 6446): QS Service init finished
V/DownloadManager( 3193): created cursor android.database.sqlite.SQLiteCursor@a868b3c on behalf of 3193
D/UEI.SmartControl( 6446): QS Service version name: 0.1.73
D/UEI.SmartControl( 6446): QS Service version code: 1073
D/UEI.SmartControl( 6446): Service requested: Control
D/UEI.SmartControl( 6446): Config is loaded...
,D/UEI.SmartControl( 6446):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6446): Notify AllClients services are ready: 0
,V/DownloadManager( 3193): DownloadService onDestroy
D/UEI.SmartControl( 6446): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6446): Service.onUnbind: IControl
D/UEI.SmartControl( 6446): Service.onDestroy
D/UEI.SmartControl( 6446): Shutdown IRRCPlayer... 
,W/irrc_jni( 6446): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6446): ~IrrcClient ++ 
,D/irrcClient( 6446): ~IrrcClient -- 
W/irrc_jni( 6446): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6446): Blaster closed
D/UEI.SmartControl( 6446): Blaster closed
D/UEI.SmartControl( 6446): Shut down QS...
D/UEI.SmartControl( 6446): Stopped file observer...
I/UEI.SmartControl( 6446): QS lib stop result = true
D/UEI.SmartControl( 6446): QS shutdown complete
D/UEI.SmartControl( 6446): QS Service created
I/ActivityManager(  870): Killing 6289:com.android.providers.calendar/u0a14 (adj 15): empty #11
,E/UEI.SmartControl( 6446): QS start get config
D/UEI.SmartControl( 6446):  configuring local db...
,W/libprocessgroup(  870): failed to open /acct/uid_10014/pid_6289/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2669): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:15:31
D/UpdateThreadPoolManager( 2669): 2 : This is isUpdating : false
D/WeatherAncestor( 2669): connectivity changed - connection : true
D/Weather_cast( 2669): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2669): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:15:31
D/WeatherService( 2669): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  870): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6520 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  870): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2669): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2669): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2669): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/UEI.SmartControl( 6446):  ---- Has DB8: true
,D/UEI.SmartControl( 6446): QS start statue = true Error code = 0
D/UEI.SmartControl( 6446): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6446): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6446): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6446): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6446): IrrcClient ++ 
D/irrcClient( 6446): getIrrcService ++ 
D/irrcClient( 6446): getIrrcService -- 
D/irrcClient( 6446): IrrcClient -- 
W/irrc_jni( 6446): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6446): Services init done
I/UEI.SmartControl( 6446): Device manager: loading config....
D/UEI.SmartControl( 6446): QS Service init finished
D/UEI.SmartControl( 6446): Config is loaded...
D/UEI.SmartControl( 6446): QS Service version name: 0.1.73
D/UEI.SmartControl( 6446): QS Service version code: 1073
D/UEI.SmartControl( 6446): Service requested: Control
I/ActivityManager(  870): Killing 6181:com.google.android.gms:car/u0a6 (adj 15): empty #11
,W/ResourcesManager( 6520): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6446):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6446): Notify AllClients services are ready: 0
,W/libprocessgroup(  870): failed to open /acct/uid_10006/pid_6181/cgroup.procs: No such file or directory
,W/ActivityManager(  870): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
,E/ActivityThread( 6446): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@5275b7b that was originally bound here
E/ActivityThread( 6446): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@5275b7b that was originally bound here
E/ActivityThread( 6446): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6446): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6446): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6446): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6446): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6446): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6446): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6446): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6446): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6446): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6446): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6446): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6446): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6446): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6446): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6446): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6446): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6446): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6446): Internal service binding...
,I/Babel_SMS( 6520): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6520): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6520): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6520): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6520): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6520): MmsConfig.loadFromResources
E/Babel_SMS( 6520): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6520): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6520): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6520): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6520): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6520): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6520): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6520): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6520): found sensor: LGE Rotation Vector Sensor, handle=36
,D/SensorManager( 6520): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6520): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6520): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6520): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6520): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6520): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6520): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6520): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6520): found sensor: Motion Accel, handle=46
W/Settings( 6520): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6520): startup - clean
I/art     ( 6520): CheckpointMarkThreadRoots callback created = 0xaaf404c0
I/Babel   ( 6520): deleted: false for 0
,I/art     ( 6520): CheckpointMarkThreadRoots callback created = 0xaaf404a0
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  870): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6558 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/AudioCapabilities( 6520): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6520): Unsupported mime audio/adpcm
W/AudioCapabilities( 6520): Unsupported mime audio/g726
,W/AudioCapabilities( 6520): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6520): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6520): Unsupported mime video/mjpg
,W/VideoCapabilities( 6520): Unsupported mime video/theora
W/AudioCapabilities( 6520): Unsupported mime audio/evrc
W/AudioCapabilities( 6520): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6520): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6520): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6520): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6520): Unsupported mime audio/evrc
W/VideoCapabilities( 6520): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6520): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6520): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6520): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6520): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6520): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6520): onServiceConnected
,W/Babel   ( 6520): Attempted to change video mute state without an active call.
I/NotificationManager( 6520): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6520): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6520): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6520): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6520): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 6520): propertyValue:false
I/ActivityManager(  870): Process com.android.vending (pid 5945) has died
,I/Babel   ( 6520): connection state changed from UNKNOWN to CONNECTED
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6558): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6558): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6558): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6558): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6558): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6558):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6558):   adb logcat -s GAv4
W/GAv4    ( 6558): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6558): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6558): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/WebViewFactory( 6558): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6558): Time to load native libraries: 3 ms (timestamps 1256-1259)
,I/LibraryLoader( 6558): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 6558): Binding Chromium to main looper Looper (main, tid 1) {18c29a79}
,I/LibraryLoader( 6558): Expected native library version number "",actual native library version number ""
I/chromium( 6558): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 6558): Initializing chromium process, singleProcess=true
,W/art     ( 6558): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6558): ApplicationContext is null in ApplicationStatus
W/chromium( 6558): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6558): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6558): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6558): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6558): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6558): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6558): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6558): Remote Branch: 
I/Adreno-EGL( 6558): Local Patches: 
I/Adreno-EGL( 6558): Reconstruct Branch: 
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AudioPolicyService(  279): registerClient() client 0xb551c660, uid 10079
,W/AudioManagerAndroid( 6558): Requires BLUETOOTH permission
I/NSApplication( 6558): Starting up...
,I/ActivityManager(  870): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6621 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  870): Killing 6331:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10081/pid_6331/cgroup.procs: No such file or directory
,I/ActivityManager(  870): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6648 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  870): Killing 6390:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10021/pid_6390/cgroup.procs: No such file or directory
,W/ResourcesManager( 6648): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/iu.SyncManager( 5521): SYNC; picasa accounts
,D/NetworkLogImpl( 5521): Loaded NetworkSpeedPredictor
,I/iu.Environment( 5521): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/ActivityManager(  870): Killing 6424:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/iu.UploadsManager( 5521): num queued entries: 0
I/iu.UploadsManager( 5521): num updated entries: 0
I/iu.SyncManager( 5521): NEXT; no task
,W/libprocessgroup(  870): failed to open /acct/uid_1000/pid_6424/cgroup.procs: No such file or directory
,I/ActivityManager(  870): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6683 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  870): Explicit concurrent mark sweep GC freed 20704(984KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.994ms total 156.967ms
,I/rmt_storage(  269): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  269): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  269): wakelock acquired: 1, error no: 42
,I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  269): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  269): 
I/rmt_storage(  269): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/MusicStore( 6683): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6683): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6683): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6683): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6683): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6683): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6683): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6683): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6683): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f295188: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6683): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6683): GMSCore installation verified
,I/ConfigStore( 6683): Config Database version: 1
,I/ThermalEngine(  292): Sensor:pa_therm0:34000 mC
,I/MediaRouter( 6683): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6683): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6683): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6683): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  870): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6721 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6683): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6683): Using platform SSLCertificateSocketFactory
E/UEI.SmartControl( 6446): file observer is disposed!
W/ResourcesManager( 6721): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6721): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6721): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  870): Killing 6469:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10011/pid_6469/cgroup.procs: No such file or directory
,I/LGEmail ( 6721): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/NotificationManager( 6683): com.google.android.music: cancel(1061) by com.google.android.music
D/LGEmail ( 6721): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6721): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  870): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6752 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 21.509ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 20.641ms
,I/HubEmail( 6721): JNI_OnLoad()
I/HubEmail( 6721): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6721): registerNatives()
I/HubEmail( 6721): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6721): registerNativeMethods()
I/HubEmail( 6721): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 6721): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  870): Killing 6308:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 26.698ms
,W/libprocessgroup(  870): failed to open /acct/uid_10038/pid_6308/cgroup.procs: No such file or directory
,W/Settings( 6721): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6752): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6752): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6752): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6752): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6752): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6752): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6752): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6752): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  870): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6776 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6752): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 6752): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6752): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
,D/LGDMClient( 6752): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6752): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6752): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  870): Killing 6446:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/AppUp4:AppBoxCP( 6776): onCreate
,W/AppUp4:DB( 6776):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6776):  setFingerPrint start
I/AppUp4:DB( 6776):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6776):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6776):  SDK version = 0
I/AppUp4:DB( 6776):  beforefinger == newfinger no write in DB
,W/libprocessgroup(  870): failed to open /acct/uid_10089/pid_6446/cgroup.procs: No such file or directory
D/AppUp4:AppBoxApplication( 6776): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6776): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6776): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6776): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6776): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 6776): onReceive
I/AppUp4:CustModeStarterReceiver( 6776): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6776): Context : android.app.ReceiverRestrictedContext@11d302ac
D/AppUp4:CustFacade( 6776): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6776): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6776): begin check event
I/AppUp4:CustModeStarterReceiver( 6776): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6776): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6776): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6776): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6776): handleAsyncCustNotification do not startCustService
I/ActivityManager(  870): Killing 6502:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10051/pid_6502/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3146): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3146): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3146): networkInfo.isConnected() = false
I/ActivityManager(  870): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6795 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6795): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6795): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6795): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  870): Killing 6520:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 6795): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6795): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6795): [parse] Load xml
V/TelephonyAutoProfiling( 6795): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 6795): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6795): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  870): failed to open /acct/uid_10061/pid_6520/cgroup.procs: No such file or directory
,V/DownloadManager( 3193): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3193): DownloadService onCreate
I/DownloadManager( 3193): in removeSpuriousFiles
V/DownloadManager( 3193): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/NotificationManager( 3193): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3193): created cursor android.database.sqlite.SQLiteCursor@28c54a1a on behalf of 3193
I/DownloadManager( 3193): in trimDatabase
V/DownloadManager( 3193): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3193): created cursor android.database.sqlite.SQLiteCursor@22b0a94b on behalf of 3193
I/ActivityManager(  870): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6817 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3193): DownloadService onStartCommand
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinService( 5521): Checkin interval check for package: unspecified last checkin: 1454422510624 min interval config: 0 actual interval: 26579
V/DownloadManager( 3193): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3193): created cursor android.database.sqlite.SQLiteCursor@13ddede6 on behalf of 3193
,I/CheckinService( 5521): Checking schedule, now: 1454422537244 next: 1454422540590
I/CheckinService( 5521): active receiver: disabled
V/DownloadManager( 3193): DownloadService onDestroy
,I/ActivityManager(  870): Killing 6558:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/CheckinService( 5521): Done disabling old GoogleServicesFramework version
,W/libprocessgroup(  870): failed to open /acct/uid_10079/pid_6558/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2669): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:15:37
D/UpdateThreadPoolManager( 2669): 2 : This is isUpdating : false
D/WeatherAncestor( 2669): connectivity changed - connection : true
D/Weather_cast( 2669): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2669): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:15:37
D/WeatherService( 2669): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  870): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6844 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  870): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2669): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2669): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2669): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6844): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6844): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6844): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6844): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6844): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6844): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6844): MmsConfig.loadFromResources
E/Babel_SMS( 6844): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6844): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 6844): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6844): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6844): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6844): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6844): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6844): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6844): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6844): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6844): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6844): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6844): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6844): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6844): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6844): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6844): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6844): found sensor: Motion Accel, handle=46
,W/Settings( 6844): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6844): startup - clean
I/art     ( 6844): CheckpointMarkThreadRoots callback created = 0xb042d610
,I/Babel   ( 6844): deleted: false for 0
,I/art     ( 6844): CheckpointMarkThreadRoots callback created = 0xb042d5f0
I/ActivityManager(  870): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6879 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/AudioCapabilities( 6844): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6844): Unsupported mime audio/adpcm
W/AudioCapabilities( 6844): Unsupported mime audio/g726
W/AudioCapabilities( 6844): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6844): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6844): Unsupported mime video/mjpg
W/VideoCapabilities( 6844): Unsupported mime video/theora
,W/AudioCapabilities( 6844): Unsupported mime audio/evrc
W/AudioCapabilities( 6844): Unsupported mime audio/qcelp
W/VideoCapabilities( 6844): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6844): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6844): Unsupported mime audio/qcelp
W/AudioCapabilities( 6844): Unsupported mime audio/evrc
,W/VideoCapabilities( 6844): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6844): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6844): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6844): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6844): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6844): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6844): onServiceConnected
W/Babel   ( 6844): Attempted to change video mute state without an active call.
I/NotificationManager( 6844): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6844): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6844): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6844): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6844): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 6844): propertyValue:false
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6879): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6879): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
I/GAv4    ( 6879): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6879):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6879):   adb logcat -s GAv4
,W/ContextImpl( 6879): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6879): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6879): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/Babel   ( 6844): connection state changed from UNKNOWN to CONNECTED
,W/GAv4    ( 6879): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  870): Killing 6621:com.android.chrome/u0a48 (adj 15): empty #11
,W/GAv4    ( 6879): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  870): failed to open /acct/uid_10048/pid_6621/cgroup.procs: No such file or directory
,I/WebViewFactory( 6879): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6879): Time to load native libraries: 2 ms (timestamps 7066-7068)
I/LibraryLoader( 6879): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6879): Binding Chromium to main looper Looper (main, tid 1) {18c29a79}
I/LibraryLoader( 6879): Expected native library version number "",actual native library version number ""
I/chromium( 6879): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6879): Initializing chromium process, singleProcess=true
,W/art     ( 6879): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6879): ApplicationContext is null in ApplicationStatus
W/chromium( 6879): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6879): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6879): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6879): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6879): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6879): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6879): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6879): Remote Branch: 
I/Adreno-EGL( 6879): Local Patches: 
I/Adreno-EGL( 6879): Reconstruct Branch: 
I/NSApplication( 6879): Starting up...
,V/AudioPolicyService(  279): registerClient() client 0xb551c700, uid 10079
W/AudioManagerAndroid( 6879): Requires BLUETOOTH permission
I/ActivityManager(  870): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6948 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  870): Killing 6648:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10086/pid_6648/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/jxcore-log( 5539): Test app app.js loaded
I/jxcore-log( 5539): 
,I/ActivityManager(  870): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6967 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  870): Killing 6683:com.google.android.music:main/u0a81 (adj 15): empty #11
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5539): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5539): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5539): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5539): 	Bluetooth MAC address: null, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5539): 	Discovery mode: BLE, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5539): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5539): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5539): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5539): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5539): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27e977d6 added. We now have 1 listener(s)
,W/libprocessgroup(  870): failed to open /acct/uid_10081/pid_6683/cgroup.procs: No such file or directory
D/BluetoothAdapterService(86465403)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2cf59629
,I/jxcore-log( 5539): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5539): 
W/ResourcesManager( 6967): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/chromium( 5539): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/ActivityManager(  870): Killing 6721:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10021/pid_6721/cgroup.procs: No such file or directory
,I/ActivityManager(  870): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6992 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 6992): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  870): Message: 20
,D/BluetoothAdapterService(86465403)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2cf59629
,D/BluetoothAdapterService(86465403)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2cf59629
I/ActivityManager(  870): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7013 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6992): Create singleton instance
,I/art     (  870): Explicit concurrent mark sweep GC freed 19207(957KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.041ms total 161.851ms
D/BluetoothManagerService(  870): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@39bc30a3:true
,D/UEI.SmartControl( 7013): Quickset Services start...
,I/UEI.SmartControl( 7013): Manufacture = LGE
D/UEI.SmartControl( 7013): File observer start...
E/UEI.SmartControl( 7013): IR Port is disabled: false
D/UEI.SmartControl( 7013): Starting file observer...
D/UEI.SmartControl( 7013): Extracting JNI libs...
D/UEI.SmartControl( 7013): --- this system supports 32-bit or 64-bit only
I/AudioManager( 6992): getMode name:com.lge.qremote
,I/AudioManager( 6992): getMode name:com.lge.qremote
D/UEI.SmartControl( 7013): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7013): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7013): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7013): --- Selecting new region: 2
I/UEI.SmartControl( 7013): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7013): Platform has CIR...
D/UEI.SmartControl( 7013): NO CIR support, need to check package...
I/UEI.SmartControl( 7013): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7013): QS Service created
E/UEI.SmartControl( 7013): QS start get config
,I/ActivityManager(  870): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7037 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UEI.SmartControl( 7013): Loading JNI Libs...
,D/UEI.SmartControl( 7013):  configuring local db...
,D/UEI.SmartControl( 7013):  ---- Has DB8: true
,D/UEI.SmartControl( 7013): QS start statue = true Error code = 0
D/UEI.SmartControl( 7013): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7013): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7013): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7013): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7013): IrrcClient ++ 
D/irrcClient( 7013): getIrrcService ++ 
D/irrcClient( 7013): getIrrcService -- 
D/irrcClient( 7013): IrrcClient -- 
W/irrc_jni( 7013): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7013): Services init done
,I/UEI.SmartControl( 7013): Device manager: loading config....
D/UEI.SmartControl( 7013): QS Service init finished
D/UEI.SmartControl( 7013): QS Service version name: 0.1.73
D/UEI.SmartControl( 7013): QS Service version code: 1073
D/UEI.SmartControl( 7013): Service requested: Control
D/UEI.SmartControl( 7013): Config is loaded...
D/UEI.SmartControl( 7013):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7013): Notify AllClients services are ready: 0
,W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/UEI.SmartControl( 7013): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7013): Internal service binding...
D/UEI.SmartControl( 7013): -----IControl: 11
D/UEI.SmartControl( 7013): Caller: com.lge.qremote
D/UEI.SmartControl( 7013): ------------ IControl registerCallback...
I/UEI.SmartControl( 7013): Registering callback...
D/UEI.SmartControl( 7013): -----IControl: 19
D/UEI.SmartControl( 7013): Caller: com.lge.qremote
I/UEI.SmartControl( 7013): Registering Services Ready callback...
I/UEI.SmartControl( 7013): Notify client services are ready...
I/ThermalEngine(  292): Sensor:pa_therm0:34000 mC
,D/UEI.SmartControl( 7013): -----IControl: 8
D/UEI.SmartControl( 7013): Caller: com.lge.qremote
I/ActivityManager(  870): Killing 6752:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_1000/pid_6752/cgroup.procs: No such file or directory
,I/Gmail   ( 7037): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 7037): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  870): Killing 6776:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10011/pid_6776/cgroup.procs: No such file or directory
,E/Gmail   ( 7037): Error finding the version of the Email provider.....
E/Gmail   ( 7037): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7037): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7037): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7037): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7037): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7037): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7037): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7037): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7037): We do not support migrating this version of the Email provider.
I/Gmail   ( 7037): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  870): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7076 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  870): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/ActivityManager(  870): Killing 6795:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/art     (  301): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 22.411ms
,I/Gmail   ( 7037): Observing account changes for notifications
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 25.672ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.529ms
,W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/libprocessgroup(  870): failed to open /acct/uid_10038/pid_6795/cgroup.procs: No such file or directory
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MusicStore( 7076): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7076): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/Gmail   ( 7037): notifyAccountChanged
,I/Gmail   ( 7037): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7037): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7037): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7037): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7037): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7076): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7076): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/Gmail   ( 7037): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 7076): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7076): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,V/JNIHelp ( 7076): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 7076): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7076): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f295188: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7076): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7076): GMSCore installation verified
I/ConfigStore( 7076): Config Database version: 1
,I/MediaRouter( 7076): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7076): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7076): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7076): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  870): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7113 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7076): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7076): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 7113): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7113): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7113): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  870): Killing 6817:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10051/pid_6817/cgroup.procs: No such file or directory
,I/NotificationManager( 7076): com.google.android.music: cancel(1061) by com.google.android.music
,I/LGEmail ( 7113): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7113): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7113): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  870): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7144 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7113): JNI_OnLoad()
,I/HubEmail( 7113): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7113): registerNatives()
I/HubEmail( 7113): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7113): registerNativeMethods()
I/HubEmail( 7113): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7113): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  870): Killing 6879:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10079/pid_6879/cgroup.procs: No such file or directory
W/Settings( 7113): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7144): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7144): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7144): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7144): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7144): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7144): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7144): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 7144): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  870): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7174 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ContextImpl( 7144): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 7144): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7144): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7144): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7144): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7144): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  870): Killing 6948:com.android.chrome/u0a48 (adj 15): empty #11
I/AppUp4:AppBoxCP( 7174): onCreate
,W/AppUp4:DB( 7174):  [AppBoxDatabaseHelper] construct
W/libprocessgroup(  870): failed to open /acct/uid_10048/pid_6948/cgroup.procs: No such file or directory
,I/AppUp4:DB( 7174):  setFingerPrint start
I/AppUp4:DB( 7174):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7174):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7174):  SDK version = 0
I/AppUp4:DB( 7174):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7174): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7174): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7174): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7174): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7174): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 7174): onReceive
I/AppUp4:CustModeStarterReceiver( 7174): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7174): Context : android.app.ReceiverRestrictedContext@11d302ac
D/AppUp4:CustFacade( 7174): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7174): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7174): begin check event
I/AppUp4:CustModeStarterReceiver( 7174): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7174): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7174): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7174): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7174): handleAsyncCustNotification do not startCustService
I/ActivityManager(  870): Killing 6967:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10086/pid_6967/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3146): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3146): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3146): networkInfo.isConnected() = true
,D/PhoneState( 3146): setPdpRejectCasuse : false
I/ActivityManager(  870): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7199 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/PhoneMonitor( 7199): Register our PhoneStateListener
,V/AlarmManager(  870): RTC_WAKEUP set : Alarm{3aa6b816 type 0 when 1454422540590 com.google.android.gms} when 1454422540590
I/ActivityManager(  870): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7216 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  870): RTC_WAKEUP set : Alarm{3c174597 type 0 when 1454422542263 com.android.vending} when 1454422542263
D/MobileConnectivityChangeReceiver( 7199): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7199): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  870): Killing 7013:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
D/PhoneMonitor( 7199): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 7199): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7199): [parse] Load xml
V/TelephonyAutoProfiling( 7199): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7199): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 7199): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/System.err( 6992): android.os.DeadObjectException
,W/System.err( 6992): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6992): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6992): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6992): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6992): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6992): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6992): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6992): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6992): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6992): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6992): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6992): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6992): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6992): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6992): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6992): android.os.DeadObjectException
W/System.err( 6992): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6992): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6992): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6992): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6992): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6992): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6992): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6992): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6992): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6992): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6992): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6992): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6992): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6992): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6992): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  870): failed to open /acct/uid_10089/pid_7013/cgroup.procs: No such file or directory
,W/ActivityManager(  870): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
V/DownloadManager( 3193): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3193): DownloadService onCreate
,I/NotificationManager( 3193): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3193): in removeSpuriousFiles
V/DownloadManager( 3193): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3193): created cursor android.database.sqlite.SQLiteCursor@128b05d4 on behalf of 3193
I/DownloadManager( 3193): in trimDatabase
V/DownloadManager( 3193): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3193): created cursor android.database.sqlite.SQLiteCursor@16f0437d on behalf of 3193
I/ActivityManager(  870): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7239 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  870): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7251 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3193): DownloadService onStartCommand
V/DownloadManager( 3193): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/CheckinService( 5521): Checkin interval check for package: unspecified last checkin: 1454422510624 min interval config: 0 actual interval: 31898
V/DownloadManager( 3193): created cursor android.database.sqlite.SQLiteCursor@47cab40 on behalf of 3193
,I/CheckinService( 5521): Checking schedule, now: 1454422542561 next: 1454422540590
I/CheckinService( 5521): active receiver: enabled
I/art     (  870): Explicit concurrent mark sweep GC freed 12545(603KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.890ms total 165.241ms
,I/CheckinService( 5521): Preparing to send checkin request
V/DownloadManager( 3193): DownloadService onDestroy
,I/EventLogService( 5521): Accumulating logs since 1454422501425
D/UEI.SmartControl( 7239): Quickset Services start...
,I/UEI.SmartControl( 7239): Manufacture = LGE
D/UEI.SmartControl( 7239): File observer start...
E/UEI.SmartControl( 7239): IR Port is disabled: false
D/UEI.SmartControl( 7239): Starting file observer...
D/UEI.SmartControl( 7239): Extracting JNI libs...
,D/UEI.SmartControl( 7239): --- this system supports 32-bit or 64-bit only
D/WeatherAncestor( 2669): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:15:42
D/UpdateThreadPoolManager( 2669): 2 : This is isUpdating : false
D/WeatherAncestor( 2669): connectivity changed - connection : true
D/Weather_cast( 2669): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2669): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:15:42
D/WeatherService( 2669): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  870): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2669): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2669): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2669): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/UEI.SmartControl( 7239): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7239): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7239): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/ActivityManager(  870): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7284 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UEI.SmartControl( 7239): --- Selecting new region: 2
I/UEI.SmartControl( 7239): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7239): Platform has CIR...
D/UEI.SmartControl( 7239): NO CIR support, need to check package...
I/UEI.SmartControl( 7239): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 7239): QS Service created
,E/UEI.SmartControl( 7239): QS start get config
,D/UEI.SmartControl( 7239): Loading JNI Libs...
D/UEI.SmartControl( 7239):  configuring local db...
,I/ActivityManager(  870): Process com.google.android.gm (pid 7037) has died
,I/CheckinRequestBuilder( 5521): Checkin reason type: 8 attempt count: 1
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,E/ActivityThread( 5521): Failed to find provider info for com.google.android.wearable.settings
W/ContextImpl( 7284): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7284): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7284): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,I/GAv4    ( 7284): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7284):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7284):   adb logcat -s GAv4
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7284): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7284): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 3905): Explicit concurrent mark sweep GC freed 2008(73KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 448us total 33.045ms
D/Finsky  ( 7216): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/GAv4    ( 7284): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 7284): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/UEI.SmartControl( 7239):  ---- Has DB8: true
,D/UEI.SmartControl( 7239): QS start statue = true Error code = 0
D/UEI.SmartControl( 7239): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7239): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7239): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7239): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7239): IrrcClient ++ 
D/irrcClient( 7239): getIrrcService ++ 
D/irrcClient( 7239): getIrrcService -- 
D/irrcClient( 7239): IrrcClient -- 
W/irrc_jni( 7239): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7239): Services init done
I/UEI.SmartControl( 7239): Device manager: loading config....
D/UEI.SmartControl( 7239): QS Service init finished
D/UEI.SmartControl( 7239): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7239): QS Service version code: 1073
D/UEI.SmartControl( 7239): Service requested: Control
D/UEI.SmartControl( 7239): Config is loaded...
,D/UEI.SmartControl( 7239):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7239): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7239): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 7239): Internal service binding...
,D/Finsky  ( 7216): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
D/UEI.SmartControl( 7239): -----IControl: 11
D/UEI.SmartControl( 7239): Caller: com.lge.qremote
D/UEI.SmartControl( 7239): ------------ IControl registerCallback...
I/UEI.SmartControl( 7239): Registering callback...
D/UEI.SmartControl( 7239): -----IControl: 19
D/UEI.SmartControl( 7239): Caller: com.lge.qremote
I/UEI.SmartControl( 7239): Registering Services Ready callback...
I/UEI.SmartControl( 7239): Notify client services are ready...
,D/UEI.SmartControl( 7239): -----IControl: 8
D/UEI.SmartControl( 7239): Caller: com.lge.qremote
W/Settings( 7216): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7216): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7216): com.android.vending: cancel(-1050172287) by com.android.vending
,D/Finsky  ( 7216): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7216): [1] Libraries$2.run: Finished loading 1 libraries.
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Ads     ( 7216): Skipping gmscore version check
,V/DownloadManager( 3193): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3193): created cursor android.database.sqlite.SQLiteCursor@882d3be on behalf of 7216
,D/Finsky  ( 7216): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 7216): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/WebViewFactory( 7284): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 7284): Time to load native libraries: 2 ms (timestamps 1663-1665)
,I/LibraryLoader( 7284): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7284): Binding Chromium to main looper Looper (main, tid 1) {18c29a79}
I/LibraryLoader( 7284): Expected native library version number "",actual native library version number ""
I/chromium( 7284): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7284): Initializing chromium process, singleProcess=true
,W/art     ( 7284): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7284): ApplicationContext is null in ApplicationStatus
W/chromium( 7284): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,I/ActivityManager(  870): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7359 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
E/libEGL  ( 7284): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7284): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7284): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7284): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7284): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7284): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7284): Remote Branch: 
I/Adreno-EGL( 7284): Local Patches: 
I/Adreno-EGL( 7284): Reconstruct Branch: 
,W/ResourcesManager( 7359): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7359): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/AudioPolicyService(  279): registerClient() client 0xb551c6e0, uid 10079
,W/AudioManagerAndroid( 7284): Requires BLUETOOTH permission
,D/Finsky  ( 7216): [925] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 7216): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/NSApplication( 7284): Starting up...
I/MultiDex( 7359): VM with version 2.1.0 has multidex support
I/MultiDex( 7359): install
,I/MultiDex( 7359): VM has multidex support, MultiDex support library is disabled.
I/ActivityManager(  870): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7389 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  870): Killing 7076:com.google.android.music:main/u0a81 (adj 15): empty #11
I/ActivityManager(  870): Killing 6992:com.lge.qremote/u0a106 (adj 15): empty #12
,W/libprocessgroup(  870): failed to open /acct/uid_10081/pid_7076/cgroup.procs: No such file or directory
,W/libprocessgroup(  870): failed to open /acct/uid_10106/pid_6992/cgroup.procs: No such file or directory
V/JNIHelp ( 7359): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7359): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7359): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3a055d09: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7359): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  870): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7409 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/NotificationManager( 7359): com.google.android.gms: cancel(10436) by com.google.android.gms
I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 20.982ms
,I/NotificationManager( 7359): com.google.android.gms: cancel(39789) by com.google.android.gms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 20.633ms
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 21.359ms
,W/ResourcesManager( 7409): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 7359): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7359): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/ActivityManager(  870): Killing 7113:com.lge.email/u0a21 (adj 15): empty #11
,D/NativeLibraryUtils( 7359): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  870): failed to open /acct/uid_10021/pid_7113/cgroup.procs: No such file or directory
D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): CdmEngine::OpenSession
I/WVCdm   (  279): Level3 Library Dec 11 2014 16:13:16
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
W/WVCdm   (  279): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  279): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  279): L1 library not specified. Falling Back to L3
,I/ActivityManager(  870): Killing 7144:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/WVCdm   (  279): PrepareKeyRequest: nonce=2315641724
,W/libprocessgroup(  870): failed to open /acct/uid_1000/pid_7144/cgroup.procs: No such file or directory
,I/ActivityManager(  870): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7435 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7435): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  870): Message: 20
D/BluetoothManagerService(  870): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a7b37dc:true
,D/BluetoothAdapterService(86465403)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2cf59629
D/BluetoothAdapterService(86465403)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2cf59629
I/AudioManager( 7435): getMode name:com.lge.qremote
,I/AudioManager( 7435): getMode name:com.lge.qremote
,D/WearableService( 1731): callingUid 10006, callindPid: 1731
,D/LocationInitializer( 5521): Restart initialization of location
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1731): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1731): No location to return for getLastLocation()
,W/FusedLocationProvider( 1731): location=null
D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/Finsky  ( 7216): [930] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  870): android: cancelAsUser(2) by android
I/art     ( 7359): CheckpointMarkThreadRoots callback created = 0xb04cbe50
I/art     ( 7359): CheckpointMarkThreadRoots callback created = 0xb04cbe40
,V/LGMDMManager( 7435): Create singleton instance
D/libc-netbsd( 7216): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7216): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7216): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7216): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
I/WVCdm   (  279): CdmEngine::OpenSession
,I/AudioManager( 7435): getMode name:com.lge.qremote
,D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 7216): propertyValue:false
D/UEI.SmartControl( 7239): -----IControl: 11
,D/UEI.SmartControl( 7239): Caller: com.lge.qremote
D/UEI.SmartControl( 7239): ------------ IControl registerCallback...
I/UEI.SmartControl( 7239): Registering callback...
D/UEI.SmartControl( 7239): -----IControl: 19
D/UEI.SmartControl( 7239): Caller: com.lge.qremote
I/UEI.SmartControl( 7239): Registering Services Ready callback...
I/UEI.SmartControl( 7239): Notify client services are ready...
D/UEI.SmartControl( 7239): -----IControl: 8
D/UEI.SmartControl( 7239): Caller: com.lge.qremote
I/ActivityManager(  870): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7464 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  870): Killing 7174:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10011/pid_7174/cgroup.procs: No such file or directory
,W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Gmail   ( 7464): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 7464): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/AudioManager( 7435): getMode name:com.lge.qremote
I/art     (  870): Explicit concurrent mark sweep GC freed 23272(1094KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.346ms total 155.014ms
,W/ActivityManager(  870): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
E/Gmail   ( 7464): Error finding the version of the Email provider.....
E/Gmail   ( 7464): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7464): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7464): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7464): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7464): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7464): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7464): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7464): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7464): We do not support migrating this version of the Email provider.
,I/Gmail   ( 7464): Observing account changes for notifications
W/ActivityManager(  870): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/CheckinService( 5521): Checkin interval check for package: unspecified last checkin: 1454422510624 min interval config: 0 actual interval: 34840
,I/AudioManager( 7435): getMode name:com.lge.qremote
I/ActivityManager(  870): Killing 7251:com.lge.drmservice/u0a51 (adj 15): empty #11
,E/MDM     ( 1731): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/ThermalEngine(  292): Sensor:pa_therm0:34000 mC
,W/libprocessgroup(  870): failed to open /acct/uid_10051/pid_7251/cgroup.procs: No such file or directory
,D/LocationInitializer( 5521): Restart initialization of location
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
I/AudioManager( 7435): getMode name:com.lge.qremote
,I/AudioManager( 7435): getMode name:com.lge.qremote
I/AudioManager( 7435): getMode name:com.lge.qremote
,W/ContextImpl( 3568): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
I/AudioManager( 7435): getMode name:com.lge.qremote
I/AudioManager( 7435): getMode name:com.lge.qremote
,I/AudioManager( 7435): getMode name:com.lge.qremote
I/AudioManager( 7435): getMode name:com.lge.qremote
,I/AudioManager( 7435): getMode name:com.lge.qremote
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/WVCdm   (  279): CdmEngine::CloseSession
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/WVCdm   (  279): PrepareKeyRequest: nonce=2917990296
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 115583522981; DSPS: 3878817; Offset : -2799301650
,I/MusicWidget( 2553): mDelayedStopHandler : unbind
,I/MusicBrowser( 2678): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
I/MusicBrowser( 2678): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2678): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2678): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2678): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2678): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2678): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2678): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  870):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2933e6bacom.lge.music.MediaPlaybackService$6@942196b
D/MusicBrowser( 2678): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2678): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2678): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2678): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2678): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@2bc39d98
I/MusicBrowser( 2678): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2678): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2678): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2678): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2678): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2678): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2678): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2678): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2678): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2678): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2678): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2678): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2678): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2678): reset
V/MediaPlayer[Native]( 2678): setListener
V/MediaPlayer[Native]( 2678): disconnect
V/MediaPlayer[Native]( 2678): destructor
V/AudioFlinger(  279): releasing 18 from 2678 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/MediaPlayer[Native]( 2678): disconnect
D/MusicBrowser( 2678): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
,I/SmartShareClient( 2678): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2678): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2678): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2678): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2678): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2678): [SmartShareManagerClient] unregisterListener: 681942216
W/SmartShareClient( 2678): [SmartShareManagerClient] unregisterListener invalid listener: 681942216
I/SmartShareClient( 2678): [SmartShareManagerClient] terminate service: 2678/MediaPlaybackService/690813182
E/HomeCloudIF( 2678): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2678): [SmartShareManagerClient] unbindService context:android.app.Application@ef8e161
,V/CloudHub( 2678): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2678): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2678): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2678): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2678): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  870): Killing 6844:com.google.android.talk/u0a61 (adj 15): empty #11
I/CloudHub( 2678): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29963
,W/libprocessgroup(  870): failed to open /acct/uid_10061/pid_6844/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7239): Internal timer expired: 1
,I/WVCdm   (  279): CdmEngine::CloseSession
,I/WVCdm   (  279): L3 Terminate.
I/dex2oat ( 7534): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=40 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7534): dex2oat took 95.176ms (threads: 4)
,I/Adreno-EGL( 7359): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7359): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7359): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7359): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7359): Remote Branch: 
I/Adreno-EGL( 7359): Local Patches: 
I/Adreno-EGL( 7359): Reconstruct Branch: 
,I/Adreno-EGL( 7359): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7359): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7359): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7359): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7359): Remote Branch: 
I/Adreno-EGL( 7359): Local Patches: 
I/Adreno-EGL( 7359): Reconstruct Branch: 
,I/Adreno-EGL( 7359): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7359): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7359): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7359): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7359): Remote Branch: 
I/Adreno-EGL( 7359): Local Patches: 
I/Adreno-EGL( 7359): Reconstruct Branch: 
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/CheckinRequestBuilder( 5521): Classify the device as Phone.
,D/libc-netbsd( 5521): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5521): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5521): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5521): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 5521): propertyValue:false
D/libc-netbsd( 5521): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5521): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5521): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5521): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5521): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5521): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5521): Sending checkin request (9769 bytes)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/GAV2    ( 7464): Thread[GAThread,5,main]: No campaign data found.
,I/CheckinRequestBuilder( 5521): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 5521): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 5521): Classify the device as Phone.
,I/CheckinTask( 5521): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5521): Checking schedule, now: 1454422550455 next: 1454949799450
,I/CheckinService( 5521): active receiver: disabled
,I/CheckinService( 5521): Checking schedule, now: 1454422550484 next: 1454949799450
,I/CheckinService( 5521): active receiver: disabled
,D/CheckinService( 5521): Recording last checkin time for package unspecified as 1454422550493
I/ThermalEngine(  292): Sensor:pa_therm0:34000 mC
,V/SetupWizard( 7199): Connected to Gservices successfully
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  870): Killing 7389:com.android.chrome/u0a48 (adj 15): empty #11
,I/ActivityManager(  870): Killing 7284:com.google.android.apps.magazines/u0a79 (adj 15): empty #12
,W/libprocessgroup(  870): failed to open /acct/uid_10048/pid_7389/cgroup.procs: No such file or directory
,W/libprocessgroup(  870): failed to open /acct/uid_10079/pid_7284/cgroup.procs: No such file or directory
I/InputReader(  870): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/ActivityManager(  870): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7572 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,D/administrator(  870): Handling package changes for user 0
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 7572): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationService(  870): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  870): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  870): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  870): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourcesManager(  870): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/BackupManagerService(  870): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  870): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@32d1dbe2
,I/Babel_SMS( 7572): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7572): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7572): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7572): MmsConfig.loadFromDatabase
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
,E/Babel_SMS( 7572): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 7572): MmsConfig.loadFromResources
E/Babel_SMS( 7572): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7572): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
W/ResourceType(  870): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,D/SensorManager( 7572): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7572): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7572): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7572): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7572): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7572): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7572): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7572): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7572): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7572): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7572): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7572): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7572): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7572): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7572): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7572): found sensor: Motion Accel, handle=46
W/Settings( 7572): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/Babel_Crash( 7572): startup - clean
I/GCoreNlp( 1731): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/Babel   ( 7572): deleted: false for 0
,D/LocationProviderProxy(  870): applying state to connected service
,I/art     ( 7572): CheckpointMarkThreadRoots callback created = 0xb042d870
,I/art     ( 7572): CheckpointMarkThreadRoots callback created = 0xb042d840
,W/AudioCapabilities( 7572): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7572): Unsupported mime audio/adpcm
W/AudioCapabilities( 7572): Unsupported mime audio/g726
W/AudioCapabilities( 7572): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7572): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7572): Unsupported mime video/mjpg
W/VideoCapabilities( 7572): Unsupported mime video/theora
,I/ActivityManager(  870): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7618 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/AudioCapabilities( 7572): Unsupported mime audio/evrc
W/AudioCapabilities( 7572): Unsupported mime audio/qcelp
W/VideoCapabilities( 7572): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 7572): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7572): Unsupported mime audio/qcelp
W/AudioCapabilities( 7572): Unsupported mime audio/evrc
W/VideoCapabilities( 7572): Unsupported mime video/mp4v-esdp
,I/AppUp4:AppBoxCP( 7618): onCreate
W/AppUp4:DB( 7618):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7618):  setFingerPrint start
,I/AppUp4:DB( 7618):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/VideoCapabilities( 7572): Unsupported profile 4 for video/mp4v-es
I/AppUp4:DB( 7618):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7618):  SDK version = 0
I/AppUp4:DB( 7618):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7618): AppBoxApplication onCreate()
W/VideoCapabilities( 7572): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7572): Unrecognized profile 2130706433 for video/avc
,I/AppUp4:CustModeStarterReceiver( 7618): onReceive
I/AppUp4:CustModeStarterReceiver( 7618): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
W/VideoCapabilities( 7572): Unrecognized profile 2130706433 for video/avc
D/AppUp4:CustFacade( 7618): Context : android.app.ReceiverRestrictedContext@17550cb9
D/AppUp4:CustFacade( 7618): isCustomizationCompleted : false
W/VideoCapabilities( 7572): Unrecognized profile 2130706433 for video/avc
D/AppUp4:CustFacade( 7618): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7618): begin check event
I/AppUp4:CustModeStarterReceiver( 7618): Event For Nothing, skip.
I/ActivityManager(  870): Killing 7409:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/art     ( 7572): Suspending all threads took: 13.946ms
,W/libprocessgroup(  870): failed to open /acct/uid_10086/pid_7409/cgroup.procs: No such file or directory
,I/vclib   ( 7572): onServiceConnected
W/Babel   ( 7572): Attempted to change video mute state without an active call.
I/NotificationManager( 7572): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7572): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7572): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  870): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7640 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,V/JNIHelp ( 7572): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 7640): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7640): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7640): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/System  ( 7572): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7572): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 7572): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AppConfig( 7640): Total System Memory = 906309632
,I/GalleryUtils( 7640): Application Heap = 96 MB
I/AppConfig( 7640): App Tier : NOT_DEF
D/SystemHelper( 7640): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  870): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7661 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  870): Killing 7216:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  870): failed to open /acct/uid_10036/pid_7216/cgroup.procs: No such file or directory
,W/ResourcesManager( 7661): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7661): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7661): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7661): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7661): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7661): BUILD Country: EU
,I/SystemConfig( 7661): BUILD Operator: OPEN
,I/ActivityManager(  870): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7686 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  870): Killing 7464:com.google.android.gm/u0a53 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  870): failed to open /acct/uid_10053/pid_7464/cgroup.procs: No such file or directory
,I/SystemConfig( 7661): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7661): existFile = false
I/SystemConfig( 7661): canReadFile = false
I/SystemConfig( 7661): systemFeature RCS result false
D/SystemConfig( 7661): refreshRcsSupport() :false
,I/LockScreenSettings( 7686): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7686): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7686): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7686): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7686): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7686): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  870): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7703 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  870): Killing 2678:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  279): 2678 died, releasing its sessions
V/AudioFlinger(  279):  pid 1745 @ 0
,V/AudioFlinger(  279):  pid 3146 @ 1
V/AudioFlinger(  279):  pid 3146 @ 2
W/libprocessgroup(  870): failed to open /acct/uid_10028/pid_2678/cgroup.procs: No such file or directory
,W/ResourcesManager( 7703): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  870): Explicit concurrent mark sweep GC freed 24068(1227KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.638ms total 150.281ms
,I/UpdateIcingCorporaServi( 1940): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  870): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7728 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1940): UpdateCorporaTask done [took 52 ms] updated apps [took 52 ms] 
I/ActivityManager(  870): Killing 7239:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7435): android.os.DeadObjectException
,W/System.err( 7435): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7435): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7435): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7435): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7435): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7435): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7435): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7435): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7435): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7435): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7435): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7435): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7435): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7435): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7435): android.os.DeadObjectException
W/System.err( 7435): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7435): 	at android.os.BinderProxy.transact(Binder.java:496)
,W/System.err( 7435): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7435): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7435): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7435): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7435): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7435): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7435): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7435): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7435): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7435): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7435): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7435): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7435): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,W/libprocessgroup(  870): failed to open /acct/uid_10089/pid_7239/cgroup.procs: No such file or directory
W/ActivityManager(  870): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  870): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7745 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7745): Quickset Services start...
,I/UEI.SmartControl( 7745): Manufacture = LGE
D/UEI.SmartControl( 7745): File observer start...
E/UEI.SmartControl( 7745): IR Port is disabled: false
D/UEI.SmartControl( 7745): Starting file observer...
D/UEI.SmartControl( 7745): Extracting JNI libs...
D/UEI.SmartControl( 7745): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7745): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7745): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7745): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/UEI.SmartControl( 7745): --- Selecting new region: 2
I/UEI.SmartControl( 7745): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7745): Platform has CIR...
,D/UEI.SmartControl( 7745): NO CIR support, need to check package...
I/UEI.SmartControl( 7745): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7745): QS Service created
D/Finsky  ( 7728): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/UEI.SmartControl( 7745): QS start get config
,D/UEI.SmartControl( 7745): Loading JNI Libs...
,D/UEI.SmartControl( 7745):  configuring local db...
,D/Finsky  ( 7728): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7728): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7728): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7728): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3193): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3193): created cursor android.database.sqlite.SQLiteCursor@3f2c3c1f on behalf of 7728
,D/Finsky  ( 7728): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7728): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 7728): Skipping gmscore version check
,D/Finsky  ( 7728): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ThermalEngine(  292): Sensor:pa_therm0:34000 mC
,D/PackageBroadcastService( 5521): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 5521): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 7728): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/Icing   ( 5521): updateResources: need to parse f{com.google.android.gms}
,D/UEI.SmartControl( 7745):  ---- Has DB8: true
,D/UEI.SmartControl( 7745): QS start statue = true Error code = 0
D/UEI.SmartControl( 7745): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 7745): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7745): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7745): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7745): IrrcClient ++ 
D/irrcClient( 7745): getIrrcService ++ 
D/irrcClient( 7745): getIrrcService -- 
D/irrcClient( 7745): IrrcClient -- 
W/irrc_jni( 7745): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7745): Services init done
I/UEI.SmartControl( 7745): Device manager: loading config....
D/UEI.SmartControl( 7745): QS Service init finished
,D/UEI.SmartControl( 7745): QS Service version name: 0.1.73
D/UEI.SmartControl( 7745): QS Service version code: 1073
D/UEI.SmartControl( 7745): Service requested: Control
D/UEI.SmartControl( 7745): Config is loaded...
D/UEI.SmartControl( 7745): Request IControl service: devices are loaded...
,I/ActivityManager(  870): Killing 7435:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 7745):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7745): Notify AllClients services are ready: 0
,W/libprocessgroup(  870): failed to open /acct/uid_10106/pid_7435/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7745): Internal service binding...
I/Icing   ( 5521): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5521): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  870): Killing 7199:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10038/pid_7199/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  870): Killing 7359:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10006/pid_7359/cgroup.procs: No such file or directory
,D/charger_monitor(  478): init target 500000
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/charger_monitor(  478): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 306, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 306
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 306
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/PowerManagerServiceEx(  870): acquireWakeLockInternal: lock=329609607, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=870
,D/WeatherService( 2669): 2 : TimeTick Intent has been received, Time(hour:min:sec) 15:16:0
,D/WeatherService( 2669): 2 : TimeTick Intent And Screen On
D/WeatherService( 2669): 2 : SDK version : 21
W/ActivityManager(  870): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2669): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2669): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2669): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2669): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2669): 2 : This is isUpdating : false
D/WeatherService( 2669): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2669): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2669): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2669): 2 : Fixed theme : optimus
I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
,D/WeatherReflect( 2669): 2 : Map key string is -2
I/[SystemUI]Clock( 1374): called onTimeUpdated()
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
,I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/lim     ( 2669): 2 : time = 15:16
I/WeatherReflect( 2669): Model Name : LG-D722
,D/WeatherTheme( 2669): 2 : Different view - status_min_formatted : 15 != 16
D/WeatherTheme( 2669): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2669): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2669): strTheme: com.lge.launcher2.theme.optimus
,D/Theme   ( 2669): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2669): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2669): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2669): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2669): forecast size is 0
,D/Theme   ( 2669): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2669): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2669): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2669): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2669): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2669): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2669): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2669): url is : null
D/Theme   ( 2669): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2669): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2669): 2 : update view, appWidgetId: 2
D/WeatherService( 2669): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 15:16:0
D/PowerManagerServiceEx(  870): releaseWakeLockInternal: lock=329609607 [*alarm*], flags=0x0
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ThermalEngine(  292): Sensor:pa_therm0:34000 mC
,D/UEI.SmartControl( 7745): Internal timer expired: 1
,D/UEI.SmartControl( 7745): Service.onUnbind: IControl
D/UEI.SmartControl( 7745): Service.onDestroy
W/System.err( 7745): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@5275b7b
W/System.err( 7745): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7745): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7745): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7745): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7745): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7745): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7745): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7745): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7745): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7745): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7745): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7745): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7745): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7745): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7745): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7745): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@5275b7b
D/UEI.SmartControl( 7745): Shutdown IRRCPlayer... 
,W/irrc_jni( 7745): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7745): ~IrrcClient ++ 
D/irrcClient( 7745): ~IrrcClient -- 
W/irrc_jni( 7745): IRRCPlayer_nativeFinalize -- 
,D/UEI.SmartControl( 7745): Blaster closed
D/UEI.SmartControl( 7745): Blaster closed
D/UEI.SmartControl( 7745): Shut down QS...
D/UEI.SmartControl( 7745): Stopped file observer...
I/UEI.SmartControl( 7745): QS lib stop result = true
D/UEI.SmartControl( 7745): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:34000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 135584487661; DSPS: 4534209; Offset : -2799312985
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/AlarmManager(  870): ELAPSED_WAKEUP set : Alarm{1b72a8b4 type 2 when 145560 com.google.android.gms} when 145560
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1731): Vacuum at: now=1454422577583 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  870): ALS enabled for SRE
D/PowerManagerServiceEx(  870): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29791 ms ago)
,D/qdlights(  870): set_light_backlight: 252
,D/qdlights(  870): set_light_backlight: 248
,D/qdlights(  870): set_light_backlight: 245
,D/qdlights(  870): set_light_backlight: 242
,D/qdlights(  870): set_light_backlight: 238
,D/qdlights(  870): set_light_backlight: 235
,D/qdlights(  870): set_light_backlight: 232
,D/qdlights(  870): set_light_backlight: 228
,D/qdlights(  870): set_light_backlight: 225
,D/qdlights(  870): set_light_backlight: 222
,D/qdlights(  870): set_light_backlight: 218
,D/qdlights(  870): set_light_backlight: 215
,D/qdlights(  870): set_light_backlight: 212
,D/qdlights(  870): set_light_backlight: 208
,D/qdlights(  870): set_light_backlight: 205
,D/qdlights(  870): set_light_backlight: 202
,D/qdlights(  870): set_light_backlight: 198
,D/qdlights(  870): set_light_backlight: 195
,D/qdlights(  870): set_light_backlight: 192
,D/qdlights(  870): set_light_backlight: 188
,D/qdlights(  870): set_light_backlight: 185
,D/qdlights(  870): set_light_backlight: 182
,D/qdlights(  870): set_light_backlight: 178
,D/qdlights(  870): set_light_backlight: 175
,D/qdlights(  870): set_light_backlight: 172
,D/qdlights(  870): set_light_backlight: 168
,D/qdlights(  870): set_light_backlight: 165
,D/qdlights(  870): set_light_backlight: 162
,D/qdlights(  870): set_light_backlight: 158
,D/qdlights(  870): set_light_backlight: 155
,D/qdlights(  870): set_light_backlight: 152
,D/qdlights(  870): set_light_backlight: 148
,D/qdlights(  870): set_light_backlight: 145
,D/qdlights(  870): set_light_backlight: 142
,D/qdlights(  870): set_light_backlight: 138
,D/qdlights(  870): set_light_backlight: 135
,D/qdlights(  870): set_light_backlight: 132
,D/qdlights(  870): set_light_backlight: 128
,D/qdlights(  870): set_light_backlight: 125
,D/qdlights(  870): set_light_backlight: 122
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/qdlights(  870): set_light_backlight: 118
,D/qdlights(  870): set_light_backlight: 115
,D/qdlights(  870): set_light_backlight: 112
,D/qdlights(  870): set_light_backlight: 108
,D/qdlights(  870): set_light_backlight: 105
,D/qdlights(  870): set_light_backlight: 102
,D/qdlights(  870): set_light_backlight: 98
,D/qdlights(  870): set_light_backlight: 95
,D/qdlights(  870): set_light_backlight: 91
,D/qdlights(  870): set_light_backlight: 88
,D/qdlights(  870): set_light_backlight: 85
,D/qdlights(  870): set_light_backlight: 81
,D/qdlights(  870): set_light_backlight: 78
,D/qdlights(  870): set_light_backlight: 75
,D/qdlights(  870): set_light_backlight: 71
,D/qdlights(  870): set_light_backlight: 68
,D/qdlights(  870): set_light_backlight: 65
,D/qdlights(  870): set_light_backlight: 61
,D/qdlights(  870): set_light_backlight: 58
,D/qdlights(  870): set_light_backlight: 55
,D/qdlights(  870): set_light_backlight: 51
,D/qdlights(  870): set_light_backlight: 48
,D/qdlights(  870): set_light_backlight: 45
,D/qdlights(  870): set_light_backlight: 41
,D/qdlights(  870): set_light_backlight: 38
,D/qdlights(  870): set_light_backlight: 35
,D/qdlights(  870): set_light_backlight: 31
,D/qdlights(  870): set_light_backlight: 28
,D/qdlights(  870): set_light_backlight: 25
,D/qdlights(  870): set_light_backlight: 21
,D/qdlights(  870): set_light_backlight: 18
,D/qdlights(  870): set_light_backlight: 15
,D/qdlights(  870): set_light_backlight: 11
,D/qdlights(  870): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 155588494163; DSPS: 5189700; Offset : -2799306292
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  870): ALS enabled for SRE
D/PowerManagerServiceEx(  870): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36783 ms ago)
I/PowerManagerService(  870): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  870): ALS enabled for SRE
D/PowerManagerServiceEx(  870): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36801 ms ago)
,W/ContextImpl(  870): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  870): Sleeping (uid 1000)...
D/LPWGController(  870): [updateScreenState] screen on = false
D/LPWGController(  870): disable proximity sensor
,D/LPWGController(  870): enable proximity sensor
I/SensorManager(  870): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@17d7ca95] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  870): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  870): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  870): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  870): activate: handle is 48, enable
,V/sensors_hal_Ctx(  870): activate sensors is 1400000000000
D/sensors_hal_Thresh(  870): enable: handle=48
I/sensors_hal_SAM(  870): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  870): waitForResponse: timeout=1000
V/sensors_hal_SAM(  870): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  870): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  870): enable: Received response: 0
D/PowerManagerServiceEx(  870): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36869 ms ago)
I/Adreno-EGL(  870): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  870): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  870): Build Date: 03/02/15 Mon
I/Adreno-EGL(  870): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  870): Remote Branch: 
I/Adreno-EGL(  870): Local Patches: 
I/Adreno-EGL(  870): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1544 us)
,I/Sensors (  429): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  870): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
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
,I/sensors_hal_Ctx(  870): activate: handle is 46, disable
,V/sensors_hal_Ctx(  870): activate sensors is 1000000000000
D/sensors_hal_LP2(  870): enable: handle=46
D/sensors_hal_LP2(  870): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  870): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  870): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/sensors_hal_SAM(  870): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  870): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,V/ActivityManager(  870): Display changed displayId=0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/DSDPConnection( 1745): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  870): Excessive delay in setPowerMode(): 180ms
I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  870): Got set_interactive hint
D/KeyguardViewMediator( 1374): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1332): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1374): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1374): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1374): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1374): unregisterProximitySensor
,D/StatusBarWindowView( 1374): onScreenTurnedOff why = 3
D/WifiServerServiceExt(  870): sendKtScanInterval  mRtspPlay : false
,V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=on, calling pid 870
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
I/WifiServerServiceExt(  870): set CMD_KT_SCAN_INTERVAL
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
,D/GpsLocationProvider(  870): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1838): |CORE| sendScreenState: state:true
I/LEDService( 1802): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1802): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDService( 1802): stopPatternFlashing()
,D/Cliptray Service( 1802): lockStatus = 0
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1785): action : android.intent.action.SCREEN_ON
I/LEDService( 1802): updateLightsLocked : turn off led
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1802): RESTART MSG
D/NfcServiceNXP( 1785): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1785): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
,D/LNfcService( 1785): isRequireNfcCRouting() return true
,D/LNfcService( 1785): isHCERoutingtoHost() return : true
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
D/SplitWindow(  870): check instance of lgWin Window{261ccf38 u0 SearchPanel}
,D/Ulp_jni (  870): JNI:system_update. Event-0
,D/InputDispatcher(  870): Window went away: Window{2883ee33 u0 SearchPanel}
,I/[SystemUI]Clock( 1374): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1374): time changed, timezoneChanged : false
,V/PhoneApp( 1745): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2669): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:16:30
D/WeatherService( 2669): 2 : ACTION screen on
D/WeatherService( 2669): 2 : shouldTimeTickRegistered : false
,D/Weather_cast( 2669): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2669): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 15:16:30
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  870): ACTION_SCREEN_ON
,D/AppCleanupService( 4003): android.intent.action.SCREEN_ON
,V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=off, calling pid 870
,D/audio_hw_primary(  279): adev_set_parameters: enter: screen_state=off
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
D/WifiController(  870): CMD_SCREEN_OFF 
D/WifiController(  870): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  870): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1838): |CORE| sendScreenState: state:false
,I/LEDService( 1802): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1802): stopPatternFlashing()
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): updateLightsLocked : turn on led
D/VolumeVibrator( 1802): clear
E/LEDService( 1802): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1802): Can't handle this request of patternId:0
D/LEDHandler( 1802): RESTART MSG
I/Cliptray Service( 1802): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1785): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1785): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1876): [Launcher.java:1711:onReceive()]Screen Off
V/PhoneApp( 1745): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2669): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:16:30
D/WeatherService( 2669): 2 : ACTION screen off
D/WeatherService( 2669): 2 : TimeTick Receiver Unregister
D/WeatherService( 2669): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 15:16:30
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  870): ACTION_SCREEN_OFF
I/Sensors (  429): sns_pwr.c(301):releasing wakelock
D/AppCleanupService( 4003): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4003): AppUsageStatsSaveTask
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
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,D/KeyguardViewMediator( 1374): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  870): ELAPSED_WAKEUP set : Alarm{3eb77b11 type 2 when 162690 com.android.systemui} when 162690
,D/PhoneUtils( 1745): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1745): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1745): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1745): getCallState : 0
,D/PhoneUtils( 1745): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1745): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1745): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1374): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1374): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:33000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 175589175405; DSPS: 5845083; Offset : -2799325208
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  870): ELAPSED_WAKEUP set : Alarm{1bc4c476 type 2 when 183743 android} when 183743
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/charger_monitor(  478): init target 500000
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 301
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 301
,D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 301, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  870): battery changed pluggedType: 2
I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/PowerManagerServiceEx(  870): acquireWakeLockInternal: lock=329609607, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=870
,V/AlarmManager(  870): ELAPSED_WAKEUP set : Alarm{2fe7ca77 type 2 when 188596 com.google.android.gms} when 188596
D/PowerManagerServiceEx(  870): releaseWakeLockInternal: lock=329609607 [*alarm*], flags=0x0
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/PhenotypeConfigurator( 1731): Scheduling Phenotype for one-off execution 12334 seconds from now (1454422620791)
,D/GetConfigurationSnapshotOperation( 1731): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/art     ( 1731): Explicit concurrent mark sweep GC freed 44238(2MB) AllocSpace objects, 24(384KB) LOS objects, 39% free, 13MB/22MB, paused 2.006ms total 139.160ms
,I/PhenotypeFlagCommitter( 1731): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1731): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  870): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 1731): propertyValue:false
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  870): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  870): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  870): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  870): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ClearcutLoggerApiImpl( 1731): disconnect managed GoogleApiClient
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 195589993887; DSPS: 6500469; Offset : -2799300001
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 215590756120; DSPS: 7155854; Offset : -2799302714
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 235591524759; DSPS: 7811239; Offset : -2799295086
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  478): init target 500000
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 298, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 255592396313; DSPS: 8466628; Offset : -2799308724
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 275593173128; DSPS: 9122013; Offset : -2799294744
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 295594016402; DSPS: 9777401; Offset : -2799306171
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): init target 500000
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  478): init target 500000
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 315594760196; DSPS: 10432786; Offset : -2799325473
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 335595411178; DSPS: 11088167; Offset : -2799314943
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/LocationManagerService(  870): remove a2d5c66
D/LocationManagerService(  870): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  870): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  870): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  870): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  870): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  870): acquireWakeLockInternal: lock=329609607, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=870
,D/PowerManagerServiceEx(  870): releaseWakeLockInternal: lock=329609607 [*alarm*], flags=0x0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  870): battery changed pluggedType: 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 355596148202; DSPS: 11743551; Offset : -2799310731
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 375596923194; DSPS: 12398936; Offset : -2799298731
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 395597623864; DSPS: 13054319; Offset : -2799299393
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 415598369689; DSPS: 13709704; Offset : -2799316611
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 294, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 435599116973; DSPS: 14365088; Offset : -2799301880
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 455599768476; DSPS: 15020470; Offset : -2799321738
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 475600737844; DSPS: 15675861; Offset : -2799298440
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  870): battery changed pluggedType: 2
I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 495601480492; DSPS: 16331246; Offset : -2799318627
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 515602137256; DSPS: 16986627; Offset : -2799302524
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 535602876206; DSPS: 17642011; Offset : -2799296491
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 555603620991; DSPS: 18297396; Offset : -2799314203
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 575604283639; DSPS: 18952778; Offset : -2799323254
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 595604952433; DSPS: 19608160; Offset : -2799325612
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 615605785446; DSPS: 20263547; Offset : -2799316678
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 635606446584; DSPS: 20918928; Offset : -2799296513
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 655607179493; DSPS: 21574312; Offset : -2799295714
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 675607894330; DSPS: 22229696; Offset : -2799315200
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 695608640988; DSPS: 22885080; Offset : -2799299583
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 715609375043; DSPS: 23540464; Offset : -2799297663
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
,D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 735610071286; DSPS: 24195847; Offset : -2799303222
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 755610720706; DSPS: 24851229; Offset : -2799326672
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 775611389344; DSPS: 25506610; Offset : -2799297392
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 795612153607; DSPS: 26161995; Offset : -2799296069
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 815612891516; DSPS: 26817380; Offset : -2799321073
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 835613549217; DSPS: 27472761; Offset : -2799304345
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 855614310615; DSPS: 28128146; Offset : -2799305836
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 875615059409; DSPS: 28783531; Offset : -2799320163
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 895615735340; DSPS: 29438913; Offset : -2799315254
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 915616405696; DSPS: 30094295; Offset : -2799316441
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 935617132512; DSPS: 30749679; Offset : -2799322073
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  870): acquireWakeLockInternal: lock=329609607, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=870
,V/AlarmManager(  870): ELAPSED_WAKEUP set : Alarm{2aaa3f67 type 2 when 952000 com.android.bluetooth} when 952000
D/PowerManagerServiceEx(  870): releaseWakeLockInternal: lock=329609607 [*alarm*], flags=0x0
,W/bt-smp  ( 1966): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1966): Plain text(LSB ~ MSB) = 9d 2b 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 1966): Encrypted text(LSB ~ MSB) = 7d 96 7c 9e 5d 0a 87 6d dd bb 2c 61 9d 3a 09 c3 
W/bt-btm  ( 1966): Stopping oneshot timer
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 955617791983; DSPS: 31405060; Offset : -2799303368
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 975618564058; DSPS: 32060446; Offset : -2799325192
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  870): acquireWakeLockInternal: lock=329609607, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=870
,V/AlarmManager(  870): ELAPSED_WAKEUP set : Alarm{3a789114 type 2 when 991709 com.google.android.gms} when 991709
I/ActivityManager(  870): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8050 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/art     (  301): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 425us total 59.316ms
,I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 410us total 35.177ms
I/art     (  301): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 399us total 31.215ms
,I/DigitalAppWidgetProvider( 8050): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8050): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@17550cb9
D/PowerManagerServiceEx(  870): releaseWakeLockInternal: lock=329609607 [*alarm*], flags=0x0
I/ActivityManager(  870): Killing 7618:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  870): failed to open /acct/uid_10011/pid_7618/cgroup.procs: No such file or directory
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 995619151760; DSPS: 32715825; Offset : -2799317506
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1015619842429; DSPS: 33371207; Offset : -2799297730
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1035620728932; DSPS: 34026596; Offset : -2799296287
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1055621463560; DSPS: 34681981; Offset : -2799324756
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1075622140688; DSPS: 35337363; Offset : -2799320732
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
,I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1095622820785; DSPS: 35992745; Offset : -2799310277
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1115623555152; DSPS: 36648129; Offset : -2799308229
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1135624241810; DSPS: 37303511; Offset : -2799292775
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  870): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  870): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  870): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1155624981543; DSPS: 37958896; Offset : -2799318064
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1175625643253; DSPS: 38614278; Offset : -2799325606
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1195626457516; DSPS: 39269664; Offset : -2799305269
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1215627201207; DSPS: 39925048; Offset : -2799294078
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/UsageStatsService(  870): User[0] Flushing usage stats to disk
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1235627883178; DSPS: 40580431; Offset : -2799315547
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1255628588691; DSPS: 41235814; Offset : -2799310089
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  870): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  870): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  870): tsOffsetIs: Apps: 1275629320871; DSPS: 41891198; Offset : -2799310514
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 8132): 
D/AndroidRuntime( 8132): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8132): CheckJNI is OFF
D/AndroidRuntime( 8132): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  870): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  870): Killing 5539:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
W/PackageSettings(  870): Skipping PackageSetting{222b9e19 com.example.hello/10317} due to missing metadata
I/WindowState(  870): WIN DEATH: Window{108a3c9a u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  870): Focus left window: Window{108a3c9a u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  870): Window went away: Window{108a3c9a u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  870):   Force finishing activity ActivityRecord{3feac500 u0 com.test.thalitest/.MainActivity t222}
V/ActivityManager(  870): Display changed displayId=0
D/DSDPConnection( 1745): Display #0 changed.
W/ActivityManager(  870): Spurious death for ProcessRecord{2b020dbd 5539:com.test.thalitest/u0a316}, curProc for 5539: null
I/ActivityManager(  870): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  870):   Force finishing activity ActivityRecord{3feac500 u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  870): Duplicate finish request for ActivityRecord{3feac500 u0 com.test.thalitest/.MainActivity t222 f}
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  870): Reconfiguring input devices.  changes=0x00000010
W/GeofencerStateMachine( 1731): Ignoring removeGeofence because network location is disabled.
W/System.err( 3568): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3568): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3568): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3568): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3568): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3568): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3568): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3568): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3568): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3568): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3568): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3568): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/art     ( 1940): Explicit concurrent mark sweep GC freed 21914(1369KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 11MB/19MB, paused 1.965ms total 97.651ms
I/ActivityManager(  870): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8164 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1876): [Launcher.java:5203:onStart()]onStart
I/art     ( 5521): Explicit concurrent mark sweep GC freed 14046(798KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 13MB/18MB, paused 891us total 115.823ms
I/[LGHome]EVENT( 1876): [Launcher.java:776:onResume()]onResume
I/[LGHome]EVENT( 1876): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[LGHome]LGActivityUtil( 1876): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1876): [Launcher.java:929:onResume()]onResume end
I/Activity( 1876): Activity.onPostResume() called 
I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
W/ResourcesManager( 1374): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1374): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1876): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1876): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourcesManager( 1374): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
I/SystemUI[Framework](  870): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  870): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  870): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  870): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  870): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@334a1603,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  870): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  870): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  870): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  870): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  870): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  870): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@334a1603,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  870): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourcesManager( 1374): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1374): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1374): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/InputDispatcher(  870): Focus entered window: Window{2f2bb11c u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourcesManager( 8164): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8164): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8164): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/art     (  870): Explicit concurrent mark sweep GC freed 74638(4MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 23MB/35MB, paused 2.179ms total 248.030ms
I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
I/art     (  870): WaitForGcToComplete blocked for 235.451ms for cause Explicit
D/KeyguardModel( 1374): handleShortcutListChanged...
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1876): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/InputMethodManagerService(  870): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
W/InputMethodManagerService(  870): Got RemoteException sending setActive(false) notification to pid 5539 uid 10316
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): handleShortcutListChanged...
D/administrator(  870): Handling package changes for user 0
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  870): Timeline: Activity_windows_visible id: ActivityRecord{236e8ff6 u0 com.lge.launcher2/.Launcher t221} time:1294691
I/LGEmail ( 8164): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
W/IInputConnectionWrapper( 1876): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/LGEmail ( 8164): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
E/b       ( 1574): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1876): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1876): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
W/IInputConnectionWrapper( 1876): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
I/NotificationService(  870): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  870): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  870): Receieved: android.intent.action.PACKAGE_REMOVED
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
D/TaskPersister(  870): removeObsoleteFile: deleting file=222_task.xml
D/PhoneStatusBar( 1374): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/art     (  870): Explicit concurrent mark sweep GC freed 8649(504KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 6.546ms total 419.066ms
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
I/PackageChangeReceiver( 8164): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/ActivityManager(  870): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8191 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  870): Killing 7572:com.google.android.talk/u0a61 (adj 15): empty #11
D/AndroidRuntime( 8132): Shutting down VM
E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  870): failed to open /acct/uid_10061/pid_7572/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/AppUp4:AppBoxCP( 8191): onCreate
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
W/AppUp4:DB( 8191):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 8191):  setFingerPrint start
I/AppUp4:DB( 8191):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/AppUp4:DB( 8191):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8191):  SDK version = 0
I/AppUp4:DB( 8191):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8191): AppBoxApplication onCreate()
D/AppUp4:PreloadHelper( 8191): added Exclude : com.test.thalitest
I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/ActivityManager(  870): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8208 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/ActivityManager(  870): Killing 7640:com.android.gallery3d/u0a23 (adj 15): empty #11
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/Timeline( 1876): Timeline: Activity_idle id: android.os.BinderProxy@69f05a5 time:1295300
W/libprocessgroup(  870): failed to open /acct/uid_10023/pid_7640/cgroup.procs: No such file or directory
I/art     ( 1876): Explicit concurrent mark sweep GC freed 27285(1482KB) AllocSpace objects, 19(2MB) LOS objects, 40% free, 15MB/25MB, paused 1.386ms total 64.623ms
W/ResourcesManager( 8208): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.

```
