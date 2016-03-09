#### Test 6012434764ab483_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/CalendarProvider2( 4684): Created com.android.providers.calendar.CalendarAlarmManager@331cc776(com.android.providers.calendar.CalendarProvider2@bd0995)
D/CalendarProviderBroadcastReceiver( 4684): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 4684): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 4684): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 4684): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 4684): [getOrCreateCalendarAlarmManager]
D/WearableService( 1730): callingUid 10006, callindPid: 1730
D/LocationInitializer( 4122): Restart initialization of location
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1730): [130] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/CalendarProvider2( 4684): [IntentService] Release Lock
D/CalendarProvider2( 4684): CalendarProviderIntentService.onDestroy()
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,I/art     ( 3820): Explicit concurrent mark sweep GC freed 2778(109KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 3.567ms total 48.613ms
--------- beginning of system
I/ActivityManager(  861): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=4722 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 327us total 23.576ms
W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 22.715ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 298us total 22.399ms
W/IcingInternalCorpora( 4122): getNumBytesRead when not calculated.
D/AndroidRuntime( 4717): 
D/AndroidRuntime( 4717): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4717): CheckJNI is OFF
W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 4722): getAccountsCursor
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
D/AndroidRuntime( 4717): Calling main entry com.android.commands.am.Am
I/art     (  861): Explicit concurrent mark sweep GC freed 14906(738KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 2.834ms total 157.517ms
W/ActivityManager(  861): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  861): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/Gmail   ( 4722): Observing account changes for notifications
D/ActivityManager(  861): setTaskToReturnTo : TaskRecord{23d39e89 #224 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  861): setTaskToReturnTo : TaskRecord{23d39e89 #224 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  861): AppWindowTokenEx init.. 
D/ContextHelper(  861): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
I/PhoneWindow(  861): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx(  861): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  861): [setNavigationBarColor2] color=0x fff5f5f5
D/SplitWindow(  861): check instance of lgWin Window{1392e6a8 u0 Starting com.test.thalitest}
I/[LGHome]EVENT( 1874): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  861): Focus left window: Window{936d916 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 4717): Shutting down VM
W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/GAV2    ( 4722): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/ActivityManager(  861): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4766 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/[LGHome]EVENT( 1874): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
E/Gmail   ( 4722): Error finding the version of the Email provider.....
E/Gmail   ( 4722): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4722): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4722): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4722): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4722): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4722): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4722): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4722): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 4722): We do not support migrating this version of the Email provider.
I/Gmail   ( 4722): getAccountsCursor
I/[LGHome]EVENT( 1874): [Launcher.java:5214:onStop()]onStop
I/WindowStateAnimator(  861): Starting window displayed
D/WindowManager(  861): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/SystemUI[Framework](  861): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
I/[SystemUI]NavigationThemeResource( 1370): notify navigation bar color(0xfff5f5f5)
W/PhoneWindowManagerEx(  861): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  861): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  861): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  861): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@c4e9513,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  861): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
D/UEI.SmartControl( 4458): Internal timer expired: 1
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/HotwordDetector( 1935): Closing mic
I/ActivityManager(  861): Killing 4458:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,I/MicrophoneInputStream( 1935): mic_close com.google.android.apps.gsa.speech.audio.u@28acdfef
V/AudioRecord( 1935): stop()
D/AudioRecord( 1935): AudioRecord->stop()
V/AudioFlinger(  285): RecordHandle::stop()
V/AudioFlinger(  285): RecordThread::stop
,V/AudioFlinger(  285): Record stopped OK
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
,V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb3e5a000
D/audio_hw_primary(  285): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  285): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  285): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  285): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  285): disable_audio_route: reset and update mixer path: audio-record
,V/audio_hw_primary(  285): disable_audio_route: exit
E/audio_hw_primary(  285): disable_snd_device: enter 144
D/hardware_info(  285): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  285): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  285): stop_input_stream: exit: status(0)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioFlinger(  285): RecordThread: loop stopping
V/AudioPolicyManager(  285): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  285): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  285): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
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
V/AudioFlinger(  285): processConfigEvents_l() DONE thread 0xb3e5a000
V/AudioFlinger(  285): RecordThread: loop stopping
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioRecord( 1935): stop()
,V/AudioRecord( 1935): stop()
V/AudioRecord( 1935): stop()
D/ContextHelper( 4766): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
V/AudioFlinger(  285): releasing 16 from 1935 for -1
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
V/AudioSystem( 2601): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  861): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  285): RecordThread 0xb3e5a000 exiting
V/AudioSystem( 3088): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1749): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  285): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  285): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  285): in_standby: exit:  status(0)
V/AudioPolicyService(  285): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  285): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  285): releaseInput() exit
V/AudioFlinger(  285): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  285): AudioCommandThread() waking up
V/AudioFlinger(  285): removeClient_l() pid 1935, calling pid 285
V/AudioPolicyService(  285): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  285): AudioCommandThread() going to sleep
V/AudioSystem( 1370): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1935): ioConfigChanged() event 4, ioHandle 17
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/HotwordRecognitionRnr( 1935): Stopping hotword detection.
I/HotwordRecognitionRnr( 1935): Hotword detection finished
,W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
,W/libprocessgroup(  861): failed to open /acct/uid_10089/pid_4458/cgroup.procs: No such file or directory
W/ActivityManager(  861): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,W/System.err( 4433): android.os.DeadObjectException
W/System.err( 4433): 	at android.os.BinderProxy.transactNative(Native Method)
,W/System.err( 4433): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4433): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 4433): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 4433): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4433): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4433): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4433): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4433): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4433): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4433): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4433): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4433): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4433): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4433): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 4433): android.os.DeadObjectException
W/System.err( 4433): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4433): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4433): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 4433): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 4433): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4433): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4433): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4433): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4433): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4433): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4433): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4433): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4433): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4433): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4433): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/WebViewFactory( 4766): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/ActivityManager(  861): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4804 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/LibraryLoader( 4766): Time to load native libraries: 3 ms (timestamps 9370-9373)
I/LibraryLoader( 4766): Expected native library version number "",actual native library version number ""
,I/ActivityManager(  861): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4823 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  861): Waited long enough for: ServiceRecord{300902f u0 com.lge.springcleaning/.service.AppCleanupService}
,V/WebViewChromiumFactoryProvider( 4766): Binding Chromium to main looper Looper (main, tid 1) {34b1177}
,I/LibraryLoader( 4766): Expected native library version number "",actual native library version number ""
I/chromium( 4766): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4766): Initializing chromium process, singleProcess=true
W/art     ( 4766): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4766): ApplicationContext is null in ApplicationStatus
I/Gmail   ( 4722): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 4823): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/UEI.SmartControl( 4804): Quickset Services start...
I/UEI.SmartControl( 4804): Manufacture = LGE
,I/Gmail   ( 4722): notifyAccountChanged
I/Gmail   ( 4722): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/UEI.SmartControl( 4804): File observer start...
E/UEI.SmartControl( 4804): IR Port is disabled: false
,D/UEI.SmartControl( 4804): Starting file observer...
D/UEI.SmartControl( 4804): Extracting JNI libs...
D/UEI.SmartControl( 4804): --- this system supports 32-bit or 64-bit only
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4722): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 4722): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/chromium( 4766): [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
I/Gmail   ( 4722): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/UEI.SmartControl( 4804): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 4804): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4804): --- Extracting JNI libs: libqs_armeabi-v7a.zip
W/chromium( 4766): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4766): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4766): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4766): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4766): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4766): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4766): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4766): Remote Branch: 
I/Adreno-EGL( 4766): Local Patches: 
I/Adreno-EGL( 4766): Reconstruct Branch: 
I/Gmail   ( 4722): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/UEI.SmartControl( 4804): --- Selecting new region: 2
I/UEI.SmartControl( 4804): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 4804): Platform has CIR...
D/UEI.SmartControl( 4804): NO CIR support, need to check package...
I/UEI.SmartControl( 4804): Model: LG-D722 uses JNI
D/UEI.SmartControl( 4804): QS Service created
,E/UEI.SmartControl( 4804): QS start get config
,D/UEI.SmartControl( 4804): Loading JNI Libs...
,D/UEI.SmartControl( 4804):  configuring local db...
V/AudioPolicyService(  285): registerClient() client 0xb551cf60, uid 10316
,D/BluetoothManagerService(  861): Message: 20
D/BluetoothManagerService(  861): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@25dc1377:true
D/BluetoothAdapter( 4766): 383077907: getState() :  mService = null. Returning STATE_OFF
,W/art     ( 4766): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4766): onDetachedFromWindow called when already detached. Ignoring
I/PhoneWindow( 4766): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 4766): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 4766): [setNavigationBarColor2] color=0x fff5f5f5
D/SystemWebViewEngine( 4766): CordovaWebView is running on device made by: LGE
,I/Babel_SMS( 4823): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4823): MmsConfig.loadMmsSettings
I/Babel_SMS( 4823): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4823): MmsConfig.loadFromDatabase
W/art     ( 4766): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4766): Attempt to remove local handle scope entry from IRT, ignoring
,E/Babel_SMS( 4823): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4823): MmsConfig.loadFromResources
E/Babel_SMS( 4823): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4823): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/UEI.SmartControl( 4804):  ---- Has DB8: true
,D/UEI.SmartControl( 4804): QS start statue = true Error code = 0
D/UEI.SmartControl( 4804): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4804): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4804): IRRCDataComm has AudioManager!!!!.
,I/Activity( 4766): Activity.onPostResume() called 
,D/OpenGLRenderer( 4766): Render dirty regions requested: true
I/OpenGLRenderer( 4766): Initialized EGL, version 1.4
W/irrc_jni( 4804): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4804): IrrcClient ++ 
D/irrcClient( 4804): getIrrcService ++ 
,D/irrcClient( 4804): getIrrcService -- 
D/irrcClient( 4804): IrrcClient -- 
W/irrc_jni( 4804): IRRCPlayer_nativeInit -- 
D/SensorManager( 4823): found sensor: LGE Accelerometer Sensor, handle=0
D/UEI.SmartControl( 4804): Services init done
D/SensorManager( 4823): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4823): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 4823): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4823): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4823): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4823): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4823): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4823): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4823): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4823): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4823): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4823): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4823): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4823): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4823): found sensor: Motion Accel, handle=46
D/OpenGLRenderer( 4766): Enabling debug mode 0
I/UEI.SmartControl( 4804): Device manager: loading config....
,D/UEI.SmartControl( 4804): QS Service init finished
I/art     ( 4823): CheckpointMarkThreadRoots callback created = 0xaaf543d0
D/UEI.SmartControl( 4804): QS Service version name: 0.1.73
D/UEI.SmartControl( 4804): QS Service version code: 1073
D/UEI.SmartControl( 4804): Service requested: Control
D/UEI.SmartControl( 4804): Config is loaded...
D/Atlas   ( 4766): Validating map...
,D/SplitWindow(  861): check instance of lgWin Window{de8f00a u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 4766): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/UEI.SmartControl( 4804):  ----- QS SDK is ready!!!
I/art     ( 4823): CheckpointMarkThreadRoots callback created = 0xaaf543b0
,I/UEI.SmartControl( 4804): Notify AllClients services are ready: 0
W/Settings( 4823): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 4823): startup - clean
,D/UEI.SmartControl( 4804): Request IControl service: devices are loaded...
D/UEI.SmartControl( 4804): -----IControl: 11
D/UEI.SmartControl( 4804): Caller: com.lge.qremote
D/InputDispatcher(  861): Focus entered window: Window{de8f00a u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/UEI.SmartControl( 4804): ------------ IControl registerCallback...
I/UEI.SmartControl( 4804): Registering callback...
,D/UEI.SmartControl( 4804): -----IControl: 19
D/UEI.SmartControl( 4804): Internal service binding...
D/UEI.SmartControl( 4804): Caller: com.lge.qremote
I/UEI.SmartControl( 4804): Registering Services Ready callback...
I/UEI.SmartControl( 4804): Notify client services are ready...
D/UEI.SmartControl( 4804): -----IControl: 8
D/UEI.SmartControl( 4804): Caller: com.lge.qremote
W/InputMethodManagerService(  861): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/Babel   ( 4823): deleted: false for 0
,I/ActivityManager(  861): Displayed com.test.thalitest/.MainActivity: +1s358ms
I/Timeline(  861): Timeline: Activity_windows_visible id: ActivityRecord{225e6e8e u0 com.test.thalitest/.MainActivity t224} time:70282
I/Timeline( 4766): Timeline: Activity_idle id: android.os.BinderProxy@3d7627fe time:70292
I/ActivityManager(  861): Killing 4535:com.lge.sync/1000 (adj 15): empty #11
,W/BindingManager( 4766): Cannot call determinedVisibility() - never saw a connection for the pid: 4766
,W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_4535/cgroup.procs: No such file or directory
,D/AlertService( 3625): Beginning updateAlertNotification
,W/AudioCapabilities( 4823): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 4823): Unsupported mime audio/adpcm
,W/AudioCapabilities( 4823): Unsupported mime audio/g726
W/AudioCapabilities( 4823): Unsupported mime audio/x-ms-wma
D/AlertService( 3625): No fired or scheduled alerts
W/AudioCapabilities( 4823): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4823): Unsupported mime video/mjpg
I/NotificationManager( 3625): com.android.calendar: cancel(0) by com.android.calendar
,I/NotificationManager( 3625): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3625): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3625): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3625): com.android.calendar: cancel(4) by com.android.calendar
W/VideoCapabilities( 4823): Unsupported mime video/theora
I/NotificationManager( 3625): com.android.calendar: cancel(5) by com.android.calendar
,I/NotificationManager( 3625): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3625): com.android.calendar: cancel(7) by com.android.calendar
,I/NotificationManager( 3625): com.android.calendar: cancel(8) by com.android.calendar
,I/NotificationManager( 3625): com.android.calendar: cancel(9) by com.android.calendar
,I/NotificationManager( 3625): com.android.calendar: cancel(10) by com.android.calendar
,W/AudioCapabilities( 4823): Unsupported mime audio/evrc
,I/NotificationManager( 3625): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3625): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3625): com.android.calendar: cancel(13) by com.android.calendar
,W/AudioCapabilities( 4823): Unsupported mime audio/qcelp
W/VideoCapabilities( 4823): Unrecognized profile 2130706433 for video/avc
I/NotificationManager( 3625): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3625): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3625): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3625): com.android.calendar: cancel(17) by com.android.calendar
,I/NotificationManager( 3625): com.android.calendar: cancel(18) by com.android.calendar
W/AudioCapabilities( 4823): Unsupported mime audio/amr-wb-plus
I/NotificationManager( 3625): com.android.calendar: cancel(19) by com.android.calendar
W/AudioCapabilities( 4823): Unsupported mime audio/qcelp
W/AudioCapabilities( 4823): Unsupported mime audio/evrc
I/NotificationManager( 3625): com.android.calendar: cancel(20) by com.android.calendar
,D/JsMessageQueue( 4766): Set native->JS mode to OnlineEventsBridgeMode
,W/VideoCapabilities( 4823): Unsupported mime video/mp4v-esdp
I/ActivityManager(  861): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=4885 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/AlertService( 3625): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 3625): No events found starting within 1 week.
,I/VideoCapabilities( 4823): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 4823): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4823): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4823): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4823): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  861): Killing 4433:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_10106/pid_4433/cgroup.procs: No such file or directory
,I/vclib   ( 4823): onServiceConnected
W/Babel   ( 4823): Attempted to change video mute state without an active call.
I/NotificationManager( 4823): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/PhoneMonitor( 4885): Register our PhoneStateListener
,I/ActivityManager(  861): Killing 4508:com.android.settings/1000 (adj 15): empty #11
,D/PhoneMonitor( 4885): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 4885): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 4885): [parse] Load xml
V/TelephonyAutoProfiling( 4885): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 4885): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_4508/cgroup.procs: No such file or directory
,D/PhoneMonitor( 4885): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  861): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4908 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/jxcore_app_log( 4766): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622879616
,W/ResourcesManager( 4908): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/ActivityManager(  861): Process com.google.android.music:main (pid 4614) has died
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4766): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4766):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4766):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4766):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4766):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4766): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@225c1eb0 added. We now have 1 listener(s)
D/BluetoothManagerService(  861): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4766): setBluetoothMacAddress: F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4766): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4766): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4766): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4766):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4766):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4766):     - Bluetooth MAC address: F8:95:C7:87:85:54
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4766):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4766):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4766):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4766):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4766):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4766):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4766): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29dc75dc added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4766): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4766): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4766): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 4766): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4766): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4766): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4766): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4766): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4766): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4766): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4766): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4766): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4766): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4766): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4766): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/JX-Cordova( 4766): jxcore cordova android initializing
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4766): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4766): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ef66e5 added. We now have 2 listener(s)
D/BluetoothManagerService(  861): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4766): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4766): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4766): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4766): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b66c5ba added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4766): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4766): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4766): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4766): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4766): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4766): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4766): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4766): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4766): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4766): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4766): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4766): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4766): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4766): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4766): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/BluetoothManagerService(  861): Message: 20
D/BluetoothManagerService(  861): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fc18de0:true
,D/BluetoothAdapter( 4908): 587588866: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 4908): 587588866: getState() :  mService = null. Returning STATE_OFF
V/LGMDMManager( 4908): Create singleton instance
,I/QCNEJ   ( 1837): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[SystemUI]QPairHandler( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]QSlideListController( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1370): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/InputReader(  861): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]LGPlusHomeDBManager( 1874): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/AudioManager( 4908): getMode name:com.lge.qremote
,D/UEI.SmartControl( 4804): -----IControl: 11
,D/UEI.SmartControl( 4804): Caller: com.lge.qremote
D/UEI.SmartControl( 4804): ------------ IControl registerCallback...
I/UEI.SmartControl( 4804): Registering callback...
D/UEI.SmartControl( 4804): -----IControl: 19
I/art     ( 1784): CheckpointMarkThreadRoots callback created = 0xaaf20b70
D/UEI.SmartControl( 4804): Caller: com.lge.qremote
I/UEI.SmartControl( 4804): Registering Services Ready callback...
I/UEI.SmartControl( 4804): Notify client services are ready...
I/AudioManager( 4908): getMode name:com.lge.qremote
D/UEI.SmartControl( 4804): -----IControl: 8
,D/UEI.SmartControl( 4804): Caller: com.lge.qremote
I/AudioManager( 4908): getMode name:com.lge.qremote
I/art     ( 1784): CheckpointMarkThreadRoots callback created = 0xaaf46310
I/[LGHome]Launcher( 1874): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  861): Handling package changes for user 0
I/ActivityManager(  861): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4931 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 4931): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4931): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4931): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/LGEmail ( 4931): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 4931): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,W/ResourcesManager(  861): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/ActivityManager(  861): Process com.lge.bnr (pid 4593) has died
,I/NotificationService(  861): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  861): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  861): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  861): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
,V/BackupManagerService(  861): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  861): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@e4021ef
I/art     (  861): Explicit concurrent mark sweep GC freed 24385(1235KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/34MB, paused 2.354ms total 185.397ms
,W/ResourceType(  861): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1874): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/PackageChangeReceiver( 4931): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/GCoreNlp( 1730): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/ActivityManager(  861): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4957 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,D/LocationProviderProxy(  861): applying state to connected service
,I/ActivityManager(  861): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4980 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  861): Killing 3395:com.android.defcontainer/u0a4 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_10004/pid_3395/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 4980): onCreate
,W/AppUp4:DB( 4980):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 4980):  setFingerPrint start
I/AppUp4:DB( 4980):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 4980):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4980):  SDK version = 0
I/AppUp4:DB( 4980):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 4980): AppBoxApplication onCreate()
I/ActivityManager(  861): Killing 4570:com.lge.clock/u0a10 (adj 15): empty #11
,W/libprocessgroup(  861): failed to open /acct/uid_10010/pid_4570/cgroup.procs: No such file or directory
,I/ActivityManager(  861): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5000 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 5000): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5000): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5000): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 5000): Total System Memory = 906309632
,I/GalleryUtils( 5000): Application Heap = 96 MB
I/AppConfig( 5000): App Tier : NOT_DEF
D/SystemHelper( 5000): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  861): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5019 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  861): Killing 4684:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  861): failed to open /acct/uid_10014/pid_4684/cgroup.procs: No such file or directory
,W/ResourcesManager( 5019): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5019): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5019): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5019): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5019): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 5019): BUILD Country: EU
I/SystemConfig( 5019): BUILD Operator: OPEN
,I/ActivityManager(  861): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5038 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  861): Killing 4722:com.google.android.gm/u0a53 (adj 15): empty #11
I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 308us total 22.359ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 25.053ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.566ms
,W/libprocessgroup(  861): failed to open /acct/uid_10053/pid_4722/cgroup.procs: No such file or directory
,I/SystemConfig( 5019): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5019): existFile = false
I/SystemConfig( 5019): canReadFile = false
I/SystemConfig( 5019): systemFeature RCS result false
D/SystemConfig( 5019): refreshRcsSupport() :false
I/LockScreenSettings( 5038): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 5038): New app installed broadcast received ..
,I/LockScreenSettings( 5038): Number of installed packages  1
I/ActivityManager(  861): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5055 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  861): Killing 4823:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_10061/pid_4823/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 5055): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5055): uri : package:com.test.thalitest
,I/ActivityManager(  861): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5072 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  861): Killing 4885:com.google.android.setupwizard/u0a38 (adj 15): empty #11
D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 73378023621; DSPS: 2502789; Offset : -3007800136
,W/libprocessgroup(  861): failed to open /acct/uid_10038/pid_4885/cgroup.procs: No such file or directory
,D/[BNRAppListMgrReceiver]( 5072): android.intent.action.PACKAGE_ADDED : com.test.thalitest
,W/MainApplication( 5072): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  861): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5090 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  861): Killing 4804:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 4908): android.os.DeadObjectException
,W/System.err( 4908): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4908): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4908): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 4908): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 4908): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4908): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4908): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4908): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4908): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4908): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4908): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4908): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4908): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 4908): android.os.DeadObjectException
W/System.err( 4908): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4908): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4908): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 4908): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 4908): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4908): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4908): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4908): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4908): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4908): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4908): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4908): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4908): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4908): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4908): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  861): failed to open /acct/uid_10089/pid_4804/cgroup.procs: No such file or directory
,W/ActivityManager(  861): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  861): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5107 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 5107): Quickset Services start...
,I/UEI.SmartControl( 5107): Manufacture = LGE
D/UEI.SmartControl( 5107): File observer start...
E/UEI.SmartControl( 5107): IR Port is disabled: false
D/UEI.SmartControl( 5107): Starting file observer...
D/UEI.SmartControl( 5107): Extracting JNI libs...
D/UEI.SmartControl( 5107): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 5107): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5107): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5107): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 5107): --- Selecting new region: 2
,I/UEI.SmartControl( 5107): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5107): Platform has CIR...
D/UEI.SmartControl( 5107): NO CIR support, need to check package...
I/UEI.SmartControl( 5107): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5107): QS Service created
E/UEI.SmartControl( 5107): QS start get config
,D/Finsky  ( 5090): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 5107): Loading JNI Libs...
D/UEI.SmartControl( 5107):  configuring local db...
,D/Finsky  ( 5090): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 5090): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5090): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5090): com.android.vending: cancel(-1050172287) by com.android.vending
D/UEI.SmartControl( 5107):  ---- Has DB8: true
,D/UEI.SmartControl( 5107): QS start statue = true Error code = 0
D/UEI.SmartControl( 5107): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5107): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5107): IRRCDataComm has AudioManager!!!!.
,V/DownloadManager( 3131): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 5090): com.android.vending: cancel(1003285959) by com.android.vending
V/DownloadManager( 3131): created cursor android.database.sqlite.SQLiteCursor@e7538d6 on behalf of 5090
W/irrc_jni( 5107): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5107): IrrcClient ++ 
D/irrcClient( 5107): getIrrcService ++ 
D/irrcClient( 5107): getIrrcService -- 
D/irrcClient( 5107): IrrcClient -- 
W/irrc_jni( 5107): IRRCPlayer_nativeInit -- 
D/Ads     ( 5090): Skipping gmscore version check
,D/UEI.SmartControl( 5107): Services init done
I/UEI.SmartControl( 5107): Device manager: loading config....
D/UEI.SmartControl( 5107): Config is loaded...
I/ActivityManager(  861): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5163 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 5107): QS Service init finished
D/Finsky  ( 5090): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5090): [1] Libraries$2.run: Finished loading 1 libraries.
D/UEI.SmartControl( 5107): QS Service version name: 0.1.73
D/UEI.SmartControl( 5107):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 5107): QS Service version code: 1073
I/UEI.SmartControl( 5107): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 5107): Service requested: Control
I/ActivityManager(  861): Killing 4908:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 5107): -----IControl: 11
D/UEI.SmartControl( 5107): Caller: com.lge.qremote
D/UEI.SmartControl( 5107): ------------ IControl registerCallback...
I/UEI.SmartControl( 5107): Registering callback...
D/Finsky  ( 5090): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/UEI.SmartControl( 5107): Internal service binding...
,W/libprocessgroup(  861): failed to open /acct/uid_10106/pid_4908/cgroup.procs: No such file or directory
D/Finsky  ( 5090): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  861): Killing 4931:com.lge.email/u0a21 (adj 15): empty #11
,D/Finsky  ( 5090): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
W/libprocessgroup(  861): failed to open /acct/uid_10021/pid_4931/cgroup.procs: No such file or directory
,I/ActivityManager(  861): Killing 4957:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/libprocessgroup(  861): failed to open /acct/uid_10009/pid_4957/cgroup.procs: No such file or directory
,I/GAv4    ( 5163): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5163):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5163):   adb logcat -s GAv4
,W/GAv4    ( 5163): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5163): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5163): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5163): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,V/AlarmManager(  861): RTC_WAKEUP set : Alarm{2b3b8e24 type 0 when 1457487470947 com.android.vending} when 1457487470947
,D/Finsky  ( 5090): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5163): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
I/ActivityManager(  861): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5205 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/art     ( 5163): CheckpointMarkThreadRoots callback created = 0xaaedd220
,W/ResourcesManager( 5163): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5163): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  861): android: cancelAsUser(2) by android
,I/art     ( 5163): CheckpointMarkThreadRoots callback created = 0xb0512a60
,I/NotificationManager( 5163): com.google.android.apps.docs: cancel(10436) by com.google.android.apps.docs
,W/ResourcesManager( 5205): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 5163): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/libc-netbsd( 5090): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5090): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5090): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5090): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  861): DNSproblemNotiEnabled is disabled ignore DNS fail CB
W/Finsky  ( 5090): [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  861): android: cancelAsUser(2) by android
,D/libc-netbsd( 5090): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5090): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/System  ( 5163): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5163): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  861): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=5240 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  861): android: cancelAsUser(2) by android
,D/libc-netbsd( 5090): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5090): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/Finsky  ( 5090): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
W/ResourcesManager( 5240): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5240): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5240): VM with version 2.1.0 has multidex support
I/MultiDex( 5240): install
I/MultiDex( 5240): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5240): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5240): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5240): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@7a913c8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5240): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5240): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5240): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 5240): Reading stored module config
,D/ChimeraCfgMgr( 5240): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/chromium( 4766): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
I/chromium( 4766): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
D/ChimeraCfgMgr( 4122): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/PackageBroadcastService( 4122): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraModuleLdr( 4122): Loading module APK com.google.android.play.games
,D/CAR.SERVICE( 5240): Connecting to CarCallService...
,I/UpdateIcingCorporaServi( 1935): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/art     ( 5240): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5240): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 5240): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 5240): com.google.android.projection.gearhead isn't installed.
,I/UpdateIcingCorporaServi( 1935): UpdateCorporaTask done [took 111 ms] updated apps [took 111 ms] 
,I/art     (  861): Explicit concurrent mark sweep GC freed 25317(1333KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 2.140ms total 149.239ms
,D/CAR.TEL.Service( 5240): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 5240): Creating a new PhoneAdapter instance
W/ActivityManager(  861): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5240): setListener: com.google.android.gms.car.dn@aa8d37
W/ActivityManager(  861): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 5240): Returning an existing PhoneAdapter instance.
,D/CAR.TEL.Service( 5240): Starting CarCallService with initial phone null
I/NotificationManager( 5240): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/ChimeraCfgMgr( 4122): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4122): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4122): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 4122): Submit a task: k
,I/Icing   ( 4122): Storage manager: low false usage 1.71MB avail 2.37GB capacity 4.06GB
D/ChimeraCfgMgr( 4122): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/CAR.SERVICE( 5240): Package validated; name: com.android.vending
D/ChimeraCfgMgr( 4122): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 4122): Processing package: com.test.thalitest
I/NotificationManager( 5090): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5090): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/GassUtils( 4122): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 4122): Found info for package com.test.thalitest in db.
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  861): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ActivityManager(  861): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5294 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/BaseAppContext( 4122): Using Auth Proxy for data requests.
W/BaseAppContext( 4122): Using Auth Proxy for data requests.
,W/BaseAppContext( 4122): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 4122): cleanUpNonGplusAccounts done.
W/BaseAppContext( 4122): Using Auth Proxy for data requests.
W/BaseAppContext( 4122): Using Auth Proxy for data requests.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  861): android: cancelAsUser(2) by android
I/ActivityManager(  861): Process com.android.contacts (pid 5019) has died
,W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/libc-netbsd( 5090): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5090): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/Finsky  ( 5090): [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.NoConnectionError: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
D/Finsky  ( 5090): [1] DailyHygiene.access$600: Logging device features
V/AlarmManager(  861): RTC_WAKEUP set : Alarm{18af85bd type 0 when 1457487472495 com.android.vending} when 1457487472495
,D/Finsky  ( 5090): [1] DailyHygiene.reschedule: Giving up. (failures=6)
D/DeviceConnectionService( 1730): client connected with version: 8296000
D/WearableService( 1730): callingUid 10006, callindPid: 1730
,I/Gmail   ( 5294): getAccountsCursor
,D/Finsky  ( 5090): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5090): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 5294): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  861): Killing 4980:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/Icing   ( 4122): updateResources: need to parse f{com.google.android.gms}
W/libprocessgroup(  861): failed to open /acct/uid_10011/pid_4980/cgroup.procs: No such file or directory
,W/ActivityManager(  861): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 5294): Observing account changes for notifications
W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5294): getAccountsCursor
,E/Gmail   ( 5294): Error finding the version of the Email provider.....
E/Gmail   ( 5294): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5294): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5294): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5294): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5294): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5294): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5294): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5294): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5294): We do not support migrating this version of the Email provider.
I/ActivityManager(  861): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5333 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  861): Killing 5000:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_10023/pid_5000/cgroup.procs: No such file or directory
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 5333): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/Icing   ( 4122): Internal init done: storage state 0
,I/Icing   ( 4122): Post-init done
,D/BluetoothManagerService(  861): Message: 20
D/BluetoothManagerService(  861): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3206a69d:true
,D/BluetoothAdapter( 5333): 587588866: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 5333): 587588866: getState() :  mService = null. Returning STATE_OFF
,I/Gmail   ( 5294): notifyAccountChanged
I/Gmail   ( 5294): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5294): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5294): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5294): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5294): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5294): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/ChimeraCfgMgr( 4122): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4122): Module APK com.google.android.play.games already loaded
,V/LGMDMManager( 5333): Create singleton instance
I/AudioManager( 5333): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5107): -----IControl: 11
D/UEI.SmartControl( 5107): Caller: com.lge.qremote
D/UEI.SmartControl( 5107): ------------ IControl registerCallback...
I/UEI.SmartControl( 5107): Registering callback...
D/UEI.SmartControl( 5107): -----IControl: 19
D/UEI.SmartControl( 5107): Caller: com.lge.qremote
I/UEI.SmartControl( 5107): Registering Services Ready callback...
I/UEI.SmartControl( 5107): Notify client services are ready...
,D/UEI.SmartControl( 5107): -----IControl: 8
D/UEI.SmartControl( 5107): Caller: com.lge.qremote
I/ActivityManager(  861): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=5363 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager(  861): Killing 5038:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_10069/pid_5038/cgroup.procs: No such file or directory
,W/ResourcesManager( 5363): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5363): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5363): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5363): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5363): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5363): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5363): MmsConfig.loadFromResources
E/Babel_SMS( 5363): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5363): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 5363): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5363): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5363): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5363): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5363): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5363): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5363): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5363): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5363): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5363): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5363): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5363): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5363): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5363): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5363): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5363): found sensor: Motion Accel, handle=46
,W/art     ( 5363): Suspending all threads took: 6.430ms
,W/Settings( 5363): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5363): startup - clean
I/art     ( 5363): CheckpointMarkThreadRoots callback created = 0xb042d880
,I/art     ( 5363): CheckpointMarkThreadRoots callback created = 0xb042d860
,I/Babel   ( 5363): deleted: false for 0
,W/AudioCapabilities( 5363): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5363): Unsupported mime audio/adpcm
W/AudioCapabilities( 5363): Unsupported mime audio/g726
W/AudioCapabilities( 5363): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5363): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5363): Unsupported mime video/mjpg
I/ActivityManager(  861): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5402 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 22.616ms
,I/Icing   ( 4122): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
W/VideoCapabilities( 5363): Unsupported mime video/theora
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 22.168ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 24.456ms
W/AudioCapabilities( 5363): Unsupported mime audio/evrc
W/AudioCapabilities( 5363): Unsupported mime audio/qcelp
W/VideoCapabilities( 5363): Unrecognized profile 2130706433 for video/avc
,I/AppUp4:AppBoxCP( 5402): onCreate
W/AppUp4:DB( 5402):  [AppBoxDatabaseHelper] construct
,W/AudioCapabilities( 5363): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5363): Unsupported mime audio/qcelp
I/AppUp4:DB( 5402):  setFingerPrint start
I/AppUp4:DB( 5402):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
W/AudioCapabilities( 5363): Unsupported mime audio/evrc
I/AppUp4:DB( 5402):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5402):  SDK version = 0
I/AppUp4:DB( 5402):  beforefinger == newfinger no write in DB
,W/VideoCapabilities( 5363): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 5363): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5363): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5363): Unrecognized profile 2130706433 for video/avc
D/Icing   ( 4122): Loaded CLD2 Version V2.0 - 20141016
W/VideoCapabilities( 5363): Unrecognized profile 2130706433 for video/avc
I/Icing   ( 4122): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,W/VideoCapabilities( 5363): Unrecognized profile 2130706433 for video/avc
I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/art     (  861): Explicit concurrent mark sweep GC freed 14247(639KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/33MB, paused 2.268ms total 134.966ms
,D/AppUp4:AppBoxApplication( 5402): AppBoxApplication onCreate()
I/ActivityManager(  861): Killing 5055:com.lge.eula/1000 (adj 15): empty #11
,I/AppUp4:CustModeStarterReceiver( 5402): onReceive
I/AppUp4:CustModeStarterReceiver( 5402): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 5402): Context : android.app.ReceiverRestrictedContext@2d765a38
D/AppUp4:CustFacade( 5402): isCustomizationCompleted : false
W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_5055/cgroup.procs: No such file or directory
,D/AppUp4:CustFacade( 5402): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 5402): begin check event
I/AppUp4:CustModeStarterReceiver( 5402): Event For Nothing, skip.
I/ActivityManager(  861): Killing 5072:com.lge.bnr/1000 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_1000/pid_5072/cgroup.procs: No such file or directory
,I/vclib   ( 5363): onServiceConnected
W/Babel   ( 5363): Attempted to change video mute state without an active call.
I/NotificationManager( 5363): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 5363): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5363): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  861): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5433 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,V/JNIHelp ( 5363): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 5433): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5433): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5433): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,W/System  ( 5363): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5363): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5363): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AppConfig( 5433): Total System Memory = 906309632
,I/GalleryUtils( 5433): Application Heap = 96 MB
I/AppConfig( 5433): App Tier : NOT_DEF
D/SystemHelper( 5433): region [EU], country [EU], operator [OPEN], sub-operator []
I/NotificationManager( 5363): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager(  861): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5455 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  861): Killing 5163:com.google.android.apps.docs/u0a58 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_10058/pid_5163/cgroup.procs: No such file or directory
,E/Babel_NetworkQueue( 5363): Retried: 20 errorCode: 101 Request: crq-285097910: devices/registerdevice created: 1457427900397
I/Babel   ( 5363): connection state changed from UNKNOWN to DISCONNECTED
,W/ResourcesManager( 5455): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5455): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5455): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5455): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,W/ResourcesManager( 5455): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ActivityManager(  861): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager(  861): RTC_WAKEUP set : Alarm{20e951ca type 0 when 1457314629019 com.android.providers.contacts} when 1457314629019
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{267f8f3b type 2 when 57247 com.google.android.talk} when 57247
I/NotificationManager( 1935): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/SystemConfig( 5455): BUILD Country: EU
I/SystemConfig( 5455): BUILD Operator: OPEN
,D/UEI.SmartControl( 5107): Internal timer expired: 1
,I/ActivityManager(  861): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5478 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  861): Killing 5205:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  861): failed to open /acct/uid_10086/pid_5205/cgroup.procs: No such file or directory
,I/SystemConfig( 5455): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5455): existFile = false
I/SystemConfig( 5455): canReadFile = false
I/SystemConfig( 5455): systemFeature RCS result false
D/SystemConfig( 5455): refreshRcsSupport() :false
I/LockScreenSettings( 5478): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 5478): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5478): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5478): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5478): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,D/LockScreenSettings( 5478): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  861): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5495 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  861): Killing 4122:com.google.android.gms/u0a6 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_10006/pid_4122/cgroup.procs: No such file or directory
,W/ResourcesManager( 5495): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1935): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  861): Start proc com.google.android.gms for service com.google.android.gms/.app.service.PackageBroadcastService: pid=5523 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/AudioManager( 5333): getMode name:com.lge.qremote
,I/UpdateIcingCorporaServi( 1935): UpdateCorporaTask done [took 116 ms] updated apps [took 116 ms] 
,I/AudioManager( 5333): getMode name:com.lge.qremote
,I/AudioManager( 5333): getMode name:com.lge.qremote
I/AudioManager( 5333): getMode name:com.lge.qremote
,I/ActivityManager(  861): Killing 5294:com.google.android.gm/u0a53 (adj 15): empty #11
W/ResourcesManager( 5523): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5523): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 5523): VM with version 2.1.0 has multidex support
I/MultiDex( 5523): install
I/MultiDex( 5523): VM has multidex support, MultiDex support library is disabled.
,W/libprocessgroup(  861): failed to open /acct/uid_10053/pid_5294/cgroup.procs: No such file or directory
,V/JNIHelp ( 5523): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5523): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5523): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@172dfa0e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5523): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5523): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5523): com.google.android.gms: cancel(39789) by com.google.android.gms
D/PackageBroadcastService( 5523): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,E/MDM     ( 1730): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/PackageBroadcastService( 5523): Null package name or gms related package.  Ignoreing.
D/LocationInitializer( 5523): Restart initialization of location
,D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/art     ( 5523): Suspending all threads took: 17.416ms
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 30705(2MB) AllocSpace objects, 35(560KB) LOS objects, 40% free, 13MB/22MB, paused 1.274ms total 86.123ms
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,I/art     ( 5523): Background sticky concurrent mark sweep GC freed 26383(1377KB) AllocSpace objects, 4(64KB) LOS objects, 9% free, 10MB/11MB, paused 21.749ms total 109.686ms
,D/NativeLibraryUtils( 5523): Install completed successfully. count=14 extracted=0
,I/art     ( 5523): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5523): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/ActivityManager(  861): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5575 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 5523): CheckpointMarkThreadRoots callback created = 0xaaef61c0
I/Icing   ( 5523): Storage manager: low false usage 1.71MB avail 2.37GB capacity 4.06GB
I/art     ( 5523): CheckpointMarkThreadRoots callback created = 0xaaef61b0
W/art     ( 5523): Suspending all threads took: 9.155ms
W/IcingInternalCorpora( 5523): getNumBytesRead when not calculated.
I/art     ( 5523): Background partial concurrent mark sweep GC freed 5166(522KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 11MB/18MB, paused 17.644ms total 94.947ms
W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
I/Gmail   ( 5575): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5575): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/Finsky  ( 5090): [594] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
E/Gmail   ( 5575): Error finding the version of the Email provider.....
E/Gmail   ( 5575): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5575): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5575): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5575): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5575): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5575): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5575): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5575): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5575): We do not support migrating this version of the Email provider.
I/Gmail   ( 5575): getAccountsCursor
W/ActivityManager(  861): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  861): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5575): Observing account changes for notifications
I/AudioManager( 5333): getMode name:com.lge.qremote
I/AudioManager( 5333): getMode name:com.lge.qremote
I/AudioManager( 5333): getMode name:com.lge.qremote
I/AudioManager( 5333): getMode name:com.lge.qremote
E/MDM     ( 1730): [103] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 5523): Restart initialization of location
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/Icing   ( 5523): updateResources: need to parse f{com.google.android.gms}
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
I/AudioManager( 5333): getMode name:com.lge.qremote
I/AudioManager( 5333): getMode name:com.lge.qremote
E/PhoneInterfaceManager( 1749): [PhoneIntfMgr] getIccId: ICC ID is null or empty.
W/VideoCapabilities( 5363): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5363): Unrecognized profile 2130706433 for video/avc
I/art     (  861): Explicit concurrent mark sweep GC freed 18302(882KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 1.765ms total 189.625ms
W/VideoCapabilities( 5363): Unrecognized profile 2130706433 for video/avc
I/NotificationManager(  861): android: cancelAsUser(2) by android
D/libc-netbsd( 5090): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5090): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5090): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5090): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  861): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ActivityManager(  861): Killing 5402:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/Gmail   ( 5575): notifyAccountChanged
,I/Gmail   ( 5575): getAccountsCursor
I/Gmail   ( 5575): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5575): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5575): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5575): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/libprocessgroup(  861): failed to open /acct/uid_10011/pid_5402/cgroup.procs: No such file or directory
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 5523): Internal init done: storage state 0
,I/NotificationManager( 5523): com.google.android.gms: cancel(10436) by com.google.android.gms
I/Icing   ( 5523): Post-init done
,I/Icing   ( 5523): updateResources: need to parse f{com.google.android.gms}
I/Gmail   ( 5575): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CAR.SERVICE( 5240): mConnectedToCar = false, abort
,E/ActivityThread( 5240): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@29a1353f that was originally bound here
E/ActivityThread( 5240): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@29a1353f that was originally bound here
E/ActivityThread( 5240): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5240): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5240): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5240): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5240): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5240): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5240): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5240): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5240): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5240): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 5240): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 5240): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 5240): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 5240): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5240): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5240): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5240): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5240): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5240): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5240): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5240): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5240): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5240): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 5240): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3e21da36 that was originally bound here
E/ActivityThread( 5240): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3e21da36 that was originally bound here
E/ActivityThread( 5240): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5240): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5240): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5240): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5240): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5240): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 5240): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 5240): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 5240): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 5240): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 5240): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 5240): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 5240): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 5240): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 5240): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 5240): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5240): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5240): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5240): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5240): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5240): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5240): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  861): Unbind failed: could not find connection for android.os.BinderProxy@9bb8cc7
D/InitAlarmsService( 3625): Clearing and rescheduling alarms.
,I/ActivityManager(  861): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5653 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5653): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5653): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@bd0995
,D/CalendarProvider2( 5653): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5653): Created com.android.providers.calendar.CalendarAlarmManager@331cc776(com.android.providers.calendar.CalendarProvider2@bd0995)
D/CalendarProvider2( 5653): Scheduling check of next Alarm
D/CalendarProvider2( 5653): SCHEDULE_ALARM_REMOVE
,I/ActivityManager(  861): Killing 3625:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_10013/pid_3625/cgroup.procs: No such file or directory
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX,
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  478): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/WifiController(  861): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
D/WifiController(  861): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/Icing   ( 5523): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 5523): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 5523): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/CalendarProvider2( 5653): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5653): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  861): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5695 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  861): Killing 5433:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  861): failed to open /acct/uid_10023/pid_5433/cgroup.procs: No such file or directory
,W/ResourcesManager( 5695): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 5695): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 5695): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 5695): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@1372a69b, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@2d765a38, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2a31aa11, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@331cc776, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@34b1177, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3f52e1e4, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1175d64d, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@2305e502, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@16d54e13, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2c4e3850, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@10568a49, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@10714f4e, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2abcb86f, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@766897c, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@36748205, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@417125a, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@11066c8b, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3350c168, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@32c03981, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2823fa26, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@2ced4667, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@7248c14, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@18b5ecbd, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@ac592b2, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@307de203, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@11c85580, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@3d5997b9, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@3d7627fe, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@17f29b5f, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@281d49ac, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@27f2f675, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1d08c60a, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@3ecf8e7b, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@29eb5498, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@128984f1, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@e7538d6, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2abe9757, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@298d2244, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@36207f2d, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3c640c62, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@282b51f3, lg_preferences_r,ecent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@225c
,D/GeneralPreferenceUtils( 5695): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 5695): [init]
I/Config  ( 5695): LGCalendar ver.4.40.17
,I/Config  ( 5695): start check model
I/Config  ( 5695): start check native_ca
I/Config  ( 5695): Config Operator=OPEN, Country=EU
D/Config  ( 5695): [setDefaultValuesToPref]
D/Config  ( 5695): [parseProfiles]
D/ProfilesParser( 5695): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 5695): [debug_displayParseInfos] profile.operator = null
D/Config  ( 5695): [updateProfiletoCountryInfo]
D/GeneralPreference( 5695): [checkAndMigrateOldPreference]
D/AlertReceiver( 5695): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/InitNotificationRingtoneService( 5695): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 5695): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 5695): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 5695): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
,I/AlertUtils( 5695): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 5695): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 5695): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 5695): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 5695): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 5695): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 5695): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 5695): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 5695): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 5695): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 5695): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 5695): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 5695): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 5695): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 5695): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,I/AlertUtils( 5695): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 5695): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 5695): onHandleIntent
,D/HolidayDataLoader( 5695): readJsonAsset : holiday.json
D/AlertService( 5695): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 5695): [updateWidgets] 
,D/MonthWidgetProvider( 5695): [onReceive]
D/CalendarWidgetProvider( 5695): [onReceive]
D/CalendarWidgetProvider( 5695): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 5695): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 5695): [onReceive]
D/CalendarWidgetProvider( 5695): [onReceive]
D/CalendarWidgetProvider( 5695): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 5695): [onCreate] mContext.getPackageName() = com.android.calendar
E/HolidayIntentService( 5695): onHandleIntent:holiday data empty
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  861): acquireWakeLockInternal: lock=948209927, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=861
,D/WeatherService( 2574): 2 : TimeTick Intent has been received, Time(hour:min:sec) 2:38:0
,D/WeatherService( 2574): 2 : TimeTick Intent And Screen On
D/WeatherService( 2574): 2 : SDK version : 21
W/ActivityManager(  861): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2574): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2574): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2574): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2574): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 2574): 2 : This is isUpdating : false
D/WeatherService( 2574): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2574): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2574): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
D/WeatherTheme( 2574): 2 : Fixed theme : optimus
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/WeatherReflect( 2574): 2 : Map key string is -2
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/lim     ( 2574): 2 : time = 02:38
,D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/WeatherReflect( 2574): Model Name : LG-D722
D/WeatherTheme( 2574): 2 : Different view - status_min_formatted : 37 != 38
D/WeatherTheme( 2574): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2574): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2574): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2574): currentPackage=com.lge.sizechangable.weather.theme.optimus
,D/Weather4x2_optimus( 2574): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2574): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2574): forecast size is 0
D/Theme   ( 2574): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2574): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2574): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2574): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2574): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2574): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2574): setTouchIntent, appWidgetId: 2
,D/Theme_WeatherAncestor_optimus( 2574): url is : null
D/Theme   ( 2574): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2574): 2 : update view, appWidgetId: 2
D/WeatherService( 2574): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 2:38:0
D/PowerManagerServiceEx(  861): releaseWakeLockInternal: lock=948209927 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/GAv4-SVC( 5523): Google Analytics 8.4.89 is starting up.
,I/GAV2    ( 5575): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  861): Killing 5455:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  861): failed to open /acct/uid_10018/pid_5455/cgroup.procs: No such file or directory
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{3163348d type 2 when 86889 com.android.providers.calendar} when 86889
,D/CalendarProviderBroadcastReceiver( 5653): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5653): [IntentService] WakeLock acquire, start IntentSerivce
,D/CalendarProvider2( 5653): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 5653): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5653): [getOrCreateCalendarAlarmManager]
D/CalendarProvider2( 5653): [IntentService] Release Lock
,D/CalendarProvider2( 5653): CalendarProviderIntentService.onDestroy()
D/AlertService( 5695): Beginning updateAlertNotification
,D/AlertService( 5695): No fired or scheduled alerts
,I/NotificationManager( 5695): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5695): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5695): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5695): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5695): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5695): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5695): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5695): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5695): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5695): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5695): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5695): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 5695): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5695): com.android.calendar: cancel(13) by com.android.calendar
,I/NotificationManager( 5695): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5695): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5695): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5695): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5695): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5695): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5695): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 5695): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 5695): No events found starting within 1 week.
,D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  861): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ActivityManager(  861): Killing 5478:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  861): failed to open /acct/uid_10069/pid_5478/cgroup.procs: No such file or directory
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  861): Killing 5495:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  861): failed to open /acct/uid_10086/pid_5495/cgroup.procs: No such file or directory
,V/AlarmManager(  861): RTC_WAKEUP set : Alarm{1598db90 type 0 when 1457487487103 com.android.vending} when 1457487487103
D/Finsky  ( 5090): [585] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5090): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 93379521649; DSPS: 3158198; Offset : -3007796974
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{265b8c89 type 2 when 98252 com.google.android.gms} when 98252
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  861): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/rmt_storage(  278): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  278): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  278): wakelock acquired: 1, error no: 42
,I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  278): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  278): 
I/rmt_storage(  278): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
W/ContextImpl( 3415): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/ThermalEngine(  296): Sensor:pa_therm0:31000 mC
,I/MusicWidget( 2539): mDelayedStopHandler : unbind
,I/MusicBrowser( 2601): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2601): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2601): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2601): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2601): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2601): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2601): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2601): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  861):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@7248c14com.lge.music.MediaPlaybackService$6@18b5ecbd
,D/MusicBrowser( 2601): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2601): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2601): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2601): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2601): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@16d54e13
I/MusicBrowser( 2601): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2601): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2601): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2601): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2601): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2601): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2601): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2601): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2601): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2601): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2601): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2601): [MediaPlaybackService.java:6745:release()] oooooo 
,I/MusicBrowser( 2601): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2601): reset
V/MediaPlayer[Native]( 2601): setListener
,V/MediaPlayer[Native]( 2601): disconnect
V/MediaPlayer[Native]( 2601): destructor
V/AudioFlinger(  285): releasing 19 from 2601 for -1
V/AudioFlinger(  285):  decremented refcount to 0
V/AudioFlinger(  285): purging stale effects
V/MediaPlayer[Native]( 2601): disconnect
D/MusicBrowser( 2601): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2601): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2601): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2601): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2601): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2601): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2601): [SmartShareManagerClient] unregisterListener: 180720306
W/SmartShareClient( 2601): [SmartShareManagerClient] unregisterListener invalid listener: 180720306
I/SmartShareClient( 2601): [SmartShareManagerClient] terminate service: 2601/MediaPlaybackService/707897873
E/HomeCloudIF( 2601): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2601): [SmartShareManagerClient] unbindService context:android.app.Application@307de203
V/CloudHub( 2601): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2601): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2601): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2601): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2601): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  861): Killing 5240:com.google.android.gms:car/u0a6 (adj 15): empty #11
I/CloudHub( 2601): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29984
,W/libprocessgroup(  861): failed to open /acct/uid_10006/pid_5240/cgroup.procs: No such file or directory
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 113381863821; DSPS: 3813635; Offset : -3007804995
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/CloudHub( 2601): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19943
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 133384186831; DSPS: 4469071; Offset : -3007801295
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{34c2c48e type 2 when 141850 com.google.android.gms} when 141850
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  861): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/CloudHub( 2601): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
I/CloudHub( 2601): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  861): acquireWakeLockInternal: lock=948209927, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=861
,D/WeatherService( 2574): 2 : TimeTick Intent has been received, Time(hour:min:sec) 2:39:0
D/WeatherService( 2574): 2 : TimeTick Intent And Screen On
D/WeatherService( 2574): 2 : SDK version : 21
W/ActivityManager(  861): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2574): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2574): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2574): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2574): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2574): 2 : This is isUpdating : false
D/WeatherService( 2574): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2574): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2574): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2574): 2 : Fixed theme : optimus
D/WeatherReflect( 2574): 2 : Map key string is -2
,D/lim     ( 2574): 2 : time = 02:39
I/WeatherReflect( 2574): Model Name : LG-D722
D/WeatherTheme( 2574): 2 : Different view - status_min_formatted : 38 != 39
D/WeatherTheme( 2574): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2574): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2574): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2574): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
D/Weather4x2_optimus( 2574): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2574): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2574): forecast size is 0
D/Theme   ( 2574): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2574): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2574): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2574): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2574): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2574): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2574): setTouchIntent, appWidgetId: 2
,D/Theme_WeatherAncestor_optimus( 2574): url is : null
D/Theme   ( 2574): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2574): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2574): 2 : update view, appWidgetId: 2
,D/WeatherService( 2574): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 2:39:0
D/PowerManagerServiceEx(  861): releaseWakeLockInternal: lock=948209927 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1874): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/PowerManagerService(  861): ALS enabled for SRE
,D/PowerManagerServiceEx(  861): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26711 ms ago)
D/qdlights(  861): set_light_backlight: 252
,D/qdlights(  861): set_light_backlight: 248
,D/qdlights(  861): set_light_backlight: 245
,D/qdlights(  861): set_light_backlight: 242
,D/qdlights(  861): set_light_backlight: 238
,D/qdlights(  861): set_light_backlight: 235
,D/qdlights(  861): set_light_backlight: 232
,D/qdlights(  861): set_light_backlight: 228
,D/qdlights(  861): set_light_backlight: 225
,D/qdlights(  861): set_light_backlight: 222
,D/qdlights(  861): set_light_backlight: 218
,D/qdlights(  861): set_light_backlight: 215
,D/qdlights(  861): set_light_backlight: 212
,D/qdlights(  861): set_light_backlight: 208
,D/qdlights(  861): set_light_backlight: 205
,D/qdlights(  861): set_light_backlight: 202
,D/qdlights(  861): set_light_backlight: 198
,D/qdlights(  861): set_light_backlight: 195
,D/qdlights(  861): set_light_backlight: 192
,D/qdlights(  861): set_light_backlight: 188
,D/qdlights(  861): set_light_backlight: 185
,D/qdlights(  861): set_light_backlight: 182
,D/qdlights(  861): set_light_backlight: 178
,D/qdlights(  861): set_light_backlight: 175
,D/qdlights(  861): set_light_backlight: 172
,D/qdlights(  861): set_light_backlight: 168
,D/qdlights(  861): set_light_backlight: 165
,D/qdlights(  861): set_light_backlight: 162
,D/qdlights(  861): set_light_backlight: 158
,D/qdlights(  861): set_light_backlight: 155
,D/qdlights(  861): set_light_backlight: 152
,D/qdlights(  861): set_light_backlight: 148
,D/qdlights(  861): set_light_backlight: 145
,D/qdlights(  861): set_light_backlight: 142
,D/qdlights(  861): set_light_backlight: 138
,D/qdlights(  861): set_light_backlight: 135
,D/qdlights(  861): set_light_backlight: 132
,D/qdlights(  861): set_light_backlight: 128
,D/qdlights(  861): set_light_backlight: 125
,D/qdlights(  861): set_light_backlight: 122
,D/qdlights(  861): set_light_backlight: 118
,D/qdlights(  861): set_light_backlight: 115
,D/qdlights(  861): set_light_backlight: 112
,D/qdlights(  861): set_light_backlight: 108
,D/qdlights(  861): set_light_backlight: 105
,D/qdlights(  861): set_light_backlight: 102
,D/qdlights(  861): set_light_backlight: 98
,D/qdlights(  861): set_light_backlight: 95
,D/qdlights(  861): set_light_backlight: 92
,D/qdlights(  861): set_light_backlight: 88
,D/qdlights(  861): set_light_backlight: 85
,D/qdlights(  861): set_light_backlight: 82
,D/qdlights(  861): set_light_backlight: 78
,D/qdlights(  861): set_light_backlight: 75
,D/qdlights(  861): set_light_backlight: 72
,D/qdlights(  861): set_light_backlight: 68
,D/qdlights(  861): set_light_backlight: 65
,D/qdlights(  861): set_light_backlight: 62
,D/qdlights(  861): set_light_backlight: 58
,D/qdlights(  861): set_light_backlight: 55
,D/qdlights(  861): set_light_backlight: 52
,D/qdlights(  861): set_light_backlight: 48
,D/qdlights(  861): set_light_backlight: 45
,D/qdlights(  861): set_light_backlight: 42
,D/qdlights(  861): set_light_backlight: 38
,D/qdlights(  861): set_light_backlight: 35
,D/qdlights(  861): set_light_backlight: 32
,D/qdlights(  861): set_light_backlight: 28
,D/qdlights(  861): set_light_backlight: 25
,D/qdlights(  861): set_light_backlight: 22
,D/qdlights(  861): set_light_backlight: 18
,D/qdlights(  861): set_light_backlight: 15
,D/qdlights(  861): set_light_backlight: 12
,D/qdlights(  861): set_light_backlight: 10
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{22a524af type 2 when 130473 com.google.android.gms} when 130473
,D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
,D/DSQN    (  861): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 153386494970; DSPS: 5124503; Offset : -3007690449
,I/PowerManagerService(  861): ALS enabled for SRE
D/PowerManagerServiceEx(  861): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33707 ms ago)
I/PowerManagerService(  861): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  861): ALS enabled for SRE
D/PowerManagerServiceEx(  861): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33723 ms ago)
,W/ContextImpl(  861): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
I/PowerManagerService(  861): Sleeping (uid 1000)...
D/LPWGController(  861): [updateScreenState] screen on = false
,D/LPWGController(  861): disable proximity sensor
D/LPWGController(  861): enable proximity sensor
I/SensorManager(  861): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@1fd820bc] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  861): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  861): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  861): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  861): activate: handle is 48, enable
V/sensors_hal_Ctx(  861): activate sensors is 1400000000000
,D/sensors_hal_Thresh(  861): enable: handle=48
I/sensors_hal_SAM(  861): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  861): waitForResponse: timeout=1000
V/sensors_hal_SAM(  861): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  861): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  861): enable: Received response: 0
D/PowerManagerServiceEx(  861): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33769 ms ago)
I/Adreno-EGL(  861): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  861): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  861): Build Date: 03/02/15 Mon
I/Adreno-EGL(  861): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  861): Remote Branch: 
I/Adreno-EGL(  861): Local Patches: 
I/Adreno-EGL(  861): Reconstruct Branch: 
,D/PermissionCache(  247): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (146 us)
,I/Sensors (  411): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  861): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  861): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  861): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  861): processInd: handle 48, count=1
V/sensors_hal_Thresh(  861): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  861): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  861): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  861): poll: count: 256
I/sensors_hal_Ctx(  861): poll: released wakelock sensor_ind
D/sensors_hal_Util(  861): waitForResponse: timeout=0
D/LPWGController(  861): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
,I/LPWGController(  861): current mode = 1  value = 1 1
I/LPWGController(  861): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  861): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  861): set_light_backlight: 0
,I/SensorManager(  861): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  861): activate: handle is 46, disable
V/sensors_hal_Ctx(  861): activate sensors is 1000000000000
D/sensors_hal_LP2(  861): enable: handle=46
D/sensors_hal_LP2(  861): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  861): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  247): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  247): hwc_blank: Blanking display: 0
I/DisplayManagerService(  861): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  861): Display changed displayId=0
,V/sensors_hal_SAM(  861): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  861): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1749): Display #0 changed.
,D/qdhwcomposer(  247): hwc_blank: Done blanking display: 0
D/SurfaceControl(  861): Excessive delay in setPowerMode(): 238ms
,I/qdhwcomposer(  247): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  861): Got set_interactive hint
D/KeyguardViewMediator( 1370): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1326): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1370): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1326): notifyScreenOffLocked
D/SmartCoverViewMediator( 1326): handleNotifyScreenOFF
D/KeyguardViewMediator( 1370): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/WifiServerServiceExt(  861): sendKtScanInterval  mRtspPlay : false
,V/AudioFlinger(  285): setParameters(): io 0, keyvalue screen_state=on, calling pid 861
D/KeyguardViewMediator( 1370): handleNotifyScreenOff
D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=on
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
D/ScreenTurnOffBySensor( 1370): unregisterProximitySensor
,D/StatusBarWindowView( 1370): onScreenTurnedOff why = 3
,D/JX-Cordova( 4766): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4766): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4766): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32dd0c6b added. We now have 3 listener(s)
D/BluetoothManagerService(  861): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4766): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4766): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4766): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4766): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a913c8 added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4766): addListener: New listener added - the number of listeners is now 1
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4766): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4766): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4766): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4766): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4766): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4766): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4766): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4766): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4766): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4766): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4766): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4766): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4766): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4766): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4766): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/GpsLocationProvider(  861): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1837): |CORE| sendScreenState: state:true
I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1801): stopPatternFlashing()
I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): updateLightsLocked : turn off led
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1801): RESTART MSG
D/Cliptray Service( 1801): lockStatus = 0
,D/SplitWindow(  861): check instance of lgWin Window{1ea95ccb u0 SearchPanel}
,D/LNfcService( 1784): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1784): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1784): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1784): isRequireNfcCRouting() return true
D/LNfcService( 1784): isHCERoutingtoHost() return : true
D/NfcService( 1784): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): newParams.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): screenState= 3
D/NfcService( 1784): Discovery configuration equal, not updating.
,D/InputDispatcher(  861): Window went away: Window{24339462 u0 SearchPanel}
,I/[SystemUI]Clock( 1370): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1370): time changed, timezoneChanged : false
,D/Ulp_jni (  861): JNI:system_update. Event-0
,V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2574): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 2:39:11
D/WeatherService( 2574): 2 : ACTION screen on
D/WeatherService( 2574): 2 : shouldTimeTickRegistered : false
,D/Weather_cast( 2574): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2574): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 2:39:11
D/AppCleanupService( 3936): android.intent.action.SCREEN_ON
,V/AudioFlinger(  285): setParameters(): io 0, keyvalue screen_state=off, calling pid 861
,D/audio_hw_primary(  285): adev_set_parameters: enter: screen_state=off
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
I/Sensors (  411): sns_pwr.c(301):releasing wakelock
D/WifiController(  861): CMD_SCREEN_OFF 
D/WifiController(  861): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  861): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1837): |CORE| sendScreenState: state:false
,I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1801): stopPatternFlashing()
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1801): clear
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1801): updateLightsLocked : turn on led
E/LEDService( 1801): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1801): Can't handle this request of patternId:0
D/LEDHandler( 1801): RESTART MSG
D/LNfcService( 1784): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1784): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1874): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2574): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 2:39:11
D/WeatherService( 2574): 2 : ACTION screen off
D/WeatherService( 2574): 2 : TimeTick Receiver Unregister
D/WeatherService( 2574): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 2:39:11
D/AppCleanupService( 3936): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 3936): AppUsageStatsSaveTask
E/NxpNfcJni( 1784): getReconnectState = 0x0
,D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
D/LNfcService( 1784): isRequireNfcCRouting() return true
D/LNfcService( 1784): isHCERoutingtoHost() return : true
D/NfcService( 1784): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): newParams.techmask= mTechMask: 0
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): screenState= 1
E/NxpNfcJni( 1784): getReconnectState = 0x0
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{38648ca8 type 2 when 159770 com.android.systemui} when 159770
,D/KeyguardViewMediator( 1370): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1749): getCallState : 0
,D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1370): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1370): doKeyguard: not showing because lockscreen is off
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 175890658502; DSPS: 5861924; Offset : -3007829477
,I/ThermalEngine(  296): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1730): disconnect managed GoogleApiClient
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{179b43c1 type 2 when 185619 com.google.android.gms} when 185619
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{406d766 type 2 when 189065 com.google.android.gms} when 189065
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 190892736549; DSPS: 6353511; Offset : -3007796186
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 208396394363; DSPS: 6927070; Offset : -3007770121
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{b6efaa7 type 2 when 190073 android} when 190073
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{32c9cb54 type 2 when 219073 com.google.android.gms} when 219073
D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd(  861): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  861): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  281): [LG DATA] No such appUid: 1000
D/DnsProxyListener(  281): App 1000 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  861): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/VacuumService( 1730): Vacuum at: now=1457487623112 tag=VacuumService
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{9069a43 type 2 when 229045 com.google.android.gms} when 229045
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  861): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 230901622336; DSPS: 7664523; Offset : -3007821585
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 253406196727; DSPS: 8401955; Offset : -3007885891
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 273408574897; DSPS: 9057389; Offset : -3007766153
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/WifiController(  861): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 293411036024; DSPS: 9712832; Offset : -3007837802
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 308413456962; DSPS: 10204427; Offset : -3007705839
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 321551726447; DSPS: 10634948; Offset : -3007894553
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 335161546185; DSPS: 11080910; Offset : -3007754966
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/LocationManagerService(  861): remove 29a62291
,D/LocationManagerService(  861): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  861): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  861): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  861): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  861): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 348459910580; DSPS: 11516686; Offset : -3008218486
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 363476312643; DSPS: 12008731; Offset : -3007838386
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  861): android: cancelAsUser(2) by android
,D/libc-netbsd( 5090): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5090): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5090): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5090): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  861): DNSproblemNotiEnabled is disabled ignore DNS fail CB
D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 378478590091; DSPS: 12500325; Offset : -3007819318
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 393481683944; DSPS: 12991949; Offset : -3007899032
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  861): acquireWakeLockInternal: lock=948209927, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=861
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{1869e616 type 2 when 403395 com.google.android.gms} when 403395
D/PowerManagerServiceEx(  861): releaseWakeLockInternal: lock=948209927 [*alarm*], flags=0x0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  861): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 407248391743; DSPS: 13443049; Offset : -3007670830
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 429759760322; DSPS: 14180706; Offset : -3007807247
,V/AlarmManager(  861): RTC_WAKEUP set : Alarm{3435db97 type 0 when 1457487828786 com.google.android.gms} when 1457487828786
,I/EventLogService( 5523): Aggregate from 1457486028713 (log), 1457486028713 (data)
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 449762212598; DSPS: 14836148; Offset : -3007857517
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 464764113452; DSPS: 15327730; Offset : -3007848907
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 479308317902; DSPS: 15804316; Offset : -3007895025
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/WifiController(  861): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 500563955241; DSPS: 16500818; Offset : -3007811782
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 520566157058; DSPS: 17156246; Offset : -3007685264
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 534638139290; DSPS: 17617362; Offset : -3007846508
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
,D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 548709447390; DSPS: 18078450; Offset : -3007829059
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 561841663026; DSPS: 18508766; Offset : -3007813984
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 578097106064; DSPS: 19041412; Offset : -3007436708
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 591394583678; DSPS: 19477155; Offset : -3007780295
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 604848889074; DSPS: 19918030; Offset : -3007912154
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 617987218784; DSPS: 20348546; Offset : -3007888108
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 635347641585; DSPS: 20917404; Offset : -3007633739
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 650519751015; DSPS: 21414570; Offset : -3007826320
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 673023837924; DSPS: 22151983; Offset : -3007798432
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  861): android: cancelAsUser(2) by android
,D/libc-netbsd( 5090): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5090): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5090): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5090): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  861): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 689280830381; DSPS: 22684666; Offset : -3007001018
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 703982123340; DSPS: 23166420; Offset : -3007673313
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 721657571106; DSPS: 23745624; Offset : -3008129047
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 734790955122; DSPS: 24175969; Offset : -3007832139
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 748093775485; DSPS: 24611877; Offset : -3007868064
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  861): acquireWakeLockInternal: lock=948209927, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=861
,V/AlarmManager(  861): ELAPSED_WAKEUP set : Alarm{ac600c6 type 2 when 752099 com.google.android.gms} when 752099
D/PowerManagerServiceEx(  861): releaseWakeLockInternal: lock=948209927 [*alarm*], flags=0x0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  281): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  281): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  861): DNSproblemNotiEnabled is disabled ignore DNS fail CB
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 762477102319; DSPS: 25083189; Offset : -3007842219
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 782479219465; DSPS: 25738618; Offset : -3007830630
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 797481944667; DSPS: 26230218; Offset : -3007546939
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 812186813537; DSPS: 26712078; Offset : -3007878160
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 827188839933; DSPS: 27203674; Offset : -3008171178
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 840320733777; DSPS: 27633970; Offset : -3007869182
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 267
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 267
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 267, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 862823867682; DSPS: 28371359; Offset : -3008061563
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 877826408536; DSPS: 28862959; Offset : -3007962324
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 891582147091; DSPS: 29313701; Offset : -3007777917
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 266, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 910336880838; DSPS: 29928258; Offset : -3007835403
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 930339115882; DSPS: 30583691; Offset : -3007828194
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 950341682481; DSPS: 31239135; Offset : -3007824993
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 265
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 265, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 970344019301; DSPS: 31894571; Offset : -3007807561
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/art     (  861): Explicit concurrent mark sweep GC freed 44182(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 22MB/34MB, paused 3.856ms total 224.875ms
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  861): android: cancelAsUser(2) by android
,D/libc-netbsd( 5090): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5090): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5090): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5090): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  861): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 990346340721; DSPS: 32550007; Offset : -3007805452
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1010348638042; DSPS: 33205441; Offset : -3007766275
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 265
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 265, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1030350999628; DSPS: 33860878; Offset : -3007754726
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1050353424348; DSPS: 34516317; Offset : -3007740842
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1065355654140; DSPS: 35007914; Offset : -3007860903
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1080358636079; DSPS: 35499535; Offset : -3007961212
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 265
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 265, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1095360670207; DSPS: 35991119; Offset : -3007880315
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1115363199621; DSPS: 36646564; Offset : -3007944685
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1130365447892; DSPS: 37138154; Offset : -3007832803
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1145369726448; DSPS: 37629807; Offset : -3007613086
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 264
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 264
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 264, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1158513411478; DSPS: 38060506; Offset : -3007818305
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1174776523173; DSPS: 38593396; Offset : -3007218820
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1188069226326; DSPS: 39028991; Offset : -3007820080
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1205269161579; DSPS: 39592587; Offset : -3007469973
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 263
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 263
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 263, mChargingStatus=5, mChargingStop=false
D/WifiController(  861): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1219340587091; DSPS: 40053687; Offset : -3007699343
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/UsageStatsService(  861): User[0] Flushing usage stats to disk
I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1239342589165; DSPS: 40709119; Offset : -3007894951
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1252792383823; DSPS: 41149835; Offset : -3007685202
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1266863705908; DSPS: 41610925; Offset : -3007713162
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  478): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 263
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 263
,I/QCNEJ   ( 1837): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1837): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 263, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  861): battery changed pluggedType: 2
I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  861): android: cancelAsUser(2) by android
,D/libc-netbsd( 5090): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5090): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5090): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5090): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  281): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  281): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  281): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=917504
D/libc-netbsd(  281): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  281): default dns: query_ipv6=0, query_ipv4=0, netid=0
D/DSQN    (  861): DNSproblemNotiEnabled is disabled ignore DNS fail CB
I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  861): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  861): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  861): tsOffsetIs: Apps: 1280619586881; DSPS: 42061680; Offset : -3007782882
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  296): Sensor:pa_therm0:26000 mC
,TIME-OUT KILL (timeout was 1200000ms)
```
