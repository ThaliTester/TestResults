#### Test 57321924b5e4f25_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/UpdateIcingCorporaServi( 1939): UpdateCorporaTask done [took 156 ms] updated apps [took 155 ms] 
,D/Finsky  ( 5557): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/Finsky  ( 5557): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 5557): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5557): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5557): com.android.vending: cancel(-1050172287) by com.android.vending
I/NotificationManager( 5557): com.android.vending: cancel(1003285959) by com.android.vending
V/DownloadManager( 3247): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3247): created cursor android.database.sqlite.SQLiteCursor@3c2954e7 on behalf of 5557
D/Ads     ( 5557): Skipping gmscore version check
D/AndroidRuntime( 5588): 
D/AndroidRuntime( 5588): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5588): CheckJNI is OFF
D/Finsky  ( 5557): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5557): [1] Libraries$2.run: Finished loading 1 libraries.
--------- beginning of system
I/ActivityManager(  863): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5614 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/Finsky  ( 5557): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 5557): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/Finsky  ( 5557): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  863): Killing 5379:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/libprocessgroup(  863): failed to open /acct/uid_10009/pid_5379/cgroup.procs: No such file or directory
W/ResourcesManager( 5614): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5614): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 5614): VM with version 2.1.0 has multidex support
I/MultiDex( 5614): install
I/MultiDex( 5614): VM has multidex support, MultiDex support library is disabled.
D/AndroidRuntime( 5588): Calling main entry com.android.commands.am.Am
I/ActivityManager(  863): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  863): setTaskToReturnTo : TaskRecord{8d2a903 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  863): setTaskToReturnTo : TaskRecord{8d2a903 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  863): AppWindowTokenEx init.. 
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
D/ContextHelper(  863): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  863): Focus left window: Window{dfa3a6b u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5588): Shutting down VM
D/SplitWindow(  863): check instance of lgWin Window{26098575 u0 Starting com.test.thalitest}
I/ActivityManager(  863): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5646 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
V/JNIHelp ( 5614): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/HotwordDetector( 1939): Closing mic
I/MicrophoneInputStream( 1939): mic_close com.google.android.apps.gsa.speech.audio.u@2e4c9e87
V/AudioRecord( 1939): stop()
D/AudioRecord( 1939): AudioRecord->stop()
V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
V/AudioFlinger(  280): Record stopped OK
V/AudioPolicyManager(  280): stopInput() input 17
V/AudioPolicyService(  280): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  280): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  280): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  280): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  280): ThreadBase::setParameters() routing=0
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb3873000
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
I/WindowStateAnimator(  863): Starting window displayed
I/SystemUI[Framework](  863): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  863): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  863): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  863): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  863): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@135739c5,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  863): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1372): draw background and invalidate : color = 16000000
D/BarTransitions( 1372): draw background and invalidate : color = 100f0f0f
V/audio_hw_primary(  280): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  280): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  280): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  280): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  280): disable_audio_route: exit
E/audio_hw_primary(  280): disable_snd_device: enter 144
D/hardware_info(  280): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  280): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  280): stop_input_stream: exit: status(0)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioFlinger(  280): RecordThread: loop stopping
,V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  280): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  280): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  280): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyService(  280): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  280): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  280): setParameters(): io 17, keyvalue hotword_active=0, calling pid 280
V/AudioFlinger(  280): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  280): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  280): in_set_parameters: exit: status(0)
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb3873000
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
W/ActivityThread( 5614): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5614): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2132fc06: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5614): Installed default security provider GmsCore_OpenSSL
V/AudioRecord( 1939): stop()
V/AudioRecord( 1939): stop()
V/AudioRecord( 1939): stop()
I/NotificationManager( 5614): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5614): com.google.android.gms: cancel(39789) by com.google.android.gms
V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
V/AudioPolicyManager(  280): releaseInput() 17
V/AudioPolicyManager(  280): closeInput(17)
V/AudioFlinger(  280): closeInput() 17
V/AudioSystem(  280): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  863): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): ThreadBase::exit
V/AudioSystem( 1743): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioFlinger(  280): releasing 16 from 1939 for -1
V/AudioFlinger(  280):  decremented refcount to 0
V/AudioFlinger(  280): purging stale effects
V/AudioSystem( 2669): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): RecordThread 0xb3873000 exiting
V/AudioSystem( 1939): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1990): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  280): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioSystem( 1372): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  280): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  280): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio port list
V/AudioSystem( 3176): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): releaseInput() exit
V/AudioFlinger(  280): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  280): removeClient_l() pid 1939, calling pid 280
I/HotwordRecognitionRnr( 1939): Stopping hotword detection.
I/HotwordRecognitionRnr( 1939): Hotword detection finished
I/art     ( 4060): Explicit concurrent mark sweep GC freed 9418(461KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 2.490ms total 39.811ms
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ContextHelper( 5646): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/PackageBroadcastService( 5614): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 5614): Reading stored module config
D/ChimeraCfgMgr( 5614): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5614): Loading module APK com.google.android.play.games
I/WebViewFactory( 5646): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5646): Time to load native libraries: 3 ms (timestamps 1983-1986)
I/LibraryLoader( 5646): Expected native library version number "",actual native library version number ""
W/art     ( 5614): Suspending all threads took: 9.814ms
V/WebViewChromiumFactoryProvider( 5646): Binding Chromium to main looper Looper (main, tid 1) {2980aa6e}
I/LibraryLoader( 5646): Expected native library version number "",actual native library version number ""
I/chromium( 5646): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5646): Initializing chromium process, singleProcess=true
W/art     ( 5646): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5646): ApplicationContext is null in ApplicationStatus
D/NativeLibraryUtils( 5614): Install completed successfully. count=14 extracted=0
W/chromium( 5646): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5646): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5646): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5646): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5646): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5646): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5646): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5646): Remote Branch: 
I/Adreno-EGL( 5646): Local Patches: 
I/Adreno-EGL( 5646): Reconstruct Branch: 
I/art     ( 5614): CheckpointMarkThreadRoots callback created = 0xb042d3f0
I/art     ( 5614): CheckpointMarkThreadRoots callback created = 0xb042d3e0
,V/AudioPolicyService(  280): registerClient() client 0xb406f1c0, uid 10316
D/BluetoothManagerService(  863): Message: 20
,D/BluetoothManagerService(  863): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32762f74:true
D/BluetoothAdapterService(789643130)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2619fba0
D/ChimeraCfgMgr( 5614): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5614): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 5614): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 5614): Submit a task: k
,D/ChimeraCfgMgr( 5614): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 5614): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/PeopleDatabaseHelper( 5614): cleanUpNonGplusAccounts done.
,D/k       ( 5614): Processing package: com.test.thalitest
W/art     ( 5646): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5646): onDetachedFromWindow called when already detached. Ignoring
,D/GassUtils( 5614): Found app info for package com.test.thalitest:18. Hash: 82ccbc74df315987b7be206c22ec4eaa3ab0d49235c4895536307c8f71b675fe
D/k       ( 5614): Found info for package com.test.thalitest in db.
,I/Icing   ( 5614): Storage manager: low false usage 1.70MB avail 2.37GB capacity 4.06GB
D/SystemWebViewEngine( 5646): CordovaWebView is running on device made by: LGE
,W/art     ( 5646): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5646): Attempt to remove local handle scope entry from IRT, ignoring
,D/WearableService( 1732): callingUid 10006, callindPid: 1732
D/LocationInitializer( 5614): Restart initialization of location
,W/BaseAppContext( 5614): Using Auth Proxy for data requests.
E/MDM     ( 1732): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/art     ( 5614): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5614): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/Activity( 5646): Activity.onPostResume() called 
,D/OpenGLRenderer( 5646): Render dirty regions requested: true
I/OpenGLRenderer( 5646): Initialized EGL, version 1.4
,E/BaseAppContext( 5614): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
D/OpenGLRenderer( 5646): Enabling debug mode 0
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/Atlas   ( 5646): Validating map...
W/BaseAppContext( 5614): Using Auth Proxy for data requests.
D/SplitWindow(  863): check instance of lgWin Window{287bcd7d u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5646): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/InputDispatcher(  863): Focus entered window: Window{287bcd7d u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  863): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5739 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 22.880ms
,W/InputMethodManagerService(  863): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 22.345ms
I/ActivityManager(  863): Displayed com.test.thalitest/.MainActivity: +1s391ms
,I/Timeline(  863): Timeline: Activity_windows_visible id: ActivityRecord{2c831080 u0 com.test.thalitest/.MainActivity t222} time:82884
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 345us total 22.056ms
W/BaseAppContext( 5614): Using Auth Proxy for data requests.
I/Timeline( 5646): Timeline: Activity_idle id: android.os.BinderProxy@10408c15 time:82894
,W/BaseAppContext( 5614): Using Auth Proxy for data requests.
,W/BaseAppContext( 5614): Using Auth Proxy for data requests.
W/BaseAppContext( 5614): Using Auth Proxy for data requests.
W/BaseAppContext( 5614): Using Auth Proxy for data requests.
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
W/IcingInternalCorpora( 5614): getNumBytesRead when not calculated.
,W/BindingManager( 5646): Cannot call determinedVisibility() - never saw a connection for the pid: 5646
,W/ActivityManager(  863): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/art     ( 5614): Background sticky concurrent mark sweep GC freed 16167(1460KB) AllocSpace objects, 14(224KB) LOS objects, 11% free, 12MB/14MB, paused 7.319ms total 96.265ms
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Icing   ( 5614): updateResources: need to parse f{com.google.android.gms}
,I/Gmail   ( 5739): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 17786(1059KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 13MB/22MB, paused 2.307ms total 112.229ms
D/JsMessageQueue( 5646): Set native->JS mode to OnlineEventsBridgeMode
,W/GAV2    ( 5739): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/ChimeraCfgMgr( 5614): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5614): Module APK com.google.android.play.games already loaded
,W/ActivityManager(  863): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 5739): Error finding the version of the Email provider.....
E/Gmail   ( 5739): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5739): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5739): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5739): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5739): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5739): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5739): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5739): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 5739): We do not support migrating this version of the Email provider.
I/Gmail   ( 5739): getAccountsCursor
W/ActivityManager(  863): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 5739): Observing account changes for notifications
W/ActivityManager(  863): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  863): Killing 5402:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/jxcore_app_log( 5646): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426203648
,I/chromium( 5646): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,W/libprocessgroup(  863): failed to open /acct/uid_10011/pid_5402/cgroup.procs: No such file or directory
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,I/art     ( 4060): Explicit concurrent mark sweep GC freed 1378(47KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.005ms total 50.640ms
V/DownloadManager( 3247): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3247): created cursor android.database.sqlite.SQLiteCursor@721b894 on behalf of 5614
,W/InstanceID/Rpc( 5614): Found 10006
,I/art     ( 5646): CheckpointMarkThreadRoots callback created = 0x9a1a8640
,I/art     ( 5646): CheckpointMarkThreadRoots callback created = 0x9a1a8610
,I/Icing   ( 5614): Internal init done: storage state 0
,I/ActivityManager(  863): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5798 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
D/InitAlarmsService( 3874): Clearing and rescheduling alarms.
I/NotificationManager( 5614): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/ActivityManager(  863): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5815 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/DownloadManager( 3247): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3247): created cursor android.database.sqlite.SQLiteCursor@2610df3d on behalf of 5614
,V/DownloadManager( 3247): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
I/Gmail   ( 5739): notifyAccountChanged
V/DownloadManager( 3247): created cursor android.database.sqlite.SQLiteCursor@3f61d332 on behalf of 5614
I/art     (  863): Explicit concurrent mark sweep GC freed 31312(1468KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.611ms total 204.968ms
I/Gmail   ( 5739): getAccountsCursor
,I/Gmail   ( 5739): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 5614): Post-init done
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 5815): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/Gmail   ( 5739): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5739): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5739): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/art     ( 5614): Background sticky concurrent mark sweep GC freed 9502(704KB) AllocSpace objects, 7(112KB) LOS objects, 6% free, 13MB/14MB, paused 8.631ms total 60.903ms
,D/CalendarProvider2( 5815): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@297f2fed
D/CalendarProvider2( 5815): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5815): Created com.android.providers.calendar.CalendarAlarmManager@2980aa6e(com.android.providers.calendar.CalendarProvider2@297f2fed)
D/CalendarProvider2( 5815): Scheduling check of next Alarm
,D/CalendarProvider2( 5815): SCHEDULE_ALARM_REMOVE
D/PhoneMonitor( 5798): Register our PhoneStateListener
,I/ActivityManager(  863): Process com.android.contacts (pid 5438) has died
,I/ActivityManager(  863): Killing 3874:com.android.calendar/u0a13 (adj 15): empty #11
,D/PhoneMonitor( 5798): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5798): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5798): [parse] Load xml
V/TelephonyAutoProfiling( 5798): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 5798): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 5798): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/CheckinService( 5614): Checkin interval check for package: unspecified last checkin: 1453879752900 min interval config: 0 actual interval: 7815
,I/Gmail   ( 5739): getAccountsCursor
,I/CheckinService( 5614): Disabling old GoogleServicesFramework version
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  863): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5845 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/CheckinService( 5614): Checking schedule, now: 1453879760859 next: 1453879782845
,I/CheckinService( 5614): active receiver: disabled
I/ActivityManager(  863): Process com.android.gallery3d (pid 5419) has died
,W/ResourcesManager( 5845): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5845): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5845): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5845): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5845): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5845): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5845): MmsConfig.loadFromResources
,E/Babel_SMS( 5845): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5845): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Icing   ( 5614): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/ActivityManager(  863): Process com.lge.lockscreensettings (pid 5457) has died
D/SensorManager( 5845): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5845): found sensor: LGE Magnetometer Sensor, handle=10
,D/SensorManager( 5845): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5845): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5845): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5845): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5845): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5845): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5845): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5845): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5845): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5845): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5845): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5845): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5845): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5845): found sensor: Motion Accel, handle=46
I/art     ( 5845): CheckpointMarkThreadRoots callback created = 0xb042d880
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/Settings( 5845): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 5845): CheckpointMarkThreadRoots callback created = 0xb042d850
,I/Babel_Crash( 5845): startup - clean
W/art     ( 5614): Suspending all threads took: 6.163ms
,I/Babel   ( 5845): deleted: false for 0
I/art     ( 5614): Background sticky concurrent mark sweep GC freed 2562(202KB) AllocSpace objects, 5(80KB) LOS objects, 2% free, 14MB/14MB, paused 9.451ms total 42.430ms
W/art     ( 5845): Suspending all threads took: 5.207ms
,D/Icing   ( 5614): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 5614): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  863): Process com.lge.eula (pid 5474) has died
,W/AudioCapabilities( 5845): Unsupported mime audio/x-lg-flac
,I/CalendarProvider2( 5815): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5815): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
W/AudioCapabilities( 5845): Unsupported mime audio/adpcm
W/AudioCapabilities( 5845): Unsupported mime audio/g726
W/AudioCapabilities( 5845): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 5845): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5845): Unsupported mime video/mjpg
W/VideoCapabilities( 5845): Unsupported mime video/theora
,W/AudioCapabilities( 5845): Unsupported mime audio/evrc
,W/AudioCapabilities( 5845): Unsupported mime audio/qcelp
W/VideoCapabilities( 5845): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5845): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5845): Unsupported mime audio/qcelp
W/AudioCapabilities( 5845): Unsupported mime audio/evrc
W/VideoCapabilities( 5845): Unsupported mime video/mp4v-esdp
,I/ActivityManager(  863): Process com.lge.bnr (pid 5259) has died
I/VideoCapabilities( 5845): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5845): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5845): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5845): Unrecognized profile 2130706433 for video/avc
W/jxcore-log( 5646): Initializing JXcore engine
I/ActivityManager(  863): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5873 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/jxcore-log( 5646): JXcore engine is ready
I/AudioManager( 5229): getMode name:com.lge.qremote
,W/VideoCapabilities( 5845): Unrecognized profile 2130706433 for video/avc
I/AudioManager( 5229): getMode name:com.lge.qremote
I/vclib   ( 5845): onServiceConnected
W/Babel   ( 5845): Attempted to change video mute state without an active call.
I/AudioManager( 5229): getMode name:com.lge.qremote
,I/NotificationManager( 5845): com.google.android.talk: cancel(10436) by com.google.android.talk
I/AudioManager( 5229): getMode name:com.lge.qremote
,I/AudioManager( 5229): getMode name:com.lge.qremote
E/MDM     ( 1732): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/Thread-676( 5788): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6513]" dev="sockfs" ino=6513 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-676( 5788): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-676( 5788): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8483]" dev="sockfs" ino=8483 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-676( 5788): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-676( 5788): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-676( 5788): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26748]" dev="sockfs" ino=26748 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5614): Restart initialization of location
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 5873): Quickset Services start...
W/jxcore-log( 5646): Starting JXcore engine
I/UEI.SmartControl( 5873): Manufacture = LGE
I/AudioManager( 5229): getMode name:com.lge.qremote
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,D/UEI.SmartControl( 5873): File observer start...
E/UEI.SmartControl( 5873): IR Port is disabled: false
D/UEI.SmartControl( 5873): Starting file observer...
D/UEI.SmartControl( 5873): Extracting JNI libs...
D/UEI.SmartControl( 5873): --- this system supports 32-bit or 64-bit only
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,W/ResourcesManager( 5845): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5845): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/NotificationManager( 5845): com.google.android.talk: cancel(8) by com.google.android.talk
,I/ActivityManager(  863): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5900 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/jxcore-log( 5646): Platform android
W/jxcore-log( 5646): 
,W/jxcore-log( 5646): Process ARCH arm
W/jxcore-log( 5646): 
,V/JNIHelp ( 5845): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 5900): onCreate
W/AppUp4:DB( 5900):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5900):  setFingerPrint start
I/AppUp4:DB( 5900):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 5900):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5900):  SDK version = 0
,I/AppUp4:DB( 5900):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5900): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 5900): onReceive
I/AppUp4:CustModeStarterReceiver( 5900): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 5900): Context : android.app.ReceiverRestrictedContext@bdc1670
D/AppUp4:CustFacade( 5900): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 5900): isSimDevice : true
W/ActivityManager(  863): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
D/AppUp4:CustModeStarterReceiver( 5900): begin check event
I/AppUp4:CustModeStarterReceiver( 5900): Event For Nothing, skip.
V/AlarmManager(  863): RTC_WAKEUP set : Alarm{13145c06 type 0 when 1453706911660 com.android.providers.contacts} when 1453706911660
,V/AlarmManager(  863): ELAPSED_WAKEUP set : Alarm{65932c7 type 2 when 60428 com.google.android.talk} when 60428
V/AlarmManager(  863): RTC_WAKEUP set : Alarm{6eba01d type 0 when 1453879762341 com.google.android.googlequicksearchbox} when 1453879762341
I/ActivityManager(  863): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5919 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/UEI.SmartControl( 5873): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5873): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5873): --- Extracting JNI libs: libqs_armeabi-v7a.zip
W/System  ( 5845): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5845): Installed default security provider GmsCore_OpenSSL
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/UEI.SmartControl( 5873): --- Selecting new region: 2
I/UEI.SmartControl( 5873): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5873): Platform has CIR...
D/UEI.SmartControl( 5873): NO CIR support, need to check package...
I/UEI.SmartControl( 5873): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5873): QS Service created
,W/ResourcesManager( 5919): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5919): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5919): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
E/UEI.SmartControl( 5873): QS start get config
,D/UEI.SmartControl( 5873): Loading JNI Libs...
,D/UEI.SmartControl( 5873):  configuring local db...
I/AppConfig( 5919): Total System Memory = 906309632
,I/GalleryUtils( 5919): Application Heap = 96 MB
I/AppConfig( 5919): App Tier : NOT_DEF
D/SystemHelper( 5919): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  863): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5943 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/jxcore-log( 5646): JXcore Cordova bridge is ready!
I/jxcore-log( 5646): 
W/jxcore-log( 5646): JXcore engine is started
,D/UEI.SmartControl( 5873):  ---- Has DB8: true
D/UEI.SmartControl( 5873): QS start statue = true Error code = 0
D/UEI.SmartControl( 5873): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 5873): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
W/ResourcesManager( 5943): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5943): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5943): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5943): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5943): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5873): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5873): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5873): IrrcClient ++ 
D/irrcClient( 5873): getIrrcService ++ 
,D/irrcClient( 5873): getIrrcService -- 
D/irrcClient( 5873): IrrcClient -- 
W/irrc_jni( 5873): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5873): Services init done
I/UEI.SmartControl( 5873): Device manager: loading config....
D/UEI.SmartControl( 5873): QS Service init finished
,D/UEI.SmartControl( 5873): QS Service version name: 0.1.73
D/UEI.SmartControl( 5873): QS Service version code: 1073
D/UEI.SmartControl( 5873): Service requested: Control
D/UEI.SmartControl( 5873): Config is loaded...
D/UEI.SmartControl( 5873):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5873): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 5873): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 5873): Internal service binding...
D/UEI.SmartControl( 5873): -----IControl: 11
D/UEI.SmartControl( 5873): Caller: com.lge.qremote
D/UEI.SmartControl( 5873): ------------ IControl registerCallback...
I/UEI.SmartControl( 5873): Registering callback...
D/UEI.SmartControl( 5873): -----IControl: 19
,D/UEI.SmartControl( 5873): Caller: com.lge.qremote
I/UEI.SmartControl( 5873): Registering Services Ready callback...
I/UEI.SmartControl( 5873): Notify client services are ready...
D/UEI.SmartControl( 5873): -----IControl: 8
D/UEI.SmartControl( 5873): Caller: com.lge.qremote
I/ActivityManager(  863): Killing 5491:com.google.android.apps.docs/u0a58 (adj 15): empty #11
,I/SystemConfig( 5943): BUILD Country: EU
I/SystemConfig( 5943): BUILD Operator: OPEN
,I/jxcore-log( 5646): Toggling radios to true
I/jxcore-log( 5646): 
,D/BluetoothAdapter( 5646): enable(): BT is already enabled..!
W/libprocessgroup(  863): failed to open /acct/uid_10058/pid_5491/cgroup.procs: No such file or directory
,I/[SystemUI]QPairHandler( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
D/WifiServiceImplEx(  863): setWifiEnabled: true pid=5646, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
D/WifiService(  863): setWifiEnabled: true pid=5646, uid=10316
,I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/InputReader(  863): Reconfiguring input devices.  changes=0x00000010
D/WifiServiceImplEx(  863): disconnect pid=5646, uid=10316, packageName=com.test.thalitest
,D/administrator(  863): Handling package changes for user 0
I/ActivityManager(  863): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5969 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  863): Killing 5526:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
,D/WifiServiceImplEx(  863): reconnect pid=5646, uid=10316, packageName=com.test.thalitest
I/wpa_supplicant( 2813): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/jxcore-log( 5646): Radios toggled
I/jxcore-log( 5646): 
I/jxcore-log( 5646): My device name is: LGE-LG-D722
I/jxcore-log( 5646): 
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2813): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  863): WifiStateMachine: Leaving Connected state
D/WfdsMonitor( 1803): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiConfigStore(  863): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/LGWifiP2pService(  863): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  863): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/libprocessgroup(  863): failed to open /acct/uid_10086/pid_5526/cgroup.procs: No such file or directory
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
,D/DhcpStateMachine(  863): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
D/CommandListener(  275): Clearing all IP addresses on wlan0
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 7
,I/SystemConfig( 5943): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5943): existFile = false
,I/SystemConfig( 5943): canReadFile = false
I/SystemConfig( 5943): systemFeature RCS result false
D/SystemConfig( 5943): refreshRcsSupport() :false
V/NativeCrypto( 1732): Read error: ssl=0xaaee0000: I/O error during system call, Connection timed out
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 7
D/ConnectivityService(  863): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  863): ignoring duplicate network state non-change
V/NativeCrypto( 1732): SSL shutdown failed: ssl=0xaaee0000: I/O error during system call, Broken pipe
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 08:29:23.234 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  863): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/WifiStateMachine(  863): Start Disconnecting Watchdog 1
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 08:29:23.249 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/wpa_supplicant( 2813): wlan0: CTRL-EVENT-SCAN-STARTED 
D/LGWifiP2pService(  863): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  863): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  863): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
,I/LockScreenSettings( 5969): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): ValidatedState{ when=-6ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): DefaultState{ when=-16ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): Forcing reevaluation
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
,D/LockScreenSettings( 5969): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5969): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5969): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5969): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5969): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
,I/ActivityManager(  863): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5992 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  863): Killing 5557:com.android.vending/u0a36 (adj 15): empty #11
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
,D/DhcpStateMachine(  863): StoppedState
D/DhcpStateMachine(  863): StoppedState{ when=-173ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/NotificationService(  863): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  863): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  863): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/CommandListener(  275): Clearing all IP addresses on wlan0
D/ConnectivityService(  863): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  863): disableDataServiceNotify
D/DSQN    (  863): stop dsqn bin
,I/ActivityManager(  863): Process com.google.android.gm (pid 5739) has died
W/libprocessgroup(  863): failed to open /acct/uid_10036/pid_5557/cgroup.procs: No such file or directory
,I/BackupManagerService(  863): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/ConnectivityService(  863): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 08:29:23.511 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WifiNetworkAgent(  863): NetworkAgent: NetworkAgent channel lost
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/WifiHS20(  863): hidePasspointNotification off =false
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiHS20(  863): hidePasspointNotification off =false
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityService(  863): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/Nat464Xlat(  863): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): Disconnected - quitting
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524292
D/WifiHS20(  863): hidePasspointNotification off =false
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/BackupManagerService(  863): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  863): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2d542576
D/CSLegacyTypeTracker(  863): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_,VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  863): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityService(  863): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  863): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  863): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  863): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  863): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/ConnectivityService(  863): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyNetworkFactory-1( 1743): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1743):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/Tethering(  863): MasterInitialState.processMessage what=3
D/Tethering(  863): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1840): |CORE| No family connected
W/QCNEJ   ( 1840): |CORE| No family connected
I/QCNEJ   ( 1840): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
V/NetworkPolicy(  863): [LG_RESTRICTED] !!!isConnected  type  :1
V/NetworkPolicy(  863): [LG_RESTRICTED] !!!isConnected  type  :1
D/NetworkManagementService(  863): Removing idletimer
I/QCNEJ   ( 1840): |CORE| sendDefaultNwMsg: default = -1
W/Settings(  863): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiHS20(  863): hidePasspointNotification off =false
,W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt(  863): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  863): setSupplicantStateDISCONNECTED
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 08:29:23.566 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 08:29:23.566 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WIFI    (  863): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  863):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/WifiServerServiceExt(  863): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  863): setSupplicantStateSCANNING
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
,W/ResourcesManager( 5992): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
W/ResourcesManager(  863): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
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
,W/ResourceType(  863): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
D/LocationProviderProxy(  863): applying state to connected service
,I/art     (  863): Explicit concurrent mark sweep GC freed 41162(2010KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.594ms total 157.589ms
,E/lowmemorykiller(  242): Error opening /proc/5229/oom_score_adj; errno=2
I/UpdateIcingCorporaServi( 1939): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ActivityManager(  863): Process com.lge.qremote (pid 5229) has died
,I/UpdateIcingCorporaServi( 1939): UpdateCorporaTask done [took 54 ms] updated apps [took 54 ms] 
I/ActivityManager(  863): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6026 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2813): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
I/wpa_supplicant( 2813): wlan0: Associated with c0:ff:d4:d3:aa:48
,I/wpa_supplicant( 2813): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2813): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 4
,I/ActivityManager(  863): Process com.uei.lg.quicksetsdk.lite (pid 5873) has died
,D/LocSvc_java(  863): onReceive
,I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 08:29:24.622 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 08:29:24.64 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 08:29:24.641 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 08:29:24.643 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/WifiServiceExtension(  863): setVHTCapabilityType  : false
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
I/WifiServerServiceExt(  863): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServerServiceExt(  863): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  863): setSecurityType  : 2
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 08:29:24.708 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-01-27 08:29:24.711 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/ConnectivityService(  863): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  863): Got NetworkAgent Messenger
D/ConnectivityService(  863): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  863): NetworkAgent connected
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
E/WifiConfigStore(  863): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
E/WifiConfigStore(  863): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  275): Setting iface cfg
E/WifiStateMachine(  863): Start Dhcp Watchdog 2
D/DhcpStateMachine(  863): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  863): WaitBeforeStartState
D/WifiServerServiceExt(  863): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  863): setSupplicantStateASSOCIATING
D/WifiServerServiceExt(  863): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  863): setSupplicantStateASSOCIATED
D/WifiServerServiceExt(  863): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  863): setSupplicantStateFOUR_WAY_HANDSHAKE
D/WifiServerServiceExt(  863): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  863): setSupplicantStateGROUP_HANDSHAKE
,D/ConnectivityService(  863): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/Finsky  ( 6026): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/WifiStateMachine(  863): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
,V/DhcpStateMachine(  863): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  863): InactiveState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@37bbb0f0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  863): P2pEnabledState{ when=-1ms what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@37bbb0f0 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  863): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
V/LgDhcpStateMachineHelper(  863): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/DhcpStateMachine(  863): DHCP Start wake lock is acquired.
D/CommandListener(  275): Setting iface cfg
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  275): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  863): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/WifiServerServiceExt(  863): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  863): setSupplicantStateCOMPLETED
,D/ConnectivityService(  863): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  863): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  863): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  863): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  863): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  863): ignoring duplicate network state non-change
,W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-27 08:29:24.891 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/ConnectivityService(  863): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-27 08:29:24.893 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  863): Adding iface wlan0 to network 101
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-27 08:29:24.904 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
E/WifiStateMachine(  863): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/WifiHS20(  863): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = true, mWifiLevel = 2
D/WifiHS20(  863): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1840): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-27 08:29:24.911 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1840): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
,W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
E/ConnectivityService(  863): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  863): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  863): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
,D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  275): netlink response contains error (File exists)
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = true, mWifiLevel = 2
D/ConnectivityService(  863): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  863): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  863): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  863): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  863): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  863): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  863): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  863): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  863):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  863):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  863):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  863):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  863):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  863): currentScore = 0, newScore = 20
D/ConnectivityService(  863):    accepting network in place of null
D/ConnectivityService(  863): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/WIFI    (  863): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
D/WIFI    (  863):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
D/TelephonyNetworkFactory-1( 1743): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
D/TelephonyNetworkFactory-1( 1743):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
E/ConnectivityService(  863): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  863): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  863): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  863): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  863): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  863): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
W/QCNEJ   ( 1840): |CORE| No family connected
I/QCNEJ   ( 1840): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): [LWD] Start DNSResolver start to wait
I/QCNEJ   ( 1840): |CORE| sendDefaultNwMsg: default = 1
D/Tethering(  863): MasterInitialState.processMessage what=3
D/ConnectivityService(  863): validation of new default Network = false
D/Connectivit,yService(  863): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  863): enableDataServiceNotify 
D/DSQN    (  863): start dsqn bin
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): [LWD] wait 500ms before dns check
V/AlarmManager(  863): ELAPSED_WAKEUP set : Alarm{318441c8 type 2 when 89316 com.google.android.gms} when 89316
,V/NetworkPolicy(  863): [LG_RESTRICTED] checkMobilePolicy_type()
I/CheckinService( 5614): Checkin interval check for package: unspecified last checkin: 1453879752900 min interval config: 0 actual interval: 12071
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
D/ConnectivityService(  863): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  863): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524290
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/DSQN    ( 6070): DSQN samuel.seo ver 141203
E/DSQN    ( 6070): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6070): created command queue thread
I/CheckinService( 5614): Checking schedule, now: 1453879764999 next: 1453879782845
I/CheckinService( 5614): active receiver: disabled
,I/DSQN    ( 6070): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6070): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/DhcpStateMachine(  863): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  863): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  863): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/dhcpcd  ( 6075): version 5.5.6 starting
E/dhcpcd  ( 6075): get_duid: Read-only file system
,D/Finsky  ( 6026): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6026): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6026): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6026): com.android.vending: cancel(-1050172287) by com.android.vending
I/dhcpcd  ( 6075): wlan0: rebinding lease of 192.168.1.134
,V/DownloadManager( 3247): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3247): created cursor android.database.sqlite.SQLiteCursor@15ac5883 on behalf of 6026
D/Ads     ( 6026): Skipping gmscore version check
,D/Finsky  ( 6026): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6026): [1] Libraries$2.run: Finished loading 1 libraries.
I/dhcpcd  ( 6075): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
D/Finsky  ( 6026): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 5614): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 6026): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  863): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6096 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/dhcpcd  ( 6075): wlan0: leased 192.168.1.134 for 86400 seconds
,I/PackageBroadcastService( 5614): Null package name or gms related package.  Ignoreing.
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 357us total 23.255ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 25.424ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 24.889ms
,I/Icing   ( 5614): updateResources: need to parse f{com.google.android.gms}
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): [LWD] DNSResolver start dns
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out(  863): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): Checking http://clients3.google.com/generate_204 on "NG700"
,V/AlarmManager(  863): ELAPSED_WAKEUP set : Alarm{37c68c5b type 2 when 89860 com.android.providers.calendar} when 89860
I/art     ( 5614): Background partial concurrent mark sweep GC freed 24728(1414KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 13MB/21MB, paused 1.892ms total 119.106ms
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 6070): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6070): restart monitoring
I/DSQN    ( 6070): dsqn report finish
,D/LGDataListener(  275): argv[0]=dsqncommand
D/LGDataListener(  275): argv[1]=wlan0
D/LGDataListener(  275): argv[2]=1
D/LGDataListener(  275): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  863): DSQM DsqnNotification wlan0  1
D/DSQN    (  863): start to monitor internet connection
W/ResourcesManager( 6096): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jan 2016 07:29:25 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1453879765559], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1453879765540]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  863): Validated
D/ConnectivityService(  863): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  863): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  863):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  863):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  863):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  863): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  863): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  863): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  863): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  863): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524290
D/WIFI    (  863): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1743): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  863):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1743):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiDataContinuityService(  863): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  863): set CMD_CAPTIVE_CHECK_COMPLETED
,D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/BluetoothManagerService(  863): Message: 20
D/BluetoothManagerService(  863): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1281180e:true
,D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  863): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  863): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  863): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  863): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  863): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  863): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  863): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  863): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  863): RunningState
,D/BluetoothAdapterService(789643130)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2619fba0
D/BluetoothAdapterService(789643130)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2619fba0
I/ActivityManager(  863): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6144 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6096): Create singleton instance
,I/AudioManager( 6096): getMode name:com.lge.qremote
,D/UEI.SmartControl( 6144): Quickset Services start...
I/UEI.SmartControl( 6144): Manufacture = LGE
,D/UEI.SmartControl( 6144): File observer start...
E/UEI.SmartControl( 6144): IR Port is disabled: false
D/UEI.SmartControl( 6144): Starting file observer...
D/UEI.SmartControl( 6144): Extracting JNI libs...
D/UEI.SmartControl( 6144): --- this system supports 32-bit or 64-bit only
I/AudioManager( 6096): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  863): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6164 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,D/UEI.SmartControl( 6144): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6144): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6144): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/ConnectivityService(  863): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/UEI.SmartControl( 6144): --- Selecting new region: 2
I/UEI.SmartControl( 6144): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6144): Platform has CIR...
D/UEI.SmartControl( 6144): NO CIR support, need to check package...
,I/UEI.SmartControl( 6144): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6144): QS Service created
,E/UEI.SmartControl( 6144): QS start get config
D/UEI.SmartControl( 6144): Loading JNI Libs...
,D/UEI.SmartControl( 6144):  configuring local db...
,I/ActivityManager(  863): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6189 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,D/UEI.SmartControl( 6144):  ---- Has DB8: true
,D/UEI.SmartControl( 6144): QS start statue = true Error code = 0
,D/UEI.SmartControl( 6144): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6144): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
I/Netd    (  275): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/UEI.SmartControl( 6144): IRRCDataComm has AudioManager!!!!.
D/ConnectivityService(  863): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  863): identical MTU - not setting
,D/Nat464Xlat(  863): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  863): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  863):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-27 08:29:26.402 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/ConnectivityService(  863): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  863): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  863): enableDataServiceNotify 
D/DSQN    (  863): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524295
W/irrc_jni( 6144): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6144): IrrcClient ++ 
D/irrcClient( 6144): getIrrcService ++ 
D/irrcClient( 6144): getIrrcService -- 
D/irrcClient( 6144): IrrcClient -- 
W/irrc_jni( 6144): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6144): Services init done
,I/UEI.SmartControl( 6144): Device manager: loading config....
D/UEI.SmartControl( 6144): QS Service init finished
D/UEI.SmartControl( 6144): QS Service version name: 0.1.73
D/UEI.SmartControl( 6144): QS Service version code: 1073
D/UEI.SmartControl( 6144): Service requested: Control
D/UEI.SmartControl( 6144): Config is loaded...
,D/DSQN    (  863): dsqn is running restart
,D/UEI.SmartControl( 6144):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6144): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6144): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6144): Internal service binding...
E/UpdateRequestReceiver( 6189): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/UEI.SmartControl( 6144): -----IControl: 11
D/UEI.SmartControl( 6144): Caller: com.lge.qremote
D/UEI.SmartControl( 6144): ------------ IControl registerCallback...
I/UEI.SmartControl( 6144): Registering callback...
I/DSQN    ( 6215): DSQN samuel.seo ver 141203
,E/DSQN    ( 6215): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6215): created command queue thread
I/DSQN    ( 6215): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6215): Interface wlan0 netmask 255.255.255.0 0xc0a80186
D/UEI.SmartControl( 6144): -----IControl: 19
D/UEI.SmartControl( 6144): Caller: com.lge.qremote
I/UEI.SmartControl( 6144): Registering Services Ready callback...
E/UpdateRequestReceiver( 6189): Received malformed URL while handling Gservices.CHANGED_ACTION
I/UEI.SmartControl( 6144): Notify client services are ready...
D/UEI.SmartControl( 6144): -----IControl: 8
D/UEI.SmartControl( 6144): Caller: com.lge.qremote
E/UpdateRequestReceiver( 6189): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 6189): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/ActivityManager(  863): Killing 5798:com.google.android.setupwizard/u0a38 (adj 15): empty #11
D/ConnectivityService(  863): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup(  863): failed to open /acct/uid_10038/pid_5798/cgroup.procs: No such file or directory
,D/ConnectivityService(  863): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
I/ActivityManager(  863): Killing 5900:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/GpsLocationProvider(  863): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  863): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  863): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/LocSvc_java(  863): onReceive
D/LocSvc_java(  863): got connectivity action
D/GpsLocationProvider(  863): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,D/LocSvc_java(  863): broadcast - no network connections
D/LocSvc_java(  863): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  863): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  863): onReceive
D/LocSvc_java(  863): got connectivity action
D/LocSvc_java(  863): broadcast - no network connections
D/LocSvc_java(  863): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  863): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  863): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  863): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  863): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  863): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  863): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  863): ignore wifi update if we are not in OPENING or CLOSING
I/Icing   ( 5614): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/ActivityManager(  863): Killing 5815:com.android.providers.calendar/u0a14 (adj 15): empty #12
,I/Icing   ( 5614): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,W/libprocessgroup(  863): failed to open /acct/uid_10014/pid_5815/cgroup.procs: No such file or directory
,W/libprocessgroup(  863): failed to open /acct/uid_10011/pid_5900/cgroup.procs: No such file or directory
I/CheckinService( 5614): Checkin interval check for package: unspecified last checkin: 1453879752900 min interval config: 0 actual interval: 13949
,I/CheckinService( 5614): Checking schedule, now: 1453879766866 next: 1453879782845
I/CheckinService( 5614): active receiver: disabled
I/GservicesUpdateTask( 1939): Updating Gservices keys
,I/SystemUpdateService( 5614): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 5614): onCreate
,D/SystemUpdateService( 5614): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 5614): cancelUpdate (empty URL)
I/SystemUpdateService( 5614): active receiver: disabled
,I/NotificationManager( 5614): com.google.android.gms: cancel(2130838165) by com.google.android.gms
I/NotificationManager( 5614): com.google.android.gms: cancel(2130838166) by com.google.android.gms
,I/art     ( 4060): Explicit concurrent mark sweep GC freed 4213(181KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 400us total 27.728ms
,I/art     ( 4060): Explicit concurrent mark sweep GC freed 2737(106KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 392us total 23.864ms
,D/SystemUpdateService( 5614): onDestroy
,I/art     ( 5614): Explicit concurrent mark sweep GC freed 20274(1244KB) AllocSpace objects, 10(160KB) LOS objects, 25% free, 13MB/17MB, paused 846us total 81.380ms
,E/DynamiteModule( 5614): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 5614): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 5614): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 5614): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 5614): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 5614): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 5614): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 5614): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 5614): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 5614): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 5614): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 5614): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/DynamiteModule( 5614): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/DynamiteModule( 5614): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/DynamiteModule( 5614): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 5614): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 5614): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/DynamiteModule( 5614): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 5614): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 5614): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/DynamiteModule( 5614): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/DynamiteModule( 5614): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 5614): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 5614): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 5614): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 5614): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 5614): 		... 17 more
E/DynamiteModule( 5614): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
,I/DynamiteModule( 5614): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 5614): Selected local version of com.google.android.gms.flags
I/NotificationManager( 1939): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/ActivityManager(  863): Killing 5845:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  863): failed to open /acct/uid_10061/pid_5845/cgroup.procs: No such file or directory
,D/SystemEventReceiver( 5614): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 5614): Updating ocr activity enabled=false
,I/QCNEJ   ( 1840): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1840): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-01-27 08:29:27.787 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/WifiInternetCheck(  863): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ConnectivityService(  863): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  863): onReceive
D/LocSvc_java(  863): got connectivity action
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  863): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  863): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  863): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  863): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  863): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  863): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  863): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
W/ActivityManager(  863): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 5614): Updating downloaded model state (gservices changed)
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 20509(1387KB) AllocSpace objects, 23(368KB) LOS objects, 40% free, 13MB/22MB, paused 2.121ms total 111.718ms
,I/art     ( 4060): Explicit concurrent mark sweep GC freed 2584(102KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.858ms total 29.043ms
,I/NotificationManager(  863): android: cancelAsUser(-591465577) by android
,D/GCM     ( 1732): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/ActivityManager(  863): Killing 5919:com.android.gallery3d/u0a23 (adj 15): empty #11
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
,I/System.out( 1732): propertyValue:false
I/DSQN    ( 6215): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6215): restart monitoring
D/LGDataListener(  275): argv[0]=dsqncommand
D/LGDataListener(  275): argv[1]=wlan0
D/LGDataListener(  275): argv[2]=1
D/LGDataListener(  275): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  863): DSQM DsqnNotification wlan0  1
D/DSQN    (  863): start to monitor internet connection
I/DSQN    ( 6215): dsqn report finish
,W/libprocessgroup(  863): failed to open /acct/uid_10023/pid_5919/cgroup.procs: No such file or directory
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     (  863): Explicit concurrent mark sweep GC freed 75910(3MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 7.069ms total 167.384ms
I/GCoreUlr( 1732): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1732): DispatchingService.onCreate()
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  863): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6273 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/GCoreUlr( 1732): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
,D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
E/ctxmgr  ( 1732): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,D/PhoneMonitor( 6273): Register our PhoneStateListener
,D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out(  863): propertyValue:false
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  863): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  863): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out(  863): propertyValue:false
V/SetupWizard( 6273): Connected to Gservices successfully
,V/WifiInternetCheck(  863): isHttpConnectionAvailable - We got a valid response : 204
,D/PhoneMonitor( 6273): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6273): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6273): [parse] Load xml
V/TelephonyAutoProfiling( 6273): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6273): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6273): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/AlarmManager(  863): RTC_WAKEUP set : Alarm{10a2bb01 type 0 when 1453879769237 com.android.vending} when 1453879769237
D/Finsky  ( 6026): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WearableService( 1732): callingUid 10006, callindPid: 1732
,E/MDM     ( 1732): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5614): Restart initialization of location
I/GCoreUlr( 1732): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,W/ctxmgr  ( 1732): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
E/ctxmgr  ( 1732): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/GCoreUlr( 1732): Unbound from all location providers
I/GCoreUlr( 1732): Place inference reporting - stopped
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1732): DispatchingService.onDestroy()
I/GCoreUlr( 1732): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1732): Unbound from all location providers
I/GCoreUlr( 1732): Place inference reporting - stopped
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,I/NotificationManager(  863): android: cancelAsUser(2) by android
I/ActivityManager(  863): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6311 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd( 6026): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6026): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6026): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6026): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 6026): propertyValue:false
,D/libc-netbsd( 6026): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6026): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/ActivityManager(  863): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/libc-netbsd( 6026): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6026): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Gmail   ( 6311): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 6311): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  863): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6311): Error finding the version of the Email provider.....
E/Gmail   ( 6311): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6311): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6311): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6311): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6311): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6311): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6311): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6311): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 6311): We do not support migrating this version of the Email provider.
I/Gmail   ( 6311): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  863): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6311): Observing account changes for notifications
W/ActivityManager(  863): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 94381144449; DSPS: 3191214; Offset : -3017433524
I/ActivityManager(  863): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6361 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 6311): notifyAccountChanged
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6311): getAccountsCursor
I/NotificationManager(  863): android: cancelAsUser(2) by android
,I/Gmail   ( 6311): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6311): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6311): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6311): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/ResourcesManager( 6361): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/qtaguid ( 6026): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6026): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6026): untagSocket(41) failed with errno -22
D/Finsky  ( 6026): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
I/ActivityManager(  863): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6381 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/CalendarApplication( 6361): CalendarApplication.onCreate()
D/PreferenceKeysParser( 6361): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6361): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@9d550b3, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@bdc1670, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@262bdde9, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@2980aa6e, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1eca450f, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@35c4299c, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@33db6fa5, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2f10ff7a, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@a70232b, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@3ab84388, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@28386121, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@e1f9946, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@364bc707, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2b521034, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@2f18ee5d, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1f2c03d2, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3553cca3, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2619fba0, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@217b1359, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@11228b1e, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@94c8fff, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@27b331cc, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@10408c15, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@3683b2a, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@21e42d1b, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@31c79eb8, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@3eaad491, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@34a6dff6, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@318e7ff7, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@34b3ee64, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@89728cd, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@12590582, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@34212493, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@27f38cd0, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@307a84c9, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3515f7ce, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@32f76ef, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3d4ca5fc, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@111da485, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@159dc2da, lg_preferences_alerts_vibratetype=com.android.calendar,.adaptation.PreferenceKey$KeyData@1426930b, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@1abc25
D/GeneralPreferenceUtils( 6361): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6361): [init]
I/Config  ( 6361): LGCalendar ver.4.40.17
I/Config  ( 6361): start check model
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Config  ( 6361): start check native_ca
I/Config  ( 6361): Config Operator=OPEN, Country=EU
D/Config  ( 6361): [setDefaultValuesToPref]
D/Config  ( 6361): [parseProfiles]
D/ProfilesParser( 6361): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6361): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6361): [updateProfiletoCountryInfo]
,D/GeneralPreference( 6361): [checkAndMigrateOldPreference]
,W/ResourcesManager( 6381): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6381): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/AlertReceiver( 6361): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/MultiDex( 6381): VM with version 2.1.0 has multidex support
I/MultiDex( 6381): install
,I/MultiDex( 6381): VM has multidex support, MultiDex support library is disabled.
I/art     ( 1732): Explicit concurrent mark sweep GC freed 23964(1431KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 13MB/23MB, paused 1.304ms total 174.357ms
,I/ActivityManager(  863): Process com.google.android.apps.plus (pid 5992) has died
,I/Gmail   ( 6311): getAccountsCursor
I/InitNotificationRingtoneService( 6361): Start InitializeAlertRingtoneService.onHandleIntent
,I/NotificationManager(  863): android: cancelAsUser(2) by android
I/AlertUtils( 6361): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/art     ( 4060): Explicit concurrent mark sweep GC freed 3014(119KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 495us total 31.222ms
,I/AlertUtils( 6361): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 6361): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
,V/JNIHelp ( 6381): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AlertUtils( 6361): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6361): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6361): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6361): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
W/ActivityThread( 6381): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6381): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35abca00: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6381): Installed default security provider GmsCore_OpenSSL
W/HolidayIntentService( 6361): onHandleIntent
,D/HolidayDataLoader( 6361): readJsonAsset : holiday.json
D/AlertService( 6361): 0 Action = android.intent.action.PROVIDER_CHANGED
,I/art     (  863): Explicit concurrent mark sweep GC freed 16801(889KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 6.616ms total 165.625ms
,I/AlertUtils( 6361): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6361): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6361): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6361): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6361): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6361): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6361): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
E/HolidayIntentService( 6361): onHandleIntent:holiday data empty
,I/AlertUtils( 6361): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6361): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6361): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6361): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,I/ActivityManager(  863): Process com.android.contacts (pid 5943) has died
E/AgendaWidgetManager( 6361): [updateWidgets] 
I/NotificationManager( 6381): com.google.android.gms: cancel(10436) by com.google.android.gms
D/MonthWidgetProvider( 6361): [onReceive]
D/CalendarWidgetProvider( 6361): [onReceive]
D/CalendarWidgetProvider( 6361): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
I/AlertUtils( 6361): set default noti to content://media/internal/audio/media/38
I/NotificationManager( 6381): com.google.android.gms: cancel(39789) by com.google.android.gms
,D/CalendarTypeController( 6361): [onCreate] mContext.getPackageName() = com.android.calendar
I/InitNotificationRingtoneService( 6361): End InitializeAlertRingtoneService.onHandleIntent
D/WeekWidgetProvider( 6361): [onReceive]
D/CalendarWidgetProvider( 6361): [onReceive]
D/CalendarWidgetProvider( 6361): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/ChimeraCfgMgr( 6381): Reading stored module config
,D/CalendarTypeController( 6361): [onCreate] mContext.getPackageName() = com.android.calendar
,I/ActivityManager(  863): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6410 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/ChimeraCfgMgr( 6381): Loading module com.google.android.gms.car from APK com.google.android.gms
I/qtaguid ( 6026): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6026): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6026): untagSocket(41) failed with errno -22
,W/ResourcesManager( 6410): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/CAR.SERVICE( 6381): Connecting to CarCallService...
,I/art     ( 6381): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6381): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6381): Install completed successfully. count=14 extracted=0
D/CAR.SERVICE( 6381): com.google.android.projection.gearhead isn't installed.
,I/jxcore-log( 5646): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5646): 
,D/CAR.TEL.Service( 6381): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 6381): Creating a new PhoneAdapter instance
,W/ActivityManager(  863): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6381): setListener: com.google.android.gms.car.dn@185318cf
W/ActivityManager(  863): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6381): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6381): Starting CarCallService with initial phone null
I/NotificationManager( 6381): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6381): Package validated; name: com.android.vending
,D/UEI.SmartControl( 6144): Internal timer expired: 1
,I/ActivityManager(  863): Process com.lge.qremote (pid 6096) has died
,D/UEI.SmartControl( 6144): Service.onUnbind: IControl
D/UEI.SmartControl( 6144): Service.onDestroy
D/UEI.SmartControl( 6144): Shutdown IRRCPlayer... 
I/art     ( 6026): CheckpointMarkThreadRoots callback created = 0xaaf990a0
,W/irrc_jni( 6144): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6144): ~IrrcClient ++ 
,D/irrcClient( 6144): ~IrrcClient -- 
W/irrc_jni( 6144): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6144): Blaster closed
D/UEI.SmartControl( 6144): Blaster closed
D/UEI.SmartControl( 6144): Shut down QS...
D/UEI.SmartControl( 6144): Stopped file observer...
I/UEI.SmartControl( 6144): QS lib stop result = true
D/UEI.SmartControl( 6144): QS shutdown complete
,V/Finsky  ( 6026): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/NotificationManager( 6026): com.android.vending: cancel(10436) by com.android.vending
,I/Babel_SMS( 6410): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6410): MmsConfig.loadMmsSettings
I/art     ( 6026): CheckpointMarkThreadRoots callback created = 0xaaf99060
,I/Babel_SMS( 6410): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6410): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6410): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6410): MmsConfig.loadFromResources
E/Babel_SMS( 6410): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6410): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6410): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6410): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6410): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6410): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6410): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6410): found sensor: LGE Linear Acceleration Sensor, handle=30
,D/SensorManager( 6410): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6410): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6410): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6410): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6410): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6410): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6410): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6410): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6410): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6410): found sensor: Motion Accel, handle=46
I/art     ( 6410): CheckpointMarkThreadRoots callback created = 0xaaf21ff0
I/art     ( 6410): CheckpointMarkThreadRoots callback created = 0xaaf21fc0
,I/ActivityManager(  863): Process com.uei.lg.quicksetsdk.lite (pid 6144) has died
,I/BackgroundMemoryTrimmer( 1939): Trimming objects from memory, since app is in the background.
I/PhoneApp( 1743): onTrimMemory: 10
I/PhoneApp( 1743): trim memory
,V/AlarmManager(  863): RTC_WAKEUP set : Alarm{252826a2 type 0 when 1453879771625 com.android.vending} when 1453879771625
W/Settings( 6410): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6410): startup - clean
I/Babel   ( 6410): deleted: false for 0
,I/ActivityManager(  863): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6447 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/AudioCapabilities( 6410): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6410): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6410): Unsupported mime audio/g726
W/AudioCapabilities( 6410): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6410): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6410): Unsupported mime video/mjpg
W/VideoCapabilities( 6410): Unsupported mime video/theora
W/AudioCapabilities( 6410): Unsupported mime audio/evrc
W/AudioCapabilities( 6410): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6410): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6410): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6410): Unsupported mime audio/qcelp
W/AudioCapabilities( 6410): Unsupported mime audio/evrc
,I/ActivityManager(  863): Process com.google.android.gm (pid 6311) has died
I/BackgroundMemoryTrimmer( 1939): Trimming objects from memory, since app is in the background.
I/PhoneApp( 1743): onTrimMemory: 10
I/PhoneApp( 1743): trim memory
,W/VideoCapabilities( 6410): Unsupported mime video/mp4v-esdp
,W/ResourcesManager( 6447): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/VideoCapabilities( 6410): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6410): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6410): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6410): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6410): Unrecognized profile 2130706433 for video/avc
,D/BluetoothManagerService(  863): Message: 20
D/BluetoothManagerService(  863): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@174b7c52:true
,D/BluetoothAdapterService(789643130)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2619fba0
D/BluetoothAdapterService(789643130)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2619fba0
,I/vclib   ( 6410): onServiceConnected
W/Babel   ( 6410): Attempted to change video mute state without an active call.
,W/ResourcesManager( 6410): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6410): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/Finsky  ( 6026): [730] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 6026): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  863): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6468 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6447): Create singleton instance
,V/JNIHelp ( 6410): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/UEI.SmartControl( 6468): Quickset Services start...
,I/UEI.SmartControl( 6468): Manufacture = LGE
D/UEI.SmartControl( 6468): File observer start...
E/UEI.SmartControl( 6468): IR Port is disabled: false
D/UEI.SmartControl( 6468): Starting file observer...
D/UEI.SmartControl( 6468): Extracting JNI libs...
D/UEI.SmartControl( 6468): --- this system supports 32-bit or 64-bit only
I/AudioManager( 6447): getMode name:com.lge.qremote
,W/System  ( 6410): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6410): Installed default security provider GmsCore_OpenSSL
I/jxcore-log( 5646): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5646): 
,I/NotificationManager( 6410): com.google.android.talk: cancel(10436) by com.google.android.talk
D/UEI.SmartControl( 6468): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6468): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6468): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/ActivityManager(  863): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6492 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/UEI.SmartControl( 6468): --- Selecting new region: 2
I/UEI.SmartControl( 6468): -- Running on KitKat(19) and above! JNI will be used.
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 21.616ms
D/UEI.SmartControl( 6468): Platform has CIR...
,I/BackgroundMemoryTrimmer( 1939): Trimming objects from memory, since app is in the background.
D/UEI.SmartControl( 6468): NO CIR support, need to check package...
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.845ms
I/NotificationManager( 6410): com.google.android.talk: cancel(8) by com.google.android.talk
I/UEI.SmartControl( 6468): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6468): QS Service created
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 21.076ms
I/jxcore-log( 5646): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5646): 
,I/jxcore-log( 5646): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5646): 
E/UEI.SmartControl( 6468): QS start get config
I/AppUp4:AppBoxCP( 6492): onCreate
,W/AppUp4:DB( 6492):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6492):  setFingerPrint start
I/AppUp4:DB( 6492):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6492):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6492):  SDK version = 0
I/AppUp4:DB( 6492):  beforefinger == newfinger no write in DB
D/UEI.SmartControl( 6468): Loading JNI Libs...
D/UEI.SmartControl( 6468):  configuring local db...
D/AppUp4:AppBoxApplication( 6492): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6492): onReceive
I/AppUp4:CustModeStarterReceiver( 6492): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6492): Context : android.app.ReceiverRestrictedContext@bdc1670
D/AppUp4:CustFacade( 6492): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6492): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6492): begin check event
I/AppUp4:CustModeStarterReceiver( 6492): Event For Nothing, skip.
I/jxcore-log( 5646): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5646): 
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  863): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6512 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/jxcore-log( 5646): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5646): 
I/jxcore-log( 5646): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5646): 
,I/jxcore-log( 5646): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5646): 
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  863): android: cancelAsUser(2) by android
W/ResourcesManager( 6512): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6512): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6512): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6468):  ---- Has DB8: true
,D/UEI.SmartControl( 6468): QS start statue = true Error code = 0
D/UEI.SmartControl( 6468): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6468): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6468): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6468): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6468): IrrcClient ++ 
D/irrcClient( 6468): getIrrcService ++ 
,D/irrcClient( 6468): getIrrcService -- 
D/irrcClient( 6468): IrrcClient -- 
W/irrc_jni( 6468): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6468): Services init done
I/UEI.SmartControl( 6468): Device manager: loading config....
,D/UEI.SmartControl( 6468): QS Service init finished
D/UEI.SmartControl( 6468): QS Service version name: 0.1.73
,D/UEI.SmartControl( 6468): QS Service version code: 1073
D/UEI.SmartControl( 6468): Service requested: Control
D/UEI.SmartControl( 6468): Config is loaded...
,V/AlarmManager(  863): RTC_WAKEUP set : Alarm{354bfb67 type 0 when 1453879773210 com.google.android.googlequicksearchbox} when 1453879773210
I/AppConfig( 6512): Total System Memory = 906309632
I/GalleryUtils( 6512): Application Heap = 96 MB
,D/UEI.SmartControl( 6468):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6468): Notify AllClients services are ready: 0
I/AppConfig( 6512): App Tier : NOT_DEF
D/UEI.SmartControl( 6468): Request IControl service: devices are loaded...
,D/SystemHelper( 6512): region [EU], country [EU], operator [OPEN], sub-operator []
D/UEI.SmartControl( 6468): Internal service binding...
I/qtaguid ( 6026): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6026): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6026): untagSocket(41) failed with errno -22
D/UEI.SmartControl( 6468): -----IControl: 11
D/UEI.SmartControl( 6468): Caller: com.lge.qremote
D/UEI.SmartControl( 6468): ------------ IControl registerCallback...
I/UEI.SmartControl( 6468): Registering callback...
D/UEI.SmartControl( 6468): -----IControl: 19
,D/UEI.SmartControl( 6468): Caller: com.lge.qremote
I/UEI.SmartControl( 6468): Registering Services Ready callback...
I/UEI.SmartControl( 6468): Notify client services are ready...
D/UEI.SmartControl( 6468): -----IControl: 8
D/UEI.SmartControl( 6468): Caller: com.lge.qremote
I/ActivityManager(  863): Process com.lge.lockscreensettings (pid 5969) has died
,I/ActivityManager(  863): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6538 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 6538): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6538): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6538): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 6538): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6538): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6026): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6026): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6026): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  863): Process com.google.android.partnersetup (pid 6164) has died
,D/Finsky  ( 6026): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager(  863): RTC_WAKEUP set : Alarm{3892e703 type 0 when 1453879773877 com.android.vending} when 1453879773877
,D/DeviceConnectionService( 1732): client connected with version: 8296000
,I/SystemConfig( 6538): BUILD Country: EU
I/SystemConfig( 6538): BUILD Operator: OPEN
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/Finsky  ( 6026): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6026): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  863): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6567 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6538): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6538): existFile = false
I/SystemConfig( 6538): canReadFile = false
I/SystemConfig( 6538): systemFeature RCS result false
D/SystemConfig( 6538): refreshRcsSupport() :false
,I/jxcore-log( 5646): Test app app.js loaded
I/jxcore-log( 5646): 
,I/ActivityManager(  863): Process com.lge.qremote (pid 6447) has died
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5646): setDiscoveryMode: Mode set to BLE
I/jxcore-log( 5646): BLE advertisement is supported
I/jxcore-log( 5646): 
,I/chromium( 5646): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/LockScreenSettings( 6567): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  863): Process com.uei.lg.quicksetsdk.lite (pid 6468) has died
,D/LockScreenSettings( 6567): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6567): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6567): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6567): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6567): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  863): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6588 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6588): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  863): Process com.android.gallery3d (pid 6512) has died
,I/UpdateIcingCorporaServi( 1939): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 5614): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  863): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6617 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/UpdateIcingCorporaServi( 1939): UpdateCorporaTask done [took 67 ms] updated apps [took 66 ms] 
I/PackageBroadcastService( 5614): Null package name or gms related package.  Ignoreing.
I/Icing   ( 5614): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 6617): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6617): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6617): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6617): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6617): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 6617): Using schema version: 115
,I/IndexDatabaseHelper( 6617): Index is fine
V/WiFiOffLoadBroadcast( 6617): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6617): MCCMNC not supported: null
I/ActivityManager(  863): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6647 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6647): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6647): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6647): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  863): Process com.android.contacts (pid 6538) has died
,I/ActivityManager(  863): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6667 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 6667): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  863): Message: 20
D/BluetoothManagerService(  863): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5986c86:true
,D/BluetoothAdapterService(789643130)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2619fba0
D/BluetoothAdapterService(789643130)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2619fba0
,I/art     (  863): Explicit concurrent mark sweep GC freed 16022(726KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.377ms total 144.586ms
,D/AlertService( 6361): Beginning updateAlertNotification
,V/WiFiOffLoadBroadcast( 6617): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6617): MCCMNC not supported: null
I/ActivityManager(  863): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6687 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/PCSuite ( 6647): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6647): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6647): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6617): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6617): MCCMNC not supported: null,
I/PCSuite ( 6647): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6647): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6647): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6617): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6617): MCCMNC not supported: null
I/PCSuite ( 6647): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6647): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6647): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6617): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,W/ResourcesManager( 6687): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/WiFiOffLoadBroadcast( 6617): MCCMNC not supported: null
I/Icing   ( 5614): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,V/WiFiOffLoadBroadcast( 6617): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 6617): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6617): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6617): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6617): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6617): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6617): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6617): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6617): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/Icing   ( 5614): Loaded CLD2 Version V2.0 - 20141016
D/CalendarProvider2( 6687): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@297f2fed
D/WiFiOffLoadBroadcast( 6617): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6617): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6617): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6617): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6617): MCCMNC not supported: null
I/Icing   ( 5614): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
V/WiFiOffLoadBroadcast( 6617): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/CalendarProvider2( 6687): [getOrCreateCalendarAlarmManager]
D/WiFiOffLoadBroadcast( 6617): MCCMNC not supported: null
I/CalendarProvider2( 6687): Created com.android.providers.calendar.CalendarAlarmManager@2980aa6e(com.android.providers.calendar.CalendarProvider2@297f2fed)
,I/ActivityManager(  863): Killing 6189:com.google.android.configupdater/u0a3 (adj 15): empty #11
,W/PackageSettings(  863): Skipping PackageSetting{645e950 com.example.hello/10317} due to missing metadata
,W/libprocessgroup(  863): failed to open /acct/uid_10003/pid_6189/cgroup.procs: No such file or directory
D/AlertService( 6361): No fired or scheduled alerts
I/NotificationManager( 6361): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6361): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6361): com.android.calendar: cancel(2) by com.android.calendar
V/WiFiOffLoadBroadcast( 6617): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/NotificationManager( 6361): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6361): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6361): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6361): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6361): com.android.calendar: cancel(7) by com.android.calendar
,I/NotificationManager( 6361): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6361): com.android.calendar: cancel(9) by com.android.calendar
D/WiFiOffLoadBroadcast( 6617): MCCMNC not supported: null
I/NotificationManager( 6361): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6361): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6361): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6361): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6361): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6361): com.android.calendar: cancel(15) by com.android.calendar
,I/NotificationManager( 6361): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6361): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6361): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6361): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6361): com.android.calendar: cancel(20) by com.android.calendar
V/WiFiOffLoadBroadcast( 6617): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6617): MCCMNC not supported: null
I/PCSuite ( 6647): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6647): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6617): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6617): MCCMNC not supported: null
I/PCSuite ( 6647): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6647): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/AlertService( 6361): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/CalendarProviderBroadcastReceiver( 6687): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6687): [IntentService] WakeLock acquire, start IntentSerivce
D/AlarmScheduler( 6361): No events found starting within 1 week.
D/CalendarProvider2( 6687): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6687): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6687): [getOrCreateCalendarAlarmManager]
,D/CalendarProvider2( 6687): [IntentService] Release Lock
,D/CalendarProvider2( 6687): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  863): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6714 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  863): Killing 6492:com.lge.appbox.client/u0a11 (adj 15): empty #11
V/LGMDMManager( 6667): Create singleton instance
,I/AudioManager( 6667): getMode name:com.lge.qremote
,W/libprocessgroup(  863): failed to open /acct/uid_10011/pid_6492/cgroup.procs: No such file or directory
,I/ActivityManager(  863): Killing 6361:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  863): failed to open /acct/uid_10013/pid_6361/cgroup.procs: No such file or directory
D/CAR.SERVICE( 6381): mConnectedToCar = false, abort
I/AudioManager( 6667): getMode name:com.lge.qremote
,E/ActivityThread( 6381): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1a5b45d7 that was originally bound here
E/ActivityThread( 6381): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1a5b45d7 that was originally bound here
E/ActivityThread( 6381): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6381): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6381): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6381): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6381): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6381): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6381): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6381): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6381): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6381): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6381): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6381): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6381): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6381): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6381): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6381): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6381): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6381): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6381): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6381): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6381): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6381): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6381): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,D/UEI.SmartControl( 6714): Quickset Services start...
I/UEI.SmartControl( 6714): Manufacture = LGE
D/UEI.SmartControl( 6714): File observer start...
E/UEI.SmartControl( 6714): IR Port is disabled: false
D/UEI.SmartControl( 6714): Starting file observer...
D/UEI.SmartControl( 6714): Extracting JNI libs...
D/UEI.SmartControl( 6714): --- this system supports 32-bit or 64-bit only
I/ActivityManager(  863): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6732 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6714): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6714): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6714): --- Extracting JNI libs: libqs_armeabi-v7a.zip
E/ActivityThread( 6381): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3c9d752e that was originally bound here
E/ActivityThread( 6381): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3c9d752e that was originally bound here
E/ActivityThread( 6381): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6381): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6381): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6381): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6381): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6381): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6381): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6381): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6381): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6381): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6381): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6381): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6381): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6381): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6381): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6381): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6381): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6381): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6381): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6381): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6381): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6381): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  863): Unbind failed: could not find connection for android.os.BinderProxy@21987cd1
,I/UEI.SmartControl( 6714): --- Selecting new region: 2
I/UEI.SmartControl( 6714): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6714): Platform has CIR...
D/UEI.SmartControl( 6714): NO CIR support, need to check package...
I/UEI.SmartControl( 6714): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6714): QS Service created
,E/UEI.SmartControl( 6714): QS start get config
,D/UEI.SmartControl( 6714): Loading JNI Libs...
,D/UEI.SmartControl( 6714):  configuring local db...
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/MusicStore( 6732): Database version: 120
,D/UEI.SmartControl( 6714):  ---- Has DB8: true
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
D/UEI.SmartControl( 6714): QS start statue = true Error code = 0
D/UEI.SmartControl( 6714): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6714): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
W/ContextImpl( 6732): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/UEI.SmartControl( 6714): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6714): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6714): IrrcClient ++ 
D/irrcClient( 6714): getIrrcService ++ 
D/irrcClient( 6714): getIrrcService -- 
D/irrcClient( 6714): IrrcClient -- 
W/irrc_jni( 6714): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6714): Services init done
,I/UEI.SmartControl( 6714): Device manager: loading config....
D/UEI.SmartControl( 6714): QS Service init finished
D/UEI.SmartControl( 6714): QS Service version name: 0.1.73
D/UEI.SmartControl( 6714): Config is loaded...
D/UEI.SmartControl( 6714): QS Service version code: 1073
D/UEI.SmartControl( 6714): Service requested: Control
D/UEI.SmartControl( 6714): Internal service binding...
D/UEI.SmartControl( 6714): -----IControl: 11
,D/UEI.SmartControl( 6714): Caller: com.lge.qremote
D/UEI.SmartControl( 6714): ------------ IControl registerCallback...
I/UEI.SmartControl( 6714): Registering callback...
D/UEI.SmartControl( 6714): -----IControl: 19
D/UEI.SmartControl( 6714): Caller: com.lge.qremote
I/UEI.SmartControl( 6714): Registering Services Ready callback...
I/UEI.SmartControl( 6714): Notify client services are ready...
D/UEI.SmartControl( 6714): -----IControl: 8
D/UEI.SmartControl( 6714): Caller: com.lge.qremote
I/ActivityManager(  863): Killing 6567:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,D/UEI.SmartControl( 6714):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6714): Notify AllClients services are ready: 0
,W/libprocessgroup(  863): failed to open /acct/uid_10069/pid_6567/cgroup.procs: No such file or directory
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6732): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6732): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6732): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6732): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6732): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6732): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6732): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@399ecdb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6732): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6732): GMSCore installation verified
I/ConfigStore( 6732): Config Database version: 1
,I/MediaRouter( 6732): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6732): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6732): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  863): Killing 6381:com.google.android.gms:car/u0a6 (adj 15): empty #11
,W/libprocessgroup(  863): failed to open /acct/uid_10006/pid_6381/cgroup.procs: No such file or directory
,I/NetworkMonitor( 6732): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  863): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6766 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 25.657ms
,I/GHttpClientFactory( 6732): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 6732): Using platform SSLCertificateSocketFactory
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 27.560ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.682ms
,I/ActivityManager(  863): Killing 6588:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/ResourcesManager( 6766): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6766): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6766): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  863): failed to open /acct/uid_10086/pid_6588/cgroup.procs: No such file or directory
I/NotificationManager( 6732): com.google.android.music: cancel(1061) by com.google.android.music
,I/ActivityManager(  863): Killing 6026:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  863): failed to open /acct/uid_10036/pid_6026/cgroup.procs: No such file or directory
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
D/charger_monitor(  490): init target 500000
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
,I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  863): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/charger_monitor(  490): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  863): battery changed pluggedType: 2
I/LGEmail ( 6766): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/LGEmail ( 6766): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/QcrilMsgTunnelSocket( 2296): readRilMessage: Buffer = [B@2a0fce22 HexData = [010000000404000011000000514f454d484f4f4bef0308000100000003]
D/QcrilMsgTunnelSocket( 2296): Rcvd UNSOL response with 28 bytes data for SUB0
D/QcrilMsgTunnelSocket( 2296): Response ID 525295 is not served in this process.
D/QcrilMsgTunnelSocket( 2296): To broadcast an Intent via the notifier to external apps
D/QcrilMsgTunnelIfaceManager( 2296): handleMessage what = 0
D/QcrilMsgTunnelIfaceManager( 2296): Broadcasting intent ACTION_UNSOL_RESPONSE_OEM_HOOK_RAW
D/QC_RIL_OEM_HOOK( 1743): Received Broadcast Intent ACTION_UNSOL_RESPONSE_OEM_HOOK_RAW
D/QC_RIL_OEM_HOOK( 1743): Oem ID in QCRILHOOK UNSOL RESP is QOEMHOOK
,V/TelephonyAutoProfiling( 1743): [getValue] PROFILE key : HOME_NETWORK, value : null, phoneId : 0
,D/eas_req ( 6766): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/PhoneInterfaceManager( 1743): [PhoneIntfMgr] handleMessage : 2
,D/PhoneInterfaceManager( 1743): [PhoneIntfMgr] handleMessage : 3
I/ActivityManager(  863): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6811 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6766): JNI_OnLoad()
I/HubEmail( 6766): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6766): registerNatives()
I/HubEmail( 6766): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6766): registerNativeMethods()
I/HubEmail( 6766): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6766): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  863): Killing 6410:com.google.android.talk/u0a61 (adj 15): empty #11
W/Settings( 6766): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/libprocessgroup(  863): failed to open /acct/uid_10061/pid_6410/cgroup.procs: No such file or directory
D/LGDMClient( 6811): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6811): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6811): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6811): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6811): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6811): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6811): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6811): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  863): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6835 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6811): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6811): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 6811): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6811): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6811): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6811): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  863): Killing 6617:com.android.settings/1000 (adj 15): empty #11
,W/libprocessgroup(  863): failed to open /acct/uid_1000/pid_6617/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 6835): onCreate
,W/AppUp4:DB( 6835):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6835):  setFingerPrint start
I/AppUp4:DB( 6835):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6835):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6835):  SDK version = 0
I/AppUp4:DB( 6835):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6835): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6835): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 6835): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6835): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6835): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6835): onReceive
I/AppUp4:CustModeStarterReceiver( 6835): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6835): Context : android.app.ReceiverRestrictedContext@1eca450f
D/AppUp4:CustFacade( 6835): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6835): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6835): begin check event
I/AppUp4:CustModeStarterReceiver( 6835): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6835): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6835): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6835): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6835): handleAsyncCustNotification do not startCustService
I/ActivityManager(  863): Killing 6647:com.lge.sync/1000 (adj 15): empty #11
W/libprocessgroup(  863): failed to open /acct/uid_1000/pid_6647/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3176): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3176): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3176): networkInfo.isConnected() = false
,D/MobileConnectivityChangeReceiver( 6273): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6273): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 3247): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3247): DownloadService onCreate
I/DownloadManager( 3247): in removeSpuriousFiles
V/DownloadManager( 3247): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3247): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3247): created cursor android.database.sqlite.SQLiteCursor@35abca00 on behalf of 3247
,I/DownloadManager( 3247): in trimDatabase
V/DownloadManager( 3247): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3247): created cursor android.database.sqlite.SQLiteCursor@2db13239 on behalf of 3247
I/ActivityManager(  863): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6857 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3247): DownloadService onStartCommand
V/DownloadManager( 3247): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3247): created cursor android.database.sqlite.SQLiteCursor@1c03862c on behalf of 3247
,V/DownloadManager( 3247): DownloadService onDestroy
,I/ActivityManager(  863): Killing 6687:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  863): failed to open /acct/uid_10014/pid_6687/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2657): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:29:38
D/UpdateThreadPoolManager( 2657): 2 : This is isUpdating : false
D/WeatherAncestor( 2657): connectivity changed - connection : true
D/Weather_cast( 2657): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2657): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:29:38
D/WeatherService( 2657): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
I/ActivityManager(  863): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6877 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  863): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2657): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2657): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2657): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 6877): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Babel_SMS( 6877): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6877): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6877): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6877): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6877): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6877): MmsConfig.loadFromResources
E/Babel_SMS( 6877): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6877): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6877): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6877): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6877): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6877): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6877): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6877): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6877): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6877): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6877): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6877): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6877): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6877): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6877): found sensor: LGE Tilt Detector Sensor, handle=55
,D/SensorManager( 6877): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6877): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6877): found sensor: Motion Accel, handle=46
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
W/Settings( 6877): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6877): startup - clean
I/art     ( 6877): CheckpointMarkThreadRoots callback created = 0xb042d8b0
I/Babel   ( 6877): deleted: false for 0
,I/art     ( 6877): CheckpointMarkThreadRoots callback created = 0xb042d890
,I/ActivityManager(  863): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6908 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6877): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6877): Unsupported mime audio/adpcm
W/AudioCapabilities( 6877): Unsupported mime audio/g726
,W/AudioCapabilities( 6877): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6877): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6877): Unsupported mime video/mjpg
W/VideoCapabilities( 6877): Unsupported mime video/theora
,W/AudioCapabilities( 6877): Unsupported mime audio/evrc
,W/AudioCapabilities( 6877): Unsupported mime audio/qcelp
W/VideoCapabilities( 6877): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6877): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6877): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6877): Unsupported mime audio/evrc
W/VideoCapabilities( 6877): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6877): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6877): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6877): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6877): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6877): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 6877): onServiceConnected
W/Babel   ( 6877): Attempted to change video mute state without an active call.
,I/NotificationManager( 6877): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 6877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 6877): propertyValue:false
I/Babel   ( 6877): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  863): Killing 6714:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 6667): android.os.DeadObjectException
,W/System.err( 6667): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6667): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6667): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6667): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6667): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6667): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6667): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6667): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6667): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6667): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6667): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6667): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6667): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6667): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6667): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6667): android.os.DeadObjectException
W/System.err( 6667): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6667): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6667): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6667): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6667): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6667): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6667): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6667): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6667): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6667): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6667): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6667): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6667): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6667): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6667): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  863): failed to open /acct/uid_10089/pid_6714/cgroup.procs: No such file or directory
,W/ActivityManager(  863): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  863): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6940 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6908): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6908): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6908): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6908): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6908): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6908):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6908):   adb logcat -s GAv4
D/UEI.SmartControl( 6940): Quickset Services start...
I/UEI.SmartControl( 6940): Manufacture = LGE
,D/UEI.SmartControl( 6940): File observer start...
E/UEI.SmartControl( 6940): IR Port is disabled: false
,D/UEI.SmartControl( 6940): Starting file observer...
D/UEI.SmartControl( 6940): Extracting JNI libs...
D/UEI.SmartControl( 6940): --- this system supports 32-bit or 64-bit only
W/GAv4    ( 6908): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6908): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6908): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/UEI.SmartControl( 6940): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6940): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6940): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6940): --- Selecting new region: 2
I/UEI.SmartControl( 6940): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6940): Platform has CIR...
D/UEI.SmartControl( 6940): NO CIR support, need to check package...
I/UEI.SmartControl( 6940): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6940): QS Service created
E/UEI.SmartControl( 6940): QS start get config
,D/UEI.SmartControl( 6940): Loading JNI Libs...
,D/UEI.SmartControl( 6940):  configuring local db...
I/WebViewFactory( 6908): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/UEI.SmartControl( 6940):  ---- Has DB8: true
,D/UEI.SmartControl( 6940): QS start statue = true Error code = 0
D/UEI.SmartControl( 6940): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6940): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6940): IRRCDataComm has AudioManager!!!!.
,I/LibraryLoader( 6908): Time to load native libraries: 6 ms (timestamps 4907-4913)
I/LibraryLoader( 6908): Expected native library version number "",actual native library version number ""
W/irrc_jni( 6940): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6940): IrrcClient ++ 
D/irrcClient( 6940): getIrrcService ++ 
D/irrcClient( 6940): getIrrcService -- 
D/irrcClient( 6940): IrrcClient -- 
W/irrc_jni( 6940): IRRCPlayer_nativeInit -- 
,V/WebViewChromiumFactoryProvider( 6908): Binding Chromium to main looper Looper (main, tid 1) {a45b330}
I/LibraryLoader( 6908): Expected native library version number "",actual native library version number ""
I/chromium( 6908): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/UEI.SmartControl( 6940): Services init done
D/UEI.SmartControl( 6940): QS Service init finished
D/UEI.SmartControl( 6940): QS Service version name: 0.1.73
D/UEI.SmartControl( 6940): QS Service version code: 1073
D/UEI.SmartControl( 6940): Service requested: Control
I/UEI.SmartControl( 6940): Device manager: loading config....
,D/UEI.SmartControl( 6940): Config is loaded...
I/BrowserStartupController( 6908): Initializing chromium process, singleProcess=true
W/art     ( 6908): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6908): ApplicationContext is null in ApplicationStatus
D/UEI.SmartControl( 6940):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6940): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6940): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6940): -----IControl: 11
D/UEI.SmartControl( 6940): Caller: com.lge.qremote
D/UEI.SmartControl( 6940): ------------ IControl registerCallback...
I/UEI.SmartControl( 6940): Registering callback...
W/chromium( 6908): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
D/UEI.SmartControl( 6940): Internal service binding...
D/UEI.SmartControl( 6940): -----IControl: 19
D/UEI.SmartControl( 6940): Caller: com.lge.qremote
I/UEI.SmartControl( 6940): Registering Services Ready callback...
I/UEI.SmartControl( 6940): Notify client services are ready...
D/UEI.SmartControl( 6940): -----IControl: 8
D/UEI.SmartControl( 6940): Caller: com.lge.qremote
,E/libEGL  ( 6908): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6908): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6908): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6908): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6908): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6908): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6908): Remote Branch: 
I/Adreno-EGL( 6908): Local Patches: 
I/Adreno-EGL( 6908): Reconstruct Branch: 
V/AudioPolicyService(  280): registerClient() client 0xb4027360, uid 10079
,W/AudioManagerAndroid( 6908): Requires BLUETOOTH permission
I/CheckinService( 5614): Done disabling old GoogleServicesFramework version
,I/art     (  863): Explicit concurrent mark sweep GC freed 22843(1375KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.111ms total 142.782ms
,I/NSApplication( 6908): Starting up...
I/ActivityManager(  863): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7005 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  863): Killing 6732:com.google.android.music:main/u0a81 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  863): Killing 6667:com.lge.qremote/u0a106 (adj 15): empty #12
,W/libprocessgroup(  863): failed to open /acct/uid_10081/pid_6732/cgroup.procs: No such file or directory
,W/libprocessgroup(  863): failed to open /acct/uid_10106/pid_6667/cgroup.procs: No such file or directory
I/ActivityManager(  863): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7024 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  863): Killing 6766:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  863): failed to open /acct/uid_10021/pid_6766/cgroup.procs: No such file or directory
,W/ResourcesManager( 7024): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.SyncManager( 5614): SYNC; picasa accounts
,D/NetworkLogImpl( 5614): Loaded NetworkSpeedPredictor
I/iu.Environment( 5614): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  863): Killing 6811:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/iu.UploadsManager( 5614): num queued entries: 0
I/iu.UploadsManager( 5614): num updated entries: 0
I/iu.SyncManager( 5614): NEXT; no task
,W/libprocessgroup(  863): failed to open /acct/uid_1000/pid_6811/cgroup.procs: No such file or directory
,I/ActivityManager(  863): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7051 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/MusicStore( 7051): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7051): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7051): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7051): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7051): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7051): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 7051): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7051): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7051): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@399ecdb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7051): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7051): GMSCore installation verified
,I/ConfigStore( 7051): Config Database version: 1
,I/MediaRouter( 7051): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7051): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7051): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7051): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  863): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7079 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7051): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 7051): Using platform SSLCertificateSocketFactory
,W/ResourcesManager( 7079): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7079): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7079): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  863): Killing 6835:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  863): failed to open /acct/uid_10011/pid_6835/cgroup.procs: No such file or directory
,I/NotificationManager( 7051): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7079): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7079): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7079): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  863): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7102 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 22.994ms
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 23.676ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 21.387ms
I/HubEmail( 7079): JNI_OnLoad()
I/HubEmail( 7079): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7079): registerNatives()
I/HubEmail( 7079): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7079): registerNativeMethods()
I/HubEmail( 7079): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 7079): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  863): Killing 6273:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  863): failed to open /acct/uid_10038/pid_6273/cgroup.procs: No such file or directory
,W/Settings( 7079): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7102): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7102): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7102): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 7102): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7102): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7102): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 7102): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7102): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  863): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7131 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7102): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7102): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7102): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7102): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7102): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7102): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  863): Killing 6857:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  863): failed to open /acct/uid_10051/pid_6857/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 7131): onCreate
W/AppUp4:DB( 7131):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7131):  setFingerPrint start
I/AppUp4:DB( 7131):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7131):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7131):  SDK version = 0
I/AppUp4:DB( 7131):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7131): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7131): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7131): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7131): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7131): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7131): onReceive
I/AppUp4:CustModeStarterReceiver( 7131): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7131): Context : android.app.ReceiverRestrictedContext@1eca450f
D/AppUp4:CustFacade( 7131): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7131): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7131): begin check event
I/AppUp4:CustModeStarterReceiver( 7131): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7131): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7131): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7131): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7131): handleAsyncCustNotification do not startCustService
I/ActivityManager(  863): Killing 6877:com.google.android.talk/u0a61 (adj 15): empty #11
,I/LgeMiscReceiver( 3176): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3176): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3176): networkInfo.isConnected() = false
W/libprocessgroup(  863): failed to open /acct/uid_10061/pid_6877/cgroup.procs: No such file or directory
,I/ActivityManager(  863): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7150 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7150): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7150): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7150): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  863): Killing 6908:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
D/PhoneMonitor( 7150): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7150): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 7150): [parse] Load xml
V/TelephonyAutoProfiling( 7150): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7150): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7150): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  863): failed to open /acct/uid_10079/pid_6908/cgroup.procs: No such file or directory
,V/DownloadManager( 3247): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3247): DownloadService onCreate
,I/NotificationManager( 3247): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3247): in removeSpuriousFiles
V/DownloadManager( 3247): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3247): created cursor android.database.sqlite.SQLiteCursor@2fdc968a on behalf of 3247
I/DownloadManager( 3247): in trimDatabase
V/DownloadManager( 3247): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3247): created cursor android.database.sqlite.SQLiteCursor@3f38d918 on behalf of 3247
I/ActivityManager(  863): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7176 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3247): DownloadService onStartCommand
V/DownloadManager( 3247): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/CheckinService( 5614): Checkin interval check for package: unspecified last checkin: 1453879752900 min interval config: 0 actual interval: 30716
V/DownloadManager( 3247): created cursor android.database.sqlite.SQLiteCursor@5f59156 on behalf of 3247
,I/CheckinService( 5614): Checking schedule, now: 1453879783651 next: 1453879782845
I/CheckinService( 5614): active receiver: enabled
,V/DownloadManager( 3247): DownloadService onDestroy
,I/CheckinService( 5614): Preparing to send checkin request
I/EventLogService( 5614): Accumulating logs since 1453879745220
,D/WeatherAncestor( 2657): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:29:43
D/UpdateThreadPoolManager( 2657): 2 : This is isUpdating : false
D/WeatherAncestor( 2657): connectivity changed - connection : true
D/Weather_cast( 2657): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2657): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:29:43
D/WeatherService( 2657): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  863): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7194 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  863): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2657): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2657): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2657): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7194): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 5614): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5614): Failed to find provider info for com.google.android.wearable.settings
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/Babel_SMS( 7194): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7194): MmsConfig.loadMmsSettings
,I/Babel_SMS( 7194): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7194): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7194): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7194): MmsConfig.loadFromResources
E/Babel_SMS( 7194): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7194): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7194): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 7194): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7194): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7194): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7194): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7194): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7194): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7194): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7194): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7194): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7194): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7194): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7194): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7194): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7194): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7194): found sensor: Motion Accel, handle=46
W/Settings( 7194): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7194): startup - clean
,I/Babel   ( 7194): deleted: false for 0
,I/art     ( 7194): CheckpointMarkThreadRoots callback created = 0xb042d8e0
,I/art     ( 7194): CheckpointMarkThreadRoots callback created = 0xb042d8b0
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/art     (  863): Explicit concurrent mark sweep GC freed 17232(881KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.322ms total 147.637ms
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  863): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7231 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 7194): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7194): Unsupported mime audio/adpcm
W/AudioCapabilities( 7194): Unsupported mime audio/g726
W/AudioCapabilities( 7194): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7194): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 7194): Unsupported mime video/mjpg
W/VideoCapabilities( 7194): Unsupported mime video/theora
W/AudioCapabilities( 7194): Unsupported mime audio/evrc
,W/AudioCapabilities( 7194): Unsupported mime audio/qcelp
W/VideoCapabilities( 7194): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7194): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7194): Unsupported mime audio/qcelp
W/AudioCapabilities( 7194): Unsupported mime audio/evrc
W/VideoCapabilities( 7194): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7194): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7194): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  863): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7252 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/VideoCapabilities( 7194): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7194): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7194): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 7194): onServiceConnected
,W/Babel   ( 7194): Attempted to change video mute state without an active call.
D/libc-netbsd( 7194): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7194): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7194): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7194): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  275): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  275): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 7194): propertyValue:false
I/NotificationManager( 7194): com.google.android.talk: cancel(10436) by com.google.android.talk
W/ResourcesManager( 7252): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7252): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Babel   ( 7194): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  863): Killing 6940:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/MultiDex( 7252): VM with version 2.1.0 has multidex support
I/MultiDex( 7252): install
,I/MultiDex( 7252): VM has multidex support, MultiDex support library is disabled.
W/libprocessgroup(  863): failed to open /acct/uid_10089/pid_6940/cgroup.procs: No such file or directory
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7231): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7231): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
I/GAv4    ( 7231): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7231):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7231):   adb logcat -s GAv4
W/ContextImpl( 7231): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7231): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,V/JNIHelp ( 7252): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/GAv4    ( 7231): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7231): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7231): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/ActivityThread( 7252): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7252): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@35abca00: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7252): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 7252): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7252): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 7252): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7252): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/WebViewFactory( 7231): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7231): Time to load native libraries: 2 ms (timestamps 9501-9503)
,I/LibraryLoader( 7231): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7231): Binding Chromium to main looper Looper (main, tid 1) {a45b330}
I/LibraryLoader( 7231): Expected native library version number "",actual native library version number ""
I/chromium( 7231): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7231): Initializing chromium process, singleProcess=true
W/art     ( 7231): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 7231): ApplicationContext is null in ApplicationStatus
W/chromium( 7231): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7231): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7231): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7231): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7231): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7231): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7231): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7231): Remote Branch: 
I/Adreno-EGL( 7231): Local Patches: 
I/Adreno-EGL( 7231): Reconstruct Branch: 
D/NativeLibraryUtils( 7252): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  280): Instantiating CDM.
I/WVCdm   (  280): CdmEngine::OpenSession
I/WVCdm   (  280): Level3 Library Dec 11 2014 16:13:16
,W/WVCdm   (  280): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  280): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  280): L1 library not specified. Falling Back to L3
,V/AudioPolicyService(  280): registerClient() client 0xb57e9540, uid 10079
,W/AudioManagerAndroid( 7231): Requires BLUETOOTH permission
I/NSApplication( 7231): Starting up...
I/ActivityManager(  863): Killing 7051:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  280): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  280): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  280): PrepareKeyRequest: nonce=2589270249
I/art     ( 7024): CheckpointMarkThreadRoots callback created = 0xb042de40
I/art     ( 7024): CheckpointMarkThreadRoots callback created = 0xb042de10
,W/libprocessgroup(  863): failed to open /acct/uid_10081/pid_7051/cgroup.procs: No such file or directory
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  863): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7317 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 7252): CheckpointMarkThreadRoots callback created = 0xb042d550
,I/art     ( 7252): CheckpointMarkThreadRoots callback created = 0xb042d540
,I/MusicStore( 7317): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7317): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7317): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7317): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/ResourcesManager( 7317): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7317): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7317): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7317): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7317): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@399ecdb: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7317): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7317): GMSCore installation verified
,I/ConfigStore( 7317): Config Database version: 1
I/dex2oat ( 7341): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7341): dex2oat took 99.561ms (threads: 4)
,I/Adreno-EGL( 7252): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7252): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7252): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7252): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7252): Remote Branch: 
I/Adreno-EGL( 7252): Local Patches: 
I/Adreno-EGL( 7252): Reconstruct Branch: 
,I/MediaRouter( 7317): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7317): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7317): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 7317): type=WIFI subType= reason=null isConnected=true
,D/LGDMClient( 7102): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7102): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7102): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 7102): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/NetworkStateForAutoUpdateMonitor( 7131): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7131): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7131): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7131): [onReceive] request level :IDLE....
W/Settings( 7079): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/AppUp4:CustModeStarterReceiver( 7131): onReceive
I/AppUp4:CustModeStarterReceiver( 7131): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7131): Context : android.app.ReceiverRestrictedContext@1eca450f
D/AppUp4:CustFacade( 7131): isCustomizationCompleted : false
D/LGDMClient( 7102): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/AppUp4:CustFacade( 7131): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7131): begin check event
I/AppUp4:CustModeStarterReceiver( 7131): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/LgeMiscReceiver( 3176): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3176): action = android.net.conn.CONNECTIVITY_CHANGE
I/LGDMClient( 7102): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/LGDMClient( 7102): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7102): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LgeMiscReceiver( 3176): networkInfo.isConnected() = true
D/PhoneState( 3176): setPdpRejectCasuse : false
W/ContextImpl( 7102): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,D/MobileConnectivityChangeReceiver( 7150): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7150): onReceive CONNECTIVITY_CHANGE networkType=1
E/LGDMClient( 7102): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7102): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7102): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7102): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
V/DownloadManager( 3247): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3247): DownloadService onCreate
I/DownloadManager( 3247): in removeSpuriousFiles
V/DownloadManager( 3247): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
D/WeatherAncestor( 2657): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:29:46
V/DownloadManager( 3247): created cursor android.database.sqlite.SQLiteCursor@236e6ec4 on behalf of 3247
D/UpdateThreadPoolManager( 2657): 2 : This is isUpdating : false
D/WeatherAncestor( 2657): connectivity changed - connection : true
D/Weather_cast( 2657): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2657): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:29:46
I/DownloadManager( 3247): in trimDatabase
V/DownloadManager( 3247): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/WeatherService( 2657): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
W/ActivityManager(  863): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,I/NotificationManager( 3247): com.android.providers.downloads: cancelAll by com.android.providers.downloads
D/Weather.Utils( 2657): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2657): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2657): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/LGDMClient( 7102): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
V/DownloadManager( 3247): DownloadService onStartCommand
V/DownloadManager( 3247): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3247): created cursor android.database.sqlite.SQLiteCursor@23246873 on behalf of 3247
I/GHttpClientFactory( 7317): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 7317): Using platform SSLCertificateSocketFactory
I/Adreno-EGL( 7252): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7252): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7252): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7252): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7252): Remote Branch: 
I/Adreno-EGL( 7252): Local Patches: 
I/Adreno-EGL( 7252): Reconstruct Branch: 
V/DownloadManager( 3247): created cursor android.database.sqlite.SQLiteCursor@a45b330 on behalf of 3247
,V/DownloadManager( 3247): DownloadService onDestroy
,I/NotificationManager( 7317): com.google.android.music: cancel(1061) by com.google.android.music
,I/ActivityManager(  863): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7361 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  863): Process com.google.android.music:main (pid 7317) has died
,I/Adreno-EGL( 7252): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7252): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7252): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7252): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7252): Remote Branch: 
I/Adreno-EGL( 7252): Local Patches: 
I/Adreno-EGL( 7252): Reconstruct Branch: 
,I/WVCdm   (  280): CdmEngine::OpenSession
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/ActivityManager(  863): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7361): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 4060): Explicit concurrent mark sweep GC freed 2194(85KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 370us total 29.994ms
,W/GAV2    ( 7361): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  863): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  863): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,E/Gmail   ( 7361): Error finding the version of the Email provider.....
E/Gmail   ( 7361): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7361): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7361): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7361): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7361): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7361): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7361): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7361): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7361): We do not support migrating this version of the Email provider.
I/Gmail   ( 7361): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  863): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 7361): Observing account changes for notifications
,I/ActivityManager(  863): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7402 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager(  863): Killing 7079:com.lge.email/u0a21 (adj 15): empty #11
,I/WVCdm   (  280): CdmEngine::CloseSession
,W/libprocessgroup(  863): failed to open /acct/uid_10021/pid_7079/cgroup.procs: No such file or directory
,V/AlarmManager(  863): RTC_WAKEUP set : Alarm{38d20f2c type 0 when 1453879782845 com.google.android.gms} when 1453879782845
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 7402): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager(  863): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7425 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  863): RTC_WAKEUP set : Alarm{1a180df5 type 0 when 1453879787455 com.android.vending} when 1453879787455
I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  280): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  280): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
D/WVCdm   (  280): PrepareKeyRequest: nonce=4179447166
,D/BluetoothManagerService(  863): Message: 20
D/BluetoothManagerService(  863): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@86517c4:true
,D/BluetoothAdapterService(789643130)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2619fba0
,D/BluetoothAdapterService(789643130)( 1990): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2619fba0
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5614): Restart initialization of location
E/MDM     ( 1732): [122] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,I/Gmail   ( 7361): notifyAccountChanged
,I/Gmail   ( 7361): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7361): getAccountsCursor
I/Gmail   ( 7361): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager(  863): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7453 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  863): Explicit concurrent mark sweep GC freed 23701(1085KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.641ms total 233.166ms
V/LGMDMManager( 7402): Create singleton instance
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 21.457ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 20.502ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.519ms
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7361): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7361): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/AudioManager( 7402): getMode name:com.lge.qremote
,I/AudioManager( 7402): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 7453): Quickset Services start...
I/UEI.SmartControl( 7453): Manufacture = LGE
D/UEI.SmartControl( 7453): File observer start...
,E/UEI.SmartControl( 7453): IR Port is disabled: false
D/UEI.SmartControl( 7453): Starting file observer...
D/UEI.SmartControl( 7453): Extracting JNI libs...
,D/UEI.SmartControl( 7453): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7453): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7453): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7453): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7453): --- Selecting new region: 2
,I/UEI.SmartControl( 7453): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7453): Platform has CIR...
D/UEI.SmartControl( 7453): NO CIR support, need to check package...
I/UEI.SmartControl( 7453): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7453): QS Service created
I/ActivityManager(  863): Process com.lge.lgdmsclient (pid 7102) has died
,I/Gmail   ( 7361): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/UEI.SmartControl( 7453): QS start get config
D/Finsky  ( 7425): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 7453): Loading JNI Libs...
,D/UEI.SmartControl( 7453):  configuring local db...
,D/Finsky  ( 7425): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7425): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7425): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7425): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3247): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3247): created cursor android.database.sqlite.SQLiteCursor@3c9d752e on behalf of 7425
I/AudioManager( 7402): getMode name:com.lge.qremote
,D/Ads     ( 7425): Skipping gmscore version check
D/Finsky  ( 7425): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7425): [1] Libraries$2.run: Finished loading 1 libraries.
I/AudioManager( 7402): getMode name:com.lge.qremote
,D/Finsky  ( 7425): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/UEI.SmartControl( 7453):  ---- Has DB8: true
D/UEI.SmartControl( 7453): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7453): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7453): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7453): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7453): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7453): IrrcClient ++ 
D/irrcClient( 7453): getIrrcService ++ 
,D/irrcClient( 7453): getIrrcService -- 
D/irrcClient( 7453): IrrcClient -- 
W/irrc_jni( 7453): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7453): Services init done
I/UEI.SmartControl( 7453): Device manager: loading config....
D/UEI.SmartControl( 7453): Config is loaded...
,D/UEI.SmartControl( 7453):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7453): Notify AllClients services are ready: 0
,I/ActivityManager(  863): Process com.lge.appbox.client (pid 7131) has died
,I/AudioManager( 7402): getMode name:com.lge.qremote
D/UEI.SmartControl( 7453): QS Service init finished
D/UEI.SmartControl( 7453): QS Service version name: 0.1.73
D/UEI.SmartControl( 7453): QS Service version code: 1073
D/UEI.SmartControl( 7453): Service requested: Control
D/UEI.SmartControl( 7453): Internal service binding...
,D/Finsky  ( 7425): [954] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 7453): -----IControl: 11
D/UEI.SmartControl( 7453): Caller: com.lge.qremote
D/UEI.SmartControl( 7453): ------------ IControl registerCallback...
I/UEI.SmartControl( 7453): Registering callback...
D/UEI.SmartControl( 7453): -----IControl: 19
D/UEI.SmartControl( 7453): Caller: com.lge.qremote
I/UEI.SmartControl( 7453): Registering Services Ready callback...
I/UEI.SmartControl( 7453): Notify client services are ready...
,I/NotificationManager(  863): android: cancelAsUser(2) by android
D/Finsky  ( 7425): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/UEI.SmartControl( 7453): -----IControl: 8
D/UEI.SmartControl( 7453): Caller: com.lge.qremote
E/MDM     ( 1732): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5614): Restart initialization of location
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1732): location=null
I/CheckinService( 5614): Checkin interval check for package: unspecified last checkin: 1453879752900 min interval config: 0 actual interval: 35855
D/libc-netbsd( 7425): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7425): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7425): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7425): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
I/AudioManager( 7402): getMode name:com.lge.qremote
I/AudioManager( 7402): getMode name:com.lge.qremote
,W/ContextImpl( 3672): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/libc-netbsd(  275): res_queryN name = xxxxx succeed
,I/System.out( 7425): propertyValue:false
I/AudioManager( 7402): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/AudioManager( 7402): getMode name:com.lge.qremote
,D/Finsky  ( 7425): [950] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7425): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  863): Killing 7150:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,W/libprocessgroup(  863): failed to open /acct/uid_10038/pid_7150/cgroup.procs: No such file or directory
,I/WVCdm   (  280): CdmEngine::CloseSession
,I/WVCdm   (  280): L3 Terminate.
I/CheckinRequestBuilder( 5614): Classify the device as Phone.
,D/libc-netbsd( 5614): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5614): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5614): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5614): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 5614): propertyValue:false
D/libc-netbsd( 5614): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5614): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5614): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5614): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5614): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5614): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 5614): Sending checkin request (9728 bytes)
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 114381961785; DSPS: 3846600; Offset : -3017410401
,I/CheckinRequestBuilder( 5614): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5614): Failed to find provider info for com.google.android.wearable.settings
,I/CheckinRequestBuilder( 5614): Classify the device as Phone.
,I/CheckinTask( 5614): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5614): Checking schedule, now: 1453879790710 next: 1454407039705
I/CheckinService( 5614): active receiver: disabled
,I/CheckinService( 5614): Checking schedule, now: 1453879790737 next: 1454407039705
I/CheckinService( 5614): active receiver: disabled
,D/CheckinService( 5614): Recording last checkin time for package unspecified as 1453879790748
,I/ActivityManager(  863): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=7551 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7551): Register our PhoneStateListener
,V/SetupWizard( 7551): Connected to Gservices successfully
,I/ActivityManager(  863): Killing 7176:com.lge.drmservice/u0a51 (adj 15): empty #11
,D/PhoneMonitor( 7551): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7551): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7551): [parse] Load xml
V/TelephonyAutoProfiling( 7551): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7551): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 7551): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  863): failed to open /acct/uid_10051/pid_7176/cgroup.procs: No such file or directory
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/MusicWidget( 2581): mDelayedStopHandler : unbind
,I/MusicBrowser( 2669): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2669): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2669): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2669): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2669): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2669): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2669): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2669): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  863):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@27b331cccom.lge.music.MediaPlaybackService$6@10408c15
,D/MusicBrowser( 2669): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
,I/MusicBrowser( 2669): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2669): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2669): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2669): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@a70232b
,I/MusicBrowser( 2669): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2669): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2669): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2669): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2669): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2669): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2669): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2669): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2669): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2669): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2669): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2669): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2669): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2669): reset
,V/MediaPlayer[Native]( 2669): setListener
V/MediaPlayer[Native]( 2669): disconnect
V/MediaPlayer[Native]( 2669): destructor
,V/AudioFlinger(  280): releasing 19 from 2669 for -1
V/AudioFlinger(  280):  decremented refcount to 0
V/AudioFlinger(  280): purging stale effects
V/MediaPlayer[Native]( 2669): disconnect
D/MusicBrowser( 2669): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2669): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2669): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2669): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2669): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2669): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2669): [SmartShareManagerClient] unregisterListener: 57162538
W/SmartShareClient( 2669): [SmartShareManagerClient] unregisterListener invalid listener: 57162538
I/SmartShareClient( 2669): [SmartShareManagerClient] terminate service: 2669/MediaPlaybackService/640409065
E/HomeCloudIF( 2669): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2669): [SmartShareManagerClient] unbindService context:android.app.Application@21e42d1b
V/CloudHub( 2669): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2669): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2669): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2669): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2669): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  863): Killing 7231:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/CloudHub( 2669): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29993
W/libprocessgroup(  863): failed to open /acct/uid_10079/pid_7231/cgroup.procs: No such file or directory
,I/GAv4-SVC( 5614): Google Analytics 8.4.89 is starting up.
,I/GAV2    ( 7361): Thread[GAThread,5,main]: No campaign data found.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 7453): Internal timer expired: 1
,I/ActivityManager(  863): Killing 7024:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/ActivityManager(  863): Killing 7005:com.android.chrome/u0a48 (adj 15): empty #12
,W/libprocessgroup(  863): failed to open /acct/uid_10086/pid_7024/cgroup.procs: No such file or directory
,W/libprocessgroup(  863): failed to open /acct/uid_10048/pid_7005/cgroup.procs: No such file or directory
I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  863): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
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
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  863): Handling package changes for user 0
I/ActivityManager(  863): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7610 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 7194): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7194): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7194): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7194): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 7610): onCreate
W/AppUp4:DB( 7610):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7610):  setFingerPrint start
I/AppUp4:DB( 7610):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7610):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7610):  SDK version = 0
I/AppUp4:DB( 7610):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7610): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 7610): onReceive
I/AppUp4:CustModeStarterReceiver( 7610): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,I/NotificationService(  863): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  863): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  863): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/AppUp4:CustFacade( 7610): Context : android.app.ReceiverRestrictedContext@bdc1670
D/AppUp4:CustFacade( 7610): isCustomizationCompleted : false
I/BackupManagerService(  863): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/AppUp4:CustFacade( 7610): isSimDevice : true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/AppUp4:CustModeStarterReceiver( 7610): begin check event
I/AppUp4:CustModeStarterReceiver( 7610): Event For Nothing, skip.
,V/BackupManagerService(  863): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  863): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@cfcabae
,W/System  ( 7194): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7194): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  863): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7633 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,W/ResourcesManager(  863): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
,W/ResourcesManager( 7633): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7633): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7633): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType(  863): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/AppConfig( 7633): Total System Memory = 906309632
,I/GalleryUtils( 7633): Application Heap = 96 MB
I/AppConfig( 7633): App Tier : NOT_DEF
,D/SystemHelper( 7633): region [EU], country [EU], operator [OPEN], sub-operator []
D/LocationProviderProxy(  863): applying state to connected service
,I/ActivityManager(  863): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7653 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  863): Killing 7425:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  863): failed to open /acct/uid_10036/pid_7425/cgroup.procs: No such file or directory
,W/ResourcesManager( 7653): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7653): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7653): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 7653): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7653): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/art     (  863): Explicit concurrent mark sweep GC freed 32507(1625KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.383ms total 169.104ms
,I/SystemConfig( 7653): BUILD Country: EU
I/SystemConfig( 7653): BUILD Operator: OPEN
,I/ActivityManager(  863): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7679 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  863): Killing 7361:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  863): failed to open /acct/uid_10053/pid_7361/cgroup.procs: No such file or directory
,I/SystemConfig( 7653): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7653): existFile = false
I/SystemConfig( 7653): canReadFile = false
I/SystemConfig( 7653): systemFeature RCS result false
D/SystemConfig( 7653): refreshRcsSupport() :false
,I/LockScreenSettings( 7679): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/LockScreenSettings( 7679): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 7679): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7679): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7679): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7679): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  863): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7696 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  863): Killing 7551:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  863): failed to open /acct/uid_10038/pid_7551/cgroup.procs: No such file or directory
,W/ResourcesManager( 7696): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1939): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  863): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7721 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1939): UpdateCorporaTask done [took 89 ms] updated apps [took 89 ms] 
,I/ActivityManager(  863): Killing 7252:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  863): failed to open /acct/uid_10006/pid_7252/cgroup.procs: No such file or directory
,D/Finsky  ( 7721): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7721): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7721): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7721): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7721): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3247): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3247): created cursor android.database.sqlite.SQLiteCursor@185318cf on behalf of 7721
D/Finsky  ( 7721): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Ads     ( 7721): Skipping gmscore version check
D/Finsky  ( 7721): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7721): [1] Libraries$2.run: Finished loading 1 libraries.
D/PackageBroadcastService( 5614): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5614): Null package name or gms related package.  Ignoreing.
,D/Finsky  ( 7721): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 5614): updateResources: need to parse f{com.google.android.gms}
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Icing   ( 5614): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Icing   ( 5614): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  863): Killing 2669:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  280): 2669 died, releasing its sessions
V/AudioFlinger(  280):  pid 1743 @ 0
V/AudioFlinger(  280):  pid 3176 @ 1
V/AudioFlinger(  280):  pid 3176 @ 2
,W/libprocessgroup(  863): failed to open /acct/uid_10028/pid_2669/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  863): Killing 7453:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7402): android.os.DeadObjectException
,W/libprocessgroup(  863): failed to open /acct/uid_10089/pid_7453/cgroup.procs: No such file or directory
W/ActivityManager(  863): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
W/System.err( 7402): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7402): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7402): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7402): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7402): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7402): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7402): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7402): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7402): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7402): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7402): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7402): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7402): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7402): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7402): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7402): android.os.DeadObjectException
W/System.err( 7402): 	at android.os.BinderProxy.transactNative(Native Method)
,W/System.err( 7402): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7402): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7402): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7402): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7402): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7402): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7402): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7402): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7402): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7402): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7402): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7402): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7402): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7402): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/ActivityManager(  863): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7809 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7809): Quickset Services start...
,I/UEI.SmartControl( 7809): Manufacture = LGE
D/UEI.SmartControl( 7809): File observer start...
E/UEI.SmartControl( 7809): IR Port is disabled: false
,D/UEI.SmartControl( 7809): Starting file observer...
D/UEI.SmartControl( 7809): Extracting JNI libs...
D/UEI.SmartControl( 7809): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7809): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7809): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7809): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7809): --- Selecting new region: 2
I/UEI.SmartControl( 7809): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7809): Platform has CIR...
D/UEI.SmartControl( 7809): NO CIR support, need to check package...
I/UEI.SmartControl( 7809): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7809): QS Service created
E/UEI.SmartControl( 7809): QS start get config
,D/UEI.SmartControl( 7809): Loading JNI Libs...
,D/UEI.SmartControl( 7809):  configuring local db...
D/UEI.SmartControl( 7809):  ---- Has DB8: true
,D/UEI.SmartControl( 7809): QS start statue = true Error code = 0
D/UEI.SmartControl( 7809): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7809): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7809): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7809): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7809): IrrcClient ++ 
D/irrcClient( 7809): getIrrcService ++ 
D/irrcClient( 7809): getIrrcService -- 
D/irrcClient( 7809): IrrcClient -- 
W/irrc_jni( 7809): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7809): Services init done
,I/UEI.SmartControl( 7809): Device manager: loading config....
D/UEI.SmartControl( 7809): QS Service init finished
D/UEI.SmartControl( 7809): Config is loaded...
D/UEI.SmartControl( 7809): QS Service version name: 0.1.73
D/UEI.SmartControl( 7809): QS Service version code: 1073
D/UEI.SmartControl( 7809): Service requested: Control
I/ActivityManager(  863): Killing 7402:com.lge.qremote/u0a106 (adj 15): empty #11
,W/libprocessgroup(  863): failed to open /acct/uid_10106/pid_7402/cgroup.procs: No such file or directory
D/UEI.SmartControl( 7809): Internal service binding...
,D/UEI.SmartControl( 7809):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7809): Notify AllClients services are ready: 0
,D/PowerManagerServiceEx(  863): acquireWakeLockInternal: lock=358834447, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=863
,D/WeatherService( 2657): 2 : TimeTick Intent has been received, Time(hour:min:sec) 8:30:0
,D/WeatherService( 2657): 2 : TimeTick Intent And Screen On
D/WeatherService( 2657): 2 : SDK version : 21
W/ActivityManager(  863): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2657): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2657): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2657): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2657): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2657): 2 : This is isUpdating : false
,D/WeatherService( 2657): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2657): 2 : buildUpdate, appWidgetId: 2
I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
D/WeatherTheme( 2657): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2657): 2 : Fixed theme : optimus
,D/WeatherReflect( 2657): 2 : Map key string is -2
,I/[SystemUI]Clock( 1372): called onTimeUpdated()
,D/lim     ( 2657): 2 : time = 08:30
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/WeatherReflect( 2657): Model Name : LG-D722
D/WeatherTheme( 2657): 2 : Different view - status_min_formatted : 29 != 30
D/WeatherTheme( 2657): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2657): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2657): strTheme: com.lge.launcher2.theme.optimus
,D/Theme   ( 2657): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2657): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2657): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
,D/Weather4x2_optimus( 2657): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2657): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2657): forecast size is 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/Theme   ( 2657): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2657): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2657): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2657): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2657): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2657): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2657): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2657): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2657): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2657): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2657): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2657): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2657): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2657): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2657): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2657): url is : null
D/Theme   ( 2657): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2657): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2657): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2657): 2 : update view, appWidgetId: 2
D/WeatherService( 2657): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 8:30:0
,D/PowerManagerServiceEx(  863): releaseWakeLockInternal: lock=358834447 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ActivityManager(  863): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7856 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 7856): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7856): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@bdc1670
I/ActivityManager(  863): Killing 7194:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  863): failed to open /acct/uid_10061/pid_7194/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  863): battery changed pluggedType: 2
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/UEI.SmartControl( 7809): Internal timer expired: 1
,D/UEI.SmartControl( 7809): Service.onUnbind: IControl
D/UEI.SmartControl( 7809): Service.onDestroy
D/UEI.SmartControl( 7809): Shutdown IRRCPlayer... 
,W/irrc_jni( 7809): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7809): ~IrrcClient ++ 
D/irrcClient( 7809): ~IrrcClient -- 
W/irrc_jni( 7809): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7809): Blaster closed
D/UEI.SmartControl( 7809): Blaster closed
D/UEI.SmartControl( 7809): Shut down QS...
,D/UEI.SmartControl( 7809): Stopped file observer...
I/UEI.SmartControl( 7809): QS lib stop result = true
D/UEI.SmartControl( 7809): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 134382804955; DSPS: 4501989; Offset : -3017451928
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  863): ELAPSED_WAKEUP set : Alarm{37d159c type 2 when 144381 com.google.android.gms} when 144381
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1732): Vacuum at: now=1453879820248 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/PowerManagerService(  863): ALS enabled for SRE
,D/PowerManagerServiceEx(  863): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28992 ms ago)
D/qdlights(  863): set_light_backlight: 253
,D/qdlights(  863): set_light_backlight: 250
D/qdlights(  863): set_light_backlight: 246
,D/qdlights(  863): set_light_backlight: 243
,D/qdlights(  863): set_light_backlight: 240
,D/qdlights(  863): set_light_backlight: 236
,D/qdlights(  863): set_light_backlight: 233
,D/qdlights(  863): set_light_backlight: 230
,D/qdlights(  863): set_light_backlight: 226
,D/qdlights(  863): set_light_backlight: 223
,D/qdlights(  863): set_light_backlight: 220
,D/qdlights(  863): set_light_backlight: 216
,D/qdlights(  863): set_light_backlight: 213
,D/qdlights(  863): set_light_backlight: 210
,D/qdlights(  863): set_light_backlight: 206
,D/qdlights(  863): set_light_backlight: 203
,D/qdlights(  863): set_light_backlight: 200
,D/qdlights(  863): set_light_backlight: 196
,D/qdlights(  863): set_light_backlight: 193
,D/qdlights(  863): set_light_backlight: 190
,D/qdlights(  863): set_light_backlight: 186
,D/qdlights(  863): set_light_backlight: 183
,D/qdlights(  863): set_light_backlight: 180
,D/qdlights(  863): set_light_backlight: 176
,D/qdlights(  863): set_light_backlight: 173
,D/qdlights(  863): set_light_backlight: 170
,D/qdlights(  863): set_light_backlight: 166
,D/qdlights(  863): set_light_backlight: 163
,D/qdlights(  863): set_light_backlight: 160
,D/qdlights(  863): set_light_backlight: 156
,D/qdlights(  863): set_light_backlight: 153
,D/qdlights(  863): set_light_backlight: 150
,D/qdlights(  863): set_light_backlight: 146
,D/qdlights(  863): set_light_backlight: 143
,D/qdlights(  863): set_light_backlight: 140
,D/qdlights(  863): set_light_backlight: 136
,D/qdlights(  863): set_light_backlight: 133
,D/qdlights(  863): set_light_backlight: 130
,D/qdlights(  863): set_light_backlight: 126
,D/qdlights(  863): set_light_backlight: 123
,D/qdlights(  863): set_light_backlight: 120
,D/qdlights(  863): set_light_backlight: 116
,D/qdlights(  863): set_light_backlight: 113
,D/qdlights(  863): set_light_backlight: 110
,D/qdlights(  863): set_light_backlight: 106
,D/qdlights(  863): set_light_backlight: 103
,D/qdlights(  863): set_light_backlight: 100
,D/qdlights(  863): set_light_backlight: 96
,D/qdlights(  863): set_light_backlight: 93
,D/qdlights(  863): set_light_backlight: 90
,D/qdlights(  863): set_light_backlight: 86
,D/qdlights(  863): set_light_backlight: 83
,D/qdlights(  863): set_light_backlight: 80
,D/qdlights(  863): set_light_backlight: 76
,D/qdlights(  863): set_light_backlight: 73
,D/qdlights(  863): set_light_backlight: 70
,D/qdlights(  863): set_light_backlight: 66
,D/qdlights(  863): set_light_backlight: 63
,D/qdlights(  863): set_light_backlight: 60
,D/qdlights(  863): set_light_backlight: 56
,D/qdlights(  863): set_light_backlight: 53
,D/qdlights(  863): set_light_backlight: 50
,D/qdlights(  863): set_light_backlight: 46
,D/qdlights(  863): set_light_backlight: 43
,D/qdlights(  863): set_light_backlight: 40
,D/qdlights(  863): set_light_backlight: 36
,D/qdlights(  863): set_light_backlight: 33
,D/qdlights(  863): set_light_backlight: 30
,D/qdlights(  863): set_light_backlight: 26
,D/qdlights(  863): set_light_backlight: 23
,D/qdlights(  863): set_light_backlight: 20
,D/qdlights(  863): set_light_backlight: 16
,D/qdlights(  863): set_light_backlight: 13
,D/qdlights(  863): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 154383503489; DSPS: 5157371; Offset : -3017424859
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  863): ALS enabled for SRE
D/PowerManagerServiceEx(  863): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35982 ms ago)
I/PowerManagerService(  863): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  863): ALS enabled for SRE
D/PowerManagerServiceEx(  863): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35993 ms ago)
W/ContextImpl(  863): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  863): Sleeping (uid 1000)...
D/LPWGController(  863): [updateScreenState] screen on = false
D/LPWGController(  863): disable proximity sensor
D/LPWGController(  863): enable proximity sensor
I/SensorManager(  863): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2f50ea5d] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  863): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  863): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  863): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  863): activate: handle is 48, enable
V/sensors_hal_Ctx(  863): activate sensors is 1400000000000
D/sensors_hal_Thresh(  863): enable: handle=48
I/sensors_hal_SAM(  863): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  863): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  863): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  863): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  863): enable: Received response: 0
D/PowerManagerServiceEx(  863): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36035 ms ago)
I/Adreno-EGL(  863): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  863): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  863): Build Date: 03/02/15 Mon
I/Adreno-EGL(  863): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  863): Remote Branch: 
I/Adreno-EGL(  863): Local Patches: 
I/Adreno-EGL(  863): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1039 us)
,I/Sensors (  422): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  863): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  863): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  863): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  863): processInd: handle 48, count=1
V/sensors_hal_Thresh(  863): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  863): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  863): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  863): poll: count: 256
I/sensors_hal_Ctx(  863): poll: released wakelock sensor_ind
D/sensors_hal_Util(  863): waitForResponse: timeout=0
D/LPWGController(  863): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  863): current mode = 1  value = 1 1
,I/LPWGController(  863): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  863): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/qdlights(  863): set_light_backlight: 0
,I/SensorManager(  863): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  863): activate: handle is 46, disable
V/sensors_hal_Ctx(  863): activate sensors is 1000000000000
D/sensors_hal_LP2(  863): enable: handle=46
D/sensors_hal_LP2(  863): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  863): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
I/DisplayManagerService(  863): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/sensors_hal_SAM(  863): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  863): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
V/ActivityManager(  863): Display changed displayId=0
,D/DSDPConnection( 1743): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  863): Excessive delay in setPowerMode(): 226ms
I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  863): Got set_interactive hint
D/KeyguardViewMediator( 1372): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1372): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1332): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1332): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1372): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1372): handleNotifyScreenOff
,D/WifiServerServiceExt(  863): sendKtScanInterval  mRtspPlay : false
,D/ScreenTurnOffBySensor( 1372): unregisterProximitySensor
I/WifiServerServiceExt(  863): set CMD_KT_SCAN_INTERVAL
V/AudioFlinger(  280): setParameters(): io 0, keyvalue screen_state=on, calling pid 863
D/audio_hw_primary(  280): adev_set_parameters: enter: screen_state=on
V/voice   (  280): voice_set_parameters: enter: screen_state=on
V/compress_voip(  280): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  280): voice_extn_compress_voip_set_parameters: exit
V/voice   (  280): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  280): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  280): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  280): platform_set_parameters: exit with code(0)
D/StatusBarWindowView( 1372): onScreenTurnedOff why = 3
V/lge_audio_loopback(  280): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  280): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  280): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  280): adev_set_parameters: exit with code(0)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
,D/GpsLocationProvider(  863): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:true
I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDService( 1803): stopPatternFlashing()
D/Cliptray Service( 1803): lockStatus = 0
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1786): action : android.intent.action.SCREEN_ON
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): updateLightsLocked : turn off led
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/NfcServiceNXP( 1786): mScreenState : 3, mInProvisionMode : false
,D/NfcServiceNXP( 1786): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1786): isRequireNfcCRouting() return true
D/LNfcService( 1786): isHCERoutingtoHost() return : true
D/NfcService( 1786): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): newParams.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): screenState= 3
D/LEDHandler( 1803): RESTART MSG
D/NfcService( 1786): Discovery configuration equal, not updating.
D/SplitWindow(  863): check instance of lgWin Window{36bf27a0 u0 SearchPanel}
,D/InputDispatcher(  863): Window went away: Window{3f33f87e u0 SearchPanel}
,I/[SystemUI]Clock( 1372): onReceive = android.intent.action.SCREEN_ON
D/Ulp_jni (  863): JNI:system_update. Event-0
,I/LgeClockWidgetControlView( 1372): time changed, timezoneChanged : false
,V/PhoneApp( 1743): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2657): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 8:30:33
,D/WeatherService( 2657): 2 : ACTION screen on
D/WeatherService( 2657): 2 : shouldTimeTickRegistered : false
,D/Weather_cast( 2657): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2657): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 8:30:33
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): ACTION_SCREEN_ON
,D/AppCleanupService( 4164): android.intent.action.SCREEN_ON
,I/Sensors (  422): sns_pwr.c(301):releasing wakelock
,V/AudioFlinger(  280): setParameters(): io 0, keyvalue screen_state=off, calling pid 863
D/audio_hw_primary(  280): adev_set_parameters: enter: screen_state=off
V/voice   (  280): voice_set_parameters: enter: screen_state=off
V/compress_voip(  280): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  280): voice_extn_compress_voip_set_parameters: exit
V/voice   (  280): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  280): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  280): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  280): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  280): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  280): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  280): adev_set_parameters: exit with code(0)
D/WifiController(  863): CMD_SCREEN_OFF 
D/WifiController(  863): shouldWifiStayAwake TRUE
,D/GpsLocationProvider(  863): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:false
,I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1803): clear
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1786): action : android.intent.action.SCREEN_OFF
I/LEDService( 1803): updateLightsLocked : turn on led
E/LEDService( 1803): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1803): Can't handle this request of patternId:0
D/LEDHandler( 1803): RESTART MSG
D/NfcServiceNXP( 1786): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1878): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1743): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2657): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 8:30:33
D/WeatherService( 2657): 2 : ACTION screen off
D/WeatherService( 2657): 2 : TimeTick Receiver Unregister
D/WeatherService( 2657): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 8:30:33
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  863): ACTION_SCREEN_OFF
,D/AppCleanupService( 4164): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4164): AppUsageStatsSaveTask
E/NxpNfcJni( 1786): getReconnectState = 0x0
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
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
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1372): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  863): ELAPSED_WAKEUP set : Alarm{1336cf59 type 2 when 161912 com.android.systemui} when 161912
,D/PhoneUtils( 1743): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1743): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1743): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1743): getCallState : 0
,D/PhoneUtils( 1743): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1743): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1743): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1372): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1372): doKeyguard: not showing because lockscreen is off
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  863): battery changed pluggedType: 2
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  863): battery changed pluggedType: 2
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 174384192283; DSPS: 5812754; Offset : -3017437892
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  863): ELAPSED_WAKEUP set : Alarm{1959971e type 2 when 183206 android} when 183206
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ClearcutLoggerApiImpl( 1732): disconnect managed GoogleApiClient
,D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  863): battery changed pluggedType: 2
,D/PowerManagerServiceEx(  863): acquireWakeLockInternal: lock=358834447, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=863
,V/AlarmManager(  863): ELAPSED_WAKEUP set : Alarm{1664abff type 2 when 187861 com.google.android.gms} when 187861
D/PowerManagerServiceEx(  863): releaseWakeLockInternal: lock=358834447 [*alarm*], flags=0x0
,I/PhenotypeConfigurator( 1732): Scheduling Phenotype for one-off execution 9322 seconds from now (1453879863874)
,D/GetConfigurationSnapshotOperation( 1732): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1732): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1732): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  863): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 44933(2MB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 14MB/23MB, paused 1.300ms total 102.212ms
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
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
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  863): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  863): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  863): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  275): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  275): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  863): android: cancelAsUser(2) by android
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,D/LocationManagerService(  863): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  863): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  863): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  863): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 194384859150; DSPS: 6468136; Offset : -3017442645
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 214385536330; DSPS: 7123518; Offset : -3017436877
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 234386286219; DSPS: 7778903; Offset : -3017450137
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/HeadsetStateMachine( 1990): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
W/Settings(  863): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  863): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  863): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 254387043815; DSPS: 8434287; Offset : -3017424651
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 274387722505; DSPS: 9089670; Offset : -3017447630
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  863): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  863): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  863): tsOffsetIs: Apps: 294388466560; DSPS: 9745054; Offset : -3017436231
,I/jxcore-log( 5646): --= Surplus to requirements =--
I/jxcore-log( 5646): 
I/jxcore-log( 5646): ****TEST TOOK:  ms ****
I/jxcore-log( 5646): 
I/jxcore-log( 5646): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 5646): 
,D/AndroidRuntime( 8037): 
D/AndroidRuntime( 8037): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 8037): CheckJNI is OFF
,D/AndroidRuntime( 8037): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  863): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
,I/ActivityManager(  863): Killing 5646:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
W/PackageSettings(  863): Skipping PackageSetting{645e950 com.example.hello/10317} due to missing metadata
,I/WindowState(  863): WIN DEATH: Window{287bcd7d u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  863): Focus left window: Window{287bcd7d u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  863): Window went away: Window{287bcd7d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  863):   Force finishing activity ActivityRecord{2c831080 u0 com.test.thalitest/.MainActivity t222}
,V/ActivityManager(  863): Display changed displayId=0
D/DSDPConnection( 1743): Display #0 changed.
,W/ActivityManager(  863): Spurious death for ProcessRecord{48692ef 5646:com.test.thalitest/u0a316}, curProc for 5646: null
,I/ActivityManager(  863): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  863):   Force finishing activity ActivityRecord{2c831080 u0 com.test.thalitest/.MainActivity t222 f}
W/ActivityManager(  863): Duplicate finish request for ActivityRecord{2c831080 u0 com.test.thalitest/.MainActivity t222 f}
,I/[LGHome]EVENT( 1878): [Launcher.java:5203:onStart()]onStart
D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  863): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[LGHome]EVENT( 1878): [Launcher.java:776:onResume()]onResume
I/art     ( 1939): Explicit concurrent mark sweep GC freed 22543(1335KB) AllocSpace objects, 5(119KB) LOS objects, 40% free, 12MB/21MB, paused 2.309ms total 127.949ms
W/System.err( 3672): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,I/art     ( 5614): Explicit concurrent mark sweep GC freed 6558(326KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 13MB/18MB, paused 772us total 108.705ms
I/ActivityManager(  863): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8068 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/System.err( 3672): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3672): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3672): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3672): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3672): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3672): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3672): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3672): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3672): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3672): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3672): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/[LGHome]EVENT( 1878): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1878): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,I/[LGHome]EVENT( 1878): [Launcher.java:929:onResume()]onResume end
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
I/Activity( 1878): Activity.onPostResume() called 
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
,I/art     (  863): Explicit concurrent mark sweep GC freed 62164(3MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 15.301ms total 211.597ms
I/art     (  863): WaitForGcToComplete blocked for 171.571ms for cause Explicit
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
,W/[LGHome]LGWallpaperInfo( 1878): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1878): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourcesManager( 8068): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8068): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8068): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1372): handleShortcutListChanged...
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1372): createShortcutInfo...
I/SystemUI[Framework](  863): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
,D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
W/PhoneWindowManagerEx(  863): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  863): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  863): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  863): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@135739c5,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  863): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  863): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  863): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  863): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  863): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  863): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@135739c5,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  863): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/InputDispatcher(  863): Focus entered window: Window{dfa3a6b u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/administrator(  863): Handling package changes for user 0
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1372): handleShortcutListChanged...
,I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1878): [setNavigationBarColor] color=0x 0
I/LGEmail ( 8068): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 8068): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/art     (  863): Explicit concurrent mark sweep GC freed 6955(401KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.076ms total 232.140ms
,W/InputMethodManagerService(  863): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,W/InputMethodManagerService(  863): Got RemoteException sending setActive(false) notification to pid 5646 uid 10316
,D/AndroidRuntime( 8037): Shutting down VM
I/NotificationService(  863): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  863): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  863): Receieved: android.intent.action.PACKAGE_REMOVED
,D/TaskPersister(  863): removeObsoleteFile: deleting file=222_task.xml
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
I/PackageChangeReceiver( 8068): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,D/AppUp4:PreloadHelper( 7610): added Exclude : com.test.thalitest
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/ActivityManager(  863): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8094 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  863): Killing 7633:com.android.gallery3d/u0a23 (adj 15): empty #11
W/IInputConnectionWrapper( 1878): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 314us total 23.303ms
,E/b       ( 1625): Unable to connect to the editor to retrieve text... will retry later
,I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 22.950ms
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 22.585ms
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/libprocessgroup(  863): failed to open /acct/uid_10023/pid_7633/cgroup.procs: No such file or directory
,W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
I/Timeline(  863): Timeline: Activity_windows_visible id: ActivityRecord{37be5b54 u0 com.lge.launcher2/.Launcher t221} time:299170
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
,W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1878): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/ResourcesManager(  863): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
,I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
,W/IInputConnectionWrapper( 1878): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]

```
