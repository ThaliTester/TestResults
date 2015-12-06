#### Test 50242285576d0b0_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/art     ( 4013): CheckpointMarkThreadRoots callback created = 0xb042dba0
--------- beginning of system
W/ResourcesManager( 4013): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4013): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 4013): CheckpointMarkThreadRoots callback created = 0xb042db80
,E/YouTube MDX( 4013): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
I/dex2oat ( 4057): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-796081260.jar --oat-fd=25 --oat-location=/data/data/com.google.android.youtube/cache/ads-796081260.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
D/libc-netbsd( 4013): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4013): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/art     ( 4013): Suspending all threads took: 10.275ms
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4013): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
I/ActivityManager(  975): Waited long enough for: ServiceRecord{2df6c7d u0 com.google.android.gms/.gcm.GcmService}
I/dex2oat ( 4057): dex2oat took 148.013ms (threads: 4)
D/AndroidRuntime( 4064): 
D/AndroidRuntime( 4064): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4064): CheckJNI is OFF
I/NotificationManager( 4013): com.google.android.youtube: cancel(2) by com.google.android.youtube
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4013): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4013): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/CursorWrapperInner( 3699): Cursor finalized without prior close()
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4013): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/InstanceID/Rpc( 4013): Found 10006
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4013): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
D/AndroidRuntime( 4064): Calling main entry com.android.commands.am.Am
I/ActivityManager(  975): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  975): setTaskToReturnTo : TaskRecord{1686e925 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  975): setTaskToReturnTo : TaskRecord{1686e925 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  975): AppWindowTokenEx init.. 
D/ContextHelper(  975): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/InputDispatcher(  975): Focus left window: Window{c68779f u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 4064): Shutting down VM
I/[LGHome]EVENT( 1964): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  975): check instance of lgWin Window{188fefb4 u0 Starting com.example.hello}
I/ActivityManager(  975): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4124 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  975): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4141 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1964): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 2041): Closing mic
I/MicrophoneInputStream( 2041): mic_close com.google.android.apps.gsa.speech.audio.u@3ae6902c
V/AudioRecord( 2041): stop()
D/AudioRecord( 2041): AudioRecord->stop()
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
I/[LGHome]EVENT( 1964): [Launcher.java:5214:onStop()]onStop
I/NotificationManager( 4013): com.google.android.youtube: cancel(10436) by com.google.android.youtube
V/AudioFlinger(  281): Record stopped OK
V/AudioPolicyManager(  281): stopInput() input 17
V/AudioPolicyService(  281): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  281): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  281): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  281): ThreadBase::setParameters() routing=0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb397c000
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
I/WindowStateAnimator(  975): Starting window displayed
I/SystemUI[Framework](  975): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
W/PhoneWindowManagerEx(  975): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  975): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  975): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PhoneStatusBar( 1388): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/SystemUI[Framework](  975): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@9fde3b4,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  975): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1388): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1388):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1388): , Keyguard show=false, IME shown=false, Panel expanded=false
I/ActivityManager(  975): Killing 3675:com.lge.drmservice/u0a51 (adj 15): empty #11
D/BarTransitions( 1388): draw background and invalidate : color = 11000000
D/BarTransitions( 1388): draw background and invalidate : color = 13121212
V/audio_hw_primary(  281): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  281): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  281): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  281): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  281): disable_audio_route: exit
E/audio_hw_primary(  281): disable_snd_device: enter 144
D/hardware_info(  281): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  281): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  281): stop_input_stream: exit: status(0)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyManager(  281): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  281): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  281): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  281): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  281): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  281): setParameters(): io 17, keyvalue hotword_active=0, calling pid 281
V/AudioFlinger(  281): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio patch list
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  281): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  281): in_set_parameters: exit: status(0)
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb397c000
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioRecord( 2041): stop()
V/AudioRecord( 2041): stop()
V/AudioRecord( 2041): stop()
V/AudioFlinger(  281): releasing 16 from 2041 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
V/AudioPolicyManager(  281): releaseInput() 17
V/AudioPolicyManager(  281): closeInput(17)
V/AudioFlinger(  281): closeInput() 17
V/AudioSystem(  281): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  975): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): ThreadBase::exit
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioSystem( 2763): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3112): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1388): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): RecordThread 0xb397c000 exiting
V/AudioSystem( 2041): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1792): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 2041): Stopping hotword detection.
D/audio_hw_primary(  281): adev_close_input_stream: enter:stream_handle(0xb546e420)
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioPolicyService(  281): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  281): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio port list
V/AudioPolicyManager(  281): releaseInput() exit
V/AudioFlinger(  281): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  281): removeClient_l() pid 2041, calling pid 281
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 2041): Hotword detection finished
W/libprocessgroup(  975): failed to open /acct/uid_10051/pid_3675/cgroup.procs: No such file or directory
D/ContextHelper( 4141): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/WebViewFactory( 4141): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 4141): Time to load native libraries: 2 ms (timestamps 5646-5648)
I/LibraryLoader( 4141): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 4141): Binding Chromium to main looper Looper (main, tid 1) {21190114}
I/LibraryLoader( 4141): Expected native library version number "",actual native library version number ""
I/chromium( 4141): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4141): Initializing chromium process, singleProcess=true
W/art     ( 4141): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4141): ApplicationContext is null in ApplicationStatus
W/chromium( 4141): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
W/chromium( 4141): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4141): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4141): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4141): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4141): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4141): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4141): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4141): Remote Branch: 
I/Adreno-EGL( 4141): Local Patches: 
I/Adreno-EGL( 4141): Reconstruct Branch: 
W/ActivityManager(  975): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/AudioPolicyService(  281): registerClient() client 0xb3808c20, uid 10030
D/BluetoothManagerService(  975): Message: 20
D/BluetoothManagerService(  975): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@29cdb46f:true
D/BluetoothAdapter( 4141): 469693694: getState() :  mService = null. Returning STATE_OFF
I/Gmail   ( 4124): getAccountsCursor
V/GLSActivity( 2087): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 4124): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager(  975): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 4124): Error finding the version of the Email provider.....
E/Gmail   ( 4124): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4124): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4124): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4124): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4124): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4124): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4124): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4124): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4124): We do not support migrating this version of the Email provider.
I/Gmail   ( 4124): getAccountsCursor
V/GLSActivity( 2087): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 2087): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  975): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/art     ( 4141): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 4141): onDetachedFromWindow called when already detached. Ignoring
V/GLSActivity( 2087): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  975): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/SystemWebViewEngine( 4141): CordovaWebView is running on device made by: LGE
W/art     ( 4141): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4141): Attempt to remove local handle scope entry from IRT, ignoring
W/ActivityManager(  975): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/SearchBackgroundTaskFac( 2041): refreshing internal icing corpora
W/ActivityManager(  975): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 4124): Observing account changes for notifications
E/ActivityThread( 4124): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@32372e6a that was originally bound here
E/ActivityThread( 4124): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@32372e6a that was originally bound here
E/ActivityThread( 4124): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4124): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4124): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4124): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4124): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4124): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4124): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4124): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4124): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4124): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4124): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4124): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4124): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4124): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4124): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4124): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  975): Unbind failed: could not find connection for android.os.BinderProxy@208b1fc8
I/VelvetNetworkClient( 2041): Network connection not availble
I/ActivityManager(  975): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4215 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/Activity( 4141): Activity.onPostResume() called 
I/SearchBackgroundTaskFac( 2041): Checking for language pack updates
D/OpenGLRenderer( 4141): Render dirty regions requested: true
I/OpenGLRenderer( 4141): Initialized EGL, version 1.4
D/OpenGLRenderer( 4141): Enabling debug mode 0
D/Atlas   ( 4141): Validating map...
D/SplitWindow(  975): check instance of lgWin Window{33167074 u0 com.example.hello/com.example.hello.MainActivity}
W/chromium( 4141): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/VelvetNetworkClient( 2041): Network connection not availble
I/GservicesUpdateTask( 2041): Updating Gservices keys
D/InputDispatcher(  975): Focus entered window: Window{33167074 u0 com.example.hello/com.example.hello.MainActivity}
I/Gmail   ( 4124): notifyAccountChanged
I/Gmail   ( 4124): getAccountsCursor
I/VelvetNetworkClient( 2041): Network connection not availble
V/GLSActivity( 2087): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/InputMethodManagerService(  975): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  975): Displayed com.example.hello/.MainActivity: +1s244ms
I/Timeline(  975): Timeline: Activity_windows_visible id: ActivityRecord{2a18bafa u0 com.example.hello/.MainActivity t220} time:56442
,I/Gmail   ( 4124): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/ActivityManager(  975): Killing 3699:com.lge.cloudhub/u0a49 (adj 15): empty #11
,I/Timeline( 4141): Timeline: Activity_idle id: android.os.BinderProxy@255e23b0 time:56471
I/Gmail   ( 4124): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/libprocessgroup(  975): failed to open /acct/uid_10049/pid_3699/cgroup.procs: No such file or directory
V/[BNRBootReceiver]( 4215): boot receiver action = android.intent.action.BOOT_COMPLETED
,V/[BNRBootReceiver]( 4215): set property sys.lge.bnrd = 1
V/[BNRBootReceiver]( 4215): End of BootComplted IF
V/[BNRBootReceiver]( 4215): Boot Receiver Return
V/[BNRBootCompletedThread]( 4215): run
,W/linker  ( 4259): /system/bin/bnrd has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/bnrd    ( 4259): BNRD > wait starting [4259-3058102400] <
I/Gmail   ( 4124): calculateUnknownSyncRationalesAndPurgeInBackground: running
E/bnrd    ( 4259): /data/data/.bnr_fifo_req
I/Gmail   ( 4124): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/UpdateIcingCorporaServi( 2041): Updating corpora: APPS=MAYBE, CONTACTS=MAYBE
,I/ActivityManager(  975): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4262 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  975): Killing 3722:com.lge.gnss.airtest/u0a54 (adj 15): empty #11
,I/NotificationManager( 2041): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,W/BindingManager( 4141): Cannot call determinedVisibility() - never saw a connection for the pid: 4141
V/[BNRBootCompletedThread]( 4215): End of BNRProcess
,V/[BNRBootCompletedThread]( 4215): End of BNRViaWifiProcess
,V/[BNRBootCompletedThread]( 4215): End of SpriteProcess
V/[BNRBootCompletedThread]( 4215): exit
W/libprocessgroup(  975): failed to open /acct/uid_10054/pid_3722/cgroup.procs: No such file or directory
,I/chromium( 4141): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
D/JsMessageQueue( 4141): Set native->JS mode to OnlineEventsBridgeMode
,E/AndroidProtocolHandler( 4141): Unable to open asset URL: file:///android_asset/www/jxcore.js
,I/Gmail   ( 4124): getAccountsCursor
,V/GLSActivity( 2087): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/libc-netbsd( 2087): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2087): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 2087): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2087): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/libc-netbsd( 2087): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2087): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/DSQN    (  975): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,W/Search.LoginHelper( 2041): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 2041): java.io.IOException: NetworkError
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 2041): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,W/Search.LoginHelper( 2041): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 2041): java.io.IOException: NetworkError
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 2041): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
I/UpdateIcingCorporaServi( 2041): UpdateCorporaTask done [took 431 ms] updated apps [took 431 ms] 
,D/libc-netbsd( 2087): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2087): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 2087): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2087): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Search.LoginHelper( 2041): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 2041): java.io.IOException: NetworkError
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 2041): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 2041): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 2041): java.io.IOException: NetworkError
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 2041): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,D/libc-netbsd( 2087): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2087): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Search.LoginHelper( 2041): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 2041): java.io.IOException: NetworkError
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 2041): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,I/WebViewFactory( 2041): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,D/libc-netbsd( 2087): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2087): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 2087): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2087): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Search.LoginHelper( 2041): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 2041): java.io.IOException: NetworkError
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 2041): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/Search.LoginHelper( 2041): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 2041): java.io.IOException: NetworkError
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolEx,ecutor.java:587)
W/Search.LoginHelper( 2041): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
D/libc-netbsd( 2087): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2087): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Search.LoginHelper( 2041): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 2041): java.io.IOException: NetworkError
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 2041): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 2041): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 2041): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
I/LibraryLoader( 2041): Time to load native libraries: 5 ms (timestamps 7217-7222)
I/LibraryLoader( 2041): Expected native library version number "",actual native library version number ""
W/art     ( 2041): Attempt to remove local handle scope entry from IRT, ignoring
,D/Finsky  ( 4262): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,W/art     ( 2041): Attempt to remove local handle scope entry from IRT, ignoring
,D/jxcore_app_log( 4141): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426127360
D/JX-Cordova( 4141): jxcore cordova android initializing
,I/ActivityManager(  975): Killing 3743:com.lge.lgfota.permission/1000 (adj 15): empty #11
,D/Finsky  ( 4262): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/jxcore-log( 4141): Initializing JXcore engine
,W/jxcore-log( 4141): JXcore engine is ready
W/jxcore-log( 4141): Starting JXcore engine
W/libprocessgroup(  975): failed to open /acct/uid_1000/pid_3743/cgroup.procs: No such file or directory
,W/Settings( 4262): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4262): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 4262): com.android.vending: cancel(-1050172287) by com.android.vending
,W/m.example.hello( 4141): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7401]" dev="sockfs" ino=7401 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4141): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 4141): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8650]" dev="sockfs" ino=8650 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4141): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 4141): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 4141): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[21622]" dev="sockfs" ino=21622 scontext=u:r:untrusted_app:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
V/DownloadManager( 2840): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 2840): created cursor android.database.sqlite.SQLiteCursor@13729974 on behalf of 4262
D/Volley  ( 4262): [433] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 4262): [426] DiskBasedCache.clear: Cache cleared.
D/Ads     ( 4262): Skipping gmscore version check
,I/ActivityManager(  975): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.ui.editor.reminder.ReminderMaker: pid=4336 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  975): Killing 3783:com.lge.hiddenmenu/1000 (adj 15): empty #11
W/libprocessgroup(  975): failed to open /acct/uid_1000/pid_3783/cgroup.procs: No such file or directory
,D/KeyguardUpdateMonitor( 1388): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1388): onReceive = com.lge.android.intent.action.BATTERYEX
D/PowerService( 1889): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1388): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1388): On Skip Timer : true
,D/Finsky  ( 4262): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4262): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 4262): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/jxcore-log( 4141): Platform android
W/jxcore-log( 4141): 
W/jxcore-log( 4141): Process ARCH arm
W/jxcore-log( 4141): 
W/ResourcesManager( 4336): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/Finsky  ( 4262): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/jxcore-log( 4141): JXcore Cordova bridge is ready!
I/jxcore-log( 4141): 
W/jxcore-log( 4141): JXcore engine is started
,E/App     ( 4336): [App][onCreate()] 4.40.21
,E/jxcore-log( 4141): >> LGE-LG-D722
E/jxcore-log( 4141): 
,I/jxcore-log( 4141): Total memory 906309632
I/jxcore-log( 4141): 
I/jxcore-log( 4141): Free memory 16965632
I/jxcore-log( 4141): 
I/jxcore-log( 4141): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4141): 
I/jxcore-log( 4141): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4141): 
I/jxcore-log( 4141): userPath [ 'www' ]
I/jxcore-log( 4141): 
I/jxcore-log( 4141): Size 720 1196
I/jxcore-log( 4141): 
,I/jxcore-log( 4141): Screen Brightness 255
I/jxcore-log( 4141): 
E/jxcore-log( 4141): Dummy Error Log.
E/jxcore-log( 4141): 
I/art     (  975): Explicit concurrent mark sweep GC freed 37247(1790KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 22MB/33MB, paused 10.593ms total 197.948ms
,D/AccountManager( 4336): setSyncFrequency
,W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.qmemoplus.ui.editor.reminder.ReminderMaker.onReceive:14 android.app.ActivityThread.handleReceiver:2663 
,D/WeatherAncestor( 2746): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:9:23
D/UpdateThreadPoolManager( 2746): 2 : This is isUpdating : false
D/WeatherAncestor( 2746): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 15:9:23
D/WeatherService( 2746): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
W/ActivityManager(  975): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2746): 2 : Utils getTopActivity com.lge.launcher2 / true
D/ReminderService( 4336): [onHandleIntent] action : com.lge.qmemoplus.action.SET_REMINDERS
D/WeatherService( 2746): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
,D/WeatherService( 2746): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2746): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2746): 2 : This is isUpdating : false
D/WeatherService( 2746): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2746): 2 : buildUpdate, appWidgetId: 2
D/LocationReminderManager( 4336): [connect] Request location client connection.
D/WeatherTheme( 2746): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2746): 2 : Fixed theme : optimus
D/WeatherReflect( 2746): 2 : Map key string is -2
,D/lim     ( 2746): 2 : time = 15:09
I/WeatherReflect( 2746): Model Name : LG-D722
D/WeatherTheme( 2746): 2 : exactly same view!
D/WeatherTheme( 2746): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
W/ContextImpl( 4336): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.google.android.gms.internal.he.a:-1 com.google.android.gms.internal.hc.connect:-1 com.google.android.gms.location.LocationClient.connect:-1 
W/ActivityManager(  975): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2746): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2746): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2746): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/ActivityManager(  975): Killing 3801:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,D/LocationReminderManager( 4336): location cilent is connected.
D/LocationReminderManager( 4336): [removeAllReminders]
,W/libprocessgroup(  975): failed to open /acct/uid_10069/pid_3801/cgroup.procs: No such file or directory
,V/UserPresentBroadcastReceiver( 1758): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
W/GCoreFlp( 1758): No location to return for getLastLocation()
W/GCoreFlp( 1758): No location to return for getLastLocation()
,W/GeofencerStateMachine( 1758): Ignoring removeGeofence because network location is disabled.
D/LocationReminderManager( 4336): [removeAllReminders] statusCode : 1000
D/LocationReminderManager( 4336): [removeAllReminders] Failed to remove reminder
,I/jxcore-log( 4141): getBuffer is called!!!!
I/jxcore-log( 4141): 
I/ActivityManager(  975): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=4363 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/art     ( 2087): Explicit concurrent mark sweep GC freed 20450(1451KB) AllocSpace objects, 22(352KB) LOS objects, 40% free, 11MB/19MB, paused 1.186ms total 85.146ms
,I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
,D/LGDMClient( 4363): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
D/LGDMClient( 4363): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 4363): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
,V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
D/LGDMClient( 4363): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/ActivityManager(  975): Killing 3819:com.lge.springcleaning/1000 (adj 15): empty #11
,I/ActivityManager(  975): Waited long enough for: ServiceRecord{8b74431 u0 com.android.mms/.service.SwitchedService}
,W/libprocessgroup(  975): failed to open /acct/uid_1000/pid_3819/cgroup.procs: No such file or directory
,V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3112): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3112): ANY_DATA_STATE event received: DISCONNECTED
I/ActivityManager(  975): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4398 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 4398): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  975): Message: 20
D/BluetoothManagerService(  975): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e44101:true
,D/BluetoothAdapter( 4398): 252648064: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4398): 252648064: getState() :  mService = null. Returning STATE_OFF
,I/ActivityManager(  975): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4419 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/LGMDMManager( 4398): Create singleton instance
I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 30.107ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.389ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.384ms
,I/AudioManager( 4398): getMode name:com.lge.qremote
,I/AudioManager( 4398): getMode name:com.lge.qremote
,D/LGDMClient( 4363): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
D/LGDMClient( 4363): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4363): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 4363): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/AudioManager( 4398): getMode name:com.lge.qremote
,D/LGDMClient( 4363): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
V/AlarmManager(  975): ELAPSED_WAKEUP set : Alarm{7fb9edf type 2 when 53559 com.google.android.talk} when 53559
,V/AlarmManager(  975): RTC_WAKEUP set : Alarm{3ec065f5 type 0 when 1449410964209 com.google.android.gms} when 1449410964209
D/UEI.SmartControl( 4419): Quickset Services start...
,I/UEI.SmartControl( 4419): Manufacture = LGE
D/UEI.SmartControl( 4419): File observer start...
,E/UEI.SmartControl( 4419): IR Port is disabled: false
D/UEI.SmartControl( 4419): Starting file observer...
D/UEI.SmartControl( 4419): Extracting JNI libs...
,D/UEI.SmartControl( 4419): --- this system supports 32-bit or 64-bit only
D/WearableService( 1758): callingUid 10006, callindPid: 1758
,E/MDM     ( 1758): [89] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/GCM     ( 2087): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/iu.UploadsManager( 2281): End new media; added: 0, uploading: 0, time: 74 ms
D/AuthorizationBluetoothService( 2087): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 2281): Restart initialization of location
V/GLSActivity( 2087): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 2087): com.google.android.gms: cancel(0) by com.google.android.gms
V/GmsCoreStatsServiceLauncher( 2281): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/UEI.SmartControl( 4419): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,I/AudioManager( 4398): getMode name:com.lge.qremote
D/UEI.SmartControl( 4419): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4419): --- Extracting JNI libs: libqs_armeabi-v7a.zip
W/GCoreFlp( 1758): No location to return for getLastLocation()
W/FusedLocationProvider( 2087): location=null
D/libc-netbsd( 2087): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2087): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 2087): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 2087): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  275): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  275): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  275): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  275): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  275): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  975): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/UEI.SmartControl( 4419): --- Selecting new region: 2
,I/UEI.SmartControl( 4419): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 4419): Platform has CIR...
D/UEI.SmartControl( 4419): NO CIR support, need to check package...
I/UEI.SmartControl( 4419): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 4419): QS Service created
I/ActivityManager(  975): Process com.google.android.youtube (pid 4013) has died
,E/UEI.SmartControl( 4419): QS start get config
,I/ActivityManager(  975): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4462 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
D/UEI.SmartControl( 4419): Loading JNI Libs...
,D/UEI.SmartControl( 4419):  configuring local db...
,W/ResourcesManager( 4462): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4462): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 4462): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LGEmail ( 4462): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 4462): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/UEI.SmartControl( 4419):  ---- Has DB8: true
,D/UEI.SmartControl( 4419): QS start statue = true Error code = 0
D/UEI.SmartControl( 4419): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4419): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4419): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 4419): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4419): IrrcClient ++ 
D/irrcClient( 4419): getIrrcService ++ 
D/irrcClient( 4419): getIrrcService -- 
D/irrcClient( 4419): IrrcClient -- 
W/irrc_jni( 4419): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 4419): Services init done
,D/UEI.SmartControl( 4419): QS Service init finished
D/UEI.SmartControl( 4419): QS Service version name: 0.1.73
D/UEI.SmartControl( 4419): QS Service version code: 1073
D/UEI.SmartControl( 4419): Service requested: Control
I/UEI.SmartControl( 4419): Device manager: loading config....
D/UEI.SmartControl( 4419): Config is loaded...
I/PackageChangeReceiver( 4462): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,D/UEI.SmartControl( 4419): Request IControl service: devices are loaded...
D/UEI.SmartControl( 4419):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 4419): Notify AllClients services are ready: 0
I/ActivityManager(  975): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4489 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,D/UEI.SmartControl( 4419): Internal service binding...
D/UEI.SmartControl( 4419): -----IControl: 11
D/UEI.SmartControl( 4419): Caller: com.lge.qremote
D/UEI.SmartControl( 4419): ------------ IControl registerCallback...
I/UEI.SmartControl( 4419): Registering callback...
D/UEI.SmartControl( 4419): -----IControl: 19
D/UEI.SmartControl( 4419): Caller: com.lge.qremote
I/UEI.SmartControl( 4419): Registering Services Ready callback...
I/UEI.SmartControl( 4419): Notify client services are ready...
D/UEI.SmartControl( 4419): -----IControl: 8
,D/UEI.SmartControl( 4419): Caller: com.lge.qremote
I/ActivityManager(  975): Killing 3853:com.google.android.configupdater/u0a3 (adj 15): empty #11
W/libprocessgroup(  975): failed to open /acct/uid_10003/pid_3853/cgroup.procs: No such file or directory
,I/ActivityManager(  975): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4509 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  975): Killing 3895:com.lge.eula/1000 (adj 15): empty #11
,W/libprocessgroup(  975): failed to open /acct/uid_1000/pid_3895/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 4509): onCreate
,W/AppUp4:DB( 4509):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 4509):  setFingerPrint start
I/AppUp4:DB( 4509):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 4509):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4509):  SDK version = 0
I/AppUp4:DB( 4509):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 4509): AppBoxApplication onCreate()
I/ActivityManager(  975): Killing 4124:com.google.android.gm/u0a53 (adj 15): empty #11
,W/libprocessgroup(  975): failed to open /acct/uid_10053/pid_4124/cgroup.procs: No such file or directory
,I/ActivityManager(  975): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=4526 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 4526): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4526): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 4526): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 4526): Total System Memory = 906309632
,I/GalleryUtils( 4526): Application Heap = 96 MB
I/AppConfig( 4526): App Tier : NOT_DEF
D/SystemHelper( 4526): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  975): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=4548 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  975): Killing 4215:com.lge.bnr/1000 (adj 15): empty #11
W/libprocessgroup(  975): failed to open /acct/uid_1000/pid_4215/cgroup.procs: No such file or directory
,W/ResourcesManager( 4548): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4548): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4548): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 4548): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 4548): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 4548): BUILD Country: EU
,I/SystemConfig( 4548): BUILD Operator: OPEN
I/ActivityManager(  975): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=4567 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  975): Killing 4262:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  975): failed to open /acct/uid_10036/pid_4262/cgroup.procs: No such file or directory
,I/SystemConfig( 4548): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 4548): existFile = false
I/SystemConfig( 4548): canReadFile = false
I/SystemConfig( 4548): systemFeature RCS result false
D/SystemConfig( 4548): refreshRcsSupport() :false
I/LockScreenSettings( 4567): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 4567): New app installed broadcast received ..
,I/LockScreenSettings( 4567): Number of installed packages  1
I/ActivityManager(  975): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=4584 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  975): Killing 4336:com.lge.qmemoplus/1000 (adj 15): empty #11
,W/libprocessgroup(  975): failed to open /acct/uid_1000/pid_4336/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 4584): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 4584): uri : package:com.example.hello
,I/ActivityManager(  975): Killing 4363:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  975): failed to open /acct/uid_1000/pid_4363/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 2281): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2281): Module APK com.google.android.play.games already loaded
D/PackageBroadcastService( 2281): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
D/ChimeraCfgMgr( 2281): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 2281): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 2281): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 2281): Submit a task: h
,I/PeopleContactsSync( 2281): CP2 sync disabled
D/ChimeraCfgMgr( 2281): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 2281): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/h       ( 2281): Processing package: com.example.hello
D/GassUtils( 2281): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
D/h       ( 2281): Found info for package com.example.hello in db.
,I/ActivityManager(  975): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4608 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/Icing   ( 2281): Storage manager: low false usage 1.61MB avail 2.05GB capacity 3.45GB
,W/BaseAppContext( 2281): Using Auth Proxy for data requests.
W/BaseAppContext( 2281): Using Auth Proxy for data requests.
,W/Icing   ( 2281): Received bad json for section weights override -- ignoring.
,W/BaseAppContext( 2281): Using Auth Proxy for data requests.
,W/Icing   ( 2281): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 2281): Received bad json for section weights override -- ignoring.
W/Icing   ( 2281): Received bad json for corpus context scoring override -- ignoring.
I/ActivityManager(  975): Waited long enough for: ServiceRecord{5f2d9d6 u0 com.lge.mlt/.MltMonitorService}
W/BaseAppContext( 2281): Using Auth Proxy for data requests.
,W/BaseAppContext( 2281): Using Auth Proxy for data requests.
W/BaseAppContext( 2281): Using Auth Proxy for data requests.
,I/Icing   ( 2281): updateResources: need to parse f{com.google.android.gms}
,D/PowerService( 1889): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1388): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1388): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1388): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1388): On Skip Timer : true
D/charger_monitor(  482): init target 500000
D/KeyguardUpdateMonitor( 1388): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1388): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1926): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1388): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/QCNEJ   ( 1926): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/charger_monitor(  482): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/WifiController(  975): battery changed pluggedType: 2
D/PowerService( 1889): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/QCNEJ   ( 1926): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1926): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1889): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1889): Battery Level Remaining: 100%
D/LEDHandler( 1889): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/LEDHandler( 1889): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1889): Battery Level Remaining: 100%
D/LEDHandler( 1889): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/WifiController(  975): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1388): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1388): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1388): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1388): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1388): On Skip Timer : true
D/KeyguardUpdateMonitor( 1388): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1388): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1388): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1388): onReceive = android.intent.action.BATTERY_CHANGED
I/Icing   ( 2281): Internal init done: storage state 0
,I/Icing   ( 2281): Post-init done
,V/AlarmManager(  975): ELAPSED_WAKEUP set : Alarm{17beafbc type 2 when 62380 com.google.android.gms} when 62380
,I/QCNEJ   ( 1926): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[LGHome]EVENT( 1964): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[SystemUI]QPairHandler( 1388): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]QSlideListController( 1388): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]LGPlusHomeDBManager( 1964): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1964): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
W/[SystemUI]QSlideLoader( 1388): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
I/InputReader(  975): Reconfiguring input devices.  changes=0x00000010
W/[SystemUI]QSlideLoader( 1388): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1388): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1388): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1388): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1388): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1388): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1388): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1388): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1388): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1388): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1388): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1388): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/GAv4    ( 4608): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4608):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4608):   adb logcat -s GAv4
,D/administrator(  975): Handling package changes for user 0
I/art     ( 1865): CheckpointMarkThreadRoots callback created = 0xaaf22b30
I/[LGHome]Launcher( 1964): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/art     ( 1865): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,W/GAv4    ( 4608): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 4608): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4608): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 4608): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,W/ResourcesManager(  975): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/NotificationService(  975): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  975): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  975): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  975): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/LCardEmulationManager( 1865): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1865): getDefaultRoute
,W/ResourceType(  975): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/art     (  975): Explicit concurrent mark sweep GC freed 25641(1245KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.167ms total 174.102ms
,V/BackupManagerService(  975): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  975): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1092eab9
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4608): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
I/[LGHome]EVENT( 1964): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/ResourcesManager( 4608): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4608): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  975): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4666 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  975): Killing 4419:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/art     ( 4608): CheckpointMarkThreadRoots callback created = 0xb050fa70
,W/System.err( 4398): android.os.DeadObjectException
W/System.err( 4398): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4398): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4398): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 4398): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 4398): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4398): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4398): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4398): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4398): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4398): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4398): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4398): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4398): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4398): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4398): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 4398): android.os.DeadObjectException
W/System.err( 4398): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4398): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4398): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 4398): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 4398): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4398): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4398): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4398): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4398): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4398): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4398): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4398): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4398): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4398): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4398): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/art     ( 4608): CheckpointMarkThreadRoots callback created = 0xb050fa50
,V/GmsNetworkLocationProvi( 1758): DISABLE
,D/BluetoothManagerService(  975): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  975): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService(  975): Message: 2
W/libprocessgroup(  975): failed to open /acct/uid_10089/pid_4419/cgroup.procs: No such file or directory
I/GCoreNlp( 1758): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/NotificationManager( 4608): com.google.android.apps.docs: cancel(10436) by com.google.android.apps.docs
,W/ResourcesManager( 4666): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  975): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4688 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/WifiServiceImplEx(  975): setWifiEnabled: false pid=4141, uid=10030, package= com.example.hello, App Lable : HelloWorld
D/WifiService(  975): setWifiEnabled: false pid=4141, uid=10030
I/jxcore-log( 4141): ****TEST TOOK:  5253  ms ****
I/jxcore-log( 4141): 
I/jxcore-log( 4141): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4141): 
V/JNIHelp ( 4608): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/LocationProviderProxy(  975): applying state to connected service
,D/UEI.SmartControl( 4688): Quickset Services start...
,I/UEI.SmartControl( 4688): Manufacture = LGE
D/UEI.SmartControl( 4688): File observer start...
E/UEI.SmartControl( 4688): IR Port is disabled: false
D/UEI.SmartControl( 4688): Starting file observer...
D/UEI.SmartControl( 4688): Extracting JNI libs...
D/UEI.SmartControl( 4688): --- this system supports 32-bit or 64-bit only
,W/System  ( 4608): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4608): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 2087): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 4688): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 4688): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4688): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 4688): --- Selecting new region: 2
,I/UEI.SmartControl( 4688): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 4688): Platform has CIR...
D/UEI.SmartControl( 4688): NO CIR support, need to check package...
I/UEI.SmartControl( 4688): Model: LG-D722 uses JNI
D/UEI.SmartControl( 4688): QS Service created
,E/UEI.SmartControl( 4688): QS start get config
,D/UEI.SmartControl( 4688): Loading JNI Libs...
,D/UEI.SmartControl( 4688):  configuring local db...
D/AndroidRuntime( 4706): 
D/AndroidRuntime( 4706): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4706): CheckJNI is OFF
I/ThermalEngine(  295): Sensor:pa_therm0:30000 mC
I/ActivityManager(  975): Killing 4398:com.lge.qremote/u0a106 (adj 15): empty #11
,D/UEI.SmartControl( 4688):  ---- Has DB8: true
,D/UEI.SmartControl( 4688): QS start statue = true Error code = 0
,D/UEI.SmartControl( 4688): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4688): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4688): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 4688): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 4688): IrrcClient ++ 
D/irrcClient( 4688): getIrrcService ++ 
D/irrcClient( 4688): getIrrcService -- 
D/irrcClient( 4688): IrrcClient -- 
W/irrc_jni( 4688): IRRCPlayer_nativeInit -- 
W/libprocessgroup(  975): failed to open /acct/uid_10106/pid_4398/cgroup.procs: No such file or directory
D/UEI.SmartControl( 4688): Services init done
I/UEI.SmartControl( 4688): Device manager: loading config....
D/UEI.SmartControl( 4688): QS Service init finished
,D/UEI.SmartControl( 4688): QS Service version name: 0.1.73
D/UEI.SmartControl( 4688): QS Service version code: 1073
D/UEI.SmartControl( 4688): Service requested: Control
D/UEI.SmartControl( 4688): Config is loaded...
D/UEI.SmartControl( 4688): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 4688):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 4688): Notify AllClients services are ready: 0
I/ActivityManager(  975): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=4732 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/UpdateIcingCorporaServi( 2041): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
D/UEI.SmartControl( 4688): Service.onUnbind: IControl
D/UEI.SmartControl( 4688): Service.onDestroy
D/UEI.SmartControl( 4688): Shutdown IRRCPlayer... 
W/irrc_jni( 4688): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 4688): ~IrrcClient ++ 
D/irrcClient( 4688): ~IrrcClient -- 
W/irrc_jni( 4688): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 4688): Blaster closed
D/UEI.SmartControl( 4688): Blaster closed
D/UEI.SmartControl( 4688): Shut down QS...
D/UEI.SmartControl( 4688): Stopped file observer...
I/UEI.SmartControl( 4688): QS lib stop result = true
D/UEI.SmartControl( 4688): QS shutdown complete
D/UEI.SmartControl( 4688): QS Service created
,I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 22.037ms
E/UEI.SmartControl( 4688): QS start get config
I/ActivityManager(  975): Waited long enough for: ServiceRecord{15d29d07 u0 com.android.calendar/.alerts.InitAlarmsService}
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 299us total 21.360ms
,D/AndroidRuntime( 4706): Calling main entry com.android.commands.pm.Pm
D/UEI.SmartControl( 4688):  configuring local db...
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 21.259ms
,I/ActivityManager(  975): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
I/ActivityManager(  975): Killing 4141:com.example.hello/u0a30 (adj 0): stop com.example.hello
,I/WindowState(  975): WIN DEATH: Window{33167074 u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  975): Focus left window: Window{33167074 u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  975): Window went away: Window{33167074 u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  975): Skipping PackageSetting{29655b3a com.test.thalitest/10316} due to missing metadata
,D/UEI.SmartControl( 4688):  ---- Has DB8: true
,D/UEI.SmartControl( 4688): QS start statue = true Error code = 0
D/UEI.SmartControl( 4688): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4688): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4688): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 4688): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4688): IrrcClient ++ 
D/irrcClient( 4688): getIrrcService ++ 
D/irrcClient( 4688): getIrrcService -- 
D/irrcClient( 4688): IrrcClient -- 
W/irrc_jni( 4688): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 4688): Services init done
I/UEI.SmartControl( 4688): Device manager: loading config....
D/UEI.SmartControl( 4688): Config is loaded...
E/libprocessgroup(  975): failed to kill 1 processes for processgroup 4141
,W/ActivityManager(  975): Force removing ActivityRecord{2a18bafa u0 com.example.hello/.MainActivity t220}: app died, no saved state
,W/ActivityManager(  975): Spurious death for ProcessRecord{ce37837 4141:com.example.hello/u0a30}, curProc for 4141: null
I/ActivityManager(  975): Force stopping com.example.hello appid=10030 user=0: pkg removed
D/UEI.SmartControl( 4688): QS Service init finished
,D/UEI.SmartControl( 4688): QS Service version name: 0.1.73
D/UEI.SmartControl( 4688): QS Service version code: 1073
D/UEI.SmartControl( 4688): Service requested: Control
I/[LGHome]EVENT( 1964): [Launcher.java:5203:onStart()]onStart
D/UEI.SmartControl( 4688):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 4688): Notify AllClients services are ready: 0
D/KeyguardModel( 1388): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,D/[BNRAppListMgrReceiver]( 4732): android.intent.action.PACKAGE_ADDED : com.example.hello
I/ActivityManager(  975): Killing 3974:com.google.android.talk/u0a61 (adj 15): empty #11
W/System.err( 3396): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/GeofencerStateMachine( 1758): Ignoring removeGeofence because network location is disabled.
,E/[BNRAppListMgrReceiver]( 4732): NameNotFoundException : com.example.hello
I/InputReader(  975): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1926): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/System.err( 3396): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3396): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3396): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3396): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3396): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3396): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3396): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3396): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3396): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3396): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3396): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,I/[LGHome]EVENT( 1964): [Launcher.java:776:onResume()]onResume
D/administrator(  975): Handling package changes for user 0
,I/NotificationService(  975): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  975): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/JobSchedulerService(  975): Receieved: android.intent.action.PACKAGE_REMOVED
,E/ActivityThread( 4688): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@f0f1a80 that was originally bound here
E/ActivityThread( 4688): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@f0f1a80 that was originally bound here
E/ActivityThread( 4688): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4688): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4688): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4688): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4688): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4688): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 4688): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 4688): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 4688): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 4688): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 4688): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 4688): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4688): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4688): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 4688): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 4688): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 4688): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 4688): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  975): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4755 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  975): Killing 4462:com.lge.email/u0a21 (adj 15): empty #11
I/[LGHome]EVENT( 1964): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
,I/art     (  975): Explicit concurrent mark sweep GC freed 19990(1435KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 22MB/34MB, paused 2.321ms total 207.570ms
D/UEI.SmartControl( 4688): Internal service binding...
W/libprocessgroup(  975): failed to open /acct/uid_10061/pid_3974/cgroup.procs: No such file or directory
I/[LGHome]Launcher.Model( 1964): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
W/libprocessgroup(  975): failed to open /acct/uid_10021/pid_4462/cgroup.procs: No such file or directory
,I/[SystemUI]QSlideListController( 1388): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1964): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1964): [Launcher.java:929:onResume()]onResume end
I/Activity( 1964): Activity.onPostResume() called 
D/TaskPersister(  975): removeObsoleteFile: deleting file=220_task.xml
,I/SystemUI[Framework](  975): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
D/InputDispatcher(  975): Focus entered window: Window{c68779f u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,W/PhoneWindowManagerEx(  975): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  975): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  975): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  975): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@9fde3b4,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  975): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/[LGHome]LGWallpaperInfo( 1964): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1964): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
I/[LGHome]EVENT( 1964): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1964): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1964): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,D/AndroidRuntime( 4706): Shutting down VM
I/[LGHome]EVENT( 1964): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1964): [setNavigationBarColor] color=0x 0
W/InputMethodManagerService(  975): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1388): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1388): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,W/InputMethodManagerService(  975): Got RemoteException sending setActive(false) notification to pid 4141 uid 10030
D/PhoneStatusBar( 1388): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
I/NotificationManager( 2281): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/KeyguardModel( 1388): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1388): createShortcutInfo...
,D/KeyguardModel( 1388): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1388): createShortcutInfo...
W/ResourceType( 1388): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1388): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1388): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1388): createShortcutInfo...
W/ResourceType( 1388): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1388): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,D/KeyguardModel( 1388): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1388): createShortcutInfo...
W/ResourceType( 1388): No package identifier when getting value for resource number 0x00000000
,W/PackageManager( 1388): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
I/UpdateIcingCorporaServi( 2041): UpdateCorporaTask done [took 747 ms] updated apps [took 747 ms] 
D/KeyguardModel( 1388): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1388): createShortcutInfo...
I/[LGHome]Launcher.Model( 1964): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
D/KeyguardModel( 1388): handleShortcutListChanged...
I/HotwordDetector( 2041): Closing mic
,D/KeyguardModel( 1388): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1388): createShortcutInfo...
D/KeyguardModel( 1388): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1388): createShortcutInfo...
W/ResourceType( 1388): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1388): Failure retrieving resources for com.android.mms: Resource ID #0x0
I/SystemUI[Framework](  975): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
I/[LGHome]EVENT( 1964): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
D/PhoneStatusBar( 1388): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
W/PhoneWindowManagerEx(  975): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  975): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  975): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  975): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@9fde3b4,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  975): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/KeyguardModel( 1388): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1388): createShortcutInfo...
I/[SystemUI]NavigationThemeResource( 1388): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1388):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1388): , Keyguard show=false, IME shown=false, Panel expanded=false
W/ResourceType( 1388): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1388): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 1964): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1964): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
D/BarTransitions( 1388): draw background and invalidate : color = f7000000
I/[LGHome]EVENT( 1964): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/KeyguardModel( 1388): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1388): createShortcutInfo...
D/BarTransitions( 1388): draw background and invalidate : color = f2e8e8e8
W/ResourceType( 1388): No package identifier when getting value for resource number 0x00000000
I/HotwordRecognitionRnr( 2041): Stopping hotword detection.
W/PackageManager( 1388): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1388): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1388): createShortcutInfo...
,D/KeyguardModel( 1388): handleShortcutListChanged...
,W/ResourcesManager(  975): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[LGHome]Launcher.Model( 1964): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1964): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1964): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1964): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,I/[LGHome]Launcher.Model( 1964): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
W/ResourceType(  975): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/Resources( 1964): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1964): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1964): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
,W/Resources( 1964): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1964): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1964): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1964): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1964): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
,W/Resources( 1964): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1964): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1964): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1964): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/Timeline(  975): Timeline: Activity_windows_visible id: ActivityRecord{35254f5 u0 com.lge.launcher2/.Launcher t219} time:64989
,D/LCardEmulationManager( 1865): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1865): getDefaultRoute
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1964): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
D/Finsky  ( 4755): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1964): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1964): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
,I/[LGHome]Launcher.Model( 1964): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]EVENT( 1964): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]EVENT( 1964): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }

```
