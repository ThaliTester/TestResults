#### Test 6216742584ac8ae_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
,I/SystemConfig( 4885): BUILD Country: EU
I/SystemConfig( 4885): BUILD Operator: OPEN
W/ResourceType(  842): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/[LGHome]EVENT( 1871): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/LocationProviderProxy(  842): applying state to connected service
--------- beginning of system
I/ActivityManager(  842): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=4915 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  842): Killing 4708:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_10038/pid_4708/cgroup.procs: No such file or directory
I/SystemConfig( 4885): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 4885): existFile = false
I/SystemConfig( 4885): canReadFile = false
I/SystemConfig( 4885): systemFeature RCS result false
D/SystemConfig( 4885): refreshRcsSupport() :false
I/LockScreenSettings( 4915): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
D/LockScreenSettings( 4915): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 4915): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 4915): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 4915): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 4915): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  842): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4933 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  842): Killing 4620:com.google.android.gm/u0a53 (adj 15): empty #11
D/AndroidRuntime( 4911): 
D/AndroidRuntime( 4911): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4911): CheckJNI is OFF
W/libprocessgroup(  842): failed to open /acct/uid_10053/pid_4620/cgroup.procs: No such file or directory
D/AndroidRuntime( 4911): Calling main entry com.android.commands.am.Am
I/ActivityManager(  842): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  842): setTaskToReturnTo : TaskRecord{168dc55a #224 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  842): setTaskToReturnTo : TaskRecord{168dc55a #224 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  842): AppWindowTokenEx init.. 
D/ContextHelper(  842): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
D/InputDispatcher(  842): Focus left window: Window{13bc188 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 1871): [Launcher.java:986:onPause()]onPause
D/AndroidRuntime( 4911): Shutting down VM
I/PhoneWindow(  842): [generateLayout] setColorNavigationBar => color=0x ff000001
D/Finsky  ( 4933): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/PhoneWindowEx(  842): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  842): [setNavigationBarColor2] color=0x fff5f5f5
D/SplitWindow(  842): check instance of lgWin Window{18ffa5b2 u0 Starting com.test.thalitest}
I/ActivityManager(  842): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4966 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1871): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1871): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  842): Starting window displayed
D/WindowManager(  842): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/SystemUI[Framework](  842): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  842): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  842): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  842): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/[SystemUI]NavigationThemeResource( 1363): notify navigation bar color(0xfff5f5f5)
I/SystemUI[Framework](  842): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@132f6ac9,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  842): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1363): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1363):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1363): , Keyguard show=false, IME shown=false, Panel expanded=false
I/HotwordDetector( 1930): Closing mic
,I/MicrophoneInputStream( 1930): mic_close com.google.android.apps.gsa.speech.audio.u@215a96dc
V/AudioRecord( 1930): stop()
D/AudioRecord( 1930): AudioRecord->stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
,V/AudioFlinger(  279): Record stopped OK
,V/AudioPolicyManager(  279): stopInput() input 17
V/AudioPolicyService(  279): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  279): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  279): ThreadBase::setParameters() routing=0
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb3845000
D/audio_hw_primary(  279): in_standby: enter: stream (0xb546dde0) usecase(7: audio-record)
D/ContextHelper( 4966): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,V/audio_hw_primary(  279): stop_input_stream: enter: usecase(7: audio-record)
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
,V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyManager(  279): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  279): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  279): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  279): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio patch list
,V/AudioPolicyService(  279): AudioCommandThread() going to sleep
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
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb3845000
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioRecord( 1930): stop()
V/AudioRecord( 1930): stop()
V/AudioRecord( 1930): stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioPolicyManager(  279): releaseInput() 17
V/AudioFlinger(  279): releasing 16 from 1930 for -1
V/AudioPolicyManager(  279): closeInput(17)
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/AudioFlinger(  279): closeInput() 17
V/AudioSystem(  279): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  842): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): ThreadBase::exit
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioSystem( 1363): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2726): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): RecordThread 0xb3845000 exiting
D/audio_hw_primary(  279): adev_close_input_stream: enter:stream_handle(0xb546dde0)
D/audio_hw_primary(  279): in_standby: enter: stream (0xb546dde0) usecase(7: audio-record)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
,V/AudioPolicyService(  279): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  279): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio port list
V/AudioPolicyManager(  279): releaseInput() exit
V/AudioFlinger(  279): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  279): removeClient_l() pid 1930, calling pid 279
V/AudioSystem( 1745): ioConfigChanged() event 4, ioHandle 17
,V/AudioSystem( 1930): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3069): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1930): Stopping hotword detection.
I/HotwordRecognitionRnr( 1930): Hotword detection finished
,D/Finsky  ( 4933): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4933): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4933): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 4933): com.android.vending: cancel(-1050172287) by com.android.vending
I/WebViewFactory( 4966): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,V/DownloadManager( 3093): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3093): created cursor android.database.sqlite.SQLiteCursor@26703ab7 on behalf of 4933
,D/Ads     ( 4933): Skipping gmscore version check
,D/Finsky  ( 4933): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4933): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 4933): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/LibraryLoader( 4966): Time to load native libraries: 6 ms (timestamps 6102-6108)
I/LibraryLoader( 4966): Expected native library version number "",actual native library version number ""
,D/Finsky  ( 4933): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/WebViewChromiumFactoryProvider( 4966): Binding Chromium to main looper Looper (main, tid 1) {160f41c4}
I/LibraryLoader( 4966): Expected native library version number "",actual native library version number ""
I/chromium( 4966): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4966): Initializing chromium process, singleProcess=true
,W/art     ( 4966): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4966): ApplicationContext is null in ApplicationStatus
I/ActivityManager(  842): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5011 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  842): Killing 4535:com.google.android.music:main/u0a81 (adj 15): empty #11
W/chromium( 4966): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,W/chromium( 4966): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4966): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4966): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4966): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4966): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4966): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4966): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4966): Remote Branch: 
I/Adreno-EGL( 4966): Local Patches: 
I/Adreno-EGL( 4966): Reconstruct Branch: 
W/libprocessgroup(  842): failed to open /acct/uid_10081/pid_4535/cgroup.procs: No such file or directory
,W/ResourcesManager( 5011): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/AudioPolicyService(  279): registerClient() client 0xb551cc60, uid 10316
,D/BluetoothManagerService(  842): Message: 20
D/BluetoothManagerService(  842): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25f01029:true
D/BluetoothAdapter( 4966): 564180528: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 4966): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4966): onDetachedFromWindow called when already detached. Ignoring
,I/PhoneWindow( 4966): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 4966): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 4966): [setNavigationBarColor2] color=0x fff5f5f5
D/SystemWebViewEngine( 4966): CordovaWebView is running on device made by: LGE
,W/art     ( 4966): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4966): Attempt to remove local handle scope entry from IRT, ignoring
,I/Activity( 4966): Activity.onPostResume() called 
,D/OpenGLRenderer( 4966): Render dirty regions requested: true
I/OpenGLRenderer( 4966): Initialized EGL, version 1.4
D/OpenGLRenderer( 4966): Enabling debug mode 0
,D/Atlas   ( 4966): Validating map...
,D/SplitWindow(  842): check instance of lgWin Window{38d05599 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 4966): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  842): Focus entered window: Window{38d05599 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/UpdateIcingCorporaServi( 1930): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/InputMethodManagerService(  842): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/Timeline( 4966): Timeline: Activity_idle id: android.os.BinderProxy@3d24b2bf time:76917
I/ActivityManager(  842): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5069 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
D/PackageBroadcastService( 4008): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/ActivityManager(  842): Displayed com.test.thalitest/.MainActivity: +1s370ms
I/Timeline(  842): Timeline: Activity_windows_visible id: ActivityRecord{a1aa38b u0 com.test.thalitest/.MainActivity t224} time:76970
V/AlarmManager(  842): RTC_WAKEUP set : Alarm{2f7e6da4 type 0 when 1457489092720 com.android.vending} when 1457489092720
D/Finsky  ( 4933): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/PackageBroadcastService( 4008): Null package name or gms related package.  Ignoreing.
,W/BindingManager( 4966): Cannot call determinedVisibility() - never saw a connection for the pid: 4966
,W/ResourcesManager( 5069): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5069): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5069): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 4008): Storage manager: low false usage 1.71MB avail 2.37GB capacity 4.06GB
,I/NotificationManager(  842): android: cancelAsUser(2) by android
,I/UpdateIcingCorporaServi( 1930): UpdateCorporaTask done [took 471 ms] updated apps [took 471 ms] 
D/JsMessageQueue( 4966): Set native->JS mode to OnlineEventsBridgeMode
,D/libc-netbsd( 4933): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4933): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4933): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4933): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  842): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/Finsky  ( 4933): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/LGEmail ( 5069): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/NotificationManager(  842): android: cancelAsUser(2) by android
,D/libc-netbsd( 4933): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4933): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LGEmail ( 5069): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ActivityManager(  842): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5113 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  842): android: cancelAsUser(2) by android
,D/libc-netbsd( 4933): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4933): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 4933): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/ResourcesManager( 5113): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5113): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5113): VM with version 2.1.0 has multidex support
I/MultiDex( 5113): install
I/MultiDex( 5113): VM has multidex support, MultiDex support library is disabled.
,I/PackageChangeReceiver( 5069): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  842): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5135 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 306us total 21.511ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 21.405ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 298us total 21.455ms
,V/JNIHelp ( 5113): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Icing   ( 4008): updateResources: need to parse f{com.google.android.gms}
,D/jxcore_app_log( 4966): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426143104
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4966): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4966):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4966):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4966):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4966):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4966): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13806989 added. We now have 1 listener(s)
D/BluetoothManagerService(  842): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4966): setBluetoothMacAddress: F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4966): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
W/ActivityThread( 5113): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4966): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
W/System  ( 5113): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@edec0c1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5113): Installed default security provider GmsCore_OpenSSL
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4966): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4966):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4966):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4966):     - Bluetooth MAC address: F8:95:C7:87:85:54
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4966):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4966):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4966):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4966):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4966):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4966):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4966): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d7d1545 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4966): addListener: New listener added - the number of listeners is now 1
I/NotificationManager( 5113): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5113): com.google.android.gms: cancel(39789) by com.google.android.gms
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4966): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4966): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 4966): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4966): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4966): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4966): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4966): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4966): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4966): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4966): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4966): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4966): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4966): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ChimeraCfgMgr( 5113): Reading stored module config
D/JX-Cordova( 4966): jxcore cordova android initializing
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4966): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4966): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@331b449a added. We now have 2 listener(s)
D/BluetoothManagerService(  842): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4966): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4966): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4966): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4966): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a9f51cb added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4966): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4966): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4966): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4966): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4966): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4966): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4966): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4966): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4966): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4966): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4966): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4966): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4966): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4966): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/LockScreenSettings( 4915): New app installed broadcast received ..
,I/LockScreenSettings( 4915): Number of installed packages  1
D/ChimeraCfgMgr( 5113): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/ActivityManager(  842): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5163 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  842): Process com.lge.qremote (pid 4372) has died
,E/lowmemorykiller(  245): Error writing /proc/4731/oom_score_adj; errno=22
,I/Icing   ( 4008): Internal init done: storage state 0
,D/EulaProviderUpdateObserver( 5163): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5163): uri : package:com.test.thalitest
D/NativeLibraryUtils( 5113): Install completed successfully. count=14 extracted=0
,I/ActivityManager(  842): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5180 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  842): Process com.uei.lg.quicksetsdk.lite (pid 4731) has died
,I/Icing   ( 4008): Post-init done
I/Icing   ( 4008): updateResources: need to parse f{com.google.android.gms}
D/CAR.SERVICE( 5113): Connecting to CarCallService...
,I/art     ( 5113): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5113): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 5113): com.google.android.projection.gearhead isn't installed.
,I/ActivityManager(  842): Process com.lge.email (pid 5069) has died
,D/CAR.TEL.Service( 5113): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5113): Creating a new PhoneAdapter instance
W/ActivityManager(  842): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5113): setListener: com.google.android.gms.car.dn@93e5284
W/ActivityManager(  842): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5113): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 5113): Starting CarCallService with initial phone null
,D/[BNRAppListMgrReceiver]( 5180): android.intent.action.PACKAGE_ADDED : com.test.thalitest
,I/NotificationManager( 5113): com.google.android.gms: cancel(10436) by com.google.android.gms
W/MainApplication( 5180): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
D/CAR.SERVICE( 5113): Package validated; name: com.android.vending
,D/InitAlarmsService( 3534): Clearing and rescheduling alarms.
,I/ActivityManager(  842): Process com.google.android.apps.plus (pid 5011) has died
,I/NotificationManager( 4933): com.android.vending: cancel(1003285959) by com.android.vending
I/art     (  842): Explicit concurrent mark sweep GC freed 37831(1931KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 2.398ms total 179.897ms
,I/ActivityManager(  842): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5203 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/Finsky  ( 4933): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,I/ActivityManager(  842): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5221 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/NotificationManager( 4933): com.android.vending: cancel(10436) by com.android.vending
,W/ResourcesManager( 5203): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
V/Finsky  ( 4933): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/CalendarProvider2( 5203): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3906c18a
,D/CalendarProvider2( 5203): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5203): Created com.android.providers.calendar.CalendarAlarmManager@307f84d7(com.android.providers.calendar.CalendarProvider2@3906c18a)
D/CalendarProvider2( 5203): Scheduling check of next Alarm
D/CalendarProvider2( 5203): SCHEDULE_ALARM_REMOVE
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  842): android: cancelAsUser(2) by android
D/libc-netbsd( 4933): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4933): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 4933): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 4933): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  842): RTC_WAKEUP set : Alarm{3ce9f71 type 0 when 1457489094807 com.android.vending} when 1457489094807
,D/Finsky  ( 4933): [1] DailyHygiene.reschedule: Scheduling new run in 32 minutes (failures=2)
,D/DeviceConnectionService( 1726): client connected with version: 8296000
,I/ActivityManager(  842): Process com.android.calendar (pid 3534) has died
,D/WearableService( 1726): callingUid 10006, callindPid: 1726
,D/Finsky  ( 4933): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 4933): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  842): Killing 4028:com.android.defcontainer/u0a4 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_10004/pid_4028/cgroup.procs: No such file or directory
,I/CheckinService( 4008): Done disabling old GoogleServicesFramework version
I/GAv4    ( 5221): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5221):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5221):   adb logcat -s GAv4
,W/GAv4    ( 5221): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5221): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5221): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/Icing   ( 4008): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
W/AnalyticsTrackerProxyImpl( 5221): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,I/ActivityManager(  842): Process com.android.contacts (pid 4885) has died
,D/Icing   ( 4008): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 4008): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,E/VoldCmdListener(  247): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  247): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  247): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5221): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 5221): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5221): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  842): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5259 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  842): Killing 5135:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_10009/pid_5135/cgroup.procs: No such file or directory
,W/ResourcesManager( 5259): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 5221): CheckpointMarkThreadRoots callback created = 0xb050fa30
V/JNIHelp ( 5221): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/art     ( 5221): CheckpointMarkThreadRoots callback created = 0xb050fa10
,I/art     ( 3093): Explicit concurrent mark sweep GC freed 7907(518KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 398us total 35.516ms
,W/System  ( 5221): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5221): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  842): Process com.android.gallery3d (pid 4864) has died
V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CalendarProvider2( 5203): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5203): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  842): Killing 4664:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  842): failed to open /acct/uid_10061/pid_4664/cgroup.procs: No such file or directory
,I/ActivityManager(  842): Killing 4841:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  842): failed to open /acct/uid_10011/pid_4841/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 4008): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraCfgMgr( 4008): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4008): Loading module APK com.google.android.play.games
I/UpdateIcingCorporaServi( 1930): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1930): UpdateCorporaTask done [took 70 ms] updated apps [took 70 ms] 
,D/ChimeraCfgMgr( 4008): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4008): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4008): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 4008): Submit a task: k
,D/ChimeraCfgMgr( 4008): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 4008): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 4008): Processing package: com.test.thalitest
D/GassUtils( 4008): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,D/k       ( 4008): Found info for package com.test.thalitest in db.
E/MDM     ( 1726): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/PeopleDatabaseHelper( 4008): cleanUpNonGplusAccounts done.
D/AuthorizationBluetoothService( 1726): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/BaseAppContext( 4008): Using Auth Proxy for data requests.
D/LocationInitializer( 4008): Restart initialization of location
W/BaseAppContext( 4008): Using Auth Proxy for data requests.
V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1726): com.google.android.gms: cancel(0) by com.google.android.gms
W/BaseAppContext( 4008): Using Auth Proxy for data requests.
D/Finsky  ( 4933): [554] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,I/ActivityManager(  842): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5306 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1726): No location to return for getLastLocation()
,W/FusedLocationProvider( 1726): location=null
W/BaseAppContext( 4008): Using Auth Proxy for data requests.
V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  842): android: cancelAsUser(2) by android
,W/BaseAppContext( 4008): Using Auth Proxy for data requests.
,W/ResourcesManager( 5306): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/libc-netbsd( 4933): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4933): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4933): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4933): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  842): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/CalendarApplication( 5306): CalendarApplication.onCreate()
D/PreferenceKeysParser( 5306): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 5306): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@15627c18, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@2f4e5671, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@f176c56, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@307f84d7, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@160f41c4, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2c20e8ad, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@33b5f7e2, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@10cd9773, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@21a0b630, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@221062a9, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@36bfb02e, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@28e037cf, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3193055c, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@28638065, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@369aa13a, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@9d281eb, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@38f91b48, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@a10bde1, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@20019706, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@315551c7, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@728a3f4, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@30fa571d, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@1e901d92, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1d4b4363, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@29260b60, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@8ea4819, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@a0e80de, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@3d24b2bf, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@35d07d8c, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@164e4cd5, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@1c7dccea, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1cfbbbdb, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@30cde678, lg_preferences_w,eek_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3cb3e151, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@3ce3cdb6, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@26703ab7, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3036f224, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3104418d, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2ad70f42, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1343cb53, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@31030c90, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@1380
D/GeneralPreferenceUtils( 5306): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 5306): [init]
I/Config  ( 5306): LGCalendar ver.4.40.17
I/Config  ( 5306): start check model
I/Config  ( 5306): start check native_ca
I/Config  ( 5306): Config Operator=OPEN, Country=EU
D/Config  ( 5306): [setDefaultValuesToPref]
D/Config  ( 5306): [parseProfiles]
D/ProfilesParser( 5306): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 5306): [debug_displayParseInfos] profile.operator = null
D/Config  ( 5306): [updateProfiletoCountryInfo]
D/GeneralPreference( 5306): [checkAndMigrateOldPreference]
D/AlertReceiver( 5306): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 5306): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 5306): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 5306): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 5306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 5306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 5306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 5306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 5306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 5306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 5306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 5306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 5306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 5306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 5306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 5306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 5306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 5306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 5306): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 5306): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 5306): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 5306): End InitializeAlertRingtoneService.onHandleIntent
,W/HolidayIntentService( 5306): onHandleIntent
,D/HolidayDataLoader( 5306): readJsonAsset : holiday.json
E/AgendaWidgetManager( 5306): [updateWidgets] 
,D/AlertService( 5306): 0 Action = android.intent.action.PROVIDER_CHANGED
D/MonthWidgetProvider( 5306): [onReceive]
D/CalendarWidgetProvider( 5306): [onReceive]
D/CalendarWidgetProvider( 5306): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 5306): [onCreate] mContext.getPackageName() = com.android.calendar
,D/WeekWidgetProvider( 5306): [onReceive]
D/CalendarWidgetProvider( 5306): [onReceive]
D/CalendarWidgetProvider( 5306): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 5306): [onCreate] mContext.getPackageName() = com.android.calendar
E/HolidayIntentService( 5306): onHandleIntent:holiday data empty
,D/ChimeraCfgMgr( 4008): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4008): Module APK com.google.android.play.games already loaded
I/Icing   ( 4008): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4008): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 297, mChargingStatus=5, mChargingStop=false
,I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/WifiController(  842): battery changed pluggedType: 2
W/MainApplication( 5180): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 298, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
W/MainApplication( 5180): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/chromium( 4966): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 4966): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/CAR.SERVICE( 5113): mConnectedToCar = false, abort
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{b21f0a7 type 2 when 83890 com.android.providers.calendar} when 83890
,E/ActivityThread( 5113): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1f31b1ec that was originally bound here
E/ActivityThread( 5113): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1f31b1ec that was originally bound here
E/ActivityThread( 5113): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5113): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5113): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5113): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5113): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5113): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5113): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5113): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5113): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5113): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5113): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5113): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5113): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5113): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5113): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5113): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5113): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5113): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5113): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5113): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5113): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5113): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5113): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 5113): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@31316097 that was originally bound here
E/ActivityThread( 5113): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@31316097 that was originally bound here
E/ActivityThread( 5113): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5113): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5113): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5113): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5113): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5113): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5113): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5113): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5113): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5113): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5113): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5113): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5113): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 5113): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 5113): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 5113): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5113): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5113): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5113): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5113): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5113): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5113): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  842): Unbind failed: could not find connection for android.os.BinderProxy@1cf08954
D/CalendarProviderBroadcastReceiver( 5203): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,D/CalendarProviderBroadcastReceiver( 5203): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 5203): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 5203): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5203): [getOrCreateCalendarAlarmManager]
D/CalendarProvider2( 5203): [IntentService] Release Lock
,D/CalendarProvider2( 5203): CalendarProviderIntentService.onDestroy()
D/PowerManagerServiceEx(  842): acquireWakeLockInternal: lock=1063352393, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=842
,D/WeatherService( 2704): 2 : TimeTick Intent has been received, Time(hour:min:sec) 3:5:0
,D/WeatherService( 2704): 2 : TimeTick Intent And Screen On
D/WeatherService( 2704): 2 : SDK version : 21
W/ActivityManager(  842): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2704): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2704): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2704): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2704): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2704): 2 : This is isUpdating : false
D/WeatherService( 2704): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2704): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2704): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2704): 2 : Fixed theme : optimus
,D/WeatherReflect( 2704): 2 : Map key string is -2
D/lim     ( 2704): 2 : time = 03:05
I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
,I/WeatherReflect( 2704): Model Name : LG-D722
D/WeatherTheme( 2704): 2 : Different view - status_min_formatted : 04 != 05
D/WeatherTheme( 2704): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2704): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
,D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2704): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
D/Weather4x2_optimus( 2704): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
,D/Weather4x2_optimus( 2704): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2704): forecast size is 0
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2704): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2704): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2704): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2704): url is : null
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2704): 2 : update view, appWidgetId: 2
D/WeatherService( 2704): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 3:5:0
D/PowerManagerServiceEx(  842): releaseWakeLockInternal: lock=1063352393 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1871): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1871): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/NotificationManager( 1930): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,D/AlertService( 5306): Beginning updateAlertNotification
,D/AlertService( 5306): No fired or scheduled alerts
,I/NotificationManager( 5306): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5306): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5306): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5306): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5306): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5306): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5306): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5306): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5306): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5306): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5306): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5306): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5306): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5306): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5306): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5306): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5306): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5306): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5306): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5306): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5306): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5306): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,I/art     (  842): Explicit concurrent mark sweep GC freed 22568(1154KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 1.935ms total 148.440ms
,D/AlarmScheduler( 5306): No events found starting within 1 week.
,I/ActivityManager(  842): Killing 4915:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  842): failed to open /acct/uid_10069/pid_4915/cgroup.procs: No such file or directory
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{26f03b3e type 2 when 87331 com.google.android.gms} when 87331
,D/libc-netbsd( 1726): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1726): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1726): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1726): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  842): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ActivityManager(  842): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5396 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5396): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5396): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5396): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5396): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5396): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5396): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5396): MmsConfig.loadFromResources
E/Babel_SMS( 5396): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5396): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 5396): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5396): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5396): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 5396): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5396): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5396): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5396): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5396): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5396): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5396): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5396): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5396): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5396): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5396): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5396): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5396): found sensor: Motion Accel, handle=46
I/art     ( 5396): CheckpointMarkThreadRoots callback created = 0xaaf3d540
,W/Settings( 5396): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5396): startup - clean
I/art     ( 5396): CheckpointMarkThreadRoots callback created = 0xaaf3d520
,I/Babel   ( 5396): deleted: false for 0
W/AudioCapabilities( 5396): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5396): Unsupported mime audio/adpcm
W/AudioCapabilities( 5396): Unsupported mime audio/g726
W/AudioCapabilities( 5396): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5396): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5396): Unsupported mime video/mjpg
W/VideoCapabilities( 5396): Unsupported mime video/theora
W/AudioCapabilities( 5396): Unsupported mime audio/evrc
W/AudioCapabilities( 5396): Unsupported mime audio/qcelp
W/VideoCapabilities( 5396): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5396): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5396): Unsupported mime audio/qcelp
W/AudioCapabilities( 5396): Unsupported mime audio/evrc
,W/VideoCapabilities( 5396): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 5396): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5396): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5396): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5396): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5396): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  842): Killing 5163:com.lge.eula/1000 (adj 15): empty #11
,W/libprocessgroup(  842): failed to open /acct/uid_1000/pid_5163/cgroup.procs: No such file or directory
,I/vclib   ( 5396): onServiceConnected
W/Babel   ( 5396): Attempted to change video mute state without an active call.
I/NotificationManager( 5396): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  842): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 92701403804; DSPS: 3129205; Offset : -2806774589
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  842): RTC_WAKEUP set : Alarm{203fefee type 0 when 1457489109581 com.android.vending} when 1457489109581
,D/Finsky  ( 4933): [545] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4933): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
W/ContextImpl( 3372): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/MusicWidget( 2648): mDelayedStopHandler : unbind
,I/MusicBrowser( 2726): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2726): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2726): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2726): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2726): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2726): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2726): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2726): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  842):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@30fa571dcom.lge.music.MediaPlaybackService$6@1e901d92
,D/MusicBrowser( 2726): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2726): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2726): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2726): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2726): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@21a0b630
I/MusicBrowser( 2726): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2726): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2726): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2726): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2726): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2726): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2726): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2726): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2726): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2726): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2726): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2726): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2726): [MediaPlaybackService.java:6706:stop()] oooooo 
,I/MediaPlayer[Native]( 2726): reset
V/MediaPlayer[Native]( 2726): setListener
,V/MediaPlayer[Native]( 2726): disconnect
V/MediaPlayer[Native]( 2726): destructor
V/AudioFlinger(  279): releasing 19 from 2726 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/MediaPlayer[Native]( 2726): disconnect
D/MusicBrowser( 2726): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2726): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2726): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2726): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2726): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2726): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2726): [SmartShareManagerClient] unregisterListener: 491471715
W/SmartShareClient( 2726): [SmartShareManagerClient] unregisterListener invalid listener: 491471715
I/SmartShareClient( 2726): [SmartShareManagerClient] terminate service: 2726/MediaPlaybackService/253193302
E/HomeCloudIF( 2726): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2726): [SmartShareManagerClient] unbindService context:android.app.Application@29260b60
V/CloudHub( 2726): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2726): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2726): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2726): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2726): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  842): Killing 5180:com.lge.bnr/1000 (adj 15): empty #11
I/CloudHub( 2726): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29987
,W/libprocessgroup(  842): failed to open /acct/uid_1000/pid_5180/cgroup.procs: No such file or directory
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 112703703368; DSPS: 3784641; Offset : -2806793996
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:32000 mC
,I/CloudHub( 2726): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19946
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
,I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
D/WifiController(  842): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
,I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 297, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{3667dc8f type 2 when 126264 com.google.android.gms} when 126264
,D/libc-netbsd( 1726): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1726): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1726): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1726): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  842): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
,I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 132706026933; DSPS: 4440077; Offset : -2806789794
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/CloudHub( 2726): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
,I/CloudHub( 2726): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  842): acquireWakeLockInternal: lock=1063352393, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=842
,D/WeatherService( 2704): 2 : TimeTick Intent has been received, Time(hour:min:sec) 3:6:0
D/WeatherService( 2704): 2 : TimeTick Intent And Screen On
D/WeatherService( 2704): 2 : SDK version : 21
W/ActivityManager(  842): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2704): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2704): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2704): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2704): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2704): 2 : This is isUpdating : false
D/WeatherService( 2704): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2704): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2704): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2704): 2 : Fixed theme : optimus
,D/WeatherReflect( 2704): 2 : Map key string is -2
D/lim     ( 2704): 2 : time = 03:06
I/WeatherReflect( 2704): Model Name : LG-D722
D/WeatherTheme( 2704): 2 : Different view - status_min_formatted : 05 != 06
D/WeatherTheme( 2704): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2704): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2704): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2704): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2704): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2704): forecast size is 0
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2704): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2704): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2704): setTouchIntent, appWidgetId: 2
,D/Theme_WeatherAncestor_optimus( 2704): url is : null
D/Theme   ( 2704): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2704): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2704): 2 : update view, appWidgetId: 2
I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
D/WeatherService( 2704): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 3:6:0
I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
,D/PowerManagerServiceEx(  842): releaseWakeLockInternal: lock=1063352393 [*alarm*], flags=0x0
I/[LgeWidgetLib]LgeAppWidgetHostView( 1871): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1871): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/PowerManagerService(  842): ALS enabled for SRE
,D/PowerManagerServiceEx(  842): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26041 ms ago)
D/qdlights(  842): set_light_backlight: 252
,D/qdlights(  842): set_light_backlight: 249
D/qdlights(  842): set_light_backlight: 246
,D/qdlights(  842): set_light_backlight: 242
,D/qdlights(  842): set_light_backlight: 239
,D/qdlights(  842): set_light_backlight: 236
,D/qdlights(  842): set_light_backlight: 232
,D/qdlights(  842): set_light_backlight: 229
,D/qdlights(  842): set_light_backlight: 226
,D/qdlights(  842): set_light_backlight: 222
,D/qdlights(  842): set_light_backlight: 219
,D/qdlights(  842): set_light_backlight: 216
,D/qdlights(  842): set_light_backlight: 212
,D/qdlights(  842): set_light_backlight: 209
,D/qdlights(  842): set_light_backlight: 206
,D/qdlights(  842): set_light_backlight: 202
,D/qdlights(  842): set_light_backlight: 199
,D/qdlights(  842): set_light_backlight: 196
,D/qdlights(  842): set_light_backlight: 192
,D/qdlights(  842): set_light_backlight: 189
,D/qdlights(  842): set_light_backlight: 186
,D/qdlights(  842): set_light_backlight: 182
,D/qdlights(  842): set_light_backlight: 179
,D/qdlights(  842): set_light_backlight: 176
,D/qdlights(  842): set_light_backlight: 173
,D/qdlights(  842): set_light_backlight: 169
,D/qdlights(  842): set_light_backlight: 166
,D/qdlights(  842): set_light_backlight: 163
,D/qdlights(  842): set_light_backlight: 159
,D/qdlights(  842): set_light_backlight: 156
,D/qdlights(  842): set_light_backlight: 153
,D/qdlights(  842): set_light_backlight: 149
,D/qdlights(  842): set_light_backlight: 146
,D/qdlights(  842): set_light_backlight: 143
,D/qdlights(  842): set_light_backlight: 139
,D/qdlights(  842): set_light_backlight: 136
,D/qdlights(  842): set_light_backlight: 133
,D/qdlights(  842): set_light_backlight: 129
,D/qdlights(  842): set_light_backlight: 126
,D/qdlights(  842): set_light_backlight: 123
,D/qdlights(  842): set_light_backlight: 119
,D/qdlights(  842): set_light_backlight: 116
,D/qdlights(  842): set_light_backlight: 113
,D/qdlights(  842): set_light_backlight: 109
,D/qdlights(  842): set_light_backlight: 106
,D/qdlights(  842): set_light_backlight: 103
,D/qdlights(  842): set_light_backlight: 99
,D/qdlights(  842): set_light_backlight: 96
,D/qdlights(  842): set_light_backlight: 92
,D/qdlights(  842): set_light_backlight: 89
,D/qdlights(  842): set_light_backlight: 86
,D/qdlights(  842): set_light_backlight: 82
,D/qdlights(  842): set_light_backlight: 79
,D/qdlights(  842): set_light_backlight: 76
,D/qdlights(  842): set_light_backlight: 72
,D/qdlights(  842): set_light_backlight: 69
,D/qdlights(  842): set_light_backlight: 66
,D/qdlights(  842): set_light_backlight: 62
,D/qdlights(  842): set_light_backlight: 59
,D/qdlights(  842): set_light_backlight: 56
,D/qdlights(  842): set_light_backlight: 52
,D/qdlights(  842): set_light_backlight: 49
,D/qdlights(  842): set_light_backlight: 46
,D/qdlights(  842): set_light_backlight: 42
,D/qdlights(  842): set_light_backlight: 39
,D/qdlights(  842): set_light_backlight: 36
,D/qdlights(  842): set_light_backlight: 32
,D/qdlights(  842): set_light_backlight: 29
,D/qdlights(  842): set_light_backlight: 26
,D/qdlights(  842): set_light_backlight: 22
,D/qdlights(  842): set_light_backlight: 19
,D/qdlights(  842): set_light_backlight: 16
,D/qdlights(  842): set_light_backlight: 12
,D/qdlights(  842): set_light_backlight: 10
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{3506ab1c type 2 when 127709 com.google.android.gms} when 127709
,D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  842): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 152707468083; DSPS: 5095483; Offset : -2806752844
,I/PowerManagerService(  842): ALS enabled for SRE
D/PowerManagerServiceEx(  842): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33038 ms ago)
,I/PowerManagerService(  842): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  842): ALS enabled for SRE
D/PowerManagerServiceEx(  842): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33056 ms ago)
W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  842): Sleeping (uid 1000)...
D/LPWGController(  842): [updateScreenState] screen on = false
D/LPWGController(  842): disable proximity sensor
D/LPWGController(  842): enable proximity sensor
I/SensorManager(  842): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@fa19325] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  842): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  842): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  842): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  842): activate: handle is 48, enable
V/sensors_hal_Ctx(  842): activate sensors is 1400000000000
D/sensors_hal_Thresh(  842): enable: handle=48
I/sensors_hal_SAM(  842): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  842): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  842): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  842): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  842): enable: Received response: 0
D/PowerManagerServiceEx(  842): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33101 ms ago)
,I/Adreno-EGL(  842): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  842): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  842): Build Date: 03/02/15 Mon
I/Adreno-EGL(  842): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  842): Remote Branch: 
I/Adreno-EGL(  842): Local Patches: 
I/Adreno-EGL(  842): Reconstruct Branch: 
,D/PermissionCache(  248): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (145 us)
,I/Sensors (  430): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  842): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  842): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  842): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  842): processInd: handle 48, count=1
V/sensors_hal_Thresh(  842): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  842): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  842): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  842): poll: count: 256
I/sensors_hal_Ctx(  842): poll: released wakelock sensor_ind
D/sensors_hal_Util(  842): waitForResponse: timeout=0
D/LPWGController(  842): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  842): current mode = 1  value = 1 1
I/LPWGController(  842): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  842): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/qdlights(  842): set_light_backlight: 0
,I/SensorManager(  842): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  842): activate: handle is 46, disable
V/sensors_hal_Ctx(  842): activate sensors is 1000000000000
D/sensors_hal_LP2(  842): enable: handle=46
D/sensors_hal_LP2(  842): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  842): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  248): Set power mode=0, type=0 flinger=0xb6082000
I/DisplayManagerService(  842): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  842): Display changed displayId=0
D/qdhwcomposer(  248): hwc_blank: Blanking display: 0
,V/sensors_hal_SAM(  842): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  842): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1745): Display #0 changed.
D/qdhwcomposer(  248): hwc_blank: Done blanking display: 0
,I/qdhwcomposer(  248): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  842): Excessive delay in setPowerMode(): 259ms
I/QCOM PowerHAL(  842): Got set_interactive hint
D/KeyguardViewMediator( 1363): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1328): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1363): notifyScreenOffLocked
D/JX-Cordova( 4966): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4966): load: Already loaded
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4966): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ec3dda8 added. We now have 3 listener(s)
D/BluetoothManagerService(  842): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4966): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4966): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/SmartCoverViewMediator( 1328): notifyScreenOffLocked
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4966): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4966): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edec0c1 added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4966): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4966): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4966): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4966): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4966): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4966): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4966): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4966): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4966): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4966): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4966): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4966): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
D/SmartCoverViewMediator( 1328): handleNotifyScreenOFF
D/KeyguardViewMediator( 1363): setting alarm to turn off keyguard, seq = 1, timeout = 5000
W/System.err( 4966): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4966): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4966): 	at android.os.Looper.loop(Looper.java:135)
D/KeyguardViewMediator( 1363): handleNotifyScreenOff
W/System.err( 4966): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ScreenTurnOffBySensor( 1363): unregisterProximitySensor
,D/WifiServerServiceExt(  842): sendKtScanInterval  mRtspPlay : false
D/StatusBarWindowView( 1363): onScreenTurnedOff why = 3
V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=on, calling pid 842
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
,D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
D/GpsLocationProvider(  842): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1834): |CORE| sendScreenState: state:true
I/LEDService( 1798): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1798): stopPatternFlashing()
D/qdlights( 1798): set_light_notifications: 0,0,0,0,3
I/LEDService( 1798): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1798): set_light_notifications: 0,0,0,0,3
,I/LEDService( 1798): updateLightsLocked : turn off led
D/qdlights( 1798): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1798): RESTART MSG
D/SplitWindow(  842): check instance of lgWin Window{35615d08 u0 SearchPanel}
,I/Cliptray Service( 1798): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1798): lockStatus = 0
D/InputDispatcher(  842): Window went away: Window{257a3db u0 SearchPanel}
,I/[SystemUI]Clock( 1363): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1363): time changed, timezoneChanged : false
,D/LNfcService( 1781): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1781): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1781): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1781): isRequireNfcCRouting() return true
D/LNfcService( 1781): isHCERoutingtoHost() return : true
D/NfcService( 1781): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1781): mEnableLPD: true
D/NfcService( 1781): mEnableReader: false
D/NfcService( 1781): mEnableHostRouting: true
D/NfcService( 1781): newParams.techmask= mTechMask: default
D/NfcService( 1781): mEnableLPD: true
D/NfcService( 1781): mEnableReader: false
D/NfcService( 1781): mEnableHostRouting: true
D/NfcService( 1781): screenState= 3
D/NfcService( 1781): Discovery configuration equal, not updating.
D/Ulp_jni (  842): JNI:system_update. Event-0
,V/PhoneApp( 1745): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2704): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 3:6:10
D/WeatherService( 2704): 2 : ACTION screen on
,D/WeatherService( 2704): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2704): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2704): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 3:6:10
D/AppCleanupService( 3817): android.intent.action.SCREEN_ON
,V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=off, calling pid 842
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
D/WifiController(  842): CMD_SCREEN_OFF 
D/WifiController(  842): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  842): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1834): |CORE| sendScreenState: state:false
I/LEDService( 1798): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1798): stopPatternFlashing()
D/qdlights( 1798): set_light_notifications: 0,0,0,0,3
I/LEDService( 1798): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1798): set_light_notifications: 0,0,0,0,3
I/LEDService( 1798): updateLightsLocked : turn on led
E/LEDService( 1798): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1798): Can't handle this request of patternId:0
D/LEDHandler( 1798): RESTART MSG
D/VolumeVibrator( 1798): clear
,I/Cliptray Service( 1798): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1781): action : android.intent.action.SCREEN_OFF
,D/NfcServiceNXP( 1781): mScreenState : 1, mInProvisionMode : false
I/Sensors (  430): sns_pwr.c(301):releasing wakelock
I/[LGHome]EVENT( 1871): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1745): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2704): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 3:6:10
D/WeatherService( 2704): 2 : ACTION screen off
D/WeatherService( 2704): 2 : TimeTick Receiver Unregister
D/WeatherService( 2704): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 3:6:10
D/AppCleanupService( 3817): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 3817): AppUsageStatsSaveTask
E/NxpNfcJni( 1781): getReconnectState = 0x0
,D/LCardEmulationManager( 1781): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1781): getDefaultRoute
D/LNfcService( 1781): isRequireNfcCRouting() return true
D/LNfcService( 1781): isHCERoutingtoHost() return : true
D/NfcService( 1781): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1781): mEnableLPD: true
D/NfcService( 1781): mEnableReader: false
D/NfcService( 1781): mEnableHostRouting: true
D/NfcService( 1781): newParams.techmask= mTechMask: 0
D/NfcService( 1781): mEnableLPD: true
D/NfcService( 1781): mEnableReader: false
D/NfcService( 1781): mEnableHostRouting: true
D/NfcService( 1781): screenState= 1
E/NxpNfcJni( 1781): getReconnectState = 0x0
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{20fd3ca1 type 2 when 159045 com.android.systemui} when 159045
,D/KeyguardViewMediator( 1363): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1745): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1745): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1745): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1745): getCallState : 0
,D/PhoneUtils( 1745): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1745): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1745): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1363): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1363): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 172709851072; DSPS: 5750922; Offset : -2806779961
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1726): disconnect managed GoogleApiClient
,I/ThermalEngine(  291): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{39d20ec6 type 2 when 184854 com.google.android.gms} when 184854
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{1214ce87 type 2 when 185933 com.google.android.gms} when 185933
,D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 292, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 192712150855; DSPS: 6406357; Offset : -2806769257
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{d3341b4 type 2 when 204131 com.google.android.gms} when 204131
,D/libc-netbsd( 1726): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1726): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1726): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1726): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  842): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 212714364795; DSPS: 7061789; Offset : -2806752557
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{21001dd type 2 when 196815 android} when 196815
V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{f505152 type 2 when 215939 com.google.android.gms} when 215939
,D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  842): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  842): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  275): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  842): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/VacuumService( 1726): Vacuum at: now=1457489242064 tag=VacuumService
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 232716650768; DSPS: 7717223; Offset : -2806724859
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
,I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 252718664417; DSPS: 8372651; Offset : -2806786430
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 272719642740; DSPS: 9028042; Offset : -2806753970
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 287721725177; DSPS: 9519630; Offset : -2806746938
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 305225097592; DSPS: 10093183; Offset : -2806822930
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 320227296592; DSPS: 10584772; Offset : -2806729645
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 340229482903; DSPS: 11240196; Offset : -2806496589
,I/LocationManagerService(  842): remove 3a43680a
,D/LocationManagerService(  842): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  842): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  842): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  842): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  842): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
,I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 354301714685; DSPS: 11701324; Offset : -2806774518
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/WifiController(  842): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  842): acquireWakeLockInternal: lock=1063352393, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=842
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{2b8fded9 type 2 when 359825 com.google.android.gms} when 359825
D/libc-netbsd( 1726): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1726): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1726): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1726): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/PowerManagerServiceEx(  842): releaseWakeLockInternal: lock=1063352393 [*alarm*], flags=0x0
D/DSQN    (  842): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
,I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 369303947244; DSPS: 12192919; Offset : -2806830830
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 1726): Explicit concurrent mark sweep GC freed 41152(2MB) AllocSpace objects, 23(368KB) LOS objects, 40% free, 13MB/22MB, paused 2.519ms total 120.838ms
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  842): android: cancelAsUser(2) by android
,D/libc-netbsd( 4933): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4933): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4933): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4933): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  842): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
,I/[SystemUI]Clock( 1363): called onTimeUpdated()
I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 389306028702; DSPS: 12848345; Offset : -2806763455
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 409308554322; DSPS: 13503788; Offset : -2806770768
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 424311238539; DSPS: 13995398; Offset : -2806833210
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 442139365936; DSPS: 14579580; Offset : -2806525664
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 457146790089; DSPS: 15071337; Offset : -2806334125
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 470278558049; DSPS: 15501654; Offset : -2806798804
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 490280707924; DSPS: 16157081; Offset : -2806693634
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 504352743691; DSPS: 16618196; Offset : -2806770903
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 519354990390; DSPS: 17109791; Offset : -2806813048
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 539357254422; DSPS: 17765186; Offset : -2805617082
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
,I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 553428953773; DSPS: 18226340; Offset : -2807221002
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 574060704291; DSPS: 18902391; Offset : -2806909590
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 588133626359; DSPS: 19363521; Offset : -2806558298
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 603461059291; DSPS: 19865785; Offset : -2807006432
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
,I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 617217043746; DSPS: 20316533; Offset : -2806759257
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 632219185404; DSPS: 20808115; Offset : -2806509742
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 645356573330; DSPS: 21238609; Offset : -2806756040
,D/PowerManagerServiceEx(  842): acquireWakeLockInternal: lock=1063352393, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=842
,V/AlarmManager(  842): RTC_WAKEUP set : Alarm{18047fe4 type 0 when 1457489629076 com.google.android.gms} when 1457489629076
D/PowerManagerServiceEx(  842): releaseWakeLockInternal: lock=1063352393 [*alarm*], flags=0x0
,I/EventLogService( 4008): Aggregate from 1457487828992 (log), 1457487828992 (data)
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 664112401476; DSPS: 21853194; Offset : -2806573543
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{5193049 type 2 when 671225 com.google.android.gms} when 671225
,D/libc-netbsd( 1726): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1726): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1726): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1726): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  842): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  842): android: cancelAsUser(2) by android
,D/libc-netbsd( 4933): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4933): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4933): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4933): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  842): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 686616143649; DSPS: 22590620; Offset : -2807286934
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 700224288804; DSPS: 23036517; Offset : -2806838287
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 720860666894; DSPS: 23712727; Offset : -2806751519
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
,I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 740863049735; DSPS: 24368165; Offset : -2806749232
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 760865381510; DSPS: 25023603; Offset : -2806797879
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 780867624916; DSPS: 25679036; Offset : -2806782204
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 800869758613; DSPS: 26334466; Offset : -2806784609
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 820872024318; DSPS: 26989898; Offset : -2806716403
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 840874435884; DSPS: 27645341; Offset : -2806837821
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
,I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 860876640520; DSPS: 28300773; Offset : -2806830399
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 880878973168; DSPS: 28956208; Offset : -2806786570
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 900881633401; DSPS: 29611655; Offset : -2806781392
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
,I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 920883823915; DSPS: 30267087; Offset : -2806788065
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 940886082859; DSPS: 30922518; Offset : -2806695974
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 960888241961; DSPS: 31577947; Offset : -2806642612
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
,I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 975890514747; DSPS: 32069542; Offset : -2806658618
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  842): android: cancelAsUser(2) by android
,D/libc-netbsd( 4933): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4933): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4933): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4933): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  842): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 997146046810; DSPS: 32766052; Offset : -2806924763
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1012148334337; DSPS: 33257642; Offset : -2806773494
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1025278758450; DSPS: 33687901; Offset : -2806812052
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1038417754626; DSPS: 34118440; Offset : -2806823497
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1055613678881; DSPS: 34681912; Offset : -2806699998
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1070615087802; DSPS: 35173480; Offset : -2806755869
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1083749521832; DSPS: 35603871; Offset : -2806812596
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 267
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 267
,D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 267, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1097363461526; DSPS: 36049973; Offset : -2806825721
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1113785951765; DSPS: 36588084; Offset : -2806180071
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1128963034215; DSPS: 37085432; Offset : -2806953986
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1143513262918; DSPS: 37562201; Offset : -2806560463
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1156657558952; DSPS: 37992916; Offset : -2806643065
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1170108828039; DSPS: 38433693; Offset : -2806820562
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1184187756553; DSPS: 38895028; Offset : -2806719032
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1204979232487; DSPS: 39576316; Offset : -2806502915
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
I/[SystemUI]LGPowerUI( 1363): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1363): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 265
,I/QCNEJ   ( 1834): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1834): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1798): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1798): Battery Level Remaining: 100%
D/LEDHandler( 1798): Battery Temp: 265, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1363): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1219520925376; DSPS: 40052831; Offset : -2806893739
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/UsageStatsService(  842): User[0] Flushing usage stats to disk
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1240152797807; DSPS: 40728893; Offset : -2806796028
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1260155079913; DSPS: 41384327; Offset : -2806772458
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1363): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1363): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1363): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1363): On Skip Timer : true
,D/PowerService( 1798): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  471): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1275159907524; DSPS: 41876023; Offset : -2807315601
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1726): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  842): android: cancelAsUser(2) by android
,D/libc-netbsd( 4933): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4933): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4933): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4933): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  275): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  842): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1363): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1363): called onTimeUpdated()
I/[SystemUI]Clock( 1363): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
I/[SystemUI]DateView( 1363): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1363): handleTimeUpdate
I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  842): acquireWakeLockInternal: lock=1063352393, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=842
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{20209cb0 type 2 when 1293959 com.google.android.gms} when 1293959
D/PowerManagerServiceEx(  842): releaseWakeLockInternal: lock=1063352393 [*alarm*], flags=0x0
,D/libc-netbsd( 1726): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1726): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1726): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1726): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  842): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  291): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1296414946528; DSPS: 42572493; Offset : -2806854417
,TIME-OUT KILL (timeout was 1200000ms)
```
