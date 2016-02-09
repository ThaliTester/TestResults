#### Test 586983493da948e_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
,I/art     (  877): Explicit concurrent mark sweep GC freed 15351(860KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.258ms total 146.750ms
--------- beginning of system
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5444): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 5444): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5444): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  877): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5480 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  877): Killing 5221:com.google.android.music:main/u0a81 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/AlertService( 3848): Beginning updateAlertNotification
W/libprocessgroup(  877): failed to open /acct/uid_10081/pid_5221/cgroup.procs: No such file or directory
D/AlertService( 3848): No fired or scheduled alerts
I/NotificationManager( 3848): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3848): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3848): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3848): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3848): com.android.calendar: cancel(4) by com.android.calendar
I/art     ( 5444): CheckpointMarkThreadRoots callback created = 0xaaf2a1f0
I/NotificationManager( 3848): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3848): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3848): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3848): com.android.calendar: cancel(8) by com.android.calendar
W/ResourcesManager( 5480): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/NotificationManager( 3848): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3848): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3848): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3848): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3848): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3848): com.android.calendar: cancel(14) by com.android.calendar
V/JNIHelp ( 5444): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/NotificationManager( 3848): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3848): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3848): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3848): com.android.calendar: cancel(18) by com.android.calendar
I/art     ( 5444): CheckpointMarkThreadRoots callback created = 0xb050fa60
I/NotificationManager( 3848): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3848): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 3848): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
W/System  ( 5444): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5444): Installed default security provider GmsCore_OpenSSL
D/AlarmScheduler( 3848): No events found starting within 1 week.
V/AlarmManager(  877): ELAPSED_WAKEUP set : Alarm{3c9a34c5 type 2 when 80196 android} when 80196
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 5488): 
D/AndroidRuntime( 5488): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 5488): CheckJNI is OFF
I/ActivityManager(  877): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5531 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/GservicesProvider( 5531): Gservices pushing to system: true; secure/global: true
I/ActivityManager(  877): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5551 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 1936): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/AndroidRuntime( 5488): Calling main entry com.android.commands.am.Am
I/GoogleHttpClient( 5531): GMS http client unavailable, use old client
I/ActivityManager(  877): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/UpdateIcingCorporaServi( 1936): UpdateCorporaTask done [took 151 ms] updated apps [took 151 ms] 
D/ActivityManager(  877): setTaskToReturnTo : TaskRecord{a07377d #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  877): setTaskToReturnTo : TaskRecord{a07377d #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  877): AppWindowTokenEx init.. 
D/ContextHelper(  877): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  877): Focus left window: Window{3799163b u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5488): Shutting down VM
I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
I/GoogleHttpClient( 5531): GMS http client unavailable, use old client
D/SplitWindow(  877): check instance of lgWin Window{210ad1ca u0 Starting com.test.thalitest}
I/ActivityManager(  877): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5574 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/ActivityManager(  877): Killing 5278:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/HotwordDetector( 1936): Closing mic
I/MicrophoneInputStream( 1936): mic_close com.google.android.apps.gsa.speech.audio.u@2297c172
V/AudioRecord( 1936): stop()
D/AudioRecord( 1936): AudioRecord->stop()
V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
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
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb384d000
D/audio_hw_primary(  278): in_standby: enter: stream (0xb546ece0) usecase(7: audio-record)
I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  877): Starting window displayed
I/SystemUI[Framework](  877): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
V/audio_hw_primary(  278): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  278): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  278): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  278): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  278): disable_audio_route: exit
E/audio_hw_primary(  278): disable_snd_device: enter 144
D/hardware_info(  278): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  278): disable_snd_device: snd_device(144: lg-vr-handset-mic)
W/PhoneWindowManagerEx(  877): Call!!!getLGSystemUiVisibility. =0x0
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
D/StatusBarManagerServiceEx(  877): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  877): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  877): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@20e6aaad,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  877): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
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
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb384d000
V/AudioFlinger(  278): RecordThread: loop stopping
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
W/libprocessgroup(  877): failed to open /acct/uid_10014/pid_5278/cgroup.procs: No such file or directory
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1372): draw background and invalidate : color = 1a000000
V/AudioRecord( 1936): stop()
V/AudioRecord( 1936): stop()
V/AudioRecord( 1936): stop()
D/BarTransitions( 1372): draw background and invalidate : color = 16161616
V/AudioFlinger(  278): releasing 16 from 1936 for -1
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
V/AudioSystem( 1987): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): RecordThread 0xb384d000 exiting
V/AudioSystem( 2708): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3270): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  278): adev_close_input_stream: enter:stream_handle(0xb546ece0)
D/audio_hw_primary(  278): in_standby: enter: stream (0xb546ece0) usecase(7: audio-record)
V/audio_hw_primary(  278): in_standby: exit:  status(0)
V/AudioSystem( 1372): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  278): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  278): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  278): releaseInput() exit
V/AudioSystem(  877): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1749): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing update audio port list
V/AudioSystem( 1936): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioFlinger(  278): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  278): removeClient_l() pid 1936, calling pid 278
I/HotwordRecognitionRnr( 1936): Stopping hotword detection.
I/HotwordRecognitionRnr( 1936): Hotword detection finished
D/ContextHelper( 5574): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/Finsky  ( 5551): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
I/WebViewFactory( 5574): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5574): Time to load native libraries: 6 ms (timestamps 1397-1403)
I/LibraryLoader( 5574): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5574): Binding Chromium to main looper Looper (main, tid 1) {1d320845}
I/LibraryLoader( 5574): Expected native library version number "",actual native library version number ""
I/chromium( 5574): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5574): Initializing chromium process, singleProcess=true
W/art     ( 5574): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5574): ApplicationContext is null in ApplicationStatus
W/chromium( 5574): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5574): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5574): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5574): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5574): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5574): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5574): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5574): Remote Branch: 
I/Adreno-EGL( 5574): Local Patches: 
I/Adreno-EGL( 5574): Reconstruct Branch: 
D/Finsky  ( 5551): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 5551): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5551): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5551): com.android.vending: cancel(-1050172287) by com.android.vending
V/AudioPolicyService(  278): registerClient() client 0xb551c8a0, uid 10316
D/BluetoothManagerService(  877): Message: 20
D/BluetoothManagerService(  877): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@35681b9c:true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@1390bbdd on behalf of 5551
I/NotificationManager( 5551): com.android.vending: cancel(1003285959) by com.android.vending
,D/Finsky  ( 5551): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5551): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 5551): Skipping gmscore version check
I/ActivityManager(  877): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5645 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 308us total 24.962ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.669ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 298us total 21.397ms
,D/Finsky  ( 5551): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/art     ( 5574): Attempt to remove local handle scope entry from IRT, ignoring
,D/Finsky  ( 5551): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/Finsky  ( 5551): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/AwContents( 5574): onDetachedFromWindow called when already detached. Ignoring
I/ActivityManager(  877): Killing 5302:com.lge.email/u0a21 (adj 15): empty #11
D/SystemWebViewEngine( 5574): CordovaWebView is running on device made by: LGE
,W/ResourcesManager( 5645): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5645): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/libprocessgroup(  877): failed to open /acct/uid_10021/pid_5302/cgroup.procs: No such file or directory
,W/art     ( 5574): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5574): Attempt to remove local handle scope entry from IRT, ignoring
I/MultiDex( 5645): VM with version 2.1.0 has multidex support
I/MultiDex( 5645): install
I/MultiDex( 5645): VM has multidex support, MultiDex support library is disabled.
,I/Activity( 5574): Activity.onPostResume() called 
,D/OpenGLRenderer( 5574): Render dirty regions requested: true
I/OpenGLRenderer( 5574): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5574): Enabling debug mode 0
D/Atlas   ( 5574): Validating map...
,D/SplitWindow(  877): check instance of lgWin Window{141ab9f7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5574): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  877): Killing 5333:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/libprocessgroup(  877): failed to open /acct/uid_10009/pid_5333/cgroup.procs: No such file or directory
,D/InputDispatcher(  877): Focus entered window: Window{141ab9f7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  877): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  877): Displayed com.test.thalitest/.MainActivity: +1s364ms
I/Timeline(  877): Timeline: Activity_windows_visible id: ActivityRecord{1fa8e672 u0 com.test.thalitest/.MainActivity t222} time:82216
I/Timeline( 5574): Timeline: Activity_idle id: android.os.BinderProxy@3bf38fd8 time:82243
,V/JNIHelp ( 5645): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/BindingManager( 5574): Cannot call determinedVisibility() - never saw a connection for the pid: 5574
,W/ActivityThread( 5645): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5645): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@f7d6cbd: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5645): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 5645): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5645): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 5645): Reading stored module config
,D/PackageBroadcastService( 5645): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/JsMessageQueue( 5574): Set native->JS mode to OnlineEventsBridgeMode
,D/ChimeraCfgMgr( 5645): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5645): Loading module APK com.google.android.play.games
,W/art     ( 5645): Suspending all threads took: 10.111ms
,D/NativeLibraryUtils( 5645): Install completed successfully. count=14 extracted=0
,I/art     ( 5645): CheckpointMarkThreadRoots callback created = 0xb042d460
,I/art     ( 5645): CheckpointMarkThreadRoots callback created = 0xb042d440
,D/jxcore_app_log( 5574): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426416640
,D/ChimeraCfgMgr( 5645): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5645): Module APK com.google.android.play.games already loaded
I/chromium( 5574): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/ChimeraCfgMgr( 5645): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/PeopleDatabaseHelper( 5645): cleanUpNonGplusAccounts done.
D/AsyncTaskServiceImpl( 5645): Submit a task: k
,D/ChimeraCfgMgr( 5645): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/ChimeraCfgMgr( 5645): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 5645): Processing package: com.test.thalitest
,D/GassUtils( 5645): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 5645): Found info for package com.test.thalitest in db.
,I/Icing   ( 5645): Storage manager: low false usage 1.74MB avail 2.38GB capacity 4.06GB
I/art     ( 5574): CheckpointMarkThreadRoots callback created = 0x990e4bb0
,I/art     ( 5574): CheckpointMarkThreadRoots callback created = 0x990e4b80
,D/WearableService( 1731): callingUid 10006, callindPid: 1731
E/MDM     ( 1731): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5645): Restart initialization of location
,W/BaseAppContext( 5645): Using Auth Proxy for data requests.
I/art     ( 5645): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5645): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,E/BaseAppContext( 5645): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 5645): Using Auth Proxy for data requests.
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
W/BaseAppContext( 5645): Using Auth Proxy for data requests.
I/ActivityManager(  877): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5736 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/BaseAppContext( 5645): Using Auth Proxy for data requests.
,W/BaseAppContext( 5645): Using Auth Proxy for data requests.
W/BaseAppContext( 5645): Using Auth Proxy for data requests.
,W/BaseAppContext( 5645): Using Auth Proxy for data requests.
,I/ActivityManager(  877): Process com.android.contacts (pid 5391) has died
,W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
W/IcingInternalCorpora( 5645): getNumBytesRead when not calculated.
,I/art     (  877): Explicit concurrent mark sweep GC freed 20632(970KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 14.166ms total 213.137ms
,I/ActivityManager(  877): Process com.android.gallery3d (pid 5372) has died
,W/ActivityManager(  877): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5736): getAccountsCursor
,I/ActivityManager(  877): Process com.lge.appbox.client (pid 5353) has died
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  877): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  877): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5736): Observing account changes for notifications
,W/GAV2    ( 5736): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Icing   ( 5645): updateResources: need to parse f{com.google.android.gms}
,D/ChimeraCfgMgr( 5645): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5645): Module APK com.google.android.play.games already loaded
W/ActivityManager(  877): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5736): Error finding the version of the Email provider.....
E/Gmail   ( 5736): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5736): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5736): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5736): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5736): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5736): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5736): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5736): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5736): We do not support migrating this version of the Email provider.
,I/Gmail   ( 5736): getAccountsCursor
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 5645): Background sticky concurrent mark sweep GC freed 10736(820KB) AllocSpace objects, 7(112KB) LOS objects, 7% free, 13MB/14MB, paused 7.765ms total 35.551ms
,I/ActivityManager(  877): Process com.lge.lockscreensettings (pid 5410) has died
W/GCoreFlp( 1731): No location to return for getLastLocation()
,W/FusedLocationProvider( 1731): location=null
V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@17cb8352 on behalf of 5645
,W/InstanceID/Rpc( 5645): Found 10006
,I/art     ( 5531): Explicit concurrent mark sweep GC freed 7878(397KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.027ms total 66.033ms
,I/Gmail   ( 5736): notifyAccountChanged
I/Gmail   ( 5736): getAccountsCursor
,I/Gmail   ( 5736): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5736): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5736): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5736): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  877): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5795 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
D/InitAlarmsService( 3848): Clearing and rescheduling alarms.
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  877): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5807 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/art     ( 5574): Suspending all threads took: 18.783ms
,W/jxcore-log( 5574): Initializing JXcore engine
W/jxcore-log( 5574): JXcore engine is ready
I/art     ( 5574): Background sticky concurrent mark sweep GC freed 10552(997KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 20MB/20MB, paused 20.148ms total 76.117ms
,V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@7161623 on behalf of 5645
,V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@1384720 on behalf of 5645
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 5807): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/Icing   ( 5645): Internal init done: storage state 0
,I/NotificationManager( 5645): com.google.android.gms: cancel(10436) by com.google.android.gms
,W/Thread-677( 5708): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7310]" dev="sockfs" ino=7310 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-677( 5708): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-677( 5708): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8442]" dev="sockfs" ino=8442 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/Thread-677( 5708): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-677( 5708): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-677( 5708): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[26769]" dev="sockfs" ino=26769 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
D/CalendarProvider2( 5807): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1397fb90
,I/ActivityManager(  877): Process com.lge.eula (pid 5427) has died
W/jxcore-log( 5574): Starting JXcore engine
,D/CalendarProvider2( 5807): [getOrCreateCalendarAlarmManager]
I/Icing   ( 5645): Post-init done
I/CalendarProvider2( 5807): Created com.android.providers.calendar.CalendarAlarmManager@1d320845(com.android.providers.calendar.CalendarProvider2@1397fb90)
D/CalendarProvider2( 5807): Scheduling check of next Alarm
,D/CalendarProvider2( 5807): SCHEDULE_ALARM_REMOVE
D/PhoneMonitor( 5795): Register our PhoneStateListener
,I/Gmail   ( 5736): getAccountsCursor
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]Clock( 1372): called onTimeUpdated()
I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
,I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
,D/PhoneMonitor( 5795): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5795): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 5795): [parse] Load xml
D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
V/TelephonyAutoProfiling( 5795): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5795): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5795): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/CheckinService( 5645): Checkin interval check for package: unspecified last checkin: 1454986251996 min interval config: 0 actual interval: 7709
,I/CheckinService( 5645): Disabling old GoogleServicesFramework version
,W/jxcore-log( 5574): Platform android
W/jxcore-log( 5574): 
,W/jxcore-log( 5574): Process ARCH arm
W/jxcore-log( 5574): 
I/CheckinService( 5645): Checking schedule, now: 1454986259801 next: 1454986281948
I/CheckinService( 5645): active receiver: disabled
,I/ActivityManager(  877): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5843 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5843): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/WeatherService( 2692): 2 : TimeTick Intent has been received, Time(hour:min:sec) 3:51:0
,D/WeatherService( 2692): 2 : TimeTick Intent And Screen On
D/WeatherService( 2692): 2 : SDK version : 21
W/ActivityManager(  877): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2692): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2692): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2692): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2692): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2692): 2 : This is isUpdating : false
D/WeatherService( 2692): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2692): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2692): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2692): 2 : Fixed theme : optimus
D/WeatherReflect( 2692): 2 : Map key string is -2
D/lim     ( 2692): 2 : time = 03:51
I/WeatherReflect( 2692): Model Name : LG-D722
,D/WeatherTheme( 2692): 2 : Different view - status_min_formatted : 50 != 51
D/WeatherTheme( 2692): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2692): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2692): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2692): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2692): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2692): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2692): forecast size is 0
,D/Theme   ( 2692): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2692): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2692): strTheme: com.lge.launcher2.theme.optimus
I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
D/Theme   ( 2692): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/Theme_WeatherAncestor_optimus( 2692): WEATHER_CP_ACCU : 
I/[SystemUI]Clock( 1372): called onTimeUpdated()
I/Theme_WeatherAncestor_optimus( 2692): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2692): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2692): setTouchIntent, appWidgetId: 2
I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/Theme_WeatherAncestor_optimus( 2692): url is : null
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/Theme   ( 2692): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2692): 2 : update view, appWidgetId: 2
D/WeatherService( 2692): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 3:51:0
,W/ActivityManager(  877): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager(  877): RTC_WAKEUP set : Alarm{bc17d6d type 0 when 1454899810740 com.android.providers.contacts} when 1454899810740
V/AlarmManager(  877): ELAPSED_WAKEUP set : Alarm{24e7cda2 type 2 when 60095 com.google.android.talk} when 60095
V/AlarmManager(  877): RTC_WAKEUP set : Alarm{d26e1f0 type 0 when 1454986260265 com.google.android.googlequicksearchbox} when 1454986260265
,I/Babel_SMS( 5843): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5843): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5843): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5843): MmsConfig.loadFromDatabase
I/jxcore-log( 5574): JXcore Cordova bridge is ready!
I/jxcore-log( 5574): 
W/jxcore-log( 5574): JXcore engine is started
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/Babel_SMS( 5843): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5843): MmsConfig.loadFromResources
E/Babel_SMS( 5843): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5843): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
W/art     ( 5843): Suspending all threads took: 6.637ms
,D/SensorManager( 5843): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5843): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5843): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5843): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5843): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5843): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5843): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5843): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5843): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5843): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5843): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5843): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5843): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5843): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5843): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5843): found sensor: Motion Accel, handle=46
I/art     ( 5843): CheckpointMarkThreadRoots callback created = 0xb042d490
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/art     ( 5843): CheckpointMarkThreadRoots callback created = 0xb042d470
W/Settings( 5843): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5843): startup - clean
I/Icing   ( 5645): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/jxcore-log( 5574): Toggling radios to true
I/jxcore-log( 5574): 
,I/CalendarProvider2( 5807): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5807): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/BluetoothAdapter( 5574): enable(): BT is already enabled..!
I/Babel   ( 5843): deleted: false for 0
D/WifiServiceImplEx(  877): setWifiEnabled: true pid=5574, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
,D/WifiService(  877): setWifiEnabled: true pid=5574, uid=10316
D/WifiServiceImplEx(  877): disconnect pid=5574, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  877): reconnect pid=5574, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 5574): Radios toggled
I/jxcore-log( 5574): 
I/jxcore-log( 5574): My device name is: LGE-LG-D722
I/jxcore-log( 5574): 
I/wpa_supplicant( 2790): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
W/art     ( 5645): Suspending all threads took: 8.324ms
,I/art     ( 5645): Background sticky concurrent mark sweep GC freed 4829(355KB) AllocSpace objects, 5(80KB) LOS objects, 3% free, 13MB/14MB, paused 10.977ms total 46.500ms
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2790): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiStateMachine(  877): WifiStateMachine: Leaving Connected state
D/WfdsMonitor( 1803): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
E/WifiConfigStore(  877): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/LGWifiP2pService(  877): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  274): Clearing all IP addresses on wlan0
D/DhcpStateMachine(  877): RunningState{ when=-1ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 7
D/libc-netbsd(  877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1731): Read error: ssl=0xaaede400: I/O error during system call, Connection timed out
D/ConnectivityService(  877): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  877): ignoring duplicate network state non-change
D/ConnectivityService(  877): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
,D/WifiHS20(  877): hidePasspointNotification off =false
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  877): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/NativeCrypto( 1731): SSL shutdown failed: ssl=0xaaede400: I/O error during system call, Broken pipe
D/libc-netbsd(  877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  877): hidePasspointNotification off =false
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  877): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/WifiStateMachine(  877): Start Disconnecting Watchdog 1
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/wpa_supplicant( 2790): wlan0: CTRL-EVENT-SCAN-STARTED 
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:51:00.75 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:51:00.755 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
,D/LGWifiP2pService(  877): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/libc-netbsd(  877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  877): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
D/Icing   ( 5645): Loaded CLD2 Version V2.0 - 20141016
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  877): ValidatedState{ when=-9ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  877): DefaultState{ when=-18ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  877): Forcing reevaluation
,D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
,I/Icing   ( 5645): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,D/CommandListener(  274): Clearing all IP addresses on wlan0
,D/ConnectivityService(  877): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  877): disableDataServiceNotify
D/DSQN    (  877): stop dsqn bin
D/WifiHS20(  877): hidePasspointNotification off =false
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:51:00.847 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
D/WifiNetworkAgent(  877): NetworkAgent: NetworkAgent channel lost
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  877): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/WifiHS20(  877): hidePasspointNotification off =false
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:51:00.857 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  877): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:51:00.861 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  877): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
,D/ConnectivityService(  877): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,D/WifiServerServiceExt(  877): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  877): setSupplicantStateDISCONNECTED
D/WifiServerServiceExt(  877): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  877): setSupplicantStateSCANNING
D/ConnectivityService(  877):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  877):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  877): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  877): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  877): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  877): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524292
D/DhcpStateMachine(  877): StoppedState
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  877): Disconnected - quitting
D/DhcpStateMachine(  877): StoppedState{ when=-152ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CSLegacyTypeTracker(  877): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  877): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,D/ConnectivityService(  877): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/Tethering(  877): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1839): |CORE| No family connected
V/NetworkPolicy(  877): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  877): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  877): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  877): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  877): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  877): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  877): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  877):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
V/NetworkPolicy(  877): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  877): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/TelephonyNetworkFactory-1( 1749): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/NetworkManagementService(  877): Removing idletimer
W/Settings(  877): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = -1
W/AudioCapabilities( 5843): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5843): Unsupported mime audio/adpcm
W/AudioCapabilities( 5843): Unsupported mime audio/g726
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
W/AudioCapabilities( 5843): Unsupported mime audio/x-ms-wma
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/AudioCapabilities( 5843): Unsupported mime audio/wma-voice
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/VideoCapabilities( 5843): Unsupported mime video/mjpg
,W/VideoCapabilities( 5843): Unsupported mime video/theora
D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/AudioCapabilities( 5843): Unsupported mime audio/evrc
,W/AudioCapabilities( 5843): Unsupported mime audio/qcelp
W/VideoCapabilities( 5843): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5843): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5843): Unsupported mime audio/qcelp
W/AudioCapabilities( 5843): Unsupported mime audio/evrc
W/VideoCapabilities( 5843): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5843): Unsupported profile 4 for video/mp4v-es
I/ActivityManager(  877): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5882 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AudioManager( 5125): getMode name:com.lge.qremote
W/VideoCapabilities( 5843): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5843): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5843): Unrecognized profile 2130706433 for video/avc
,I/AudioManager( 5125): getMode name:com.lge.qremote
W/VideoCapabilities( 5843): Unrecognized profile 2130706433 for video/avc
,I/AudioManager( 5125): getMode name:com.lge.qremote
I/vclib   ( 5843): onServiceConnected
W/Babel   ( 5843): Attempted to change video mute state without an active call.
I/NotificationManager( 5843): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AudioManager( 5125): getMode name:com.lge.qremote
I/AudioManager( 5125): getMode name:com.lge.qremote
E/MDM     ( 1731): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5645): Restart initialization of location
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 5125): getMode name:com.lge.qremote
,W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
I/art     (  877): Explicit concurrent mark sweep GC freed 33625(1557KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.771ms total 189.062ms
,D/UEI.SmartControl( 5882): Quickset Services start...
I/UEI.SmartControl( 5882): Manufacture = LGE
,D/UEI.SmartControl( 5882): File observer start...
E/UEI.SmartControl( 5882): IR Port is disabled: false
D/UEI.SmartControl( 5882): Starting file observer...
D/UEI.SmartControl( 5882): Extracting JNI libs...
I/ActivityManager(  877): Process com.google.android.apps.docs (pid 5444) has died
D/UEI.SmartControl( 5882): --- this system supports 32-bit or 64-bit only
I/AudioManager( 5125): getMode name:com.lge.qremote
,I/NotificationManager( 5843): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 5843): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5843): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  877): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5909 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,V/JNIHelp ( 5843): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 5909): onCreate
W/AppUp4:DB( 5909):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 5909):  setFingerPrint start
I/AppUp4:DB( 5909):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 5909):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5909):  SDK version = 0
I/AppUp4:DB( 5909):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5909): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 5909): onReceive
I/AppUp4:CustModeStarterReceiver( 5909): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 5909): Context : android.app.ReceiverRestrictedContext@3386c4af
D/AppUp4:CustFacade( 5909): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5909): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 5909): begin check event
I/AppUp4:CustModeStarterReceiver( 5909): Event For Nothing, skip.
W/System  ( 5843): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5843): Installed default security provider GmsCore_OpenSSL
,D/UEI.SmartControl( 5882): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5882): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5882): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/ActivityManager(  877): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5929 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
V/AlarmManager(  877): ELAPSED_WAKEUP set : Alarm{270e364d type 2 when 87631 com.google.android.gms} when 87631
,I/UEI.SmartControl( 5882): --- Selecting new region: 2
I/UEI.SmartControl( 5882): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5882): Platform has CIR...
D/UEI.SmartControl( 5882): NO CIR support, need to check package...
,I/UEI.SmartControl( 5882): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5882): QS Service created
,E/UEI.SmartControl( 5882): QS start get config
I/wpa_supplicant( 2790): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,W/ResourcesManager( 5929): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5929): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5929): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5882): Loading JNI Libs...
,D/UEI.SmartControl( 5882):  configuring local db...
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
,D/LocSvc_java(  877): onReceive
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:51:01.921 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  877): NETWORK_STATE_CHANGED_ACTION [SCANNING]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  877): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
,D/WifiServerServiceExt(  877): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  877): setSupplicantStateASSOCIATING
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:51:01.926 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/wpa_supplicant( 2790): wlan0: Associated with c0:ff:d4:d3:aa:48
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
D/WifiServerServiceExt(  877): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  877): setSupplicantStateASSOCIATED
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
,W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  877): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:51:01.962 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  877): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  877): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  877): setSupplicantStateFOUR_WAY_HANDSHAKE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:51:01.966 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/wpa_supplicant( 2790): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant,( 2790): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
D/WifiServerServiceExt(  877): SUPPLICANT_STATE_CHANGED_ACTION
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  877): setSupplicantStateGROUP_HANDSHAKE
I/WifiServiceExtension(  877): setVHTCapabilityType  : false
I/WifiServerServiceExt(  877): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServerServiceExt(  877): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  877): setSecurityType  : 2
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  877): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:51:02.046 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
D/ConnectivityService(  877): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  877): Got NetworkAgent Messenger
D/ConnectivityService(  877): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  877): NetworkAgent connected
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
E/WifiConfigStore(  877): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  877): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:51:02.053 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
E/WifiConfigStore(  877): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,I/InputReader(  877): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]QPairHandler( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 9
D/libc-netbsd(  877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
D/libc-netbsd(  877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  274): Setting iface cfg
,E/WifiStateMachine(  877): Start Dhcp Watchdog 2
D/DhcpStateMachine(  877): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  877): WaitBeforeStartState
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
D/ConnectivityService(  877): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/AppConfig( 5929): Total System Memory = 906309632
,I/GalleryUtils( 5929): Application Heap = 96 MB
E/WifiStateMachine(  877): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  877): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  877): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3cfc5598 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3cfc5598 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  877): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
I/AppConfig( 5929): App Tier : NOT_DEF
,D/SystemHelper( 5929): region [EU], country [EU], operator [OPEN], sub-operator []
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/DhcpStateMachine(  877): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  877): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/CommandListener(  274): Setting iface cfg
I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 6
D/libc-netbsd(  877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  274): Trying to bring up wlan0
V/LgDhcpStateMachineHelper(  877): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/administrator(  877): Handling package changes for user 0
,I/ActivityManager(  877): Process com.lge.bnr (pid 5200) has died
,D/ConnectivityService(  877): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/LGWifiP2pService(  877): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
E/WifiStateMachine(  877): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  877): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/ConnectivityService(  877): ignoring duplicate network state non-change
,D/ConnectivityService(  877): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
E/WifiStateMachine(  877): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
D/ConnectivityService(  877): Adding iface wlan0 to network 101
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:51:02.335 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = true, mWifiLevel = 2
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:51:02.363 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
E/ConnectivityService(  877): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  877): Adding Route [fe80::/64 -> :: wlan0] to network 101
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
D/ConnectivityService(  877): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  274): netlink response contains error (File exists)
D/ConnectivityService(  877): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/ConnectivityService(  877): addLocalRoutetoDefaultNetwork
D/ConnectivityService(  877): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
D/ConnectivityService(  877): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1372): mWifiConnected = true, mWifiLevel = 2
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  877): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  877): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  877): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  877): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  877): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  877): EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService(  877): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  877):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  877):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  877):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  877):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  877):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  877): currentScore = 0, newScore = 20
D/ConnectivityService(  877):    accepting network in place of null
D/ConnectivityService(  877): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  877): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  877):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/UEI.SmartControl( 5882):  ---- Has DB8: true
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:51:02.382 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:51:02.386 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/TelephonyNetworkFactory-1( 1749): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  877): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  877): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/ConnectivityService(  877): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  877): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  877): [e] list.add(nai) empty : false size: 1
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/ConnectivityService(  877): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = 1
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  877): [LWD] Start DNSResolver start to wait
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1372): Remote
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  877): [LWD] wait 500ms before dns check
D/ConnectivityService(  877): validation of new default Network = false
D/ConnectivityService(  877): Default network via Wi-Fi connected. start DSQN
D/DSQN    (  877): enableDataServiceNotify 
D/DSQN    (  877): start dsqn bin
D/UEI.SmartControl( 5882): QS start statue = true Error code = 0
,D/DhcpStateMachine(  877): DHCPV4 request on wlan0
V/LgDhcpStateMachineHelper(  877): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  877): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/UEI.SmartControl( 5882): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 5882): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/ConnectivityService(  877): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  877):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  877):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  877): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524290
I/DSQN    ( 5953): DSQN samuel.seo ver 141203
E/DSQN    ( 5953): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5953): created command queue thread
I/DSQN    ( 5953): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5953): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/dhcpcd  ( 5954): version 5.5.6 starting
I/ActivityManager(  877): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5955 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
E/dhcpcd  ( 5954): get_duid: Read-only file system
V/NetworkPolicy(  877): [LG_RESTRICTED] checkMobilePolicy_type()
D/UEI.SmartControl( 5882): IRRCDataComm has AudioManager!!!!.
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
I/CheckinService( 5645): Checkin interval check for package: unspecified last checkin: 1454986251996 min interval config: 0 actual interval: 10493
,D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/art     ( 5645): Background sticky concurrent mark sweep GC freed 1791(102KB) AllocSpace objects, 0(0B) LOS objects, 1% free, 14MB/14MB, paused 17.872ms total 44.261ms
I/NotificationService(  877): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  877): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  877): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/irrc_jni( 5882): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5882): IrrcClient ++ 
D/irrcClient( 5882): getIrrcService ++ 
D/irrcClient( 5882): getIrrcService -- 
D/irrcClient( 5882): IrrcClient -- 
W/irrc_jni( 5882): IRRCPlayer_nativeInit -- 
I/dhcpcd  ( 5954): wlan0: rebinding lease of 192.168.1.134
D/UEI.SmartControl( 5882): Services init done
,I/BackupManagerService(  877): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/CheckinService( 5645): Checking schedule, now: 1454986262564 next: 1454986281948
I/CheckinService( 5645): active receiver: disabled
I/UEI.SmartControl( 5882): Device manager: loading config....
,D/WifiServerServiceExt(  877): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  877): setSupplicantStateCOMPLETED
,D/UEI.SmartControl( 5882): QS Service init finished
D/WifiServerServiceExt(  877): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  877): setSupplicantStateCOMPLETED
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  877): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  877): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/WifiHS20(  877): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  877): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiHS20(  877): [PASSPOINT] passpointNotification: hs20AP list is checked
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  877): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
D/Tethering(  877): MasterInitialState.processMessage what=3
D/UEI.SmartControl( 5882): Config is loaded...
D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/UEI.SmartControl( 5882): QS Service version name: 0.1.73
,D/UEI.SmartControl( 5882): QS Service version code: 1073
D/UEI.SmartControl( 5882): Service requested: Control
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
V/BackupManagerService(  877): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/UEI.SmartControl( 5882): Internal service binding...
V/BackupManagerService(  877): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@279e29c3
D/UEI.SmartControl( 5882):  ----- QS SDK is ready!!!
,D/UEI.SmartControl( 5882): -----IControl: 11
I/UEI.SmartControl( 5882): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5882): Caller: com.lge.qremote
D/UEI.SmartControl( 5882): ------------ IControl registerCallback...
I/UEI.SmartControl( 5882): Registering callback...
D/UEI.SmartControl( 5882): -----IControl: 19
D/UEI.SmartControl( 5882): Caller: com.lge.qremote
I/UEI.SmartControl( 5882): Registering Services Ready callback...
I/UEI.SmartControl( 5882): Notify client services are ready...
D/UEI.SmartControl( 5882): -----IControl: 8
D/UEI.SmartControl( 5882): Caller: com.lge.qremote
,I/ActivityManager(  877): Killing 3848:com.android.calendar/u0a13 (adj 15): empty #11
,W/ResourcesManager( 5955): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5955): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5955): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 5955): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5955): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  877): failed to open /acct/uid_10013/pid_3848/cgroup.procs: No such file or directory
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
W/ResourcesManager(  877): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/SystemConfig( 5955): BUILD Country: EU
,I/SystemConfig( 5955): BUILD Operator: OPEN
W/ResourceType(  877): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  877): [LWD] DNSResolver start dns
D/libc-netbsd(  877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out(  877): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  877): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  877): Checking http://clients3.google.com/generate_204 on "NG700"
D/libc-netbsd(  877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 5953): first global connection report this to start monitoring at DSQM.
,I/DSQN    ( 5953): restart monitoring
D/LGDataListener(  274): argv[0]=dsqncommand
D/LGDataListener(  274): argv[1]=wlan0
D/LGDataListener(  274): argv[2]=1
D/LGDataListener(  274): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  877): DSQM DsqnNotification wlan0  1
D/DSQN    (  877): start to monitor internet connection
I/DSQN    ( 5953): dsqn report finish
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  877): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 02:51:02 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1454986262994], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1454986262975]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  877): Don't send network conditions - lacking user consent.
,D/WifiServiceExtension( 1803): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  877): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  877): Validated
D/ConnectivityService(  877): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  877): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  877):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  877):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  877):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  877): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  877): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  877):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  877):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  877): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  877): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  877): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  877): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  877):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1749): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1749):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/ActivityManager(  877): Process com.google.android.gm (pid 5736) has died
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/WifiDataContinuityService(  877): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  877): set CMD_CAPTIVE_CHECK_COMPLETED
I/GCoreNlp( 1731): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  877): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5990 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,D/TelephonyIcons( 1372): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1372): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully_disconnected mWifiActivityIconId=(null)
I/SystemConfig( 5955): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/SystemConfig( 5955): existFile = false
I/SystemConfig( 5955): canReadFile = false
I/SystemConfig( 5955): systemFeature RCS result false
D/SystemConfig( 5955): refreshRcsSupport() :false
D/LocationProviderProxy(  877): applying state to connected service
,I/LockScreenSettings( 5990): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 5990): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5990): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5990): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5990): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5990): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  877): Process com.android.vending (pid 5551) has died
,I/UpdateIcingCorporaServi( 1936): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  877): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6010 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/ConnectivityService(  877): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/UpdateIcingCorporaServi( 1936): UpdateCorporaTask done [took 160 ms] updated apps [took 159 ms] 
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  877): Process com.lge.qremote (pid 5125) has died
,D/Finsky  ( 6010): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Netd    (  274): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  877): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  877): identical MTU - not setting
D/Nat464Xlat(  877): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  877): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  877):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  877):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  877): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
I/dhcpcd  ( 5954): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
D/ConnectivityService(  877): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  877): enableDataServiceNotify 
D/DSQN    (  877): start dsqn bin
D/ConnectivityManager.CallbackHandler( 1372): CM callback handler got msg 524295
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-61 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:51:03.923 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/dhcpcd  ( 5954): wlan0: leased 192.168.1.134 for 86400 seconds
D/DSQN    (  877): dsqn is running restart
D/ConnectivityService(  877): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  877): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
I/DSQN    ( 6040): DSQN samuel.seo ver 141203
E/DSQN    ( 6040): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 6040): created command queue thread
I/DSQN    ( 6040): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 6040): Interface wlan0 netmask 255.255.255.0 0xc0a80186
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/GpsLocationProvider(  877): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/LocSvc_java(  877): onReceive
D/LocSvc_java(  877): got connectivity action
I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  877): broadcast - no network connections
D/LocSvc_java(  877): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  877): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  877): onReceive
D/LocSvc_java(  877): got connectivity action
D/LocSvc_java(  877): broadcast - no network connections
D/LocSvc_java(  877): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  877): Sending msg: 4 arg1:0 arg2:1
,D/LocSvc_java(  877): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  877): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  877): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  877): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  877): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  877): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  877): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  877): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/GpsLocationProvider(  877): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/Finsky  ( 6010): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6010): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6010): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6010): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@d6238d9 on behalf of 6010
D/libc-netbsd(  877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  877): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  877): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  877): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,D/libc-netbsd(  877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  877): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  877): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  877): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  877): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  877): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  877): RunningState
D/Ads     ( 6010): Skipping gmscore version check
D/Finsky  ( 6010): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6010): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 6010): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 5645): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/Finsky  ( 6010): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  877): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6083 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/PackageBroadcastService( 5645): Null package name or gms related package.  Ignoreing.
I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 323us total 26.900ms
,I/Icing   ( 5645): updateResources: need to parse f{com.google.android.gms}
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 613us total 36.069ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 300us total 25.748ms
W/ResourcesManager( 6083): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,V/AlarmManager(  877): ELAPSED_WAKEUP set : Alarm{b81dfda type 2 when 90417 com.android.providers.calendar} when 90417
,D/BluetoothManagerService(  877): Message: 20
D/BluetoothManagerService(  877): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8be0ae8:true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
,D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
V/LGMDMManager( 6083): Create singleton instance
,I/AudioManager( 6083): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5882): -----IControl: 11
,D/UEI.SmartControl( 5882): Caller: com.lge.qremote
D/UEI.SmartControl( 5882): ------------ IControl registerCallback...
I/UEI.SmartControl( 5882): Registering callback...
D/UEI.SmartControl( 5882): -----IControl: 19
D/UEI.SmartControl( 5882): Caller: com.lge.qremote
I/UEI.SmartControl( 5882): Registering Services Ready callback...
I/UEI.SmartControl( 5882): Notify client services are ready...
D/UEI.SmartControl( 5882): -----IControl: 8
D/UEI.SmartControl( 5882): Caller: com.lge.qremote
V/SetupWizard( 5795): Connected to Gservices successfully
,I/ActivityManager(  877): Killing 5807:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  877): failed to open /acct/uid_10014/pid_5807/cgroup.procs: No such file or directory
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/LocationInitializer( 5645): Restart initialization of location
,D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1731): [123] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1731): propertyValue:false
,I/DSQN    ( 6040): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 6040): restart monitoring
,I/ActivityManager(  877): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6117 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/DSQN    ( 6040): dsqn report finish
D/LGDataListener(  274): argv[0]=dsqncommand
D/LGDataListener(  274): argv[1]=wlan0
D/LGDataListener(  274): argv[2]=1
D/LGDataListener(  274): notifyDSQN DSQN STARTMONITOR wlan0 1
D/DSQN    (  877): DSQM DsqnNotification wlan0  1
D/DSQN    (  877): start to monitor internet connection
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/GCoreFlp( 1731): No location to return for getLastLocation()
,W/FusedLocationProvider( 1731): location=null
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 03:51:05.119 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/ActivityManager(  877): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6117): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1731): Explicit concurrent mark sweep GC freed 31382(1971KB) AllocSpace objects, 15(240KB) LOS objects, 40% free, 13MB/22MB, paused 3.185ms total 110.934ms
,W/GAV2    ( 6117): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  877): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ConnectivityService(  877): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  877): onReceive
D/LocSvc_java(  877): got connectivity action
D/LocSvc_java(  877): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  877): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  877): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  877): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  877): ignore wifi update if we are not in OPENING or CLOSING
E/Gmail   ( 6117): Error finding the version of the Email provider.....
E/Gmail   ( 6117): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6117): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6117): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6117): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6117): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6117): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6117): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6117): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/[SystemUI]QuickSettingsHandler( 1372): Got action android.net.conn.CONNECTIVITY_CHANGE at null
W/EmailMigration( 6117): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6117): getAccountsCursor
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1936): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/ActivityManager(  877): Killing 5909:com.lge.appbox.client/u0a11 (adj 15): empty #11
V/WifiInternetCheck(  877): Single check msg out of sync, ignoring.
,W/libprocessgroup(  877): failed to open /acct/uid_10011/pid_5909/cgroup.procs: No such file or directory
W/ActivityManager(  877): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/GpsLocationProvider(  877): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  877): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,I/Gmail   ( 6117): Observing account changes for notifications
,I/Icing   ( 5645): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/Icing   ( 5645): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/art     (  877): Explicit concurrent mark sweep GC freed 75259(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.429ms total 188.940ms
,W/ActivityManager(  877): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  877): Process com.android.contacts (pid 5955) has died
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/QcrilMsgTunnelSocket( 2319): readRilMessage: Buffer = [B@7bc2c89 HexData = [010000000404000011000000514f454d484f4f4bef0308000100000003]
D/QcrilMsgTunnelSocket( 2319): Rcvd UNSOL response with 28 bytes data for SUB0
D/QcrilMsgTunnelSocket( 2319): Response ID 525295 is not served in this process.
D/QcrilMsgTunnelSocket( 2319): To broadcast an Intent via the notifier to external apps
D/QcrilMsgTunnelIfaceManager( 2319): handleMessage what = 0
D/QcrilMsgTunnelIfaceManager( 2319): Broadcasting intent ACTION_UNSOL_RESPONSE_OEM_HOOK_RAW
,D/QC_RIL_OEM_HOOK( 1749): Received Broadcast Intent ACTION_UNSOL_RESPONSE_OEM_HOOK_RAW
D/QC_RIL_OEM_HOOK( 1749): Oem ID in QCRILHOOK UNSOL RESP is QOEMHOOK
,V/TelephonyAutoProfiling( 1749): [getValue] PROFILE key : HOME_NETWORK, value : null, phoneId : 0
,I/ActivityManager(  877): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6170 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  877): Process com.android.gallery3d (pid 5929) has died
,I/Gmail   ( 6117): notifyAccountChanged
W/ResourcesManager( 6170): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Gmail   ( 6117): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6117): getAccountsCursor
I/Gmail   ( 6117): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PhoneInterfaceManager( 1749): [PhoneIntfMgr] handleMessage : 2
I/Gmail   ( 6117): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6117): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PhoneInterfaceManager( 1749): [PhoneIntfMgr] handleMessage : 3
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CalendarApplication( 6170): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6170): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6170): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@1ba6e48e, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3386c4af, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@ea940bc, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1d320845, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1730bb9a, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2c04fccb, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1327aca8, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@306fe3c1, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@1f4ef766, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@22e49aa7, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@69eeb54, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1455fafd, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@37c323f2, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@32363a43, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@39a968c0, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@2f8c49f9, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2cdb8d3e, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3a78379f, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@2a1c50ec, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@113e8cb5, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2f7f3f4a, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@3bb2aebb, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@3bf38fd8, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@15983f31, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@25fa0616, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@24537b97, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@14fdd184, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@16009d6d, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@3d886da2, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@31ca3a33, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@74881f0, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2116a369, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@8a3c1ee, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3ee4468f, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@364bcd1c, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@366d0d25, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@360e0efa, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@1be8bcab, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@22d69f08, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@20656a1, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@2c9e20c6, lg_preferences_,recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@c74
D/GeneralPreferenceUtils( 6170): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
I/Gmail   ( 6117): getAccountsCursor
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Config  ( 6170): [init]
I/Config  ( 6170): LGCalendar ver.4.40.17
I/Config  ( 6170): start check model
I/Config  ( 6170): start check native_ca
I/Config  ( 6170): Config Operator=OPEN, Country=EU
D/Config  ( 6170): [setDefaultValuesToPref]
,D/Config  ( 6170): [parseProfiles]
D/ProfilesParser( 6170): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6170): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6170): [updateProfiletoCountryInfo]
D/GeneralPreference( 6170): [checkAndMigrateOldPreference]
D/AlertReceiver( 6170): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6170): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6170): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/AlertUtils( 6170): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6170): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6170): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6170): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6170): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6170): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6170): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6170): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6170): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6170): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6170): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6170): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6170): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6170): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6170): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6170): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6170): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,I/AlertUtils( 6170): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6170): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 6170): onHandleIntent
,D/HolidayDataLoader( 6170): readJsonAsset : holiday.json
D/AlertService( 6170): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6170): [updateWidgets] 
D/MonthWidgetProvider( 6170): [onReceive]
D/CalendarWidgetProvider( 6170): [onReceive]
D/CalendarWidgetProvider( 6170): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6170): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6170): [onReceive]
D/CalendarWidgetProvider( 6170): [onReceive]
,D/CalendarWidgetProvider( 6170): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6170): [onCreate] mContext.getPackageName() = com.android.calendar
I/ActivityManager(  877): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6199 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,E/HolidayIntentService( 6170): onHandleIntent:holiday data empty
,W/ResourcesManager( 6199): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6199): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6199): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6199): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6199): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/libc-netbsd(  877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/IndexDatabaseHelper( 6199): Using schema version: 115
I/IndexDatabaseHelper( 6199): Index is fine
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  877): propertyValue:false
D/libc-netbsd(  877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  877): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  877): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  274): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out(  877): propertyValue:false
V/WifiInternetCheck(  877): isHttpConnectionAvailable - We got a valid response : 204
,V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6199): MCCMNC not supported: null
I/ActivityManager(  877): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6226 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6226): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6226): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6226): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/AlarmManager(  877): RTC_WAKEUP set : Alarm{1ff143bc type 0 when 1454986267272 com.android.vending} when 1454986267272
,D/Finsky  ( 6010): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6199): MCCMNC not supported: null
I/PCSuite ( 6226): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6226): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6226): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6199): MCCMNC not supported: null
I/PCSuite ( 6226): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6226): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6226): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6199): MCCMNC not supported: null
I/NotificationManager(  877): android: cancelAsUser(2) by android
I/PCSuite ( 6226): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6226): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6226): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6199): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6199): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6199): MCCMNC not supported: null
,D/libc-netbsd( 6010): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6010): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd( 6010): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6010): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/WiFiOffLoadBroadcast( 6199): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6199): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6199): MCCMNC not supported: null
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6010): propertyValue:false
D/libc-netbsd( 6010): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6010): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WiFiOffLoadBroadcast( 6199): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6199): MCCMNC not supported: null
D/libc-netbsd( 6010): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6010): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  877): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6264 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/UEI.SmartControl( 5882): Internal timer expired: 1
,I/NotificationManager( 5843): com.google.android.talk: cancel(8) by com.google.android.talk
,I/AppUp4:AppBoxCP( 6264): onCreate
W/AppUp4:DB( 6264):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6264):  setFingerPrint start
,I/AppUp4:DB( 6264):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6264):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6264):  SDK version = 0
,I/AppUp4:DB( 6264):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6264): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6264): onReceive
I/AppUp4:CustModeStarterReceiver( 6264): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6264): Context : android.app.ReceiverRestrictedContext@3386c4af
D/AppUp4:CustFacade( 6264): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6264): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6264): begin check event
I/AppUp4:CustModeStarterReceiver( 6264): Event For Nothing, skip.
,I/ActivityManager(  877): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6284 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  877): android: cancelAsUser(2) by android
,W/ResourcesManager( 6284): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6284): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6284): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.,
,I/qtaguid ( 6010): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6010): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6010): untagSocket(41) failed with errno -22
D/Finsky  ( 6010): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/AppConfig( 6284): Total System Memory = 906309632
,I/GalleryUtils( 6284): Application Heap = 96 MB
I/AppConfig( 6284): App Tier : NOT_DEF
D/SystemHelper( 6284): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  877): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6304 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  877): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6321 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  877): Killing 5990:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  877): failed to open /acct/uid_10069/pid_5990/cgroup.procs: No such file or directory
,I/NotificationManager(  877): android: cancelAsUser(2) by android
,W/ResourcesManager( 6304): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6304): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 6321): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6321): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6321): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6321): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6321): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/MultiDex( 6304): VM with version 2.1.0 has multidex support
I/MultiDex( 6304): install
I/MultiDex( 6304): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  877): Process com.google.android.gm (pid 6117) has died
,I/qtaguid ( 6010): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6010): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6010): untagSocket(41) failed with errno -22
I/SystemConfig( 6321): BUILD Country: EU
I/SystemConfig( 6321): BUILD Operator: OPEN
,V/JNIHelp ( 6304): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 94483698250; DSPS: 3194766; Offset : -3023978915
,W/ActivityThread( 6304): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6304): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12a9f17f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6304): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  877): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6343 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/NotificationManager( 6304): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6304): com.google.android.gms: cancel(39789) by com.google.android.gms
,I/SystemConfig( 6321): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6321): existFile = false
I/SystemConfig( 6321): canReadFile = false
I/SystemConfig( 6321): systemFeature RCS result false
D/SystemConfig( 6321): refreshRcsSupport() :false
,D/ChimeraCfgMgr( 6304): Reading stored module config
,I/art     ( 6010): CheckpointMarkThreadRoots callback created = 0xb0571730
D/ChimeraCfgMgr( 6304): Loading module com.google.android.gms.car from APK com.google.android.gms
I/art     ( 6010): CheckpointMarkThreadRoots callback created = 0xb0571710
,I/LockScreenSettings( 6343): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6343): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6343): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6343): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6343): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6343): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/UpdateIcingCorporaServi( 1936): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 5645): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 5645): Null package name or gms related package.  Ignoreing.
,V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6199): MCCMNC not supported: null
,I/Icing   ( 5645): updateResources: need to parse f{com.google.android.gms}
V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,I/UpdateIcingCorporaServi( 1936): UpdateCorporaTask done [took 84 ms] updated apps [took 84 ms] 
,D/WiFiOffLoadBroadcast( 6199): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6199): MCCMNC not supported: null
I/PCSuite ( 6226): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6226): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6199): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/NativeLibraryUtils( 6304): Install completed successfully. count=14 extracted=0
D/WiFiOffLoadBroadcast( 6199): MCCMNC not supported: null
I/PCSuite ( 6226): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6226): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/AudioManager( 6083): getMode name:com.lge.qremote
,D/CAR.SERVICE( 6304): Connecting to CarCallService...
,I/ActivityManager(  877): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6372 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  877): Process com.android.gallery3d (pid 6284) has died
,I/art     ( 6304): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6304): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 6304): com.google.android.projection.gearhead isn't installed.
,I/art     (  877): Explicit concurrent mark sweep GC freed 19806(998KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.111ms total 144.578ms
,I/ActivityManager(  877): Process com.android.contacts (pid 6321) has died
,D/CAR.TEL.Service( 6304): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6304): Creating a new PhoneAdapter instance
,W/ActivityManager(  877): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6304): setListener: com.google.android.gms.car.dn@2958925a
W/ActivityManager(  877): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6304): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6304): Starting CarCallService with initial phone null
,I/jxcore-log( 5574): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5574): 
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/NotificationManager( 6304): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6304): Package validated; name: com.android.vending
,I/NotificationManager( 6010): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6010): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/MusicStore( 6372): Database version: 120
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6372): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  877): android: cancelAsUser(2) by android
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6372): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6372): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6372): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6372): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6372): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/qtaguid ( 6010): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6010): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6010): untagSocket(41) failed with errno -22
,W/ActivityThread( 6372): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6372): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2faeb8d6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6372): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6372): GMSCore installation verified
I/ConfigStore( 6372): Config Database version: 1
,I/Icing   ( 5645): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5645): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,V/AlarmManager(  877): RTC_WAKEUP set : Alarm{3acb6103 type 0 when 1454986270453 com.google.android.googlequicksearchbox} when 1454986270453
,W/ResourcesManager( 6010): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6010): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MediaRouter( 6372): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6372): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6372): type=WIFI subType= reason=null isConnected=true
,W/ResourcesManager( 6010): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/NetworkMonitor( 6372): type=WIFI subType= reason=null isConnected=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  877): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6413 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/Finsky  ( 6010): [1] DailyHygiene.access$600: Logging device features
I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 23.428ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.498ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 20.521ms
,V/AlarmManager(  877): RTC_WAKEUP set : Alarm{19d51347 type 0 when 1454986270694 com.android.vending} when 1454986270694
,I/GHttpClientFactory( 6372): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6372): Using platform SSLCertificateSocketFactory
D/WearableService( 1731): callingUid 10006, callindPid: 1731
,D/DeviceConnectionService( 1731): client connected with version: 8296000
I/jxcore-log( 5574): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5574): 
,W/ResourcesManager( 6413): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6413): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6413): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  877): Process com.lge.appbox.client (pid 6264) has died
I/NotificationManager( 6372): com.google.android.music: cancel(1061) by com.google.android.music
,D/Finsky  ( 6010): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 6010): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  877): Killing 5480:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/jxcore-log( 5574): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5574): 
I/ActivityManager(  877): Killing 6343:com.lge.lockscreensettings/u0a69 (adj 15): empty #12
,I/jxcore-log( 5574): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5574): 
I/jxcore-log( 5574): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5574): 
I/jxcore-log( 5574): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5574): 
,W/libprocessgroup(  877): failed to open /acct/uid_10086/pid_5480/cgroup.procs: No such file or directory,
,I/LGEmail ( 6413): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6413): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ActivityManager(  877): Process com.android.settings (pid 6199) has died
W/libprocessgroup(  877): failed to open /acct/uid_10069/pid_6343/cgroup.procs: No such file or directory
,D/eas_req ( 6413): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  877): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6443 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/AlertService( 6170): Beginning updateAlertNotification
I/ActivityManager(  877): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6460 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/HubEmail( 6413): JNI_OnLoad()
I/HubEmail( 6413): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6413): registerNatives()
I/HubEmail( 6413): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6413): registerNativeMethods()
I/HubEmail( 6413): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6413): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/Settings( 6413): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ResourcesManager( 6460): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6460): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1397fb90
,D/LGDMClient( 6443): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6443): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
D/CalendarProvider2( 6460): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6460): Created com.android.providers.calendar.CalendarAlarmManager@1d320845(com.android.providers.calendar.CalendarProvider2@1397fb90)
W/ContextImpl( 6443): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6443): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,D/LGDMClient( 6443): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6443): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6443): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6443): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  877): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6494 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/AlertService( 6170): No fired or scheduled alerts
,I/NotificationManager( 6170): com.android.calendar: cancel(0) by com.android.calendar
W/ContextImpl( 6443): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
I/NotificationManager( 6170): com.android.calendar: cancel(1) by com.android.calendar
,E/LGDMClient( 6443): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6443): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6443): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6443): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6443): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/NotificationManager( 6170): com.android.calendar: cancel(2) by com.android.calendar
I/ActivityManager(  877): Killing 6226:com.lge.sync/1000 (adj 15): empty #11
,I/NotificationManager( 6170): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6170): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6170): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6170): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6170): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6170): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6170): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6170): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6170): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6170): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6170): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6170): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6170): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6170): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6170): com.android.calendar: cancel(17) by com.android.calendar
,I/NotificationManager( 6170): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6170): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6170): com.android.calendar: cancel(20) by com.android.calendar
,W/libprocessgroup(  877): failed to open /acct/uid_1000/pid_6226/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 6494): onCreate
,W/AppUp4:DB( 6494):  [AppBoxDatabaseHelper] construct
D/AlertService( 6170): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/ActivityManager(  877): Killing 5795:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/AppUp4:DB( 6494):  setFingerPrint start
I/AppUp4:DB( 6494):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6494):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6494):  SDK version = 0
I/AppUp4:DB( 6494):  beforefinger == newfinger no write in DB
W/libprocessgroup(  877): failed to open /acct/uid_10038/pid_5795/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6494): AppBoxApplication onCreate()
D/AlarmScheduler( 6170): No events found starting within 1 week.
,I/NetworkStateForAutoUpdateMonitor( 6494): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6494): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6494): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6494): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6494): onReceive
I/AppUp4:CustModeStarterReceiver( 6494): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6494): Context : android.app.ReceiverRestrictedContext@1730bb9a
D/AppUp4:CustFacade( 6494): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6494): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6494): begin check event
I/AppUp4:CustModeStarterReceiver( 6494): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6494): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 6494): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6494): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6494): handleAsyncCustNotification do not startCustService
I/ActivityManager(  877): Killing 5882:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,I/LgeMiscReceiver( 3270): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3270): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3270): networkInfo.isConnected() = false
W/System.err( 6083): android.os.DeadObjectException
W/System.err( 6083): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6083): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6083): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6083): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6083): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6083): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6083): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6083): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6083): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6083): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6083): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6083): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6083): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6083): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6083): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6083): android.os.DeadObjectException
W/System.err( 6083): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6083): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6083): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6083): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6083): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6083): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6083): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6083): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6083): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6083): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6083): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6083): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6083): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6083): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6083): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,W/libprocessgroup(  877): failed to open /acct/uid_10089/pid_5882/cgroup.procs: No such file or directory
,W/ActivityManager(  877): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  877): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6521 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  877): Killing 6170:com.android.calendar/u0a13 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  877): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6544 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup(  877): failed to open /acct/uid_10013/pid_6170/cgroup.procs: No such file or directory
,I/ActivityManager(  877): Killing 5843:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 6521): Register our PhoneStateListener
,W/libprocessgroup(  877): failed to open /acct/uid_10061/pid_5843/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6544): Quickset Services start...
,I/UEI.SmartControl( 6544): Manufacture = LGE
D/UEI.SmartControl( 6544): File observer start...
E/UEI.SmartControl( 6544): IR Port is disabled: false
D/UEI.SmartControl( 6544): Starting file observer...
D/UEI.SmartControl( 6544): Extracting JNI libs...
D/UEI.SmartControl( 6544): --- this system supports 32-bit or 64-bit only
D/MobileConnectivityChangeReceiver( 6521): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6521): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  877): Killing 6083:com.lge.qremote/u0a106 (adj 15): empty #11
D/PhoneMonitor( 6521): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6521): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6521): [parse] Load xml
V/TelephonyAutoProfiling( 6521): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6521): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6521): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/UEI.SmartControl( 6544): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6544): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6544): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6544): --- Selecting new region: 2
I/UEI.SmartControl( 6544): -- Running on KitKat(19) and above! JNI will be used.
,W/libprocessgroup(  877): failed to open /acct/uid_10106/pid_6083/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6544): Platform has CIR...
D/UEI.SmartControl( 6544): NO CIR support, need to check package...
V/DownloadManager( 3216): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
I/UEI.SmartControl( 6544): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 6544): QS Service created
V/DownloadManager( 3216): DownloadService onCreate
I/CheckinService( 5645): Checkin interval check for package: unspecified last checkin: 1454986251996 min interval config: 0 actual interval: 21079
I/DownloadManager( 3216): in removeSpuriousFiles
,V/DownloadManager( 3216): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3216): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@30fa829e on behalf of 3216
I/DownloadManager( 3216): in trimDatabase
V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@12a9f17f on behalf of 3216
,E/UEI.SmartControl( 6544): QS start get config
I/ActivityManager(  877): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6573 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3216): DownloadService onStartCommand
I/CheckinService( 5645): Checking schedule, now: 1454986273124 next: 1454986281948
I/CheckinService( 5645): active receiver: disabled
D/UEI.SmartControl( 6544): Loading JNI Libs...
,D/UEI.SmartControl( 6544):  configuring local db...
V/DownloadManager( 3216): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@11882aaa on behalf of 3216
,V/DownloadManager( 3216): DownloadService onDestroy
,I/ActivityManager(  877): Killing 6372:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  877): failed to open /acct/uid_10081/pid_6372/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6544):  ---- Has DB8: true
D/WeatherAncestor( 2692): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:51:13
D/UpdateThreadPoolManager( 2692): 2 : This is isUpdating : false
D/WeatherAncestor( 2692): connectivity changed - connection : true
D/Weather_cast( 2692): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2692): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:51:13
D/WeatherService( 2692): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/UEI.SmartControl( 6544): QS start statue = true Error code = 0
D/UEI.SmartControl( 6544): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 6544): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6544): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6544): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6544): IrrcClient ++ 
D/irrcClient( 6544): getIrrcService ++ 
,D/irrcClient( 6544): getIrrcService -- 
D/irrcClient( 6544): IrrcClient -- 
W/irrc_jni( 6544): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6544): Services init done
I/UEI.SmartControl( 6544): Device manager: loading config....
,D/UEI.SmartControl( 6544): Config is loaded...
I/ActivityManager(  877): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6594 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  877): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2692): 2 : Utils getTopActivity com.lge.launcher2 / true
D/UEI.SmartControl( 6544): QS Service init finished
D/UEI.SmartControl( 6544):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6544): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6544): QS Service version name: 0.1.73
,D/UEI.SmartControl( 6544): QS Service version code: 1073
D/WeatherService( 2692): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2692): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/UEI.SmartControl( 6544): Service requested: Control
D/UEI.SmartControl( 6544): Service.onUnbind: IControl
D/UEI.SmartControl( 6544): Service.onDestroy
D/UEI.SmartControl( 6544): Shutdown IRRCPlayer... 
W/irrc_jni( 6544): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6544): ~IrrcClient ++ 
D/irrcClient( 6544): ~IrrcClient -- 
W/irrc_jni( 6544): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6544): Blaster closed
,D/UEI.SmartControl( 6544): Blaster closed
D/UEI.SmartControl( 6544): Shut down QS...
D/UEI.SmartControl( 6544): Stopped file observer...
I/UEI.SmartControl( 6544): QS lib stop result = true
D/UEI.SmartControl( 6544): QS shutdown complete
D/UEI.SmartControl( 6544): QS Service created
E/UEI.SmartControl( 6544): QS start get config
,W/ResourcesManager( 6594): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6544):  configuring local db...
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 6544):  ---- Has DB8: true
,D/UEI.SmartControl( 6544): QS start statue = true Error code = 0
D/UEI.SmartControl( 6544): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6544): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6544): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6544): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6544): IrrcClient ++ 
D/irrcClient( 6544): getIrrcService ++ 
D/irrcClient( 6544): getIrrcService -- 
D/irrcClient( 6544): IrrcClient -- 
W/irrc_jni( 6544): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6544): Services init done
I/UEI.SmartControl( 6544): Device manager: loading config....
D/UEI.SmartControl( 6544): QS Service init finished
D/UEI.SmartControl( 6544): QS Service version name: 0.1.73
D/UEI.SmartControl( 6544): QS Service version code: 1073
D/UEI.SmartControl( 6544): Service requested: Control
D/UEI.SmartControl( 6544): Config is loaded...
D/UEI.SmartControl( 6544):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6544): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6544): Request IControl service: devices are loaded...
E/ActivityThread( 6544): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@306fe3c1 that was originally bound here
E/ActivityThread( 6544): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@306fe3c1 that was originally bound here
E/ActivityThread( 6544): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6544): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6544): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6544): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6544): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6544): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6544): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6544): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6544): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6544): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6544): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6544): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6544): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6544): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6544): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6544): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6544): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6544): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6544): Internal service binding...
I/Babel_SMS( 6594): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6594): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6594): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6594): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6594): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6594): MmsConfig.loadFromResources
E/Babel_SMS( 6594): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6594): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6594): CheckpointMarkThreadRoots callback created = 0xb042d540
,D/SensorManager( 6594): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6594): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6594): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6594): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6594): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6594): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6594): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6594): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6594): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6594): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6594): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6594): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6594): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6594): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6594): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6594): found sensor: Motion Accel, handle=46
,I/art     ( 6594): CheckpointMarkThreadRoots callback created = 0xb042d530
W/Settings( 6594): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6594): startup - clean
I/Babel   ( 6594): deleted: false for 0
,I/ActivityManager(  877): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6624 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  877): Killing 6304:com.google.android.gms:car/u0a6 (adj 15): empty #11
W/libprocessgroup(  877): failed to open /acct/uid_10006/pid_6304/cgroup.procs: No such file or directory
,W/ActivityManager(  877): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
W/AudioCapabilities( 6594): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6594): Unsupported mime audio/adpcm
W/AudioCapabilities( 6594): Unsupported mime audio/g726
W/AudioCapabilities( 6594): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6594): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6594): Unsupported mime video/mjpg
,W/VideoCapabilities( 6594): Unsupported mime video/theora
,W/AudioCapabilities( 6594): Unsupported mime audio/evrc
,W/AudioCapabilities( 6594): Unsupported mime audio/qcelp
W/VideoCapabilities( 6594): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6594): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6594): Unsupported mime audio/qcelp
W/AudioCapabilities( 6594): Unsupported mime audio/evrc
,W/VideoCapabilities( 6594): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6594): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6594): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6594): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6594): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6594): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6594): onServiceConnected
,W/Babel   ( 6594): Attempted to change video mute state without an active call.
I/NotificationManager( 6594): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 6594): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6594): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6594): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6594): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6594): propertyValue:false
I/Babel   ( 6594): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  877): Killing 6010:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  877): failed to open /acct/uid_10036/pid_6010/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6624): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6624): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6624): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6624): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6624): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6624):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6624):   adb logcat -s GAv4
,I/art     (  877): Explicit concurrent mark sweep GC freed 18836(905KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.315ms total 146.352ms
,W/GAv4    ( 6624): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 6624): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6624): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/WebViewFactory( 6624): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6624): Time to load native libraries: 2 ms (timestamps 1220-1222)
I/LibraryLoader( 6624): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6624): Binding Chromium to main looper Looper (main, tid 1) {3d68386f}
,I/LibraryLoader( 6624): Expected native library version number "",actual native library version number ""
,I/chromium( 6624): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6624): Initializing chromium process, singleProcess=true
W/art     ( 6624): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6624): ApplicationContext is null in ApplicationStatus
,W/chromium( 6624): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6624): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6624): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6624): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6624): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6624): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6624): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6624): Remote Branch: 
I/Adreno-EGL( 6624): Local Patches: 
I/Adreno-EGL( 6624): Reconstruct Branch: 
V/AudioPolicyService(  278): registerClient() client 0xb3846ea0, uid 10079
,W/AudioManagerAndroid( 6624): Requires BLUETOOTH permission
I/NSApplication( 6624): Starting up...
,I/ActivityManager(  877): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6695 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  877): Killing 6413:com.lge.email/u0a21 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  877): failed to open /acct/uid_10021/pid_6413/cgroup.procs: No such file or directory
,I/ActivityManager(  877): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6714 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  877): Killing 6460:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  877): failed to open /acct/uid_10014/pid_6460/cgroup.procs: No such file or directory
,W/ResourcesManager( 6714): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/iu.SyncManager( 5645): SYNC; picasa accounts
,D/NetworkLogImpl( 5645): Loaded NetworkSpeedPredictor
,I/iu.Environment( 5645): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  877): Killing 6443:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/iu.UploadsManager( 5645): num queued entries: 0
I/iu.UploadsManager( 5645): num updated entries: 0
I/iu.SyncManager( 5645): NEXT; no task
W/libprocessgroup(  877): failed to open /acct/uid_1000/pid_6443/cgroup.procs: No such file or directory
,I/rmt_storage(  271): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  271): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  271): wakelock acquired: 1, error no: 42
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,I/ActivityManager(  877): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6755 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 306us total 22.232ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 22.027ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 22.977ms
,I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
I/rmt_storage(  271): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  271): 
I/rmt_storage(  271): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/MusicStore( 6755): Database version: 120
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6755): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6755): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6755): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6755): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6755): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6755): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6755): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6755): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2faeb8d6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6755): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6755): GMSCore installation verified
,I/ConfigStore( 6755): Config Database version: 1
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/MediaRouter( 6755): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6755): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6755): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6755): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  877): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6797 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6755): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6755): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  877): Killing 6494:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 6797): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6797): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6797): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
E/UEI.SmartControl( 6544): file observer is disposed!
,W/libprocessgroup(  877): failed to open /acct/uid_10011/pid_6494/cgroup.procs: No such file or directory
I/NotificationManager( 6755): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6797): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6797): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6797): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  877): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6828 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6797): JNI_OnLoad()
I/HubEmail( 6797): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6797): registerNatives()
I/HubEmail( 6797): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6797): registerNativeMethods()
I/HubEmail( 6797): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6797): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  877): Killing 6521:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  877): failed to open /acct/uid_10038/pid_6521/cgroup.procs: No such file or directory
,W/Settings( 6797): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 6828): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6828): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6828): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 6828): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6828): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6828): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6828): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/ActivityManager(  877): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6865 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/LGDMClient( 6828): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 6828): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6828): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6828): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6828): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6828): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 6828): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  877): Killing 6573:com.lge.drmservice/u0a51 (adj 15): empty #11
I/AppUp4:AppBoxCP( 6865): onCreate
,W/AppUp4:DB( 6865):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6865):  setFingerPrint start
I/AppUp4:DB( 6865):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6865):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6865):  SDK version = 0
I/AppUp4:DB( 6865):  beforefinger == newfinger no write in DB
,W/libprocessgroup(  877): failed to open /acct/uid_10051/pid_6573/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6865): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6865): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6865): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 6865): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6865): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6865): onReceive
I/AppUp4:CustModeStarterReceiver( 6865): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 6865): Context : android.app.ReceiverRestrictedContext@1730bb9a
D/AppUp4:CustFacade( 6865): isCustomizationCompleted : false
D/UEI.SmartControl( 6544): Internal timer expired: 2
D/UEI.SmartControl( 6544): Service.onUnbind: IControl
D/UEI.SmartControl( 6544): Service.onDestroy
D/UEI.SmartControl( 6544): Shutdown IRRCPlayer... 
W/irrc_jni( 6544): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6544): ~IrrcClient ++ 
D/irrcClient( 6544): ~IrrcClient -- 
W/irrc_jni( 6544): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6544): Blaster closed
D/UEI.SmartControl( 6544): Blaster closed
D/UEI.SmartControl( 6544): Shut down QS...
I/UEI.SmartControl( 6544): QS lib stop result = true
D/UEI.SmartControl( 6544): QS shutdown complete
D/AppUp4:CustFacade( 6865): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6865): begin check event
I/AppUp4:CustModeStarterReceiver( 6865): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6865): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6865): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6865): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6865): handleAsyncCustNotification do not startCustService
I/ActivityManager(  877): Killing 6544:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  877): failed to open /acct/uid_10089/pid_6544/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3270): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3270): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3270): networkInfo.isConnected() = false
I/ActivityManager(  877): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6893 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6893): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 6893): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 6893): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  877): Killing 6594:com.google.android.talk/u0a61 (adj 15): empty #11
,D/PhoneMonitor( 6893): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6893): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6893): [parse] Load xml
V/TelephonyAutoProfiling( 6893): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6893): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6893): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  877): failed to open /acct/uid_10061/pid_6594/cgroup.procs: No such file or directory
,V/DownloadManager( 3216): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3216): DownloadService onCreate
I/NotificationManager( 3216): com.android.providers.downloads: cancelAll by com.android.providers.downloads
,I/CheckinService( 5645): Checkin interval check for package: unspecified last checkin: 1454986251996 min interval config: 0 actual interval: 27364
I/DownloadManager( 3216): in removeSpuriousFiles
V/DownloadManager( 3216): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@1f3da38 on behalf of 3216
I/DownloadManager( 3216): in trimDatabase
V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@19964776 on behalf of 3216
,I/ActivityManager(  877): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6926 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3216): DownloadService onStartCommand
I/CheckinService( 5645): Checking schedule, now: 1454986279395 next: 1454986281948
I/CheckinService( 5645): active receiver: disabled
V/DownloadManager( 3216): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@1e2861e4 on behalf of 3216
,V/DownloadManager( 3216): DownloadService onDestroy
,I/ActivityManager(  877): Killing 6624:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  877): failed to open /acct/uid_10079/pid_6624/cgroup.procs: No such file or directory
D/WeatherAncestor( 2692): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:51:19
D/UpdateThreadPoolManager( 2692): 2 : This is isUpdating : false
D/WeatherAncestor( 2692): connectivity changed - connection : true
D/Weather_cast( 2692): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2692): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:51:19
,D/WeatherService( 2692): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  877): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6949 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  877): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2692): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2692): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2692): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/CheckinService( 5645): Done disabling old GoogleServicesFramework version
,W/ResourcesManager( 6949): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6949): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6949): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6949): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6949): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6949): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6949): MmsConfig.loadFromResources
E/Babel_SMS( 6949): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6949): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6949): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 6949): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6949): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6949): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6949): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6949): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6949): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6949): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6949): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6949): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6949): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6949): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6949): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6949): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6949): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6949): found sensor: Motion Accel, handle=46
W/Settings( 6949): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6949): startup - clean
I/art     ( 6949): CheckpointMarkThreadRoots callback created = 0xaaf3e550
I/Babel   ( 6949): deleted: false for 0
,I/art     ( 6949): CheckpointMarkThreadRoots callback created = 0xaaf3e520
,I/ActivityManager(  877): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6988 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 6949): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6949): Unsupported mime audio/adpcm
W/AudioCapabilities( 6949): Unsupported mime audio/g726
W/AudioCapabilities( 6949): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6949): Unsupported mime audio/wma-voice
I/jxcore-log( 5574): Test app app.js loaded
I/jxcore-log( 5574): 
W/VideoCapabilities( 6949): Unsupported mime video/mjpg
W/VideoCapabilities( 6949): Unsupported mime video/theora
,W/AudioCapabilities( 6949): Unsupported mime audio/evrc
W/AudioCapabilities( 6949): Unsupported mime audio/qcelp
W/VideoCapabilities( 6949): Unrecognized profile 2130706433 for video/avc
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16fdd87f added. We now have 1 listener(s)
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
,W/AudioCapabilities( 6949): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6949): Unsupported mime audio/qcelp
W/AudioCapabilities( 6949): Unsupported mime audio/evrc
I/jxcore-log( 5574): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5574): 
,W/VideoCapabilities( 6949): Unsupported mime video/mp4v-esdp
,I/chromium( 5574): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/VideoCapabilities( 6949): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6949): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6949): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6949): Unrecognized profile 2130706433 for video/avc
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6988): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
W/VideoCapabilities( 6949): Unrecognized profile 2130706433 for video/avc
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6988): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/vclib   ( 6949): onServiceConnected
W/Babel   ( 6949): Attempted to change video mute state without an active call.
,I/GAv4    ( 6988): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6988):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6988):   adb logcat -s GAv4
D/libc-netbsd( 6949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager( 6949): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 6949): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6949): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
,D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
I/System.out( 6949): propertyValue:false
W/ContextImpl( 6988): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6988): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 6988): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/Babel   ( 6949): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  877): Killing 6695:com.android.chrome/u0a48 (adj 15): empty #11
W/GAv4    ( 6988): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6988): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/libprocessgroup(  877): failed to open /acct/uid_10048/pid_6695/cgroup.procs: No such file or directory
,I/art     (  877): Explicit concurrent mark sweep GC freed 19381(936KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.132ms total 139.807ms
,I/WebViewFactory( 6988): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6988): Time to load native libraries: 2 ms (timestamps 6941-6943)
I/LibraryLoader( 6988): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6988): Binding Chromium to main looper Looper (main, tid 1) {3d68386f}
I/LibraryLoader( 6988): Expected native library version number "",actual native library version number ""
I/chromium( 6988): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6988): Initializing chromium process, singleProcess=true
,W/art     ( 6988): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6988): ApplicationContext is null in ApplicationStatus
W/chromium( 6988): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6988): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6988): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 6988): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6988): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6988): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6988): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6988): Remote Branch: 
I/Adreno-EGL( 6988): Local Patches: 
I/Adreno-EGL( 6988): Reconstruct Branch: 
V/AudioPolicyService(  278): registerClient() client 0xb4027080, uid 10079
,W/AudioManagerAndroid( 6988): Requires BLUETOOTH permission
I/NSApplication( 6988): Starting up...
,I/ActivityManager(  877): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7062 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  877): Killing 6714:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  877): failed to open /acct/uid_10086/pid_6714/cgroup.procs: No such file or directory
,I/ActivityManager(  877): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7081 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  877): Killing 6755:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  877): failed to open /acct/uid_10081/pid_6755/cgroup.procs: No such file or directory
,W/ResourcesManager( 7081): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  877): Killing 6797:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  877): failed to open /acct/uid_10021/pid_6797/cgroup.procs: No such file or directory
,I/ActivityManager(  877): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7105 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7105): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 7105): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1397fb90
,D/CalendarProvider2( 7105): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 7105): Created com.android.providers.calendar.CalendarAlarmManager@1d320845(com.android.providers.calendar.CalendarProvider2@1397fb90)
D/CalendarProviderBroadcastReceiver( 7105): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 7105): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 7105): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 7105): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 7105): [getOrCreateCalendarAlarmManager]
,I/ActivityManager(  877): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7124 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/art     (  310): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 307us total 24.911ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.826ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.684ms
D/CalendarProvider2( 7105): [IntentService] Release Lock
D/CalendarProvider2( 7105): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  877): Killing 6828:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/ResourcesManager( 7124): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/libprocessgroup(  877): failed to open /acct/uid_1000/pid_6828/cgroup.procs: No such file or directory
,D/BluetoothManagerService(  877): Message: 20
D/BluetoothManagerService(  877): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c25ea6b:true
,D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
,I/ActivityManager(  877): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7151 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/LGMDMManager( 7124): Create singleton instance
,D/UEI.SmartControl( 7151): Quickset Services start...
,I/UEI.SmartControl( 7151): Manufacture = LGE
D/UEI.SmartControl( 7151): File observer start...
E/UEI.SmartControl( 7151): IR Port is disabled: false
D/UEI.SmartControl( 7151): Starting file observer...
D/UEI.SmartControl( 7151): Extracting JNI libs...
D/UEI.SmartControl( 7151): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7124): getMode name:com.lge.qremote
,I/AudioManager( 7124): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7151): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 7151): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7151): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/ActivityManager(  877): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7174 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UEI.SmartControl( 7151): --- Selecting new region: 2
I/UEI.SmartControl( 7151): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7151): Platform has CIR...
D/UEI.SmartControl( 7151): NO CIR support, need to check package...
I/UEI.SmartControl( 7151): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7151): QS Service created
,E/UEI.SmartControl( 7151): QS start get config
,D/UEI.SmartControl( 7151): Loading JNI Libs...
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
D/UEI.SmartControl( 7151):  configuring local db...
W/ActivityManager(  877): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7174): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 7151):  ---- Has DB8: true
W/GAV2    ( 7174): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/UEI.SmartControl( 7151): QS start statue = true Error code = 0
D/UEI.SmartControl( 7151): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7151): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7151): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7151): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 7151): IrrcClient ++ 
D/irrcClient( 7151): getIrrcService ++ 
,D/irrcClient( 7151): getIrrcService -- 
D/irrcClient( 7151): IrrcClient -- 
W/irrc_jni( 7151): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7151): Services init done
I/UEI.SmartControl( 7151): Device manager: loading config....
D/UEI.SmartControl( 7151): QS Service init finished
,D/UEI.SmartControl( 7151): QS Service version name: 0.1.73
D/UEI.SmartControl( 7151): QS Service version code: 1073
D/UEI.SmartControl( 7151): Service requested: Control
D/UEI.SmartControl( 7151): Config is loaded...
W/ActivityManager(  877): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 7174): Error finding the version of the Email provider.....
E/Gmail   ( 7174): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7174): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7174): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7174): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7174): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7174): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7174): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7174): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 7174): We do not support migrating this version of the Email provider.
D/UEI.SmartControl( 7151):  ----- QS SDK is ready!!!
I/Gmail   ( 7174): getAccountsCursor
,I/UEI.SmartControl( 7151): Notify AllClients services are ready: 0
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 7151): Request IControl service: devices are loaded...
D/UEI.SmartControl( 7151): Internal service binding...
D/UEI.SmartControl( 7151): -----IControl: 11
D/UEI.SmartControl( 7151): Caller: com.lge.qremote
,D/UEI.SmartControl( 7151): ------------ IControl registerCallback...
I/UEI.SmartControl( 7151): Registering callback...
D/UEI.SmartControl( 7151): -----IControl: 19
W/ActivityManager(  877): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/UEI.SmartControl( 7151): Caller: com.lge.qremote
I/UEI.SmartControl( 7151): Registering Services Ready callback...
I/UEI.SmartControl( 7151): Notify client services are ready...
D/UEI.SmartControl( 7151): -----IControl: 8
D/UEI.SmartControl( 7151): Caller: com.lge.qremote
I/Gmail   ( 7174): Observing account changes for notifications
I/ActivityManager(  877): Killing 6893:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/ActivityManager(  877): Killing 6865:com.lge.appbox.client/u0a11 (adj 15): empty #12
,I/ActivityManager(  877): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7219 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  877): Killing 6926:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  877): failed to open /acct/uid_10011/pid_6865/cgroup.procs: No such file or directory
,W/ActivityManager(  877): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/libprocessgroup(  877): failed to open /acct/uid_10038/pid_6893/cgroup.procs: No such file or directory
W/libprocessgroup(  877): failed to open /acct/uid_10051/pid_6926/cgroup.procs: No such file or directory
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/MusicStore( 7219): Database version: 120
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7219): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/Gmail   ( 7174): notifyAccountChanged
I/Gmail   ( 7174): getAccountsCursor
I/Gmail   ( 7174): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 7174): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7174): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7174): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7174): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7219): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7219): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 7219): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7219): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 7219): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 7219): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7219): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2faeb8d6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7219): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7219): GMSCore installation verified
I/ConfigStore( 7219): Config Database version: 1
,I/MediaRouter( 7219): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7219): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7219): type=WIFI subType= reason=null isConnected=true
,I/art     (  877): Explicit concurrent mark sweep GC freed 14663(737KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.180ms total 135.526ms
,I/NetworkMonitor( 7219): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  877): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7258 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 7219): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 7219): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  877): Killing 6988:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/ResourcesManager( 7258): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7258): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 7258): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  877): failed to open /acct/uid_10079/pid_6988/cgroup.procs: No such file or directory
,I/LGEmail ( 7258): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/NotificationManager( 7219): com.google.android.music: cancel(1061) by com.google.android.music
D/LGEmail ( 7258): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7258): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  877): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7286 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7258): JNI_OnLoad()
I/HubEmail( 7258): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7258): registerNatives()
I/HubEmail( 7258): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7258): registerNativeMethods()
I/HubEmail( 7258): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 7258): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  877): Killing 7062:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  877): failed to open /acct/uid_10048/pid_7062/cgroup.procs: No such file or directory
W/Settings( 7258): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/LGDMClient( 7286): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7286): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7286): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7286): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 7286): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 7286): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  877): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7313 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7286): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7286): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 7286): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7286): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 7286): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7286): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  877): Killing 7081:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  877): failed to open /acct/uid_10086/pid_7081/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 7313): onCreate
W/AppUp4:DB( 7313):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7313):  setFingerPrint start
I/AppUp4:DB( 7313):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7313):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7313):  SDK version = 0
I/AppUp4:DB( 7313):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7313): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7313): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7313): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7313): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7313): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7313): onReceive
I/AppUp4:CustModeStarterReceiver( 7313): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7313): Context : android.app.ReceiverRestrictedContext@1730bb9a
D/AppUp4:CustFacade( 7313): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7313): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7313): begin check event
I/AppUp4:CustModeStarterReceiver( 7313): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7313): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7313): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7313): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7313): handleAsyncCustNotification do not startCustService
I/ActivityManager(  877): Killing 7105:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  877): failed to open /acct/uid_10014/pid_7105/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3270): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3270): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3270): networkInfo.isConnected() = true
,D/PhoneState( 3270): setPdpRejectCasuse : false
I/ActivityManager(  877): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7332 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7332): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7332): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7332): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  877): Killing 7151:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
D/PhoneMonitor( 7332): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7332): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7332): [parse] Load xml
V/TelephonyAutoProfiling( 7332): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7332): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,W/System.err( 7124): android.os.DeadObjectException
D/PhoneMonitor( 7332): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/System.err( 7124): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7124): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7124): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7124): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7124): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7124): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7124): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7124): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7124): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7124): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7124): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7124): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7124): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7124): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7124): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7124): android.os.DeadObjectException
W/System.err( 7124): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7124): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7124): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7124): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7124): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7124): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7124): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7124): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7124): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7124): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7124): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7124): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7124): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7124): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7124): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,W/libprocessgroup(  877): failed to open /acct/uid_10089/pid_7151/cgroup.procs: No such file or directory
W/ActivityManager(  877): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
V/DownloadManager( 3216): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3216): DownloadService onCreate
I/DownloadManager( 3216): in removeSpuriousFiles
,I/NotificationManager( 3216): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3216): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@37976502 on behalf of 3216
I/DownloadManager( 3216): in trimDatabase
V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@22fbb850 on behalf of 3216
I/ActivityManager(  877): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7354 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3216): DownloadService onStartCommand
V/DownloadManager( 3216): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@1c9acf4e on behalf of 3216
,I/CheckinService( 5645): Checkin interval check for package: unspecified last checkin: 1454986251996 min interval config: 0 actual interval: 32598
I/ActivityManager(  877): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7371 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/CheckinService( 5645): Checking schedule, now: 1454986284635 next: 1454986281948
I/CheckinService( 5645): active receiver: enabled
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/DownloadManager( 3216): DownloadService onDestroy
,I/CheckinService( 5645): Preparing to send checkin request
,D/UEI.SmartControl( 7371): Quickset Services start...
I/UEI.SmartControl( 7371): Manufacture = LGE
,D/UEI.SmartControl( 7371): File observer start...
E/UEI.SmartControl( 7371): IR Port is disabled: false
D/UEI.SmartControl( 7371): Starting file observer...
D/UEI.SmartControl( 7371): Extracting JNI libs...
D/WeatherAncestor( 2692): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:51:24
D/UEI.SmartControl( 7371): --- this system supports 32-bit or 64-bit only
D/UpdateThreadPoolManager( 2692): 2 : This is isUpdating : false
D/WeatherAncestor( 2692): connectivity changed - connection : true
D/Weather_cast( 2692): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2692): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:51:24
D/WeatherService( 2692): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/EventLogService( 5645): Accumulating logs since 1454986243666
W/ActivityManager(  877): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2692): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2692): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2692): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/UEI.SmartControl( 7371): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,I/ActivityManager(  877): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7401 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UEI.SmartControl( 7371): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7371): --- Extracting JNI libs: libqs_armeabi-v7a.zip
V/AlarmManager(  877): RTC_WAKEUP set : Alarm{25cf093a type 0 when 1454986281948 com.google.android.gms} when 1454986281948
I/UEI.SmartControl( 7371): --- Selecting new region: 2
I/UEI.SmartControl( 7371): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7371): Platform has CIR...
I/ActivityManager(  877): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7407 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/AlarmManager(  877): RTC_WAKEUP set : Alarm{32147f06 type 0 when 1454986284778 com.android.vending} when 1454986284778
D/UEI.SmartControl( 7371): NO CIR support, need to check package...
I/UEI.SmartControl( 7371): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7371): QS Service created
I/art     (  310): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 22.592ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 298us total 21.383ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 371us total 22.509ms
,E/UEI.SmartControl( 7371): QS start get config
,D/UEI.SmartControl( 7371): Loading JNI Libs...
D/UEI.SmartControl( 7371):  configuring local db...
,D/Finsky  ( 7407): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/CheckinRequestBuilder( 5645): Checkin reason type: 8 attempt count: 1
,I/GAv4    ( 7401): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7401):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7401):   adb logcat -s GAv4
,E/ActivityThread( 5645): Failed to find provider info for com.google.android.wearable.settings
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7401): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/GAv4    ( 7401): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/ContextImpl( 7401): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/art     ( 5531): Explicit concurrent mark sweep GC freed 2815(109KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 398us total 46.401ms
E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7401): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  248): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  248): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  248): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7401): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 7401): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7401): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,D/UEI.SmartControl( 7371):  ---- Has DB8: true
,D/UEI.SmartControl( 7371): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7371): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7371): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7371): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7371): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7371): IrrcClient ++ 
D/irrcClient( 7371): getIrrcService ++ 
,D/irrcClient( 7371): getIrrcService -- 
D/irrcClient( 7371): IrrcClient -- 
W/irrc_jni( 7371): IRRCPlayer_nativeInit -- 
D/Finsky  ( 7407): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
D/UEI.SmartControl( 7371): Services init done
I/UEI.SmartControl( 7371): Device manager: loading config....
D/UEI.SmartControl( 7371): QS Service init finished
,D/UEI.SmartControl( 7371): QS Service version name: 0.1.73
D/UEI.SmartControl( 7371): QS Service version code: 1073
D/UEI.SmartControl( 7371): Config is loaded...
D/UEI.SmartControl( 7371): Service requested: Control
W/Settings( 7407): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/UEI.SmartControl( 7371): -----IControl: 11
W/Settings( 7407): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
D/UEI.SmartControl( 7371): Internal service binding...
D/UEI.SmartControl( 7371): Caller: com.lge.qremote
,D/UEI.SmartControl( 7371): ------------ IControl registerCallback...
I/UEI.SmartControl( 7371): Registering callback...
I/NotificationManager( 7407): com.android.vending: cancel(-1050172287) by com.android.vending
D/UEI.SmartControl( 7371): -----IControl: 19
D/UEI.SmartControl( 7371): Caller: com.lge.qremote
I/UEI.SmartControl( 7371): Registering Services Ready callback...
I/UEI.SmartControl( 7371): Notify client services are ready...
D/UEI.SmartControl( 7371): -----IControl: 8
D/UEI.SmartControl( 7371): Caller: com.lge.qremote
,D/UEI.SmartControl( 7371):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7371): Notify AllClients services are ready: 0
,V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@3b6c097c on behalf of 7407
,D/Ads     ( 7407): Skipping gmscore version check
D/Finsky  ( 7407): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7407): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  877): Killing 7124:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  877): failed to open /acct/uid_10106/pid_7124/cgroup.procs: No such file or directory
,D/Finsky  ( 7407): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 7407): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/WebViewFactory( 7401): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7401): Time to load native libraries: 2 ms (timestamps 1532-1534)
,I/LibraryLoader( 7401): Expected native library version number "",actual native library version number ""
I/ActivityManager(  877): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7491 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
V/WebViewChromiumFactoryProvider( 7401): Binding Chromium to main looper Looper (main, tid 1) {3d68386f}
I/LibraryLoader( 7401): Expected native library version number "",actual native library version number ""
I/chromium( 7401): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/BrowserStartupController( 7401): Initializing chromium process, singleProcess=true
W/art     ( 7401): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7401): ApplicationContext is null in ApplicationStatus
,W/chromium( 7401): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 7401): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7401): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 7401): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7401): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7401): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7401): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7401): Remote Branch: 
I/Adreno-EGL( 7401): Local Patches: 
I/Adreno-EGL( 7401): Reconstruct Branch: 
W/ResourcesManager( 7491): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7491): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/Finsky  ( 7407): [955] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 7407): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
V/AudioPolicyService(  278): registerClient() client 0xb4027060, uid 10079
,I/MultiDex( 7491): VM with version 2.1.0 has multidex support
W/AudioManagerAndroid( 7401): Requires BLUETOOTH permission
I/MultiDex( 7491): install
I/MultiDex( 7491): VM has multidex support, MultiDex support library is disabled.
I/NSApplication( 7401): Starting up...
,V/JNIHelp ( 7491): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  877): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7527 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  877): Killing 7174:com.google.android.gm/u0a53 (adj 15): empty #11
W/ActivityThread( 7491): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7491): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@12a9f17f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7491): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  877): failed to open /acct/uid_10053/pid_7174/cgroup.procs: No such file or directory
,I/NotificationManager( 7491): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7491): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 7491): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 7491): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  877): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7547 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  877): Killing 7219:com.google.android.music:main/u0a81 (adj 15): empty #11
,D/NativeLibraryUtils( 7491): Install completed successfully. count=14 extracted=0
,W/libprocessgroup(  877): failed to open /acct/uid_10081/pid_7219/cgroup.procs: No such file or directory
,I/art     (  877): Explicit concurrent mark sweep GC freed 19663(923KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 11.172ms total 160.458ms
,I/ActivityManager(  877): Killing 7258:com.lge.email/u0a21 (adj 15): empty #11
W/ResourcesManager( 7547): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  877): failed to open /acct/uid_10021/pid_7258/cgroup.procs: No such file or directory
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): CdmEngine::OpenSession
I/WVCdm   (  278): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  278): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  278): Properties::GetOEMCryptoPath: null. applies level3
,W/WVCdm   (  278): L1 library not specified. Falling Back to L3
I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
D/WVCdm   (  278): PrepareKeyRequest: nonce=452148686
I/ActivityManager(  877): Killing 7286:com.lge.lgdmsclient/1000 (adj 15): empty #11
,W/libprocessgroup(  877): failed to open /acct/uid_1000/pid_7286/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  877): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7572 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/WVCdm   (  278): CdmEngine::OpenSession
,W/ActivityManager(  877): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 7572): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 7572): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  877): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/WearableService( 1731): callingUid 10006, callindPid: 1731
E/Gmail   ( 7572): Error finding the version of the Email provider.....
E/Gmail   ( 7572): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7572): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7572): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7572): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7572): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7572): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7572): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7572): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/MDM     ( 1731): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/EmailMigration( 7572): We do not support migrating this version of the Email provider.
,D/LocationInitializer( 5645): Restart initialization of location
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/Gmail   ( 7572): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  877): Killing 7313:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  877): failed to open /acct/uid_10011/pid_7313/cgroup.procs: No such file or directory
,W/ActivityManager(  877): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7572): Observing account changes for notifications
,I/ActivityManager(  877): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7621 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
W/ActivityManager(  877): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 7621): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/BluetoothManagerService(  877): Message: 20
D/BluetoothManagerService(  877): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3341be77:true
,D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
I/AudioManager( 7621): getMode name:com.lge.qremote
,I/Gmail   ( 7572): notifyAccountChanged
,I/Gmail   ( 7572): getAccountsCursor
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7572): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 7572): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7572): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/AudioManager( 7621): getMode name:com.lge.qremote
I/Gmail   ( 7572): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/Finsky  ( 7407): [960] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/NotificationManager(  877): android: cancelAsUser(2) by android
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/libc-netbsd( 7407): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7407): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7407): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7407): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
V/LGMDMManager( 7621): Create singleton instance
,I/Gmail   ( 7572): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 7407): propertyValue:false
I/AudioManager( 7621): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7371): -----IControl: 11
D/UEI.SmartControl( 7371): Caller: com.lge.qremote
D/UEI.SmartControl( 7371): ------------ IControl registerCallback...
I/UEI.SmartControl( 7371): Registering callback...
D/UEI.SmartControl( 7371): -----IControl: 19
D/UEI.SmartControl( 7371): Caller: com.lge.qremote
I/UEI.SmartControl( 7371): Registering Services Ready callback...
I/UEI.SmartControl( 7371): Notify client services are ready...
D/UEI.SmartControl( 7371): -----IControl: 8
,D/UEI.SmartControl( 7371): Caller: com.lge.qremote
,I/AudioManager( 7621): getMode name:com.lge.qremote
,I/CheckinService( 5645): Checkin interval check for package: unspecified last checkin: 1454986251996 min interval config: 0 actual interval: 35632
,I/AudioManager( 7621): getMode name:com.lge.qremote
E/MDM     ( 1731): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5645): Restart initialization of location
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
I/AudioManager( 7621): getMode name:com.lge.qremote
,I/AudioManager( 7621): getMode name:com.lge.qremote
W/ContextImpl( 3672): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/AudioManager( 7621): getMode name:com.lge.qremote
,I/AudioManager( 7621): getMode name:com.lge.qremote
,I/AudioManager( 7621): getMode name:com.lge.qremote
,I/AudioManager( 7621): getMode name:com.lge.qremote
I/ActivityManager(  877): Killing 7354:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  877): failed to open /acct/uid_10051/pid_7354/cgroup.procs: No such file or directory
,I/WVCdm   (  278): CdmEngine::CloseSession
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 114485631523; DSPS: 3850190; Offset : -3023996996
I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
D/WVCdm   (  278): PrepareKeyRequest: nonce=3642416219
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/MusicWidget( 2625): mDelayedStopHandler : unbind
,I/MusicBrowser( 2708): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2708): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2708): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2708): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2708): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2708): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2708): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2708): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  877):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3bb2aebbcom.lge.music.MediaPlaybackService$6@3bf38fd8
,D/MusicBrowser( 2708): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2708): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2708): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2708): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2708): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@1f4ef766
,I/MusicBrowser( 2708): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2708): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2708): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2708): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2708): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2708): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2708): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2708): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2708): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2708): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2708): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2708): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2708): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2708): reset
V/MediaPlayer[Native]( 2708): setListener
V/MediaPlayer[Native]( 2708): disconnect
V/MediaPlayer[Native]( 2708): destructor
,V/AudioFlinger(  278): releasing 19 from 2708 for -1
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
V/MediaPlayer[Native]( 2708): disconnect
D/MusicBrowser( 2708): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2708): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2708): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2708): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2708): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2708): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2708): [SmartShareManagerClient] unregisterListener: 362299185
W/SmartShareClient( 2708): [SmartShareManagerClient] unregisterListener invalid listener: 362299185
I/SmartShareClient( 2708): [SmartShareManagerClient] terminate service: 2708/MediaPlaybackService/245973180
E/HomeCloudIF( 2708): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2708): [SmartShareManagerClient] unbindService context:android.app.Application@25fa0616
V/CloudHub( 2708): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2708): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2708): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2708): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2708): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  877): Killing 6949:com.google.android.talk/u0a61 (adj 15): empty #11
I/CloudHub( 2708): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29993
W/libprocessgroup(  877): failed to open /acct/uid_10061/pid_6949/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 7371): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/WVCdm   (  278): CdmEngine::CloseSession
,I/WVCdm   (  278): L3 Terminate.
I/art     ( 7491): CheckpointMarkThreadRoots callback created = 0xb042d8b0
,I/art     ( 7491): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,I/dex2oat ( 7690): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=40 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 7690): dex2oat took 90.419ms (threads: 4)
,I/Adreno-EGL( 7491): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7491): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7491): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7491): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7491): Remote Branch: 
I/Adreno-EGL( 7491): Local Patches: 
I/Adreno-EGL( 7491): Reconstruct Branch: 
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/Adreno-EGL( 7491): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7491): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7491): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7491): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7491): Remote Branch: 
I/Adreno-EGL( 7491): Local Patches: 
I/Adreno-EGL( 7491): Reconstruct Branch: 
,I/Adreno-EGL( 7491): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7491): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7491): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7491): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7491): Remote Branch: 
I/Adreno-EGL( 7491): Local Patches: 
I/Adreno-EGL( 7491): Reconstruct Branch: 
,I/CheckinRequestBuilder( 5645): Classify the device as Phone.
,D/libc-netbsd( 5645): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5645): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5645): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5645): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 5645): propertyValue:false
I/GAV2    ( 7572): Thread[GAThread,5,main]: No campaign data found.
,D/libc-netbsd( 5645): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5645): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/GAv4-SVC( 5645): Google Analytics 8.4.89 is starting up.
D/libc-netbsd( 5645): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5645): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5645): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5645): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 5645): Sending checkin request (9769 bytes)
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/CheckinRequestBuilder( 5645): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5645): Failed to find provider info for com.google.android.wearable.settings
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/art     (  877): Explicit concurrent mark sweep GC freed 17228(780KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.115ms total 162.956ms
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 5645): Classify the device as Phone.
,I/CheckinTask( 5645): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5645): Checking schedule, now: 1454986292865 next: 1455513541858
I/CheckinService( 5645): active receiver: disabled
,I/CheckinService( 5645): Checking schedule, now: 1454986292905 next: 1455513541858
I/CheckinService( 5645): active receiver: disabled
,D/CheckinService( 5645): Recording last checkin time for package unspecified as 1454986292913
I/ActivityManager(  877): Killing 7401:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  877): failed to open /acct/uid_10079/pid_7401/cgroup.procs: No such file or directory
,V/SetupWizard( 7332): Connected to Gservices successfully
I/ActivityManager(  877): Killing 7527:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  877): failed to open /acct/uid_10048/pid_7527/cgroup.procs: No such file or directory
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]QPairHandler( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  877): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  877): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7736 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/administrator(  877): Handling package changes for user 0
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 7736): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationService(  877): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  877): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  877): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  877): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  877): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  877): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1ffc4e34
,W/ResourcesManager(  877): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Babel_SMS( 7736): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7736): MmsConfig.loadMmsSettings
I/Babel_SMS( 7736): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7736): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7736): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7736): MmsConfig.loadFromResources
E/Babel_SMS( 7736): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7736): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
W/ResourceType(  877): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1731): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/SensorManager( 7736): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 7736): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7736): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7736): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7736): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7736): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7736): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7736): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7736): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7736): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7736): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7736): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7736): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7736): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7736): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7736): found sensor: Motion Accel, handle=46
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
,D/LocationProviderProxy(  877): applying state to connected service
I/art     ( 7736): CheckpointMarkThreadRoots callback created = 0xb042d8b0
,W/Settings( 7736): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7736): startup - clean
I/Babel   ( 7736): deleted: false for 0
,I/art     ( 7736): CheckpointMarkThreadRoots callback created = 0xb042d890
W/AudioCapabilities( 7736): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7736): Unsupported mime audio/adpcm
W/AudioCapabilities( 7736): Unsupported mime audio/g726
W/AudioCapabilities( 7736): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7736): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7736): Unsupported mime video/mjpg
W/VideoCapabilities( 7736): Unsupported mime video/theora
W/AudioCapabilities( 7736): Unsupported mime audio/evrc
,W/AudioCapabilities( 7736): Unsupported mime audio/qcelp
W/VideoCapabilities( 7736): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7736): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7736): Unsupported mime audio/qcelp
W/AudioCapabilities( 7736): Unsupported mime audio/evrc
I/ActivityManager(  877): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7774 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/VideoCapabilities( 7736): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7736): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7736): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7736): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7736): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7736): Unrecognized profile 2130706433 for video/avc
,I/AppUp4:AppBoxCP( 7774): onCreate
,W/AppUp4:DB( 7774):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7774):  setFingerPrint start
I/AppUp4:DB( 7774):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7774):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7774):  SDK version = 0
I/AppUp4:DB( 7774):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7774): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 7774): onReceive
I/AppUp4:CustModeStarterReceiver( 7774): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 7774): Context : android.app.ReceiverRestrictedContext@3386c4af
D/AppUp4:CustFacade( 7774): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7774): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7774): begin check event
I/AppUp4:CustModeStarterReceiver( 7774): Event For Nothing, skip.
I/ActivityManager(  877): Killing 7547:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/art     ( 7736): Suspending all threads took: 30.200ms
,W/libprocessgroup(  877): failed to open /acct/uid_10086/pid_7547/cgroup.procs: No such file or directory
,I/ActivityManager(  877): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7795 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/vclib   ( 7736): onServiceConnected
W/Babel   ( 7736): Attempted to change video mute state without an active call.
I/NotificationManager( 7736): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7736): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7736): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 7795): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 7795): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 7795): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
V/JNIHelp ( 7736): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 7736): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7736): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 7736): com.google.android.talk: cancel(10436) by com.google.android.talk
I/AppConfig( 7795): Total System Memory = 906309632
,I/GalleryUtils( 7795): Application Heap = 96 MB
I/AppConfig( 7795): App Tier : NOT_DEF
D/SystemHelper( 7795): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  877): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7817 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  877): Killing 7407:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  877): failed to open /acct/uid_10036/pid_7407/cgroup.procs: No such file or directory
,W/ResourcesManager( 7817): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7817): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7817): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7817): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 7817): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 7817): BUILD Country: EU
I/SystemConfig( 7817): BUILD Operator: OPEN
,I/ActivityManager(  877): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7839 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  877): Killing 7572:com.google.android.gm/u0a53 (adj 15): empty #11
,W/libprocessgroup(  877): failed to open /acct/uid_10053/pid_7572/cgroup.procs: No such file or directory
,I/SystemConfig( 7817): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 7817): existFile = false
I/SystemConfig( 7817): canReadFile = false
I/SystemConfig( 7817): systemFeature RCS result false
D/SystemConfig( 7817): refreshRcsSupport() :false
I/LockScreenSettings( 7839): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7839): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7839): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7839): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7839): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7839): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  877): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7859 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  877): Killing 2708:com.lge.music/u0a28 (adj 15): empty #11
,I/art     (  310): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 22.873ms
,V/AudioFlinger(  278): 2708 died, releasing its sessions
V/AudioFlinger(  278):  pid 1749 @ 0
V/AudioFlinger(  278):  pid 3270 @ 1
V/AudioFlinger(  278):  pid 3270 @ 2
I/art     (  310): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 24.035ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 22.699ms
,W/libprocessgroup(  877): failed to open /acct/uid_10028/pid_2708/cgroup.procs: No such file or directory
,W/ResourcesManager( 7859): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/UpdateIcingCorporaServi( 1936): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  877): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7898 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 1936): UpdateCorporaTask done [took 52 ms] updated apps [took 52 ms] 
I/ActivityManager(  877): Killing 7371:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7621): android.os.DeadObjectException
,W/System.err( 7621): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7621): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7621): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7621): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7621): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7621): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7621): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7621): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7621): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7621): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7621): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7621): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7621): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7621): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7621): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7621): android.os.DeadObjectException
W/System.err( 7621): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7621): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7621): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7621): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7621): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7621): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7621): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7621): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7621): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7621): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7621): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7621): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7621): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7621): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7621): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  877): failed to open /acct/uid_10089/pid_7371/cgroup.procs: No such file or directory
,W/ActivityManager(  877): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  877): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7915 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 7915): Quickset Services start...
,I/UEI.SmartControl( 7915): Manufacture = LGE
D/UEI.SmartControl( 7915): File observer start...
E/UEI.SmartControl( 7915): IR Port is disabled: false
D/UEI.SmartControl( 7915): Starting file observer...
D/UEI.SmartControl( 7915): Extracting JNI libs...
D/UEI.SmartControl( 7915): --- this system supports 32-bit or 64-bit only
D/Finsky  ( 7898): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 7915): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7915): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7915): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7915): --- Selecting new region: 2
,I/UEI.SmartControl( 7915): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7915): Platform has CIR...
D/UEI.SmartControl( 7915): NO CIR support, need to check package...
I/UEI.SmartControl( 7915): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7915): QS Service created
D/Finsky  ( 7898): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7898): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7898): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/UEI.SmartControl( 7915): QS start get config
I/NotificationManager( 7898): com.android.vending: cancel(-1050172287) by com.android.vending
I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,D/UEI.SmartControl( 7915): Loading JNI Libs...
,D/UEI.SmartControl( 7915):  configuring local db...
I/art     ( 5531): Explicit concurrent mark sweep GC freed 3287(136KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 409us total 35.009ms
,V/DownloadManager( 3216): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
D/Finsky  ( 7898): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7898): [1] Libraries$2.run: Finished loading 1 libraries.
,I/ActivityManager(  877): Killing 7621:com.lge.qremote/u0a106 (adj 15): empty #11
D/Ads     ( 7898): Skipping gmscore version check
,V/DownloadManager( 3216): created cursor android.database.sqlite.SQLiteCursor@9cc0205 on behalf of 7898
W/libprocessgroup(  877): failed to open /acct/uid_10106/pid_7621/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 5645): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5645): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 7898): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/Icing   ( 5645): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 7898): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/UEI.SmartControl( 7915):  ---- Has DB8: true
,D/UEI.SmartControl( 7915): QS start statue = true Error code = 0
D/UEI.SmartControl( 7915): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7915): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7915): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7915): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7915): IrrcClient ++ 
D/irrcClient( 7915): getIrrcService ++ 
D/irrcClient( 7915): getIrrcService -- 
D/irrcClient( 7915): IrrcClient -- 
W/irrc_jni( 7915): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7915): Services init done
I/UEI.SmartControl( 7915): Device manager: loading config....
,D/UEI.SmartControl( 7915): QS Service init finished
,D/UEI.SmartControl( 7915): QS Service version name: 0.1.73
,D/UEI.SmartControl( 7915): QS Service version code: 1073
D/UEI.SmartControl( 7915): Service requested: Control
D/UEI.SmartControl( 7915): Config is loaded...
D/UEI.SmartControl( 7915):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7915): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7915): Request IControl service: devices are loaded...
D/UEI.SmartControl( 7915): Service.onUnbind: IControl
,D/UEI.SmartControl( 7915): Service.onDestroy
D/UEI.SmartControl( 7915): Shutdown IRRCPlayer... 
W/irrc_jni( 7915): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7915): ~IrrcClient ++ 
D/irrcClient( 7915): ~IrrcClient -- 
W/irrc_jni( 7915): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7915): Blaster closed
D/UEI.SmartControl( 7915): Blaster closed
,D/UEI.SmartControl( 7915): Shut down QS...
,D/UEI.SmartControl( 7915): Stopped file observer...
I/UEI.SmartControl( 7915): QS lib stop result = true
D/UEI.SmartControl( 7915): QS shutdown complete
D/UEI.SmartControl( 7915): QS Service created
E/UEI.SmartControl( 7915): QS start get config
,D/UEI.SmartControl( 7915):  configuring local db...
,D/UEI.SmartControl( 7915):  ---- Has DB8: true
,D/UEI.SmartControl( 7915): QS start statue = true Error code = 0
D/UEI.SmartControl( 7915): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7915): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7915): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7915): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7915): IrrcClient ++ 
D/irrcClient( 7915): getIrrcService ++ 
D/irrcClient( 7915): getIrrcService -- 
D/irrcClient( 7915): IrrcClient -- 
W/irrc_jni( 7915): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7915): Services init done
I/UEI.SmartControl( 7915): Device manager: loading config....
D/UEI.SmartControl( 7915): QS Service init finished
D/UEI.SmartControl( 7915): QS Service version name: 0.1.73
D/UEI.SmartControl( 7915): QS Service version code: 1073
D/UEI.SmartControl( 7915): Service requested: Control
D/UEI.SmartControl( 7915): Config is loaded...
D/UEI.SmartControl( 7915):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7915): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7915): Request IControl service: devices are loaded...
,E/ActivityThread( 7915): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@306fe3c1 that was originally bound here
E/ActivityThread( 7915): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@306fe3c1 that was originally bound here
E/ActivityThread( 7915): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 7915): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 7915): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 7915): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 7915): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 7915): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 7915): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 7915): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 7915): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 7915): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 7915): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 7915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 7915): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 7915): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 7915): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 7915): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 7915): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 7915): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 7915): Internal service binding...
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/Icing   ( 5645): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 5645): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  877): Killing 7332:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  877): failed to open /acct/uid_10038/pid_7332/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ActivityManager(  877): Killing 7491:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  877): failed to open /acct/uid_10006/pid_7491/cgroup.procs: No such file or directory
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  492): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
,W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
D/WifiController(  877): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,E/UEI.SmartControl( 7915): file observer is disposed!
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/UEI.SmartControl( 7915): Internal timer expired: 2
,D/UEI.SmartControl( 7915): Service.onUnbind: IControl
D/UEI.SmartControl( 7915): Service.onDestroy
W/System.err( 7915): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@37c323f2
W/System.err( 7915): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 7915): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 7915): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 7915): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 7915): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 7915): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 7915): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 7915): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 7915): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 7915): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7915): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7915): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7915): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7915): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7915): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7915): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@37c323f2
D/UEI.SmartControl( 7915): Shutdown IRRCPlayer... 
W/irrc_jni( 7915): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 7915): ~IrrcClient ++ 
D/irrcClient( 7915): ~IrrcClient -- 
W/irrc_jni( 7915): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 7915): Blaster closed
D/UEI.SmartControl( 7915): Blaster closed
D/UEI.SmartControl( 7915): Shut down QS...
I/UEI.SmartControl( 7915): QS lib stop result = true
D/UEI.SmartControl( 7915): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
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
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 134486415474; DSPS: 4505576; Offset : -3024006502
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
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
,V/AlarmManager(  877): ELAPSED_WAKEUP set : Alarm{39ae889 type 2 when 145594 com.google.android.gms} when 145594
,I/art     (  877): Explicit concurrent mark sweep GC freed 35646(1773KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.253ms total 152.221ms
,D/PowerManagerServiceEx(  877): acquireWakeLockInternal: lock=204933320, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=877
D/WeatherService( 2692): 2 : TimeTick Intent has been received, Time(hour:min:sec) 3:52:0
D/WeatherService( 2692): 2 : TimeTick Intent And Screen On
D/WeatherService( 2692): 2 : SDK version : 21
W/ActivityManager(  877): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2692): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2692): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2692): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2692): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2692): 2 : This is isUpdating : false
D/WeatherService( 2692): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2692): 2 : buildUpdate, appWidgetId: 2
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
D/WeatherTheme( 2692): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2692): 2 : Fixed theme : optimus
I/[SystemUI]Clock( 1372): called onTimeUpdated()
I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
,I/[SystemUI]DateView( 1372): called onTimeUpdated()
,I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/WeatherReflect( 2692): 2 : Map key string is -2
D/lim     ( 2692): 2 : time = 03:52
,I/WeatherReflect( 2692): Model Name : LG-D722
D/WeatherTheme( 2692): 2 : Different view - status_min_formatted : 51 != 52
D/WeatherTheme( 2692): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2692): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2692): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2692): currentPackage=com.lge.sizechangable.weather.theme.optimus
,D/Weather4x2_optimus( 2692): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2692): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2692): forecast size is 0
,D/Theme   ( 2692): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2692): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2692): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2692): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2692): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2692): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2692): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2692): url is : null
D/Theme   ( 2692): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2692): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2692): 2 : update view, appWidgetId: 2
D/WeatherService( 2692): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 3:52:0
D/PowerManagerServiceEx(  877): releaseWakeLockInternal: lock=204933320 [*alarm*], flags=0x0
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/VacuumService( 1731): Vacuum at: now=1454986320171 tag=VacuumService
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/art     ( 1731): Explicit concurrent mark sweep GC freed 44685(2MB) AllocSpace objects, 20(320KB) LOS objects, 39% free, 13MB/22MB, paused 1.308ms total 88.321ms
,I/PhenotypeConfigurator( 1731): Scheduling Phenotype for one-off execution 7137 seconds from now (1454986320683)
,D/GetConfigurationSnapshotOperation( 1731): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1731): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1731): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  877): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
,D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1731): propertyValue:false
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  877): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/LocationManagerService(  877): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  877): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  877): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  877): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  877): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/PowerManagerService(  877): ALS enabled for SRE
D/PowerManagerServiceEx(  877): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29145 ms ago)
,D/qdlights(  877): set_light_backlight: 254
,D/qdlights(  877): set_light_backlight: 251
D/qdlights(  877): set_light_backlight: 248
,D/qdlights(  877): set_light_backlight: 244
,D/qdlights(  877): set_light_backlight: 241
,D/qdlights(  877): set_light_backlight: 238
,D/qdlights(  877): set_light_backlight: 234
,D/qdlights(  877): set_light_backlight: 231
,D/qdlights(  877): set_light_backlight: 228
,D/qdlights(  877): set_light_backlight: 224
,D/qdlights(  877): set_light_backlight: 221
,D/qdlights(  877): set_light_backlight: 218
,D/qdlights(  877): set_light_backlight: 214
,D/qdlights(  877): set_light_backlight: 211
,D/qdlights(  877): set_light_backlight: 208
,D/qdlights(  877): set_light_backlight: 204
,D/qdlights(  877): set_light_backlight: 201
,D/qdlights(  877): set_light_backlight: 198
,D/qdlights(  877): set_light_backlight: 194
,D/qdlights(  877): set_light_backlight: 191
,D/qdlights(  877): set_light_backlight: 188
,D/qdlights(  877): set_light_backlight: 184
,D/qdlights(  877): set_light_backlight: 181
,D/qdlights(  877): set_light_backlight: 178
,D/qdlights(  877): set_light_backlight: 174
,D/qdlights(  877): set_light_backlight: 171
,D/qdlights(  877): set_light_backlight: 168
,D/qdlights(  877): set_light_backlight: 164
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  877): set_light_backlight: 161
,D/qdlights(  877): set_light_backlight: 158
,D/qdlights(  877): set_light_backlight: 154
,D/qdlights(  877): set_light_backlight: 151
,D/qdlights(  877): set_light_backlight: 148
,D/qdlights(  877): set_light_backlight: 144
,D/qdlights(  877): set_light_backlight: 141
,D/qdlights(  877): set_light_backlight: 138
,D/qdlights(  877): set_light_backlight: 134
,D/qdlights(  877): set_light_backlight: 131
,D/qdlights(  877): set_light_backlight: 128
,D/qdlights(  877): set_light_backlight: 124
,D/qdlights(  877): set_light_backlight: 121
,D/qdlights(  877): set_light_backlight: 118
,D/qdlights(  877): set_light_backlight: 114
,D/qdlights(  877): set_light_backlight: 111
,D/qdlights(  877): set_light_backlight: 108
,D/qdlights(  877): set_light_backlight: 104
,D/qdlights(  877): set_light_backlight: 101
,D/qdlights(  877): set_light_backlight: 98
,D/qdlights(  877): set_light_backlight: 94
,D/qdlights(  877): set_light_backlight: 91
,D/qdlights(  877): set_light_backlight: 88
,D/qdlights(  877): set_light_backlight: 84
,D/qdlights(  877): set_light_backlight: 81
,D/qdlights(  877): set_light_backlight: 78
,D/qdlights(  877): set_light_backlight: 74
,D/qdlights(  877): set_light_backlight: 71
,D/qdlights(  877): set_light_backlight: 68
,D/qdlights(  877): set_light_backlight: 64
,D/qdlights(  877): set_light_backlight: 61
,D/qdlights(  877): set_light_backlight: 58
,D/qdlights(  877): set_light_backlight: 54
,D/qdlights(  877): set_light_backlight: 51
,D/qdlights(  877): set_light_backlight: 48
,D/qdlights(  877): set_light_backlight: 44
,D/qdlights(  877): set_light_backlight: 41
,D/qdlights(  877): set_light_backlight: 38
,D/qdlights(  877): set_light_backlight: 34
,D/qdlights(  877): set_light_backlight: 31
,D/qdlights(  877): set_light_backlight: 28
,D/qdlights(  877): set_light_backlight: 24
,D/qdlights(  877): set_light_backlight: 21
,D/qdlights(  877): set_light_backlight: 18
,D/qdlights(  877): set_light_backlight: 14
,D/qdlights(  877): set_light_backlight: 11
,D/qdlights(  877): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 154487083487; DSPS: 5160957; Offset : -3023981129
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/PowerManagerService(  877): ALS enabled for SRE
D/PowerManagerServiceEx(  877): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36142 ms ago)
I/PowerManagerService(  877): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  877): ALS enabled for SRE
D/PowerManagerServiceEx(  877): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36156 ms ago)
,W/ContextImpl(  877): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  877): Sleeping (uid 1000)...
D/LPWGController(  877): [updateScreenState] screen on = false
D/LPWGController(  877): disable proximity sensor
,D/LPWGController(  877): enable proximity sensor
I/SensorManager(  877): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@197b31] by com.android.server.power.ProximitySensorListener.enable():120
I/sensors_hal_Ctx(  877): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  877): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
,D/sensors_hal_SAM(  877): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  877): activate: handle is 48, enable
V/sensors_hal_Ctx(  877): activate sensors is 1400000000000
D/sensors_hal_Thresh(  877): enable: handle=48
I/sensors_hal_SAM(  877): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  877): waitForResponse: timeout=1000
V/sensors_hal_SAM(  877): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  877): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  877): enable: Received response: 0
D/PowerManagerServiceEx(  877): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36197 ms ago)
I/Adreno-EGL(  877): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  877): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  877): Build Date: 03/02/15 Mon
I/Adreno-EGL(  877): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  877): Remote Branch: 
I/Adreno-EGL(  877): Local Patches: 
I/Adreno-EGL(  877): Reconstruct Branch: 
,D/PermissionCache(  249): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1316 us)
,I/Sensors (  437): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  877): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,I/sensors_hal_SAM(  877): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  877): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  877): processInd: handle 48, count=1
V/sensors_hal_Thresh(  877): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  877): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  877): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  877): poll: count: 256
I/sensors_hal_Ctx(  877): poll: released wakelock sensor_ind
D/sensors_hal_Util(  877): waitForResponse: timeout=0
D/LPWGController(  877): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  877): current mode = 1  value = 1 1
I/LPWGController(  877): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  877): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/qdlights(  877): set_light_backlight: 0
,I/SensorManager(  877): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  877): activate: handle is 46, disable
V/sensors_hal_Ctx(  877): activate sensors is 1000000000000
D/sensors_hal_LP2(  877): enable: handle=46
D/sensors_hal_LP2(  877): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  877): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  249): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  249): hwc_blank: Blanking display: 0
I/DisplayManagerService(  877): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  877): Display changed displayId=0
,V/sensors_hal_SAM(  877): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  877): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1749): Display #0 changed.
D/qdhwcomposer(  249): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  877): Excessive delay in setPowerMode(): 236ms
I/qdhwcomposer(  249): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  877): Got set_interactive hint
,D/KeyguardViewMediator( 1372): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1331): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1372): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1331): notifyScreenOffLocked
D/SmartCoverViewMediator( 1331): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1372): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1372): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1372): unregisterProximitySensor
,D/WifiServerServiceExt(  877): sendKtScanInterval  mRtspPlay : false
,D/StatusBarWindowView( 1372): onScreenTurnedOff why = 3
V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=on, calling pid 877
,I/WifiServerServiceExt(  877): set CMD_KT_SCAN_INTERVAL
D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=on
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
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
,D/GpsLocationProvider(  877): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:true
I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1803): stopPatternFlashing()
,I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1803): lockStatus = 0
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): updateLightsLocked : turn off led
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/Sensors (  437): sns_pwr.c(301):releasing wakelock
D/LEDHandler( 1803): RESTART MSG
D/SplitWindow(  877): check instance of lgWin Window{166d3d84 u0 SearchPanel}
,D/LNfcService( 1786): action : android.intent.action.SCREEN_ON
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
D/NfcService( 1786): Discovery configuration equal, not updating.
D/Ulp_jni (  877): JNI:system_update. Event-0
D/InputDispatcher(  877): Window went away: Window{2a1a0e9b u0 SearchPanel}
,I/[SystemUI]Clock( 1372): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1372): time changed, timezoneChanged : false
,V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2692): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 3:52:12
D/WeatherService( 2692): 2 : ACTION screen on
,D/WeatherService( 2692): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2692): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2692): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 3:52:12
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  877): ACTION_SCREEN_ON
,D/AppCleanupService( 4131): android.intent.action.SCREEN_ON
,V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=off, calling pid 877
D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=off
V/voice   (  278): voice_set_parameters: enter: screen_state=off
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: exit
V/voice   (  278): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  278): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  278): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  278): adev_set_parameters: exit with code(0)
D/WifiController(  877): CMD_SCREEN_OFF 
D/WifiController(  877): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  877): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:false
,I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1803): clear
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1803): updateLightsLocked : turn on led
E/LEDService( 1803): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1803): Can't handle this request of patternId:0
D/LEDHandler( 1803): RESTART MSG
,D/LNfcService( 1786): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1786): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1876): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2692): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 3:52:12
D/WeatherService( 2692): 2 : ACTION screen off
D/WeatherService( 2692): 2 : TimeTick Receiver Unregister
D/WeatherService( 2692): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 3:52:12
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  877): ACTION_SCREEN_OFF
D/AppCleanupService( 4131): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4131): AppUsageStatsSaveTask
,E/NxpNfcJni( 1786): getReconnectState = 0x0
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1786): getDefaultRoute
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
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/KeyguardViewMediator( 1372): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  877): ELAPSED_WAKEUP set : Alarm{2d59996d type 2 when 162141 com.android.systemui} when 162141
,D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1749): getCallState : 0
,D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1372): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1372): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 174487783583; DSPS: 5816340; Offset : -3023981088
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  877): ELAPSED_WAKEUP set : Alarm{3333b9a2 type 2 when 182237 android} when 182237
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
,I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  877): battery changed pluggedType: 2
V/AlarmManager(  877): ELAPSED_WAKEUP set : Alarm{4e19633 type 2 when 188230 com.google.android.gms} when 188230
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 194488536076; DSPS: 6471725; Offset : -3023991744
,I/ClearcutLoggerApiImpl( 1731): disconnect managed GoogleApiClient
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 214489286537; DSPS: 7127110; Offset : -3024004013
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 234489960643; DSPS: 7782492; Offset : -3024001477
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
,D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  877): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 254490730637; DSPS: 8437877; Offset : -3023994578
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
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 274491434587; DSPS: 9093260; Offset : -3023992193
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5574): TAP version 13
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # multiplex can send data
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 1 String should be length:200
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # enqueue and run in order
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 2 firstPromise setTimeout
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 3 firstPromise result
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 4 firstPromise testValue
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 5 secondPromise setTimeout
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 6 secondPromise result
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 7 secondPromise testValue
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 8 thirdPromise in promise
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 9 thirdPromise result
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 10 thirdPromise testValue
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # basic
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 11 sane
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # another
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 12 sane
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 13 should be equal
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 14 null
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 15 (unnamed assert)
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 16 should be equal
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 17 should not throw
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 18 (unnamed assert)
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 19 (unnamed assert)
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 20 should not throw
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 21 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 22 should be equal
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
I/jxcore-log( 5574): ok 23 should be equal
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # failed to get mobile documents path
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 24 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 25 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 26 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 27 should be equal
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # #init should register the networkChanged event
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 28 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # #startBroadcasting should throw on null device name
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 29 should throw
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 30 should throw
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # #startBroadcasting should throw on non-number port
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 31 should throw
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # #startBroadcasting should throw on NaN port
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 32 should throw
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # #startBroadcasting should throw on negative port
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 33 should throw
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # #startBroadcasting should throw on too large port
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 34 should throw
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 35 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 36 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 37 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 38 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 39 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 40 should be equal
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 41 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 42 should be equal
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 43 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 44 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 45 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 46 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 47 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 48 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 49 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # should call Mobile("Disconnect") without an error
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 50 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 51 should be equal
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): ok 52 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): ok 53 should be equal
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1346104c added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986463738.5574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986463738.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: RUNNING
,I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: OK
I/io.jxcore.node.ConnectionHelper( 5574): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986463738.5574, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5574): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986463738.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: {"pi":"F8:95:C7:87:85:54","pn":"1454986463738.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454986463738.5574","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,I/bt-btif ( 1987): BTA_JvCreateRecordByUser
,D/LGBluetoothServiceAdapter( 1987): [BTUI] createSocketChannel FD=87 mFd=85
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986463738.5574, mode: WIFI
I/bt-btif ( 1987): BTA_JvRfcommStartServer
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Waiting for incoming connections...
I/io.jxcore.node.ConnectionHelper( 5574): start: OK
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 5574): ok 54 Should be able to call startBroadcasting without error
I/jxcore-log( 5574): 
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
I/io.jxcore.node.ConnectionHelper( 5574): stop
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): stopListeningForIncomingConnections: Stopping...
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): shutdown
I/bt-btif ( 1987): BTA_JvDeleteRecord
I/bt-btif ( 1987): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: 1 listener(s) left
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@dcd7fc40 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5574): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  877): P2pEnabledState{ when=-8ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@dcd7fc40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState add service
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5574): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  877): add a new client
I/jxcore-log( 5574): ok 55 Should be able to call stopBroadcasting without error
I/jxcore-log( 5574): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Maximum number of connection attempt retries: 0
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local service added successfully
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29e9e538 added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: STARTED
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
D/LGWifiP2pService(  877): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/LGWifiP2pService(  877): InactiveState{ when=-9ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-9ms what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/wpa_supplicant( 2790): p2p0: CTRL-EVENT-SCAN-STARTED 
,D/LGWifiP2pService(  877): remove client information from framework
D/LGWifiP2pService(  877): InactiveState{ when=-26ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2790): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local services cleared successfully
D/LGWifiP2pService(  877): InactiveState{ when=-27ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-27ms what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5574): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986463908.5574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): initialize: My bluetooth address is F8:95:C7:87:85:54
D/LGWifiP2pService(  877): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): discovery change broadcast false
D/WfdsMonitor( 1803): Event [CTRL-EVENT-SCAN-STARTED ]
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986463908.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: OK
I/io.jxcore.node.ConnectionHelper( 5574): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5574): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986463908.5574, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): bind: Binding a new listener
I/bt-btif ( 1987): BTA_JvCreateRecordByUser
,I/bt-btif ( 1987): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986463908.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: {"pi":"F8:95:C7:87:85:54","pn":"1454986463908.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454986463908.5574","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@662e1b82 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@662e1b82 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState add service
D/LGWifiP2pService(  877): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): start: Starting P2P device discovery...
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: RUNNING_WIFI
I/wpa_supplicant( 2790): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
D/LGWifiP2pService(  877): discovery change broadcast true
D/WfdsMonitor( 1803): Event [P2P: Reject scan trigger since one is already pending]
I/io.jxcore.node.ConnectionHelper( 5574): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986463908.5574, mode: WIFI
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 5574): ok 56 Should be able to call startBroadcasting without error
I/jxcore-log( 5574): 
I/io.jxcore.node.ConnectionHelper( 5574): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): onServerStopped
I/bt-btif ( 1987): BTA_JvDeleteRecord
I/bt-btif ( 1987): BTA_JvRfcommStopServer
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5574): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: RESTARTING
,I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery started successfully
,D/LGWifiP2pService(  877): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopWifiPeerDiscovery: Stopped
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5574): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  877): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local services cleared successfully
I/jxcore-log( 5574): ok 57 Should be able to call stopBroadcasting without error
I/jxcore-log( 5574): 
D/LGWifiP2pService(  877): InactiveState{ when=-3ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2790): P2P-FIND-STOPPED 
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
D/LGWifiP2pService(  877): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): discovery change broadcast false
D/LGWifiP2pService(  877): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5574): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p,.btconnectorlib.DiscoveryManagerSettings( 5574): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16f41ce4 added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986463983.5574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986463983.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: OK
I/io.jxcore.node.ConnectionHelper( 5574): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5574): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1987): BTA_JvCreateRecordByUser
I/bt-btif ( 1987): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986463983.5574, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986463983.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: {"pi":"F8:95:C7:87:85:54","pn":"1454986463983.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454986463983.5574","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  877): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@30c83b3c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@30c83b3c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState add service
D/LGWifiP2pService(  877): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
I/io.jxcore.node.ConnectionHelper( 5574): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986463983.5574, mode: WIFI
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 5574): ok 58 Should be able to call startBroadcasting without error
I/jxcore-log( 5574): 
I/io.jxcore.node.ConnectionHelper( 5574): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): shutdown
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2790): p2p0: P2P: Reject scan trigger since one is already pending
D/LGWifiP2pService(  877): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local service added successfully
D/WfdsMonitor( 1803): Event [P2P: Reject scan trigger since one is already pending]
I/bt-btif ( 1987): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: 1 listener(s) left
I/bt-btif ( 1987): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5574): stopProvideBluetoothMacAddressMode
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): stop: Stopping services
I/wpa_supplicant( 2790): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: STARTED
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: NOT_INITIALIZED
D/LGWifiP2pService(  877): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): release: No more listeners, de-initializing...
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5574): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  877): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local services cleared successfully
D/LGWifiP2pService(  877): InactiveState{ when=-2ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
D/LGWifiP2pService(  877): InactiveState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5574): Service requests cleared successfully
I/jxcore-log( 5574): ok 59 Should be able to call stopBroadcasting without error
I/jxcore-log( 5574): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c482350 added. We now have 5 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464038.5574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986464038.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: OK
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5574): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464038.5574, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): bind: Binding a new listener
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5574): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986464038.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: {"pi":"F8:95:C7:87:85:54","pn":"1454986464038.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454986464038.5574","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
I/bt-btif ( 1987): BTA_JvCreateRecordByUser
I/bt-btif ( 1987): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Waiting for incoming connections...
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2fa9874c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2fa9874c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState add service
D/LGWifiP2pService(  877): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
I/io.jxcore.node.ConnectionHelper( 5574): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464038.5574, mode: WIFI
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2790): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1803): Event [P2P: Reject scan trigger since one is already pending]
I/jxcore-log( 5574): ok 60 Should be able to call startBroadcasting without error
I/jxcore-log( 5574): 
D/LGWifiP2pService(  877): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 5574): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): shutdown
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: 1 listener(s) left
I/bt-btif ( 1987): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/bt-btif ( 1987): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stop: Stopping peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5574): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local service added successfully
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery started successfully
I/wpa_supplicant( 2790): P2P-FIND-STOPPED 
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): onServerStopped
D/LGWifiP2pService(  877): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: NOT_INITIALIZED
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5574): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  877): remove client information from framework
D/LGWifiP2pService(  877): InactiveState{ when=-3ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local services cleared successfully
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5574): Service requests cleared successfully
I/jxcore-log( 5574): ok 61 Should be able to call stopBroadcasting without error
I/jxcore-log( 5574): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3494247c added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464088.5574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986464088.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: OK
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5574): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464088.5574, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5574): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1987): BTA_JvCreateRecordByUser
I/bt-btif ( 1987): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986464088.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: {"pi":"F8:95:C7:87:85:54","pn":"1454986464088.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454986464088.5574","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  877): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@79644002 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@79644002 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState add service
D/LGWifiP2pService(  877): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: RUNNING_WIFI
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
I/io.jxcore.node.ConnectionHelper( 5574): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464088.5574, mode: WIFI
I/wpa_supplicant( 2790): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1803): Event [P2P: Reject scan trigger since one is already pending]
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  877): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: STARTED
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/wpa_supplicant( 2790): P2P-FIND-STOPPED 
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  877): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
I/jxcore-log( 5574): ok 62 Should be able to call startBroadcasting without error
I/jxcore-log( 5574): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): restart: Restarting...
I/io.jxcore.node.ConnectionHelper( 5574): stop
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): onServerStopped
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/bt-btif ( 1987): BTA_JvDeleteRecord
I/bt-btif ( 1987): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5574): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): stop: Stopping services
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5574): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  877): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local services cleared successfully
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5574): ok 63 Should be able to call stopBroadcasting without error
I/jxcore-log( 5574): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
D/LGWifiP2pService(  877): InactiveState{ when=-2ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-2ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5574): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@353d0c68 added. We now have 7 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464141.5574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986464141.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: OK
I/io.jxcore.node.ConnectionHelper( 5574): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5574): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1987): BTA_JvCreateRecordByUser
I/bt-btif ( 1987): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464141.5574, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986464141.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: {"pi":"F8:95:C7:87:85:54","pn":"1454986464141.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454986464141.5574","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@dc7bf296 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@dc7bf296 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState add service
D/LGWifiP2pService(  877): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
I/io.jxcore.node.ConnectionHelper( 5574): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464141.5574, mode: WIFI
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2790): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1803): Event [P2P: Reject scan trigger since one is already pending]
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  877): discovery change broadcast true
I/jxcore-log( 5574): ok 64 Should be able to call startBroadcasting without error
I/jxcore-log( 5574): 
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): restart: Restarting...
I/io.jxcore.node.ConnectionHelper( 5574): stop
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): shutdown
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: 1 listener(s) left
I/bt-btif ( 1987): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local service added successfully
I/bt-btif ( 1987): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5574): stopProvideBluetoothMacAddressMode
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.bluetoo,th.BluetoothServerThread( 5574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): onServerStopped
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): stop: Stopping P2P device discovery...
I/wpa_supplicant( 2790): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): release: No more listeners, de-initializing...
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
D/LGWifiP2pService(  877): InactiveState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5574): clear
D/LGWifiP2pService(  877): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: NOT_STARTED
D/LGWifiP2pService(  877): P2pEnabledState clear service
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  877): remove client information from framework
D/LGWifiP2pService(  877): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local services cleared successfully
D/LGWifiP2pService(  877): discovery change broadcast false
I/jxcore-log( 5574): ok 65 Should be able to call stopBroadcasting without error
I/jxcore-log( 5574): 
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service request
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Maximum number of connection attempt retries: 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5574): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSet,tings( 5574): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@230a8714 added. We now have 8 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464191.5574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986464191.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: OK
I/io.jxcore.node.ConnectionHelper( 5574): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5574): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464191.5574, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): bind: Binding a new listener
I/bt-btif ( 1987): BTA_JvCreateRecordByUser
I/bt-btif ( 1987): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986464191.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: {"pi":"F8:95:C7:87:85:54","pn":"1454986464191.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454986464191.5574","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2636ab4c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@2636ab4c target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState add service
D/LGWifiP2pService(  877): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): start: Starting P2P device discovery...
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: RUNNING_WIFI
I/wpa_supplicant( 2790): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
D/WfdsMonitor( 1803): Event [P2P: Reject scan trigger since one is already pending]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464191.5574, mode: WIFI
D/LGWifiP2pService(  877): discovery change broadcast true
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 5574): start: OK
I/jxcore-log( 5574): ok 66 Should be able to call startBroadcasting without error
I/jxcore-log( 5574): 
I/io.jxcore.node.ConnectionHelper( 5574): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): shutdown
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2790): P2P-FIND-STOPPED 
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
I/bt-btif ( 1987): BTA_JvDeleteRecord
I/bt-btif ( 1987): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: NOT_STARTED
D/LGWifiP2pService(  877): InactiveState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): discovery change broadcast false
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5574): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): stop: Stopping services
D/LGWifiP2pService(  877): InactiveState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  877): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): release: No more listeners, de-initializing...
D/LGWifiP2pService(  877): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: No more listeners, de-initializing...
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5574): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: NOT_STARTED
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service request
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5574): Service requests cleared successfully
I/jxcore-log( 5574): ok 67 Should be able to call stopBroadcasting without error
I/jxcore-log( 5574): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25930080 added. We now have 9 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464247.5574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986464247.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: OK
I/io.jxcore.node.ConnectionHelper( 5574): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464247.5574, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): bind: Binding a new listener
W/BluetoothAdapter( 5574): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/bt-btif ( 1987): BTA_JvCreateRecordByUser
I/bt-btif ( 1987): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986464247.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: {"pi":"F8:95:C7:87:85:54","pn":"1454986464247.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454986464247.5574","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6b4f2448 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6b4f2448 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState add service
D/LGWifiP2pService(  877): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
I/io.jxcore.node.ConnectionHelper( 5574): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464247.5574, mode: WIFI
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2790): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 5574): ok 68 Should be able to call startBroadcasting without error
I/jxcore-log( 5574): 
D/WfdsMonitor( 1803): Event [P2P: Reject scan trigger since one is already pending]
I/io.jxcore.node.ConnectionHelper( 5574): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): stopListeningForIncomingConnections: Stopping...
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): shutdown
D/LGWifiP2pService(  877): discovery change broadcast true
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): onServerStopped
I/bt-btif ( 1987): BTA_JvDeleteRecord
I/bt-btif ( 1987): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5574): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): release: No more listeners, de-initializing...
D/LGWifiP2pService(  877): remove client information from framework
D/LGWifiP2pService(  877): InactiveState{ when=-2ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: No more listeners, de-initializing...
I/wpa_supplicant( 2790): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local services cleared successfully
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5574): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: NOT_STARTED
D/LGWifiP2pService(  877): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): discovery change broadcast false
D/LGWifiP2pService(  877): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5574): ok 69 Should be able to call stopBroadcasting without error
I/jxcore-log( 5574): 
D/LGWifiP2pService(  877): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service request
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5574): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@567a4ac added. We now have 10 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464303.5574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986464303.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: OK
I/io.jxcore.node.ConnectionHelper( 5574): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5574): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1987): BTA_JvCreateRecordByUser
I/bt-btif ( 1987): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464303.5574, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986464303.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: {"pi":"F8:95:C7:87:85:54","pn":"1454986464303.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454986464303.5574","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService(  877): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@686bb296 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@686bb296 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState add service
D/LGWifiP2pService(  877): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464303.5574, mode: WIFI
I/wpa_supplicant( 2790): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1803): Event [P2P: Reject scan trigger since one is already pending]
I/io.jxcore.node.ConnectionHelper( 5574): start: OK
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  877): discovery change broadcast true
I/jxcore-log( 5574): ok 70 Should be able to call startBroadcasting without error
I/jxcore-log( 5574): 
I/io.jxcore.node.ConnectionHelper( 5574): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: 1 listener(s) left
I/bt-btif ( 1987): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: NOT_STARTED
I/bt-btif ( 1987): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopForRestart
D/org.thaliproject.p2,p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5574): stopProvideBluetoothMacAddressMode
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): stop: Stopping services
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2790): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery started successfully
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: NOT_INITIALIZED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopWifiPeerDiscovery: Stopped
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: No more listeners, de-initializing...
D/LGWifiP2pService(  877): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  877): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5574): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  877): InactiveState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service
D/LGWifiP2pService(  877): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local services cleared successfully
I/jxcore-log( 5574): ok 71 Should be able to call stopBroadcasting without error
I/jxcore-log( 5574): 
D/LGWifiP2pService(  877): InactiveState{ when=-2ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): InactiveState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5574): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21005f98 added. We now have 11 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/Blu,etoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464357.5574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986464357.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: OK
I/io.jxcore.node.ConnectionHelper( 5574): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5574): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 1987): BTA_JvCreateRecordByUser
I/bt-btif ( 1987): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464357.5574, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986464357.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: {"pi":"F8:95:C7:87:85:54","pn":"1454986464357.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454986464357.5574","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
,D/LGWifiP2pService(  877): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d4d79044 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@d4d79044 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState add service
D/LGWifiP2pService(  877): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
I/io.jxcore.node.ConnectionHelper( 5574): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464357.5574, mode: WIFI
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2790): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1803): Event [P2P: Reject scan trigger since one is already pending]
I/jxcore-log( 5574): ok 72 Should be able to call startBroadcasting without error
I/jxcore-log( 5574): 
D/LGWifiP2pService(  877): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 5574): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): shutdown
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): onServerStopped
I/bt-btif ( 1987): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: NOT_STARTED
I/bt-btif ( 1987): BTA_JvRfcommStopServer
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5574): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): stop: Stopping services
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): restart: Restarting...
D/org.t,haliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery started successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: No more listeners, de-initializing...
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5574): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: NOT_STARTED
D/LGWifiP2pService(  877): remove client information from framework
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local services cleared successfully
,D/LGWifiP2pService(  877): InactiveState{ when=-2ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2790): P2P-FIND-STOPPED 
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
I/jxcore-log( 5574): ok 73 Should be able to call stopBroadcasting without error
I/jxcore-log( 5574): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
D/LGWifiP2pService(  877): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): discovery change broadcast false
D/LGWifiP2pService(  877): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
D/LGWifiP2pService(  877): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5574): Service requests cleared successfully
I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # ThaliEmitter calls startBroadcasting twice with error
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 4
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@467dd44 added. We now have 12 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
,D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464908.5574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): initialize: My bluetooth address is F8:95:C7:87:85:54
,D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986464908.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: OK
I/io.jxcore.node.ConnectionHelper( 5574): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464908.5574, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986464908.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: {"pi":"F8:95:C7:87:85:54","pn":"1454986464908.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454986464908.5574","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 5574): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1987): BTA_JvCreateRecordByUser
I/bt-btif ( 1987): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Waiting for incoming connections...
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3481fe40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@3481fe40 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState add service
D/LGWifiP2pService(  877): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986464908.5574, mode: WIFI
,I/io.jxcore.node.ConnectionHelper( 5574): start: OK
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local service added successfully
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5574): ok 74 Should be able to call startBroadcasting without error
I/jxcore-log( 5574): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: STARTED
,D/LGWifiP2pService(  877): discovery change broadcast true
I/wpa_supplicant( 2790): p2p0: CTRL-EVENT-SCAN-STARTED 
D/WfdsMonitor( 1803): Event [CTRL-EVENT-SCAN-STARTED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
,D/LGWifiP2pService(  877): InactiveState{ when=-22ms what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2790): P2P-FIND-STOPPED 
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
D/LGWifiP2pService(  877): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: RESTARTING
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5574): ok 75 Cannot call startBroadcasting twice
I/jxcore-log( 5574): 
I/io.jxcore.node.ConnectionHelper( 5574): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): onServerStopped
,I/bt-btif ( 1987): BTA_JvDeleteRecord
I/bt-btif ( 1987): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5574): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): stop: Stopping services
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139298 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service
D/LGWifiP2pService(  877): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: NOT_INITIALIZED
,D/LGWifiP2pService(  877): InactiveState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5574): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5574): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5574): ok 76 Should be able to call stopBroadcasting without error
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
I/jxcore-log( 5574): # ThaliEmitter throws on connection to bad peer
I/jxcore-log( 5574): 
,I/jxcore-log( 5574): # teardown
I/jxcore-log( 5574): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5574): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fa789b0 added. We now have 13 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(812639169)( 1987): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a78379f
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5574): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986465407.5574
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986465407.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): start: OK
I/io.jxcore.node.ConnectionHelper( 5574): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986465407.5574, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
W/BluetoothAdapter( 5574): getBluetoothService() called with no BluetoothManagerCallback
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/bt-btif ( 1987): BTA_JvCreateRecordByUser
I/bt-btif ( 1987): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5574): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1454986465407.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: {"pi":"F8:95:C7:87:85:54","pn":"1454986465407.5574","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1454986465407.5574","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): start: Starting P2P device discovery...
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b43a348a target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@b43a348a target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: true
D/LGWifiP2pService(  877): P2pEnabledState add service
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/LGWifiP2pService(  877): add a new client
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: Peer ID: F8:95:C7:87:85:54, peer name: 1454986465407.5574, mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5574): start: OK
D/BluetoothManagerService(  877): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 5574): ok 77 Should be able to call startBroadcasting without error
I/jxcore-log( 5574): 
I/io.jxcore.node.ConnectionHelper( 5574): connect: Trying to connect to peer with ID foobar
W/io.jxcore.node.ConnectionHelper( 5574): connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): start: OK
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: RUNNING_WIFI
E/io.jxcore.node.ConnectionHelper( 5574): connect: Invalid Bluetooth address: foobar
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: RESTARTING
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5574): ok 78 Should not connect to a bad peer
I/jxcore-log( 5574): 
I/wpa_supplicant( 2790): p2p0: P2P: Reject scan trigger since one is already pending
I/io.jxcore.node.ConnectionHelper( 5574): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): Shutting down...
D/WfdsMonitor( 1803): Event [P2P: Reject scan trigger since one is already pending]
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5574): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5574): stopProvideBluetoothMacAddressMode
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5574): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5574): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5574): stop: Stopping services
I/bt-btif ( 1987): BTA_JvDeleteRecord
I/bt-btif ( 1987): BTA_JvRfcommStopServer
I/io.jxcore.node.ConnectionHelper( 5574): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery started successfully
D/LGWifiP2pService(  877): discovery change broadcast true
D/LGWifiP2pService(  877): InactiveState{ when=-4ms what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2790): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: NOT_INITIALIZED
D/WfdsMonitor( 1803): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5574): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.intern,al.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5574): release: No more listeners, de-initializing...
D/LGWifiP2pService(  877): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): discovery change broadcast false
D/LGWifiP2pService(  877): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5574): clear
D/LGWifiP2pService(  877): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5574): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5574): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  877): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5574): Local services cleared successfully
D/LGWifiP2pService(  877): InactiveState{ when=-2ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5574): ok 79 Should be able to call stopBroadcasting without error
I/jxcore-log( 5574): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): P2P device discovery stopped successfully
D/LGWifiP2pService(  877): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState{ when=-3ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  877): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5574): Service requests cleared successfully
I/jxcore-log( 5574): # setup
I/jxcore-log( 5574): 
,I/Netd    (  274): M: Get netlink event, ifname: p2p0 action: 4
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 294492165099; DSPS: 9748644; Offset : -3023995979
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): Start timer timeout, starting now...
E/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5574): start: Cannot start, because not initialized
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  877): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  877): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  877): battery changed pluggedType: 2
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 314492830301; DSPS: 10404026; Offset : -3024001018
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  877): battery changed pluggedType: 2
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
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 334493507949; DSPS: 11059408; Offset : -3023993975
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/LocationManagerService(  877): remove 2b8d98da
D/LocationManagerService(  877): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  877): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  877): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  877): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  877): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  877): acquireWakeLockInternal: lock=204933320, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=877
,D/PowerManagerServiceEx(  877): releaseWakeLockInternal: lock=204933320 [*alarm*], flags=0x0
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 354494343411; DSPS: 11714795; Offset : -3023984545
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  877): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 374495025122; DSPS: 12370178; Offset : -3024002759
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
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 394495767197; DSPS: 13025562; Offset : -3023993340
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 414496424481; DSPS: 13680943; Offset : -3023976717
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  877): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 434497255515; DSPS: 14336331; Offset : -3024000228
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 454497996497; DSPS: 14991715; Offset : -3023991693
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 474498654615; DSPS: 15647097; Offset : -3024005222
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  877): battery changed pluggedType: 2
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 494499449607; DSPS: 16302483; Offset : -3024003296
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 514500547413; DSPS: 16957879; Offset : -3024004279
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 534501267561; DSPS: 17613262; Offset : -3023986374
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  877): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 554501936251; DSPS: 18268644; Offset : -3023988915
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  877): battery changed pluggedType: 2
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 574502767233; DSPS: 18924031; Offset : -3023981908
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 594503426652; DSPS: 19579413; Offset : -3023993668
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  877): battery changed pluggedType: 2
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 614504172842; DSPS: 20234797; Offset : -3023979535
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 634504825335; DSPS: 20890179; Offset : -3023998845
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 654505517306; DSPS: 21545561; Offset : -3023978338
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  877): battery changed pluggedType: 2
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 674506258549; DSPS: 22200946; Offset : -3023999956
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 694506914739; DSPS: 22856327; Offset : -3023984584
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 714507572804; DSPS: 23511709; Offset : -3023997749
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  877): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 734508390349; DSPS: 24167096; Offset : -3024004153
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 754509059872; DSPS: 24822478; Offset : -3024006459
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 774509798458; DSPS: 25477862; Offset : -3024000295
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  877): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 794510687879; DSPS: 26133251; Offset : -3023995727
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 814511349642; DSPS: 26788633; Offset : -3024005195
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 834512121663; DSPS: 27444018; Offset : -3023996009
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  877): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 854512943949; DSPS: 28099405; Offset : -3023998401
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 874513687848; DSPS: 28754789; Offset : -3023986403
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 894514344663; DSPS: 29410171; Offset : -3024001158
,D/PowerManagerServiceEx(  877): acquireWakeLockInternal: lock=204933320, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=877
,V/AlarmManager(  877): RTC_WAKEUP set : Alarm{32aec6b1 type 0 when 1454986970966 com.google.android.gms} when 1454986970966
V/AlarmManager(  877): RTC_WAKEUP set : Alarm{1f140f17 type 0 when 1454987072193 com.google.android.gms} when 1454987072193
,I/ActivityManager(  877): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8254 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/Icing   ( 5645): Performing maintenance.
,I/EventLogService( 5645): Aggregate from 1454986285114 (log), 1454985170897 (data)
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DigitalAppWidgetProvider( 8254): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8254): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3386c4af
,D/PowerManagerServiceEx(  877): releaseWakeLockInternal: lock=204933320 [*alarm*], flags=0x0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 1731): propertyValue:false
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  877): android: cancelAsUser(2) by android
,I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
,D/libc-netbsd( 5645): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5645): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5645): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5645): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 5645): propertyValue:false
,D/libc-netbsd( 5645): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5645): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/Icing   ( 5645): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 5645): Performing maintenance usage 1829542 budget 729390419 free 99.749% index free 99.972% purge? false target 510573293
,I/ActivityManager(  877): Killing 7774:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  877): failed to open /acct/uid_10011/pid_7774/cgroup.procs: No such file or directory
,I/Icing   ( 5645): Query from com.google.android.gms package restrict com.google.android.gms start 0 num 100
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
V/AlarmManager(  877): RTC_WAKEUP set : Alarm{1783842a type 0 when 1454987083567 com.google.android.googlequicksearchbox} when 1454987083567
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/art     ( 1936): Attempt to remove local handle scope entry from IRT, ignoring
,D/libc-netbsd( 1936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
,E/BandwidthController(  274): [LG DATA] No such appUid: 10042
D/DnsProxyListener(  274): App 10042 tries DNS query. Accept family:2 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
D/libc-netbsd( 1936): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1936): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
,E/BandwidthController(  274): [LG DATA] No such appUid: 10042
D/DnsProxyListener(  274): App 10042 tries DNS query. Accept family:2 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=2
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/HotwordDataManager( 1936): setSpeakerModel(thalitester@gmail.com,null)
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 914515143978; DSPS: 30065557; Offset : -3023994857
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 934515885116; DSPS: 30720941; Offset : -3023986297
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  877): acquireWakeLockInternal: lock=204933320, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=877
,V/AlarmManager(  877): ELAPSED_WAKEUP set : Alarm{e60e101 type 2 when 951519 com.android.bluetooth} when 951519
,I/art     (  877): Explicit concurrent mark sweep GC freed 65787(3MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 3.214ms total 279.219ms
D/PowerManagerServiceEx(  877): releaseWakeLockInternal: lock=204933320 [*alarm*], flags=0x0
,W/bt-smp  ( 1987): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1987): Plain text(LSB ~ MSB) = fc 3b 45 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 1987): Encrypted text(LSB ~ MSB) = 5e ad f8 02 bd 74 0c 87 1f 87 b6 21 9c 65 9a 82 
W/bt-btm  ( 1987): Stopping oneshot timer
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 954516631307; DSPS: 31376326; Offset : -3024005051
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 974517388903; DSPS: 32031710; Offset : -3023979824
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  877): acquireWakeLockInternal: lock=204933320, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=877
,V/AlarmManager(  877): ELAPSED_WAKEUP set : Alarm{2b944ba6 type 2 when 991228 com.google.android.gms} when 991228
,D/PowerManagerServiceEx(  877): releaseWakeLockInternal: lock=204933320 [*alarm*], flags=0x0
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 994518108635; DSPS: 32687094; Offset : -3023992489
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 1014518856544; DSPS: 33342479; Offset : -3024007622
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 1034519602422; DSPS: 33997863; Offset : -3023992057
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 1054520701373; DSPS: 34653259; Offset : -3023991713
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 1074521431938; DSPS: 35308643; Offset : -3023993622
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  877): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 1094522175316; DSPS: 35964027; Offset : -3023982510
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 1114522833017; DSPS: 36619409; Offset : -3023996221
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 1134523634832; DSPS: 37274795; Offset : -3023988045
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  877): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 1154524417741; DSPS: 37930181; Offset : -3023998150
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 1174525086171; DSPS: 38585563; Offset : -3024003425
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 1194525730798; DSPS: 39240944; Offset : -3023997688
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  877): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 1214526398499; DSPS: 39896326; Offset : -3024001036
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/UsageStatsService(  877): User[0] Flushing usage stats to disk
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 1234527141460; DSPS: 40551710; Offset : -3023990705
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 1254527857806; DSPS: 41207094; Offset : -3024006703
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/HeadsetStateMachine( 1987): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
W/Settings(  877): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  877): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  877): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 1274528683841; DSPS: 41862481; Offset : -3024006959
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 8396): 
D/AndroidRuntime( 8396): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8396): CheckJNI is OFF
D/AndroidRuntime( 8396): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  877): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  877): Killing 5574:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
W/PackageSettings(  877): Skipping PackageSetting{3096d0f com.example.hello/10317} due to missing metadata
I/WindowState(  877): WIN DEATH: Window{141ab9f7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  877): Focus left window: Window{141ab9f7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  877): Window went away: Window{141ab9f7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  877):   Force finishing activity ActivityRecord{1fa8e672 u0 com.test.thalitest/.MainActivity t222}
V/ActivityManager(  877): Display changed displayId=0
D/DSDPConnection( 1749): Display #0 changed.
W/ActivityManager(  877): Spurious death for ProcessRecord{2594f9e7 5574:com.test.thalitest/u0a316}, curProc for 5574: null
I/ActivityManager(  877): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  877): Reconfiguring input devices.  changes=0x00000010
D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1876): [Launcher.java:5203:onStart()]onStart
W/GeofencerStateMachine( 1731): Ignoring removeGeofence because network location is disabled.
I/art     ( 1936): Explicit concurrent mark sweep GC freed 32423(1920KB) AllocSpace objects, 8(222KB) LOS objects, 40% free, 12MB/20MB, paused 1.994ms total 110.215ms
I/[LGHome]EVENT( 1876): [Launcher.java:776:onResume()]onResume
W/System.err( 3672): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/ActivityManager(  877): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8430 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
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
I/[LGHome]EVENT( 1876): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/art     ( 5645): Explicit concurrent mark sweep GC freed 49796(2MB) AllocSpace objects, 13(208KB) LOS objects, 25% free, 13MB/18MB, paused 887us total 142.254ms
W/SQLiteConnectionPool( 5645): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1876): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1876): [Launcher.java:929:onResume()]onResume end
I/Activity( 1876): Activity.onPostResume() called 
I/art     (  877): Explicit concurrent mark sweep GC freed 14990(1152KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 10.226ms total 186.448ms
I/art     (  877): WaitForGcToComplete blocked for 117.644ms for cause Explicit
I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
W/[LGHome]LGWallpaperInfo( 1876): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1876): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1372): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
I/SystemUI[Framework](  877): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
D/InputDispatcher(  877): Focus entered window: Window{3799163b u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PhoneWindowManagerEx(  877): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  877): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  877): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  877): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@20e6aaad,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  877): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/SystemUI[Framework](  877): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  877): Call!!!getLGSystemUiVisibility. =0x0
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/StatusBarManagerServiceEx(  877): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  877): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  877): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@20e6aaad,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  877): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/ResourcesManager( 8430): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourcesManager( 8430): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/administrator(  877): Handling package changes for user 0
W/ResourcesManager( 8430): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1372): handleShortcutListChanged...
D/KeyguardModel( 1372): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1372): createShortcutInfo...
D/KeyguardModel( 1372): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1372): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1372): createShortcutInfo...
W/ResourceType( 1372): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1372): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1372): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1372): createShortcutInfo...
D/KeyguardModel( 1372): handleShortcutListChanged...
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1876): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  877): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  877): Got RemoteException sending setActive(false) notification to pid 5574 uid 10316
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  877): Timeline: Activity_windows_visible id: ActivityRecord{3ba7c7e3 u0 com.lge.launcher2/.Launcher t221} time:1294013
I/LGEmail ( 8430): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
W/IInputConnectionWrapper( 1876): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1615): Unable to connect to the editor to retrieve text... will retry later
D/LGEmail ( 8430): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1876): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1876): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/art     (  877): Explicit concurrent mark sweep GC freed 4732(254KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.504ms total 354.559ms
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
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
I/NotificationService(  877): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  877): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  877): Receieved: android.intent.action.PACKAGE_REMOVED
D/TaskPersister(  877): removeObsoleteFile: deleting file=222_task.xml
D/PhoneStatusBar( 1372): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
D/AndroidRuntime( 8396): Shutting down VM
I/PackageChangeReceiver( 8430): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/ActivityManager(  877): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8458 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  877): Killing 7736:com.google.android.talk/u0a61 (adj 15): empty #11
E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  877): failed to open /acct/uid_10061/pid_7736/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
W/IInputConnectionWrapper( 1876): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
I/AppUp4:AppBoxCP( 8458): onCreate
W/AppUp4:DB( 8458):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 8458):  setFingerPrint start
I/AppUp4:DB( 8458):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 8458):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8458):  SDK version = 0
I/AppUp4:DB( 8458):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8458): AppBoxApplication onCreate()
I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/sensors_hal_Time(  877): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  877): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  877): tsOffsetIs: Apps: 1294529417270; DSPS: 42517865; Offset : -3024003973
D/AppUp4:PreloadHelper( 8458): added Exclude : com.test.thalitest
I/Timeline( 1876): Timeline: Activity_idle id: android.os.BinderProxy@10930e7b time:1294582
I/ActivityManager(  877): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8478 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  877): Killing 7795:com.android.gallery3d/u0a23 (adj 15): empty #11
I/art     ( 1876): Explicit concurrent mark sweep GC freed 30303(1651KB) AllocSpace objects, 19(2MB) LOS objects, 40% free, 15MB/25MB, paused 1.225ms total 61.948ms
W/libprocessgroup(  877): failed to open /acct/uid_10023/pid_7795/cgroup.procs: No such file or directory

```
