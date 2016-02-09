#### Test 583805003a0697c_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/GAv4    ( 5443): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5443):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5443):   adb logcat -s GAv4
W/GAv4    ( 5443): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5443): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5443): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:27.368 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/AlertService( 3765): Beginning updateAlertNotification
W/AnalyticsTrackerProxyImpl( 5443): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
D/AlertService( 3765): No fired or scheduled alerts
I/NotificationManager( 3765): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3765): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3765): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3765): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3765): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3765): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3765): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3765): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3765): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3765): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3765): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3765): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3765): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3765): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3765): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3765): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3765): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3765): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3765): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3765): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3765): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 3765): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 3765): No events found starting within 1 week.
W/art     ( 5443): Suspending all threads took: 5.917ms
--------- beginning of system
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5443): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 5443): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5443): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/AndroidRuntime( 5473): 
D/AndroidRuntime( 5473): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/ActivityManager(  978): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5491 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  978): Killing 5264:com.android.providers.calendar/u0a14 (adj 15): empty #11
D/AndroidRuntime( 5473): CheckJNI is OFF
W/libprocessgroup(  978): failed to open /acct/uid_10014/pid_5264/cgroup.procs: No such file or directory
I/art     ( 5443): CheckpointMarkThreadRoots callback created = 0xb050e9b0
W/ResourcesManager( 5491): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/JNIHelp ( 5443): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/art     ( 5443): CheckpointMarkThreadRoots callback created = 0xb050e990
W/System  ( 5443): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5443): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AndroidRuntime( 5473): Calling main entry com.android.commands.am.Am
I/ActivityManager(  978): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  978): setTaskToReturnTo : TaskRecord{2246c4f6 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  978): setTaskToReturnTo : TaskRecord{2246c4f6 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  978): AppWindowTokenEx init.. 
D/ContextHelper(  978): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
D/InputDispatcher(  978): Focus left window: Window{3c6cbde8 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5473): Shutting down VM
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  978): check instance of lgWin Window{2b4c49d0 u0 Starting com.test.thalitest}
I/ActivityManager(  978): Killing 5286:com.lge.email/u0a21 (adj 15): empty #11
I/ActivityManager(  978): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5536 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup(  978): failed to open /acct/uid_10021/pid_5286/cgroup.procs: No such file or directory
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/ActivityManager(  978): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5554 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
I/HotwordDetector( 1937): Closing mic
I/WindowStateAnimator(  978): Starting window displayed
I/MicrophoneInputStream( 1937): mic_close com.google.android.apps.gsa.speech.audio.u@1dd88b2a
V/AudioRecord( 1937): stop()
D/AudioRecord( 1937): AudioRecord->stop()
V/AudioFlinger(  287): RecordHandle::stop()
V/AudioFlinger(  287): RecordThread::stop
V/AudioFlinger(  287): Record stopped OK
V/AudioPolicyManager(  287): stopInput() input 16
I/SystemUI[Framework](  978): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.test.thalitest
V/AudioPolicyService(  287): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  287): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  287): AudioCommandThread() waking up
V/AudioPolicyService(  287): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  287): releaseAudioPatch handle 17
V/AudioFlinger::PatchPanel(  287): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  287): ThreadBase::setParameters() routing=0
V/AudioFlinger(  287): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  287): processConfigEvents_l() remaining events 1
V/AudioFlinger(  287): processConfigEvents_l() DONE thread 0xb3838000
D/audio_hw_primary(  287): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
D/PhoneStatusBar( 1375): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
W/PhoneWindowManagerEx(  978): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  978): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  978): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  978): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1ea84cfb,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  978): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1375): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1375):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1375): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1375): draw background and invalidate : color = 14000000
,D/BarTransitions( 1375): draw background and invalidate : color = 1d1c1c1c
I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
V/audio_hw_primary(  287): stop_input_stream: enter: usecase(7: audio-record)
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
V/AudioPolicyManager(  287): removeAudioPatch() handle 18 af handle 17
V/AudioPolicyService(  287): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  287): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  287): AudioCommandThread() waking up
V/AudioPolicyService(  287): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  287): AudioCommandThread() going to sleep
V/AudioPolicyService(  287): AudioCommandThread() adding set parameter string hotword_active=0, io 16 ,delay 0
V/AudioPolicyService(  287): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  287): AudioCommandThread() waking up
V/AudioPolicyService(  287): AudioCommandThread() processing set parameters string hotword_active=0, io 16
V/AudioFlinger(  287): setParameters(): io 16, keyvalue hotword_active=0, calling pid 287
V/AudioFlinger(  287): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  287): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  287): RecordThread: loop starting
V/AudioFlinger(  287): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  287): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  287): in_set_parameters: exit: status(0)
V/AudioFlinger(  287): processConfigEvents_l() DONE thread 0xb3838000
V/AudioFlinger(  287): RecordThread: loop stopping
V/AudioPolicyService(  287): AudioCommandThread() going to sleep
V/AudioRecord( 1937): stop()
V/AudioRecord( 1937): stop()
V/AudioRecord( 1937): stop()
V/AudioFlinger(  287): RecordHandle::stop()
V/AudioFlinger(  287): RecordThread::stop
V/AudioPolicyManager(  287): releaseInput() 16
V/AudioPolicyManager(  287): closeInput(16)
V/AudioFlinger(  287): closeInput() 16
V/AudioSystem(  287): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1375): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  287): ThreadBase::exit
V/AudioSystem( 1966): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 3157): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1750): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem(  978): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 1937): ioConfigChanged() event 4, ioHandle 16
V/AudioSystem( 2673): ioConfigChanged() event 4, ioHandle 16
V/AudioFlinger(  287): RecordThread: loop starting
V/AudioFlinger(  287): releasing 15 from 1937 for -1
V/AudioFlinger(  287):  decremented refcount to 0
V/AudioFlinger(  287): purging stale effects
V/AudioFlinger(  287): RecordThread 0xb3838000 exiting
D/audio_hw_primary(  287): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  287): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  287): in_standby: exit:  status(0)
V/AudioPolicyService(  287): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  287): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  287): releaseInput() exit
V/AudioPolicyService(  287): AudioCommandThread() waking up
V/AudioPolicyService(  287): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  287): AudioCommandThread() going to sleep
V/AudioFlinger(  287): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  287): removeClient_l() pid 1937, calling pid 287
I/HotwordRecognitionRnr( 1937): Stopping hotword detection.
I/HotwordRecognitionRnr( 1937): Hotword detection finished
D/ContextHelper( 5536): convertTheme. context->name=com.test.thalitest themeResourceId=16973833
I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 157 ms] updated apps [took 157 ms] 
I/WebViewFactory( 5536): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5536): Time to load native libraries: 6 ms (timestamps 1049-1055)
I/LibraryLoader( 5536): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5536): Binding Chromium to main looper Looper (main, tid 1) {d5af652}
I/LibraryLoader( 5536): Expected native library version number "",actual native library version number ""
I/chromium( 5536): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5536): Initializing chromium process, singleProcess=true
W/art     ( 5536): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5536): ApplicationContext is null in ApplicationStatus
W/chromium( 5536): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5536): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5536): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5536): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5536): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5536): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5536): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5536): Remote Branch: 
I/Adreno-EGL( 5536): Local Patches: 
I/Adreno-EGL( 5536): Reconstruct Branch: 
D/Finsky  ( 5554): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
V/AudioPolicyService(  287): registerClient() client 0xb3830380, uid 10316
D/BluetoothManagerService(  978): Message: 20
D/BluetoothManagerService(  978): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12342983:true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,W/art     ( 5536): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5536): onDetachedFromWindow called when already detached. Ignoring
,D/Finsky  ( 5554): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,D/SystemWebViewEngine( 5536): CordovaWebView is running on device made by: LGE
W/art     ( 5536): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5536): Attempt to remove local handle scope entry from IRT, ignoring
W/Settings( 5554): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5554): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5554): com.android.vending: cancel(-1050172287) by com.android.vending
,I/Activity( 5536): Activity.onPostResume() called 
D/OpenGLRenderer( 5536): Render dirty regions requested: true
I/OpenGLRenderer( 5536): Initialized EGL, version 1.4
,V/DownloadManager( 3229): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@1850657b on behalf of 5554
D/OpenGLRenderer( 5536): Enabling debug mode 0
I/NotificationManager( 5554): com.android.vending: cancel(1003285959) by com.android.vending
D/Ads     ( 5554): Skipping gmscore version check
D/Finsky  ( 5554): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5554): [1] Libraries$2.run: Finished loading 1 libraries.
D/Atlas   ( 5536): Validating map...
,D/SplitWindow(  978): check instance of lgWin Window{1ec0f030 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  978): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5627 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/chromium( 5536): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/Finsky  ( 5554): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5554): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 5554): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/InputDispatcher(  978): Focus entered window: Window{1ec0f030 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  978): Killing 5315:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/libprocessgroup(  978): failed to open /acct/uid_10009/pid_5315/cgroup.procs: No such file or directory
,W/ResourcesManager( 5627): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5627): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/InputMethodManagerService(  978): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/ActivityManager(  978): Displayed com.test.thalitest/.MainActivity: +1s252ms
I/Timeline(  978): Timeline: Activity_windows_visible id: ActivityRecord{346900f7 u0 com.test.thalitest/.MainActivity t222} time:81853
I/Timeline( 5536): Timeline: Activity_idle id: android.os.BinderProxy@3f481949 time:81874
,I/MultiDex( 5627): VM with version 2.1.0 has multidex support
I/MultiDex( 5627): install
I/MultiDex( 5627): VM has multidex support, MultiDex support library is disabled.
,W/BindingManager( 5536): Cannot call determinedVisibility() - never saw a connection for the pid: 5536
,D/JsMessageQueue( 5536): Set native->JS mode to OnlineEventsBridgeMode
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  488): init target 500000
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
D/WifiController(  978): battery changed pluggedType: 2
W/MainApplication( 5192): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
V/JNIHelp ( 5627): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/charger_monitor(  488): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
,D/LEDHandler( 1804): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/MainApplication( 5192): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/WifiController(  978): battery changed pluggedType: 2
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ActivityThread( 5627): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5627): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1473646a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5627): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5627): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5627): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 5627): Reading stored module config
,D/PackageBroadcastService( 5627): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/ChimeraCfgMgr( 5627): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5627): Loading module APK com.google.android.play.games
D/NativeLibraryUtils( 5627): Install completed successfully. count=14 extracted=0
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:30.384 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/art     ( 5627): CheckpointMarkThreadRoots callback created = 0xb042d390
,D/jxcore_app_log( 5536): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1618700800
,I/art     ( 5627): CheckpointMarkThreadRoots callback created = 0xb042d380
I/chromium( 5536): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,D/ChimeraCfgMgr( 5627): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 5627): Module APK com.google.android.play.games already loaded
I/art     ( 5536): CheckpointMarkThreadRoots callback created = 0x9aa25470
,I/art     ( 3941): Explicit concurrent mark sweep GC freed 7966(400KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 475us total 60.140ms
D/ChimeraCfgMgr( 5627): Loading module com.google.android.gms.gass from APK com.google.android.gms
I/art     ( 5536): CheckpointMarkThreadRoots callback created = 0x9aa25440
,D/AsyncTaskServiceImpl( 5627): Submit a task: k
,D/ChimeraCfgMgr( 5627): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 5627): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 5627): Processing package: com.test.thalitest
,I/PeopleDatabaseHelper( 5627): cleanUpNonGplusAccounts done.
D/GassUtils( 5627): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,D/k       ( 5627): Found info for package com.test.thalitest in db.
I/Icing   ( 5627): Storage manager: low false usage 1.77MB avail 2.38GB capacity 4.06GB
,D/WearableService( 1732): callingUid 10006, callindPid: 1732
,E/MDM     ( 1732): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/art     ( 5627): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5627): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/BaseAppContext( 5627): Using Auth Proxy for data requests.
,E/BaseAppContext( 5627): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
W/BaseAppContext( 5627): Using Auth Proxy for data requests.
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 5627): Restart initialization of location
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  978): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5692 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/BaseAppContext( 5627): Using Auth Proxy for data requests.
,W/BaseAppContext( 5627): Using Auth Proxy for data requests.
,W/BaseAppContext( 5627): Using Auth Proxy for data requests.
W/BaseAppContext( 5627): Using Auth Proxy for data requests.
,W/BaseAppContext( 5627): Using Auth Proxy for data requests.
,I/art     (  978): Explicit concurrent mark sweep GC freed 23419(1124KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.468ms total 267.303ms
I/art     (  978): WaitForGcToComplete blocked for 129.437ms for cause HeapTrim
,I/ActivityManager(  978): Process com.android.contacts (pid 5374) has died
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
W/IcingInternalCorpora( 5627): getNumBytesRead when not calculated.
,I/ActivityManager(  978): Process com.android.gallery3d (pid 5355) has died
,W/ActivityManager(  978): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ActivityManager(  978): Process com.lge.appbox.client (pid 5338) has died
,D/InitAlarmsService( 3765): Clearing and rescheduling alarms.
,I/Icing   ( 5627): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  978): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5720 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/Gmail   ( 5692): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 5720): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/GAV2    ( 5692): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/CalendarProvider2( 5720): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2d07c5a1
,D/CalendarProvider2( 5720): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5720): Created com.android.providers.calendar.CalendarAlarmManager@d5af652(com.android.providers.calendar.CalendarProvider2@2d07c5a1)
D/CalendarProvider2( 5720): Scheduling check of next Alarm
D/CalendarProvider2( 5720): SCHEDULE_ALARM_REMOVE
,W/ActivityManager(  978): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5692): getAccountsCursor
,E/Gmail   ( 5692): Error finding the version of the Email provider.....
E/Gmail   ( 5692): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5692): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5692): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5692): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5692): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5692): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5692): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5692): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5692): We do not support migrating this version of the Email provider.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 5627): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 5627): Module APK com.google.android.play.games already loaded
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  978): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  978): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
I/Gmail   ( 5692): Observing account changes for notifications
,I/art     ( 5627): Background sticky concurrent mark sweep GC freed 12047(939KB) AllocSpace objects, 12(192KB) LOS objects, 6% free, 13MB/14MB, paused 14.063ms total 145.826ms
,I/ActivityManager(  978): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5767 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,V/DownloadManager( 3229): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@1148df98 on behalf of 5627
W/InstanceID/Rpc( 5627): Found 10006
,W/art     ( 5536): Suspending all threads took: 21.753ms
I/art     ( 5536): Background sticky concurrent mark sweep GC freed 8619(814KB) AllocSpace objects, 0(0B) LOS objects, 0% free, 20MB/20MB, paused 23.208ms total 70.612ms
,W/jxcore-log( 5536): Initializing JXcore engine
W/jxcore-log( 5536): JXcore engine is ready
I/Gmail   ( 5692): notifyAccountChanged
,I/Gmail   ( 5692): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5692): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/DownloadManager( 3229): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@17b7b3f1 on behalf of 5627
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/DownloadManager( 3229): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@2f713bd6 on behalf of 5627
I/Gmail   ( 5692): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5692): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5692): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Icing   ( 5627): Internal init done: storage state 0
,W/Thread-651( 5660): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5089]" dev="sockfs" ino=5089 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-651( 5660): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/Thread-651( 5660): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8238]" dev="sockfs" ino=8238 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/Thread-651( 5660): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-651( 5660): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/Thread-651( 5660): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[25101]" dev="sockfs" ino=25101 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
I/NotificationManager( 5627): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/PhoneMonitor( 5767): Register our PhoneStateListener
,W/jxcore-log( 5536): Starting JXcore engine
I/Icing   ( 5627): Post-init done
I/art     ( 3941): Explicit concurrent mark sweep GC freed 3162(123KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.503ms total 32.573ms
,D/PhoneMonitor( 5767): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5767): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 5767): [parse] Load xml
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
V/TelephonyAutoProfiling( 5767): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5767): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5767): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,W/jxcore-log( 5536): Platform android
W/jxcore-log( 5536): 
W/jxcore-log( 5536): Process ARCH arm
W/jxcore-log( 5536): 
,I/Gmail   ( 5692): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinService( 5627): Checkin interval check for package: unspecified last checkin: 1455056124705 min interval config: 0 actual interval: 8293
I/CheckinService( 5627): Disabling old GoogleServicesFramework version
,I/CheckinService( 5627): Checking schedule, now: 1455056133104 next: 1455056154664
I/CheckinService( 5627): active receiver: disabled
,I/ActivityManager(  978): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5795 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 20.863ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 262us total 20.196ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 20.155ms
,I/CalendarProvider2( 5720): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5720): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  978): Killing 3765:com.android.calendar/u0a13 (adj 15): empty #11
W/ResourcesManager( 5795): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/libprocessgroup(  978): failed to open /acct/uid_10013/pid_3765/cgroup.procs: No such file or directory
,I/ActivityManager(  978): Process com.google.android.apps.docs (pid 5443) has died
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:33.444 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ActivityManager(  978): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
,V/AlarmManager(  978): RTC_WAKEUP set : Alarm{38c9047c type 0 when 1454969684066 com.android.providers.contacts} when 1454969684066
V/AlarmManager(  978): ELAPSED_WAKEUP set : Alarm{20dce105 type 2 when 58652 com.google.android.talk} when 58652
V/AlarmManager(  978): RTC_WAKEUP set : Alarm{1cfb638b type 0 when 1455056133539 com.google.android.googlequicksearchbox} when 1455056133539
,I/jxcore-log( 5536): JXcore Cordova bridge is ready!
I/jxcore-log( 5536): 
,W/jxcore-log( 5536): JXcore engine is started
,I/Babel_SMS( 5795): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5795): MmsConfig.loadMmsSettings
I/Babel_SMS( 5795): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5795): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5795): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5795): MmsConfig.loadFromResources
E/Babel_SMS( 5795): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5795): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5795): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5795): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5795): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 5795): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5795): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5795): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5795): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5795): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5795): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5795): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5795): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5795): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5795): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5795): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5795): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5795): found sensor: Motion Accel, handle=46
I/jxcore-log( 5536): Toggling radios to true
I/jxcore-log( 5536): 
,I/art     ( 5795): CheckpointMarkThreadRoots callback created = 0xb042d820
D/BluetoothAdapter( 5536): enable(): BT is already enabled..!
W/Settings( 5795): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5795): startup - clean
D/WifiServiceImplEx(  978): setWifiEnabled: true pid=5536, uid=10316, package= com.test.thalitest, App Lable : ThaliTest
D/WifiService(  978): setWifiEnabled: true pid=5536, uid=10316
,I/Babel   ( 5795): deleted: false for 0
D/WifiServiceImplEx(  978): disconnect pid=5536, uid=10316, packageName=com.test.thalitest
D/WifiServiceImplEx(  978): reconnect pid=5536, uid=10316, packageName=com.test.thalitest
,I/jxcore-log( 5536): Radios toggled
I/jxcore-log( 5536): 
I/art     ( 5795): CheckpointMarkThreadRoots callback created = 0xb042d800
I/jxcore-log( 5536): My device name is: LGE-LG-D722
I/jxcore-log( 5536): 
,I/wpa_supplicant( 2783): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 4
,E/WifiStateMachine(  978): WifiStateMachine: Leaving Connected state
W/art     ( 5795): Suspending all threads took: 11.238ms
I/wpa_supplicant( 2783): p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
E/WifiConfigStore(  978): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/WfdsMonitor( 1804): Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,D/LGWifiP2pService(  978): InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  978): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  282): Clearing all IP addresses on wlan0
I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 7
V/NativeCrypto( 1732): Read error: ssl=0xb045aa00: I/O error during system call, Connection timed out
V/NativeCrypto( 1732): SSL shutdown failed: ssl=0xb045aa00: I/O error during system call, Broken pipe
,D/ConnectivityService(  978): reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
I/Icing   ( 5627): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
D/libc-netbsd(  978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 10
I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 7
D/ConnectivityService(  978): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  978): ignoring duplicate network state non-change
D/ConnectivityService(  978): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
D/WifiHS20(  978): hidePasspointNotification off =false
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  978): ValidatedState{ when=-7ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  978): DefaultState{ when=-21ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  978): Forcing reevaluation
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:34.029 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/libc-netbsd(  978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  978): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
E/WifiStateMachine(  978): Start Disconnecting Watchdog 1
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/wpa_supplicant( 2783): wlan0: CTRL-EVENT-SCAN-STARTED 
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:34.05 DNS addrs= 0.0.0.0, 0.0.0.0, 
D/WifiHS20(  978): hidePasspointNotification off =false
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  978): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/LGWifiP2pService(  978): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/libc-netbsd(  978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 32895(1908KB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 13MB/22MB, paused 41.747ms total 166.182ms
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
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
D/CommandListener(  282): Clearing all IP addresses on wlan0
D/ConnectivityService(  978): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  978): disableDataServiceNotify
,D/WifiHS20(  978): hidePasspointNotification off =false
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/DSQN    (  978): stop dsqn bin
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  978): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:34.116 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/WifiNetworkAgent(  978): NetworkAgent: NetworkAgent channel lost
D/WifiHS20(  978): hidePasspointNotification off =false
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  978): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:34.123 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
D/ConnectivityService(  978): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  978): NETWORK_STATE_CHANGED_ACTION [SCANNING]
D/WifiServerServiceExt(  978): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  978): setSupplicantStateDISCONNECTED
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiServerServiceExt(  978): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  978): setSupplicantStateSCANNING
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:34.134 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
,D/ConnectivityService(  978):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  978):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  978): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/Nat464Xlat(  978): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  978): ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  978): DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  978): Disconnected - quitting
D/CSLegacyTypeTracker(  978): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  978): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524292
D/ConnectivityService(  978): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  978): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  978): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
W/QCNEJ   ( 1839): |CORE| No family connected
V/NetworkPolicy(  978): [LG_RESTRICTED] !!!isConnected  type  :1
D/ConnectivityService(  978): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  978): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  978): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
V/NetworkPolicy(  978): [LG_RESTRICTED] !!!isConnected  type  :1
D/NetworkManagementService(  978): Removing idletimer
D/Tethering(  978): MasterInitialState.processMessage what=3
D/Tethering(  978): MasterInitialState.processMessage what=3
D/WIFI    (  978): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  978):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/TelephonyNetworkFactory-1( 1750): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
W/Settings(  978): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = -1
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
,I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/DhcpStateMachine(  978): StoppedState
D/DhcpStateMachine(  978): StoppedState{ when=-140ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/art     (  978): Explicit concurrent mark sweep GC freed 28122(1329KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.382ms total 298.646ms
D/Icing   ( 5627): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 5627): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,W/AudioCapabilities( 5795): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5795): Unsupported mime audio/adpcm
W/AudioCapabilities( 5795): Unsupported mime audio/g726
W/AudioCapabilities( 5795): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5795): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5795): Unsupported mime video/mjpg
,W/VideoCapabilities( 5795): Unsupported mime video/theora
W/AudioCapabilities( 5795): Unsupported mime audio/evrc
,W/AudioCapabilities( 5795): Unsupported mime audio/qcelp
W/VideoCapabilities( 5795): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5795): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5795): Unsupported mime audio/qcelp
,W/AudioCapabilities( 5795): Unsupported mime audio/evrc
W/VideoCapabilities( 5795): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5795): Unsupported profile 4 for video/mp4v-es
,I/ActivityManager(  978): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5843 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AudioManager( 5168): getMode name:com.lge.qremote
,I/AudioManager( 5168): getMode name:com.lge.qremote
,W/VideoCapabilities( 5795): Unrecognized profile 2130706433 for video/avc
I/AudioManager( 5168): getMode name:com.lge.qremote
W/VideoCapabilities( 5795): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5795): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5795): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 5795): onServiceConnected
W/Babel   ( 5795): Attempted to change video mute state without an active call.
I/AudioManager( 5168): getMode name:com.lge.qremote
,I/NotificationManager( 5795): com.google.android.talk: cancel(10436) by com.google.android.talk
D/UEI.SmartControl( 5843): Quickset Services start...
I/UEI.SmartControl( 5843): Manufacture = LGE
I/AudioManager( 5168): getMode name:com.lge.qremote
D/UEI.SmartControl( 5843): File observer start...
E/UEI.SmartControl( 5843): IR Port is disabled: false
D/UEI.SmartControl( 5843): Starting file observer...
D/UEI.SmartControl( 5843): Extracting JNI libs...
D/UEI.SmartControl( 5843): --- this system supports 32-bit or 64-bit only
,E/MDM     ( 1732): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 5627): Restart initialization of location
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  978): Process com.lge.bnr (pid 5192) has died
,W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1732): location=null
I/[SystemUI]QPairHandler( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  978): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/AudioManager( 5168): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5843): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
D/administrator(  978): Handling package changes for user 0
,D/UEI.SmartControl( 5843): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5843): --- Extracting JNI libs: libqs_armeabi-v7a.zip
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
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
I/UEI.SmartControl( 5843): --- Selecting new region: 2
,I/UEI.SmartControl( 5843): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5843): Platform has CIR...
,W/ResourcesManager( 5795): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5795): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5843): NO CIR support, need to check package...
,I/UEI.SmartControl( 5843): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5843): QS Service created
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,E/UEI.SmartControl( 5843): QS start get config
,I/ActivityManager(  978): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5870 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 5795): com.google.android.talk: cancel(8) by com.google.android.talk
D/UEI.SmartControl( 5843): Loading JNI Libs...
,D/UEI.SmartControl( 5843):  configuring local db...
I/NotificationService(  978): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  978): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  978): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  978): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  978): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  978): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@24999fed
,V/JNIHelp ( 5795): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2783): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
I/AppUp4:AppBoxCP( 5870): onCreate
,W/AppUp4:DB( 5870):  [AppBoxDatabaseHelper] construct
D/LocSvc_java(  978): onReceive
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:35.223 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  978): NETWORK_STATE_CHANGED_ACTION [SCANNING]
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  978): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
D/WifiServerServiceExt(  978): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  978): setSupplicantStateASSOCIATING
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:35.23 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 4
,I/wpa_supplicant( 2783): wlan0: Associated with c0:ff:d4:d3:aa:48
D/WifiServerServiceExt(  978): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  978): setSupplicantStateASSOCIATED
I/AppUp4:DB( 5870):  setFingerPrint start
I/AppUp4:DB( 5870):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  978): NETWORK_STATE_CHANGED_ACTION [CONNECTING]
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  978): NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
D/WifiServerServiceExt(  978): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  978): setSupplicantStateFOUR_WAY_HANDSHAKE
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:35.269 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:35.271 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/wpa_supplicant( 2783): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
I/wpa_supplicant( 2783): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed [id=0 id_str=]
I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 4
D/WifiServerServiceExt(  978): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  978): setSupplicantStateGROUP_HANDSHAKE
I/WifiServiceExtension(  978): setVHTCapabilityType  : false
,I/WifiServerServiceExt(  978): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
I/WifiServerServiceExt(  978): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
I/WifiServiceExtension(  978): setSecurityType  : 2
,I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  978): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:35.332 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
I/AppUp4:DB( 5870):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5870):  SDK version = 0
I/AppUp4:DB( 5870):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5870): AppBoxApplication onCreate()
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:35.34 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr= ipV6Addr=
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  978): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/ConnectivityService(  978): registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
D/ConnectivityService(  978): Got NetworkAgent Messenger
D/ConnectivityService(  978): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
D/ConnectivityService(  978): NetworkAgent connected
,D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
E/WifiConfigStore(  978): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
I/AppUp4:CustModeStarterReceiver( 5870): onReceive
I/AppUp4:CustModeStarterReceiver( 5870): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5870): Context : android.app.ReceiverRestrictedContext@32421eb4
D/AppUp4:CustFacade( 5870): isCustomizationCompleted : false
E/WifiConfigStore(  978): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/System  ( 5795): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5795): Installed default security provider GmsCore_OpenSSL
D/AppUp4:CustFacade( 5870): isSimDevice : true
I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 9
,D/libc-netbsd(  978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/AppUp4:CustModeStarterReceiver( 5870): begin check event
I/AppUp4:CustModeStarterReceiver( 5870): Event For Nothing, skip.
D/libc-netbsd(  978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/CommandListener(  282): Setting iface cfg
E/WifiStateMachine(  978): Start Dhcp Watchdog 2
D/DhcpStateMachine(  978): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  978): WaitBeforeStartState
I/ActivityManager(  978): Process com.lge.lockscreensettings (pid 5408) has died
,W/ResourcesManager(  978): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  978): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5891 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,D/UEI.SmartControl( 5843):  ---- Has DB8: true
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
D/ConnectivityService(  978): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
D/UEI.SmartControl( 5843): QS start statue = true Error code = 0
D/UEI.SmartControl( 5843): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5843): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 5843): IRRCDataComm has AudioManager!!!!.
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-54 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:35.585 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/WifiStateMachine(  978): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  978): Current State is mWaitBeforeStartState.
D/LGWifiP2pService(  978): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@95fa7d target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@95fa7d target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  978): WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  978): DHCP Start wake lock is acquired.
,V/LgDhcpStateMachineHelper(  978): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
W/irrc_jni( 5843): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5843): IrrcClient ++ 
D/irrcClient( 5843): getIrrcService ++ 
D/irrcClient( 5843): getIrrcService -- 
D/irrcClient( 5843): IrrcClient -- 
W/irrc_jni( 5843): IRRCPlayer_nativeInit -- 
D/CommandListener(  282): Setting iface cfg
I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 6
D/CommandListener(  282): Trying to bring up wlan0
D/libc-netbsd(  978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
V/LgDhcpStateMachineHelper(  978): setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.134/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
D/libc-netbsd(  978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/UEI.SmartControl( 5843): Services init done
,I/UEI.SmartControl( 5843): Device manager: loading config....
D/UEI.SmartControl( 5843): Config is loaded...
W/ResourceType(  978): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  978): Process com.android.vending (pid 5554) has died
D/UEI.SmartControl( 5843): QS Service init finished
,D/WifiServerServiceExt(  978): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  978): setSupplicantStateCOMPLETED
D/UEI.SmartControl( 5843):  ----- QS SDK is ready!!!
D/LGWifiP2pService(  978): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiServerServiceExt(  978): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  978): setSupplicantStateCOMPLETED
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/UEI.SmartControl( 5843): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5843): QS Service version name: 0.1.73
D/UEI.SmartControl( 5843): QS Service version code: 1073
D/UEI.SmartControl( 5843): Service requested: Control
D/ConnectivityService(  978): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/ConnectivityService(  978): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
E/WifiStateMachine(  978): WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
D/ConnectivityService(  978): ignoring duplicate network state non-change
D/UEI.SmartControl( 5843): Internal service binding...
D/UEI.SmartControl( 5843): -----IControl: 11
,D/UEI.SmartControl( 5843): Caller: com.lge.qremote
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
D/UEI.SmartControl( 5843): ------------ IControl registerCallback...
I/UEI.SmartControl( 5843): Registering callback...
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
D/UEI.SmartControl( 5843): -----IControl: 19
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  978): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/UEI.SmartControl( 5843): Caller: com.lge.qremote
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:35.749 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
I/UEI.SmartControl( 5843): Registering Services Ready callback...
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/UEI.SmartControl( 5843): Notify client services are ready...
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/UEI.SmartControl( 5843): -----IControl: 8
,D/UEI.SmartControl( 5843): Caller: com.lge.qremote
W/ResourcesManager( 5891): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5891): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5891): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/ConnectivityService(  978): NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = false, mWifiLevel = 0
,W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  978): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 0 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:35.771 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=0 ipV4Addr=192.168.1.134 ipV6Addr=
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
D/ConnectivityService(  978): Adding iface wlan0 to network 101
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/WifiHS20(  978): [PASSPOINT] passpointNotification: hs20AP list is checked
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:35.78 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = true, mWifiLevel = 3
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  978): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/WifiStateMachine(  978): Did not find remoteAddress {192.168.1.1} in /proc/net/arp
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
E/ConnectivityService(  978): Unexpected mtu value: 0, wlan0
D/ConnectivityService(  978): Adding Route [fe80::/64 -> :: wlan0] to network 101
,D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/ConnectivityService(  978): Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/Netd    (  282): netlink response contains error (File exists)
D/ConnectivityService(  978): Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
D/WifiHS20(  978): [PASSPOINT] passpointNotification: hs20AP list is checked
I/QCNEJ   ( 1839): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  978): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:35.804 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/QCNEJ   ( 1839): |CORE| notifyRatConnectStatus ratType=1 status=1 ipV4Addr=192.168.1.134 ipV6Addr=
D/ConnectivityService(  978): addLocalRoutetoDefaultNetwork
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
D/ConnectivityService(  978): defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
,D/ConnectivityService(  978): Setting Dns servers for network 101 to [/192.168.1.1]
D/libc-netbsd(  978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=53; cache_mode=local, netid=0; mark=0
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Nat464Xlat(  978): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  978): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  978): notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  978): DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  978): Connected
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  978): EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/ConnectivityService(  978): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  978):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  978):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  978):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  978):   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  978):     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
D/ConnectivityService(  978): currentScore = 0, newScore = 20
D/ConnectivityService(  978):    accepting network in place of null
D/ConnectivityService(  978): sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  978): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  978):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/TelephonyNetworkFactory-1( 1750): new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
E/ConnectivityService(  978): [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
D/CSLegacyTypeTracker(  978): Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/ConnectivityService(  978): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  978): [LWD] Start DNSResolver start to wait
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  978): [LWD] wait 500ms before dns check
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): mWifiConnected = true, mWifiLevel = 3
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSig,nalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1375): Remote
,D/Tethering(  978): MasterInitialState.processMessage what=3
D/ConnectivityService(  978): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/CSLegacyTypeTracker(  978): [e] list.add(nai) empty : false size: 1
D/ConnectivityService(  978): Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.134/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
,D/ConnectivityService(  978): validation of new default Network = false
D/ConnectivityService(  978): Default network via Wi-Fi connected. start DSQN
W/QCNEJ   ( 1839): |CORE| No family connected
I/QCNEJ   ( 1839): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
D/DSQN    (  978): enableDataServiceNotify 
D/DSQN    (  978): start dsqn bin
I/QCNEJ   ( 1839): |CORE| sendDefaultNwMsg: default = 1
I/CheckinService( 5627): Checkin interval check for package: unspecified last checkin: 1455056124705 min interval config: 0 actual interval: 11160
,D/LocationProviderProxy(  978): applying state to connected service
I/CheckinService( 5627): Checking schedule, now: 1455056135881 next: 1455056154664
I/CheckinService( 5627): active receiver: disabled
,V/NetworkPolicy(  978): [LG_RESTRICTED] checkMobilePolicy_type()
D/DhcpStateMachine(  978): DHCPV4 request on wlan0
,V/LgDhcpStateMachineHelper(  978): [bssid] hash key :c0:ff:d4:d3:aa:48
D/LgDhcpStateMachineHelper(  978): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
D/ConnectivityService(  978): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  978):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  978):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  978): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524290
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=(null)
I/DSQN    ( 5916): DSQN samuel.seo ver 141203
E/DSQN    ( 5916): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5916): created command queue thread
I/DSQN    ( 5916): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5916): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,I/dhcpcd  ( 5917): version 5.5.6 starting
E/dhcpcd  ( 5917): get_duid: Read-only file system
I/dhcpcd  ( 5917): wlan0: rebinding lease of 192.168.1.134
,I/AppConfig( 5891): Total System Memory = 906309632
,I/GalleryUtils( 5891): Application Heap = 96 MB
I/AppConfig( 5891): App Tier : NOT_DEF
D/SystemHelper( 5891): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  978): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5928 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 5928): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5928): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5928): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5928): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5928): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 5928): BUILD Country: EU
I/SystemConfig( 5928): BUILD Operator: OPEN
,D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  978): [LWD] DNSResolver start dns
D/libc-netbsd(  978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=101; mark=0
D/libc-netbsd(  978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  282): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  282): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=983141
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  978): Process com.google.android.gm (pid 5692) has died
,I/SystemConfig( 5928): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 5928): existFile = false
,I/SystemConfig( 5928): canReadFile = false
I/SystemConfig( 5928): systemFeature RCS result false
D/SystemConfig( 5928): refreshRcsSupport() :false
,I/ActivityManager(  978): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5951 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/LockScreenSettings( 5951): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 5951): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5951): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5951): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5951): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5951): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  978): Killing 5426:com.lge.eula/1000 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 61 ms] updated apps [took 61 ms] 
,W/libprocessgroup(  978): failed to open /acct/uid_1000/pid_5426/cgroup.procs: No such file or directory
I/ActivityManager(  978): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5975 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Netd    (  282): M: Get netlink event, ifname: wlan0 action: 6
,D/libc-netbsd(  978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/ConnectivityService(  978): Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
D/ConnectivityService(  978): identical MTU - not setting
D/Nat464Xlat(  978): requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityService(  978): notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  978):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  978):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  978): sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  978): Wi-Fi IP changed. Lp difference / No Route difference
D/DSQN    (  978): enableDataServiceNotify 
D/DSQN    (  978): start dsqn bin
,D/libc-netbsd(  282): res_queryN name = xxxxx succeed
I/System.out(  978): propertyValue:false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  978): [LWD] DNSResolver end dns
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  978): Checking http://clients3.google.com/generate_204 on "NG700"
D/DSQN    (  978): dsqn is running restart
,D/libc-netbsd(  978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/DSQN    ( 5984): DSQN samuel.seo ver 141203
E/DSQN    ( 5984): DSQN sock connect success to lgdatalistenerd
I/DSQN    ( 5984): created command queue thread
,I/DSQN    ( 5984): Interface wlan0 address 192.168.1.134 0xc0a80186
I/DSQN    ( 5984): Interface wlan0 netmask 255.255.255.0 0xc0a80186
,D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524295
I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.LINK_CONFIGURATION_CHANGED
I/DSQN    ( 5984): first global connection report this to start monitoring at DSQM.
I/DSQN    ( 5984): restart monitoring
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/LGDataListener(  282): argv[0]=dsqncommand
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:36.886 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/LGDataListener(  282): argv[1]=wlan0
D/LGDataListener(  282): argv[2]=1
D/LGDataListener(  282): notifyDSQN DSQN STARTMONITOR wlan0 1
I/DSQN    ( 5984): dsqn report finish
D/DSQN    (  978): DSQM DsqnNotification wlan0  1
D/DSQN    (  978): start to monitor internet connection
D/ConnectivityService(  978): NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,I/ActivityManager(  978): Process com.lge.qremote (pid 5168) has died
,D/ConnectivityService(  978): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/ConnectivityService(  978): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
D/LocSvc_java(  978): onReceive
D/LocSvc_java(  978): got connectivity action
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  978): broadcast - no network connections
D/LocSvc_java(  978): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  978): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  978): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  978): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  978): ignore wifi update if we are not in OPENING or CLOSING
D/LocSvc_java(  978): onReceive
D/LocSvc_java(  978): got connectivity action
D/LocSvc_java(  978): broadcast - no network connections
D/LocSvc_java(  978): Connectivity status : mWifiConnectivity - false; mWwanConnectivity - false
D/LocSvc_java(  978): Sending msg: 4 arg1:0 arg2:1
D/LocSvc_java(  978): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  978): updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  978): ignore wifi update if we are not in OPENING or CLOSING
,D/GpsLocationProvider(  978): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  978): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.conn.CONNECTIVITY_CHANGE at null
,V/AlarmManager(  978): ELAPSED_WAKEUP set : Alarm{14631ce2 type 2 when 89518 com.android.providers.calendar} when 89518
,D/GpsLocationProvider(  978): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/GpsLocationProvider(  978): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  978): isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Feb 2016 22:15:36 GMT], Server=[GFE/2.0], X-Android-Received-Millis=[1455056137217], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1455056136885]}
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  978): Don't send network conditions - lacking user consent.
D/WifiServiceExtension( 1804): isInternetCheckAvailable return false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  978): [LWD] wifi && isInternetCheckAvailable is false
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  978): Validated
D/ConnectivityService(  978): Validated NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  978): rematching NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  978):  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityService(  978):   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  978):     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
D/ConnectivityService(  978): Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
D/ConnectivityService(  978): notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
D/ConnectivityService(  978):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  978):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  978): sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  978): sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  978): sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
D/WIFI    (  978): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  978):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/ConnectivityManager.CallbackHandler( 1375): CM callback handler got msg 524290
D/TelephonyNetworkFactory-1( 1750): new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/TelephonyNetworkFactory-1( 1750):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
D/WifiDataContinuityService(  978): sendCaptiveCheckCompletedCmd isCaptive : false url : http://www.google.compopUp : 0
I/WifiServerServiceExt(  978): set CMD_CAPTIVE_CHECK_COMPLETED
D/TelephonyIcons( 1375): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1375): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconI,d=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully_disconnected mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/dhcpcd  ( 5917): wlan0: acknowledged 192.168.1.134 from 192.168.1.1
,I/dhcpcd  ( 5917): wlan0: leased 192.168.1.134 for 86400 seconds
,I/ActivityManager(  978): Process com.uei.lg.quicksetsdk.lite (pid 5843) has died
,D/Finsky  ( 5975): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/libc-netbsd(  978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DhcpStateMachine(  978): DHCPV4 succeeded on wlan0
D/LgDhcpStateMachineHelper(  978): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  978): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/libc-netbsd(  978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LgDhcpStateMachineHelper(  978): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.134
V/LgDhcpStateMachineHelper(  978): Don't need to update mDhcpResultsCacheList
V/DhcpStateMachine(  978): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  978): bShouldSendDhcpAction Result: false
D/DhcpStateMachine(  978): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  978): RunningState
I/ActivityManager(  978): Process com.android.providers.calendar (pid 5720) has died
,D/Finsky  ( 5975): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5975): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5975): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5975): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3229): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@10f5de57 on behalf of 5975
D/Ads     ( 5975): Skipping gmscore version check
D/Finsky  ( 5975): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5975): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 5975): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  978): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6056 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/PackageBroadcastService( 5627): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 5627): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 5627): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 5975): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,W/ResourcesManager( 6056): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  978): Message: 20
D/BluetoothManagerService(  978): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fcf45d5:true
,D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
,D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
I/ActivityManager(  978): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6082 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6056): Create singleton instance
,I/AudioManager( 6056): getMode name:com.lge.qremote
,I/AudioManager( 6056): getMode name:com.lge.qremote
,D/UEI.SmartControl( 6082): Quickset Services start...
I/UEI.SmartControl( 6082): Manufacture = LGE
D/UEI.SmartControl( 6082): File observer start...
E/UEI.SmartControl( 6082): IR Port is disabled: false
D/UEI.SmartControl( 6082): Starting file observer...
D/UEI.SmartControl( 6082): Extracting JNI libs...
D/UEI.SmartControl( 6082): --- this system supports 32-bit or 64-bit only
,I/ActivityManager(  978): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6101 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
D/UEI.SmartControl( 6082): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6082): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6082): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:15:38.591 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/UEI.SmartControl( 6082): --- Selecting new region: 2
I/UEI.SmartControl( 6082): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6082): Platform has CIR...
D/UEI.SmartControl( 6082): NO CIR support, need to check package...
I/UEI.SmartControl( 6082): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6082): QS Service created
,E/UEI.SmartControl( 6082): QS start get config
,D/UEI.SmartControl( 6082): Loading JNI Libs...
,D/UEI.SmartControl( 6082):  configuring local db...
V/WifiInternetCheck(  978): Single check msg out of sync, ignoring.
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  978): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6130 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
D/ConnectivityService(  978): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]QuickSettingsHandler( 1375): Got action android.net.conn.CONNECTIVITY_CHANGE at null
D/LocSvc_java(  978): onReceive
D/LocSvc_java(  978): got connectivity action
D/LocSvc_java(  978): Connectivity status : mWifiConnectivity - true; mWwanConnectivity - false
D/LocSvc_java(  978): Sending msg: 4 arg1:1 arg2:1
D/LocSvc_java(  978): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  978): updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
D/LocSvc_java(  978): ignore wifi update if we are not in OPENING or CLOSING
D/GpsLocationProvider(  978): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
D/GpsLocationProvider(  978): updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,E/UpdateRequestReceiver( 6130): Received malformed URL while handling Gservices.CHANGED_ACTION
,D/UEI.SmartControl( 6082):  ---- Has DB8: true
D/UEI.SmartControl( 6082): QS start statue = true Error code = 0
D/UEI.SmartControl( 6082): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 6082): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6082): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6082): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6082): IrrcClient ++ 
D/irrcClient( 6082): getIrrcService ++ 
D/irrcClient( 6082): getIrrcService -- 
D/irrcClient( 6082): IrrcClient -- 
W/irrc_jni( 6082): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6082): Services init done
I/UEI.SmartControl( 6082): Device manager: loading config....
I/art     (  978): Explicit concurrent mark sweep GC freed 75775(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.709ms total 235.357ms
,I/Icing   ( 5627): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
D/UEI.SmartControl( 6082): Config is loaded...
D/UEI.SmartControl( 6082):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6082): Notify AllClients services are ready: 0
,I/ActivityManager(  978): Process com.google.android.setupwizard (pid 5767) has died
D/UEI.SmartControl( 6082): QS Service init finished
,D/UEI.SmartControl( 6082): QS Service version name: 0.1.73
D/UEI.SmartControl( 6082): QS Service version code: 1073
D/UEI.SmartControl( 6082): Service requested: Control
D/UEI.SmartControl( 6082): -----IControl: 11
,D/UEI.SmartControl( 6082): Caller: com.lge.qremote
D/UEI.SmartControl( 6082): Internal service binding...
D/UEI.SmartControl( 6082): ------------ IControl registerCallback...
E/UpdateRequestReceiver( 6130): Received malformed URL while handling Gservices.CHANGED_ACTION
I/UEI.SmartControl( 6082): Registering callback...
D/UEI.SmartControl( 6082): -----IControl: 19
D/UEI.SmartControl( 6082): Caller: com.lge.qremote
I/UEI.SmartControl( 6082): Registering Services Ready callback...
I/UEI.SmartControl( 6082): Notify client services are ready...
,D/UEI.SmartControl( 6082): -----IControl: 8
D/UEI.SmartControl( 6082): Caller: com.lge.qremote
E/UpdateRequestReceiver( 6130): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 6130): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/Icing   ( 5627): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/ActivityManager(  978): Killing 5870:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  978): failed to open /acct/uid_10011/pid_5870/cgroup.procs: No such file or directory
,I/CheckinService( 5627): Checkin interval check for package: unspecified last checkin: 1455056124705 min interval config: 0 actual interval: 14867
,I/CheckinService( 5627): Checking schedule, now: 1455056139582 next: 1455056154664
I/CheckinService( 5627): active receiver: disabled
I/GservicesUpdateTask( 1937): Updating Gservices keys
,I/SystemUpdateService( 5627): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 5627): onCreate
,D/SystemUpdateService( 5627): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 5627): cancelUpdate (empty URL)
I/SystemUpdateService( 5627): active receiver: disabled
,I/NotificationManager( 5627): com.google.android.gms: cancel(2130838165) by com.google.android.gms
,I/NotificationManager( 5627): com.google.android.gms: cancel(2130838166) by com.google.android.gms
,I/art     ( 3941): Explicit concurrent mark sweep GC freed 3987(171KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 408us total 33.734ms
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/libc-netbsd(  978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  282): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  282): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  282): res_queryN name = xxxxx succeed
I/System.out(  978): propertyValue:false
,D/libc-netbsd(  978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  282): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  282): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  282): res_queryN name = xxxxx succeed
I/System.out(  978): propertyValue:false
I/art     ( 5627): Explicit concurrent mark sweep GC freed 23505(1424KB) AllocSpace objects, 9(144KB) LOS objects, 24% free, 13MB/17MB, paused 964us total 101.129ms
,I/art     ( 3941): Explicit concurrent mark sweep GC freed 2729(106KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 399us total 25.982ms
,D/SystemUpdateService( 5627): onDestroy
,E/DynamiteModule( 5627): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 5627): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 5627): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 5627): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 5627): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 5627): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 5627): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 5627): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 5627): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 5627): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 5627): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 5627): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/DynamiteModule( 5627): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/DynamiteModule( 5627): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/DynamiteModule( 5627): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 5627): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 5627): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/DynamiteModule( 5627): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 5627): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 5627): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/DynamiteModule( 5627): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/DynamiteModule( 5627): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 5627): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 5627): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 5627): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 5627): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 5627): 		... 17 more
E/DynamiteModule( 5627): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
,I/DynamiteModule( 5627): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 5627): Selected local version of com.google.android.gms.flags
I/ActivityManager(  978): Killing 5891:com.android.gallery3d/u0a23 (adj 15): empty #11
,V/WifiInternetCheck(  978): isHttpConnectionAvailable - We got a valid response : 204
,W/libprocessgroup(  978): failed to open /acct/uid_10023/pid_5891/cgroup.procs: No such file or directory
,D/Finsky  ( 5975): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  978): RTC_WAKEUP set : Alarm{3b4ffb3e type 0 when 1455056140263 com.android.vending} when 1455056140263
D/SystemEventReceiver( 5627): Received GSERVICES_CHANGED broadcast
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/OcrUtils( 5627): Updating ocr activity enabled=false
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
I/NotificationManager(  978): android: cancelAsUser(2) by android
,D/libc-netbsd( 5975): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5975): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5975): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5975): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  282): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  282): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
W/ActivityManager(  978): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/libc-netbsd(  282): res_queryN name = xxxxx succeed
I/System.out( 5975): propertyValue:false
D/libc-netbsd( 5975): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5975): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/OcrModelManager( 5627): Updating downloaded model state (gservices changed)
,V/AlarmManager(  978): ELAPSED_WAKEUP set : Alarm{17e18e87 type 2 when 93055 com.google.android.gms} when 93055
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 13887(1071KB) AllocSpace objects, 27(432KB) LOS objects, 40% free, 13MB/22MB, paused 1.380ms total 80.195ms
,I/NotificationManager(  978): android: cancelAsUser(-591465577) by android
,D/libc-netbsd( 5975): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5975): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 3941): Explicit concurrent mark sweep GC freed 2626(104KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 757us total 25.587ms
,D/GCM     ( 1732): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  282): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  282): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  282): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  978): android: cancelAsUser(2) by android
,I/GCoreUlr( 1732): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1732): DispatchingService.onCreate()
,I/qtaguid ( 5975): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5975): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5975): untagSocket(41) failed with errno -22
D/Finsky  ( 5975): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
I/ActivityManager(  978): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6207 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 302us total 21.772ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 21.333ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 21.231ms
,W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
,I/ActivityManager(  978): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6226 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/PhoneMonitor( 6207): Register our PhoneStateListener
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  978): android: cancelAsUser(2) by android
,E/ctxmgr  ( 1732): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,I/GCoreUlr( 1732): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/ResourcesManager( 6226): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6226): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/SetupWizard( 6207): Connected to Gservices successfully
,D/PhoneMonitor( 6207): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6207): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6207): [parse] Load xml
V/TelephonyAutoProfiling( 6207): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6207): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6207): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/MultiDex( 6226): VM with version 2.1.0 has multidex support
I/MultiDex( 6226): install
I/MultiDex( 6226): VM has multidex support, MultiDex support library is disabled.
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/WearableService( 1732): callingUid 10006, callindPid: 1732
,D/LocationInitializer( 5627): Restart initialization of location
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1732): [140] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ctxmgr  ( 1732): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
I/qtaguid ( 5975): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5975): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5975): untagSocket(41) failed with errno -22
E/ctxmgr  ( 1732): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
V/JNIHelp ( 6226): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/GCoreUlr( 1732): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/ActivityManager(  978): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6255 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityThread( 6226): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6226): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@30b85d44: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6226): Installed default security provider GmsCore_OpenSSL
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
I/NotificationManager( 6226): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6226): com.google.android.gms: cancel(39789) by com.google.android.gms
,I/GCoreUlr( 1732): Unbound from all location providers
I/GCoreUlr( 1732): Place inference reporting - stopped
D/ChimeraCfgMgr( 6226): Reading stored module config
,I/GCoreUlr( 1732): DispatchingService.onDestroy()
I/GCoreUlr( 1732): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1732): Unbound from all location providers
I/GCoreUlr( 1732): Place inference reporting - stopped
,D/ChimeraCfgMgr( 6226): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/art     ( 5975): Suspending all threads took: 5.880ms
,I/art     ( 5975): WaitForGcToComplete blocked for 48.956ms for cause HomogeneousSpaceCompact
,D/CAR.SERVICE( 6226): Connecting to CarCallService...
,I/art     ( 6226): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6226): Install completed successfully. count=14 extracted=0
I/art     ( 6226): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/CAR.SERVICE( 6226): com.google.android.projection.gearhead isn't installed.
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 94559543353; DSPS: 3196965; Offset : -3013575118
,I/art     ( 5975): CheckpointMarkThreadRoots callback created = 0xb0580300
,I/ActivityManager(  978): Process com.google.android.talk (pid 5795) has died
W/ActivityManager(  978): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/CAR.TEL.Service( 6226): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 6226): Creating a new PhoneAdapter instance
,I/art     ( 5975): CheckpointMarkThreadRoots callback created = 0xb05802f0
,I/art     (  978): Explicit concurrent mark sweep GC freed 27932(1432KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.313ms total 146.947ms
,W/ActivityManager(  978): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6226): setListener: com.google.android.gms.car.dn@10cd14e3
W/ActivityManager(  978): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6226): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6226): Starting CarCallService with initial phone null
I/NotificationManager( 6226): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/Gmail   ( 6255): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 3941): Explicit concurrent mark sweep GC freed 2857(112KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 436us total 28.732ms
,D/CAR.SERVICE( 6226): Package validated; name: com.android.vending
I/NotificationManager( 5975): com.android.vending: cancel(10436) by com.android.vending
,W/GAV2    ( 6255): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
V/Finsky  ( 5975): [1] GearheadStateMonitor.access$100: mIsProjecting:false
W/ActivityManager(  978): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  978): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  978): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6255): Observing account changes for notifications
E/Gmail   ( 6255): Error finding the version of the Email provider.....
E/Gmail   ( 6255): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6255): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6255): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6255): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6255): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6255): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6255): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6255): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6255): We do not support migrating this version of the Email provider.
I/Gmail   ( 6255): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  978): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6306 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 6255): notifyAccountChanged
,I/Gmail   ( 6255): getAccountsCursor
I/Gmail   ( 6255): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6255): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6255): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6255): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/ResourcesManager( 6306): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CalendarApplication( 6306): CalendarApplication.onCreate()
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 23827(1428KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 13MB/23MB, paused 1.477ms total 84.749ms
,I/NotificationManager(  978): android: cancelAsUser(2) by android
,D/PreferenceKeysParser( 6306): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6306): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@ad0ff87, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@32421eb4, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3eba1add, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@d5af652, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3c340d23, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@a3c7220, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@2b4287d9, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@1b8e259e, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@130587f, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2dc6904c, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@244ac895, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3532fdaa, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@b7bfd9b, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@2bf26538, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@125c5911, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@289b4a76, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2812d877, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@31049ce4, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@31c754d, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@5699802, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@dd28513, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@6e0a350, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@3f481949, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@dd324e, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@39d65f6f, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3034a47c, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@4700105, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@12de255a, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@3593838b, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@a658c68, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@1e74a881, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@17c93d26, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@22b4cd67, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@223b0714, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@1cc24bbd, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@2fc05b2, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@28b6d903, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@274b8080, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1f4ce6b9, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2e20cafe, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@2044025f, lg_preferences_recent_ti,mezones=com.android.calendar.adaptation.PreferenceKey$KeyData@2a2824ac, lg
D/GeneralPreferenceUtils( 6306): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
,D/Config  ( 6306): [init]
I/Config  ( 6306): LGCalendar ver.4.40.17
I/Config  ( 6306): start check model
I/Config  ( 6306): start check native_ca
I/Config  ( 6306): Config Operator=OPEN, Country=EU
D/Config  ( 6306): [setDefaultValuesToPref]
D/Config  ( 6306): [parseProfiles]
D/ProfilesParser( 6306): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6306): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6306): [updateProfiletoCountryInfo]
D/GeneralPreference( 6306): [checkAndMigrateOldPreference]
I/jxcore-log( 5536): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMultiplex.js
I/jxcore-log( 5536): 
,D/AlertReceiver( 6306): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/InitNotificationRingtoneService( 6306): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6306): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 6306): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/Gmail   ( 6255): getAccountsCursor
I/AlertUtils( 6306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AlertUtils( 6306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 6306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 6306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6306): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6306): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6306): End InitializeAlertRingtoneService.onHandleIntent
,W/HolidayIntentService( 6306): onHandleIntent
,D/HolidayDataLoader( 6306): readJsonAsset : holiday.json
D/AlertService( 6306): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6306): [updateWidgets] 
D/MonthWidgetProvider( 6306): [onReceive]
D/CalendarWidgetProvider( 6306): [onReceive]
D/CalendarWidgetProvider( 6306): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6306): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6306): [onReceive]
D/CalendarWidgetProvider( 6306): [onReceive]
,D/CalendarWidgetProvider( 6306): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6306): [onCreate] mContext.getPackageName() = com.android.calendar
E/HolidayIntentService( 6306): onHandleIntent:holiday data empty
,I/ActivityManager(  978): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=6333 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/qtaguid ( 5975): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5975): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5975): untagSocket(41) failed with errno -22
,W/ResourcesManager( 6333): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5975): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5975): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/ResourcesManager( 5975): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5975): [1] DailyHygiene.access$600: Logging device features
,I/ActivityManager(  978): Process com.lge.qremote (pid 6056) has died
,V/AlarmManager(  978): RTC_WAKEUP set : Alarm{2c5fa6ed type 0 when 1455056143887 com.android.vending} when 1455056143887
I/Babel_SMS( 6333): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6333): MmsConfig.loadMmsSettings
,D/DeviceConnectionService( 1732): client connected with version: 8296000
I/Babel_SMS( 6333): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6333): MmsConfig.loadFromDatabase
,D/Finsky  ( 5975): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5975): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/art     ( 6333): CheckpointMarkThreadRoots callback created = 0xb042d6c0
,E/Babel_SMS( 6333): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6333): MmsConfig.loadFromResources
E/Babel_SMS( 6333): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6333): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6333): CheckpointMarkThreadRoots callback created = 0xb042d6a0
,D/SensorManager( 6333): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6333): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6333): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6333): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6333): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6333): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6333): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6333): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6333): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6333): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6333): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6333): found sensor: LGE Orientation Sensor, handle=49
,D/SensorManager( 6333): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6333): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6333): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6333): found sensor: Motion Accel, handle=46
W/Settings( 6333): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6333): startup - clean
I/Babel   ( 6333): deleted: false for 0
,D/UEI.SmartControl( 6082): Internal timer expired: 1
,D/UEI.SmartControl( 6082): Service.onUnbind: IControl
D/UEI.SmartControl( 6082): Service.onDestroy
D/UEI.SmartControl( 6082): Shutdown IRRCPlayer... 
,W/irrc_jni( 6082): IRRCPlayer_nativeFinalize ++ 
,D/irrcClient( 6082): ~IrrcClient ++ 
D/irrcClient( 6082): ~IrrcClient -- 
W/irrc_jni( 6082): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6082): Blaster closed
D/UEI.SmartControl( 6082): Blaster closed
D/UEI.SmartControl( 6082): Shut down QS...
D/UEI.SmartControl( 6082): Stopped file observer...
I/UEI.SmartControl( 6082): QS lib stop result = true
D/UEI.SmartControl( 6082): QS shutdown complete
I/ActivityManager(  978): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=6362 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  978): Killing 5928:com.android.contacts/u0a18 (adj 15): empty #11
,W/AudioCapabilities( 6333): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6333): Unsupported mime audio/adpcm
W/AudioCapabilities( 6333): Unsupported mime audio/g726
W/AudioCapabilities( 6333): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6333): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 6333): Unsupported mime video/mjpg
W/VideoCapabilities( 6333): Unsupported mime video/theora
W/AudioCapabilities( 6333): Unsupported mime audio/evrc
,W/AudioCapabilities( 6333): Unsupported mime audio/qcelp
W/VideoCapabilities( 6333): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6333): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6333): Unsupported mime audio/qcelp
W/AudioCapabilities( 6333): Unsupported mime audio/evrc
,W/VideoCapabilities( 6333): Unsupported mime video/mp4v-esdp
W/libprocessgroup(  978): failed to open /acct/uid_10018/pid_5928/cgroup.procs: No such file or directory
,I/VideoCapabilities( 6333): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6333): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6333): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6333): Unrecognized profile 2130706433 for video/avc
V/AlarmManager(  978): RTC_WAKEUP set : Alarm{37016ed2 type 0 when 1455056144538 com.google.android.googlequicksearchbox} when 1455056144538
W/VideoCapabilities( 6333): Unrecognized profile 2130706433 for video/avc
,I/jxcore-log( 5536): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
I/jxcore-log( 5536): 
,I/vclib   ( 6333): onServiceConnected
W/Babel   ( 6333): Attempted to change video mute state without an active call.
,W/ResourcesManager( 6333): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6333): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6362): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6362): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 6362): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6362): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 6362): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,V/JNIHelp ( 6333): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/jxcore-log( 5536): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliCryptoManager.js
I/jxcore-log( 5536): 
W/System  ( 6333): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6333): Installed default security provider GmsCore_OpenSSL
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/NotificationManager( 6333): com.google.android.talk: cancel(10436) by com.google.android.talk
I/IndexDatabaseHelper( 6362): Using schema version: 115
,I/IndexDatabaseHelper( 6362): Index is fine
I/jxcore-log( 5536): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliEmitter.js
I/jxcore-log( 5536): 
,I/ActivityManager(  978): Process com.uei.lg.quicksetsdk.lite (pid 6082) has died
,I/jxcore-log( 5536): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
I/jxcore-log( 5536): 
,V/WiFiOffLoadBroadcast( 6362): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6362): MCCMNC not supported: null
I/ActivityManager(  978): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6392 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/PCSuite ( 6392): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6392): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6392): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  978): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6412 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/ActivityManager(  978): Killing 5951:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  978): failed to open /acct/uid_10069/pid_5951/cgroup.procs: No such file or directory
,I/art     (  978): Explicit concurrent mark sweep GC freed 14940(721KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.420ms total 154.526ms
,W/ResourcesManager( 6412): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  978): Message: 20
D/BluetoothManagerService(  978): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e71def7:true
,D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/WiFiOffLoadBroadcast( 6362): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 6362): MCCMNC not supported: null
I/PCSuite ( 6392): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 6392): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6392): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6362): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6362): MCCMNC not supported: null
I/PCSuite ( 6392): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6392): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6392): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 6362): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6362): MCCMNC not supported: null
I/ActivityManager(  978): Process com.google.android.apps.plus (pid 5491) has died
,I/PCSuite ( 6392): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
D/PCSuite ( 6392): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 6392): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6362): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6362): MCCMNC not supported: null
I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  978): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6434 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/NotificationManager( 6333): com.google.android.talk: cancel(8) by com.google.android.talk
,I/AppUp4:AppBoxCP( 6434): onCreate
,W/AppUp4:DB( 6434):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6434):  setFingerPrint start
I/AppUp4:DB( 6434):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6434):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6434):  SDK version = 0
I/AppUp4:DB( 6434):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6434): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 6434): onReceive
I/AppUp4:CustModeStarterReceiver( 6434): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6434): Context : android.app.ReceiverRestrictedContext@32421eb4
D/AppUp4:CustFacade( 6434): isCustomizationCompleted : false
I/ActivityManager(  978): Process com.google.android.gm (pid 6255) has died
,D/AppUp4:CustFacade( 6434): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6434): begin check event
I/AppUp4:CustModeStarterReceiver( 6434): Event For Nothing, skip.
I/ActivityManager(  978): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6454 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 6454): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6454): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6454): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/AppConfig( 6454): Total System Memory = 906309632
,I/GalleryUtils( 6454): Application Heap = 96 MB
I/AppConfig( 6454): App Tier : NOT_DEF
,D/SystemHelper( 6454): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  978): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6473 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  978): Killing 6101:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  978): failed to open /acct/uid_10009/pid_6101/cgroup.procs: No such file or directory
,W/ResourcesManager( 6473): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6473): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6473): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6473): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6473): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6473): BUILD Country: EU
I/SystemConfig( 6473): BUILD Operator: OPEN
,I/ActivityManager(  978): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6492 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  978): Killing 6130:com.google.android.configupdater/u0a3 (adj 15): empty #11
,I/art     (  312): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 26.512ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.989ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 26.511ms
,W/libprocessgroup(  978): failed to open /acct/uid_10003/pid_6130/cgroup.procs: No such file or directory
,I/SystemConfig( 6473): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6473): existFile = false
I/SystemConfig( 6473): canReadFile = false
I/SystemConfig( 6473): systemFeature RCS result false
D/SystemConfig( 6473): refreshRcsSupport() :false
I/LockScreenSettings( 6492): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6492): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6492): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6492): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6492): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6492): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  978): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6513 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  978): Killing 6207:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  978): failed to open /acct/uid_10038/pid_6207/cgroup.procs: No such file or directory
,W/ResourcesManager( 6513): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CAR.SERVICE( 6226): mConnectedToCar = false, abort
,E/ActivityThread( 6226): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@5c1a36b that was originally bound here
E/ActivityThread( 6226): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@5c1a36b that was originally bound here
E/ActivityThread( 6226): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6226): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6226): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6226): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6226): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6226): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6226): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6226): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6226): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6226): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6226): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6226): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6226): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6226): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6226): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6226): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6226): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6226): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6226): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6226): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6226): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6226): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6226): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6226): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1984512 that was originally bound here
E/ActivityThread( 6226): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1984512 that was originally bound here
E/ActivityThread( 6226): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6226): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6226): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6226): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6226): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6226): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6226): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6226): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6226): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6226): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6226): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6226): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6226): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6226): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6226): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6226): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6226): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6226): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6226): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6226): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6226): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6226): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  978): Unbind failed: could not find connection for android.os.BinderProxy@7ad7b85
I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,V/WiFiOffLoadBroadcast( 6362): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 6362): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 6362): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/PackageBroadcastService( 5627): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
D/WiFiOffLoadBroadcast( 6362): MCCMNC not supported: null
,I/PackageBroadcastService( 5627): Null package name or gms related package.  Ignoreing.
I/Icing   ( 5627): updateResources: need to parse f{com.google.android.gms}
,V/WiFiOffLoadBroadcast( 6362): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 82 ms] updated apps [took 82 ms] 
D/WiFiOffLoadBroadcast( 6362): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 6362): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6362): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6362): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6362): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6362): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6362): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6362): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6362): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6362): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6362): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 6362): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6362): MCCMNC not supported: null
I/ActivityManager(  978): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6551 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 6412): Create singleton instance
,I/AudioManager( 6412): getMode name:com.lge.qremote
,V/WiFiOffLoadBroadcast( 6362): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6362): MCCMNC not supported: null
I/PCSuite ( 6392): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 6392): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 6362): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 6362): MCCMNC not supported: null
I/PCSuite ( 6392): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 6392): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/UEI.SmartControl( 6551): Quickset Services start...
,I/UEI.SmartControl( 6551): Manufacture = LGE
D/UEI.SmartControl( 6551): File observer start...
E/UEI.SmartControl( 6551): IR Port is disabled: false
D/UEI.SmartControl( 6551): Starting file observer...
D/UEI.SmartControl( 6551): Extracting JNI libs...
D/UEI.SmartControl( 6551): --- this system supports 32-bit or 64-bit only
I/ActivityManager(  978): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6569 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/UEI.SmartControl( 6551): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6551): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6551): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6551): --- Selecting new region: 2
,I/UEI.SmartControl( 6551): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6551): Platform has CIR...
D/UEI.SmartControl( 6551): NO CIR support, need to check package...
I/UEI.SmartControl( 6551): Model: LG-D722 uses JNI
D/AlertService( 6306): Beginning updateAlertNotification
,D/UEI.SmartControl( 6551): QS Service created
E/UEI.SmartControl( 6551): QS start get config
,I/ActivityManager(  978): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6586 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6551): Loading JNI Libs...
D/UEI.SmartControl( 6551):  configuring local db...
,W/ResourcesManager( 6586): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/PhoneMonitor( 6569): Register our PhoneStateListener
,I/ActivityManager(  978): Killing 6226:com.google.android.gms:car/u0a6 (adj 15): empty #11
,D/PhoneMonitor( 6569): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6569): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6569): [parse] Load xml
,V/TelephonyAutoProfiling( 6569): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6569): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6569): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/CalendarProvider2( 6586): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2d07c5a1
,D/UEI.SmartControl( 6551):  ---- Has DB8: true
,D/UEI.SmartControl( 6551): QS start statue = true Error code = 0
D/UEI.SmartControl( 6551): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6551): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6551): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6551): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6551): IrrcClient ++ 
,D/irrcClient( 6551): getIrrcService ++ 
D/irrcClient( 6551): getIrrcService -- 
D/irrcClient( 6551): IrrcClient -- 
W/irrc_jni( 6551): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6551): Services init done
I/UEI.SmartControl( 6551): Device manager: loading config....
W/PackageSettings(  978): Skipping PackageSetting{425bb94 com.example.hello/10317} due to missing metadata
,W/libprocessgroup(  978): failed to open /acct/uid_10006/pid_6226/cgroup.procs: No such file or directory
D/CalendarProvider2( 6586): [getOrCreateCalendarAlarmManager]
D/UEI.SmartControl( 6551): QS Service init finished
I/CalendarProvider2( 6586): Created com.android.providers.calendar.CalendarAlarmManager@d5af652(com.android.providers.calendar.CalendarProvider2@2d07c5a1)
D/UEI.SmartControl( 6551): QS Service version name: 0.1.73
D/UEI.SmartControl( 6551): QS Service version code: 1073
D/UEI.SmartControl( 6551): Service requested: Control
,D/UEI.SmartControl( 6551): Config is loaded...
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/UEI.SmartControl( 6551):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6551): Notify AllClients services are ready: 0
I/ActivityManager(  978): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6609 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UEI.SmartControl( 6551): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6551): Internal service binding...
,D/AlertService( 6306): No fired or scheduled alerts
I/CheckinService( 5627): Checkin interval check for package: unspecified last checkin: 1455056124705 min interval config: 0 actual interval: 24292
D/UEI.SmartControl( 6551): -----IControl: 11
D/UEI.SmartControl( 6551): Caller: com.lge.qremote
D/UEI.SmartControl( 6551): ------------ IControl registerCallback...
I/UEI.SmartControl( 6551): Registering callback...
D/UEI.SmartControl( 6551): -----IControl: 19
,D/UEI.SmartControl( 6551): Caller: com.lge.qremote
I/UEI.SmartControl( 6551): Registering Services Ready callback...
I/UEI.SmartControl( 6551): Notify client services are ready...
D/UEI.SmartControl( 6551): -----IControl: 8
D/UEI.SmartControl( 6551): Caller: com.lge.qremote
I/ActivityManager(  978): Killing 6454:com.android.gallery3d/u0a23 (adj 15): empty #11
,I/NotificationManager( 6306): com.android.calendar: cancel(0) by com.android.calendar
,I/NotificationManager( 6306): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6306): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6306): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6306): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6306): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6306): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6306): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6306): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6306): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6306): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6306): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6306): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6306): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6306): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6306): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6306): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6306): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6306): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6306): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6306): com.android.calendar: cancel(20) by com.android.calendar
I/Icing   ( 5627): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/ActivityManager(  978): Killing 6434:com.lge.appbox.client/u0a11 (adj 15): empty #12
,W/libprocessgroup(  978): failed to open /acct/uid_10023/pid_6454/cgroup.procs: No such file or directory
,I/CheckinService( 5627): Checking schedule, now: 1455056149316 next: 1455056154664
I/CheckinService( 5627): active receiver: disabled
W/libprocessgroup(  978): failed to open /acct/uid_10011/pid_6434/cgroup.procs: No such file or directory
D/AlertService( 6306): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,I/ActivityManager(  978): Killing 6473:com.android.contacts/u0a18 (adj 15): empty #11
D/Icing   ( 5627): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 5627): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,W/libprocessgroup(  978): failed to open /acct/uid_10018/pid_6473/cgroup.procs: No such file or directory
D/AlarmScheduler( 6306): No events found starting within 1 week.
I/ActivityManager(  978): Killing 6492:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  978): failed to open /acct/uid_10069/pid_6492/cgroup.procs: No such file or directory
,I/ActivityManager(  978): Killing 6306:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  978): failed to open /acct/uid_10013/pid_6306/cgroup.procs: No such file or directory
,I/MusicStore( 6609): Database version: 120
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6609): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6609): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6609): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 6609): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6609): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6609): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6609): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6609): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2a30932f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6609): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 6609): GMSCore installation verified
I/ConfigStore( 6609): Config Database version: 1
,I/MediaRouter( 6609): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6609): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6609): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 6609): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  978): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6648 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6609): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6609): Using platform SSLCertificateSocketFactory
I/ActivityManager(  978): Killing 6513:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/ResourcesManager( 6648): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6648): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6648): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  978): failed to open /acct/uid_10086/pid_6513/cgroup.procs: No such file or directory
,I/NotificationManager( 6609): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 6648): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 6648): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 6648): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/rmt_storage(  280): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  280): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  280): wakelock acquired: 1, error no: 42
I/rmt_storage(  280): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/ActivityManager(  978): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6680 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/rmt_storage(  280): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  280): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  280): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  280): 
I/rmt_storage(  280): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/HubEmail( 6648): JNI_OnLoad()
I/HubEmail( 6648): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6648): registerNatives()
I/HubEmail( 6648): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6648): registerNativeMethods()
I/HubEmail( 6648): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6648): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,W/Settings( 6648): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/art     (  978): Explicit concurrent mark sweep GC freed 19592(1183KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.323ms total 146.677ms
,I/ActivityManager(  978): Killing 5975:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  978): failed to open /acct/uid_10036/pid_5975/cgroup.procs: No such file or directory
,I/ActivityManager(  978): Killing 6333:com.google.android.talk/u0a61 (adj 15): empty #11
D/LGDMClient( 6680): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6680): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 6680): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/libprocessgroup(  978): failed to open /acct/uid_10061/pid_6333/cgroup.procs: No such file or directory
,W/ContextImpl( 6680): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6680): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6680): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager(  978): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6702 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/LGDMClient( 6680): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 6680): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,W/ContextImpl( 6680): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6680): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6680): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6680): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 6680): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6680): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  978): Killing 6362:com.android.settings/1000 (adj 15): empty #11
I/AppUp4:AppBoxCP( 6702): onCreate
,W/AppUp4:DB( 6702):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6702):  setFingerPrint start
I/AppUp4:DB( 6702):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6702):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6702):  SDK version = 0
,I/AppUp4:DB( 6702):  beforefinger == newfinger no write in DB
W/libprocessgroup(  978): failed to open /acct/uid_1000/pid_6362/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 6702): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 6702): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 6702): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 6702): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 6702): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 6702): onReceive
I/AppUp4:CustModeStarterReceiver( 6702): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 6702): Context : android.app.ReceiverRestrictedContext@3c340d23
D/AppUp4:CustFacade( 6702): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6702): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6702): begin check event
I/AppUp4:CustModeStarterReceiver( 6702): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 6702): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 6702): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 6702): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 6702): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  978): Killing 6551:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 6412): android.os.DeadObjectException
,W/System.err( 6412): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6412): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6412): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6412): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6412): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6412): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6412): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6412): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6412): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6412): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6412): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6412): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6412): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6412): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6412): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6412): android.os.DeadObjectException
W/System.err( 6412): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6412): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6412): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6412): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6412): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6412): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6412): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6412): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6412): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6412): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6412): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6412): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6412): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6412): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6412): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  978): failed to open /acct/uid_10089/pid_6551/cgroup.procs: No such file or directory
,W/ActivityManager(  978): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  978): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6727 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/LgeMiscReceiver( 3157): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3157): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3157): networkInfo.isConnected() = false
D/MobileConnectivityChangeReceiver( 6569): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 6569): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 3229): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3229): DownloadService onCreate
,I/DownloadManager( 3229): in removeSpuriousFiles
I/NotificationManager( 3229): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3229): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@30b85d44 on behalf of 3229
I/DownloadManager( 3229): in trimDatabase
V/DownloadManager( 3229): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@11829e2d on behalf of 3229
D/UEI.SmartControl( 6727): Quickset Services start...
I/UEI.SmartControl( 6727): Manufacture = LGE
D/UEI.SmartControl( 6727): File observer start...
E/UEI.SmartControl( 6727): IR Port is disabled: false
D/UEI.SmartControl( 6727): Starting file observer...
D/UEI.SmartControl( 6727): Extracting JNI libs...
I/ActivityManager(  978): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6757 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
D/UEI.SmartControl( 6727): --- this system supports 32-bit or 64-bit only
,D/UEI.SmartControl( 6727): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6727): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6727): --- Extracting JNI libs: libqs_armeabi-v7a.zip
V/DownloadManager( 3229): DownloadService onStartCommand
,V/DownloadManager( 3229): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@308009b0 on behalf of 3229
I/UEI.SmartControl( 6727): --- Selecting new region: 2
I/UEI.SmartControl( 6727): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6727): Platform has CIR...
D/UEI.SmartControl( 6727): NO CIR support, need to check package...
I/UEI.SmartControl( 6727): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6727): QS Service created
,E/UEI.SmartControl( 6727): QS start get config
,V/DownloadManager( 3229): DownloadService onDestroy
,I/ActivityManager(  978): Killing 6392:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 6727): Loading JNI Libs...
,D/UEI.SmartControl( 6727):  configuring local db...
W/libprocessgroup(  978): failed to open /acct/uid_1000/pid_6392/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2645): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:15:52
D/UpdateThreadPoolManager( 2645): 2 : This is isUpdating : false
D/WeatherAncestor( 2645): connectivity changed - connection : true
D/Weather_cast( 2645): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2645): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:15:52
D/WeatherService( 2645): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  978): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6777 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  978): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2645): 2 : Utils getTopActivity com.lge.launcher2 / true
I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 20.722ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.365ms
,D/WeatherService( 2645): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2645): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/UEI.SmartControl( 6727):  ---- Has DB8: true
D/UEI.SmartControl( 6727): QS start statue = true Error code = 0
D/UEI.SmartControl( 6727): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 6727): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 28.028ms
D/UEI.SmartControl( 6727): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6727): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6727): IrrcClient ++ 
D/irrcClient( 6727): getIrrcService ++ 
,D/irrcClient( 6727): getIrrcService -- 
D/irrcClient( 6727): IrrcClient -- 
W/irrc_jni( 6727): IRRCPlayer_nativeInit -- 
W/ResourcesManager( 6777): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6727): Services init done
D/UEI.SmartControl( 6727): QS Service init finished
,D/UEI.SmartControl( 6727): QS Service version name: 0.1.73
I/UEI.SmartControl( 6727): Device manager: loading config....
D/UEI.SmartControl( 6727): QS Service version code: 1073
D/UEI.SmartControl( 6727): Service requested: Control
D/UEI.SmartControl( 6727): Config is loaded...
D/UEI.SmartControl( 6727):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6727): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6727): Request IControl service: devices are loaded...
I/ActivityManager(  978): Killing 6412:com.lge.qremote/u0a106 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 6727): Internal service binding...
W/libprocessgroup(  978): failed to open /acct/uid_10106/pid_6412/cgroup.procs: No such file or directory
,I/Babel_SMS( 6777): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6777): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6777): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6777): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6777): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6777): MmsConfig.loadFromResources
E/Babel_SMS( 6777): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6777): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 6777): CheckpointMarkThreadRoots callback created = 0xb042d810
,D/SensorManager( 6777): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6777): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6777): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6777): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6777): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6777): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6777): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6777): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6777): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6777): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6777): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6777): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6777): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6777): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6777): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6777): found sensor: Motion Accel, handle=46
I/art     ( 6777): CheckpointMarkThreadRoots callback created = 0xb042d800
,I/CheckinService( 5627): Done disabling old GoogleServicesFramework version
,W/Settings( 6777): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6777): startup - clean
I/Babel   ( 6777): deleted: false for 0
,I/ActivityManager(  978): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6816 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/AudioCapabilities( 6777): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6777): Unsupported mime audio/adpcm
W/AudioCapabilities( 6777): Unsupported mime audio/g726
W/AudioCapabilities( 6777): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6777): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6777): Unsupported mime video/mjpg
W/VideoCapabilities( 6777): Unsupported mime video/theora
,W/AudioCapabilities( 6777): Unsupported mime audio/evrc
,W/AudioCapabilities( 6777): Unsupported mime audio/qcelp
W/VideoCapabilities( 6777): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6777): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6777): Unsupported mime audio/qcelp
W/AudioCapabilities( 6777): Unsupported mime audio/evrc
W/VideoCapabilities( 6777): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6777): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6777): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6777): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6777): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6777): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 6777): onServiceConnected
W/Babel   ( 6777): Attempted to change video mute state without an active call.
,I/NotificationManager( 6777): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 6777): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6777): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6777): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6777): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  282): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  282): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  282): res_queryN name = xxxxx succeed
I/System.out( 6777): propertyValue:false
I/jxcore-log( 5536): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNativeLayer.js
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
I/jxcore-log( 5536): 
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6816): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6816): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6816): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6816): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 6816): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 6816):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 6816):   adb logcat -s GAv4
W/GAv4    ( 6816): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 6777): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  978): Killing 6586:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/GAv4    ( 6816): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 6816): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  978): failed to open /acct/uid_10014/pid_6586/cgroup.procs: No such file or directory
,I/jxcore-log( 5536): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationManager.js
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
I/jxcore-log( 5536): 
I/WebViewFactory( 6816): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 6816): Time to load native libraries: 2 ms (timestamps 6500-6502)
I/LibraryLoader( 6816): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 6816): Binding Chromium to main looper Looper (main, tid 1) {220f9f74}
,I/LibraryLoader( 6816): Expected native library version number "",actual native library version number ""
I/chromium( 6816): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 6816): Initializing chromium process, singleProcess=true
,W/art     ( 6816): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 6816): ApplicationContext is null in ApplicationStatus
W/chromium( 6816): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 6816): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 6816): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 6816): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6816): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6816): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6816): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6816): Remote Branch: 
I/Adreno-EGL( 6816): Local Patches: 
I/Adreno-EGL( 6816): Reconstruct Branch: 
V/AudioPolicyService(  287): registerClient() client 0xb551c920, uid 10079
,W/AudioManagerAndroid( 6816): Requires BLUETOOTH permission
,I/NSApplication( 6816): Starting up...
I/ActivityManager(  978): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6879 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  978): Killing 6609:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  978): failed to open /acct/uid_10081/pid_6609/cgroup.procs: No such file or directory
,I/ActivityManager(  978): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6898 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  978): Killing 6648:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  978): failed to open /acct/uid_10021/pid_6648/cgroup.procs: No such file or directory
,W/ResourcesManager( 6898): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/jxcore-log( 5536): Test app app.js loaded
I/jxcore-log( 5536): 
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@184c386c added. We now have 1 listener(s)
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
I/jxcore-log( 5536): BLE advertisement is not supported: Bluetooth LE advertising is not supported
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): TAP version 13
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # #generatePreambleAndBeacons null ECDH for local device
I/jxcore-log( 5536): 
I/chromium( 5536): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/jxcore-log( 5536): ok 1 publicKeysToNotify cannot be null
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # #generatePreambleAndBeacons null ECDH for local device
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 2 ecdhForLocalDevice cannot be null
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # #generatePreambleAndBeacons expiration out of range lower
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 3 secondsUntilExpiration out of range.
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # #generatePreambleAndBeacons expiration out of range upper
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 4 secondsUntilExpiration out of range.
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # #generatePreambleAndBeacons empty keys to notify
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 5 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # #generatePreambleAndBeacons multiple keys to notify
I/jxcore-log( 5536): 
,D/NetworkLogImpl( 5627): Loaded NetworkSpeedPredictor
I/iu.SyncManager( 5627): SYNC; picasa accounts
I/iu.Environment( 5627): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/ActivityManager(  978): Killing 6680:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/iu.UploadsManager( 5627): num queued entries: 0
I/iu.UploadsManager( 5627): num updated entries: 0
,I/iu.SyncManager( 5627): NEXT; no task
I/jxcore-log( 5536): ok 6 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 7 should be equal
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 8 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 9 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
I/jxcore-log( 5536): 
W/libprocessgroup(  978): failed to open /acct/uid_1000/pid_6680/cgroup.procs: No such file or directory
,I/jxcore-log( 5536): ok 10 should throw
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # #parseBeacons invalid expiration in beaconStreamWithPreAmble
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 11 Preamble expiration must be a 64 bit integer
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # #parseBeacons expiration out of range lower
I/jxcore-log( 5536): 
I/ActivityManager(  978): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6934 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/jxcore-log( 5536): ok 12 Expiration out of range
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # #parseBeacons expiration out of range lower
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 13 Expiration out of range
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # #parseBeacons no beacons returns null
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 14 should be equal
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 15 Malformed encrypted beacon key ID
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # #parseBeacons addressBookCallback fails decrypt
I/jxcore-log( 5536): 
I/MusicStore( 6934): Database version: 120
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6934): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 6934): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6934): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/jxcore-log( 5536): ok 16 should be equal
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
I/jxcore-log( 5536): # #parseBeacons addressBookCallback returns no matches
I/jxcore-log( 5536): 
W/ResourcesManager( 6934): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6934): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 6934): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6934): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6934): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2a30932f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6934): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6934): GMSCore installation verified
,I/ConfigStore( 6934): Config Database version: 1
,I/MediaRouter( 6934): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 6934): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 6934): type=WIFI subType= reason=null isConnected=true
,I/jxcore-log( 5536): ok 17 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 18 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # #parseBeacons addressBookCallback returns public key
I/jxcore-log( 5536): 
,I/NetworkMonitor( 6934): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  978): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6969 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 6934): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6934): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  978): Killing 6702:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ResourcesManager( 6969): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6969): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6969): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/jxcore-log( 5536): ok 19 should be equal
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 20 (unnamed assert)
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # #parseBeacons with beacons both for and not for the user
I/jxcore-log( 5536): 
W/libprocessgroup(  978): failed to open /acct/uid_10011/pid_6702/cgroup.procs: No such file or directory
,I/LGEmail ( 6969): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/NotificationManager( 6934): com.google.android.music: cancel(1061) by com.google.android.music
,D/LGEmail ( 6969): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/jxcore-log( 5536): ok 21 (unnamed assert)
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,D/eas_req ( 6969): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  978): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=6993 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 6969): JNI_OnLoad()
,I/HubEmail( 6969): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6969): registerNatives()
I/HubEmail( 6969): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 6969): registerNativeMethods()
,I/HubEmail( 6969): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 6969): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
W/Settings( 6969): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  978): Killing 6569:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  978): failed to open /acct/uid_10038/pid_6569/cgroup.procs: No such file or directory
,D/LGDMClient( 6993): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 6993): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 6993): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 6993): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 6993): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 6993): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/LGDMClient( 6993): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 6993): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/ActivityManager(  978): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7017 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 6993): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 6993): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 6993): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 6993): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 6993): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 6993): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  978): Killing 6727:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  978): failed to open /acct/uid_10089/pid_6727/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7017): onCreate
,W/AppUp4:DB( 7017):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7017):  setFingerPrint start
I/AppUp4:DB( 7017):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7017):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7017):  SDK version = 0
I/AppUp4:DB( 7017):  beforefinger == newfinger no write in DB
,I/art     (  978): Explicit concurrent mark sweep GC freed 19882(963KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.142ms total 157.394ms
,D/AppUp4:AppBoxApplication( 7017): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7017): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7017): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7017): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7017): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7017): onReceive
I/AppUp4:CustModeStarterReceiver( 7017): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7017): Context : android.app.ReceiverRestrictedContext@3c340d23
D/AppUp4:CustFacade( 7017): isCustomizationCompleted : false
D/AppUp4:CustFacade( 7017): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7017): begin check event
I/AppUp4:CustModeStarterReceiver( 7017): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7017): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7017): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7017): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7017): handleAsyncCustNotification do not startCustService
I/ActivityManager(  978): Killing 6757:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  978): failed to open /acct/uid_10051/pid_6757/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3157): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3157): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3157): networkInfo.isConnected() = false
I/ActivityManager(  978): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7039 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 7039): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 7039): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 7039): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  978): Killing 6777:com.google.android.talk/u0a61 (adj 15): empty #11
D/PhoneMonitor( 7039): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7039): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7039): [parse] Load xml
V/TelephonyAutoProfiling( 7039): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 7039): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 7039): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  978): failed to open /acct/uid_10061/pid_6777/cgroup.procs: No such file or directory
,V/DownloadManager( 3229): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3229): DownloadService onCreate
I/DownloadManager( 3229): in removeSpuriousFiles
V/DownloadManager( 3229): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,I/NotificationManager( 3229): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@3f93efae on behalf of 3229
I/DownloadManager( 3229): in trimDatabase
V/DownloadManager( 3229): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@3398414f on behalf of 3229
I/ActivityManager(  978): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7061 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3229): DownloadService onStartCommand
V/DownloadManager( 3229): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@153358ba on behalf of 3229
I/CheckinService( 5627): Checkin interval check for package: unspecified last checkin: 1455056124705 min interval config: 0 actual interval: 32798
I/CheckinService( 5627): Checking schedule, now: 1455056157521 next: 1455056154664
I/CheckinService( 5627): active receiver: enabled
,I/CheckinService( 5627): Preparing to send checkin request
V/DownloadManager( 3229): DownloadService onDestroy
I/EventLogService( 5627): Accumulating logs since 1455056116528
D/WeatherAncestor( 2645): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:15:57
,D/UpdateThreadPoolManager( 2645): 2 : This is isUpdating : false
D/WeatherAncestor( 2645): connectivity changed - connection : true
D/Weather_cast( 2645): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2645): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:15:57
D/WeatherService( 2645): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/ActivityManager(  978): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7090 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  978): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2645): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2645): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2645): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,V/AlarmManager(  978): RTC_WAKEUP set : Alarm{7a04df7 type 0 when 1455056154664 com.google.android.gms} when 1455056154664
,I/ActivityManager(  978): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=7107 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/AlarmManager(  978): RTC_WAKEUP set : Alarm{1b0ca464 type 0 when 1455056157653 com.android.vending} when 1455056157653
I/art     (  312): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 353us total 23.484ms
,W/ResourcesManager( 7090): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 336us total 24.725ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 304us total 22.157ms
,I/CheckinRequestBuilder( 5627): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 5627): Failed to find provider info for com.google.android.wearable.settings
,I/Babel_SMS( 7090): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 7090): MmsConfig.loadMmsSettings
I/Babel_SMS( 7090): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/Babel_SMS( 7090): MmsConfig.loadFromDatabase
D/Finsky  ( 7107): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/Babel_SMS( 7090): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7090): MmsConfig.loadFromResources
E/Babel_SMS( 7090): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7090): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/SensorManager( 7090): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7090): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7090): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7090): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7090): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7090): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7090): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7090): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7090): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7090): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7090): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7090): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7090): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7090): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7090): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7090): found sensor: Motion Accel, handle=46
,W/Settings( 7090): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 7090): startup - clean
,I/Babel   ( 7090): deleted: false for 0
,I/art     ( 7090): CheckpointMarkThreadRoots callback created = 0xb042d8c0
I/art     ( 7090): CheckpointMarkThreadRoots callback created = 0xb042d890
,I/ActivityManager(  978): Process com.google.android.apps.magazines (pid 6816) has died
,D/Finsky  ( 7107): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/ActivityManager(  978): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7160 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/Settings( 7107): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7107): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7107): com.android.vending: cancel(-1050172287) by com.android.vending
,I/ActivityManager(  978): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7177 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/AudioCapabilities( 7090): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7090): Unsupported mime audio/adpcm
W/AudioCapabilities( 7090): Unsupported mime audio/g726
W/AudioCapabilities( 7090): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7090): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7090): Unsupported mime video/mjpg
,W/VideoCapabilities( 7090): Unsupported mime video/theora
D/Ads     ( 7107): Skipping gmscore version check
D/Finsky  ( 7107): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7107): [1] Libraries$2.run: Finished loading 1 libraries.
W/ResourcesManager( 7177): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7177): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/DownloadManager( 3229): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,W/AudioCapabilities( 7090): Unsupported mime audio/evrc
V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@2ff5ec8 on behalf of 7107
W/AudioCapabilities( 7090): Unsupported mime audio/qcelp
W/VideoCapabilities( 7090): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 7090): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 7090): Unsupported mime audio/qcelp
W/AudioCapabilities( 7090): Unsupported mime audio/evrc
W/VideoCapabilities( 7090): Unsupported mime video/mp4v-esdp
,D/Finsky  ( 7107): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7160): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/MultiDex( 7177): VM with version 2.1.0 has multidex support
I/MultiDex( 7177): install
I/MultiDex( 7177): VM has multidex support, MultiDex support library is disabled.
D/Finsky  ( 7107): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/VideoCapabilities( 7090): Unsupported profile 4 for video/mp4v-es
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7160): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 7160): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7160):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7160):   adb logcat -s GAv4
W/VideoCapabilities( 7090): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7090): Unrecognized profile 2130706433 for video/avc
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7160): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,W/VideoCapabilities( 7090): Unrecognized profile 2130706433 for video/avc
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7160): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/VideoCapabilities( 7090): Unrecognized profile 2130706433 for video/avc
W/GAv4    ( 7160): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/vclib   ( 7090): onServiceConnected
W/Babel   ( 7090): Attempted to change video mute state without an active call.
V/JNIHelp ( 7177): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/libc-netbsd( 7090): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7090): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7090): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7090): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  282): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  282): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  282): res_queryN name = xxxxx succeed
I/System.out( 7090): propertyValue:false
I/NotificationManager( 7090): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/GAv4    ( 7160): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 7160): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/Babel   ( 7090): connection state changed from UNKNOWN to CONNECTED
W/ActivityThread( 7177): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 7177): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@30b85d44: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7177): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 7177): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 7177): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 7177): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 7177): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/Finsky  ( 7107): [900] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 7107): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/NativeLibraryUtils( 7177): Install completed successfully. count=14 extracted=0
,I/WebViewFactory( 7160): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/art     ( 3941): Explicit concurrent mark sweep GC freed 2186(80KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 441us total 27.953ms
D/WVCdm   (  287): Instantiating CDM.
,I/WVCdm   (  287): CdmEngine::OpenSession
I/WVCdm   (  287): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  287): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  287): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  287): L1 library not specified. Falling Back to L3
I/WVCdm   (  287): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  287): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  287): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  287): CdmEngine::GenerateKeyRequest
D/WVCdm   (  287): PrepareKeyRequest: nonce=3993314765
I/LibraryLoader( 7160): Time to load native libraries: 2 ms (timestamps 1608-1610)
I/LibraryLoader( 7160): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 7160): Binding Chromium to main looper Looper (main, tid 1) {220f9f74}
I/LibraryLoader( 7160): Expected native library version number "",actual native library version number ""
I/chromium( 7160): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 7160): Initializing chromium process, singleProcess=true
,W/art     ( 7160): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7160): ApplicationContext is null in ApplicationStatus
W/chromium( 7160): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7160): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7160): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7160): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7160): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7160): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7160): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7160): Remote Branch: 
I/Adreno-EGL( 7160): Local Patches: 
I/Adreno-EGL( 7160): Reconstruct Branch: 
V/AudioPolicyService(  287): registerClient() client 0xb4027180, uid 10079
,W/AudioManagerAndroid( 7160): Requires BLUETOOTH permission
I/ActivityManager(  978): Process com.google.android.music:main (pid 6934) has died
I/NSApplication( 7160): Starting up...
,I/ActivityManager(  978): Killing 6969:com.lge.email/u0a21 (adj 15): empty #11
,I/art     ( 7177): CheckpointMarkThreadRoots callback created = 0xb059b360
,W/libprocessgroup(  978): failed to open /acct/uid_10021/pid_6969/cgroup.procs: No such file or directory
I/art     ( 7177): CheckpointMarkThreadRoots callback created = 0xb059b340
,I/ActivityManager(  978): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=7246 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 7246): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 7246): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2d07c5a1
,D/CalendarProvider2( 7246): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 7246): Created com.android.providers.calendar.CalendarAlarmManager@d5af652(com.android.providers.calendar.CalendarProvider2@2d07c5a1)
D/CalendarProviderBroadcastReceiver( 7246): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 7246): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 7246): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 7246): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 7246): [getOrCreateCalendarAlarmManager]
I/ActivityManager(  978): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7266 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/CalendarProvider2( 7246): [IntentService] Release Lock
,D/CalendarProvider2( 7246): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  978): Killing 6993:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/ResourcesManager( 7266): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/dex2oat ( 7283): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,W/libprocessgroup(  978): failed to open /acct/uid_1000/pid_6993/cgroup.procs: No such file or directory
I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
,D/WeatherService( 2645): 2 : TimeTick Intent has been received, Time(hour:min:sec) 23:16:0
,D/WeatherService( 2645): 2 : TimeTick Intent And Screen On
D/WeatherService( 2645): 2 : SDK version : 21
W/ActivityManager(  978): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2645): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2645): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2645): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2645): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2645): 2 : This is isUpdating : false
D/WeatherService( 2645): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2645): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2645): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2645): 2 : Fixed theme : optimus
D/WeatherReflect( 2645): 2 : Map key string is -2
,D/BluetoothManagerService(  978): Message: 20
D/BluetoothManagerService(  978): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@20d230cb:true
D/lim     ( 2645): 2 : time = 23:16
I/WeatherReflect( 2645): Model Name : LG-D722
,D/WeatherTheme( 2645): 2 : Different view - status_min_formatted : 15 != 16
D/WeatherTheme( 2645): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
D/WeatherReflect( 2645): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
I/dex2oat ( 7283): dex2oat took 152.723ms (threads: 4)
,D/Theme   ( 2645): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2645): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2645): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2645): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/Adreno-EGL( 7177): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7177): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7177): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7177): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7177): Remote Branch: 
I/Adreno-EGL( 7177): Local Patches: 
I/Adreno-EGL( 7177): Reconstruct Branch: 
,D/Weather4x2_optimus( 2645): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2645): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2645): forecast size is 0
D/Theme   ( 2645): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2645): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2645): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2645): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2645): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2645): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2645): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2645): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2645): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2645): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2645): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2645): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2645): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2645): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2645): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2645): url is : null
D/Theme   ( 2645): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2645): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2645): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/WeatherAncestor( 2645): 2 : update view, appWidgetId: 2
D/WeatherService( 2645): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 23:16:0
I/ActivityManager(  978): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7290 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7266): Create singleton instance
,D/UEI.SmartControl( 7290): Quickset Services start...
,I/UEI.SmartControl( 7290): Manufacture = LGE
D/UEI.SmartControl( 7290): File observer start...
E/UEI.SmartControl( 7290): IR Port is disabled: false
D/UEI.SmartControl( 7290): Starting file observer...
D/UEI.SmartControl( 7290): Extracting JNI libs...
D/UEI.SmartControl( 7290): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7266): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7290): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7290): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7290): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 7290): --- Selecting new region: 2
I/UEI.SmartControl( 7290): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7290): Platform has CIR...
D/UEI.SmartControl( 7290): NO CIR support, need to check package...
I/UEI.SmartControl( 7290): Model: LG-D722 uses JNI
I/ActivityManager(  978): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7310 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/UEI.SmartControl( 7290): QS Service created
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/art     (  978): Explicit concurrent mark sweep GC freed 24129(1129KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.430ms total 167.415ms
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,E/UEI.SmartControl( 7290): QS start get config
,I/MusicStore( 7310): Database version: 120
D/UEI.SmartControl( 7290): Loading JNI Libs...
,D/UEI.SmartControl( 7290):  configuring local db...
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7310): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/Adreno-EGL( 7177): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7177): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7177): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7177): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7177): Remote Branch: 
I/Adreno-EGL( 7177): Local Patches: 
I/Adreno-EGL( 7177): Reconstruct Branch: 
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Adreno-EGL( 7177): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7177): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7177): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7177): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7177): Remote Branch: 
I/Adreno-EGL( 7177): Local Patches: 
I/Adreno-EGL( 7177): Reconstruct Branch: 
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 7310): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7310): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/WVCdm   (  287): CdmEngine::OpenSession
,W/ResourcesManager( 7310): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 7310): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 7310): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/UEI.SmartControl( 7290):  ---- Has DB8: true
,D/UEI.SmartControl( 7290): QS start statue = true Error code = 0
,D/UEI.SmartControl( 7290): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7290): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7290): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7290): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 7290): IrrcClient ++ 
D/irrcClient( 7290): getIrrcService ++ 
D/irrcClient( 7290): getIrrcService -- 
D/irrcClient( 7290): IrrcClient -- 
W/irrc_jni( 7290): IRRCPlayer_nativeInit -- 
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
D/UEI.SmartControl( 7290): Services init done
D/UEI.SmartControl( 7290): QS Service init finished
D/UEI.SmartControl( 7290): QS Service version name: 0.1.73
D/UEI.SmartControl( 7290): QS Service version code: 1073
,D/UEI.SmartControl( 7290): Service requested: Control
I/UEI.SmartControl( 7290): Device manager: loading config....
W/ActivityThread( 7310): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 7310): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2a30932f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 7310): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 7310): GMSCore installation verified
D/UEI.SmartControl( 7290): Config is loaded...
I/ConfigStore( 7310): Config Database version: 1
,D/UEI.SmartControl( 7290): Request IControl service: devices are loaded...
D/UEI.SmartControl( 7290): Internal service binding...
D/UEI.SmartControl( 7290): -----IControl: 11
D/UEI.SmartControl( 7290):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7290): Notify AllClients services are ready: 0
D/UEI.SmartControl( 7290): Caller: com.lge.qremote
D/UEI.SmartControl( 7290): ------------ IControl registerCallback...
I/UEI.SmartControl( 7290): Registering callback...
D/UEI.SmartControl( 7290): -----IControl: 19
D/UEI.SmartControl( 7290): Caller: com.lge.qremote
I/UEI.SmartControl( 7290): Registering Services Ready callback...
I/UEI.SmartControl( 7290): Notify client services are ready...
D/UEI.SmartControl( 7290): -----IControl: 8
D/UEI.SmartControl( 7290): Caller: com.lge.qremote
I/ActivityManager(  978): Process com.lge.appbox.client (pid 7017) has died
,I/MediaRouter( 7310): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 7310): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 7310): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  978): Killing 7039:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/WVCdm   (  287): CdmEngine::CloseSession
,W/libprocessgroup(  978): failed to open /acct/uid_10038/pid_7039/cgroup.procs: No such file or directory
,I/NetworkMonitor( 7310): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  978): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7347 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/WVCdm   (  287): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  287): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  287): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  287): CdmEngine::GenerateKeyRequest
D/WVCdm   (  287): PrepareKeyRequest: nonce=3258470133
,I/GHttpClientFactory( 7310): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 7310): Using platform SSLCertificateSocketFactory
,I/ActivityManager(  978): Killing 7061:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/ResourcesManager( 7347): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7347): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7347): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  978): failed to open /acct/uid_10051/pid_7061/cgroup.procs: No such file or directory
,I/NotificationManager( 7310): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 7347): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7347): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 7347): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/ActivityManager(  978): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=7373 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/HubEmail( 7347): JNI_OnLoad()
I/HubEmail( 7347): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7347): registerNatives()
I/HubEmail( 7347): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 7347): registerNativeMethods()
I/HubEmail( 7347): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 7347): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  978): Killing 7090:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  978): failed to open /acct/uid_10061/pid_7090/cgroup.procs: No such file or directory
W/Settings( 7347): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 7373): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 7373): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 7373): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 7373): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 7373): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 7373): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,D/LGDMClient( 7373): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 7373): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  978): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7403 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 7373): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 7373): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 7373): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 7373): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 7373): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 7373): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  978): Killing 7160:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  978): tsOffsetIs: Apps: 114560349075; DSPS: 3852352; Offset : -3013593944
W/libprocessgroup(  978): failed to open /acct/uid_10079/pid_7160/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 7403): onCreate
,W/AppUp4:DB( 7403):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 7403):  setFingerPrint start
I/AppUp4:DB( 7403):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 7403):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7403):  SDK version = 0
I/AppUp4:DB( 7403):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 7403): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 7403): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 7403): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 7403): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 7403): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 7403): onReceive
I/AppUp4:CustModeStarterReceiver( 7403): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 7403): Context : android.app.ReceiverRestrictedContext@3c340d23
D/AppUp4:CustFacade( 7403): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7403): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 7403): begin check event
I/AppUp4:CustModeStarterReceiver( 7403): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 7403): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 7403): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 7403): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 7403): handleAsyncCustNotification do not startCustService
I/ActivityManager(  978): Killing 7107:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  978): failed to open /acct/uid_10036/pid_7107/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3157): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3157): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3157): networkInfo.isConnected() = true
,D/PhoneState( 3157): setPdpRejectCasuse : false
I/ActivityManager(  978): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7426 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/MusicWidget( 2569): mDelayedStopHandler : unbind
,I/MusicBrowser( 2673): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2673): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2673): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/MusicBrowser( 2673): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2673): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2673): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2673): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2673): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  978):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@dd324ecom.lge.music.MediaPlaybackService$6@39d65f6f
,D/MusicBrowser( 2673): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2673): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2673): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2673): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2673): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@130587f
I/MusicBrowser( 2673): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2673): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2673): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2673): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2673): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2673): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2673): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2673): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2673): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2673): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2673): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2673): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2673): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2673): reset
,V/MediaPlayer[Native]( 2673): setListener
,D/PhoneMonitor( 7426): Register our PhoneStateListener
,V/MediaPlayer[Native]( 2673): disconnect
V/MediaPlayer[Native]( 2673): destructor
V/AudioFlinger(  287): releasing 18 from 2673 for -1
V/AudioFlinger(  287):  decremented refcount to 0
V/AudioFlinger(  287): purging stale effects
V/MediaPlayer[Native]( 2673): disconnect
D/MusicBrowser( 2673): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
D/MobileConnectivityChangeReceiver( 7426): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 7426): onReceive CONNECTIVITY_CHANGE networkType=1
I/SmartShareClient( 2673): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2673): [SmartShareManagerClient] smartshare client enabled
I/ActivityManager(  978): Killing 6879:com.android.chrome/u0a48 (adj 15): empty #11
I/MusicBrowser( 2673): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2673): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2673): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2673): [SmartShareManagerClient] unregisterListener: 808756348
W/SmartShareClient( 2673): [SmartShareManagerClient] unregisterListener invalid listener: 808756348
D/PhoneMonitor( 7426): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 7426): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 7426): [parse] Load xml
I/SmartShareClient( 2673): [SmartShareManagerClient] terminate service: 2673/MediaPlaybackService/1052383965
V/TelephonyAutoProfiling( 7426): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 7426): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,E/HomeCloudIF( 2673): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2673): [SmartShareManagerClient] unbindService context:android.app.Application@4700105
D/PhoneMonitor( 7426): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  978): failed to open /acct/uid_10048/pid_6879/cgroup.procs: No such file or directory
,V/DownloadManager( 3229): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3229): DownloadService onCreate
I/NotificationManager( 3229): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3229): in removeSpuriousFiles
V/DownloadManager( 3229): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/CloudHub( 2673): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@2c4c7b61 on behalf of 3229
V/CloudHub( 2673): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/DownloadManager( 3229): in trimDatabase
V/DownloadManager( 3229): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/CloudHub( 2673): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2673): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@16d50b47 on behalf of 3229
D/MusicBrowser( 2673): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  978): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7458 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3229): DownloadService onStartCommand
I/CloudHub( 2673): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29963
I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 21.547ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.336ms
,V/DownloadManager( 3229): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/ActivityManager(  978): Killing 6898:com.google.android.apps.plus/u0a86 (adj 15): empty #11
V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@af46c9d on behalf of 3229
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 22.874ms
,W/libprocessgroup(  978): failed to open /acct/uid_10086/pid_6898/cgroup.procs: No such file or directory
,I/CheckinService( 5627): Checkin interval check for package: unspecified last checkin: 1455056124705 min interval config: 0 actual interval: 38517
V/DownloadManager( 3229): DownloadService onDestroy
I/ActivityManager(  978): Killing 7246:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  978): failed to open /acct/uid_10014/pid_7246/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2645): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:16:3
D/UpdateThreadPoolManager( 2645): 2 : This is isUpdating : false
D/WeatherAncestor( 2645): connectivity changed - connection : true
D/Weather_cast( 2645): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2645): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:16:3
D/WeatherService( 2645): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/ActivityManager(  978): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7476 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  978): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2645): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2645): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2645): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 7476): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/WVCdm   (  287): CdmEngine::CloseSession
I/WVCdm   (  287): L3 Terminate.
,I/Babel_SMS( 7476): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 7476): MmsConfig.loadMmsSettings
I/Babel_SMS( 7476): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 7476): MmsConfig.loadFromDatabase
,E/Babel_SMS( 7476): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 7476): MmsConfig.loadFromResources
E/Babel_SMS( 7476): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 7476): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 7476): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 7476): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 7476): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 7476): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 7476): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 7476): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 7476): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 7476): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 7476): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 7476): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 7476): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 7476): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 7476): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 7476): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 7476): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 7476): found sensor: Motion Accel, handle=46
,W/Settings( 7476): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 7476): startup - clean
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/Babel   ( 7476): deleted: false for 0
I/CheckinRequestBuilder( 5627): Classify the device as Phone.
I/art     ( 7476): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,I/ActivityManager(  978): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7513 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 7476): CheckpointMarkThreadRoots callback created = 0xb042d870
W/AudioCapabilities( 7476): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 7476): Unsupported mime audio/adpcm
W/AudioCapabilities( 7476): Unsupported mime audio/g726
W/AudioCapabilities( 7476): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 7476): Unsupported mime audio/wma-voice
W/VideoCapabilities( 7476): Unsupported mime video/mjpg
W/VideoCapabilities( 7476): Unsupported mime video/theora
,W/AudioCapabilities( 7476): Unsupported mime audio/evrc
,W/AudioCapabilities( 7476): Unsupported mime audio/qcelp
W/VideoCapabilities( 7476): Unrecognized profile 2130706433 for video/avc
D/libc-netbsd( 5627): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5627): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5627): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5627): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  282): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  282): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  282): res_queryN name = xxxxx succeed
I/System.out( 5627): propertyValue:false
W/AudioCapabilities( 7476): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 7476): Unsupported mime audio/qcelp
W/AudioCapabilities( 7476): Unsupported mime audio/evrc
,W/VideoCapabilities( 7476): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 7476): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 7476): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7476): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 7476): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 7476): Unrecognized profile 2130706433 for video/avc
D/libc-netbsd( 5627): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5627): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/vclib   ( 7476): onServiceConnected
W/Babel   ( 7476): Attempted to change video mute state without an active call.
,D/libc-netbsd( 7476): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7476): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7476): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7476): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  282): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  282): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
,D/libc-netbsd(  282): res_queryN name = xxxxx succeed
I/System.out( 7476): propertyValue:false
I/NotificationManager( 7476): com.google.android.talk: cancel(10436) by com.google.android.talk
I/GAv4    ( 7513): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 7513):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 7513):   adb logcat -s GAv4
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7513): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7513): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 7513): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
D/libc-netbsd( 5627): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5627): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/GAv4    ( 7513): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/libc-netbsd( 5627): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5627): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/ContextImpl( 7513): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/Babel   ( 7476): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  978): Killing 7266:com.lge.qremote/u0a106 (adj 15): empty #11
W/GAv4    ( 7513): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/CheckinTask( 5627): Sending checkin request (9815 bytes)
W/GAv4    ( 7513): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/libprocessgroup(  978): failed to open /acct/uid_10106/pid_7266/cgroup.procs: No such file or directory
,I/WebViewFactory( 7513): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 7513): Time to load native libraries: 1 ms (timestamps 6809-6810)
I/LibraryLoader( 7513): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 7513): Binding Chromium to main looper Looper (main, tid 1) {220f9f74}
I/LibraryLoader( 7513): Expected native library version number "",actual native library version number ""
I/chromium( 7513): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 7513): Initializing chromium process, singleProcess=true
,W/art     ( 7513): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 7513): ApplicationContext is null in ApplicationStatus
W/chromium( 7513): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 7513): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 7513): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 7513): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 7513): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 7513): Build Date: 03/02/15 Mon
I/Adreno-EGL( 7513): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 7513): Remote Branch: 
I/Adreno-EGL( 7513): Local Patches: 
I/Adreno-EGL( 7513): Reconstruct Branch: 
V/AudioPolicyService(  287): registerClient() client 0xb3830300, uid 10079
,W/AudioManagerAndroid( 7513): Requires BLUETOOTH permission
I/NSApplication( 7513): Starting up...
,I/CheckinRequestBuilder( 5627): Checkin reason type: 8 attempt count: 1
,I/ActivityManager(  978): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7580 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  978): Killing 7290:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,E/ActivityThread( 5627): Failed to find provider info for com.google.android.wearable.settings
,W/libprocessgroup(  978): failed to open /acct/uid_10089/pid_7290/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  978): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7599 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  978): Explicit concurrent mark sweep GC freed 15267(734KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.288ms total 189.956ms
,I/ActivityManager(  978): Killing 7310:com.google.android.music:main/u0a81 (adj 15): empty #11
W/ResourcesManager( 7599): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  978): failed to open /acct/uid_10081/pid_7310/cgroup.procs: No such file or directory
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 5627): Classify the device as Phone.
,I/CheckinTask( 5627): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 5627): Checking schedule, now: 1455056165197 next: 1455583414190
I/CheckinService( 5627): active receiver: disabled
,I/CheckinService( 5627): Checking schedule, now: 1455056165236 next: 1455583414190
I/CheckinService( 5627): active receiver: disabled
,D/CheckinService( 5627): Recording last checkin time for package unspecified as 1455056165248
,I/ActivityManager(  978): Killing 7373:com.lge.lgdmsclient/1000 (adj 15): empty #11
,I/ActivityManager(  978): Killing 7347:com.lge.email/u0a21 (adj 15): empty #12
,W/libprocessgroup(  978): failed to open /acct/uid_10021/pid_7347/cgroup.procs: No such file or directory
,W/libprocessgroup(  978): failed to open /acct/uid_1000/pid_7373/cgroup.procs: No such file or directory
I/ActivityManager(  978): Killing 7403:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  978): failed to open /acct/uid_10011/pid_7403/cgroup.procs: No such file or directory
,I/ActivityManager(  978): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=7626 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 7626): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  978): Message: 20
D/BluetoothManagerService(  978): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b685b6e:true
,D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
I/ActivityManager(  978): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7647 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 7626): Create singleton instance
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:16:05.702 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/UEI.SmartControl( 7647): Quickset Services start...
I/UEI.SmartControl( 7647): Manufacture = LGE
,D/UEI.SmartControl( 7647): File observer start...
E/UEI.SmartControl( 7647): IR Port is disabled: false
D/UEI.SmartControl( 7647): Starting file observer...
D/UEI.SmartControl( 7647): Extracting JNI libs...
D/UEI.SmartControl( 7647): --- this system supports 32-bit or 64-bit only
I/AudioManager( 7626): getMode name:com.lge.qremote
,D/UEI.SmartControl( 7647): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7647): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7647): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/UEI.SmartControl( 7647): --- Selecting new region: 2
I/UEI.SmartControl( 7647): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 7647): Platform has CIR...
,D/UEI.SmartControl( 7647): NO CIR support, need to check package...
I/UEI.SmartControl( 7647): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7647): QS Service created
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
E/UEI.SmartControl( 7647): QS start get config
D/UEI.SmartControl( 7647): Loading JNI Libs...
,D/UEI.SmartControl( 7647):  configuring local db...
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,E/MDM     ( 1732): [121] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 5627): Restart initialization of location
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  978): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=7675 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,D/UEI.SmartControl( 7647):  ---- Has DB8: true
,D/UEI.SmartControl( 7647): QS start statue = true Error code = 0
D/UEI.SmartControl( 7647): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7647): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7647): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 7647): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7647): IrrcClient ++ 
D/irrcClient( 7647): getIrrcService ++ 
D/irrcClient( 7647): getIrrcService -- 
D/irrcClient( 7647): IrrcClient -- 
W/irrc_jni( 7647): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 7647): Services init done
I/UEI.SmartControl( 7647): Device manager: loading config....
D/UEI.SmartControl( 7647): QS Service init finished
,D/UEI.SmartControl( 7647): QS Service version name: 0.1.73
D/UEI.SmartControl( 7647): Config is loaded...
D/UEI.SmartControl( 7647): QS Service version code: 1073
D/UEI.SmartControl( 7647): Service requested: Control
D/UEI.SmartControl( 7647): Internal service binding...
D/UEI.SmartControl( 7647): -----IControl: 11
D/UEI.SmartControl( 7647): Caller: com.lge.qremote
D/UEI.SmartControl( 7647): ------------ IControl registerCallback...
,I/UEI.SmartControl( 7647): Registering callback...
D/UEI.SmartControl( 7647): -----IControl: 19
D/UEI.SmartControl( 7647): Caller: com.lge.qremote
I/UEI.SmartControl( 7647): Registering Services Ready callback...
I/UEI.SmartControl( 7647): Notify client services are ready...
D/UEI.SmartControl( 7647): -----IControl: 8
D/UEI.SmartControl( 7647): Caller: com.lge.qremote
D/UEI.SmartControl( 7647):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 7647): Notify AllClients services are ready: 0
W/ActivityManager(  978): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 7675): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 7675): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  978): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 7675): Error finding the version of the Email provider.....
E/Gmail   ( 7675): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 7675): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 7675): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 7675): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 7675): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 7675): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 7675): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 7675): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 7675): We do not support migrating this version of the Email provider.
,I/Gmail   ( 7675): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  978): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver: pid=7715 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  978): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/ActivityManager(  978): Killing 2673:com.lge.music/u0a28 (adj 15): empty #11
,I/Gmail   ( 7675): Observing account changes for notifications
V/AudioFlinger(  287): 2673 died, releasing its sessions
V/AudioFlinger(  287):  pid 1750 @ 0
V/AudioFlinger(  287):  pid 3157 @ 1
V/AudioFlinger(  287):  pid 3157 @ 2
,W/ActivityManager(  978): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/libprocessgroup(  978): failed to open /acct/uid_10028/pid_2673/cgroup.procs: No such file or directory
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 7715): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/Gmail   ( 7675): notifyAccountChanged
,I/Gmail   ( 7675): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 7675): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7675): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 7675): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 7675): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 7675): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/Finsky  ( 7715): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
W/Settings( 7715): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 7715): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 7715): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3229): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@10cd14e3 on behalf of 7715
I/AudioManager( 7626): getMode name:com.lge.qremote
,D/Finsky  ( 7715): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 7715): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 7715): Skipping gmscore version check
D/Finsky  ( 7715): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/AudioManager( 7626): getMode name:com.lge.qremote
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/Finsky  ( 7715): [999] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7715): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinService( 5627): Checkin interval check for package: unspecified last checkin: 1455056165248 min interval config: 0 actual interval: 1727
E/MDM     ( 1732): [146] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/CheckinService( 5627): Checking schedule, now: 1455056166992 next: 1455583414190
I/CheckinService( 5627): active receiver: disabled
D/LocationInitializer( 5627): Restart initialization of location
I/NotificationManager(  978): android: cancelAsUser(2) by android
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/art     (  978): Explicit concurrent mark sweep GC freed 22910(1080KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.122ms total 160.464ms
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,I/AudioManager( 7626): getMode name:com.lge.qremote
I/AudioManager( 7626): getMode name:com.lge.qremote
W/ContextImpl( 3579): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,V/SetupWizard( 7426): Connected to Gservices successfully
,I/AudioManager( 7626): getMode name:com.lge.qremote
,D/libc-netbsd( 7715): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7715): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 7715): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 7715): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  282): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  282): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
I/AudioManager( 7626): getMode name:com.lge.qremote
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/libc-netbsd(  282): res_queryN name = xxxxx succeed
I/System.out( 7715): propertyValue:false
I/AudioManager( 7626): getMode name:com.lge.qremote
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/AudioManager( 7626): getMode name:com.lge.qremote
,I/AudioManager( 7626): getMode name:com.lge.qremote
I/AudioManager( 7626): getMode name:com.lge.qremote
I/AudioManager( 7626): getMode name:com.lge.qremote
,I/AudioManager( 7626): getMode name:com.lge.qremote
I/ActivityManager(  978): Killing 7458:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  978): failed to open /acct/uid_10051/pid_7458/cgroup.procs: No such file or directory
,I/[SystemUI]QPairHandler( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/InputReader(  978): Reconfiguring input devices.  changes=0x00000010
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  978): Handling package changes for user 0
,I/ActivityManager(  978): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7792 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/NotificationManager( 7476): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 7476): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 7476): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/AppUp4:AppBoxCP( 7792): onCreate
W/AppUp4:DB( 7792):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 7792):  setFingerPrint start
,I/AppUp4:DB( 7792):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 7792):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7792):  SDK version = 0
I/AppUp4:DB( 7792):  beforefinger == newfinger no write in DB
,V/JNIHelp ( 7476): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/NotificationService(  978): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  978): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  978): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/System  ( 7476): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 7476): Installed default security provider GmsCore_OpenSSL
W/ResourcesManager(  978): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  978): Process com.google.android.apps.magazines (pid 7513) has died
,D/AppUp4:AppBoxApplication( 7792): AppBoxApplication onCreate()
I/BackupManagerService(  978): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/AppUp4:CustModeStarterReceiver( 7792): onReceive
,I/AppUp4:CustModeStarterReceiver( 7792): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
D/AppUp4:CustFacade( 7792): Context : android.app.ReceiverRestrictedContext@32421eb4
D/AppUp4:CustFacade( 7792): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 7792): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 7792): begin check event
I/AppUp4:CustModeStarterReceiver( 7792): Event For Nothing, skip.
I/ActivityManager(  978): Process com.android.vending (pid 7715) has died
,V/BackupManagerService(  978): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/BackupManagerService(  978): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@254fd676
,I/ActivityManager(  978): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7814 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourceType(  978): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/ResourcesManager( 7814): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7814): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 7814): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  978): applying state to connected service
,I/AppConfig( 7814): Total System Memory = 906309632
,I/GalleryUtils( 7814): Application Heap = 96 MB
I/AppConfig( 7814): App Tier : NOT_DEF
D/SystemHelper( 7814): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  978): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7837 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.093ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 22.155ms
W/ResourcesManager( 7837): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7837): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 7837): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 7837): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,W/ResourcesManager( 7837): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 20.752ms
I/ActivityManager(  978): Process com.google.android.apps.plus (pid 7599) has died
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:16:08.722 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/SystemConfig( 7837): BUILD Country: EU
I/SystemConfig( 7837): BUILD Operator: OPEN
,I/ActivityManager(  978): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7856 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 7837): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 7837): existFile = false
I/SystemConfig( 7837): canReadFile = false
I/SystemConfig( 7837): systemFeature RCS result false
D/SystemConfig( 7837): refreshRcsSupport() :false
,I/LockScreenSettings( 7856): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 7856): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 7856): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 7856): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 7856): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 7856): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  978): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7876 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  978): Killing 7580:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  978): failed to open /acct/uid_10048/pid_7580/cgroup.procs: No such file or directory
,W/ResourcesManager( 7876): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  978): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7901 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 55 ms] updated apps [took 55 ms] 
I/ActivityManager(  978): Killing 7426:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  978): failed to open /acct/uid_10038/pid_7426/cgroup.procs: No such file or directory
,D/Finsky  ( 7901): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 7901): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 7901): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 7901): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 7901): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3229): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,D/Finsky  ( 7901): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 7901): [1] Libraries$2.run: Finished loading 1 libraries.
V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@2e413ee0 on behalf of 7901
D/Ads     ( 7901): Skipping gmscore version check
I/ActivityManager(  978): Killing 7647:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 7626): android.os.DeadObjectException
,W/System.err( 7626): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7626): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7626): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 7626): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 7626): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7626): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7626): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7626): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7626): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7626): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7626): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7626): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7626): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7626): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7626): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 7626): android.os.DeadObjectException
W/System.err( 7626): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 7626): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 7626): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 7626): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 7626): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 7626): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 7626): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 7626): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 7626): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 7626): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 7626): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 7626): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 7626): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 7626): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 7626): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  978): failed to open /acct/uid_10089/pid_7647/cgroup.procs: No such file or directory
W/ActivityManager(  978): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,D/Finsky  ( 7901): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/ActivityManager(  978): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=7941 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/PackageBroadcastService( 5627): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 5627): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 5627): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 7901): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/UEI.SmartControl( 7941): Quickset Services start...
,I/UEI.SmartControl( 7941): Manufacture = LGE
,D/UEI.SmartControl( 7941): File observer start...
E/UEI.SmartControl( 7941): IR Port is disabled: false
D/UEI.SmartControl( 7941): Starting file observer...
D/UEI.SmartControl( 7941): Extracting JNI libs...
D/UEI.SmartControl( 7941): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 7941): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 7941): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 7941): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 7941): --- Selecting new region: 2
,I/UEI.SmartControl( 7941): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 7941): Platform has CIR...
D/UEI.SmartControl( 7941): NO CIR support, need to check package...
I/UEI.SmartControl( 7941): Model: LG-D722 uses JNI
D/UEI.SmartControl( 7941): QS Service created
E/UEI.SmartControl( 7941): QS start get config
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/UEI.SmartControl( 7941): Loading JNI Libs...
D/UEI.SmartControl( 7941):  configuring local db...
D/UEI.SmartControl( 7941):  ---- Has DB8: true
,D/UEI.SmartControl( 7941): QS start statue = true Error code = 0
D/UEI.SmartControl( 7941): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 7941): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 7941): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 7941): IRRCPlayer_nativeInit ++ 
D/irrcClient( 7941): IrrcClient ++ 
D/irrcClient( 7941): getIrrcService ++ 
,D/irrcClient( 7941): getIrrcService -- 
D/irrcClient( 7941): IrrcClient -- 
W/irrc_jni( 7941): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 7941): Services init done
I/UEI.SmartControl( 7941): Device manager: loading config....
D/UEI.SmartControl( 7941): QS Service init finished
,D/UEI.SmartControl( 7941): Config is loaded...
D/UEI.SmartControl( 7941): QS Service version name: 0.1.73
D/UEI.SmartControl( 7941): QS Service version code: 1073
D/UEI.SmartControl( 7941): Service requested: Control
I/ActivityManager(  978): Killing 7675:com.google.android.gm/u0a53 (adj 15): empty #11
D/UEI.SmartControl( 7941): -----IControl: 11
D/UEI.SmartControl( 7941): Caller: com.lge.qremote
D/UEI.SmartControl( 7941): ------------ IControl registerCallback...
I/UEI.SmartControl( 7941): Registering callback...
D/UEI.SmartControl( 7941): -----IControl: 19
,D/UEI.SmartControl( 7941): Caller: com.lge.qremote
I/UEI.SmartControl( 7941): Registering Services Ready callback...
I/UEI.SmartControl( 7941): Notify client services are ready...
D/UEI.SmartControl( 7941): -----IControl: 8
D/UEI.SmartControl( 7941): Caller: com.lge.qremote
D/UEI.SmartControl( 7941):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 7941): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 7941): Internal service binding...
W/libprocessgroup(  978): failed to open /acct/uid_10053/pid_7675/cgroup.procs: No such file or directory
I/AudioManager( 7626): getMode name:com.lge.qremote
,I/AudioManager( 7626): getMode name:com.lge.qremote
,I/AudioManager( 7626): getMode name:com.lge.qremote
I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/Icing   ( 5627): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Icing   ( 5627): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:16:11.742 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  978): Killing 7792:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  978): failed to open /acct/uid_10011/pid_7792/cgroup.procs: No such file or directory
,I/ActivityManager(  978): Killing 7476:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  978): failed to open /acct/uid_10061/pid_7476/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/charger_monitor(  488): init target 500000
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
,I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/charger_monitor(  488): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
,D/WifiController(  978): battery changed pluggedType: 2
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 7941): Internal timer expired: 1
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:16:17.769 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:16:20.781 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 134561242661; DSPS: 4507741; Offset : -3013585315
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:16:23.795 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  978): ELAPSED_WAKEUP set : Alarm{b2e0b74 type 2 when 148154 com.google.android.gms} when 148154
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/art     (  978): Explicit concurrent mark sweep GC freed 37110(1775KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.454ms total 164.957ms
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1732): Vacuum at: now=1455056196237 tag=VacuumService
,I/PowerManagerService(  978): ALS enabled for SRE
,D/PowerManagerServiceEx(  978): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (29069 ms ago)
D/qdlights(  978): set_light_backlight: 252
,D/qdlights(  978): set_light_backlight: 249
D/qdlights(  978): set_light_backlight: 246
,D/qdlights(  978): set_light_backlight: 242
,D/qdlights(  978): set_light_backlight: 239
,D/qdlights(  978): set_light_backlight: 236
,D/qdlights(  978): set_light_backlight: 232
,D/qdlights(  978): set_light_backlight: 229
,D/qdlights(  978): set_light_backlight: 226
,D/qdlights(  978): set_light_backlight: 222
,D/qdlights(  978): set_light_backlight: 219
,D/qdlights(  978): set_light_backlight: 216
,D/qdlights(  978): set_light_backlight: 212
,D/qdlights(  978): set_light_backlight: 209
,D/qdlights(  978): set_light_backlight: 206
,D/qdlights(  978): set_light_backlight: 202
,D/qdlights(  978): set_light_backlight: 199
,D/qdlights(  978): set_light_backlight: 196
,D/qdlights(  978): set_light_backlight: 192
,D/qdlights(  978): set_light_backlight: 189
,D/qdlights(  978): set_light_backlight: 186
,D/qdlights(  978): set_light_backlight: 182
,D/qdlights(  978): set_light_backlight: 179
,D/qdlights(  978): set_light_backlight: 176
,D/qdlights(  978): set_light_backlight: 172
,D/qdlights(  978): set_light_backlight: 169
,D/qdlights(  978): set_light_backlight: 166
,D/qdlights(  978): set_light_backlight: 162
,D/qdlights(  978): set_light_backlight: 159
,D/qdlights(  978): set_light_backlight: 156
,D/qdlights(  978): set_light_backlight: 152
,D/qdlights(  978): set_light_backlight: 149
,D/qdlights(  978): set_light_backlight: 146
,D/qdlights(  978): set_light_backlight: 142
,D/qdlights(  978): set_light_backlight: 139
,D/qdlights(  978): set_light_backlight: 136
,D/qdlights(  978): set_light_backlight: 132
,D/qdlights(  978): set_light_backlight: 129
,D/qdlights(  978): set_light_backlight: 126
,D/qdlights(  978): set_light_backlight: 122
,D/qdlights(  978): set_light_backlight: 119
,D/qdlights(  978): set_light_backlight: 116
,D/qdlights(  978): set_light_backlight: 112
,D/qdlights(  978): set_light_backlight: 109
,D/qdlights(  978): set_light_backlight: 106
,D/qdlights(  978): set_light_backlight: 102
,D/qdlights(  978): set_light_backlight: 99
,D/qdlights(  978): set_light_backlight: 96
,D/qdlights(  978): set_light_backlight: 92
,D/qdlights(  978): set_light_backlight: 89
,D/qdlights(  978): set_light_backlight: 86
,D/qdlights(  978): set_light_backlight: 82
,D/qdlights(  978): set_light_backlight: 79
,D/qdlights(  978): set_light_backlight: 76
,D/qdlights(  978): set_light_backlight: 72
,D/qdlights(  978): set_light_backlight: 69
,D/qdlights(  978): set_light_backlight: 66
,D/qdlights(  978): set_light_backlight: 62
,D/qdlights(  978): set_light_backlight: 59
,D/qdlights(  978): set_light_backlight: 56
,D/qdlights(  978): set_light_backlight: 52
,D/qdlights(  978): set_light_backlight: 49
,D/qdlights(  978): set_light_backlight: 46
,D/qdlights(  978): set_light_backlight: 42
,D/qdlights(  978): set_light_backlight: 39
,D/qdlights(  978): set_light_backlight: 36
,D/qdlights(  978): set_light_backlight: 32
,D/qdlights(  978): set_light_backlight: 29
,D/qdlights(  978): set_light_backlight: 26
,D/qdlights(  978): set_light_backlight: 22
,D/qdlights(  978): set_light_backlight: 19
,D/qdlights(  978): set_light_backlight: 16
,D/qdlights(  978): set_light_backlight: 12
,D/qdlights(  978): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:16:38.852 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:16:41.867 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 154563413434; DSPS: 5163173; Offset : -3013611600
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/PowerManagerService(  978): ALS enabled for SRE
D/PowerManagerServiceEx(  978): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (36063 ms ago)
I/PowerManagerService(  978): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  978): ALS enabled for SRE
D/PowerManagerServiceEx(  978): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (36075 ms ago)
W/ContextImpl(  978): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  978): Sleeping (uid 1000)...
D/LPWGController(  978): [updateScreenState] screen on = false
D/LPWGController(  978): disable proximity sensor
D/LPWGController(  978): enable proximity sensor
I/SensorManager(  978): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2ea50e55] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  978): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  978): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  978): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  978): activate: handle is 48, enable
V/sensors_hal_Ctx(  978): activate sensors is 1400000000000
D/sensors_hal_Thresh(  978): enable: handle=48
I/sensors_hal_SAM(  978): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  978): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  978): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  978): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  978): enable: Received response: 0
D/PowerManagerServiceEx(  978): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (36114 ms ago)
I/Adreno-EGL(  978): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  978): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  978): Build Date: 03/02/15 Mon
I/Adreno-EGL(  978): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  978): Remote Branch: 
I/Adreno-EGL(  978): Local Patches: 
I/Adreno-EGL(  978): Reconstruct Branch: 
,D/PermissionCache(  248): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1027 us)
,I/Sensors (  442): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  978): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  978): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  978): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  978): processInd: handle 48, count=1
V/sensors_hal_Thresh(  978): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  978): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  978): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  978): poll: count: 256
I/sensors_hal_Ctx(  978): poll: released wakelock sensor_ind
D/sensors_hal_Util(  978): waitForResponse: timeout=0
D/LPWGController(  978): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  978): current mode = 1  value = 1 1
I/LPWGController(  978): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  978): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/qdlights(  978): set_light_backlight: 0
,I/SensorManager(  978): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  978): activate: handle is 46, disable
,V/sensors_hal_Ctx(  978): activate sensors is 1000000000000
D/sensors_hal_LP2(  978): enable: handle=46
D/sensors_hal_LP2(  978): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  978): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  248): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  248): hwc_blank: Blanking display: 0
I/DisplayManagerService(  978): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  978): Display changed displayId=0
,V/sensors_hal_SAM(  978): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  978): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1750): Display #0 changed.
,D/qdhwcomposer(  248): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  978): Excessive delay in setPowerMode(): 221ms
I/qdhwcomposer(  248): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  978): Got set_interactive hint
,D/KeyguardViewMediator( 1375): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1334): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1375): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1334): notifyScreenOffLocked
D/KeyguardViewMediator( 1375): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1375): handleNotifyScreenOff
D/WifiServerServiceExt(  978): sendKtScanInterval  mRtspPlay : false
,I/QCNEJ   ( 1839): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
D/ScreenTurnOffBySensor( 1375): unregisterProximitySensor
I/QCNEJ   ( 1839): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-57 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.134 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-02-09 23:16:44.724 DNS addrs= 192.168.1.1, 0.0.0.0, 
D/SmartCoverViewMediator( 1334): handleNotifyScreenOFF
,V/AudioFlinger(  287): setParameters(): io 0, keyvalue screen_state=on, calling pid 978
,D/StatusBarWindowView( 1375): onScreenTurnedOff why = 3
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
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/WifiServerServiceExt(  978): set CMD_KT_SCAN_INTERVAL
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
,D/GpsLocationProvider(  978): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:true
I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/Cliptray Service( 1804): lockStatus = 0
D/LEDService( 1804): stopPatternFlashing()
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1786): action : android.intent.action.SCREEN_ON
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): updateLightsLocked : turn off led
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1804): RESTART MSG
,D/NfcServiceNXP( 1786): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1786): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
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
D/SplitWindow(  978): check instance of lgWin Window{17beb5f8 u0 SearchPanel}
,D/Ulp_jni (  978): JNI:system_update. Event-0
,D/InputDispatcher(  978): Window went away: Window{3ef4cd2e u0 SearchPanel}
I/[SystemUI]Clock( 1375): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1375): time changed, timezoneChanged : false
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2645): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 23:16:45
D/WeatherService( 2645): 2 : ACTION screen on
,D/WeatherService( 2645): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2645): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2645): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 23:16:45
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  978): ACTION_SCREEN_ON
,D/AppCleanupService( 4045): android.intent.action.SCREEN_ON
,V/AudioFlinger(  287): setParameters(): io 0, keyvalue screen_state=off, calling pid 978
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
D/WifiController(  978): CMD_SCREEN_OFF 
D/WifiController(  978): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  978): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/Sensors (  442): sns_pwr.c(301):releasing wakelock
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:false
,I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1804): stopPatternFlashing()
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): updateLightsLocked : turn on led
E/LEDService( 1804): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1804): Can't handle this request of patternId:0
D/LEDHandler( 1804): RESTART MSG
D/VolumeVibrator( 1804): clear
I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1786): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1786): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1878): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2645): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 23:16:45
D/WeatherService( 2645): 2 : ACTION screen off
D/WeatherService( 2645): 2 : TimeTick Receiver Unregister
D/WeatherService( 2645): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 23:16:45
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  978): ACTION_SCREEN_OFF
D/AppCleanupService( 4045): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4045): AppUsageStatsSaveTask
E/NxpNfcJni( 1786): getReconnectState = 0x0
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
D/LNfcService( 1786): isRequireNfcCRouting() return true
D/LNfcService( 1786): isHCERoutingtoHost() return : true
,D/NfcService( 1786): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): newParams.techmask= mTechMask: 0
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): screenState= 1
E/NxpNfcJni( 1786): getReconnectState = 0x0
,I/ThermalEngine(  297): Sensor:pa_therm0:32000 mC
,D/KeyguardViewMediator( 1375): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  978): ELAPSED_WAKEUP set : Alarm{2d753ad1 type 2 when 161996 com.android.systemui} when 161996
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1750): getCallState : 0
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1375): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1375): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 174564240041; DSPS: 5818560; Offset : -3013609228
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  978): acquireWakeLockInternal: lock=561768758, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=978
,V/AlarmManager(  978): ELAPSED_WAKEUP set : Alarm{1894f037 type 2 when 182910 android} when 182910
D/PowerManagerServiceEx(  978): releaseWakeLockInternal: lock=561768758 [*alarm*], flags=0x0
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  488): init target 500000
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  978): battery changed pluggedType: 2
V/AlarmManager(  978): ELAPSED_WAKEUP set : Alarm{1a2539a4 type 2 when 187931 com.google.android.gms} when 187931
,I/PhenotypeConfigurator( 1732): Scheduling Phenotype for one-off execution 808 seconds from now (1455056235956)
,D/GetConfigurationSnapshotOperation( 1732): no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,I/PhenotypeFlagCommitter( 1732): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1732): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  978): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 44547(2MB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 14MB/23MB, paused 1.954ms total 107.942ms
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  282): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  282): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  282): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=101; mark=917605
D/libc-netbsd(  282): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  282): default dns: query_ipv6=0, query_ipv4=1, netid=101
D/libc-netbsd(  282): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  282): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationManagerService(  978): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  978): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  978): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1732): disconnect managed GoogleApiClient
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 194564908575; DSPS: 6473942; Offset : -3013612002
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 214565587109; DSPS: 7129324; Offset : -3013604516
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 234566339810; DSPS: 7784708; Offset : -3013584210
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  488): init target 500000
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  978): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 254567108500; DSPS: 8440094; Offset : -3013609030
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 274567781253; DSPS: 9095476; Offset : -3013608133
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # multiplex can send data
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 22 String should be length:200
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # enqueue and run in order
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 23 firstPromise setTimeout
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 24 firstPromise result
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 25 firstPromise testValue
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 26 secondPromise setTimeout
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 27 secondPromise result
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 28 secondPromise testValue
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 29 thirdPromise in promise
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 30 thirdPromise result
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 31 thirdPromise testValue
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # basic
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 32 sane
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # another
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 33 sane
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # successfully create a new pkcs12 file and return hash value
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 34 should be equal
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 35 null
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 36 (unnamed assert)
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 37 should be equal
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 38 should not throw
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # successfully read a previous pkcs12 file and return hash value
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 39 (unnamed assert)
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 40 (unnamed assert)
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 41 should not throw
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 42 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 43 should be equal
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # failed to extract public key because of corrupt pkcs12 file
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 44 should be equal
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # failed to get mobile documents path
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 45 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # #init should register the peerAvailabilityChanged event
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 46 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 47 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 48 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # #init should register the networkChanged event
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 49 should be equal
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # #startBroadcasting should throw on null device name
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 50 should throw
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # #startBroadcasting should throw on empty string device name
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 51 should throw
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/jxcore-log( 5536): # #startBroadcasting should throw on non-number port
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 52 should throw
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # #startBroadcasting should throw on NaN port
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 53 should throw
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # #startBroadcasting should throw on negative port
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 54 should throw
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # #startBroadcasting should throw on too large port
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 55 should throw
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # #startBroadcasting should call Mobile("StartBroadcasting") without an error
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 56 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 57 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 58 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # #startBroadcasting should call Mobile("StartBroadcasting") and handle an error
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 59 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 60 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 61 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # #stopBroadcasting should call Mobile("StopBroadcasting") without an error
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 62 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 63 should be equal
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 64 should be equal
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 65 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # #connect should call Mobile("Connect") with a port and without an error
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 66 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 67 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 68 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # #connect should call Mobile("Connect") and handle an error
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 69 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 70 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # should call Mobile("Disconnect") without an error
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 71 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 72 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # should call Mobile("Disconnect") and handle an error
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 73 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 74 should be equal
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # #start should fail if called twice in a row
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 75 specific error should be received
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # #startListeningForAdvertisements should fail if start not called
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 76 specific error should be returned
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # should be able to call #stopListeningForAdvertisements many times
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 77 error should be null
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 78 error should be null
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # should be able to call #startListeningForAdvertisements many times
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 79 error should be null
I/jxcore-log( 5536): 
I/jxcore-log( 5536): ok 80 error should be null
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # should be able to call #startUpdateAdvertisingAndListening many times
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 81 error should be null
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 82 error should be null
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # #startUpdateAdvertisingAndListening should fail if start not called
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): ok 83 specific error should be returned
I/jxcore-log( 5536): 
I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # setup
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error
I/jxcore-log( 5536): 
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@316832ca added. We now have 2 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338383.5536
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): bind: Binding a new listener
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5536): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455056338383.5536","ra":"F8:95:C7:87:85:54"}
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5536): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): start: OK
I/io.jxcore.node.ConnectionHelper( 5536): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338383.5536, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5536): bind: Binding a new listener
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5536): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455056338383.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: {"pi":"F8:95:C7:87:85:54","pn":"1455056338383.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455056338383.5536","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
W/BluetoothAdapter( 5536): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 1966): BTA_JvCreateRecordByUser
,D/LGBluetoothServiceAdapter( 1966): [BTUI] createSocketChannel FD=87 mFd=85
,I/bt-btif ( 1966): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): Waiting for incoming connections...
D/LGWifiP2pService(  978): InactiveState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9b1d06e0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-1ms what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@9b1d06e0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState add service
D/LGWifiP2pService(  978): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): start: Starting P2P device discovery...
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): setState: RUNNING_WIFI
D/LGWifiP2pService(  978): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338383.5536, mode: WIFI
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery started successfully
,I/wpa_supplicant( 2783): p2p0: CTRL-EVENT-SCAN-STARTED 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5536): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/io.jxcore.node.ConnectionHelper( 5536): start: OK
D/WfdsMonitor( 1804): Event [CTRL-EVENT-SCAN-STARTED ]
I/jxcore-log( 5536): ok 84 Should be able to call startBroadcasting without error
I/jxcore-log( 5536): 
I/io.jxcore.node.ConnectionHelper( 5536): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): shutdown
,I/bt-btif ( 1966): BTA_JvDeleteRecord
I/bt-btif ( 1966): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5536): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): stop: Stopping services
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState clear service
D/LGWifiP2pService(  978): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2783): P2P-FIND-STOPPED 
D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  978): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): discovery change broadcast false
I/io.jxcore.node.ConnectionHelper( 5536): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery stopped successfully
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5536): release: No more listeners, de-initializing...
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139307 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState clear service request
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5536): Service requests cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5536): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5536): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5536): ok 85 Should be able to call stopBroadcasting without error
I/jxcore-log( 5536): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3eb196 added. We now have 3 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): setDiscoveryMode: WIFI -> BLE_AND_WIFI
,D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338631.5536
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): bind: Binding a new listener
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5536): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455056338631.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): start: OK
I/io.jxcore.node.ConnectionHelper( 5536): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5536): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5536): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338631.5536, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5536): bind: Binding a new listener
,I/bt-btif ( 1966): BTA_JvCreateRecordByUser
I/bt-btif ( 1966): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): Waiting for incoming connections...
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5536): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455056338631.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: {"pi":"F8:95:C7:87:85:54","pn":"1455056338631.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455056338631.5536","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@50662a68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@50662a68 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState add service
D/LGWifiP2pService(  978): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onIsWifiPeerDiscoveryStartedChanged: true
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: Already running, call stopListening() first to restart
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: OK
I/wpa_supplicant( 2783): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1804): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  978): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 5536): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338631.5536, mode: WIFI
I/jxcore-log( 5536): ok 86 Should be able to call startBroadcasting without error
I/jxcore-log( 5536): 
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 5536): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): shutdown
I/bt-btif ( 1966): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): Exiting thread
,I/bt-btif ( 1966): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): onServerStopped
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: RESTARTING
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5536): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5536): onConnectionManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stopForRestart
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5536): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): stop: Stopping services
I/wpa_supplicant( 2783): P2P-FIND-STOPPED 
D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery stopped successfully
D/LGWifiP2pService(  978): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): discovery change broadcast false
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState clear service
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: NOT_INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5536): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5536): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): setState: NOT_STARTED
,D/LGWifiP2pService(  978): remove client information from framework
I/io.jxcore.node.ConnectionHelper( 5536): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5536): ok 87 Should be able to call stopBroadcasting without error
I/jxcore-log( 5536): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Scan mode: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e2c5122 added. We now have 4 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): Local services cleared successfully
D/LGWifiP2pService(  978): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  978): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5536): Service requests cleared successfully
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4,
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338703.5536
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): bind: Binding a new listener
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5536): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455056338703.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): setState: RUNNING
I/io.jxcore.node.ConnectionHelper( 5536): onConnectionManagerStateChanged: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): start: OK
I/io.jxcore.node.ConnectionHelper( 5536): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5536): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1966): BTA_JvCreateRecordByUser
I/bt-btif ( 1966): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338703.5536, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5536): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
,D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5536): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455056338703.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: {"pi":"F8:95:C7:87:85:54","pn":"1455056338703.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455056338703.5536","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@904b61e8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@904b61e8 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState add service
D/LGWifiP2pService(  978): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onIsWifiPeerDiscoveryStartedChanged: true
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: OK
I/io.jxcore.node.ConnectionHelper( 5536): start: OK
I/wpa_supplicant( 2783): p2p0: P2P: Reject scan trigger since one is already pending
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338703.5536, mode: WIFI
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/LGWifiP2pService(  978): discovery change broadcast true
,D/WfdsMonitor( 1804): Event [P2P: Reject scan trigger since one is already pending]
I/jxcore-log( 5536): ok 88 Should be able to call startBroadcasting without error
I/jxcore-log( 5536): 
I/io.jxcore.node.ConnectionHelper( 5536): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): onServerStopped
I/bt-btif ( 1966): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): release: 1 listener(s) left
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: Already running, call stopListening() first to restart
I/bt-btif ( 1966): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: OK
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): Local service added successfully
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5536): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5536): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5536): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: NOT_INITIALIZED
D/LGWifiP2pService(  978): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5536): release: No more listeners, de-initializing...
D/LGWifiP2pService(  978): InactiveState{ when=-1ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2783): P2P-FIND-STOPPED 
D/WfdsMonitor( 18,04): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5536): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): setState: NOT_STARTED
D/LGWifiP2pService(  978): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): discovery change broadcast false
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState clear service request
I/io.jxcore.node.ConnectionHelper( 5536): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5536): Service requests cleared successfully
I/jxcore-log( 5536): ok 89 Should be able to call stopBroadcasting without error
I/jxcore-log( 5536): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Maximum number of connection attempt retries: 0
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	,Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16625d6e added. We now have 5 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338762.5536
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): bind: Binding a new listener
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5536): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455056338762.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): start: OK
I/io.jxcore.node.ConnectionHelper( 5536): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5536): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5536): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 1966): BTA_JvCreateRecordByUser
I/bt-btif ( 1966): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338762.5536, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5536): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5536): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455056338762.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: {"pi":"F8:95:C7:87:85:54","pn":"1455056338762.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455056338762.5536","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6018c31e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@6018c31e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState add service
D/LGWifiP2pService(  978): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: INITIALIZED
,I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onIsWifiPeerDiscoveryStartedChanged: true
,D/LGWifiP2pService(  978): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2783): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1804): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  978): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: OK
I/io.jxcore.node.ConnectionHelper( 5536): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338762.5536, mode: WIFI
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 5536): ok 90 Should be able to call startBroadcasting without error
I/jxcore-log( 5536): 
I/io.jxcore.node.ConnectionHelper( 5536): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): onServerStopped
I/bt-btif ( 1966): BTA_JvDeleteRecord
I/bt-btif ( 1966): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5536): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: RESTARTING
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5536): onDiscoveryManagerStateChanged: R,UNNING_WIFI
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5536): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  978): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5536): release: No more listeners, de-initializing...
D/LGWifiP2pService(  978): remove client information from framework
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): release: No more listeners, de-initializing...
I/wpa_supplicant( 2783): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): Local services cleared successfully
D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
,I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5536): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): setState: NOT_STARTED
D/LGWifiP2pService(  978): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5536): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery stopped successfully
D/LGWifiP2pService(  978): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState clear service request
D/LGWifiP2pService(  978): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): discovery change broadcast false
I/jxcore-log( 5536): ok 91 Should be able to call stopBroadcasting without error
I/jxcore-log( 5536): 
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5536): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13dae27a added. We now have 6 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND,_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338813.5536
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): bind: Binding a new listener
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5536): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455056338813.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): start: OK
I/io.jxcore.node.ConnectionHelper( 5536): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5536): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5536): getBluetoothService() called with no BluetoothManagerCallback
,I/bt-btif ( 1966): BTA_JvCreateRecordByUser
I/bt-btif ( 1966): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338813.5536, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5536): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): Waiting for incoming connections...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5536): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455056338813.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: {"pi":"F8:95:C7:87:85:54","pn":"1455056338813.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455056338813.5536","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f9d3cde4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@f9d3cde4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState add service
D/LGWifiP2pService(  978): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): start: Starting P2P device discovery...
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: OK
I/io.jxcore.node.ConnectionHelper( 5536): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338813.5536, mode: WIFI
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 5536): ok 92 Should be able to call startBroadcasting without error
I/jxcore-log( 5536): 
I/io.jxcore.node.ConnectionHelper( 5536): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): shutdown
I/bt-btif ( 1966): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): setState: NOT_STARTED
I/bt-btif ( 1966): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): onServerStopped
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-1ms what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2783): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1804): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  978): discovery change broadcast true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: OK
I/io.jxcore.node.ConnectionHelper( 5536): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stopForRestart
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5536): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): stop: Stopping services
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5536): onConnectionManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery started successfully
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what,=139298 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5536): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5536): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): setState: NOT_STARTED
D/LGWifiP2pService(  978): remove client information from framework
D/LGWifiP2pService(  978): InactiveState{ when=-1ms what=139268 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2783): P2P-FIND-STOPPED 
I/io.jxcore.node.ConnectionHelper( 5536): onDiscoveryManagerStateChanged: NOT_STARTED
D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): Local services cleared successfully
I/jxcore-log( 5536): ok 93 Should be able to call stopBroadcasting without error
I/jxcore-log( 5536): 
D/LGWifiP2pService(  978): InactiveState{ when=-1ms what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery stopped successfully
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Maximum number of connection attempt retries: 0
D/LGWifiP2pService(  978): InactiveState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState clear service request
D/LGWifiP2pService(  978): InactiveState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-2ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5536): Service requests cleared successfully
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Ad,vertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3924ac46 added. We now have 7 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338860.5536
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): bind: Binding a new listener
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5536): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455056338860.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): start: OK
I/io.jxcore.node.ConnectionHelper( 5536): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5536): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5536): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1966): BTA_JvCreateRecordByUser
I/bt-btif ( 1966): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338860.5536, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5536): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5536): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455056338860.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: {"pi":"F8:95:C7:87:85:54","pn":"1455056338860.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455056338860.5536","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a989aae0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@a989aae0 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState add service
D/LGWifiP2pService(  978): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): startWifiPeerDiscovery: Wi-Fi Direct OK
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: OK
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338860.5536, mode: WIFI
,I/wpa_supplicant( 2783): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1804): Event [P2P: Reject scan trigger since one is already pending]
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 5536): start: OK
D/LGWifiP2pService(  978): discovery change broadcast true
I/jxcore-log( 5536): ok 94 Should be able to call startBroadcasting without error
I/jxcore-log( 5536): 
I/io.jxcore.node.ConnectionHelper( 5536): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): shutdown
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: RESTARTING
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): Local service added successfully
I/io.jxcore.node.ConnectionHelper( 5536): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2783): P2P-FIND-STOPPED 
I/bt-btif ( 1966): BTA_JvDeleteRecord
I/bt-btif ( 1966): BTA_JvRfcommStopServer
D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  978): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5536): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): stop: Stopping services
I/io.jxcore.node.ConnectionHelper( 5536): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  978): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5536): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): release: No more listeners, de-initializing...
D/LGWifiP2pService(  978): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5536): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): setState: NOT_STARTED
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5536): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery stopped successfully
D/LGWifiP2pService(  978): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5536): Service requests cleared successfully
I/jxcore-log( 5536): ok 95 Should be able to call stopBroadcasting without error
I/jxcore-log( 5536): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30ef46d2 added. We now have 8 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338912.5536
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): bind: Binding a new listener
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5536): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455056338912.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): start: OK
I/io.jxcore.node.ConnectionHelper( 5536): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5536): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5536): getBluetoothService() called with no BluetoothManagerCallback
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338912.5536, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5536): bind: Binding a new listener
I/bt-btif ( 1966): BTA_JvCreateRecordByUser
I/bt-btif ( 1966): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5536): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455056338912.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: {"pi":"F8:95:C7:87:85:54","pn":"1455056338912.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455056338912.5536","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@cbf0fee4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@cbf0fee4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState add service
D/LGWifiP2pService(  978): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): start: Starting P2P device discovery...
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2783): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1804): Event [P2P: Reject scan trigger since one is already pending]
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: OK
D/LGWifiP2pService(  978): discovery change broadcast true
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338912.5536, mode: WIFI
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/io.jxcore.node.ConnectionHelper( 5536): start: OK
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5536): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5536): ok 96 Should be able to call startBroadcasting without error
I/jxcore-log( 5536): 
I/wpa_supplicant( 2783): P2P-FIND-STOPPED 
D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
I/io.jxcore.node.ConnectionHelper( 5536): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): release: 1 listener(s) left
I/bt-btif ( 1966): BTA_JvDeleteRecord
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): setState: NOT_STARTED
I/bt-btif ( 1966): BTA_JvRfcommStopServer
I/io.jxcore.node.ConnectionHelper( 5536): onConnectionManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  978): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stopForRestart
D/LGWifiP2pService(  978): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5536): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): onServerStopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): stop: Stopping services
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState clear service
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: RESTARTING
D/LGWifiP2pService(  978): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): Local services cleared successfully
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5536): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5536): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5536): onDiscoveryManagerStateChanged: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery stopped successfully
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139268 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
I/jxcore-log( 5536): ok 97 Should be able to call stopBroadcasting without error
I/jxcore-log( 5536): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Maximum number of connection attempt retries: 0
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery stopped successfully
D/LGWifiP2pService(  978): InactiveState{ when=-2ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-2ms what=139307 arg2=7 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState clear service request
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f56fe1e added. We now have 9 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5536): Service requests cleared successfully
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338968.5536
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): bind: Binding a new listener
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5536): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455056338968.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): start: OK
I/io.jxcore.node.ConnectionHelper( 5536): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5536): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338968.5536, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5536): bind: Binding a new listener
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5536): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1966): BTA_JvCreateRecordByUser
I/bt-btif ( 1966): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5536): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455056338968.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: {"pi":"F8:95:C7:87:85:54","pn":"1455056338968.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455056338968.5536","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@49b56f0e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@49b56f0e target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState add service
D/LGWifiP2pService(  978): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: OK
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056338968.5536, mode: WIFI
I/wpa_supplicant( 2783): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1804): Event [P2P: Reject scan trigger since one is already pending]
I/io.jxcore.node.ConnectionHelper( 5536): start: OK
D/LGWifiP2pService(  978): discovery change broadcast true
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 5536): ok 98 Should be able to call startBroadcasting without error
I/jxcore-log( 5536): 
I/io.jxcore.node.ConnectionHelper( 5536): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): onServerStopped
I/bt-btif ( 1966): BTA_JvDeleteRecord
I/bt-btif ( 1966): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): setState: NOT_STARTED
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5536): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
I/io.jxcore.node.ConnectionHelper( 5536): onConnectionManagerStateChanged: NOT_STARTED
,D/LGWifiP2pService(  978): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stop: Stopping peer discovery...
I/wpa_supplicant( 2783): P2P-FIND-STOPPED 
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5536): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): stop: Stopping services
D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery stopped successfully
D/LGWifiP2pService(  978): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): discovery change broadcast false
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): stop: Stopping P2P device discovery...
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: NOT_INITIALIZED
D/LGWifiP2pService(  978): P2pEnabledState{ when=-1ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5536): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): release: No more listeners, de-initializing...
D/LGWifiP2pService(  978): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5536): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): Local services cleared successfully
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery stopped successfully
D/LGWifiP2pService(  978): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-2ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5536): Service requests cleared successfully
I/io.jxcore.node.ConnectionHelper( 5536): onDiscoveryManagerStateChanged: NOT_STARTED
I/jxcore-log( 5536): ok 99 Should be able to call stopBroadcasting without error
I/jxcore-log( 5536): 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.t,haliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bf0de2a added. We now have 10 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): setDiscoveryMode: WIFI -> BLE_AND_WIFI
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056339024.5536
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): bind: Binding a new listener
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5536): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455056339024.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): startListeningForIncomingConnections: Starting...
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): setState: RUNNING
,I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): start: OK
I/io.jxcore.node.ConnectionHelper( 5536): start: Using peer discovery mode: WIFI
I/io.jxcore.node.ConnectionHelper( 5536): onConnectionManagerStateChanged: RUNNING
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 5536): getBluetoothService() called with no BluetoothManagerCallback
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056339024.5536, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5536): bind: Binding a new listener
I/bt-btif ( 1966): BTA_JvCreateRecordByUser
I/bt-btif ( 1966): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5536): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455056339024.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: {"pi":"F8:95:C7:87:85:54","pn":"1455056339024.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455056339024.5536","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@894719ae target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@894719ae target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState add service
D/LGWifiP2pService(  978): add a new client
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: OK
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5536): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056339024.5536, mode: WIFI
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/wpa_supplicant( 2783): p2p0: P2P: Reject scan trigger since one is already pending
D/WfdsMonitor( 1804): Event [P2P: Reject scan trigger since one is already pending]
,D/LGWifiP2pService(  978): discovery change broadcast true
I/jxcore-log( 5536): ok 100 Should be able to call startBroadcasting without error
I/jxcore-log( 5536): 
I/io.jxcore.node.ConnectionHelper( 5536): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): release: 1 listener(s) left
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): Exiting thread
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): setState: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): onServerStopped
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: OK
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5536): onDiscoveryManagerStateChanged: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: STARTED
I/io.jxcore.node.ConnectionHelper( 5536): onConnectionManagerStateChanged: NOT_STARTED
I/bt-btif ( 1966): BTA_JvDeleteRecord
I/bt-btif ( 1966): BTA_JvRfcommStopServer
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5536): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): stop: Stopping services
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/wpa_supplicant( 2783): P2P-FIND-STOPPED 
D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5536): release: No more listeners, de-initializing...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery stopped successfully
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): release: No more listeners, de-initializing...
D/LGWifiP2pService(  978): InactiveState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-2ms what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  ,978): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5536): clear
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): setState: NOT_STARTED
D/LGWifiP2pService(  978): remove client information from framework
D/LGWifiP2pService(  978): InactiveState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-3ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): discovery change broadcast false
I/jxcore-log( 5536): ok 101 Should be able to call stopBroadcasting without error
I/jxcore-log( 5536): 
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Connection timeout in milliseconds: 15000, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Insecure RFCOMM socket port number: -1, 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5536): 	Maximum number of connection attempt retries: 0
D/LGWifiP2pService(  978): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState clear service request
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Automate Bluetooth MAC address resolution: true, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Provide Bluetooth MAC address timeout in milliseconds: 40000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Bluetooth MAC address: F8:95:C7:87:85:54, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Discovery mode: WIFI, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Peer expiration time in milliseconds: 60000, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise mode: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Advertise TX power level: 1, 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): 	Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1096b2f6 added. We now have 11 listener(s)
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): setDiscoveryMode: WIFI -> BLE_AND_WIFI
I/io.jxcore.node.ConnectionHelper( 5536): onDiscoveryManagerStateChanged: NOT_STARTED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): Local services cleared successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery stopped successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5536): Service requests cleared successfully
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
D/BluetoothAdapterService(462300574)( 1966): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@31049ce4
,W/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onDiscoveryModeChanged: Failed to set discovery mode to BLE_AND_WIFI, BLE advertisement supported: false, Wi-Fi supported: true
,D/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5536): setDiscoveryMode: Failed to set the discovery mode to BLE_AND_WIFI, restoring the previous mode (WIFI)
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056339075.5536
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): bind: Binding a new listener
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): initialize: My bluetooth address is F8:95:C7:87:85:54
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5536): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455056339075.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): setConnectionTimeout: 15000
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): startListeningForIncomingConnections
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): startListeningForIncomingConnections: Starting...
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): setState: RUNNING
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): start: OK
I/io.jxcore.node.ConnectionHelper( 5536): onConnectionManagerStateChanged: RUNNING
I/io.jxcore.node.ConnectionHelper( 5536): start: Using peer discovery mode: WIFI
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056339075.5536, mode: WIFI
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): bind: Binding a new listener
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5536): bind: Binding a new listener
W/BluetoothAdapter( 5536): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1966): BTA_JvCreateRecordByUser
I/bt-btif ( 1966): BTA_JvRfcommStartServer
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): Waiting for incoming connections...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onWifiStateChanged: State changed to 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onWifiStateChanged: Wi-Fi enabled, trying to restart Wi-Fi Direct based peer discovery...
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5536): verifyIdentityString: Identity string created: {"pi":"F8:95:C7:87:85:54","pn":"1455056339075.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: {"pi":"F8:95:C7:87:85:54","pn":"1455056339075.5536","ra":"F8:95:C7:87:85:54"}
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): start: Identity string: "{"pi":"F8:95:C7:87:85:54","pn":"1455056339075.5536","ra":"F8:95:C7:87:85:54"}", service type: "Cordovap2p._tcp"
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5bae1ba2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139292 arg2=1 obj=android.net.wifi.p2p.nsd.WifiP2pServiceInfo@5bae1ba2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState add service
D/LGWifiP2pService(  978): add a new client
,D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): start: Starting P2P device discovery...
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onIsWifiPeerDiscoveryStartedChanged: true
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): startWifiPeerDiscovery: Wi-Fi Direct OK
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): setState: RUNNING_WIFI
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: OK
I/io.jxcore.node.ConnectionHelper( 5536): start: OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: Peer ID: F8:95:C7:87:85:54, peer name: 1455056339075.5536, mode: WIFI
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139265 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/BluetoothManagerService(  978): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/wpa_supplicant( 2783): p2p0: P2P: Reject scan trigger since one is already pending
I/jxcore-log( 5536): ok 102 Should be able to call startBroadcasting without error
I/jxcore-log( 5536): 
D/WfdsMonitor( 1804): Event [P2P: Reject scan trigger since one is already pending]
D/LGWifiP2pService(  978): discovery change broadcast true
I/io.jxcore.node.ConnectionHelper( 5536): stop
I/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): stop: Stopping Bluetooth...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): Shutting down...
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): stopListeningForIncomingConnections: Stopping...
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): shutdown
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread( 5536): Exiting thread
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5536): onServerStopped
I/bt-btif ( 1966): BTA_JvDeleteRecord
I/bt-btif ( 1966): BTA_JvRfcommStopServer
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): release: 1 listener(s) left
W/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): start: Already running, call stopListening() first to restart
D/org.thaliproject.p2p.btconnectorlib.ConnectionManager( 5536): setState: NOT_STARTED
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): startWifiPeerDiscovery: Wi-Fi Direct OK
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): start: OK
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): Local service added successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery stopped, restarting...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): restart: Restarting...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: RESTARTING
I/io.jxcore.node.ConnectionHelper( 5536): onDiscoveryManagerStateChanged: RUNNING_WIFI
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery started successfully
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: STARTED
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): PeerDiscoveryBroadcastReceiver.onReceive: Wi-Fi P2P device discovery started
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139268 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
I/io.jxcore.node.ConnectionHelper( 5536): onConnectionManagerSt,ateChanged: NOT_STARTED
I/wpa_supplicant( 2783): P2P-FIND-STOPPED 
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stop: Stopping peer discovery...
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stopForRestart
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager/BluetoothMacAddressResolutionHelper( 5536): stopProvideBluetoothMacAddressMode
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiPeerDiscoverer( 5536): stop: Stopping services
D/WfdsMonitor( 1804): Event [P2P-FIND-STOPPED ]
D/LGWifiP2pService(  978): InactiveState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-1ms what=147493 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): discovery change broadcast false
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery stopped successfully
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=0 what=139298 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState clear service
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): stop: Stopping P2P device discovery...
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): setState: NOT_INITIALIZED
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): onIsWifiPeerDiscoveryStartedChanged: false
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): stopWifiPeerDiscovery: Stopped
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager( 5536): release: No more listeners, de-initializing...
D/LGWifiP2pService(  978): remove client information from framework
I/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 5536): release: No more listeners, de-initializing...
I/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceAdvertiser( 5536): Local services cleared successfully
I/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5536): clear
D/LGWifiP2pService(  978): InactiveState{ when=0 what=139268 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.DiscoveryManager( 5536): setState: NOT_STARTED
I/io.jxcore.node.ConnectionHelper( 5536): onDiscoveryManagerStateChanged: NOT_STARTED
D/LGWifiP2pService(  978): InactiveState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  978): P2pEnabledState{ when=-1ms what=139307 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiP2pDeviceDiscoverer( 5536): P2P device discovery stopped successfully
D/LGWifiP2pService(  978): P2pEnabledState clear service request
D/org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiServiceWatcher( 5536): Service requests cleared successfully
I/jxcore-log( 5536): ok 103 Should be able to call stopBroadcasting without error
I/jxcore-log( 5536): 
,I/jxcore-log( 5536): # teardown
I/jxcore-log( 5536): 
I/Netd    (  282): M: Get netlink event, ifname: p2p0 action: 4
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 294568549317; DSPS: 9750861; Offset : -3013603008
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  488): init target 500000
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  978): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 314569285717; DSPS: 10406245; Offset : -3013598848
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  978): battery changed pluggedType: 2
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  978): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 334569942532; DSPS: 11061627; Offset : -3013613394
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/LocationManagerService(  978): remove 25e07506
,D/LocationManagerService(  978): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  978): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  978): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  978): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  978): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  978): acquireWakeLockInternal: lock=561768758, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=978
,D/PowerManagerServiceEx(  978): releaseWakeLockInternal: lock=561768758 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 354571093411; DSPS: 11717024; Offset : -3013591612
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  978): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 374571856371; DSPS: 12372409; Offset : -3013591487
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 394572580947; DSPS: 13027793; Offset : -3013599568
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 414573241044; DSPS: 13683175; Offset : -3013610702
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  978): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 434573898223; DSPS: 14338556; Offset : -3013594313
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 454574558996; DSPS: 14993938; Offset : -3013605370
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  978): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 474575345916; DSPS: 15649324; Offset : -3013611933
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 494576078877; DSPS: 16304708; Offset : -3013611264
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 514576818662; DSPS: 16960092; Offset : -3013603797
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 534577476049; DSPS: 17615473; Offset : -3013587070
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  978): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 554578153906; DSPS: 18270856; Offset : -3013611612
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 574578813482; DSPS: 18926237; Offset : -3013592384
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 594579546964; DSPS: 19581621; Offset : -3013591611
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  978): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 614580394873; DSPS: 20237009; Offset : -3013597855
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 634581080700; DSPS: 20892392; Offset : -3013614115
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 654581838035; DSPS: 21547776; Offset : -3013589281
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  978): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 674582586726; DSPS: 22203161; Offset : -3013603503
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 694583249114; DSPS: 22858543; Offset : -3013612528
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 714583982543; DSPS: 23513927; Offset : -3013611338
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 734584716026; DSPS: 24169311; Offset : -3013610901
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 754585373726; DSPS: 24824692; Offset : -3013593395
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 774586130697; DSPS: 25480077; Offset : -3013599518
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  978): battery changed pluggedType: 2
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 794586878659; DSPS: 26135461; Offset : -3013583797
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  978): acquireWakeLockInternal: lock=561768758, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=978
,V/AlarmManager(  978): RTC_WAKEUP set : Alarm{2f6e8d19 type 0 when 1455056847596 com.google.android.gms} when 1455056847596
D/PowerManagerServiceEx(  978): releaseWakeLockInternal: lock=561768758 [*alarm*], flags=0x0
,I/EventLogService( 5627): Aggregate from 1455056157780 (log), 1455055047511 (data)
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 814587536307; DSPS: 26790843; Offset : -3013597692
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 834588279580; DSPS: 27446227; Offset : -3013587387
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 854588975719; DSPS: 28101610; Offset : -3013592632
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 874589632065; DSPS: 28756992; Offset : -3013607569
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 894590734871; DSPS: 29412388; Offset : -3013603628
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 914591406270; DSPS: 30067770; Offset : -3013603435
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 934592096991; DSPS: 30723153; Offset : -3013614904
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  978): acquireWakeLockInternal: lock=561768758, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=978
,V/AlarmManager(  978): ELAPSED_WAKEUP set : Alarm{226a3dea type 2 when 951170 com.android.bluetooth} when 951170
D/PowerManagerServiceEx(  978): releaseWakeLockInternal: lock=561768758 [*alarm*], flags=0x0
,W/bt-smp  ( 1966): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1966): Plain text(LSB ~ MSB) = 7c 3a 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1966): Encrypted text(LSB ~ MSB) = f7 fc 5f fd b9 17 81 76 13 58 86 c3 26 95 7e a1 
W/bt-btm  ( 1966): Stopping oneshot timer
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 954592855004; DSPS: 31378537; Offset : -3013589417
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 974593530621; DSPS: 32033920; Offset : -3013615809
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  978): acquireWakeLockInternal: lock=561768758, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=978
,V/AlarmManager(  978): ELAPSED_WAKEUP set : Alarm{1315d8db type 2 when 993573 com.google.android.gms} when 993573
,I/ActivityManager(  978): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=8310 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 8310): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 8310): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@32421eb4
D/PowerManagerServiceEx(  978): releaseWakeLockInternal: lock=561768758 [*alarm*], flags=0x0
I/ActivityManager(  978): Killing 7814:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  978): failed to open /acct/uid_10023/pid_7814/cgroup.procs: No such file or directory
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 994594183843; DSPS: 32689301; Offset : -3013603196
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 1014594939773; DSPS: 33344686; Offset : -3013610048
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 1034595776588; DSPS: 34000073; Offset : -3013597416
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 1054596491737; DSPS: 34655457; Offset : -3013614794
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 1074597221416; DSPS: 35310840; Offset : -3013586707
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 1094597910731; DSPS: 35966223; Offset : -3013599243
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 1114598626037; DSPS: 36621606; Offset : -3013586102
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 1134599339466; DSPS: 37276990; Offset : -3013604990
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1966): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  978): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  978): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  978): battery changed pluggedType: 2
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 1154600444511; DSPS: 37932386; Offset : -3013598709
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 1174601107473; DSPS: 38587768; Offset : -3013606692
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 1194601921840; DSPS: 39243154; Offset : -3013585885
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 1214602595426; DSPS: 39898537; Offset : -3013614647
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/UsageStatsService(  978): User[0] Flushing usage stats to disk
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 1234603258022; DSPS: 40553918; Offset : -3013592580
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 1254603940202; DSPS: 41209300; Offset : -3013582048
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  488): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  978): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  978): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  978): tsOffsetIs: Apps: 1274604673111; DSPS: 41864685; Offset : -3013612001
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  297): Sensor:pa_therm0:29000 mC
,TIME-OUT KILL (timeout was 1200000ms),D/AndroidRuntime( 8376): 
D/AndroidRuntime( 8376): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8376): CheckJNI is OFF
D/AndroidRuntime( 8376): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  978): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  978): Killing 5536:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  978): WIN DEATH: Window{1ec0f030 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  978): Skipping PackageSetting{425bb94 com.example.hello/10317} due to missing metadata
D/InputDispatcher(  978): Focus left window: Window{1ec0f030 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  978): Window went away: Window{1ec0f030 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  978):   Force finishing activity ActivityRecord{346900f7 u0 com.test.thalitest/.MainActivity t222}
V/ActivityManager(  978): Display changed displayId=0
D/DSDPConnection( 1750): Display #0 changed.
W/ActivityManager(  978): Spurious death for ProcessRecord{1cc23f78 5536:com.test.thalitest/u0a316}, curProc for 5536: null
I/ActivityManager(  978): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
D/KeyguardModel( 1375): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/System.err( 3579): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  978): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]EVENT( 1878): [Launcher.java:5203:onStart()]onStart
W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
I/ActivityManager(  978): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=8408 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/System.err( 3579): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3579): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3579): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3579): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3579): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3579): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3579): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3579): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3579): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3579): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3579): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/art     ( 5627): Explicit concurrent mark sweep GC freed 7223(389KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 13MB/18MB, paused 768us total 138.697ms
I/art     ( 1937): Explicit concurrent mark sweep GC freed 24255(1404KB) AllocSpace objects, 5(118KB) LOS objects, 40% free, 12MB/21MB, paused 1.273ms total 148.286ms
D/KeyguardModel( 1375): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1375): createShortcutInfo...
I/[LGHome]EVENT( 1878): [Launcher.java:776:onResume()]onResume
I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1375): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1375): createShortcutInfo...
I/[LGHome]EVENT( 1878): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
I/[LGHome]LGActivityUtil( 1878): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
W/PackageManager( 1375): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/[LGHome]EVENT( 1878): [Launcher.java:929:onResume()]onResume end
I/Activity( 1878): Activity.onPostResume() called 
D/KeyguardModel( 1375): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1375): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1375): createShortcutInfo...
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1375): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/KeyguardModel( 1375): handleShortcutListChanged...
D/KeyguardModel( 1375): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1375): createShortcutInfo...
W/[LGHome]LGWallpaperInfo( 1878): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1878): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/KeyguardModel( 1375): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1375): createShortcutInfo...
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1375): createShortcutInfo...
I/SystemUI[Framework](  978): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
W/PhoneWindowManagerEx(  978): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  978): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  978): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  978): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1ea84cfb,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  978): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1375): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1375): createShortcutInfo...
I/SystemUI[Framework](  978): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  978): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  978): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  978): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  978): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1ea84cfb,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  978): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/ResourceType( 1375): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1375): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1375): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1375): createShortcutInfo...
D/InputDispatcher(  978): Focus entered window: Window{3c6cbde8 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/KeyguardModel( 1375): handleShortcutListChanged...
W/ResourcesManager( 8408): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8408): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 8408): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/art     (  978): Explicit concurrent mark sweep GC freed 67327(4MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 23MB/35MB, paused 7.371ms total 291.894ms
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
I/art     (  978): WaitForGcToComplete blocked for 186.224ms for cause Explicit
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1878): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  978): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  978): Got RemoteException sending setActive(false) notification to pid 5536 uid 10316
D/administrator(  978): Handling package changes for user 0
I/LGEmail ( 8408): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
D/LGEmail ( 8408): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
I/Timeline(  978): Timeline: Activity_windows_visible id: ActivityRecord{5063935 u0 com.lge.launcher2/.Launcher t221} time:1293556
W/IInputConnectionWrapper( 1878): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
E/b       ( 1587): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1878): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/NotificationService(  978): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  978): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
D/JobSchedulerService(  978): Receieved: android.intent.action.PACKAGE_REMOVED
W/IInputConnectionWrapper( 1878): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/PhoneStatusBar( 1375): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=0 newVal=8600 diff=8600
I/[SystemUI]NavigationThemeResource( 1375): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1375):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1375): , Keyguard show=false, IME shown=false, Panel expanded=false
D/TaskPersister(  978): removeObsoleteFile: deleting file=222_task.xml
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
I/art     (  978): Explicit concurrent mark sweep GC freed 6827(397KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.059ms total 343.567ms
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
I/PackageChangeReceiver( 8408): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
D/AndroidRuntime( 8376): Shutting down VM
I/ActivityManager(  978): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=8436 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  978): Killing 7837:com.android.contacts/u0a18 (adj 15): empty #11
I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1878): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  978): failed to open /acct/uid_10018/pid_7837/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 8436): onCreate
W/AppUp4:DB( 8436):  [AppBoxDatabaseHelper] construct
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/AppUp4:DB( 8436):  setFingerPrint start
I/AppUp4:DB( 8436):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/AppUp4:DB( 8436):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 8436):  SDK version = 0
I/AppUp4:DB( 8436):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 8436): AppBoxApplication onCreate()
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/AppUp4:PreloadHelper( 8436): added Exclude : com.test.thalitest
I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/ActivityManager(  978): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=8454 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  978): Killing 7177:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1878): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  978): failed to open /acct/uid_10006/pid_7177/cgroup.procs: No such file or directory
I/Timeline( 1878): Timeline: Activity_idle id: android.os.BinderProxy@10dcb709 time:1294196
I/art     ( 1878): Explicit concurrent mark sweep GC freed 28061(1533KB) AllocSpace objects, 19(2MB) LOS objects, 40% free, 15MB/25MB, paused 1.547ms total 55.908ms

```
