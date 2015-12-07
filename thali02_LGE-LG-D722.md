#### Test 50242285e707819_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
W/libprocessgroup(  861): failed to open /acct/uid_10034/pid_3674/cgroup.procs: No such file or directory
,W/ResourcesManager( 4048): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4048): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
--------- beginning of main
V/JNIHelp ( 4048): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
W/System  ( 4048): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4048): Installed default security provider GmsCore_OpenSSL
D/AndroidRuntime( 4073): 
D/AndroidRuntime( 4073): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4073): CheckJNI is OFF
W/CursorWrapperInner( 3717): Cursor finalized without prior close()
W/art     ( 4048): Suspending all threads took: 22.290ms
W/ResourcesManager( 4048): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4048): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 4048): CheckpointMarkThreadRoots callback created = 0xb042dc80
E/YouTube MDX( 4048): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
D/libc-netbsd( 4048): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4048): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/AndroidRuntime( 4073): Calling main entry com.android.commands.am.Am
I/art     ( 4048): CheckpointMarkThreadRoots callback created = 0xb4958de0
I/ActivityManager(  861): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
I/art     (  861): Explicit concurrent mark sweep GC freed 15965(798KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 22MB/33MB, paused 1.992ms total 149.761ms
W/art     ( 4048): Suspending all threads took: 6.479ms
D/ActivityManager(  861): setTaskToReturnTo : TaskRecord{2e1a7805 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  861): setTaskToReturnTo : TaskRecord{2e1a7805 #220 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  861): AppWindowTokenEx init.. 
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4048): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
D/ContextHelper(  861): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/InputDispatcher(  861): Focus left window: Window{20e8dd69 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 4073): Shutting down VM
I/dex2oat ( 4103): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-234068914.jar --oat-fd=28 --oat-location=/data/data/com.google.android.youtube/cache/ads-234068914.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/[LGHome]EVENT( 1876): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  861): check instance of lgWin Window{1bf38c67 u0 Starting com.example.hello}
I/ActivityManager(  861): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4117 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/HotwordDetector( 1937): Closing mic
V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{1a245a14 type 2 when 55195 com.google.android.talk} when 55195
I/MicrophoneInputStream( 1937): mic_close com.google.android.apps.gsa.speech.audio.u@8498aec
V/AudioRecord( 1937): stop()
D/AudioRecord( 1937): AudioRecord->stop()
V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{3464a2bd type 2 when 56475 com.google.android.gms} when 56475
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
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
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb4146000
D/audio_hw_primary(  281): in_standby: enter: stream (0xb40367a0) usecase(7: audio-record)
I/[LGHome]EVENT( 1876): [Launcher.java:5214:onStop()]onStop
I/dex2oat ( 4103): dex2oat took 176.386ms (threads: 4)
I/WindowStateAnimator(  861): Starting window displayed
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
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  281): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  281): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  281): setParameters(): io 17, keyvalue hotword_active=0, calling pid 281
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioFlinger(  281): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  281): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  281): in_set_parameters: exit: status(0)
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb4146000
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioRecord( 1937): stop()
,I/SystemUI[Framework](  861): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
W/PhoneWindowManagerEx(  861): Call!!!getLGSystemUiVisibility. =0x0
V/AudioRecord( 1937): stop()
V/AudioRecord( 1937): stop()
D/StatusBarManagerServiceEx(  861): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  861): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  861): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1d99f586,  pkg=WindowManager.LayoutParams
D/PhoneStatusBar( 1371): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/SystemUI[Framework](  861): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1371): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1371):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1371): , Keyguard show=false, IME shown=false, Panel expanded=false
V/AudioFlinger(  281): RecordHandle::stop()
V/AudioFlinger(  281): RecordThread::stop
V/AudioPolicyManager(  281): releaseInput() 17
V/AudioPolicyManager(  281): closeInput(17)
V/AudioFlinger(  281): closeInput() 17
V/AudioSystem(  281): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1371): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): ThreadBase::exit
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioSystem( 1739): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): RecordThread 0xb4146000 exiting
V/AudioSystem( 2672): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  281): adev_close_input_stream: enter:stream_handle(0xb40367a0)
V/AudioSystem(  861): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  281): in_standby: enter: stream (0xb40367a0) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioPolicyService(  281): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  281): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyManager(  281): releaseInput() exit
V/AudioFlinger(  281): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  281): removeClient_l() pid 1937, calling pid 281
V/AudioSystem( 1937): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3147): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  281): releasing 16 from 1937 for -1
V/AudioFlinger(  281):  decremented refcount to 0
V/AudioFlinger(  281): purging stale effects
D/BarTransitions( 1371): draw background and invalidate : color = a000000
D/BarTransitions( 1371): draw background and invalidate : color = f0e0e0e
I/HotwordRecognitionRnr( 1937): Hotword detection finished
I/HotwordRecognitionRnr( 1937): Stopping hotword detection.
D/ContextHelper( 4117): convertTheme. context->name=com.example.hello themeResourceId=16973833
I/WebViewFactory( 4117): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 4117): Time to load native libraries: 2 ms (timestamps 6815-6817)
I/LibraryLoader( 4117): Expected native library version number "",actual native library version number ""
I/NotificationManager( 4048): com.google.android.youtube: cancel(2) by com.google.android.youtube
V/WebViewChromiumFactoryProvider( 4117): Binding Chromium to main looper Looper (main, tid 1) {5112527}
I/LibraryLoader( 4117): Expected native library version number "",actual native library version number ""
I/chromium( 4117): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4117): Initializing chromium process, singleProcess=true
W/art     ( 4117): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4117): ApplicationContext is null in ApplicationStatus
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4048): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
W/chromium( 4117): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4048): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4048): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
W/chromium( 4117): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
W/InstanceID/Rpc( 4048): Found 10006
E/libEGL  ( 4117): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4117): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4117): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4117): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4117): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4117): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4117): Remote Branch: 
I/Adreno-EGL( 4117): Local Patches: 
I/Adreno-EGL( 4117): Reconstruct Branch: 
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4048): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
V/AudioPolicyService(  281): registerClient() client 0xb2c1b9c0, uid 10030
D/BluetoothManagerService(  861): Message: 20
D/BluetoothManagerService(  861): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3107c99:true
D/BluetoothAdapter( 4117): 368083065: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  861): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4197 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/NotificationManager( 4048): com.google.android.youtube: cancel(10436) by com.google.android.youtube
I/ActivityManager(  861): Killing 3698:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/art     ( 4117): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 4117): onDetachedFromWindow called when already detached. Ignoring
,D/SystemWebViewEngine( 4117): CordovaWebView is running on device made by: LGE
,W/libprocessgroup(  861): failed to open /acct/uid_10051/pid_3698/cgroup.procs: No such file or directory
W/art     ( 4117): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4117): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 4117): Activity.onPostResume() called 
,D/OpenGLRenderer( 4117): Render dirty regions requested: true
I/OpenGLRenderer( 4117): Initialized EGL, version 1.4
D/OpenGLRenderer( 4117): Enabling debug mode 0
,D/Atlas   ( 4117): Validating map...
,D/SplitWindow(  861): check instance of lgWin Window{734106c u0 com.example.hello/com.example.hello.MainActivity}
W/chromium( 4117): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/InputDispatcher(  861): Focus entered window: Window{734106c u0 com.example.hello/com.example.hello.MainActivity}
,W/InputMethodManagerService(  861): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/Timeline( 4117): Timeline: Activity_idle id: android.os.BinderProxy@9c68cb3 time:57629
,I/ActivityManager(  861): Displayed com.example.hello/.MainActivity: +1s251ms
I/Timeline(  861): Timeline: Activity_windows_visible id: ActivityRecord{ab4d05a u0 com.example.hello/.MainActivity t220} time:57632
W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/BindingManager( 4117): Cannot call determinedVisibility() - never saw a connection for the pid: 4117
,I/chromium( 4117): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
,I/Gmail   ( 4197): getAccountsCursor
,V/GLSActivity( 1982): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 4197): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/JsMessageQueue( 4117): Set native->JS mode to OnlineEventsBridgeMode
,W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  861): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 4197): Observing account changes for notifications
,W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/AndroidProtocolHandler( 4117): Unable to open asset URL: file:///android_asset/www/jxcore.js
E/Gmail   ( 4197): Error finding the version of the Email provider.....
E/Gmail   ( 4197): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4197): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4197): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4197): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4197): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4197): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4197): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4197): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 4197): We do not support migrating this version of the Email provider.
I/Gmail   ( 4197): getAccountsCursor
V/GLSActivity( 1982): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 4197): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@774f71e that was originally bound here
E/ActivityThread( 4197): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@774f71e that was originally bound here
E/ActivityThread( 4197): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4197): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4197): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4197): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4197): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4197): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4197): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4197): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4197): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4197): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4197): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4197): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4197): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4197): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4197): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4197): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/ActivityManager(  861): Unbind failed: could not find connection for android.os.BinderProxy@145b334
I/SearchBackgroundTaskFac( 1937): Checking for language pack updates
,I/VelvetNetworkClient( 1937): Network connection not availble
,I/ActivityManager(  861): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4258 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/Gmail   ( 4197): notifyAccountChanged
,I/Gmail   ( 4197): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/VelvetNetworkClient( 1937): Network connection not availble
,I/ActivityManager(  861): Killing 3717:com.lge.cloudhub/u0a49 (adj 15): empty #11
,I/VelvetNetworkClient( 1937): Network connection not availble
,I/Gmail   ( 4197): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4197): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4197): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/libprocessgroup(  861): failed to open /acct/uid_10049/pid_3717/cgroup.procs: No such file or directory
,I/NotificationManager( 1937): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
D/jxcore_app_log( 4117): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426127360
,D/JX-Cordova( 4117): jxcore cordova android initializing
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
V/[BNRBootReceiver]( 4258): boot receiver action = android.intent.action.BOOT_COMPLETED
,V/[BNRBootReceiver]( 4258): set property sys.lge.bnrd = 1
V/[BNRBootReceiver]( 4258): End of BootComplted IF
V/[BNRBootReceiver]( 4258): Boot Receiver Return
V/[BNRBootCompletedThread]( 4258): run
W/jxcore-log( 4117): Initializing JXcore engine
W/jxcore-log( 4117): JXcore engine is ready
,W/jxcore-log( 4117): Starting JXcore engine
W/linker  ( 4293): /system/bin/bnrd has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/bnrd    ( 4293): BNRD > wait starting [4293-3058102400] <
,E/bnrd    ( 4293): /data/data/.bnr_fifo_req
I/ActivityManager(  861): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4296 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  861): Killing 3737:com.lge.gnss.airtest/u0a54 (adj 15): empty #11
V/[BNRBootCompletedThread]( 4258): End of BNRProcess
,V/[BNRBootCompletedThread]( 4258): End of BNRViaWifiProcess
V/[BNRBootCompletedThread]( 4258): End of SpriteProcess
V/[BNRBootCompletedThread]( 4258): exit
W/m.example.hello( 4117): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7297]" dev="sockfs" ino=7297 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 4117): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 4117): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7393]" dev="sockfs" ino=7393 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4117): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 4117): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 4117): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[20048]" dev="sockfs" ino=20048 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/libprocessgroup(  861): failed to open /acct/uid_10054/pid_3737/cgroup.procs: No such file or directory
V/GLSActivity( 1982): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4197): getAccountsCursor
V/GLSActivity( 1982): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4197): getAccountsCursor
,V/GLSActivity( 1982): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/jxcore-log( 4117): Platform android
W/jxcore-log( 4117): 
W/jxcore-log( 4117): Process ARCH arm
W/jxcore-log( 4117): 
,D/libc-netbsd( 1982): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1982): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1982): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1982): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  272): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  861): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/jxcore-log( 4117): JXcore Cordova bridge is ready!
I/jxcore-log( 4117): 
W/Search.LoginHelper( 1937): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1937): java.io.IOException: NetworkError
W/Search.LoginHelper( 1937): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1937): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1937): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1937): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1937): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1937): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1937): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1937): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1937): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1937): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1937): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
W/jxcore-log( 4117): JXcore engine is started
,I/ActivityManager(  861): Killing 3758:com.lge.lgfota.permission/1000 (adj 15): empty #11
,E/jxcore-log( 4117): >> LGE-LG-D722
E/jxcore-log( 4117): 
,I/jxcore-log( 4117): Total memory 906309632
I/jxcore-log( 4117): 
I/jxcore-log( 4117): Free memory 30142464
I/jxcore-log( 4117): 
I/jxcore-log( 4117): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4117): 
I/jxcore-log( 4117): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4117): 
I/jxcore-log( 4117): userPath [ 'www' ]
I/jxcore-log( 4117): 
I/jxcore-log( 4117): Size 720 1196
I/jxcore-log( 4117): 
,I/jxcore-log( 4117): Screen Brightness 255
I/jxcore-log( 4117): 
E/jxcore-log( 4117): Dummy Error Log.
E/jxcore-log( 4117): 
W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_3758/cgroup.procs: No such file or directory
,D/libc-netbsd( 1982): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1982): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Search.LoginHelper( 1937): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1937): java.io.IOException: NetworkError
W/Search.LoginHelper( 1937): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1937): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1937): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1937): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1937): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1937): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1937): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1937): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1937): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1937): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1937): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
D/libc-netbsd( 1982): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1982): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Search.LoginHelper( 1937): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1937): java.io.IOException: NetworkError
W/Search.LoginHelper( 1937): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1937): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1937): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1937): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1937): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1937): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1937): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1937): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1937): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1937): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1937): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
D/libc-netbsd( 1982): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1982): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Search.LoginHelper( 1937): IO exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
W/Search.LoginHelper( 1937): java.io.IOException: NetworkError
W/Search.LoginHelper( 1937): 	at com.google.android.gms.auth.b.b(Unknown Source)
W/Search.LoginHelper( 1937): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1937): 	at com.google.android.gms.auth.b.c(Unknown Source)
W/Search.LoginHelper( 1937): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1937): 	at com.google.android.gms.auth.b.a(Unknown Source)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
W/Search.LoginHelper( 1937): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1937): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/Search.LoginHelper( 1937): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/Search.LoginHelper( 1937): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/Search.LoginHelper( 1937): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/Search.LoginHelper( 1937): 	at java.lang.Thread.run(Thread.java:818)
W/Search.LoginHelper( 1937): 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,D/Finsky  ( 4296): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/art     (  861): Explicit concurrent mark sweep GC freed 19083(903KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/33MB, paused 2.111ms total 148.915ms
,I/ActivityManager(  861): Waited long enough for: ServiceRecord{141ae2d u0 com.android.mms/.service.SwitchedService}
,D/Finsky  ( 4296): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 4296): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4296): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 4296): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 2730): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,D/Volley  ( 4296): [443] DiskBasedCache.clear: Cache cleared.
V/DownloadManager( 2730): created cursor android.database.sqlite.SQLiteCursor@6c08546 on behalf of 4296
D/Volley  ( 4296): [436] DiskBasedCache.clear: Cache cleared.
D/Ads     ( 4296): Skipping gmscore version check
,I/ActivityManager(  861): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.ui.editor.reminder.ReminderMaker: pid=4348 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  861): Killing 3796:com.lge.hiddenmenu/1000 (adj 15): empty #11
,I/jxcore-log( 4117): getBuffer is called!!!!
I/jxcore-log( 4117): 
,W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_3796/cgroup.procs: No such file or directory
,D/Finsky  ( 4296): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4296): [1] Libraries$2.run: Finished loading 1 libraries.
W/ResourcesManager( 4348): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/Finsky  ( 4296): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 4296): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/App     ( 4348): [App][onCreate()] 4.40.21
,D/AccountManager( 4348): setSyncFrequency
,W/ContextImpl( 4348): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.qmemoplus.ui.editor.reminder.ReminderMaker.onReceive:14 android.app.ActivityThread.handleReceiver:2663 
,D/ReminderService( 4348): [onHandleIntent] action : com.lge.qmemoplus.action.SET_REMINDERS
D/LocationReminderManager( 4348): [connect] Request location client connection.
W/ContextImpl( 4348): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.google.android.gms.internal.he.a:-1 com.google.android.gms.internal.hc.connect:-1 com.google.android.gms.location.LocationClient.connect:-1 
,I/ActivityManager(  861): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4371 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/art     (  304): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.646ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 21.391ms
,I/ActivityManager(  861): Killing 3814:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 21.677ms
D/LocationReminderManager( 4348): location cilent is connected.
D/LocationReminderManager( 4348): [removeAllReminders]
,W/libprocessgroup(  861): failed to open /acct/uid_10069/pid_3814/cgroup.procs: No such file or directory
W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
D/LocationReminderManager( 4348): [removeAllReminders] statusCode : 1000
D/LocationReminderManager( 4348): [removeAllReminders] Failed to remove reminder
W/ResourcesManager( 4371): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  861): Message: 20
D/BluetoothManagerService(  861): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bf61cd5:true
,D/BluetoothAdapter( 4371): 249621699: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4371): 249621699: getState() :  mService = null. Returning STATE_OFF
I/ActivityManager(  861): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4389 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 4371): Create singleton instance
,D/UEI.SmartControl( 4389): Quickset Services start...
,I/UEI.SmartControl( 4389): Manufacture = LGE
D/UEI.SmartControl( 4389): File observer start...
E/UEI.SmartControl( 4389): IR Port is disabled: false
D/UEI.SmartControl( 4389): Starting file observer...
D/UEI.SmartControl( 4389): Extracting JNI libs...
D/UEI.SmartControl( 4389): --- this system supports 32-bit or 64-bit only
I/AudioManager( 4371): getMode name:com.lge.qremote
,I/AudioManager( 4371): getMode name:com.lge.qremote
,I/ActivityManager(  861): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=4408 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/UEI.SmartControl( 4389): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 4389): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4389): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/ActivityManager(  861): Process com.google.android.talk (pid 4010) has died
,I/UEI.SmartControl( 4389): --- Selecting new region: 2
,I/UEI.SmartControl( 4389): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 4389): Platform has CIR...
D/UEI.SmartControl( 4389): NO CIR support, need to check package...
I/UEI.SmartControl( 4389): Model: LG-D722 uses JNI
D/UEI.SmartControl( 4389): QS Service created
D/LGDMClient( 4408): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
D/LGDMClient( 4408): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4408): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4408): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
E/UEI.SmartControl( 4389): QS start get config
,D/LGDMClient( 4408): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
D/LGDMClient( 4408): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) },
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
D/UEI.SmartControl( 4389): Loading JNI Libs...
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
,D/UEI.SmartControl( 4389):  configuring local db...
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3147): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3147): ANY_DATA_STATE event received: DISCONNECTED
D/LGDMClient( 4408): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
D/LGDMClient( 4408): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4408): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4408): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
I/AudioManager( 4371): getMode name:com.lge.qremote
D/LGDMClient( 4408): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/LGDMClient( 4408): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
,D/WearableService( 1732): callingUid 10006, callindPid: 1732
,E/MDM     ( 1732): [88] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/UEI.SmartControl( 4389):  ---- Has DB8: true
,D/UEI.SmartControl( 4389): QS start statue = true Error code = 0
,I/art     ( 1982): Explicit concurrent mark sweep GC freed 18166(1257KB) AllocSpace objects, 20(320KB) LOS objects, 40% free, 11MB/19MB, paused 1.119ms total 63.408ms
D/UEI.SmartControl( 4389): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 4389): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4389): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 4389): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4389): IrrcClient ++ 
D/irrcClient( 4389): getIrrcService ++ 
D/irrcClient( 4389): getIrrcService -- 
D/irrcClient( 4389): IrrcClient -- 
W/irrc_jni( 4389): IRRCPlayer_nativeInit -- 
,D/GCM     ( 1982): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
D/AuthorizationBluetoothService( 1982): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 3922): Restart initialization of location
V/GLSActivity( 1982): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 4389): Services init done
I/NotificationManager( 1982): com.google.android.gms: cancel(0) by com.google.android.gms
V/GmsCoreStatsServiceLauncher( 3922): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
I/AudioManager( 4371): getMode name:com.lge.qremote
D/UEI.SmartControl( 4389): QS Service init finished
,D/UEI.SmartControl( 4389): QS Service version name: 0.1.73
D/UEI.SmartControl( 4389): QS Service version code: 1073
D/UEI.SmartControl( 4389): Service requested: Control
I/UEI.SmartControl( 4389): Device manager: loading config....
D/UEI.SmartControl( 4389): Config is loaded...
,D/UEI.SmartControl( 4389):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 4389): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 4389): Request IControl service: devices are loaded...
,I/ActivityManager(  861): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4443 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/UEI.SmartControl( 4389): Internal service binding...
,D/UEI.SmartControl( 4389): -----IControl: 11
D/UEI.SmartControl( 4389): Caller: com.lge.qremote
D/UEI.SmartControl( 4389): ------------ IControl registerCallback...
I/UEI.SmartControl( 4389): Registering callback...
D/UEI.SmartControl( 4389): -----IControl: 19
D/UEI.SmartControl( 4389): Caller: com.lge.qremote
I/UEI.SmartControl( 4389): Registering Services Ready callback...
,I/UEI.SmartControl( 4389): Notify client services are ready...
D/UEI.SmartControl( 4389): -----IControl: 8
D/UEI.SmartControl( 4389): Caller: com.lge.qremote
W/GCoreFlp( 1732): No location to return for getLastLocation()
,I/ActivityManager(  861): Killing 3832:com.lge.springcleaning/1000 (adj 15): empty #11
W/FusedLocationProvider( 1982): location=null
W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_3832/cgroup.procs: No such file or directory
,W/ResourcesManager( 4443): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 4443): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4443): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4443): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4443): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4443): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4443): MmsConfig.loadFromResources
E/Babel_SMS( 4443): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4443): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 4443): found sensor: LGE Accelerometer Sensor, handle=0
,D/SensorManager( 4443): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4443): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 4443): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4443): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4443): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4443): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4443): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4443): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4443): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4443): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4443): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4443): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4443): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4443): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4443): found sensor: Motion Accel, handle=46
I/art     ( 4443): CheckpointMarkThreadRoots callback created = 0xb042d880
W/Settings( 4443): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4443): startup - clean
,I/art     ( 4443): CheckpointMarkThreadRoots callback created = 0xb042d850
I/Babel   ( 4443): deleted: false for 0
,W/AudioCapabilities( 4443): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 4443): Unsupported mime audio/adpcm
W/AudioCapabilities( 4443): Unsupported mime audio/g726
W/AudioCapabilities( 4443): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4443): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4443): Unsupported mime video/mjpg
W/VideoCapabilities( 4443): Unsupported mime video/theora
,W/AudioCapabilities( 4443): Unsupported mime audio/evrc
,W/AudioCapabilities( 4443): Unsupported mime audio/qcelp
W/VideoCapabilities( 4443): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4443): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 4443): Unsupported mime audio/qcelp
W/AudioCapabilities( 4443): Unsupported mime audio/evrc
W/VideoCapabilities( 4443): Unsupported mime video/mp4v-esdp
,I/ActivityManager(  861): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4470 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/VideoCapabilities( 4443): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4443): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4443): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4443): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4443): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  861): Killing 3866:com.google.android.configupdater/u0a3 (adj 15): empty #11
W/ResourcesManager( 4470): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4470): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4470): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  861): failed to open /acct/uid_10003/pid_3866/cgroup.procs: No such file or directory
,I/vclib   ( 4443): onServiceConnected
W/Babel   ( 4443): Attempted to change video mute state without an active call.
I/NotificationManager( 4443): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/LGEmail ( 4470): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 4470): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/PackageChangeReceiver( 4470): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  861): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4492 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  861): Killing 3901:com.lge.eula/1000 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_3901/cgroup.procs: No such file or directory
,I/ActivityManager(  861): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4515 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/ActivityManager(  861): Waited long enough for: ServiceRecord{fa03458 u0 com.lge.mlt/.MltMonitorService}
,I/ActivityManager(  861): Killing 4048:com.google.android.youtube/u0a100 (adj 15): empty #11
,W/libprocessgroup(  861): failed to open /acct/uid_10100/pid_4048/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 4515): onCreate
W/AppUp4:DB( 4515):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 4515):  setFingerPrint start
I/AppUp4:DB( 4515):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 4515):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4515):  SDK version = 0
I/AppUp4:DB( 4515):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 4515): AppBoxApplication onCreate()
D/AppUp4:PreloadHelper( 4515): removed from Exclude : com.example.hello : 1
,I/ActivityManager(  861): Killing 4197:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_10053/pid_4197/cgroup.procs: No such file or directory
,I/ActivityManager(  861): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=4532 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 4532): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4532): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 4532): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 4532): Total System Memory = 906309632
,I/GalleryUtils( 4532): Application Heap = 96 MB
I/AppConfig( 4532): App Tier : NOT_DEF
D/SystemHelper( 4532): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  861): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=4560 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  861): Killing 4258:com.lge.bnr/1000 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_4258/cgroup.procs: No such file or directory
,W/ResourcesManager( 4560): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4560): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 4560): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 4560): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 4560): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 4560): BUILD Country: EU
,I/SystemConfig( 4560): BUILD Operator: OPEN
,I/SystemConfig( 4560): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 4560): existFile = false
I/SystemConfig( 4560): canReadFile = false
I/SystemConfig( 4560): systemFeature RCS result false
D/SystemConfig( 4560): refreshRcsSupport() :false
,I/ActivityManager(  861): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=4579 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  861): Killing 4296:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_10036/pid_4296/cgroup.procs: No such file or directory
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/LockScreenSettings( 4579): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 4579): New app installed broadcast received ..
,I/LockScreenSettings( 4579): Number of installed packages  1
I/ActivityManager(  861): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=4596 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  861): Killing 4348:com.lge.qmemoplus/1000 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_4348/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 4596): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 4596): uri : package:com.example.hello
,I/ActivityManager(  861): Killing 4408:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_4408/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 3922): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3922): Loading module APK com.google.android.play.games
D/PackageBroadcastService( 3922): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.example.hello
D/ChimeraCfgMgr( 3922): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 3922): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 3922): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/PeopleContactsSync( 3922): CP2 sync disabled
D/AsyncTaskServiceImpl( 3922): Submit a task: h
,I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  861): Reconfiguring input devices.  changes=0x00000010
I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
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
D/administrator(  861): Handling package changes for user 0
I/Icing   ( 3922): Storage manager: low false usage 1.61MB avail 2.05GB capacity 3.45GB
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/ChimeraCfgMgr( 3922): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 3922): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/h       ( 3922): Processing package: com.example.hello
I/[LGHome]Launcher( 1876): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/Icing   ( 3922): Received bad json for section weights override -- ignoring.
I/art     ( 1785): CheckpointMarkThreadRoots callback created = 0xaaf1eb80
,D/GassUtils( 3922): Found app info for package com.example.hello:18. Hash: 68ddfd019b48f789223df845f1e49bbdc6edef025bd9dbaddc0e41222bbc602e
,D/h       ( 3922): Found info for package com.example.hello in db.
W/Icing   ( 3922): Received bad json for corpus context scoring override -- ignoring.
W/Icing   ( 3922): Received bad json for section weights override -- ignoring.
W/Icing   ( 3922): Received bad json for corpus context scoring override -- ignoring.
,I/ActivityManager(  861): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=4635 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/art     ( 1785): CheckpointMarkThreadRoots callback created = 0xb042d710
I/art     (  304): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 314us total 23.060ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 20.950ms
,D/BluetoothManagerService(  861): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  861): disable(): mBluetooth = null mBinding = false
D/BluetoothManagerService(  861): Message: 2
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 311us total 21.067ms
,D/WifiServiceImplEx(  861): setWifiEnabled: false pid=4117, uid=10030, package= com.example.hello, App Lable : HelloWorld
D/WifiService(  861): setWifiEnabled: false pid=4117, uid=10030
I/jxcore-log( 4117): ****TEST TOOK:  5119  ms ****
I/jxcore-log( 4117): 
I/jxcore-log( 4117): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4117): 
,I/art     (  861): Explicit concurrent mark sweep GC freed 22223(1026KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.320ms total 245.620ms
,W/BaseAppContext( 3922): Using Auth Proxy for data requests.
W/BaseAppContext( 3922): Using Auth Proxy for data requests.
,W/BaseAppContext( 3922): Using Auth Proxy for data requests.
,W/BaseAppContext( 3922): Using Auth Proxy for data requests.
W/BaseAppContext( 3922): Using Auth Proxy for data requests.
W/BaseAppContext( 3922): Using Auth Proxy for data requests.
,W/ResourcesManager(  861): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/NotificationService(  861): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  861): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  861): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  861): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  861): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  861): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@29a07ff8
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
,D/AndroidRuntime( 4654): 
D/AndroidRuntime( 4654): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,D/AndroidRuntime( 4654): CheckJNI is OFF
W/ResourceType(  861): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1732): DISABLE
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  861): Waited long enough for: ServiceRecord{feb36e1 u0 com.android.calendar/.alerts.InitAlarmsService}
,D/LocationProviderProxy(  861): applying state to connected service
D/AndroidRuntime( 4654): Calling main entry com.android.commands.pm.Pm
,I/Icing   ( 3922): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  861): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
I/ActivityManager(  861): Killing 4117:com.example.hello/u0a30 (adj 0): stop com.example.hello
,I/WindowState(  861): WIN DEATH: Window{734106c u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  861): Focus left window: Window{734106c u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  861): Window went away: Window{734106c u0 com.example.hello/com.example.hello.MainActivity}
,W/PackageSettings(  861): Skipping PackageSetting{17379625 com.test.thalitest/10316} due to missing metadata
,D/ChimeraCfgMgr( 3922): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 3922): Module APK com.google.android.play.games already loaded
,I/GAv4    ( 4635): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4635):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4635):   adb logcat -s GAv4
,E/GameAgent( 3922): Caller attempted to insert game data for non-existent package.
E/GameAgent( 3922): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
E/GameAgent( 3922): 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:281)
E/GameAgent( 3922): 	at com.google.android.gms.games.broker.GameAgent.registerGame(GameAgent.java:1562)
E/GameAgent( 3922): 	at com.google.android.gms.games.broker.DataBroker.registerGame(DataBroker.java:3120)
E/GameAgent( 3922): 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:24)
E/GameAgent( 3922): 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:978)
E/GameAgent( 3922): 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
E/GameAgent( 3922): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/GameAgent( 3922): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/GameAgent( 3922): 	at java.lang.Thread.run(Thread.java:818)
,W/ActivityManager(  861): Force removing ActivityRecord{ab4d05a u0 com.example.hello/.MainActivity t220}: app died, no saved state
,W/ActivityManager(  861): Spurious death for ProcessRecord{e9b5a58 4117:com.example.hello/u0a30}, curProc for 4117: null
I/ActivityManager(  861): Force stopping com.example.hello appid=10030 user=0: pkg removed
I/[LGHome]EVENT( 1876): [Launcher.java:5203:onStart()]onStart
,W/GAv4    ( 4635): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
I/[LGHome]EVENT( 1876): [Launcher.java:776:onResume()]onResume
,D/KeyguardModel( 1371): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1732): Ignoring removeGeofence because network location is disabled.
,I/InputReader(  861): Reconfiguring input devices.  changes=0x00000010
D/administrator(  861): Handling package changes for user 0
W/System.err( 3418): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 3418): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3418): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3418): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3418): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3418): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3418): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3418): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3418): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3418): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3418): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3418): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
D/KeyguardModel( 1371): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1371): createShortcutInfo...
I/[LGHome]EVENT( 1876): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_REMOVED
D/KeyguardModel( 1371): package = com.android.mms, class = com.android.mms.ui.ConversationList
I/[LGHome]LGActivityUtil( 1876): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/KeyguardModel( 1371): createShortcutInfo...
I/art     ( 3922): Explicit concurrent mark sweep GC freed 33442(2MB) AllocSpace objects, 30(480KB) LOS objects, 39% free, 12MB/21MB, paused 1.390ms total 123.476ms
I/[LGHome]EVENT( 1876): [Launcher.java:929:onResume()]onResume end
I/Activity( 1876): Activity.onPostResume() called 
,W/GAv4    ( 4635): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.mms: Resource ID #0x0
W/[LGHome]LGWallpaperInfo( 1876): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1876): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,D/KeyguardModel( 1371): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1371): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1371): createShortcutInfo...
I/SystemUI[Framework](  861): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  861): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  861): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  861): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  861): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1d99f586,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  861): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,D/InputDispatcher(  861): Focus entered window: Window{20e8dd69 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1371): createShortcutInfo...
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1876): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,W/GAv4    ( 4635): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1371): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/KeyguardModel( 1371): handleShortcutListChanged...
I/[LGHome]EVENT( 1876): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1876): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1371): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1371): createShortcutInfo...
D/KeyguardModel( 1371): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1371): createShortcutInfo...
W/AnalyticsTrackerProxyImpl( 4635): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,I/NotificationService(  861): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  861): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService(  861): Receieved: android.intent.action.PACKAGE_REMOVED
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1371): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1371): createShortcutInfo...
W/ResourceType( 1371): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1371): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1371): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1371): createShortcutInfo...
D/PhoneStatusBar( 1371): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
D/TaskPersister(  861): removeObsoleteFile: deleting file=220_task.xml
,D/KeyguardModel( 1371): handleShortcutListChanged...
I/Icing   ( 3922): Internal init done: storage state 0
,I/Icing   ( 3922): Post-init done
E/Icing   ( 3922): Package com.example.hello not found
,W/InputMethodManagerService(  861): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  861): Got RemoteException sending setActive(false) notification to pid 4117 uid 10030
,I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
,I/SystemUI[Framework](  861): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
I/HotwordDetector( 1937): Closing mic
D/PhoneStatusBar( 1371): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
W/PhoneWindowManagerEx(  861): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  861): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  861): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  861): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1d99f586,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  861): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/HotwordRecognitionRnr( 1937): Stopping hotword detection.
I/[SystemUI]NavigationThemeResource( 1371): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1371):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1371): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1371): draw background and invalidate : color = ed000000
,D/BarTransitions( 1371): draw background and invalidate : color = e9e0e0e0
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
W/art     ( 4635): Suspending all threads took: 10.614ms
,I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1876): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1876): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
,W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/ResourceType(  861): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
,W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
,W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
,W/Resources( 1876): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
E/VoldCmdListener(  243): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  243): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  243): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4635): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
I/ActivityManager(  861): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4692 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     (  861): Explicit concurrent mark sweep GC freed 26550(1695KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 22MB/34MB, paused 8.377ms total 650.336ms
I/ActivityManager(  861): Killing 4389:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/art     ( 4635): CheckpointMarkThreadRoots callback created = 0xb0510c20
,W/System.err( 4371): android.os.DeadObjectException
W/System.err( 4371): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4371): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4371): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 4371): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 4371): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4371): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4371): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4371): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4371): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4371): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4371): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4371): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4371): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4371): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4371): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 4371): android.os.DeadObjectException
W/System.err( 4371): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4371): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4371): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 4371): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 4371): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4371): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4371): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4371): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4371): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4371): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4371): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4371): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4371): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4371): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4371): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/ResourcesManager( 4635): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4635): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/AndroidRuntime( 4654): Shutting down VM
,I/art     ( 4635): CheckpointMarkThreadRoots callback created = 0xb0510bf0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
,I/[LGHome]Launcher.Model( 1876): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
I/[LGHome]EVENT( 1876): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1876): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1876): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/Timeline(  861): Timeline: Activity_windows_visible id: ActivityRecord{2b712ce1 u0 com.lge.launcher2/.Launcher t219} time:66308
W/libprocessgroup(  861): failed to open /acct/uid_10089/pid_4389/cgroup.procs: No such file or directory
W/ActivityManager(  861): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
,I/NotificationManager( 4635): com.google.android.apps.docs: cancel(10436) by com.google.android.apps.docs
,W/ResourcesManager( 4692): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager(  861): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4715 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/HotwordRecognitionRnr( 1937): Starting hotword detection.
W/OpenGLRenderer( 1876): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
W/OpenGLRenderer( 1876): Incorrectly called buildLayer on View: ShortcutAndWidgetContainer, destroying layer...
I/MicrophoneInputStream( 1937): mic_starting com.google.android.apps.gsa.speech.audio.u@3e0e685b
V/AudioRecord( 1937): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
,V/AudioRecord( 1937): set(): mSessionId 22
,V/AudioPolicyManager(  281): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 22, flags 0
V/AudioPolicyManager(  281): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  281): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  281): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546e1a0)
V/audio_hw_primary(  281): adev_open_input_stream: exit
V/AudioFlinger(  281): openInput_l() openInputStream returned input 0xb546e1a0, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  281): openInput_l() created record thread: ID 23 thread 0xb3846000
I/AudioFlinger(  281): AudioFlinger's thread 0xb3846000 ready to run
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioSystem(  281): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem(  861): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 1371): ioConfigChanged() event 3, ioHandle 23
D/audio_hw_primary(  281): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  281): in_standby: exit:  status(0)
V/AudioFlinger(  281): RecordThread: loop stopping
V/AudioSystem( 1739): ioConfigChanged() event 3, ioHandle 23
V/AudioPolicyService(  281): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  281): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioSystem( 1937): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 3147): ioConfigChanged() event 3, ioHandle 23
V/AudioSystem( 2672): ioConfigChanged() event 3, ioHandle 23
V/AudioFlinger(  281): openRecord() lSessionId: 22 input 23
,V/AudioFlinger(  281): getOrphanEffectChain_l session 22 index -2
V/AudioFlinger(  281): acquiring 22 from 1937, for -1
V/AudioFlinger(  281):  added new entry for 22
V/AudioRecord( 1937): start, sync event 0 trigger session 0
V/AudioRecord( 1937): mAudioRecord->start()
V/AudioFlinger(  281): RecordHandle::start()
V/AudioFlinger(  281): RecordThread::start event 0, triggerSession 0
V/AudioPolicyManager(  281): startInput() module primary->input primary(23)
V/AudioPolicyManager(  281): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  281): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  281): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  281): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  281): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  281): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  281): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  281): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  281): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): RecordThread: loop starting
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  281): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  281): in_set_parameters: exit: status(0)
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb3846000
V/AudioFlinger::PatchPanel(  281): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  281): createAudioPatch() added new patch handle 24 halHandle 0
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyManager(  281): setInputDevice() createAudioPatch returned 0 patchHandle 24
V/AudioPolicyManager(  281): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  281): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  281): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
V/AudioPolicyService(  281): AudioCommandThread() adding set parameter string hotword_active=1, io 23 ,delay 0
V/AudioPolicyService(  281): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  281): AudioCommandThread() waking up
V/AudioPolicyService(  281): AudioCommandThread() processing set parameters string hotword_active=1, io 23
V/AudioFlinger(  281): setParameters(): io 23, keyvalue hotword_active=1, calling pid 281
V/AudioFlinger(  281): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  281): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  281): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  281): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  281): in_set_parameters: exit: status(0)
V/AudioFlinger(  281): processConfigEvents_l() DONE thread 0xb3846000
V/AudioPolicyService(  281): AudioCommandThread() going to sleep
,V/AudioPolicyManager(  281): AudioPolicyManager::startInput() input source = 1999
I/Timeline( 1876): Timeline: Activity_idle id: android.os.BinderProxy@3000edad time:66454
V/msm8974_platform(  281): platform_update_usecase_from_source: input source :6
D/audio_hw_primary(  281): start_input_stream: enter: stream(0xb546e1a0)usecase(7: audio-record)
V/voice   (  281): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  281): start_input_stream: usecase(7)
E/audio_hw_primary(  281): select_devices: enter and usecase(7)
V/msm8974_platform(  281): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  281): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  281): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  281): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  281): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  281): enable_snd_device: enter  144
D/hardware_info(  281): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  281): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  281): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
I/MicrophoneInputStream( 1937): mic_started com.google.android.apps.gsa.speech.audio.u@3e0e685b
D/ACDB-LOADER(  281): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  281): ACDB -> send_adm_topology
D/ACDB-LOADER(  281): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
D/ACDB-LOADER(  281): ACDB -> send_asm_topology
D/ACDB-LOADER(  281): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  281): ACDB -> send_audtable
D/ACDB-LOADER(  281): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  281): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  281): ACDB -> send_audvoltable
D/ACDB-LOADER(  281): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  281): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  281): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  281): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  281): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  281): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  281): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  281): enable_audio_route: apply mixer and update path: audio-record
V/audio_hw_primary(  281): enable_audio_route: exit
D/audio_hw_primary(  281): select_devices: done
V/audio_hw_primary(  281): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
V/audio_hw_primary(  281): start_input_stream: exit
V/JNIHelp ( 4635): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,W/FileUtils( 1982): Failed to chmod(/data/data/com.google.android.gms/shared_prefs/sizeCache.xml): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,E/UEI.SmartControl( 4715): Failed while opening the log file.
E/UEI.SmartControl( 4715): java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.lite/app_log/app.log: open failed: EROFS (Read-only file system)
E/UEI.SmartControl( 4715): 	at libcore.io.IoBridge.open(IoBridge.java:456)
E/UEI.SmartControl( 4715): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
E/UEI.SmartControl( 4715): 	at java.io.FileWriter.<init>(FileWriter.java:58)
E/UEI.SmartControl( 4715): 	at com.uei.f.c.a(Unknown Source)
E/UEI.SmartControl( 4715): 	at com.uei.f.c.a(Unknown Source)
E/UEI.SmartControl( 4715): 	at com.uei.f.c.<init>(Unknown Source)
E/UEI.SmartControl( 4715): 	at com.uei.f.c.a(Unknown Source)
E/UEI.SmartControl( 4715): 	at com.uei.control.core.QSApp.onCreate(Unknown Source)
E/UEI.SmartControl( 4715): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1011)
E/UEI.SmartControl( 4715): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4657)
E/UEI.SmartControl( 4715): 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
E/UEI.SmartControl( 4715): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
E/UEI.SmartControl( 4715): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/UEI.SmartControl( 4715): 	at android.os.Looper.loop(Looper.java:135)
E/UEI.SmartControl( 4715): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/UEI.SmartControl( 4715): 	at java.lang.reflect.Method.invoke(Native Method)
E/UEI.SmartControl( 4715): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/UEI.SmartControl( 4715): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/UEI.SmartControl( 4715): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4715): Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
E/UEI.SmartControl( 4715): 	at libcore.io.Posix.open(Native Method)
E/UEI.SmartControl( 4715): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
E/UEI.SmartControl( 4715): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/UEI.SmartControl( 4715): 	... 18 more
D/UEI.SmartControl( 4715): Quickset Services start...
,I/UEI.SmartControl( 4715): Manufacture = LGE
D/UEI.SmartControl( 4715): File observer start...
E/UEI.SmartControl( 4715): IR Port is disabled: false
D/UEI.SmartControl( 4715): Starting file observer...
D/UEI.SmartControl( 4715): Extracting JNI libs...
D/UEI.SmartControl( 4715): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 4715): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 4715): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4715): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,W/System  ( 4635): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4635): Installed default security provider GmsCore_OpenSSL
E/UEI.SmartControl( 4715): unzip: java.io.FileNotFoundException: /data/data/com.uei.lg.quicksetsdk.lite/files/libqs_jni.so: open failed: EROFS (Read-only file system)
I/UEI.SmartControl( 4715): --- Selecting new region: 2
I/UEI.SmartControl( 4715): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 4715): Platform has CIR...
D/UEI.SmartControl( 4715): NO CIR support, need to check package...
I/UEI.SmartControl( 4715): Model: LG-D722 uses JNI
V/GLSActivity( 1982): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 4715): QS Service created

```
