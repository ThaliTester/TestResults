#### Test 50388019aa1a16d_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/FileApkUtils( 2325): Spent 65ms computing apk sha1.
D/FileApkUtils( 2325): Module already staged or being staged:chimera-modules/MapsModule.apk
I/art     ( 2325): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d93aca1818df11c4cd5bccf493ad94e2b544d57a@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
D/DexOptUtils( 2325): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d93aca1818df11c4cd5bccf493ad94e2b544d57a/MapsModule.apk is already optimized. Bailing.
D/FileApkUtils( 2325): Keeping up-to-date module: module-d93aca1818df11c4cd5bccf493ad94e2b544d57a
D/GmsModuleFndr( 2325): Beginning GMS chimera module scan
D/GmsModuleFndr( 2325): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 2325): Beginning module configuration check
D/ChimeraCfgMgr( 2325): Module APKs unchanged, check complete
I/art     ( 2325): Explicit concurrent mark sweep GC freed 16957(1342KB) AllocSpace objects, 24(384KB) LOS objects, 25% free, 11MB/15MB, paused 850us total 79.381ms
I/CheckinService( 2325): Checkin interval check for package: unspecified last checkin: 1448018070975 min interval config: 0 actual interval: 2118696
D/GCM     ( 2325): COMPAT: Multi user not supported
D/GCM     ( 1997): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
I/CheckinService( 2325): Disabling old GoogleServicesFramework version
I/GCoreUlr( 2325): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
D/SystemUpdateService( 2325): onCreate
I/GCoreUlr( 1764): DispatchingService.onCreate()
D/SystemUpdateService( 2325): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
V/AuthZen ( 2325): Handling intent: android.intent.action.BOOT_COMPLETED
I/SystemUpdateService( 2325): cancelUpdate (empty URL)
I/SystemUpdateService( 2325): active receiver: disabled
D/AuthZenEventHandler( 2325): Handling event: android.intent.action.BOOT_COMPLETED
I/NotificationManager( 2325): com.google.android.gms: cancel(2130838130) by com.google.android.gms
I/NotificationManager( 2325): com.google.android.gms: cancel(2130838131) by com.google.android.gms
W/BaseAppContext( 2325): Using Auth Proxy for data requests.
--------- beginning of system
V/AlarmManager(  834): ELAPSED_WAKEUP set : Alarm{2eeb63e8 type 2 when 55332 com.android.providers.calendar} when 55332
D/AndroidRuntime( 4215): 
D/AndroidRuntime( 4215): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4215): CheckJNI is OFF
D/ChimeraCfgMgr( 2325): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/CheckinService( 2325): Checking schedule, now: 1448020189970 next: 1448545319938
I/CheckinService( 2325): active receiver: disabled
I/GCoreUlr( 1764): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
I/AuthZen ( 2325): Fetching signing key...
D/SystemUpdateService( 2325): onDestroy
D/ChimeraCfgMgr( 2325): Loading module com.google.android.gms.kids from APK com.google.android.gms
I/AuthZen ( 2325): Signing key fetched successfully!
W/GCoreFlp( 1764): No location to return for getLastLocation()
W/FusedLocationProvider( 2325): location=null
W/Auth    ( 1997): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/BaseAppContext( 2325): Using Auth Proxy for data requests.
W/GCoreFlp( 1764): No location to return for getLastLocation()
W/FusedLocationProvider( 2325): location=null
V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GmsCoreStatsServiceLauncher( 2325): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
W/Kids    ( 2325): [AbstractKidsOperation] Invalid device state 3
D/a       ( 2325): Opening database auth.proximity.permit_store...
V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/AuthZenTransactionCache( 2325): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2325): Clearing transaction cache
D/PersistentNotificationBroadcastReceiver( 1997): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
I/ActivityManager(  834): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4275 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/AndroidRuntime( 4215): Calling main entry com.android.commands.am.Am
I/ActivityManager(  834): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  834): setTaskToReturnTo : TaskRecord{17c3c1a9 #217 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  834): setTaskToReturnTo : TaskRecord{17c3c1a9 #217 A=com.example.hello U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  834): AppWindowTokenEx init.. 
D/ContextHelper(  834): convertTheme. context->name=com.example.hello themeResourceId=16973833
D/InputDispatcher(  834): Focus left window: Window{31c59cde u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 4215): Shutting down VM
I/[LGHome]EVENT( 1907): [Launcher.java:986:onPause()]onPause
D/SplitWindow(  834): check instance of lgWin Window{1846f648 u0 Starting com.example.hello}
I/ActivityManager(  834): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4294 uid=10030 gids={50030, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/art     (  302): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 347us total 24.488ms
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 307us total 22.313ms
V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 302us total 23.392ms
I/NotificationManager(  834): android: cancelAsUser(-591465577) by android
I/WindowStateAnimator(  834): Starting window displayed
W/ResourcesManager( 4275): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/SystemUI[Framework](  834): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x0, pkg=com.example.hello
W/PhoneWindowManagerEx(  834): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  834): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  834): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  834): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@68860b4,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  834): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
D/PhoneStatusBar( 1385): setSystemUiVisibility vis=0 mask=ffffffff oldVal=8600 newVal=0 diff=8600
I/[SystemUI]NavigationThemeResource( 1385): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1385):  BarMode=0, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1385): , Keyguard show=false, IME shown=false, Panel expanded=false
D/BarTransitions( 1385): draw background and invalidate : color = 10000000
D/BarTransitions( 1385): draw background and invalidate : color = 100f0f0f
I/[LGHome]EVENT( 1907): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[LGHome]EVENT( 1907): [Launcher.java:5214:onStop()]onStop
D/ContextHelper( 4294): convertTheme. context->name=com.example.hello themeResourceId=16973833
W/ActivityThread( 1907): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1907): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1907): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3407)
W/ActivityThread( 1907): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3496)
W/ActivityThread( 1907): 	at android.app.ActivityThread.access$1100(ActivityThread.java:155)
W/ActivityThread( 1907): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1352)
W/ActivityThread( 1907): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 1907): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 1907): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/ActivityThread( 1907): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 1907): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 1907): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/ActivityThread( 1907): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/MicrophoneInputStream( 1973): mic_close com.google.android.apps.gsa.speech.audio.u@1ca7ff60
V/AudioRecord( 1973): stop()
D/AudioRecord( 1973): AudioRecord->stop()
V/AudioFlinger(  274): RecordHandle::stop()
V/AudioFlinger(  274): RecordThread::stop
I/HotwordDetector( 1973): Closing mic
V/AudioFlinger(  274): Record stopped OK
V/AudioPolicyManager(  274): stopInput() input 17
V/AudioPolicyService(  274): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  274): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  274): AudioCommandThread() waking up
V/AudioPolicyService(  274): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  274): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  274): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  274): ThreadBase::setParameters() routing=0
V/AudioFlinger(  274): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  274): processConfigEvents_l() remaining events 1
V/AudioFlinger(  274): processConfigEvents_l() DONE thread 0xb3c4a000
D/audio_hw_primary(  274): in_standby: enter: stream (0xb546dde0) usecase(7: audio-record)
,V/audio_hw_primary(  274): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  274): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  274): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  274): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  274): disable_audio_route: exit
E/audio_hw_primary(  274): disable_snd_device: enter 144
D/hardware_info(  274): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  274): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  274): stop_input_stream: exit: status(0)
V/audio_hw_primary(  274): in_standby: exit:  status(0)
V/AudioFlinger(  274): RecordThread: loop stopping
V/AudioPolicyService(  274): AudioCommandThread() going to sleep
V/AudioPolicyManager(  274): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  274): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  274): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  274): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  274): AudioCommandThread() waking up
V/AudioPolicyService(  274): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  274): AudioCommandThread() going to sleep
V/AudioPolicyService(  274): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  274): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  274): AudioCommandThread() waking up
V/AudioPolicyService(  274): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  274): setParameters(): io 17, keyvalue hotword_active=0, calling pid 274
V/AudioFlinger(  274): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  274): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  274): RecordThread: loop starting
V/AudioFlinger(  274): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  274): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  274): in_set_parameters: exit: status(0)
V/AudioFlinger(  274): processConfigEvents_l() DONE thread 0xb3c4a000
V/AudioFlinger(  274): RecordThread: loop stopping
V/AudioPolicyService(  274): AudioCommandThread() going to sleep
V/AudioRecord( 1973): stop()
V/AudioRecord( 1973): stop()
V/AudioRecord( 1973): stop()
V/AudioFlinger(  274): releasing 16 from 1973 for -1
V/AudioFlinger(  274):  decremented refcount to 0
V/AudioFlinger(  274): purging stale effects
V/AudioFlinger(  274): RecordHandle::stop()
V/AudioFlinger(  274): RecordThread::stop
V/AudioPolicyManager(  274): releaseInput() 17
V/AudioPolicyManager(  274): closeInput(17)
V/AudioFlinger(  274): closeInput() 17
V/AudioSystem(  274): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  834): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1973): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1782): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1385): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  274): ThreadBase::exit
V/AudioSystem( 2710): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2018): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  274): RecordThread: loop starting
V/AudioSystem( 3209): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  274): RecordThread 0xb3c4a000 exiting
D/audio_hw_primary(  274): adev_close_input_stream: enter:stream_handle(0xb546dde0)
D/audio_hw_primary(  274): in_standby: enter: stream (0xb546dde0) usecase(7: audio-record)
V/audio_hw_primary(  274): in_standby: exit:  status(0)
V/AudioPolicyService(  274): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  274): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  274): AudioCommandThread() waking up
V/AudioPolicyService(  274): AudioCommandThread() processing update audio port list
V/AudioPolicyManager(  274): releaseInput() exit
V/AudioPolicyService(  274): AudioCommandThread() going to sleep
V/AudioFlinger(  274): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  274): removeClient_l() pid 1973, calling pid 274
I/HotwordRecognitionRnr( 1973): Hotword detection finished
I/HotwordRecognitionRnr( 1973): Stopping hotword detection.
I/ActivityManager(  834): Activity reported stop, but no longer stopping: ActivityRecord{22468432 u0 com.lge.launcher2/.Launcher t216}
I/WebViewFactory( 4294): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/art     ( 1997): Explicit concurrent mark sweep GC freed 6731(400KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 11MB/18MB, paused 1.518ms total 121.011ms
I/GCoreUlr( 1764): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
I/GCoreUlr( 1764): Unbound from all location providers
I/LibraryLoader( 4294): Time to load native libraries: 2 ms (timestamps 6191-6193)
I/LibraryLoader( 4294): Expected native library version number "",actual native library version number ""
I/GCoreUlr( 1764): DispatchingService.onDestroy()
I/GCoreUlr( 1764): Stopping handler for UlrDispSvcFast
I/GCoreUlr( 1764): Unbound from all location providers
V/WebViewChromiumFactoryProvider( 4294): Binding Chromium to main looper Looper (main, tid 1) {3192b0e5}
I/LibraryLoader( 4294): Expected native library version number "",actual native library version number ""
I/chromium( 4294): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4294): Initializing chromium process, singleProcess=true
W/art     ( 4294): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4294): ApplicationContext is null in ApplicationStatus
W/chromium( 4294): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 4294): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4294): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4294): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4294): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4294): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4294): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4294): Remote Branch: 
I/Adreno-EGL( 4294): Local Patches: 
I/Adreno-EGL( 4294): Reconstruct Branch: 
V/AudioPolicyService(  274): registerClient() client 0xb551c840, uid 10030
D/BluetoothManagerService(  834): Message: 20
D/BluetoothManagerService(  834): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3e53308d:true
D/BluetoothAdapterService(843216481)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f7f6f3f
I/Babel_SMS( 4275): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4275): MmsConfig.loadMmsSettings
I/Babel_SMS( 4275): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4275): MmsConfig.loadFromDatabase
E/Babel_SMS( 4275): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4275): MmsConfig.loadFromResources
E/Babel_SMS( 4275): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4275): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
W/art     ( 4294): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 4294): onDetachedFromWindow called when already detached. Ignoring
D/SensorManager( 4275): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4275): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4275): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 4275): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4275): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4275): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4275): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4275): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4275): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4275): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4275): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4275): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4275): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4275): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4275): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4275): found sensor: Motion Accel, handle=46
D/SystemWebViewEngine( 4294): CordovaWebView is running on device made by: LGE
I/art     ( 4275): CheckpointMarkThreadRoots callback created = 0xb002d880
W/art     ( 4294): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4294): Attempt to remove local handle scope entry from IRT, ignoring
I/art     ( 4275): CheckpointMarkThreadRoots callback created = 0xb002d860
,W/Settings( 4275): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 4275): startup - clean
I/Activity( 4294): Activity.onPostResume() called 
,D/OpenGLRenderer( 4294): Render dirty regions requested: true
I/OpenGLRenderer( 4294): Initialized EGL, version 1.4
D/OpenGLRenderer( 4294): Enabling debug mode 0
D/Atlas   ( 4294): Validating map...
,D/SplitWindow(  834): check instance of lgWin Window{3253eabb u0 com.example.hello/com.example.hello.MainActivity}
I/Babel   ( 4275): deleted: false for 0
W/chromium( 4294): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  834): Focus entered window: Window{3253eabb u0 com.example.hello/com.example.hello.MainActivity}
,W/InputMethodManagerService(  834): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  834): Displayed com.example.hello/.MainActivity: +1s124ms
I/Timeline(  834): Timeline: Activity_windows_visible id: ActivityRecord{3511232e u0 com.example.hello/.MainActivity t217} time:56904
I/Timeline( 4294): Timeline: Activity_idle id: android.os.BinderProxy@1f0d0f8 time:56923
,W/AudioCapabilities( 4275): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 4275): Unsupported mime audio/adpcm
W/AudioCapabilities( 4275): Unsupported mime audio/g726
W/AudioCapabilities( 4275): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4275): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 4275): Unsupported mime video/mjpg
W/VideoCapabilities( 4275): Unsupported mime video/theora
,W/AudioCapabilities( 4275): Unsupported mime audio/evrc
,W/AudioCapabilities( 4275): Unsupported mime audio/qcelp
W/VideoCapabilities( 4275): Unrecognized profile 2130706433 for video/avc
W/BindingManager( 4294): Cannot call determinedVisibility() - never saw a connection for the pid: 4294
W/AudioCapabilities( 4275): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 4275): Unsupported mime audio/qcelp
W/AudioCapabilities( 4275): Unsupported mime audio/evrc
W/VideoCapabilities( 4275): Unsupported mime video/mp4v-esdp
,I/chromium( 4294): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
I/VideoCapabilities( 4275): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4275): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4275): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4275): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4275): Unrecognized profile 2130706433 for video/avc
,I/vclib   ( 4275): onServiceConnected
W/Babel   ( 4275): Attempted to change video mute state without an active call.
,D/JsMessageQueue( 4294): Set native->JS mode to OnlineEventsBridgeMode
I/NotificationManager( 4275): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager(  834): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4353 uid=10100 gids={50100, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/AndroidProtocolHandler( 4294): Unable to open asset URL: file:///android_asset/www/jxcore.js
,W/ResourcesManager( 4353): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4353): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/CursorWrapperInner( 3984): Cursor finalized without prior close()
,V/JNIHelp ( 4353): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,D/jxcore_app_log( 4294): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426850816
D/JX-Cordova( 4294): jxcore cordova android initializing
,W/System  ( 4353): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.youtube-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.youtube-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4353): Installed default security provider GmsCore_OpenSSL
,W/jxcore-log( 4294): Initializing JXcore engine
,W/jxcore-log( 4294): JXcore engine is ready
W/jxcore-log( 4294): Starting JXcore engine
,W/art     ( 4353): Suspending all threads took: 5.782ms
,W/m.example.hello( 4294): type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5680]" dev="sockfs" ino=5680 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
W/m.example.hello( 4294): type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
W/m.example.hello( 4294): type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8033]" dev="sockfs" ino=8033 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,W/m.example.hello( 4294): type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 4294): type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
W/m.example.hello( 4294): type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[20191]" dev="sockfs" ino=20191 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
W/ResourcesManager( 4353): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4353): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/art     ( 4353): CheckpointMarkThreadRoots callback created = 0xb002dbf0
,I/art     ( 4353): CheckpointMarkThreadRoots callback created = 0xb4958de0
,E/YouTube MDX( 4353): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/libc-netbsd( 4353): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4353): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/dex2oat ( 4394): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads-2126072530.jar --oat-fd=28 --oat-location=/data/data/com.google.android.youtube/cache/ads-2126072530.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4353): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
W/jxcore-log( 4294): Platform android
W/jxcore-log( 4294): 
W/jxcore-log( 4294): Process ARCH arm
W/jxcore-log( 4294): 
V/AlarmManager(  834): ELAPSED_WAKEUP set : Alarm{9608cc6 type 2 when 56883 com.google.android.talk} when 56883
V/AlarmManager(  834): ELAPSED_WAKEUP set : Alarm{10247487 type 2 when 58418 com.google.android.gms} when 58418
,I/jxcore-log( 4294): JXcore Cordova bridge is ready!
I/jxcore-log( 4294): 
W/jxcore-log( 4294): JXcore engine is started
,I/Choreographer( 4294): Skipped 32 frames!  The application may be doing too much work on its main thread.
I/dex2oat ( 4394): dex2oat took 136.398ms (threads: 4)
,E/jxcore-log( 4294): >> LGE-LG-D722
E/jxcore-log( 4294): 
,I/jxcore-log( 4294): Total memory 906309632
I/jxcore-log( 4294): 
I/jxcore-log( 4294): Free memory 24485888
I/jxcore-log( 4294): 
I/jxcore-log( 4294): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4294): 
I/jxcore-log( 4294): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4294): 
I/jxcore-log( 4294): userPath [ 'www' ]
I/jxcore-log( 4294): 
I/jxcore-log( 4294): Size 720 1196
I/jxcore-log( 4294): 
,I/jxcore-log( 4294): Screen Brightness 255
I/jxcore-log( 4294): 
E/jxcore-log( 4294): Dummy Error Log.
E/jxcore-log( 4294): 
,I/NotificationManager( 4353): com.google.android.youtube: cancel(2) by com.google.android.youtube
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
W/ContextImpl( 4353): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4353): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4353): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/files
,W/InstanceID/Rpc( 4353): Found 10006
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.youtube/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4353): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.youtube/cache
,I/art     (  834): Explicit concurrent mark sweep GC freed 22624(1130KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/34MB, paused 2.682ms total 170.378ms
,D/libc-netbsd( 4353): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4353): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4353): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4353): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  270): [LG DATA] No such appUid: 10100
D/DnsProxyListener(  270): App 10100 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  270): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  270): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  270): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  270): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  270): res_queryN name = xxxxx succeed
,I/System.out( 4353): propertyValue:false
D/libc-netbsd( 4353): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4353): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  834): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4451 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/NotificationManager( 4353): com.google.android.youtube: cancel(10436) by com.google.android.youtube
,I/ActivityManager(  834): Killing 3984:com.lge.cloudhub/u0a49 (adj 15): empty #11
,I/jxcore-log( 4294): getBuffer is called!!!!
I/jxcore-log( 4294): 
,W/libprocessgroup(  834): failed to open /acct/uid_10049/pid_3984/cgroup.procs: No such file or directory
,D/libc-netbsd( 4353): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4353): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/QCNEJ   ( 1870): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1870): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-52 ssid=NG700 bssid=c0:ff:d4:d3:aa:48 ipV4Addr=192.168.1.109 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2015-11-20 12:49:53.816 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ActivityManager(  834): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4451): getAccountsCursor
,V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 4451): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  834): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  834): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 4451): Observing account changes for notifications
W/ActivityManager(  834): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 4451): Error finding the version of the Email provider.....
E/Gmail   ( 4451): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 4451): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 4451): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 4451): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 4451): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 4451): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 4451): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 4451): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 4451): We do not support migrating this version of the Email provider.
I/Gmail   ( 4451): getAccountsCursor
V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  834): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  834): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/ActivityThread( 4451): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@1094a87d that was originally bound here
E/ActivityThread( 4451): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@1094a87d that was originally bound here
E/ActivityThread( 4451): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 4451): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 4451): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 4451): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 4451): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 4451): 	at com.android.emailcommon.service.ak.a(SourceFile:181)
E/ActivityThread( 4451): 	at com.android.emailcommon.service.ak.e(SourceFile:224)
E/ActivityThread( 4451): 	at com.android.email.service.n.c(SourceFile:177)
E/ActivityThread( 4451): 	at com.android.email.provider.b.a(SourceFile:198)
E/ActivityThread( 4451): 	at com.android.email.provider.b.a(SourceFile:142)
E/ActivityThread( 4451): 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
E/ActivityThread( 4451): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
E/ActivityThread( 4451): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 4451): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 4451): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 4451): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager(  834): Unbind failed: could not find connection for android.os.BinderProxy@2c84c86b
,I/ActivityManager(  834): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4494 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/Gmail   ( 4451): notifyAccountChanged
,I/Gmail   ( 4451): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ActivityManager(  834): Killing 4005:com.lge.gnss.airtest/u0a54 (adj 15): empty #11
,I/Gmail   ( 4451): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 4451): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 4451): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  834): failed to open /acct/uid_10054/pid_4005/cgroup.procs: No such file or directory
,D/KeyguardUpdateMonitor( 1385): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1385): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1385): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1385): On Skip Timer : true
,D/PowerService( 1834): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
V/[BNRBootReceiver]( 4494): boot receiver action = android.intent.action.BOOT_COMPLETED
V/[BNRBootReceiver]( 4494): set property sys.lge.bnrd = 1
V/[BNRBootReceiver]( 4494): End of BootComplted IF
V/[BNRBootReceiver]( 4494): Boot Receiver Return
,V/[BNRBootCompletedThread]( 4494): run
W/linker  ( 4513): /system/bin/bnrd has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/bnrd    ( 4513): BNRD > wait starting [4513-3058102400] <
E/bnrd    ( 4513): /data/data/.bnr_fifo_req
V/[BNRBootCompletedThread]( 4494): End of BNRProcess
,V/[BNRBootCompletedThread]( 4494): End of BNRViaWifiProcess
V/[BNRBootCompletedThread]( 4494): End of SpriteProcess
V/[BNRBootCompletedThread]( 4494): exit
I/ActivityManager(  834): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=4519 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  834): Killing 4026:com.lge.lgfota.permission/1000 (adj 15): empty #11
W/libprocessgroup(  834): failed to open /acct/uid_1000/pid_4026/cgroup.procs: No such file or directory
,V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 4451): getAccountsCursor
V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 4451): getAccountsCursor
,V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  834): Waited long enough for: ServiceRecord{2153a2ae u0 com.android.mms/.service.SwitchedService}
,D/Finsky  ( 4519): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 4519): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 4519): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4519): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 4519): com.android.vending: cancel(-1050172287) by com.android.vending
I/ActivityManager(  834): Killing 4063:com.lge.hiddenmenu/1000 (adj 15): empty #11
,W/libprocessgroup(  834): failed to open /acct/uid_1000/pid_4063/cgroup.procs: No such file or directory
,V/DownloadManager( 3230): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3230): created cursor android.database.sqlite.SQLiteCursor@115b443c on behalf of 4519
D/Volley  ( 4519): [473] DiskBasedCache.clear: Cache cleared.
,D/Volley  ( 4519): [466] DiskBasedCache.clear: Cache cleared.
I/ActivityManager(  834): Start proc com.lge.qmemoplus for broadcast com.lge.qmemoplus/.ui.editor.reminder.ReminderMaker: pid=4566 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  834): Killing 4081:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  834): failed to open /acct/uid_10014/pid_4081/cgroup.procs: No such file or directory
,D/Finsky  ( 4519): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 4519): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 4519): Skipping gmscore version check
D/Finsky  ( 4519): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/ResourcesManager( 4566): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/Finsky  ( 4519): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/App     ( 4566): [App][onCreate()] 4.40.21
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  834): RTC_WAKEUP set : Alarm{10705e3c type 0 when 1448020195594 com.google.android.googlequicksearchbox} when 1448020195594
,D/AccountManager( 4566): setSyncFrequency
,W/ContextImpl( 4566): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.lge.qmemoplus.ui.editor.reminder.ReminderMaker.onReceive:14 android.app.ActivityThread.handleReceiver:2663 
,D/ReminderService( 4566): [onHandleIntent] action : com.lge.qmemoplus.action.SET_REMINDERS
D/LocationReminderManager( 4566): [connect] Request location client connection.
W/ContextImpl( 4566): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.google.android.gms.internal.he.a:-1 com.google.android.gms.internal.hc.connect:-1 com.google.android.gms.location.LocationClient.connect:-1 
,I/ActivityManager(  834): Start proc com.lge.lgdmsclient for broadcast com.lge.lgdmsclient/.dmclient.agent.DmDeviceActionReceiver: pid=4604 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  834): Killing 4098:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,D/LocationReminderManager( 4566): location cilent is connected.
D/LocationReminderManager( 4566): [removeAllReminders]
,W/libprocessgroup(  834): failed to open /acct/uid_10069/pid_4098/cgroup.procs: No such file or directory
,W/GeofencerStateMachine( 1764): Ignoring removeGeofence because network location is disabled.
,D/LocationReminderManager( 4566): [removeAllReminders] statusCode : 1000
D/LocationReminderManager( 4566): [removeAllReminders] Failed to remove reminder
W/GCoreFlp( 1764): No location to return for getLastLocation()
W/GCoreFlp( 1764): No location to return for getLastLocation()
D/LGDMClient( 4604): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
,D/LGDMClient( 4604): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 4604): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
,V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
D/LGDMClient( 4604): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 4604): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
W/ContextImpl( 4604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
E/LGDMClient( 4604): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
,D/LGDMClient( 4604): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 4604): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
D/LGDMClient( 4604): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
D/LGDMClient( 4604): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
,I/ActivityManager(  834): Killing 4118:com.lge.springcleaning/1000 (adj 15): empty #11
W/libprocessgroup(  834): failed to open /acct/uid_1000/pid_4118/cgroup.procs: No such file or directory
,V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
I/ActivityManager(  834): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4630 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ResourcesManager( 4630): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  834): Message: 20
D/BluetoothManagerService(  834): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@52726b1:true
,D/BluetoothAdapterService(843216481)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f7f6f3f
D/BluetoothAdapterService(843216481)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f7f6f3f
I/ActivityManager(  834): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4651 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 4630): Create singleton instance
,D/UEI.SmartControl( 4651): Quickset Services start...
,I/UEI.SmartControl( 4651): Manufacture = LGE
D/UEI.SmartControl( 4651): File observer start...
E/UEI.SmartControl( 4651): IR Port is disabled: false
D/UEI.SmartControl( 4651): Starting file observer...
D/UEI.SmartControl( 4651): Extracting JNI libs...
D/UEI.SmartControl( 4651): --- this system supports 32-bit or 64-bit only
I/AudioManager( 4630): getMode name:com.lge.qremote
,I/AudioManager( 4630): getMode name:com.lge.qremote
,V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
,V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
D/UEI.SmartControl( 4651): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 4651): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4651): --- Extracting JNI libs: libqs_armeabi-v7a.zip
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
,V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3209): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3209): ANY_DATA_STATE event received: DISCONNECTED
D/LGDMClient( 4604): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
,D/LGDMClient( 4604): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 4604): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 4604): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,D/LGDMClient( 4604): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
I/ActivityManager(  834): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=4677 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/charger_monitor(  484): init target 500000
,I/UEI.SmartControl( 4651): --- Selecting new region: 2
I/UEI.SmartControl( 4651): -- Running on KitKat(19) and above! JNI will be used.
W/ContextImpl( 4604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
D/UEI.SmartControl( 4651): Platform has CIR...
,D/PowerService( 1834): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1385): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1385): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1385): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1385): On Skip Timer : true
D/UEI.SmartControl( 4651): NO CIR support, need to check package...
I/UEI.SmartControl( 4651): Model: LG-D722 uses JNI
E/LGDMClient( 4604): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 4604): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 4604): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 4604): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 4604): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,D/UEI.SmartControl( 4651): QS Service created
I/QCNEJ   ( 1870): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1385): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1385): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1870): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1834): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1834): Battery Level Remaining: 100%
D/LEDHandler( 1834): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2018): Disconnected process message: 10, size: 0
I/[SystemUI]LGPowerUI( 1385): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  834): battery changed pluggedType: 2
D/PowerService( 1834): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]BatterySaverHandler( 1385): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1385): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1385): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1385): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1385): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,V/AlarmManager(  834): RTC_WAKEUP set : Alarm{3aaf5ca5 type 0 when 1448020196843 com.google.android.gms} when 1448020196843
E/UEI.SmartControl( 4651): QS start get config
D/KeyguardUpdateMonitor( 1385): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
D/LEDHandler( 1834): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1834): Battery Level Remaining: 100%
D/LEDHandler( 1834): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1385): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1385): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/QCNEJ   ( 1870): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1870): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2018): Disconnected process message: 10, size: 0
,W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1385): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  834): battery changed pluggedType: 2
,D/UEI.SmartControl( 4651): Loading JNI Libs...
,D/UEI.SmartControl( 4651):  configuring local db...
W/ResourcesManager( 4677): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4677): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 4677): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4677): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 4677): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 4677): Using schema version: 115
,I/IndexDatabaseHelper( 4677): Index is fine
I/art     (  834): Explicit concurrent mark sweep GC freed 20933(994KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.414ms total 180.425ms
,I/iu.UploadsManager( 2325): End new media; added: 0, uploading: 0, time: 230 ms
,V/WiFiOffLoadBroadcast( 4677): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/UEI.SmartControl( 4651):  ---- Has DB8: true
D/UEI.SmartControl( 4651): QS start statue = true Error code = 0
,D/UEI.SmartControl( 4651): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4651): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4651): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 4651): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4651): IrrcClient ++ 
D/irrcClient( 4651): getIrrcService ++ 
,D/irrcClient( 4651): getIrrcService -- 
D/irrcClient( 4651): IrrcClient -- 
W/irrc_jni( 4651): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 4651): Services init done
I/UEI.SmartControl( 4651): Device manager: loading config....
D/UEI.SmartControl( 4651): QS Service init finished
D/UEI.SmartControl( 4651): QS Service version name: 0.1.73
D/UEI.SmartControl( 4651): QS Service version code: 1073
,D/WiFiOffLoadBroadcast( 4677): MCCMNC not supported: null
D/UEI.SmartControl( 4651): Config is loaded...
D/UEI.SmartControl( 4651): Service requested: Control
D/UEI.SmartControl( 4651):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 4651): Notify AllClients services are ready: 0
I/ActivityManager(  834): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4705 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  834): Killing 4155:com.google.android.configupdater/u0a3 (adj 15): empty #11
W/libprocessgroup(  834): failed to open /acct/uid_10003/pid_4155/cgroup.procs: No such file or directory
D/UEI.SmartControl( 4651): Internal service binding...
,D/UEI.SmartControl( 4651): -----IControl: 11
D/UEI.SmartControl( 4651): Caller: com.lge.qremote
D/UEI.SmartControl( 4651): ------------ IControl registerCallback...
I/UEI.SmartControl( 4651): Registering callback...
D/UEI.SmartControl( 4651): -----IControl: 19
D/UEI.SmartControl( 4651): Caller: com.lge.qremote
I/UEI.SmartControl( 4651): Registering Services Ready callback...
I/UEI.SmartControl( 4651): Notify client services are ready...
D/UEI.SmartControl( 4651): -----IControl: 8
D/UEI.SmartControl( 4651): Caller: com.lge.qremote
,I/ActivityManager(  834): Killing 4275:com.google.android.talk/u0a61 (adj 15): empty #11
D/PCSuite ( 4705): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  834): Killing 4185:com.lge.eula/1000 (adj 15): empty #12
,W/libprocessgroup(  834): failed to open /acct/uid_10061/pid_4275/cgroup.procs: No such file or directory
,W/libprocessgroup(  834): failed to open /acct/uid_1000/pid_4185/cgroup.procs: No such file or directory
D/UsbSettingsReceiver( 4677): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,D/UsbSettingsReceiver( 4677): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 4677): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 4677): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 4677): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsControl( 4677): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 4677): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 4677): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 4677): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 4677): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 4677): [AUTORUN] onReceive() : TetherState Changed=wlan0
,D/UsbSettingsControl( 4677): [AUTORUN] setTetherStatus() : status=false
I/AudioManager( 4630): getMode name:com.lge.qremote
V/WiFiOffLoadBroadcast( 4677): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 4677): MCCMNC not supported: null
D/PCSuite ( 4705): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDMClient( 4604): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4604): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,V/WiFiOffLoadBroadcast( 4677): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/LGDMClient( 4604): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/WiFiOffLoadBroadcast( 4677): MCCMNC not supported: null
I/LGDMClient( 4604): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4604): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
,D/LGDMClient( 4604): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/ContextImpl( 4604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4604): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 4604): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 4604): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 4604): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
I/PCSuite ( 4705): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/LGDMClient( 4604): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
D/PCSuite ( 4705): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4705): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/WiFiOffLoadBroadcast( 4677): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4677): MCCMNC not supported: null
V/[BNRBootReceiver]( 4494): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 4494): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 4494): Boot Receiver Return
V/WiFiOffLoadBroadcast( 4677): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
D/WiFiOffLoadBroadcast( 4677): Not supported operator for automatic switch
I/ActivityManager(  834): Killing 4353:com.google.android.youtube/u0a100 (adj 15): empty #11
,W/libprocessgroup(  834): failed to open /acct/uid_10100/pid_4353/cgroup.procs: No such file or directory
,D/WearableService( 1764): callingUid 10006, callindPid: 1764
,E/MDM     ( 1764): [96] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/GCM     ( 1997): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/LocationInitializer( 2325): Restart initialization of location
D/AuthorizationBluetoothService( 1997): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1997): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1997): com.google.android.gms: cancel(0) by com.google.android.gms
V/GmsCoreStatsServiceLauncher( 2325): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,V/WiFiOffLoadBroadcast( 4677): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
W/GCoreFlp( 1764): No location to return for getLastLocation()
W/FusedLocationProvider( 1997): location=null
D/WiFiOffLoadBroadcast( 4677): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 4677): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4677): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4677): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4677): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4677): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4677): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4677): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4677): MCCMNC not supported: null
I/ActivityManager(  834): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=4743 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  302): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 20.807ms
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.947ms
,I/art     (  302): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 21.318ms
,W/ResourcesManager( 4743): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4743): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4743): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LGEmail ( 4743): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 4743): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/BluetoothManagerService(  834): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  834): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@266c1185 mBinding = false
,D/BluetoothManagerService(  834): Message: 2
D/BluetoothAdapterService(843216481)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f7f6f3f
D/BluetoothManagerService(  834): Sending off request.
D/BluetoothAdapterService(843216481)( 2018): disable() called...
D/BluetoothAdapterService(843216481)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f7f6f3f
D/BluetoothAdapterService(843216481)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f7f6f3f
D/LocationManagerService(  834): getAllProviders()=[passive, gps, network]
D/WifiServiceImplEx(  834): setWifiEnabled: false pid=4294, uid=10030, package= com.example.hello, App Lable : HelloWorld
D/WifiService(  834): setWifiEnabled: false pid=4294, uid=10030
D/BluetoothAdapterState( 2018): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,D/BluetoothAdapterProperties( 2018): Setting state to 13
I/BluetoothAdapterState( 2018): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService(843216481)( 2018): updateAdapterState() - Broadcasting state to 1 receivers.
D/Ulp_jni (  834): JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  834): JNI:system_update. Event-4
D/BluetoothAdapterProperties( 2018): onBluetoothDisable()
I/BluetoothAdapterState( 2018): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btif ( 2018): HAL bt_hal_cbacks->adapter_properties_cb
,D/BluetoothAdapterProperties( 2018): Scan Mode:20
D/BluetoothAdapterState( 2018): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bt-btif ( 2018): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
E/bt-btif ( 2018): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
D/bt-btif ( 2018): btsock_ctrl_hci_cleanup(L202): poll handle:4
I/bt-btif ( 2018): BTA_JvDeleteRecord
I/bt-btif ( 2018): BTA_JvRfcommStopServer
I/bt-btif ( 2018): BTA_JvDeleteRecord
I/bt-btif ( 2018): BTA_JvRfcommStopServer
W/bt-btif ( 2018): invalid rfc slot id: 1
D/IOP_DB_BT( 2018): db_close: nbr users 0
D/IOP_DB_BT( 2018): db_close: free database
D/LocationManagerService(  834): getAllProviders()=[passive, gps, network]
D/Ulp_jni (  834): JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
D/Ulp_jni (  834): JNI:system_update. Event-4
I/jxcore-log( 4294): ****TEST TOOK:  5091  ms ****
I/jxcore-log( 4294): 
D/btif_config_util( 2018): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
D/btif_config_util( 2018): enum_config(L300): in, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 2018): enum_config(L302): section name:Local, key name:Adapter, value name:BluezMigrationDone, value type:int
I/jxcore-log( 4294): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4294): 
D/btif_config_util( 2018): enum_config(L343): out, key:Adapter, value:BluezMigrationDone
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:Adapter, value:Address
D/btif_config_util( 2018): enum_config(L302): section name:Local, key name:Adapter, value name:Address, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:Adapter, value:Address
D/btif_config_util( 2018): enum_config(L344): out, value:f8:95:c7:87:85:54
D/btif_config_util( 2018): enum_config(L300): in, key:Adapter, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Local, key name:Adapter, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:Adapter, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:G3s-1
D/btif_config_util( 2018): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 2018): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IR, value type:binary
D/btif_config_util( 2018): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IR
D/btif_config_util( 2018): enum_config(L344): out, value:��l:4A�O���x�x�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 2018): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 2018): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_IRK, value type:binary
D/btif_config_util( 2018): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_IRK
D/btif_config_util( 2018): enum_config(L344): out, value:�E@=-��ӑ`-'����8�\�婓��n�ScanMode
D/btif_config_util( 2018): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 2018): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_DHK, value type:binary
D/btif_config_util( 2018): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_DHK
D/btif_config_util( 2018): enum_config(L344): out, value:��8�\�婓��n�ScanMode
D/btif_config_util( 2018): enum_config(L300): in, key:Adapter, value:ScanMode
D/btif_config_util( 2018): enum_config(L302): section name:Local, key name:Adapter, value name:ScanMode, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:Adapter, value:ScanMode
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:Adapter, value:DiscoveryTimeout
D/btif_config_uti,l( 2018): enum_config(L302): section name:Local, key name:Adapter, value name:DiscoveryTimeout, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:Adapter, value:DiscoveryTimeout
D/btif_config_util( 2018): enum_config(L344): out, value:x
D/btif_config_util( 2018): enum_config(L300): in, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 2018): enum_config(L302): section name:Local, key name:Adapter, value name:LE_LOCAL_KEY_ER, value type:binary
D/btif_config_util( 2018): enum_config(L343): out, key:Adapter, value:LE_LOCAL_KEY_ER
D/btif_config_util( 2018): enum_config(L344): out, value:s!WE�(E��00:0F:F6
D/btif_config_util( 2018): enum_config(L300): in, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 2018): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:AddressBlacklist, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:AutoPairBlacklist, value:AddressBlacklist
D/btif_config_util( 2018): enum_config(L344): out, value:00:02:C7,00:16:FE,00:19:C1,00:1B:FB,00:1E:3D,00:21:4F,00:23:06,00:24:33,00:A0:79,00:0E:6D,00:13:E0,00:21:E8,00:60:57,00:0E:9F,00:12:1C,00:18:91,00:18:96,00:13:04,00:16:FD,00:22:A0,00:0B:4C,00:60:6F,00:23:3D,00:C0:59,00:0A:30,00:1E:AE,00:1C:D7,00:80:F0,00:12:8A,00:09:93,00:80:37,00:26:7E,00:06:F7,00:13:7B,00:1E:B2,00:07:04,00:13:7B,00:14:0A,00:1A:1B,00:22:4D,00:0B:24,00:1E:B2,00:0B:1F,18:6D:99,00:54:AF,18:6D:99,94:44:44,00:21:CC,04:98:F3,00:26:E8
D/btif_config_util( 2018): enum_config(L300): in, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 2018): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:ExactNameBlacklist, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:AutoPairBlacklist, value:ExactNameBlacklist
D/btif_config_util( 2018): enum_config(L344): out, value:Motorola IHF1000,i.TechBlueBAND,X5 Stereo v1.3,KML_CAN,Microsoft Mouse
D/btif_config_util( 2018): enum_config(L300): in, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 2018): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:PartialNameBlacklist, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:AutoPairBlacklist, value:PartialNameBlacklist
D/btif_config_util( 2018): enum_config(L344): out, value:BMW,Audi,Parrot,Car
D/btif_config_util( 2018): enum_config(L300): in, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 2018): enum_config(L302): section name:Local, key name:AutoPairBlacklist, value name:FixedPinZerosKeyboardBlacklist, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:AutoPairBlacklist, value:FixedPinZerosKeyboardBlacklist
D/btif_config_util( 2018): enum_config(L344): out, value:00:0F:F6
D/btif_config_util( 2018): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:�
D/btif_config_util( 2018): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 2018): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:b4:ce:f6:ab:a4:6a, value name:Service, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:b4:ce:f6:ab:a4:6a, value:Service
D/btif_config_util( 2018): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 2018): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:$
D/btif_config_util( 2018): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:Galaxy S6-1
D/btif_config_util( 2018): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:10:d3:8a:fb:85:d4, value name:Service, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:10:d3:8a:fb:85:d4, value:Service
D/btif_config_util( 2018): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:�
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:A5-1
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:37:96:ab, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:37:96:ab, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:#
D/btif_config_util( 2018): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:Nexus 6
D/btif_config_util( 2018): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:GlobalTrust, value type:int
W/bt-btif ( 2018): bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
E/bt-btif ( 2018): btif_hf_upstreams_evt: wrong handle = 1280 
D/btif_config_util( 2018): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f8:cf:c5:d9:e5:61, value name:Service, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:f8:cf:c5:d9:e5:61, value:Service
D/btif_config_util( 2018): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2018): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:�
D/btif_config_util( 2018): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:XT1072
D/btif_config_util( 2018): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevClass, value type:int
W/bt-obex ( 2018): Ignore event 10 in state 1
I/bt-btif ( 2018): HAL bt_op_callbacks->ops_state_cb
D/BluetoothOPPServiceJni( 2018): ops_state_cb(L223):  ops_state_cb state:3
D/OppService( 2018): onOpsStateChange() :3
W/bt-obex ( 2018): Ignore event 10 in state 1
D/btif_config_util( 2018): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:DevType, value type:int
E/bt-btif ( 2018): bta_gattc_deregister Deregister Failedm unknown client cif
D/OppService( 2018): Recieved MESSAGE_OPS_DISABLE
V/BluetoothMapMasInstance( 2018): Accept exception: (expected at shutdown)
V/BluetoothMapMasInstance( 2018): java.io.IOException: read failed, socket might closed or timeout, read ret: -1
V/BluetoothMapMasInstance( 2018): 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
V/BluetoothMapMasInstance( 2018): 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
V/BluetoothMapMasInstance( 2018): 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
V/BluetoothMapMasInstance( 2018): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
V/BluetoothMapMasInstance( 2018): 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
V/BluetoothMapMasInstance( 2018): 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
D/btif_config_util( 2018): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:44:80:eb:7b:5a:05, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:44:80:eb:7b:5a:05, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:a
V/BluetoothPbapService( 2018): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:S5-1
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:34:8a:a0, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:34:8a:a0, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:	a
D/btif_config_util( 2018): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:G4-1
D/btif_config_util( 2018): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:JustWorks,
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:f8:95:c7:87:3c:51, value:Service
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f8:95:c7:87:3c:51, value name:Service, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:f8:95:c7:87:3c:51, value:Service
D/btif_config_util( 2018): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2018): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:a
D/btif_config_util( 2018): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:Thali Test (Galaxy S5)
D/btif_config_util( 2018): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:b0:c5:59:3f:75:69, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:b0:c5:59:3f:75:69, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:�
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:Thali Test (Galaxy A5)
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:7c:f9:0e:51:18:22, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:7c:f9:0e:51:18:22, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:08:ec:a9:50:76:27, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:�
D/btif_config_util( 2018): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:Thali Test (Galaxy A3)
D/btif_config_util( 2018): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:08:ec:a9:50:76:27, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:08:ec:a9:50:76:27, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:08:ec:a9:50:76:27, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:ec:a9:50:76:27, value name:Service, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:08:ec:a9:50:76:27, value:Service
D/btif_config_util( 2018): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:A
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:Thali Test's G2
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:9d:93:0b, value name:Service, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:9d:93:0b, value:Service
D/btif_config_util( 2018): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2018): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:	a
D/btif_config_util( 2018): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:Note3-1
D/btif_config_util( 2018): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:e0:db:10:1f:c9:5e, value name:Service, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:e0:db:10:1f:c9:5e, value:Service
D/btif_config_util( 2018): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2018): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:08:ec:a9:50:75:41, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:�
D/btif_config_util( 2018): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:A3-1
D/btif_config_util( 2018): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:08:ec:a9:50:75:41, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:08:ec:a9:50:75:41, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:08:ec:a9:50:75:41, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:ec:a9:50:75:41, value name:Service, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:08:ec:a9:50:75:41, value:Service
D/btif_config_util( 2018): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2018): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:�
D/btif_config_util( 2018): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:XT1039
D/btif_config_util( 2018): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:f4:f1:e1:5c:3b:e2, value name:Service, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:f4:f1:e1:5c:3b:e2, value:Service
D/btif_config_util( 2018): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:	a
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:Nexus 5
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:11:ae:67, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:11:ae:67, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:�
D/btif_config_util( 2018): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:HTC One_M8
D/btif_config_util( 2018): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
,D/btif_config_util( 2018): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:Service
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:Service, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:Service
D/btif_config_util( 2018): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 2018): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:50:2e:6c:ac:21:50, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:50:2e:6c:ac:21:50, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:"
D/btif_config_util( 2018): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:Note4-1
D/btif_config_util( 2018): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:e0:db:10:14:e2:c0, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:e0:db:10:14:e2:c0, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:e0:db:10:14:e2:c0, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:80:01:84:8a:b3:68, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:80:01:84:8a:b3:68, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:�
D/btif_config_util( 2018): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:HTC Desire 820
D/btif_config_util( 2018): enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:80:01:84:8a:b3:68, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:80:01:84:8a:b3:68, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:80:01:84:8a:b3:68, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:80:01:84:8a:b3:68, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:80:01:84:8a:b3:68, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:80:01:84:8a:b3:68, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:80:01:84:8a:b3:68, value:Service
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:80:01:84:8a:b3:68, value name:Service, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:80:01:84:8a:b3:68, value:Service
D/btif_config_util( 2018): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb 00006675-7475-7265-6469-616c62756d70 fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2018): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:58:3f:54:73:64:c0, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:58:3f:54:73:64:c0, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:�
D/btif_config_util( 2018): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:G3-1
D/btif_config_util( 2018): enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:58:3f:54:73:64:c0, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:58:3f:54:73:64:c0, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:58:3f:54:73:64:c0, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:58:3f:54:73:64:c0, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:58:3f:54:73:64:c0, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:58:3f:54:73:64:c0, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:58:3f:54:73:64:c0, value:Service
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:58:3f:54:73:64:c0, value name:Service, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:58:3f:54:73:64:c0, value:Service
D/btif_config_util( 2018): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:	a
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:Nexus 5
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:34:fc:ef:11:b1:66, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:34:fc:ef:11:b1:66, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:34:fc:ef:11:b1:66, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:�
D/btif_config_util( 2018): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:HTC One M8s
D/btif_config_util( 2018): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:90:e7:c4:f6:69:77, value name:Service, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:90:e7:c4:f6:69:77, value:Service
D/btif_config_util( 2018): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001106-0000-1000-8000-00805f9b34fb 0000110e-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 00006675-7475-7265-6469-616c62756d70 
D/btif_config_util( 2018): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:A
D/btif_config_util( 2018): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:S5mini-1
D/btif_config_util( 2018): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:00:f4:6f:30:e0:6c, value name:Service, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:00:f4:6f:30:e0:6c, value:Service
D/btif_config_util( 2018): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000112d-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2018): enum_config(L300): in, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:08:00:00:00:67:f3, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:T\���K�`�D�`�D�
D/btif_config_util( 2018): enum_config(L300): in, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:���
D/btif_config_util( 2018): enum_config(L300): in, key:08:00:00:00:67:f3, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:08:00:00:00:67:f3, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:08:00:00:00:67:f3, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:ALE-L21
D/btif_config_util( 2018): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:58:2a:f7:ed:96:be, value name:Service, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:58:2a:f7:ed:96:be, value:Service
D/btif_config_util( 2018): enum_config(L344): out, value:0000110a-0000-1000-8000-00805f9b34fb 00001105-0000-1000-8000-00805f9b34fb 00001115-0000-1000-8000-00805f9b34fb 00001116-0000-1000-8000-00805f9b34fb 0000110c-0000-1000-8000-00805f9b34fb 0000112f-0000-1000-8000-00805f9b34fb 00001112-0000-1000-8000-00805f9b34fb 0000111f-0000-1000-8000-00805f9b34fb 00001132-0000-1000-8000-00805f9b34fb 00000000-0000-1000-8000-00805f9b34fb fa87c0d0-afac-11de-8a39-0800200c9a66 
D/btif_config_util( 2018): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpVer
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:LmpSubVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:LmpSubVer
D/btif_config_util( 2018): enum_config(L344): out, value:#
D/btif_config_util( 2018): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:Name
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:Name, value type:string
D/btif_config_util( 2018): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:Name
D/btif_config_util( 2018): enum_config(L344): out, value:onem9-1
D/btif_config_util( 2018): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:DevClass
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevClass, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevClass
D/btif_config_util( 2018): enum_config(L344): out, value:Z
D/btif_config_util( 2018): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:DevType, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:DevType
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:JustWorks
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:JustWorks, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:JustWorks
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:90:e7:c4:3c:62:6a, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:90:e7:c4:3c:62:6a, value name:GlobalTrust, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:90:e7:c4:3c:62:6a, value:GlobalTrust
D/btif_config_util( 2018): enum_config(L344): out, value:
D/btif_config_util( 2018): enum_config(L300): in, key:14:b4:84:21:3b:49, value:Manufacturer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:Manufacturer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:14:b4:84:21:3b:49, value:Manufacturer
D/btif_config_util( 2018): enum_config(L344): out, value:H
D/btif_config_util( 2018): enum_config(L300): in, key:14:b4:84:21:3b:49, value:LmpVer
D/btif_config_util( 2018): enum_config(L302): section name:Remote, key name:14:b4:84:21:3b:49, value name:LmpVer, value type:int
D/btif_config_util( 2018): enum_config(L343): out, key:14:b4:84:21:3b:49, value:LmpVer
E/WifiStateMachine(  834): WifiStateMachine: Leaving Connected state
E/WifiConfigStore(  834): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
D/BluetoothAdapterService(843216481)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f7f6f3f
D/BluetoothManagerService(  834): Message: 60
D/BluetoothManagerService(  834): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
D/BluetoothManagerService(  834): Bluetooth State Change Intent: 12 -> 13
D/BluetoothAdapterService(843216481)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f7f6f3f
D/BluetoothAdapterService(843216481)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f7f6f3f
I/BluetoothMapService( 2018): onReceive: android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 2018): STATE_TURNING_OFF
I/[SystemUI]QuickSettingsHandler( 1385): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
I/[SystemUI]BluetoothHandler( 1385): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
D/BluetoothAdapterService(843216481)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f7f6f3f
D/LGBluetoothAPIService( 1834): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothMapService( 2018): Handler(): got msg=4
D/BluetoothAdapterService(843216481)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f7f6f3f
D/BluetoothMapService( 2018): MAP Service closeService in
D/BluetoothMapMasInstance( 2018): MAP Service shutdown
D/LGBluetoothMapAdapter( 2018): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2018): MAP Service closeService out
I/PackageChangeReceiver( 4743): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  834): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=4783 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
W/ContextImpl( 4677): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,V/BluetoothPbapReceiver( 2018): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 2018): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 2018): ***********state = 13
V/BluetoothPbapReceiver( 2018): ***********Calling start service!!!! with action = null
,V/BluetoothPbapService( 2018): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 2018): state: 13
V/BluetoothPbapService( 2018): Pbap Service closeService in
V/BluetoothPbapService( 2018): successfully stopped pbap service
,V/BluetoothPbapService( 2018): Pbap Service closeService out
V/BluetoothPbapService( 2018): Pbap Service onDestroy
V/BluetoothPbapService( 2018): Pbap Service closeService in
V/BluetoothPbapService( 2018): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 2018): [BTUI] cleanup
D/BluetoothManagerService(  834): Message: 20
D/BluetoothManagerService(  834): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c3b36e8:true
,D/BluetoothAdapterService(843216481)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f7f6f3f
,D/BluetoothManagerService(  834): Message: 30
D/BluetoothManagerService(  834): Message: 30
,D/LGWifiP2pService(  834): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  834): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  834): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/LocalBluetoothProfileManager( 4677): Adding local MAP profile
D/BluetoothMap( 4677): Create BluetoothMap proxy object
D/BluetoothManagerService(  834): Message: 30
D/CommandListener(  270): Clearing all IP addresses on wlan0
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 7
,D/BluetoothManagerService(  834): Message: 30
D/LocalBluetoothProfileManager( 4677): LocalBluetoothProfileManager construction complete
D/LGBluetoothFeatureConfig( 4677):  get() - isFeatureLoaded : false
,I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 10
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 7
,D/ConnectivityService(  834): NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
D/ConnectivityService(  834): ignoring duplicate network state non-change
D/ConnectivityService(  834): NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WifiHS20(  834): hidePasspointNotification off =false
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  834): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/QCNEJ   ( 1870): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/LGWifiP2pService(  834): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  834): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,I/QCNEJ   ( 1870): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-11-20 12:49:58.496 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1870): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/WifiNetworkAgent(  834): NetworkAgent: NetworkAgent channel lost
D/WifiHS20(  834): hidePasspointNotification off =false
I/QCNEJ   ( 1870): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
I/QCNEJ   ( 1870): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-11-20 12:49:58.502 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1870): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/[SystemUI]StatusBar.NetworkController( 1385): mWifiConnected = false, mWifiLevel = 0
D/LGBluetoothUserBindClient( 4677): [BTUI] initUserBindClient
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  834): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiScanningService(  834): SCAN_AVAILABLE : 1
D/RttService(  834): SCAN_AVAILABLE : 1
D/LGWifiP2pService(  834): P2pDisablingState
D/WifiScanningService(  834): DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService(  834): EnabledState got{ when=-2ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGWifiP2pService(  834): P2pDisablingState{ when=-9ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  834): p2p socket connection lost
D/LGWifiP2pService(  834): P2pDisabledState
D/WfdsService( 1834): WifiP2pState is changed : false
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WfdsService( 1834): WfdsEnabledState: Receive the WFDS_DISABLE message
D/WfdsJNI ( 1834): doCommand: P2P_STOP_FIND
D/LGWifiP2pService(  834): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/LGWifiP2pService(  834): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl( 4677): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1864 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:98 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:57 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WfdsService( 1834): Set the WFDS Monitor: false
I/[SystemUI]QuickSettingsHandler( 1385): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1385): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1385): Remote
I/[SystemUI]StatusBar.NetworkController( 1385): mWifiConnected = false, mWifiLevel = 0
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1385): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1385): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1385): Remote
,I/[SystemUI]QuickSettingsHandler( 1385): Got action android.net.wifi.p2p.STATE_CHANGED at null
D/WfdsMonitor( 1834): WFDS Monitor is stopped
D/CtrlSupplicant( 1834): Received on exit socket, terminate
E/CtrlSupplicant( 1834): wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
D/WfdsMonitor( 1834): Event [CTRL-EVENT-TERMINATING  - connection closed]
D/WfdsMonitor( 1834): WfdsMonitorThread is received the interrupt - closing
,D/WfdsService( 1834): STATE : WfdsDisabledState - enter
D/WfdsService( 1834): WFDS: Scanner is paused
D/WfdsDiscoveryStore( 1834): Clear Discovery Method Map: ScanAlwaysMode false
W/WfdsSession:Controller( 1834): DefaultState - msg [9441355] is not handled
I/ActivityManager(  834): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=4812 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/DockEventReceiver( 4677): finishStartingService: stopping service
D/BluetoothInputDevice( 4677): Proxy object connected
D/HidProfile( 4677): Bluetooth service connected
D/BluetoothAdapterService(843216481)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f7f6f3f
D/BluetoothPan( 4677): BluetoothPAN Proxy object connected
D/PanProfile( 4677): Bluetooth service connected
D/BluetoothAdapterService(843216481)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f7f6f3f
,D/BluetoothMap( 4677): Proxy object connected
D/MapProfile( 4677): Bluetooth service connected
D/BluetoothMap( 4677): getConnectedDevices()
D/BluetoothAdapterService(843216481)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f7f6f3f
D/BluetoothMap( 4677): Bluetooth is Not enabled
D/LGBluetoothUserBindClient( 4677): [BTUI] onServiceConnected
D/LGBluetoothAuthorization( 4677): [BTUI] cancel All Notification
,I/NotificationManager( 4677): com.android.settings: cancel(17301632) by com.android.settings
D/CommandListener(  270): Clearing all IP addresses on wlan0
D/ConnectivityService(  834): Default network via Wi-Fi disconnect. stop DSQN
D/DSQN    (  834): disableDataServiceNotify
I/NotificationManager( 4677): com.android.settings: cancel(-1000001) by com.android.settings
I/NotificationManager( 4677): com.android.settings: cancel(-1000011) by com.android.settings
I/NotificationManager( 4677): com.android.settings: cancel(-1000021) by com.android.settings
D/DSQN    (  834): stop dsqn bin
I/NotificationManager( 4677): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 4677): com.android.settings: cancel(-1000041) by com.android.settings
I/QCNEJ   ( 1870): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
D/WifiHS20(  834): hidePasspointNotification off =false
W/Settings(  834): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  834): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  834): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
I/[SystemUI]StatusBar.NetworkController( 1385): mWifiConnected = false, mWifiLevel = 0
I/QCNEJ   ( 1870): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-11-20 12:49:58.637 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1870): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/BluetoothPermissionRequest( 4677): onReceive
,I/QCNEJ   ( 1870): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1870): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-11-20 12:49:58.645 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1870): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
D/LGBluetoothAuthorization( 4677): [BTUI] cancel All Notification
I/NotificationManager( 4677): com.android.settings: cancel(17301632) by com.android.settings
I/NotificationManager( 4677): com.android.settings: cancel(-1000001) by com.android.settings
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1385): Got action android.net.wifi.STATE_CHANGE at null
I/[SystemUI]QuickSettingsHandler( 1385): Got action android.net.wifi.STATE_CHANGE at Quick
I/[SystemUI]QuickSettingsHandler( 1385): Remote
I/WifiServerServiceExt(  834): WIFI_STATE_CHANGED_ACTION [0]
,D/WifiServerServiceExt(  834): SUPPLICANT_STATE_CHANGED_ACTION
D/WifiServerServiceExt(  834): setSupplicantStateDISCONNECTED
I/NotificationManager( 4677): com.android.settings: cancel(-1000011) by com.android.settings
D/ConnectivityService(  834): notifyType LOST for NetworkAgentInfo [WIFI () - 100]
D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
I/NotificationManager( 4677): com.android.settings: cancel(-1000021) by com.android.settings
I/NotificationManager( 4677): com.android.settings: cancel(-1000031) by com.android.settings
I/NotificationManager( 4677): com.android.settings: cancel(-1000041) by com.android.settings
D/ConnectivityService(  834): sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
D/ConnectivityService(  834):  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityManager.CallbackHandler( 1385): CM callback handler got msg 524292
D/ConnectivityService(  834): sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/Nat464Xlat(  834): requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
D/ConnectivityManager.CallbackHandler( 2325): CM callback handler got msg 524292
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitor NetworkAgentInfo [WIFI () - null](  834): Disconnected - quitting
,D/CSLegacyTypeTracker(  834): [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
D/CSLegacyTypeTracker(  834): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1385): Got action android.net.wifi.WIFI_STATE_CHANGED at null
D/ConnectivityService(  834): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
D/ConnectivityService(  834): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  834): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
V/NetworkPolicy(  834): [LG_RESTRICTED] !!!isConnected  type  :1
W/QCNEJ   ( 1870): |CORE| No family connected
D/Tethering(  834): MasterInitialState.processMessage what=3
D/ConnectivityService(  834): sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
D/ConnectivityService(  834): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/ConnectivityService(  834): sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/NetworkManagementService(  834): Removing idletimer
D/WIFI    (  834): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI    (  834):   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
W/Settings(  834): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyNetworkFactory-1( 1782): new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,D/TelephonyNetworkFactory-1( 1782):   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
I/ActivityManager(  834): Killing 4451:com.google.android.gm/u0a53 (adj 15): empty #11
D/DhcpStateMachine(  834): StoppedState
D/DhcpStateMachine(  834): StoppedState{ when=-163ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,I/AppUp4:AppBoxCP( 4812): onCreate
,W/AppUp4:DB( 4812):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 4812):  setFingerPrint start
I/AppUp4:DB( 4812):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
V/BluetoothOppReceiver( 2018): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 2018): [BTUI] cancel opp incoming file confirm notification
I/NotificationManager( 2018): com.android.bluetooth: cancel(-1) by com.android.bluetooth
D/BluetoothOppNotification( 2018): [BTUI] cancel opp active transfer file notification
,I/NotificationManager( 2018): com.android.bluetooth: cancel(-1) by com.android.bluetooth
W/libprocessgroup(  834): failed to open /acct/uid_10053/pid_4451/cgroup.procs: No such file or directory
V/NetworkPolicy(  834): [LG_RESTRICTED] !!!isConnected  type  :1
D/Tethering(  834): MasterInitialState.processMessage what=3
W/QCNEJ   ( 1870): |CORE| No family connected
I/QCNEJ   ( 1870): |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
I/QCNEJ   ( 1870): |CORE| sendDefaultNwMsg: default = -1
V/BluetoothSapReceiver( 2018): [BTUI] checkServiceStart
I/AppUp4:DB( 4812):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4812):  SDK version = 0
,D/LGBluetoothStateChangeReceiver( 2018): [BTUI] action : android.bluetooth.adapter.action.STATE_CHANGED
I/AppUp4:DB( 4812):  beforefinger == newfinger no write in DB
I/Netd    (  270): M: Get netlink event, ifname: p2p0 action: 4
I/Netd    (  270): M: Get netlink event, ifname: p2p0 action: 5
I/wpa_supplicant( 2791): p2p0: CTRL-EVENT-TERMINATING 
I/wpa_supplicant( 2791): monitor socket send errors count : 1
I/wpa_supplicant( 2791): CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1834-2\x00 that cannot receive messages
I/Netd    (  270): M: Get netlink event, ifname: p2p0 action: 10
I/Netd    (  270): M: Get netlink event, ifname: p2p0 action: 7
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/wpa_supplicant( 2791): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/AndroidRuntime( 4775): 
D/AndroidRuntime( 4775): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/wpa_supplicant( 2791): USIM:  scard_deinit function
,D/AndroidRuntime( 4775): CheckJNI is OFF
,I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 4
I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 4
D/libc-netbsd(  834): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd(  834): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  834): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4834 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/AppUp4:AppBoxApplication( 4812): AppBoxApplication onCreate()
,I/ActivityManager(  834): Killing 4519:com.android.vending/u0a36 (adj 15): empty #11
,I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 4
,I/Netd    (  270): M: Get netlink event, ifname: wlan0 action: 5
I/wpa_supplicant( 2791): wlan0: CTRL-EVENT-TERMINATING 
D/Tethering(  834): InitialState.processMessage what=4
,W/libprocessgroup(  834): failed to open /acct/uid_10036/pid_4519/cgroup.procs: No such file or directory
D/Tethering(  834): sendTetherStateChangedBroadcast 0, 0, 0
,D/WfdsService( 1834): Supplicant Connection state is changed : false
D/WfdsService( 1834): DefaultState - WIFI_SUPPLICANT_DISCONNECTED
D/WfdsService( 1834): Set the WFDS Monitor: false
D/WfdsMonitor( 1834): WFDS Monitor is stopped
D/WifiOffDelayIfNotUsed(  834): stopMonitoring
I/QCNEJ   ( 1870): |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.WIFI_STATE_CHANGED
I/QCNEJ   ( 1870): |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2015-11-20 12:49:58.885 DNS addrs= 0.0.0.0, 0.0.0.0, 
I/QCNEJ   ( 1870): |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
I/WifiServerServiceExt(  834): WIFI_STATE_CHANGED_ACTION [1]
,I/WifiServerServiceExt(  834): batteryPsActivateMsgHandler : state:0 event:1
I/WifiServerServiceExt(  834): batteryPsActivateMsgHandler : this is not treated
W/Settings( 1764): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TelephonyIcons( 1385): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1385): updateLGTelephonySignalStrength : !hasService()
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  834): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=4861 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 4834): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/TelephonyIcons( 1385): null signal icon name: drawable/stat_sys_signal_null
I/[SystemUI]LGNetworkController( 1385): updateLGTelephonySignalStrength : !hasService()
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1385): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=(null) mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]QuickSettingsHandler( 1385): Got action android.net.wifi.WIFI_STATE_CHANGED at null
I/ActivityManager(  834): Killing 4566:com.lge.qmemoplus/1000 (adj 15): empty #11
,W/libprocessgroup(  834): failed to open /acct/uid_1000/pid_4566/cgroup.procs: No such file or directory
,D/AuthorizationBluetoothService( 1997): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
W/ResourcesManager( 4861): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4861): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 4861): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/AndroidRuntime( 4775): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  834): Force stopping com.example.hello appid=10030 user=-1: uninstall pkg
,I/ActivityManager(  834): Killing 4294:com.example.hello/u0a30 (adj 0): stop com.example.hello
I/WindowState(  834): WIN DEATH: Window{3253eabb u0 com.example.hello/com.example.hello.MainActivity}
,D/InputDispatcher(  834): Focus left window: Window{3253eabb u0 com.example.hello/com.example.hello.MainActivity}
D/InputDispatcher(  834): Window went away: Window{3253eabb u0 com.example.hello/com.example.hello.MainActivity}
W/bt-l2cap( 2018): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2018): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-btif ( 2018): ag scb idx 1 not allocated
E/bt-btif ( 2018): BTA AG is already disabled, ignoring ...
W/bt-l2cap( 2018): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2018): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 2018): ag scb idx 1 not allocated
E/bt-btif ( 2018): BTA AG is already disabled, ignoring ...
E/bt-btif ( 2018): bta_gattc_deregister Deregister Failedm unknown client cif
E/bt-btif ( 2018): bta_gattc_deregister Deregister Failedm unknown client cif
W/bt_userial( 2018): select_read return size <=0:0, exiting userial_read_thread
D/bt_hwcfg( 2018): hw_epilog_process
I/bt_userial_vendor( 2018): device fd = 70 close
,W/PackageSettings(  834): Skipping PackageSetting{3e415e53 com.test.thalitest/10316} due to missing metadata
,E/bt_vendor( 2018): [BTUI] Proto is enabled. Set Proto disable!!
W/ActivityManager(  834): Force removing ActivityRecord{3511232e u0 com.example.hello/.MainActivity t217}: app died, no saved state
,I/ActivityManager(  834): Waited long enough for: ServiceRecord{3c2e2716 u0 com.lge.mlt/.MltMonitorService}
,I/ActivityManager(  834): Force stopping com.example.hello appid=10030 user=0: pkg removed
W/ActivityManager(  834): Spurious death for ProcessRecord{37ca38a9 4294:com.example.hello/u0a30}, curProc for 4294: null
,I/AppConfig( 4861): Total System Memory = 906309632
I/[LGHome]EVENT( 1907): [Launcher.java:5203:onStart()]onStart
D/KeyguardModel( 1385): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
W/GeofencerStateMachine( 1764): Ignoring removeGeofence because network location is disabled.
,W/System.err( 3679): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 3679): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3679): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3679): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3679): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3679): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3679): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3679): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3679): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3679): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3679): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3679): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/GalleryUtils( 4861): Application Heap = 96 MB
I/QCNEJ   ( 1870): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/AppConfig( 4861): App Tier : NOT_DEF
I/[LGHome]EVENT( 1907): [Launcher.java:776:onResume()]onResume
,D/SystemHelper( 4861): region [EU], country [EU], operator [OPEN], sub-operator []
,I/GKI_LINUX( 2018): GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/InputReader(  834): Reconfiguring input devices.  changes=0x00000010
I/ActivityManager(  834): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4882 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,D/administrator(  834): Handling package changes for user 0
I/[SystemUI]QSlideListController( 1385): onReceive = android.intent.action.PACKAGE_REMOVED
I/GKI_LINUX( 2018): gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 2018): GKI_destroy_task(): task [BTU] terminated
I/bt-btif ( 2018): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothAdapterState( 2018): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterService( 2018): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2018): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService( 2018): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2018): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,D/BtSettings.ProfileConfig( 2018): Unable to read settings
D/BtSettings.ProfileConfig( 2018): android.provider.Settings$SettingNotFoundException: bt_svcst_com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2018): 	at android.provider.Settings$System.getIntForUser(Settings.java:1453)
D/BtSettings.ProfileConfig( 2018): 	at android.provider.Settings$System.getInt(Settings.java:1443)
D/BtSettings.ProfileConfig( 2018): 	at com.broadcom.bt.service.ProfileConfig.isProfileConfiguredEnabled(ProfileConfig.java:654)
D/BtSettings.ProfileConfig( 2018): 	at com.android.bluetooth.btservice.AdapterService.setProfileServiceState(AdapterService.java:1047)
D/BtSettings.ProfileConfig( 2018): 	at com.android.bluetooth.btservice.AdapterService.stopProfileServices(AdapterService.java:738)
D/BtSettings.ProfileConfig( 2018): 	at com.android.bluetooth.btservice.AdapterState$PendingCommandState.processMessage(AdapterState.java:529)
D/BtSettings.ProfileConfig( 2018): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
D/BtSettings.ProfileConfig( 2018): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
D/BtSettings.ProfileConfig( 2018): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/BtSettings.ProfileConfig( 2018): 	at android.os.Looper.loop(Looper.java:135)
D/BtSettings.ProfileConfig( 2018): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BluetoothAdapterService( 2018): Not skipping com.android.bluetooth.hfp.HeadsetService
D/BluetoothAdapterService(843216481)( 2018): setProfileServiceState() - Stopping service com.android.bluetooth.hfp.HeadsetService
,I/ActivityManager(  834): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=4900 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  834): Killing 4604:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/art     (  834): Explicit concurrent mark sweep GC freed 32663(1862KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.895ms total 277.337ms
,D/BluetoothAdapterService( 2018): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2018): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BluetoothAdapterService( 2018): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2018): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2018): Not skipping com.android.bluetooth.a2dp.A2dpService
D/HeadsetService( 2018): Received stop request...Stopping profile...
D/BluetoothAdapterService(843216481)( 2018): setProfileServiceState() - Stopping service com.android.bluetooth.a2dp.A2dpService
W/libprocessgroup(  834): failed to open /acct/uid_1000/pid_4604/cgroup.procs: No such file or directory
D/BluetoothAdapterService( 2018): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2018): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2018): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2018): getProfileSaveSetting: com.android.bluetooth.hid.HidService
I/[LGHome]LGActivityUtil( 1907): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
W/BluetoothAdapterService( 2018): Not skipping com.android.bluetooth.hid.HidService
D/BluetoothAdapterService(843216481)( 2018): setProfileServiceState() - Stopping service com.android.bluetooth.hid.HidService
,I/LGBluetoothHfpAdapter( 2018): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 2018): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 2018): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32427661
D/HeadsetStateMachine( 2018): Exit Disconnected: -1
D/BluetoothAdapterService( 2018): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2018): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2018): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2018): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
W/BluetoothAdapterService( 2018): Not skipping com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService(843216481)( 2018): setProfileServiceState() - Stopping service com.android.bluetooth.hdp.HealthService
I/[LGHome]EVENT( 1907): [Launcher.java:929:onResume()]onResume end
I/Activity( 1907): Activity.onPostResume() called 
D/BluetoothHeadset( 1782): Proxy object disconnected
D/BluetoothHeadset( 1782): Proxy object disconnected
D/BluetoothHeadset( 1782): Proxy object disconnected
D/BluetoothAdapterService( 2018): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2018): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 2018): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2018): getProfileSaveSetting: com.android.bluetooth.pan.PanService
,D/A2dpService( 2018): Received stop request...Stopping profile...
D/A2dpStateMachine( 2018): Exit Disconnected: -1
W/BluetoothAdapterService( 2018): Not skipping com.android.bluetooth.pan.PanService
D/BluetoothAdapterService(843216481)( 2018): setProfileServiceState() - Stopping service com.android.bluetooth.pan.PanService
,D/BluetoothAdapterService( 2018): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2018): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 2018): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2018): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
W/BluetoothAdapterService( 2018): Not skipping com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService(843216481)( 2018): setProfileServiceState() - Stopping service com.android.bluetooth.gatt.GattService
D/BluetoothAdapterService( 2018): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2018): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2018): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2018): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
W/BluetoothAdapterService( 2018): Not skipping com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService(843216481)( 2018): setProfileServiceState() - Stopping service com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2018): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2018): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2018): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2018): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 2018): Not skipping com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(843216481)( 2018): setProfileServiceState() - Stopping service com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2018): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2018): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 2018): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2018): getProfileSaveSetting: com.broadcom.bt.service.ftp.FTPService
W/BluetoothAdapterService( 2018): Not skipping com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(843216481)( 2018): setProfileServiceState() - Stopping service com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 2018): getQuietmodeRadioCount = 0
W/BluetoothAdapterService( 2018): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2018): getQuietmodeRadioCount = 0
D/BtSettings.ProfileConfig( 2018): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
W/BluetoothAdapterService( 2018): Not skipping com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(843216481)( 2018): setProfileServiceState() - Stopping service com.broadcom.bt.service.opp.OppService
D/LGBluetoothA2dpAdapter( 2018): [BTUI] LGBluetoothA2dpAdapter cleanup
D/BluetoothAdapterState( 2018): Stopping profile services that were post enabled
W/LGBluetoothA2dpServiceJni( 2018): Cleaning up Bluetooth Handsfree callback object
D/LGBluetoothPowerControlManager( 2018): [BTUI] terminate
,D/BluetoothManagerService(  834): Message: 31
D/BluetoothAdapterService( 2018): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32427661
D/BluetoothAdapterService(843216481)( 2018): handleMessage() - Message: 1
D/BluetoothAdapterService(843216481)( 2018): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(843216481)( 2018): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BluetoothAdapterState( 2018): isTurningOnRadio()=false
D/BluetoothAdapterState( 2018): isTurningOffRadio()=false
D/BluetoothAdapterState( 2018): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2018): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2018): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2018): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2018): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(843216481)( 2018): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/HidService( 2018): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2018): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32427661
I/LockScreenSettings( 4882): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/HealthService( 2018): Received stop request...Stopping profile...
D/BluetoothInputDevice( 4677): Proxy object disconnected
D/HidProfile( 4677): Bluetooth service disconnected
I/SystemUI[Framework](  834): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x600, pkg=com.lge.launcher2
W/PhoneWindowManagerEx(  834): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  834): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  834): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  834): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@68860b4,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  834): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
W/[LGHome]LGWallpaperInfo( 1907): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1907): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
D/BluetoothAdapterService( 2018): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32427661
D/HeadsetStateMachine( 2018): Unbinding service...
D/HeadsetPhoneState( 2018): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 2018): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 2018): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 2018): [BTUI] listenForMultiSimPhoneState : start = false
W/BluetoothHeadsetServiceJni( 2018): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2018): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 2018): [BTUI] LGBluetoothHfpAdapter cleanup
D/PanService( 2018): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2018): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32427661
D/BtGatt.DebugUtils( 2018): handleDebugAction() action=null
,D/BtGatt.GattService( 2018): Received stop request...Stopping profile...
D/BtGatt.GattService( 2018): stop()
D/BtGatt.AdvertiseManager( 2018): advertise clients cleared
D/LGBluetoothGattAdapter( 2018): [BTUI] LGBluetoothGattAdapter cleanup
D/BluetoothAdapterService( 2018): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32427661
,D/BluetoothMapService( 2018): Received stop request...Stopping profile...
D/BluetoothMapService( 2018): stop()
D/BluetoothMapEmailAppObserver( 2018): deinitObservers()
D/BluetoothMapEmailAppObserver( 2018): removeReceiver()
D/BluetoothAdapterService( 2018): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32427661
D/SapService( 2018): Received stop request...Stopping profile...
D/SapService( 2018): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 2018): [BTUI] LGBluetoothSapAdapter cleanup
D/LGBluetoothSapManager( 2018): [BTUI] terminateSapManager
,D/InputDispatcher(  834): Focus entered window: Window{31c59cde u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/BluetoothAdapterService( 2018): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32427661
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1385): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.example.hello
D/KeyguardModel( 1385): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/LgeBluetoothSimManager( 1782): [BTUI] SAP_DISABLE_EVT
D/**BluetoothFTPService( 2018): Received stop request...Stopping profile...
D/**BluetoothFTPService( 2018): Stopping Bluetooth FTP Service
V/BluetoothFTPServiceJni( 2018): closeFtpServerNative
D/BluetoothAdapterService( 2018): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32427661
I/art     ( 1817): CheckpointMarkThreadRoots callback created = 0xaaf1fb80
,D/**OppService( 2018): Received stop request...Stopping profile...
D/OppService( 2018): Stopping Bluetooth OppService
D/OppService( 2018): cleanup OPP Service
W/BluetoothOPPServiceJni( 2018): Cleaning up Bluetooth Opp Interface...
W/BluetoothOPPServiceJni( 2018): Cleaning up Bluetooth OPP callback object
D/BluetoothPan( 4677): BluetoothPAN Proxy object disconnected
D/PanProfile( 4677): Bluetooth service disconnected
D/BluetoothMap( 4677): Proxy object disconnected
D/MapProfile( 4677): Bluetooth service disconnected
D/OppService( 2018): remove callbacks and handler
D/LGBluetoothOppAdapter( 2018): [BTUI] LGBluetoothOppAdapter cleanup
D/OppService( 2018): cleanup done
D/BluetoothAdapterService( 2018): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32427661
D/BluetoothAdapterService(843216481)( 2018): handleMessage() - Message: 1
D/BluetoothAdapterService(843216481)( 2018): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(843216481)( 2018): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BluetoothAdapterState( 2018): isTurningOnRadio()=false
D/BluetoothAdapterState( 2018): isTurningOffRadio()=false
D/BluetoothAdapterState( 2018): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2018): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2018): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2018): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2018): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(843216481)( 2018): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
I/BluetoothA2dpServiceJni( 2018): cleanupNative
I/GKI_LINUX( 2018): GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2018): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2018): GKI_destroy_task(): task [A2DP-MEDIA] terminated
D/BluetoothAdapterService(843216481)( 2018): handleMessage() - Message: 1
D/BluetoothAdapterService(843216481)( 2018): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(843216481)( 2018): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BluetoothAdapterState( 2018): isTurningOnRadio()=false
D/BluetoothAdapterState( 2018): isTurningOffRadio()=false
D/BluetoothAdapterState( 2018): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2018): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2018): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hid.HidService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2018): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2018): Profile still running: com.broadcom.bt.service.opp.OppService
,D/BluetoothAdapterService(843216481)( 2018): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHidServiceJni( 2018): Cleaning up Bluetooth HID Interface...
W/BluetoothHidServiceJni( 2018): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService(843216481)( 2018): handleMessage() - Message: 1
D/BluetoothAdapterService(843216481)( 2018): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(843216481)( 2018): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BluetoothAdapterState( 2018): isTurningOnRadio()=false
D/BluetoothAdapterState( 2018): isTurningOffRadio()=false
D/BluetoothAdapterState( 2018): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2018): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2018): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.hdp.HealthService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2018): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2018): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(843216481)( 2018): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothHealthServiceJni( 2018): Cleaning up Bluetooth Health Interface...
W/BluetoothHealthServiceJni( 2018): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 2018): Cleaning up Bluetooth Health object
D/BluetoothAdapterService(843216481)( 2018): handleMessage() - Message: 1
D/BluetoothAdapterService(843216481)( 2018): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(843216481)( 2018): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BluetoothAdapterState( 2018): isTurningOnRadio()=false
D/BluetoothAdapterState( 2018): isTurningOffRadio()=false
D/BluetoothAdapterState( 2018): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2018): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2018): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.pan.PanService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2018): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2018): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(843216481)( 2018): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothPanServiceJni( 2018): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2018): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService(843216481)( 2018): handleMessage() - Message: 1
D/BluetoothAdapterService(843216481)( 2018): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(843216481)( 2018): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=true
D/BluetoothAdapterState( 2018): isTurningOnRadio()=false
D/BluetoothAdapterState( 2018): isTurningOffRadio()=false
D/BluetoothAdapterState( 2018): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2018): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2018): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.gatt.GattService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2018): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2018): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(843216481)( 2018): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
V/BluetoothMapService( 2018): Handler(): got msg=4
D/BluetoothMapService( 2018): MAP Service closeServ,ice in
D/LGBluetoothMapAdapter( 2018): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2018): MAP Service closeService out
D/BluetoothAdapterService(843216481)( 2018): handleMessage() - Message: 1
D/BluetoothAdapterService(843216481)( 2018): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(843216481)( 2018): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BluetoothAdapterState( 2018): isTurningOnRadio()=false
D/BluetoothAdapterState( 2018): isTurningOffRadio()=false
D/BluetoothAdapterState( 2018): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2018): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2018): processProfileServiceStateChanged(): serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2018): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2018): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(843216481)( 2018): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothMapService( 2018): cleanup()
D/BluetoothMapService( 2018): MAP Service closeService in
D/LGBluetoothMapAdapter( 2018): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 2018): MAP Service closeService out
D/BluetoothAdapterService(843216481)( 2018): handleMessage() - Message: 1
D/BluetoothAdapterService(843216481)( 2018): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(843216481)( 2018): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
D/BluetoothAdapterState( 2018): isTurningOnRadio()=false
D/BluetoothAdapterState( 2018): isTurningOffRadio()=false
D/BluetoothAdapterState( 2018): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2018): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2018): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.sap.SapService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2018): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2018): Profile still running: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService(843216481)( 2018): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
W/BluetoothSAPServiceJni( 2018): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2018): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService(843216481)( 2018): handleMessage() - Message: 1
D/BluetoothAdapterService(843216481)( 2018): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
I/[LGHome]EVENT( 1907): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/BluetoothAdapterService(843216481)( 2018): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, doUpdate=true
D/BluetoothAdapterState( 2018): isTurningOnRadio()=false
D/BluetoothAdapterState( 2018): isTurningOffRadio()=false
D/BluetoothAdapterState( 2018): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2018): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2018): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.ftp.FTPService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BtSettings.ProfileConfig( 2018): getProfileSaveSetting: com.broadcom.bt.service.opp.OppService
D/BluetoothAdapterService( 2018): Profile still running: com.broadcom.bt.service.opp.OppService
,D/BluetoothAdapterService(843216481)( 2018): onProfileServiceStateChange() - Profile still running: com.broadcom.bt.service.opp.OppService
I/[LGHome]LGPlusHomeDBManager( 1907): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
D/BluetoothFTPService( 2018): cleanup FTP Service
V/BluetoothFTPServiceJni( 2018): closeFtpServerNative
V/BluetoothFTPServiceJni( 2018): cleanupNative
W/BluetoothFTPServiceJni( 2018): Cleaning up Bluetooth FTP Server Interface...
W/BluetoothFTPServiceJni( 2018): Cleaning up Bluetooth FTP callback object
D/BluetoothFTPService( 2018): BluetoothFtpBinder.cleanup()
D/BluetoothFTPService( 2018): cleanup done
D/BluetoothAdapterService(843216481)( 2018): handleMessage() - Message: 1
,D/BluetoothAdapterService(843216481)( 2018): handleMessage() - MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService(843216481)( 2018): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.opp.OppService, state=10, doUpdate=true
D/BluetoothAdapterState( 2018): isTurningOnRadio()=false
D/BluetoothAdapterState( 2018): isTurningOffRadio()=false
D/BluetoothAdapterState( 2018): isQuietModeServiceTurningOn()=false
D/BluetoothAdapterState( 2018): isQuietModeServiceTurningOff()=false
D/BluetoothAdapterService( 2018): processProfileServiceStateChanged(): serviceName=com.broadcom.bt.service.opp.OppService, state=10, Bluetooth isTurningOff=true,Bluetooth isTurningOn=false
D/BluetoothAdapterService(843216481)( 2018): onProfileServiceStateChange() - All profile services stopped...
,D/OppService( 2018): cleanup OPP Service
D/OppService( 2018): remove callbacks and handler
D/LGBluetoothOppAdapter( 2018): [BTUI] LGBluetoothOppAdapter cleanup
D/BluetoothAdapterState( 2018): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
D/OppService( 2018): cleanup done
D/BluetoothAdapterProperties( 2018): Setting state to 10
I/BluetoothAdapterState( 2018): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService(843216481)( 2018): updateAdapterState() - Broadcasting state to 1 receivers.
D/BluetoothManagerService(  834): Message: 60
,D/BluetoothManagerService(  834): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  834): Broadcasting onBluetoothStateChange(false) to 9 receivers.
I/[LGHome]LGPlusHomeDBManager( 1907): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
I/BluetoothAdapterState( 2018): Entering OffState
D/BluetoothHeadset( 1782): onBluetoothStateChange: up=false
D/BluetoothHeadset(  834): onBluetoothStateChange: up=false
D/BluetoothPbap( 4677): onBluetoothStateChange: up=false
,D/BluetoothMap( 4677): onBluetoothStateChange: up=false
D/KeyguardModel( 1385): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1385): createShortcutInfo...
D/BluetoothPan( 4677): onBluetoothStateChange on: false
D/BluetoothInputDevice( 4677): onBluetoothStateChange: up=false
D/BluetoothA2dp(  834): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1782): onBluetoothStateChange: up=false
D/KeyguardModel( 1385): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1385): createShortcutInfo...
D/BluetoothHeadset( 1782): onBluetoothStateChange: up=false
D/BluetoothAdapterService(843216481)( 2018): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f7f6f3f
D/BluetoothManagerService(  834): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  834): Broadcasting onBluetoothServiceDown() to 10 receivers.
I/[LGHome]EVENT( 1907): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,I/PhoneWindow( 1907): [setNavigationBarColor] color=0x 0
W/ResourcesManager( 1385): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4900): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4900): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4900): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 1385): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
D/BluetoothManagerService(  834): Calling onQBluetoothServiceDown callbacks
D/BluetoothManagerService(  834): Broadcasting onQBluetoothServiceDown() to 0 receivers.
D/BluetoothManagerService(  834): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@266c1185 mBinding = false
D/BluetoothManagerService(  834): Sending unbind request.
D/BluetoothAdapterService(843216481)( 2018): onUnbind() - calling cleanup
D/BluetoothAdapterService(843216481)( 2018): cleanup()
W/ResourceType( 1385): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1385): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/AndroidRuntime( 4775): Shutting down VM
D/BluetoothManagerService(  834): Bluetooth State Change Intent: 13 -> 10
,D/LGBluetoothAPIService( 1834): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1834): Message: 2
D/KeyguardModel( 1385): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1385): createShortcutInfo...
W/ResourcesManager( 4900): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 4900): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/LGBluetoothAPIService( 1834): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@31e0a504 mBinding = false
D/LGBluetoothAPIService( 1834): Sending unbind request.
D/LGBluetoothFeatureConfig( 4677): isPrivacyLogsEnabled : true
D/LGBluetoothUtils( 4677): [BTUI] resetProperty - success
E/LGBluetoothEventManager( 4677): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
I/NotificationService(  834): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/LGBluetoothEventManager( 4677): [BTUI] clear device connection state
D/BackupManagerService(  834): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/BluetoothAdapter( 1385): 704310469: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1385): 704310469: getState() :  mService = null. Returning STATE_OFF
W/ContextImpl( 4677): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
D/BluetoothAdapterService(843216481)( 2018): cleanup() - Cleaning up adapter native
I/bt-btif ( 2018): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 2018): GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/bt-btif ( 2018): HAL bt_hal_cbacks->thread_evt_cb
I/GKI_LINUX( 2018): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2018): GKI_destroy_task(): task [BTIF] terminated
I/GKI_LINUX( 2018): GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2018): GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2018): GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 2018): GKI_exit_task 2 done
I/GKI_LINUX( 2018): GKI_exit_task 1 done
I/GKI_LINUX( 2018): GKI_exit_task 0 done
I/BluetoothServiceJni( 2018): cleanupNative: return from cleanup
W/LGBluetoothServiceJni( 2018): Cleaning up Bluetooth Service callback object
W/InputMethodManagerService(  834): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/art     ( 1817): CheckpointMarkThreadRoots callback created = 0xaaf462d0
D/JobSchedulerService(  834): Receieved: android.intent.action.PACKAGE_REMOVED
I/[SystemUI]QuickSettingsHandler( 1385): Got action android.bluetooth.adapter.action.STATE_CHANGED at null
D/LGBluetoothSettingsDBObserver( 2018): [BTUI] unregister observer for LG device name DB
I/[SystemUI]BluetoothHandler( 1385): Receive : BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
D/BluetoothAdapterService(843216481)( 2018): cleanup() - Bluetooth process exited normally.
W/InputMethodManagerService(  834): Got RemoteException sending setActive(false) notification to pid 4294 uid 10030
D/BluetoothAdapterService(843216481)( 2018): cleanup() done
,D/TaskPersister(  834): removeObsoleteFile: deleting file=217_task.xml
I/art     ( 2018): System.exit called, status: 0
I/AndroidRuntime( 2018): VM exiting with result code 0, cleanup skipped.
D/PhoneStatusBar( 1385): setSystemUiVisibility vis=600 mask=ffffffff oldVal=0 newVal=600 diff=600
,D/DockEventReceiver( 4677): finishStartingService: stopping service
W/ResourcesManager( 1385): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourceType( 1385): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1385): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/BluetoothAdapter( 1764): 93260721: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1764): 93260721: getState() :  mService = null. Returning STATE_OFF
V/AudioFlinger(  274): 2018 died, releasing its sessions
V/AudioFlinger(  274):  pid 1782 @ 0
V/AudioFlinger(  274):  pid 2710 @ 1
V/AudioFlinger(  274):  pid 3209 @ 2
V/AudioFlinger(  274):  pid 3209 @ 3
D/FMFRW_FmProxy( 1834): Fm Proxy object disconnected
,D/KeyguardModel( 1385): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1385): createShortcutInfo...
D/LGBluetoothUserBindClient( 4677): [BTUI] onServiceDisconnected
W/ResourcesManager( 1385): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1385): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 1385): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourceType( 1385): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1385): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1385): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1385): createShortcutInfo...
I/HotwordRecognitionRnr( 1973): Starting hotword detection.
,I/MicrophoneInputStream( 1973): mic_starting com.google.android.apps.gsa.speech.audio.u@69eda3e
V/AudioRecord( 1973): set(): inputSource 1999, sampleRate 16000, format 0x1, channelMask 0x10, frameCount 128000, notificationFrames 0, sessionId 0, transferType 0, flags 0
V/AudioRecord( 1973): set(): mSessionId 23
V/AudioPolicyManager(  274): getInput() inputSource 1999, samplingRate 16000, format 1, channelMask 10, session 23, flags 0
V/AudioPolicyManager(  274): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  274): isPlaybackThread 0,isRecordThread 1
D/audio_hw_primary(  274): adev_open_input_stream: enter: sample_rate(16000) channel_mask(0x10) devices(0x80000004)        stream_handle(0xb546e420)
V/audio_hw_primary(  274): adev_open_input_stream: exit
V/AudioFlinger(  274): openInput_l() openInputStream returned input 0xb546e420, SamplingRate 16000, Format 0x1, Channels 10, flags 0, status 0
V/AudioFlinger(  274): openInput_l() created record thread: ID 24 thread 0xb3c4a000
V/AudioSystem(  274): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem(  834): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 2710): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 3209): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 1385): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 1973): ioConfigChanged() event 3, ioHandle 24
V/AudioSystem( 1782): ioConfigChanged() event 3, ioHandle 24
V/AudioPolicyService(  274): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  274): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  274): AudioCommandThread() waking up
V/AudioPolicyService(  274): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  274): AudioCommandThread() going to sleep
I/AudioFlinger(  274): AudioFlinger's thread 0xb3c4a000 ready to run
D/audio_hw_primary(  274): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
V/audio_hw_primary(  274): in_standby: exit:  status(0)
V/AudioFlinger(  274): openRecord() lSessionId: 23 input 24
D/audio_hw_primary(  274): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
V/audio_hw_primary(  274): in_standby: exit:  status(0)
V/AudioFlinger(  274): RecordThread: loop stopping
V/AudioFlinger(  274): getOrphanEffectChain_l session 23 index -2
I/Timeline( 1907): Timeline: Activity_idle id: android.os.BinderProxy@aa0c01b time:65203
V/AudioFlinger(  274): acquiring 23 from 1973, for -1
V/AudioFlinger(  274):  added new entry for 23
V/AudioRecord( 1973): start, sync event 0 trigger session 0
V/AudioRecord( 1973): mAudioRecord->start()
V/AudioFlinger(  274): RecordHandle::start()
V/AudioFlinger(  274): RecordThread::start event 0, triggerSession 0
I/SystemUI[Framework](  834): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
V/AudioPolicyManager(  274): startInput() module primary->input primary(24)
V/AudioPolicyManager(  274): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager(  274): getNewInputDevice() selected device 80000004
V/AudioPolicyManager(  274): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager(  274): DeviceVector::getDevicesFromType() for type 80000004 found 0xb547b280
V/AudioPolicyService(  274): AudioCommandThread() adding create patch delay 0
V/AudioPolicyService(  274): inserting command: 7 at index 0, num commands 0
V/AudioPolicyService(  274): AudioCommandThread() waking up
V/AudioPolicyService(  274): AudioCommandThread() processing create audio patch
V/AudioFlinger::PatchPanel(  274): createAudioPatch() num_sources 1 num_sinks 1 handle 0
V/AudioFlinger::PatchPanel(  274): createAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters input_source=6;routing=-2147483644
V/AudioFlinger(  274): ThreadBase::setParameters() input_source=6;routing=-2147483644
V/AudioFlinger(  274): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  274): RecordThread: loop starting
V/AudioFlinger(  274): processCo,nfigEvents_l() remaining events 1
D/audio_hw_primary(  274): in_set_parameters: enter: kvpairs=input_source=6;routing=-2147483644
V/audio_hw_primary(  274): in_set_parameters: exit: status(0)
V/AudioFlinger(  274): processConfigEvents_l() DONE thread 0xb3c4a000
D/PhoneStatusBar( 1385): setSystemUiVisibility vis=8600 mask=ffffffff oldVal=600 newVal=8600 diff=8000
V/AudioFlinger::PatchPanel(  274): createAudioPatch() status 0
V/AudioFlinger::PatchPanel(  274): createAudioPatch() added new patch handle 25 halHandle 0
V/AudioPolicyService(  274): AudioCommandThread() going to sleep
V/AudioPolicyManager(  274): setInputDevice() createAudioPatch returned 0 patchHandle 25
V/AudioPolicyManager(  274): addAudioPatch() handle 20 af handle 0 num_sources 1 num_sinks 1 source handle 10sink handle 19
V/AudioPolicyService(  274): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  274): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  274): AudioCommandThread() waking up
V/AudioPolicyService(  274): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  274): AudioCommandThread() adding set parameter string hotword_active=1, io 24 ,delay 0
V/AudioPolicyService(  274): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  274): AudioCommandThread() waking up
V/AudioPolicyService(  274): AudioCommandThread() processing set parameters string hotword_active=1, io 24
V/AudioFlinger(  274): setParameters(): io 24, keyvalue hotword_active=1, calling pid 274
V/AudioFlinger(  274): ThreadBase::setParameters() hotword_active=1
V/AudioFlinger(  274): sendConfigEvent_l() num events 1 event 2
I/[SystemUI]NavigationThemeResource( 1385): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1385):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1385): , Keyguard show=false, IME shown=false, Panel expanded=false
,W/PhoneWindowManagerEx(  834): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  834): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  834): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  834): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@68860b4,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  834): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/AudioPolicyService(  274): AudioCommandThread() going to sleep
V/AudioFlinger(  274): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  274): in_set_parameters: enter: kvpairs=hotword_active=1
V/audio_hw_primary(  274): in_set_parameters: exit: status(0)
V/AudioFlinger(  274): processConfigEvents_l() DONE thread 0xb3c4a000
V/AudioPolicyService(  274): AudioCommandThread() going to sleep
V/AudioPolicyManager(  274): AudioPolicyManager::startInput() input source = 1999
D/BarTransitions( 1385): draw background and invalidate : color = f0000000
D/BarTransitions( 1385): draw background and invalidate : color = f0e7e7e7
V/msm8974_platform(  274): platform_update_usecase_from_source: input source :6
,D/audio_hw_primary(  274): start_input_stream: enter: stream(0xb546e420)usecase(7: audio-record)
V/voice   (  274): voice_check_and_set_incall_rec_usecase: voice call not active
V/audio_hw_primary(  274): start_input_stream: usecase(7)
E/audio_hw_primary(  274): select_devices: enter and usecase(7)
V/msm8974_platform(  274): platform_get_input_snd_device: enter: out_device(0) in_device(0x4)
V/msm8974_platform(  274): platform_get_input_snd_device: exit: in_snd_device(voice-rec-mic)
V/msm8974_platform_lge(  274): LGE_platform_get_input_snd_device: exit: in_snd_device(lg-vr-handset-mic)
V/audio_hw_lge_primary(  274): LGE_exeption_scenario: enter and out: 0, in: 144
D/audio_hw_primary(  274): select_devices: out_snd_device(0: ) in_snd_device(144: lg-vr-handset-mic)
E/audio_hw_primary(  274): enable_snd_device: enter  144
D/hardware_info(  274): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  274): enable_snd_device: snd_device(144: lg-vr-handset-mic)
V/msm8974_platform_lge(  274): LGE_platform_send_audio_calibration: sending audio calibration for snd_Device(144) acdb_id(65)
I/ActivityManager(  834): Process com.android.bluetooth (pid 2018) has died
D/ACDB-LOADER(  274): ACDB -> send_audio_cal, acdb_id = 65, path =  1
D/ACDB-LOADER(  274): ACDB -> send_adm_topology
D/ACDB-LOADER(  274): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TOPOLOGY_ID
W/ActivityManager(  834): Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
W/ActivityManager(  834): Scheduling restart of crashed service com.android.bluetooth/com.broadcom.fm.fmreceiver.FmService in 10999ms
D/ACDB-LOADER(  274): ACDB -> send_asm_topology
D/ACDB-LOADER(  274): ACDB -> ACDB_CMD_GET_AUDPROC_STREAM_TOPOLOGY_ID
D/ACDB-LOADER(  274): ACDB -> send_audtable
D/ACDB-LOADER(  274): ACDB -> ACDB_CMD_GET_AUDPROC_COMMON_TABLE
D/ACDB-LOADER(  274): ACDB -> AUDIO_SET_AUDPROC_CAL
D/ACDB-LOADER(  274): ACDB -> send_audvoltable
D/ACDB-LOADER(  274): ACDB -> ACDB_CMD_GET_AUDPROC_GAIN_DEP_STEP_TABLE
D/        (  274): Failed to fetch the lookup information of the device 00000041 
E/ACDB-LOADER(  274): Error: ACDB AudProc vol returned = -19
D/ACDB-LOADER(  274): ACDB -> AUDIO_SET_AUDPROC_VOL_CAL
D/ACDB-LOADER(  274): ACDB -> AUDIO_SET_AFE_CAL
V/audio_hw_primary(  274): enable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  274): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  274): enable_audio_route: apply mixer and update path: audio-record
,V/audio_hw_primary(  274): enable_audio_route: exit
D/audio_hw_primary(  274): select_devices: done
V/audio_hw_primary(  274): start_input_stream: Opening PCM device card_id(0) device_id(0), channels 1
I/MicrophoneInputStream( 1973): mic_started com.google.android.apps.gsa.speech.audio.u@69eda3e
V/audio_hw_primary(  274): start_input_stream: exit
D/KeyguardModel( 1385): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1385): createShortcutInfo...
D/KeyguardModel( 1385): handleShortcutListChanged...
,D/BluetoothPermissionRequest( 4677): onReceive
D/KeyguardModel( 1385): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1385): createShortcutInfo...
D/LGBluetoothUtils( 4677): [BTUI] FileNotFound: readProperty
,D/BluetoothDiscoverableTimeoutReceiver( 4677): cancelDiscoverableAlarm(): Enter
W/ResourceType( 1385): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1385): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1385): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1385): createShortcutInfo...
W/ResourceType( 1385): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1385): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1385): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1385): createShortcutInfo...
W/ResourceType( 1385): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1385): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,D/KeyguardModel( 1385): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1385): createShortcutInfo...
I/ActivityManager(  834): Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=4926 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 1035, 4002, 1023} abi=armeabi-v7a
,I/[SystemUI]TimeTickManager( 1385): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1385): called onTimeUpdated()
,I/[LGHome]EVENT( 1907): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1907): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1907): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[SystemUI]Clock( 1385): called onTimeUpdated()
I/LgeClockWidgetControlView( 1385): called onTimeUpdated()
,I/[SystemUI]DateView( 1385): called onTimeUpdated()
I/[SystemUI]DateView( 1385): called onTimeUpdated()
I/ActivityManager(  834): Killing 4494:com.lge.bnr/1000 (adj 15): empty #11
I/QCNEJ   ( 1870): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  834): Reconfiguring input devices.  changes=0x00000010
I/HotwordWorker( 1973): onReady
,D/administrator(  834): Handling package changes for user 0
D/KeyguardModel( 1385): handleShortcutListChanged...
,W/libprocessgroup(  834): failed to open /acct/uid_1000/pid_4494/cgroup.procs: No such file or directory
I/[SystemUI]QPairHandler( 1385): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]QSlideListController( 1385): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1385): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1385): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1385): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
D/KeyguardUpdateMonitor( 1385): handleTimeUpdate
,I/[SystemUI]TimeTickManager( 1385): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1385): called onTimeUpdated()
I/[SystemUI]Clock( 1385): called onTimeUpdated()
,I/Timeline(  834): Timeline: Activity_windows_visible id: ActivityRecord{22468432 u0 com.lge.launcher2/.Launcher t216} time:65486
W/ResourcesManager( 4926): Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
W/ResourcesManager( 4926): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4926): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/LgeClockWidgetControlView( 1385): called onTimeUpdated()
I/[SystemUI]DateView( 1385): called onTimeUpdated()
I/[SystemUI]DateView( 1385): called onTimeUpdated()
W/ResourcesManager( 4926): Asset path '/system/framework/com.broadcom.fm.jar' does not exist or contains no resources.
D/KeyguardUpdateMonitor( 1385): handleTimeUpdate
,I/NotificationService(  834): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  834): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }

```
