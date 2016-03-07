#### Test 61362366a48397d_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/NotificationManager(  953): android: cancelAsUser(2) by android
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
--------- beginning of system
W/libprocessgroup(  953): failed to open /acct/uid_10089/pid_4709/cgroup.procs: No such file or directory
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5024): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5024): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
I/GAv4    ( 5024): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5024):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5024):   adb logcat -s GAv4
W/ContextImpl( 5024): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5024): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/GAv4    ( 5024): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5024): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5024): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  953): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5065 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
W/ResourcesManager( 5065): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5065): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 5065): VM with version 2.1.0 has multidex support
I/MultiDex( 5065): install
I/MultiDex( 5065): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 5065): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 5065): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5065): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d162e2a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5065): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5065): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5065): com.google.android.gms: cancel(39789) by com.google.android.gms
D/AndroidRuntime( 5062): 
D/AndroidRuntime( 5062): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/art     ( 5065): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5065): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/AndroidRuntime( 5062): CheckJNI is OFF
I/WebViewFactory( 5024): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5024): Time to load native libraries: 2 ms (timestamps 2807-2809)
I/LibraryLoader( 5024): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5024): Binding Chromium to main looper Looper (main, tid 1) {2c2e75da}
I/LibraryLoader( 5024): Expected native library version number "",actual native library version number ""
I/chromium( 5024): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/WVCdm   (  280): Instantiating CDM.
I/WVCdm   (  280): CdmEngine::OpenSession
I/WVCdm   (  280): Level3 Library Dec 11 2014 16:13:16
I/BrowserStartupController( 5024): Initializing chromium process, singleProcess=true
W/art     ( 5024): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5024): ApplicationContext is null in ApplicationStatus
D/NativeLibraryUtils( 5065): Install completed successfully. count=14 extracted=0
W/WVCdm   (  280): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  280): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  280): L1 library not specified. Falling Back to L3
I/ActivityManager(  953): Process com.google.android.music:main (pid 4827) has died
I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  280): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  280): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
D/WVCdm   (  280): PrepareKeyRequest: nonce=1076318296
W/chromium( 5024): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5024): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5024): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 73130375236; DSPS: 2495240; Offset : -3030381272
I/Adreno-EGL( 5024): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5024): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5024): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5024): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5024): Remote Branch: 
I/Adreno-EGL( 5024): Local Patches: 
I/Adreno-EGL( 5024): Reconstruct Branch: 
D/AndroidRuntime( 5062): Calling main entry com.android.commands.am.Am
I/ActivityManager(  953): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
D/ActivityManager(  953): setTaskToReturnTo : TaskRecord{2c14fd4d #224 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  953): setTaskToReturnTo : TaskRecord{2c14fd4d #224 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
V/AudioPolicyService(  280): registerClient() client 0xb57e9460, uid 10079
W/AudioManagerAndroid( 5024): Requires BLUETOOTH permission
D/WindowStateEx(  953): AppWindowTokenEx init.. 
D/ContextHelper(  953): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
I/PhoneWindow(  953): [generateLayout] setColorNavigationBar => color=0x ff000001
I/[LGHome]EVENT( 1875): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  953): Focus left window: Window{17bd7344 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 5062): Shutting down VM
D/PhoneWindowEx(  953): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  953): [setNavigationBarColor2] color=0x fff5f5f5
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/SplitWindow(  953): check instance of lgWin Window{3ea1567 u0 Starting com.test.thalitest}
I/ActivityManager(  953): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5137 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/art     ( 5065): CheckpointMarkThreadRoots callback created = 0xb04d3e40
I/NSApplication( 5024): Starting up...
I/[LGHome]EVENT( 1875): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/art     ( 5065): CheckpointMarkThreadRoots callback created = 0xb04d3e30
I/ActivityManager(  953): Process com.lge.email (pid 4865) has died
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  953): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/HotwordDetector( 1935): Closing mic
,I/MicrophoneInputStream( 1935): mic_close com.google.android.apps.gsa.speech.audio.u@f8367a7
,V/AudioRecord( 1935): stop()
D/AudioRecord( 1935): AudioRecord->stop()
V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/WindowStateAnimator(  953): Starting window displayed
,D/WindowManager(  953): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/SystemUI[Framework](  953): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
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
W/PhoneWindowManagerEx(  953): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  953): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  953): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  953): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@270d821a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  953): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb386c000
,I/[LGHome]EVENT( 1875): [Launcher.java:5214:onStop()]onStop
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
D/administrator(  953): Handling package changes for user 0
,V/audio_hw_primary(  280): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  280): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  280): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  280): disable_audio_route: reset and update mixer path: audio-record
,V/audio_hw_primary(  280): disable_audio_route: exit
E/audio_hw_primary(  280): disable_snd_device: enter 144
D/hardware_info(  280): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  280): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  280): stop_input_stream: exit: status(0)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
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
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb386c000
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
I/ActivityManager(  953): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5154 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourceType(  953): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/NotificationService(  953): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,D/BackupManagerService(  953): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  953): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  953): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
V/AudioRecord( 1935): stop()
I/[SystemUI]NavigationThemeResource( 1374): notify navigation bar color(0xfff5f5f5)
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
V/AudioRecord( 1935): stop()
V/AudioRecord( 1935): stop()
V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
V/AudioPolicyManager(  280): releaseInput() 17
V/AudioPolicyManager(  280): closeInput(17)
V/AudioFlinger(  280): closeInput() 17
V/AudioSystem(  280): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  953): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): ThreadBase::exit
V/AudioSystem( 2027): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioSystem( 1374): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): RecordThread 0xb386c000 exiting
V/AudioSystem( 1750): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1935): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2700): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3115): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  280): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  280): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioPolicyService(  280): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  280): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio port list
V/AudioPolicyManager(  280): releaseInput() exit
V/AudioFlinger(  280): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  280): removeClient_l() pid 1935, calling pid 280
,V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioFlinger(  280): releasing 16 from 1935 for -1
V/AudioFlinger(  280):  decremented refcount to 0
V/AudioFlinger(  280): purging stale effects
I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
I/art     ( 1785): CheckpointMarkThreadRoots callback created = 0xb042d300
,I/HotwordRecognitionRnr( 1935): Stopping hotword detection.
I/HotwordRecognitionRnr( 1935): Hotword detection finished
,D/LocationProviderProxy(  953): applying state to connected service
I/art     ( 1785): CheckpointMarkThreadRoots callback created = 0xaaf71710
,I/art     ( 4027): Explicit concurrent mark sweep GC freed 2841(112KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.303ms total 42.640ms
,V/BackupManagerService(  953): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  953): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3aab0c58
I/art     ( 1785): Background partial concurrent mark sweep GC freed 53342(3MB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/14MB, paused 18.596ms total 98.715ms
D/ContextHelper( 5137): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/WebViewFactory( 5137): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5137): Time to load native libraries: 3 ms (timestamps 4157-4160)
I/LibraryLoader( 5137): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5137): Binding Chromium to main looper Looper (main, tid 1) {2f863d41}
I/LibraryLoader( 5137): Expected native library version number "",actual native library version number ""
I/chromium( 5137): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 5137): Initializing chromium process, singleProcess=true
W/art     ( 5137): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5137): ApplicationContext is null in ApplicationStatus
I/dex2oat ( 5176): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/chromium( 5137): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5137): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5137): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5137): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5137): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5137): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5137): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5137): Remote Branch: 
I/Adreno-EGL( 5137): Local Patches: 
I/Adreno-EGL( 5137): Reconstruct Branch: 
,I/dex2oat ( 5176): dex2oat took 93.384ms (threads: 4)
,I/Adreno-EGL( 5065): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5065): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5065): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5065): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5065): Remote Branch: 
I/Adreno-EGL( 5065): Local Patches: 
I/Adreno-EGL( 5065): Reconstruct Branch: 
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
,V/AudioPolicyService(  280): registerClient() client 0xb4027520, uid 10316
D/BluetoothManagerService(  953): Message: 20
,D/BluetoothManagerService(  953): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ed79d0f:true
D/BluetoothAdapterService(1051079380)( 2027): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29a582ca
,I/ActivityManager(  953): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5201 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/art     ( 5137): Attempt to remove local handle scope entry from IRT, ignoring
,I/Adreno-EGL( 5065): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5065): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5065): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5065): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5065): Remote Branch: 
I/Adreno-EGL( 5065): Local Patches: 
I/Adreno-EGL( 5065): Reconstruct Branch: 
W/AwContents( 5137): onDetachedFromWindow called when already detached. Ignoring
,I/PhoneWindow( 5137): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 5137): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 5137): [setNavigationBarColor2] color=0x fff5f5f5
,D/SystemWebViewEngine( 5137): CordovaWebView is running on device made by: LGE
,W/art     ( 5137): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5137): Attempt to remove local handle scope entry from IRT, ignoring
,I/Adreno-EGL( 5065): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5065): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5065): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5065): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5065): Remote Branch: 
I/Adreno-EGL( 5065): Local Patches: 
I/Adreno-EGL( 5065): Reconstruct Branch: 
,I/ActivityManager(  953): Process com.lge.appbox.client (pid 4900) has died
,I/Activity( 5137): Activity.onPostResume() called 
,D/OpenGLRenderer( 5137): Render dirty regions requested: true
I/OpenGLRenderer( 5137): Initialized EGL, version 1.4
D/OpenGLRenderer( 5137): Enabling debug mode 0
W/ResourcesManager( 5201): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/Atlas   ( 5137): Validating map...
,D/SplitWindow(  953): check instance of lgWin Window{35fe7ff u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5137): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  953): Focus entered window: Window{35fe7ff u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  953): Process com.lge.sync (pid 4768) has died
,I/ActivityManager(  953): Displayed com.test.thalitest/.MainActivity: +1s526ms
I/Timeline(  953): Timeline: Activity_windows_visible id: ActivityRecord{20ab8002 u0 com.test.thalitest/.MainActivity t224} time:74956
W/InputMethodManagerService(  953): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/CheckinRequestBuilder( 4338): Classify the device as Phone.
,I/Timeline( 5137): Timeline: Activity_idle id: android.os.BinderProxy@eb027b3 time:74997
,W/BindingManager( 5137): Cannot call determinedVisibility() - never saw a connection for the pid: 5137
,D/libc-netbsd( 4338): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4338): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4338): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4338): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 4338): propertyValue:false
D/JsMessageQueue( 5137): Set native->JS mode to OnlineEventsBridgeMode
,D/libc-netbsd( 4338): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4338): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4338): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4338): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4338): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4338): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4338): Sending checkin request (7705 bytes)
,I/ActivityManager(  953): Process com.lge.lgdmsclient (pid 4657) has died
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  953): Process com.google.android.setupwizard (pid 4930) has died
,I/WVCdm   (  280): CdmEngine::CloseSession
,I/WVCdm   (  280): L3 Terminate.
I/art     ( 5201): CheckpointMarkThreadRoots callback created = 0xaaf05460
,I/iu.SyncManager( 4338): SYNC; picasa accounts
I/art     ( 5201): CheckpointMarkThreadRoots callback created = 0xaaf05440
,D/NetworkLogImpl( 4338): Loaded NetworkSpeedPredictor
,D/jxcore_app_log( 5137): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426384768
I/iu.Environment( 4338): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5137): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5137):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5137):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5137):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5137):     - Handshake required: false
,I/iu.UploadsManager( 4338): num queued entries: 0
I/iu.UploadsManager( 4338): num updated entries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5137): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a89ed5d added. We now have 1 listener(s)
I/iu.SyncManager( 4338): NEXT; no task
D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5137): setBluetoothMacAddress: F8:95:C7:87:85:54
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5137): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5137): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5137): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5137):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5137):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5137):     - Bluetooth MAC address: F8:95:C7:87:85:54
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5137):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5137):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5137):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5137):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5137):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5137):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5137): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7d0259 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5137): addListener: New listener added - the number of listeners is now 1
D/BluetoothAdapterService(1051079380)( 2027): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29a582ca
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5137): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 5137): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 5137): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 5137): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 5137): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 5137): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 5137): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 5137): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 5137): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 5137): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 5137): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 5137): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 5137): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5137): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5137): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  953): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5250 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
D/JX-Cordova( 5137): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5137): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5137): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31c74e1e added. We now have 2 listener(s)
,D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5137): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5137): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5137): load: Already loaded
I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 338us total 27.309ms
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5137): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34dd96ff added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5137): addListener: New listener added - the number of listeners is now 1
D/BluetoothAdapterService(1051079380)( 2027): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29a582ca
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5137): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 5137): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 5137): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 5137): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 5137): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
,W/System.err( 5137): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 5137): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 5137): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 5137): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 5137): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 5137): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 5137): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 5137): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5137): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5137): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 23.592ms
,I/CheckinRequestBuilder( 4338): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4338): Failed to find provider info for com.google.android.wearable.settings
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 275us total 25.139ms
,W/ResourcesManager( 5250): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 4338): Classify the device as Phone.
,I/CheckinTask( 4338): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4338): Checking schedule, now: 1457354185708 next: 1457881434699
I/CheckinService( 4338): active receiver: disabled
D/BluetoothManagerService(  953): Message: 20
,D/BluetoothManagerService(  953): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17f2bc85:true
D/BluetoothAdapterService(1051079380)( 2027): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29a582ca
D/BluetoothAdapterService(1051079380)( 2027): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29a582ca
D/CheckinService( 4338): Recording last checkin time for package unspecified as 1457354185735
,I/ActivityManager(  953): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=5270 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 5270): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 2683): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:36:25
D/UpdateThreadPoolManager( 2683): 2 : This is isUpdating : false
D/Weather_cast( 2683): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2683): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:36:25
D/WeatherService( 2683): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
,W/ActivityManager(  953): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2683): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2683): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2683): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
V/SmsReceiverService( 3115): onStart: #1 mResultCode: -1 = Activity.RESULT_OK
,D/MmsConfig( 3115): isNotAllowedSms: currentUser:0
D/MmsConfig( 3115): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3115): isUserMode:false
D/SmsReceiverService( 3115): handleMessage isUserMode:false
I/[LGHome]LGNumberBadgeReceiver( 1875): [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = lge.intent.action.UNREAD_MESSAGES
V/SmsReceiverService( 3115): handleMessage action: com.android.mms.transaction.SEND_MESSAGE error: 0
,D/SmsReceiverService( 3115): [LGE] handleSendMessage Send messages in queue
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1875): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1875): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1875): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1875): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
I/ActivityManager(  953): Process com.google.android.talk (pid 4981) has died
I/art     (  953): Explicit concurrent mark sweep GC freed 31816(1686KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 7.724ms total 188.152ms
,I/ActivityManager(  953): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=5292 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,V/AlarmManager(  953): ELAPSED_WAKEUP set : Alarm{2e2beaa6 type 2 when 76668 android} when 76668
,W/ResourcesManager( 5292): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5292): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5292): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5292): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5292): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 5292): Using schema version: 115
,I/IndexDatabaseHelper( 5292): Index is fine
I/ActivityManager(  953): Process com.lge.drmservice (pid 4960) has died
,D/UsbSettingsReceiver( 5292): [AUTORUN] onReceive() : action = android.hardware.usb.action.USB_STATE
D/UsbSettingsReceiver( 5292): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5292): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5292): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 5292): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsReceiver( 5292): [AUTORUN] onReceive() : getDefaultFunction = ptp_only
D/UsbSettingsReceiver( 5292): [AUTORUN] onReceive() : USB_FUNCTION_CDROM_STORAGE = false
D/UsbSettingsReceiver( 5292): [AUTORUN] onReceive() : mDirectAutorun = true
D/UsbSettingsReceiver( 5292): [AUTORUN] onReceive() : mActivityUsbModeChange = false
D/UsbSettingsReceiver( 5292): [AUTORUN] onReceive() : mActivityFinish = false
D/UsbSettingsReceiver( 5292): [AUTORUN] onReceive() : ===== USB Configured =====
,D/UsbSettingsControl( 5292): [AUTORUN] setUsbConnected() : connected=true
D/UsbSettingsReceiver( 5292): [AUTORUN] onReceive() : checkQmicm = ptp_only,adb
D/UsbSettingsReceiver( 5292): [AUTORUN] : topPackageName=com.test.thalitest
D/UsbSettingsReceiver( 5292): [AUTORUN] : topClassName=com.test.thalitest.MainActivity
D/UsbSettingsReceiver( 5292): [AUTORUN] Not exist com.android.LGSetupWizard
D/UsbSettingsReceiver( 5292): [AUTORUN] setUsbConnect() : mUsbSettingsRun = false
D/UsbSettingsReceiver( 5292): [AUTORUN] startUsbSettings() : deviceProvisioned=1
,I/ActivityManager(  953): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5314 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/MtpService( 3168): updating state; isCurrentUser=true, mMtpLocked=false
,I/PCSuite ( 5314): [StartReceiver]USB CONNECTED ver UsbManger : ptp_only
I/PCSuite ( 5314): [StartReceiver]isUsbPCSuiteMode : false
,D/PCSuite ( 5314): [StartReceiver][checkEUTStatus] eutStatus = 
D/PCSuite ( 5314): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5314): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/LGMDMManager( 5250): Create singleton instance
,I/DigitalAppWidgetProvider( 5270): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 2683): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:36:26
D/UpdateThreadPoolManager( 2683): 2 : This is isUpdating : false
D/Weather_cast( 2683): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2683): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:36:26
D/WeatherService( 2683): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
,W/ActivityManager(  953): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2683): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2683): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2683): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/AlertReceiver( 3831): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
D/AlertService( 3831): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 3831): [updateWidgets] 
,D/MonthWidgetProvider( 3831): [onReceive]
D/CalendarWidgetProvider( 3831): [onReceive]
D/CalendarWidgetProvider( 3831): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 3831): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 3831): [onReceive]
D/CalendarWidgetProvider( 3831): [onReceive]
D/CalendarWidgetProvider( 3831): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 3831): [onCreate] mContext.getPackageName() = com.android.calendar
,I/[SystemUI]SafeModeBroadcastReceiver( 1374): onReceive = com.lge.statusbar.bootcompleted
,D/CalendarWeatherReceiver( 3831): Get action=com.lge.calendar.action.WEATHER_SERVICE_START
I/ActivityManager(  953): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.MediaScanReceiver: pid=5335 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  953): Process com.google.android.apps.magazines (pid 5024) has died
,E/MediaScanReceiver( 5335): media scanning start or checking
,W/MainApplication( 5335): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/ActivityManager(  953): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5352 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  953): Process com.google.android.apps.plus (pid 5201) has died
,I/MusicStore( 5352): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5352): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5352): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5352): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 5352): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5352): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5352): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,W/ActivityThread( 5352): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5352): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@10d750ad: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5352): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5352): GMSCore installation verified
I/ConfigStore( 5352): Config Database version: 1
,I/MediaRouter( 5352): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/ToneMappingReceiver( 5270): Enter doAlarmRingToneUriMapping()
,I/NetworkMonitor( 5352): type=WIFI subType= reason=null isConnected=true
,D/ToneMappingReceiver( 5270): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5270): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/CommonUtil( 5270): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5270): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5270): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5270): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5270): Alarm Success count is 0
D/ToneMappingReceiver( 5270): Timer Success count is 0
I/MediaScannerReceiver( 3831): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///system/media
,E/MediaScanReceiver( 5335): media scanning finished
I/InitNotificationRingtoneService( 3831): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3831): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/com.lge.bnr.receiver.MediaScanReceiver( 5335): android.intent.action.MEDIA_SCANNER_FINISHED
I/NetworkMonitor( 5352): type=WIFI subType= reason=null isConnected=true
,I/AlertUtils( 3831): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/GHttpClientFactory( 5352): Using our fixed implementation of GMSCore's GoogleHttpClient
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/GoogleURLConnFactory( 5352): Using platform SSLCertificateSocketFactory
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,E/MediaScanReceiver( 5335): media scanning start or checking
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3831): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 3831): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3831): End InitializeAlertRingtoneService.onHandleIntent
I/NotificationManager( 5352): com.google.android.music: cancel(1061) by com.google.android.music
,D/ToneMappingReceiver( 5270): Enter doAlarmRingToneUriMapping()
D/ToneMappingReceiver( 5270): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5270): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5270): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5270): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5270): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5270): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5270): Alarm Success count is 0
D/ToneMappingReceiver( 5270): Timer Success count is 0
I/MediaScannerReceiver( 3831): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///storage/emulated/0
,E/MediaScanReceiver( 5335): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 5335): android.intent.action.MEDIA_SCANNER_FINISHED
I/InitNotificationRingtoneService( 3831): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3831): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/AlertUtils( 3831): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/ActivityManager(  953): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5402 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3831): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3831): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,I/AlertUtils( 3831): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3831): End InitializeAlertRingtoneService.onHandleIntent
,W/ResourcesManager( 5402): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/art     ( 5352): CheckpointMarkThreadRoots callback created = 0xb042d400
D/CalendarProvider2( 5402): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@ded4a2f
,I/art     ( 5352): CheckpointMarkThreadRoots callback created = 0xb042d3d0
,D/CalendarProvider2( 5402): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5402): Created com.android.providers.calendar.CalendarAlarmManager@28a17c28(com.android.providers.calendar.CalendarProvider2@ded4a2f)
,D/CalendarProviderBroadcastReceiver( 5402): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5402): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 5402): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 5402): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5402): [getOrCreateCalendarAlarmManager]
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1732): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 4338): Restart initialization of location
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
I/MediaStoreImporter( 5352): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  953): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5425 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/CalendarProvider2( 5402): [IntentService] Release Lock
,D/CalendarProvider2( 5402): CalendarProviderIntentService.onDestroy()
,I/art     ( 4338): Explicit concurrent mark sweep GC freed 24799(1961KB) AllocSpace objects, 32(512KB) LOS objects, 39% free, 11MB/19MB, paused 1.267ms total 102.417ms
,I/art     (  953): Explicit concurrent mark sweep GC freed 14400(781KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 3.876ms total 156.511ms
,V/AlarmManager(  953): RTC_WAKEUP set : Alarm{721b6ec type 0 when 1457354188508 com.google.android.googlequicksearchbox} when 1457354188508
W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/IcingInternalCorpora( 4338): getNumBytesRead when not calculated.
,I/Gmail   ( 5425): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5425): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5425): Error finding the version of the Email provider.....
E/Gmail   ( 5425): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5425): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5425): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5425): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5425): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5425): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5425): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5425): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 5425): We do not support migrating this version of the Email provider.
I/Gmail   ( 5425): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  953): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 5425): Observing account changes for notifications
,W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1732): location=null
I/ActivityManager(  953): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5474 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Gmail   ( 5425): notifyAccountChanged
I/Gmail   ( 5425): getAccountsCursor
,I/Gmail   ( 5425): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5425): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5425): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5425): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5425): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PhoneMonitor( 5474): Register our PhoneStateListener
,I/ActivityManager(  953): Killing 3663:com.android.defcontainer/u0a4 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10004/pid_3663/cgroup.procs: No such file or directory
,D/PhoneMonitor( 5474): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/CheckinService( 4338): Checkin interval check for package: unspecified last checkin: 1457354185735 min interval config: 0 actual interval: 3457
V/TelephonyAutoProfiling( 5474): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5474): [parse] Load xml
I/CheckinService( 4338): Checking schedule, now: 1457354189198 next: 1457354215699
I/CheckinService( 4338): active receiver: disabled
,V/TelephonyAutoProfiling( 5474): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 5474): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 5474): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  953): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5500 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,V/DownloadManager( 3168): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3168): created cursor android.database.sqlite.SQLiteCursor@2c7d0259 on behalf of 4338
,W/ResourcesManager( 5500): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 4027): Explicit concurrent mark sweep GC freed 3184(126KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 731us total 31.989ms
,V/DownloadManager( 3168): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3168): created cursor android.database.sqlite.SQLiteCursor@31c74e1e on behalf of 4338
V/DownloadManager( 3168): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3168): created cursor android.database.sqlite.SQLiteCursor@34dd96ff on behalf of 4338
I/ActivityManager(  953): Killing 5154:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10048/pid_5154/cgroup.procs: No such file or directory
,W/ProcessCpuTracker(  953): Skipping unknown process pid 5388
W/ProcessCpuTracker(  953): Skipping unknown process pid 5391
,I/Babel_SMS( 5500): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5500): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5500): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5500): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5500): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5500): MmsConfig.loadFromResources
E/Babel_SMS( 5500): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5500): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 5500): CheckpointMarkThreadRoots callback created = 0xb042d870
,D/SensorManager( 5500): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5500): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5500): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 5500): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5500): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5500): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5500): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5500): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5500): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5500): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5500): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5500): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5500): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5500): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5500): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5500): found sensor: Motion Accel, handle=46
I/art     ( 5500): CheckpointMarkThreadRoots callback created = 0xb042d850
,I/ActivityManager(  953): Process com.lge.bnr (pid 5335) has died
,W/Settings( 5500): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5500): startup - clean
I/Babel   ( 5500): deleted: false for 0
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,W/AudioCapabilities( 5500): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5500): Unsupported mime audio/adpcm
W/AudioCapabilities( 5500): Unsupported mime audio/g726
W/AudioCapabilities( 5500): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5500): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 5500): Unsupported mime video/mjpg
W/VideoCapabilities( 5500): Unsupported mime video/theora
,I/chromium( 5137): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 5137): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
W/AudioCapabilities( 5500): Unsupported mime audio/evrc
W/AudioCapabilities( 5500): Unsupported mime audio/qcelp
W/VideoCapabilities( 5500): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5500): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5500): Unsupported mime audio/qcelp
W/AudioCapabilities( 5500): Unsupported mime audio/evrc
W/VideoCapabilities( 5500): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5500): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5500): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5500): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5500): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5500): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 5500): onServiceConnected
W/Babel   ( 5500): Attempted to change video mute state without an active call.
,W/ResourcesManager( 5500): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5500): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5500): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  953): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5536 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/System  ( 5500): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5500): Installed default security provider GmsCore_OpenSSL
,I/AudioManager( 5250): getMode name:com.lge.qremote
I/AudioManager( 5250): getMode name:com.lge.qremote
,I/AudioManager( 5250): getMode name:com.lge.qremote
,I/NotificationManager( 5500): com.google.android.talk: cancel(10436) by com.google.android.talk
I/AudioManager( 5250): getMode name:com.lge.qremote
,I/AudioManager( 5250): getMode name:com.lge.qremote
D/UEI.SmartControl( 5536): Quickset Services start...
,I/UEI.SmartControl( 5536): Manufacture = LGE
D/UEI.SmartControl( 5536): File observer start...
E/UEI.SmartControl( 5536): IR Port is disabled: false
D/UEI.SmartControl( 5536): Starting file observer...
D/UEI.SmartControl( 5536): Extracting JNI libs...
D/UEI.SmartControl( 5536): --- this system supports 32-bit or 64-bit only
I/ActivityManager(  953): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5556 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 21.514ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 21.586ms
,W/ResourcesManager( 5556): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5556): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5556): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 21.111ms
,D/UEI.SmartControl( 5536): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5536): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5536): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/LGEmail ( 5556): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,I/UEI.SmartControl( 5536): --- Selecting new region: 2
,I/UEI.SmartControl( 5536): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5536): Platform has CIR...
D/UEI.SmartControl( 5536): NO CIR support, need to check package...
D/LGEmail ( 5556): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/UEI.SmartControl( 5536): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5536): QS Service created
,I/art     (  953): Explicit concurrent mark sweep GC freed 15227(726KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.512ms total 146.461ms
E/UEI.SmartControl( 5536): QS start get config
,I/PackageChangeReceiver( 5556): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,D/UEI.SmartControl( 5536): Loading JNI Libs...
,D/UEI.SmartControl( 5536):  configuring local db...
I/ActivityManager(  953): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5577 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  953): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5597 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  953): Killing 5292:com.android.settings/1000 (adj 15): empty #11
,D/UEI.SmartControl( 5536):  ---- Has DB8: true
,D/UEI.SmartControl( 5536): QS start statue = true Error code = 0
,D/UEI.SmartControl( 5536): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5536): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5536): IRRCDataComm has AudioManager!!!!.
W/libprocessgroup(  953): failed to open /acct/uid_1000/pid_5292/cgroup.procs: No such file or directory
,W/irrc_jni( 5536): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5536): IrrcClient ++ 
D/irrcClient( 5536): getIrrcService ++ 
D/irrcClient( 5536): getIrrcService -- 
D/irrcClient( 5536): IrrcClient -- 
W/irrc_jni( 5536): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5536): Services init done
,I/UEI.SmartControl( 5536): Device manager: loading config....
D/UEI.SmartControl( 5536): Config is loaded...
D/UEI.SmartControl( 5536): QS Service init finished
,D/UEI.SmartControl( 5536): QS Service version name: 0.1.73
I/AppUp4:AppBoxCP( 5597): onCreate
D/UEI.SmartControl( 5536):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 5536): QS Service version code: 1073
I/UEI.SmartControl( 5536): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5536): Service requested: Control
W/AppUp4:DB( 5597):  [AppBoxDatabaseHelper] construct
D/UEI.SmartControl( 5536): Internal service binding...
D/UEI.SmartControl( 5536): -----IControl: 11
D/UEI.SmartControl( 5536): Caller: com.lge.qremote
D/UEI.SmartControl( 5536): ------------ IControl registerCallback...
,I/UEI.SmartControl( 5536): Registering callback...
D/UEI.SmartControl( 5536): -----IControl: 19
D/UEI.SmartControl( 5536): Caller: com.lge.qremote
I/UEI.SmartControl( 5536): Registering Services Ready callback...
I/UEI.SmartControl( 5536): Notify client services are ready...
I/AppUp4:DB( 5597):  setFingerPrint start
I/AppUp4:DB( 5597):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
D/UEI.SmartControl( 5536): -----IControl: 8
D/UEI.SmartControl( 5536): Caller: com.lge.qremote
I/AppUp4:DB( 5597):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5597):  SDK version = 0
I/AppUp4:DB( 5597):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5597): AppBoxApplication onCreate()
I/ActivityManager(  953): Killing 5270:com.lge.clock/u0a10 (adj 15): empty #11
D/AppUp4:PreloadHelper( 5597): removed from Exclude : com.test.thalitest : 1
,I/ActivityManager(  953): Killing 5314:com.lge.sync/1000 (adj 15): empty #12
,W/libprocessgroup(  953): failed to open /acct/uid_10010/pid_5270/cgroup.procs: No such file or directory
,W/libprocessgroup(  953): failed to open /acct/uid_1000/pid_5314/cgroup.procs: No such file or directory
I/ActivityManager(  953): Killing 5352:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  953): failed to open /acct/uid_10081/pid_5352/cgroup.procs: No such file or directory
,I/ActivityManager(  953): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5617 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 5617): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5617): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5617): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 5617): Total System Memory = 906309632
,I/GalleryUtils( 5617): Application Heap = 96 MB
I/AppConfig( 5617): App Tier : NOT_DEF
D/SystemHelper( 5617): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  953): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5636 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  953): Killing 5402:com.android.providers.calendar/u0a14 (adj 15): empty #11
D/AlertService( 3831): Beginning updateAlertNotification
D/InitAlarmsService( 3831): Clearing and rescheduling alarms.
,E/lowmemorykiller(  243): Error opening /proc/5402/oom_score_adj; errno=2
,W/libprocessgroup(  953): failed to open /acct/uid_10014/pid_5402/cgroup.procs: No such file or directory
I/ActivityManager(  953): Killing 3831:com.android.calendar/u0a13 (adj 8): depends on provider com.android.providers.calendar/.CalendarProvider2 in dying proc com.android.providers.calendar
I/ActivityManager(  953): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5656 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup(  953): failed to open /acct/uid_10013/pid_3831/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/ActivityManager(  953): Scheduling restart of crashed service com.android.calendar/.alerts.AlertService in 10320ms
W/ActivityManager(  953): Scheduling restart of crashed service com.android.calendar/.alerts.InitAlarmsService in 20314ms
,I/ActivityManager(  953): Killing 5425:com.google.android.gm/u0a53 (adj 15): empty #11
W/ResourcesManager( 5636): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5636): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5636): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5636): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5636): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  953): failed to open /acct/uid_10053/pid_5425/cgroup.procs: No such file or directory
W/ResourcesManager( 5656): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5656): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@ded4a2f
,D/CalendarProvider2( 5656): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5656): Created com.android.providers.calendar.CalendarAlarmManager@28a17c28(com.android.providers.calendar.CalendarProvider2@ded4a2f)
I/SystemConfig( 5636): BUILD Country: EU
I/SystemConfig( 5636): BUILD Operator: OPEN
,I/ActivityManager(  953): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5676 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  953): Killing 5474:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10038/pid_5474/cgroup.procs: No such file or directory
,I/SystemConfig( 5636): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5636): existFile = false
I/SystemConfig( 5636): canReadFile = false
I/SystemConfig( 5636): systemFeature RCS result false
D/SystemConfig( 5636): refreshRcsSupport() :false
I/LockScreenSettings( 5676): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 5676): New app installed broadcast received ..
,I/LockScreenSettings( 5676): Number of installed packages  1
I/ActivityManager(  953): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5693 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  953): Killing 5065:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10006/pid_5065/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 5693): action : android.intent.action.PACKAGE_ADDED
,D/EulaProviderUpdateObserver( 5693): uri : package:com.test.thalitest
,I/ActivityManager(  953): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5710 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  953): Killing 4027:com.google.process.gapps/u0a6 (adj 15): empty #11
W/libprocessgroup(  953): failed to open /acct/uid_10006/pid_4027/cgroup.procs: No such file or directory
,D/[BNRAppListMgrReceiver]( 5710): android.intent.action.PACKAGE_ADDED : com.test.thalitest
,W/MainApplication( 5710): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ActivityManager(  953): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5728 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  953): Killing 5536:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 5250): android.os.DeadObjectException
,W/System.err( 5250): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5250): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5250): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5250): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5250): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5250): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5250): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5250): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5250): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5250): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5250): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5250): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5250): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5250): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5250): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5250): android.os.DeadObjectException
W/System.err( 5250): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5250): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5250): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5250): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5250): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5250): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5250): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5250): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5250): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5250): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5250): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5250): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5250): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5250): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5250): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/CheckinService( 4338): Done disabling old GoogleServicesFramework version
,W/libprocessgroup(  953): failed to open /acct/uid_10089/pid_5536/cgroup.procs: No such file or directory
,W/ActivityManager(  953): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 19433ms
I/ActivityManager(  953): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5746 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 5746): Quickset Services start...
I/UEI.SmartControl( 5746): Manufacture = LGE
,D/UEI.SmartControl( 5746): File observer start...
E/UEI.SmartControl( 5746): IR Port is disabled: false
D/UEI.SmartControl( 5746): Starting file observer...
D/UEI.SmartControl( 5746): Extracting JNI libs...
D/UEI.SmartControl( 5746): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 5746): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5746): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5746): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 5746): --- Selecting new region: 2
I/UEI.SmartControl( 5746): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5746): Platform has CIR...
D/UEI.SmartControl( 5746): NO CIR support, need to check package...
I/UEI.SmartControl( 5746): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5746): QS Service created
I/ActivityManager(  953): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5764 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 25.268ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 22.219ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 31.368ms
,E/UEI.SmartControl( 5746): QS start get config
,I/GservicesProvider( 5764): Gservices pushing to system: true; secure/global: true
D/UEI.SmartControl( 5746): Loading JNI Libs...
,D/UEI.SmartControl( 5746):  configuring local db...
I/GoogleHttpClient( 5764): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5764): GMS http client unavailable, use old client
,D/Finsky  ( 5728): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 5746):  ---- Has DB8: true
,D/UEI.SmartControl( 5746): QS start statue = true Error code = 0
D/UEI.SmartControl( 5746): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5746): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5746): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5746): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5746): IrrcClient ++ 
D/irrcClient( 5746): getIrrcService ++ 
D/irrcClient( 5746): getIrrcService -- 
D/irrcClient( 5746): IrrcClient -- 
W/irrc_jni( 5746): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5746): Services init done
,I/UEI.SmartControl( 5746): Device manager: loading config....
D/UEI.SmartControl( 5746): QS Service init finished
D/UEI.SmartControl( 5746): QS Service version name: 0.1.73
D/UEI.SmartControl( 5746): QS Service version code: 1073
D/UEI.SmartControl( 5746): Config is loaded...
D/UEI.SmartControl( 5746): Service requested: Control
,I/ActivityManager(  953): Killing 5250:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 5746): -----IControl: 11
D/UEI.SmartControl( 5746): Caller: com.lge.qremote
D/UEI.SmartControl( 5746): ------------ IControl registerCallback...
I/UEI.SmartControl( 5746): Registering callback...
,D/UEI.SmartControl( 5746):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 5746): Notify AllClients services are ready: 0
W/libprocessgroup(  953): failed to open /acct/uid_10106/pid_5250/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 5746): Internal service binding...
,D/Finsky  ( 5728): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5728): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5728): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 5728): com.android.vending: cancel(-1050172287) by com.android.vending
I/NotificationManager( 1935): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,V/DownloadManager( 3168): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3168): created cursor android.database.sqlite.SQLiteCursor@e952ccc on behalf of 5728
I/NotificationManager( 5728): com.android.vending: cancel(1003285959) by com.android.vending
,D/Ads     ( 5728): Skipping gmscore version check
,I/ActivityManager(  953): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5820 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,D/Finsky  ( 5728): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5728): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 5728): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ActivityManager(  953): Killing 5556:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10021/pid_5556/cgroup.procs: No such file or directory
,D/Finsky  ( 5728): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  953): Killing 5577:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10009/pid_5577/cgroup.procs: No such file or directory
,D/Finsky  ( 5728): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  953): Killing 5597:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10011/pid_5597/cgroup.procs: No such file or directory
,I/GAv4    ( 5820): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5820):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5820):   adb logcat -s GAv4
,W/GAv4    ( 5820): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5820): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5820): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5820): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5820): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 5820): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5820): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  953): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5868 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  953): Killing 5617:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10023/pid_5617/cgroup.procs: No such file or directory
I/art     ( 5820): CheckpointMarkThreadRoots callback created = 0xaaf26210
W/ResourcesManager( 5868): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/JNIHelp ( 5820): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/art     ( 5820): CheckpointMarkThreadRoots callback created = 0xb050ea70
W/System  ( 5820): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5820): Installed default security provider GmsCore_OpenSSL
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  953): Killing 5636:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  953): failed to open /acct/uid_10018/pid_5636/cgroup.procs: No such file or directory
D/PackageBroadcastService( 4338): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 4338): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4338): Loading module APK com.google.android.play.games
I/UpdateIcingCorporaServi( 1935): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1935): UpdateCorporaTask done [took 108 ms] updated apps [took 108 ms] 
,D/ChimeraCfgMgr( 4338): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4338): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4338): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/Icing   ( 4338): Storage manager: low false usage 1.69MB avail 2.37GB capacity 4.06GB
,D/AsyncTaskServiceImpl( 4338): Submit a task: k
,D/ChimeraCfgMgr( 4338): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 4338): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 4338): Processing package: com.test.thalitest
,I/PeopleDatabaseHelper( 4338): cleanUpNonGplusAccounts done.
,D/GassUtils( 4338): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 4338): Found info for package com.test.thalitest in db.
I/ActivityManager(  953): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5927 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  953): Reconfiguring input devices.  changes=0x00000010
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/administrator(  953): Handling package changes for user 0
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
W/BaseAppContext( 4338): Using Auth Proxy for data requests.
W/BaseAppContext( 4338): Using Auth Proxy for data requests.
,W/BaseAppContext( 4338): Using Auth Proxy for data requests.
W/BaseAppContext( 4338): Using Auth Proxy for data requests.
,W/BaseAppContext( 4338): Using Auth Proxy for data requests.
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationService(  953): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  953): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  953): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  953): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  953): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  953): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@aa1f73
,W/ResourcesManager( 5927): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/BluetoothManagerService(  953): Message: 20
D/BluetoothManagerService(  953): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b2abf06:true
,D/BluetoothAdapterService(1051079380)( 2027): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29a582ca
,D/BluetoothAdapterService(1051079380)( 2027): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29a582ca
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,E/MDM     ( 1732): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4338): Restart initialization of location
,W/ResourcesManager(  953): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,I/art     (  953): Explicit concurrent mark sweep GC freed 29277(1419KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 6.463ms total 204.309ms
,I/ActivityManager(  953): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5955 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ResourceType(  953): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1732): location=null
W/ResourcesManager( 5500): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5500): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/NotificationManager( 5500): com.google.android.talk: cancel(8) by com.google.android.talk
,D/LocationProviderProxy(  953): applying state to connected service
I/AppUp4:AppBoxCP( 5955): onCreate
W/AppUp4:DB( 5955):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 5955):  setFingerPrint start
I/AppUp4:DB( 5955):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5955):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5955):  SDK version = 0
I/AppUp4:DB( 5955):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5955): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 5955): onReceive
I/AppUp4:CustModeStarterReceiver( 5955): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 5955): Context : android.app.ReceiverRestrictedContext@3b371f1a
D/AppUp4:CustFacade( 5955): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5955): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5955): begin check event
I/AppUp4:CustModeStarterReceiver( 5955): Event For Nothing, skip.
,I/ActivityManager(  953): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5977 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/Icing   ( 4338): updateResources: need to parse f{com.google.android.gms}
W/ResourcesManager( 5977): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5977): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5977): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/AppConfig( 5977): Total System Memory = 906309632
,I/GalleryUtils( 5977): Application Heap = 96 MB
I/AppConfig( 5977): App Tier : NOT_DEF
D/SystemHelper( 5977): region [EU], country [EU], operator [OPEN], sub-operator []
,I/Icing   ( 4338): Internal init done: storage state 0
,I/Icing   ( 4338): Post-init done
,D/ChimeraCfgMgr( 4338): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4338): Module APK com.google.android.play.games already loaded
,I/ActivityManager(  953): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6000 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  953): Killing 5656:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/ActivityManager(  953): Process com.lge.bnr (pid 5710) has died
,W/libprocessgroup(  953): failed to open /acct/uid_10014/pid_5656/cgroup.procs: No such file or directory
W/ResourcesManager( 6000): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6000): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6000): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6000): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6000): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6000): BUILD Country: EU
I/SystemConfig( 6000): BUILD Operator: OPEN
,I/SystemConfig( 6000): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6000): existFile = false
I/SystemConfig( 6000): canReadFile = false
I/SystemConfig( 6000): systemFeature RCS result false
,D/SystemConfig( 6000): refreshRcsSupport() :false
D/LockScreenSettings( 5676): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5676): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5676): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5676): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5676): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/UpdateIcingCorporaServi( 1935): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 4338): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4338): Null package name or gms related package.  Ignoreing.
I/Icing   ( 4338): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  953): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6040 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1935): UpdateCorporaTask done [took 142 ms] updated apps [took 142 ms] 
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 29139(1933KB) AllocSpace objects, 26(416KB) LOS objects, 40% free, 13MB/22MB, paused 1.666ms total 134.354ms
I/ActivityManager(  953): Process com.google.android.apps.docs (pid 5820) has died
,D/PhoneMonitor( 6040): Register our PhoneStateListener
,V/SetupWizard( 6040): Connected to Gservices successfully
,D/PhoneMonitor( 6040): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6040): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6040): [parse] Load xml
,V/TelephonyAutoProfiling( 6040): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6040): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PhoneMonitor( 6040): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/LGMDMManager( 5927): Create singleton instance
,I/AudioManager( 5927): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5746): -----IControl: 11
,D/UEI.SmartControl( 5746): Caller: com.lge.qremote
D/UEI.SmartControl( 5746): ------------ IControl registerCallback...
I/UEI.SmartControl( 5746): Registering callback...
D/UEI.SmartControl( 5746): -----IControl: 19
D/UEI.SmartControl( 5746): Caller: com.lge.qremote
I/UEI.SmartControl( 5746): Registering Services Ready callback...
I/UEI.SmartControl( 5746): Notify client services are ready...
I/AudioManager( 5927): getMode name:com.lge.qremote
D/UEI.SmartControl( 5746): -----IControl: 8
,D/UEI.SmartControl( 5746): Caller: com.lge.qremote
I/ActivityManager(  953): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6068 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  953): Killing 5693:com.lge.eula/1000 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_1000/pid_5693/cgroup.procs: No such file or directory
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6068): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 4338): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,W/GAV2    ( 6068): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6068): Error finding the version of the Email provider.....
E/Gmail   ( 6068): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6068): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6068): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6068): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6068): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6068): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6068): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6068): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6068): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6068): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ActivityManager(  953): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/ActivityManager(  953): Killing 5955:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/Gmail   ( 6068): Observing account changes for notifications
D/Icing   ( 4338): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 4338): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,W/ActivityManager(  953): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/libprocessgroup(  953): failed to open /acct/uid_10011/pid_5955/cgroup.procs: No such file or directory
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AudioManager( 5927): getMode name:com.lge.qremote
,I/ActivityManager(  953): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6123 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,V/AlarmManager(  953): RTC_WAKEUP set : Alarm{9427367 type 0 when 1457354198267 com.android.vending} when 1457354198267
,I/NotificationManager( 5500): com.google.android.talk: cancel(8) by com.google.android.talk
D/Finsky  ( 5728): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,I/Gmail   ( 6068): notifyAccountChanged
I/Gmail   ( 6068): getAccountsCursor
I/Gmail   ( 6068): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6068): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/AppUp4:AppBoxCP( 6123): onCreate
W/AppUp4:DB( 6123):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6123):  setFingerPrint start
I/Gmail   ( 6068): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/NotificationManager(  953): android: cancelAsUser(2) by android
I/AppUp4:DB( 6123):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/Gmail   ( 6068): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/AppUp4:DB( 6123):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6123):  SDK version = 0
I/AppUp4:DB( 6123):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6123): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6123): onReceive
I/AppUp4:CustModeStarterReceiver( 6123): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6123): Context : android.app.ReceiverRestrictedContext@3b371f1a
D/AppUp4:CustFacade( 6123): isCustomizationCompleted : false
I/Icing   ( 4338): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/Icing   ( 4338): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,D/UEI.SmartControl( 5746): Internal timer expired: 1
,I/art     (  953): Explicit concurrent mark sweep GC freed 20001(983KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.164ms total 148.622ms
,D/AppUp4:CustFacade( 6123): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6123): begin check event
I/AppUp4:CustModeStarterReceiver( 6123): Event For Nothing, skip.
D/LockScreenSettings( 5676): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5676): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5676): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5676): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5676): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/UpdateIcingCorporaServi( 1935): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/libc-netbsd( 5728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  276): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
D/PackageBroadcastService( 4338): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/Gmail   ( 6068): getAccountsCursor
I/PackageBroadcastService( 4338): Null package name or gms related package.  Ignoreing.
I/AudioManager( 5927): getMode name:com.lge.qremote
I/System.out( 5728): propertyValue:false
D/libc-netbsd( 5728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AudioManager( 5927): getMode name:com.lge.qremote
,I/Icing   ( 4338): updateResources: need to parse f{com.google.android.gms}
I/UpdateIcingCorporaServi( 1935): UpdateCorporaTask done [took 49 ms] updated apps [took 49 ms] 
I/AudioManager( 5927): getMode name:com.lge.qremote
,I/AudioManager( 5927): getMode name:com.lge.qremote
,I/AudioManager( 5927): getMode name:com.lge.qremote
I/AudioManager( 5927): getMode name:com.lge.qremote
I/art     ( 4338): Explicit concurrent mark sweep GC freed 70021(4MB) AllocSpace objects, 29(464KB) LOS objects, 39% free, 14MB/23MB, paused 3.973ms total 114.360ms
,W/SQLiteConnectionPool( 4338): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/libc-netbsd( 5728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  953): android: cancelAsUser(2) by android
I/qtaguid ( 5728): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5728): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5728): untagSocket(41) failed with errno -22
,D/Finsky  ( 5728): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430700] >= Server Version [-1]
,I/ActivityManager(  953): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6172 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  953): android: cancelAsUser(2) by android
,W/ResourcesManager( 6172): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6172): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6172): VM with version 2.1.0 has multidex support
I/MultiDex( 6172): install
I/MultiDex( 6172): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6172): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6172): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6172): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d162e2a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6172): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6172): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6172): com.google.android.gms: cancel(39789) by com.google.android.gms
E/MDM     ( 1732): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/Icing   ( 4338): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/ChimeraCfgMgr( 6172): Reading stored module config
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 4338): Restart initialization of location
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
D/ChimeraCfgMgr( 6172): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
I/Icing   ( 4338): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,D/CAR.SERVICE( 6172): Connecting to CarCallService...
,I/art     ( 6172): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6172): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/NativeLibraryUtils( 6172): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6172): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6172): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6172): Creating a new PhoneAdapter instance
W/ActivityManager(  953): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6172): setListener: com.google.android.gms.car.dn@ddb9301
W/ActivityManager(  953): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6172): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6172): Starting CarCallService with initial phone null
I/NotificationManager( 6172): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/qtaguid ( 5728): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5728): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5728): untagSocket(41) failed with errno -22
D/CAR.SERVICE( 6172): Package validated; name: com.android.vending
,I/NotificationManager( 5728): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 5728): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/art     ( 5728): CheckpointMarkThreadRoots callback created = 0xb05a7580
,I/art     ( 5728): CheckpointMarkThreadRoots callback created = 0xb05a7540
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  953): android: cancelAsUser(2) by android
,I/qtaguid ( 5728): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5728): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5728): untagSocket(41) failed with errno -22
,W/ResourcesManager( 5728): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5728): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5728): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5728): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  953): RTC_WAKEUP set : Alarm{1c381c04 type 0 when 1457354201580 com.android.vending} when 1457354201580
D/DeviceConnectionService( 1732): client connected with version: 8296000
,D/Finsky  ( 5728): [679] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5728): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5728): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/NotificationManager(  953): android: cancelAsUser(2) by android
,D/libc-netbsd( 5728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5728): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5728): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  276): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 5728): propertyValue:false
,I/ActivityManager(  953): Waited long enough for: ServiceRecord{2c95ace7 u0 com.android.calendar/.alerts.AlertService}
,I/ActivityManager(  953): Killing 6123:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/ActivityManager(  953): Killing 6040:com.google.android.setupwizard/u0a38 (adj 15): empty #12
,W/libprocessgroup(  953): failed to open /acct/uid_10011/pid_6123/cgroup.procs: No such file or directory
,W/libprocessgroup(  953): failed to open /acct/uid_10038/pid_6040/cgroup.procs: No such file or directory
I/ActivityManager(  953): Start proc com.android.calendar for service com.android.calendar/.alerts.AlertService: pid=6232 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 283us total 26.840ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 21.716ms
W/ResourcesManager( 6232): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 24.377ms
,D/CalendarApplication( 6232): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6232): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6232): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@188dc9c5, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@3b371f1a, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2a0e5a4b, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@28a17c28, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2f863d41, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@41812e6, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@17e65027, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@3ea632d4, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@34386c7d, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@12c27772, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@115dc7c3, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3b9da840, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@ce45379, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@173c98be, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3c4b1d1f, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@33d5086c, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@29cdae35, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@29a582ca, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1b8e6c3b, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@11403f58, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@1b7f8b1, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@13010196, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@35ed9117, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@2725f904, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@1a226eed, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@16c3a122, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@eb027b3, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@148ba170, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@17440ce9, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@91ead6e, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@bfb8c0f, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@2161649c, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@fc78ea5, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3e0c327a, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@26eeda2b, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@26e2e88, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@20477021, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@1d1afc46, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@17eee07, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@2ffbab34, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3a89ed5d, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@25fa96d
D/GeneralP,referenceUtils( 6232): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6232): [init]
I/Config  ( 6232): LGCalendar ver.4.40.17
I/Config  ( 6232): start check model
I/Config  ( 6232): start check native_ca
I/Config  ( 6232): Config Operator=OPEN, Country=EU
,D/Config  ( 6232): [setDefaultValuesToPref]
D/Config  ( 6232): [parseProfiles]
D/ProfilesParser( 6232): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6232): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6232): [updateProfiletoCountryInfo]
D/GeneralPreference( 6232): [checkAndMigrateOldPreference]
I/InitNotificationRingtoneService( 6232): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6232): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,D/AlertService( 6232): 0 Action = android.intent.action.PROVIDER_CHANGED
I/AlertUtils( 6232): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6232): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6232): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6232): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6232): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6232): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6232): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6232): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6232): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6232): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6232): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6232): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6232): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6232): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6232): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6232): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6232): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6232): set default noti to content://media/internal/audio/media/38
,I/InitNotificationRingtoneService( 6232): End InitializeAlertRingtoneService.onHandleIntent
D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 93131151998; DSPS: 3150625; Offset : -3030368595
W/HolidayIntentService( 6232): onHandleIntent
D/HolidayDataLoader( 6232): readJsonAsset : holiday.json
E/HolidayIntentService( 6232): onHandleIntent:holiday data empty
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,I/GAV2    ( 6068): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  953): Killing 5500:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10061/pid_5500/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  953): Killing 5977:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10023/pid_5977/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 6172): mConnectedToCar = false, abort
,E/ActivityThread( 6172): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@35633c9 that was originally bound here
E/ActivityThread( 6172): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@35633c9 that was originally bound here
E/ActivityThread( 6172): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6172): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6172): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6172): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6172): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6172): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6172): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6172): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6172): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6172): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6172): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6172): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6172): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6172): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6172): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6172): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6172): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6172): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6172): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6172): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6172): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6172): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6172): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6172): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2dc390e8 that was originally bound here
E/ActivityThread( 6172): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2dc390e8 that was originally bound here
E/ActivityThread( 6172): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6172): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6172): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6172): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6172): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6172): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6172): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6172): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6172): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6172): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6172): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6172): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6172): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6172): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6172): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6172): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6172): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6172): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6172): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6172): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6172): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6172): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/ActivityManager(  953): Unbind failed: could not find connection for android.os.BinderProxy@2a5a6746
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/AlertService( 6232): Beginning updateAlertNotification
,I/ActivityManager(  953): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6277 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6277): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6277): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@ded4a2f
,D/CalendarProvider2( 6277): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6277): Created com.android.providers.calendar.CalendarAlarmManager@28a17c28(com.android.providers.calendar.CalendarProvider2@ded4a2f)
D/AlertService( 6232): No fired or scheduled alerts
I/NotificationManager( 6232): com.android.calendar: cancel(0) by com.android.calendar
,I/NotificationManager( 6232): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6232): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6232): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6232): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6232): com.android.calendar: cancel(5) by com.android.calendar
,I/NotificationManager( 6232): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6232): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6232): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6232): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6232): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6232): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6232): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6232): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6232): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6232): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6232): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6232): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6232): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6232): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6232): com.android.calendar: cancel(20) by com.android.calendar
,I/ThermalEngine(  294): Sensor:pa_therm0:33000 mC
,D/AlertService( 6232): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/ActivityManager(  953): Killing 6000:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10018/pid_6000/cgroup.procs: No such file or directory
,D/AlarmScheduler( 6232): No events found starting within 1 week.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/rmt_storage(  274): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  274): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  274): wakelock acquired: 1, error no: 42
,I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  274): 
I/rmt_storage(  274): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  953): RTC_WAKEUP set : Alarm{256b1959 type 0 when 1457354215699 com.google.android.gms} when 1457354215699
,V/AlarmManager(  953): RTC_WAKEUP set : Alarm{165b05ff type 0 when 1457354215794 com.android.vending} when 1457354215794
,I/CheckinService( 4338): Checkin interval check for package: unspecified last checkin: 1457354185735 min interval config: 0 actual interval: 33195
,W/ContextImpl( 3642): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/CheckinService( 4338): Checking schedule, now: 1457354218990 next: 1457354215699
I/CheckinService( 4338): active receiver: enabled
,I/CheckinService( 4338): Preparing to send checkin request
I/EventLogService( 4338): Accumulating logs since 1457354180031
,I/CheckinRequestBuilder( 4338): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4338): Failed to find provider info for com.google.android.wearable.settings
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/Finsky  ( 5728): [670] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 5728): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/art     (  953): Explicit concurrent mark sweep GC freed 21462(1000KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.254ms total 147.482ms
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  953): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6339 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 6339): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6339): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6339): VM with version 2.1.0 has multidex support
I/MultiDex( 6339): install
I/MultiDex( 6339): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6339): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6339): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6339): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d162e2a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6339): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6339): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6339): com.google.android.gms: cancel(39789) by com.google.android.gms
D/LocationInitializer( 4338): Restart initialization of location
,D/WearableService( 1732): callingUid 10006, callindPid: 1732
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
E/MDM     ( 1732): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,I/art     ( 6339): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6339): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6339): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  280): Instantiating CDM.
I/WVCdm   (  280): CdmEngine::OpenSession
I/WVCdm   (  280): Level3 Library Dec 11 2014 16:13:16
,W/WVCdm   (  280): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  280): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  280): L1 library not specified. Falling Back to L3
I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  280): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  280): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
D/WVCdm   (  280): PrepareKeyRequest: nonce=3967312527
,D/PowerManagerServiceEx(  953): acquireWakeLockInternal: lock=475988134, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=953
D/WeatherService( 2683): 2 : TimeTick Intent has been received, Time(hour:min:sec) 13:37:0
D/WeatherService( 2683): 2 : TimeTick Intent And Screen On
D/WeatherService( 2683): 2 : SDK version : 21
,W/ActivityManager(  953): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2683): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2683): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2683): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2683): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2683): 2 : This is isUpdating : false
D/WeatherService( 2683): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2683): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2683): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2683): 2 : Fixed theme : optimus
D/WeatherReflect( 2683): 2 : Map key string is -2
D/lim     ( 2683): 2 : time = 13:37
,I/WeatherReflect( 2683): Model Name : LG-D722
D/WeatherTheme( 2683): 2 : Different view - status_min_formatted : 36 != 37
,D/WeatherTheme( 2683): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2683): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2683): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2683): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
,I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/Weather4x2_optimus( 2683): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2683): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2683): forecast size is 0
D/Theme   ( 2683): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2683): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2683): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2683): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2683): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2683): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2683): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2683): url is : null
D/Theme   ( 2683): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2683): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2683): 2 : update view, appWidgetId: 2
,D/WeatherService( 2683): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 13:37:0
D/PowerManagerServiceEx(  953): releaseWakeLockInternal: lock=475988134 [*alarm*], flags=0x0
I/art     ( 6339): CheckpointMarkThreadRoots callback created = 0xb04d3f00
I/[SystemUI]DateView( 1374): called onTimeUpdated()
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/art     ( 6339): CheckpointMarkThreadRoots callback created = 0xb04d3ef0
,I/art     ( 6339): Background partial concurrent mark sweep GC freed 14827(895KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 10MB/16MB, paused 5.175ms total 33.726ms
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/dex2oat ( 6386): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6386): dex2oat took 113.008ms (threads: 4)
,I/Adreno-EGL( 6339): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6339): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6339): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6339): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6339): Remote Branch: 
I/Adreno-EGL( 6339): Local Patches: 
I/Adreno-EGL( 6339): Reconstruct Branch: 
,I/Adreno-EGL( 6339): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6339): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6339): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6339): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6339): Remote Branch: 
I/Adreno-EGL( 6339): Local Patches: 
I/Adreno-EGL( 6339): Reconstruct Branch: 
,I/Adreno-EGL( 6339): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6339): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6339): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6339): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6339): Remote Branch: 
I/Adreno-EGL( 6339): Local Patches: 
I/Adreno-EGL( 6339): Reconstruct Branch: 
,I/CheckinRequestBuilder( 4338): Classify the device as Phone.
,D/libc-netbsd( 4338): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4338): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4338): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4338): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 4338): propertyValue:false
D/libc-netbsd( 4338): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4338): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4338): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4338): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4338): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4338): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4338): Sending checkin request (7664 bytes)
I/CheckinRequestBuilder( 4338): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4338): Failed to find provider info for com.google.android.wearable.settings
,I/WVCdm   (  280): CdmEngine::CloseSession
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/WVCdm   (  280): L3 Terminate.
I/CheckinRequestBuilder( 4338): Classify the device as Phone.
,I/CheckinTask( 4338): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4338): Checking schedule, now: 1457354222129 next: 1457881471124
I/CheckinService( 4338): active receiver: disabled
,D/CheckinService( 4338): Recording last checkin time for package unspecified as 1457354222157
I/ActivityManager(  953): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6414 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6414): Register our PhoneStateListener
,V/SetupWizard( 6414): Connected to Gservices successfully
,D/PhoneMonitor( 6414): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6414): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6414): [parse] Load xml
,V/TelephonyAutoProfiling( 6414): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 6414): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6414): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 113131934281; DSPS: 3806011; Offset : -3030379743
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/MusicWidget( 2593): mDelayedStopHandler : unbind
,I/MusicBrowser( 2700): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2700): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2700): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2700): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2700): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2700): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2700): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2700): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  953):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@13010196com.lge.music.MediaPlaybackService$6@35ed9117
,D/MusicBrowser( 2700): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2700): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2700): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2700): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2700): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@34386c7d
,I/MusicBrowser( 2700): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2700): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2700): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2700): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2700): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2700): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2700): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2700): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2700): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2700): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2700): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2700): [MediaPlaybackService.java:6745:release()] oooooo 
,I/MusicBrowser( 2700): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2700): reset
V/MediaPlayer[Native]( 2700): setListener
V/MediaPlayer[Native]( 2700): disconnect
V/MediaPlayer[Native]( 2700): destructor
,V/AudioFlinger(  280): releasing 19 from 2700 for -1
V/AudioFlinger(  280):  decremented refcount to 0
V/AudioFlinger(  280): purging stale effects
V/MediaPlayer[Native]( 2700): disconnect
D/MusicBrowser( 2700): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2700): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2700): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2700): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
,I/MusicBrowser( 2700): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2700): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2700): [SmartShareManagerClient] unregisterListener: 656800004
W/SmartShareClient( 2700): [SmartShareManagerClient] unregisterListener invalid listener: 656800004
I/SmartShareClient( 2700): [SmartShareManagerClient] terminate service: 2700/MediaPlaybackService/705583691
E/HomeCloudIF( 2700): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2700): [SmartShareManagerClient] unbindService context:android.app.Application@1a226eed
,V/CloudHub( 2700): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2700): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2700): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2700): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2700): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  953): Killing 5676:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/CloudHub( 2700): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29994
W/libprocessgroup(  953): failed to open /acct/uid_10069/pid_5676/cgroup.procs: No such file or directory
,I/ActivityManager(  953): Killing 6068:com.google.android.gm/u0a53 (adj 15): empty #11
,I/ActivityManager(  953): Killing 5868:com.google.android.apps.plus/u0a86 (adj 15): empty #12
,W/libprocessgroup(  953): failed to open /acct/uid_10053/pid_6068/cgroup.procs: No such file or directory
,W/libprocessgroup(  953): failed to open /acct/uid_10086/pid_5868/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  953): Reconfiguring input devices.  changes=0x00000010
,I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/ActivityManager(  953): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6469 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/administrator(  953): Handling package changes for user 0
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
,W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,W/ResourcesManager( 6469): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationService(  953): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  953): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  953): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  953): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/BackupManagerService(  953): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  953): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@306145f9
W/ResourcesManager(  953): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  953): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  953): applying state to connected service
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
,I/Babel_SMS( 6469): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6469): MmsConfig.loadMmsSettings
I/Babel_SMS( 6469): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6469): MmsConfig.loadFromDatabase
I/art     ( 6469): CheckpointMarkThreadRoots callback created = 0xb042d6e0
,E/Babel_SMS( 6469): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6469): MmsConfig.loadFromResources
I/art     ( 6469): CheckpointMarkThreadRoots callback created = 0xb042d6c0
E/Babel_SMS( 6469): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6469): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
W/art     ( 6469): No such thread id for suspend: 16
,D/SensorManager( 6469): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6469): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6469): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6469): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6469): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6469): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6469): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6469): found sensor: LGE Step Detector Sensor, handle=43
,D/SensorManager( 6469): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6469): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6469): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6469): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6469): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6469): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6469): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6469): found sensor: Motion Accel, handle=46
W/Settings( 6469): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6469): startup - clean
I/Babel   ( 6469): deleted: false for 0
,W/AudioCapabilities( 6469): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6469): Unsupported mime audio/adpcm
W/AudioCapabilities( 6469): Unsupported mime audio/g726
W/AudioCapabilities( 6469): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6469): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6469): Unsupported mime video/mjpg
I/ActivityManager(  953): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6507 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/VideoCapabilities( 6469): Unsupported mime video/theora
,W/AudioCapabilities( 6469): Unsupported mime audio/evrc
,W/AudioCapabilities( 6469): Unsupported mime audio/qcelp
W/VideoCapabilities( 6469): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6469): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6469): Unsupported mime audio/qcelp
,W/AudioCapabilities( 6469): Unsupported mime audio/evrc
I/AppUp4:AppBoxCP( 6507): onCreate
W/AppUp4:DB( 6507):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6507):  setFingerPrint start
I/AppUp4:DB( 6507):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,W/VideoCapabilities( 6469): Unsupported mime video/mp4v-esdp
I/AppUp4:DB( 6507):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6507):  SDK version = 0
,I/AppUp4:DB( 6507):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6507): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6507): onReceive
I/AppUp4:CustModeStarterReceiver( 6507): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6507): Context : android.app.ReceiverRestrictedContext@3b371f1a
D/AppUp4:CustFacade( 6507): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6507): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6507): begin check event
I/AppUp4:CustModeStarterReceiver( 6507): Event For Nothing, skip.
I/ActivityManager(  953): Killing 6172:com.google.android.gms:car/u0a6 (adj 15): empty #11
,I/VideoCapabilities( 6469): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6469): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6469): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6469): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6469): Unrecognized profile 2130706433 for video/avc
,W/libprocessgroup(  953): failed to open /acct/uid_10006/pid_6172/cgroup.procs: No such file or directory
,I/ActivityManager(  953): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6528 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/vclib   ( 6469): onServiceConnected
W/Babel   ( 6469): Attempted to change video mute state without an active call.
,I/NotificationManager( 6469): com.google.android.talk: cancel(8) by com.google.android.talk
W/ResourcesManager( 6469): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6469): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6469): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 6528): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6528): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6528): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/System  ( 6469): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6469): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6469): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/AppConfig( 6528): Total System Memory = 906309632
I/GalleryUtils( 6528): Application Heap = 96 MB
I/AppConfig( 6528): App Tier : NOT_DEF
D/SystemHelper( 6528): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  953): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6553 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  953): Killing 5746:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5927): android.os.DeadObjectException
,W/System.err( 5927): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5927): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5927): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5927): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5927): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5927): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5927): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5927): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5927): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5927): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5927): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5927): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5927): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5927): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5927): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5927): android.os.DeadObjectException
W/System.err( 5927): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5927): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5927): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5927): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5927): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5927): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5927): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5927): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5927): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5927): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5927): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5927): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5927): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5927): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5927): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,W/libprocessgroup(  953): failed to open /acct/uid_10089/pid_5746/cgroup.procs: No such file or directory
,W/ActivityManager(  953): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
W/ResourcesManager( 6553): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6553): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6553): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 6553): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6553): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  953): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6571 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6553): BUILD Country: EU
I/SystemConfig( 6553): BUILD Operator: OPEN
D/UEI.SmartControl( 6571): Quickset Services start...
I/UEI.SmartControl( 6571): Manufacture = LGE
D/UEI.SmartControl( 6571): File observer start...
,E/UEI.SmartControl( 6571): IR Port is disabled: false
D/UEI.SmartControl( 6571): Starting file observer...
D/UEI.SmartControl( 6571): Extracting JNI libs...
D/UEI.SmartControl( 6571): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6571): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6571): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6571): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6571): --- Selecting new region: 2
,I/UEI.SmartControl( 6571): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6571): Platform has CIR...
D/UEI.SmartControl( 6571): NO CIR support, need to check package...
I/UEI.SmartControl( 6571): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6571): QS Service created
,I/ActivityManager(  953): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6591 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  953): Killing 5927:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  953): failed to open /acct/uid_10106/pid_5927/cgroup.procs: No such file or directory
,I/SystemConfig( 6553): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 6553): existFile = false
I/SystemConfig( 6553): canReadFile = false
I/SystemConfig( 6553): systemFeature RCS result false
D/SystemConfig( 6553): refreshRcsSupport() :false
E/UEI.SmartControl( 6571): QS start get config
I/LockScreenSettings( 6591): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6591): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6591): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6591): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6591): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6591): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,D/UEI.SmartControl( 6571): Loading JNI Libs...
D/UEI.SmartControl( 6571):  configuring local db...
,I/ActivityManager(  953): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6608 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  953): Killing 6277:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  953): failed to open /acct/uid_10014/pid_6277/cgroup.procs: No such file or directory
,W/ResourcesManager( 6608): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6571):  ---- Has DB8: true
,D/UEI.SmartControl( 6571): QS start statue = true Error code = 0
D/UEI.SmartControl( 6571): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6571): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6571): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6571): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6571): IrrcClient ++ 
D/irrcClient( 6571): getIrrcService ++ 
,D/irrcClient( 6571): getIrrcService -- 
D/irrcClient( 6571): IrrcClient -- 
W/irrc_jni( 6571): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6571): Services init done
I/UEI.SmartControl( 6571): Device manager: loading config....
,D/UEI.SmartControl( 6571): Config is loaded...
D/UEI.SmartControl( 6571):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6571): Notify AllClients services are ready: 0
,I/art     (  953): Explicit concurrent mark sweep GC freed 27531(1462KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 2.454ms total 151.448ms
,D/UEI.SmartControl( 6571): QS Service init finished
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 6571): QS Service version name: 0.1.73
D/UEI.SmartControl( 6571): QS Service version code: 1073
D/UEI.SmartControl( 6571): Service requested: Control
D/UEI.SmartControl( 6571): Service.onUnbind: IControl
D/UEI.SmartControl( 6571): Service.onDestroy
,D/UEI.SmartControl( 6571): Shutdown IRRCPlayer... 
W/irrc_jni( 6571): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6571): ~IrrcClient ++ 
D/irrcClient( 6571): ~IrrcClient -- 
W/irrc_jni( 6571): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6571): Blaster closed
D/UEI.SmartControl( 6571): Blaster closed
D/UEI.SmartControl( 6571): Shut down QS...
D/UEI.SmartControl( 6571): Stopped file observer...
I/UEI.SmartControl( 6571): QS lib stop result = true
,D/UEI.SmartControl( 6571): QS shutdown complete
D/UEI.SmartControl( 6571): QS Service created
I/UpdateIcingCorporaServi( 1935): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 4338): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4338): Null package name or gms related package.  Ignoreing.
E/UEI.SmartControl( 6571): QS start get config
,I/Icing   ( 4338): updateResources: need to parse f{com.google.android.gms}
,D/UEI.SmartControl( 6571):  configuring local db...
I/UpdateIcingCorporaServi( 1935): UpdateCorporaTask done [took 52 ms] updated apps [took 52 ms] 
D/UEI.SmartControl( 6571):  ---- Has DB8: true
,D/UEI.SmartControl( 6571): QS start statue = true Error code = 0
D/UEI.SmartControl( 6571): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6571): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6571): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6571): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6571): IrrcClient ++ 
D/irrcClient( 6571): getIrrcService ++ 
D/irrcClient( 6571): getIrrcService -- 
D/irrcClient( 6571): IrrcClient -- 
W/irrc_jni( 6571): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6571): Services init done
I/UEI.SmartControl( 6571): Device manager: loading config....
D/UEI.SmartControl( 6571): QS Service init finished
D/UEI.SmartControl( 6571): QS Service version name: 0.1.73
D/UEI.SmartControl( 6571): QS Service version code: 1073
D/UEI.SmartControl( 6571): Service requested: Control
D/UEI.SmartControl( 6571): Config is loaded...
,D/UEI.SmartControl( 6571):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 6571): Request IControl service: devices are loaded...
,I/ActivityManager(  953): Killing 6414:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/UEI.SmartControl( 6571): Notify AllClients services are ready: 0
W/libprocessgroup(  953): failed to open /acct/uid_10038/pid_6414/cgroup.procs: No such file or directory
,E/ActivityThread( 6571): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@3ea632d4 that was originally bound here
E/ActivityThread( 6571): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@3ea632d4 that was originally bound here
E/ActivityThread( 6571): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6571): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6571): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6571): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6571): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6571): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6571): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6571): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6571): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6571): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6571): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6571): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6571): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6571): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6571): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6571): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6571): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6571): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6571): Internal service binding...
I/Icing   ( 4338): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4338): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  953): Killing 6339:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  953): failed to open /acct/uid_10006/pid_6339/cgroup.procs: No such file or directory
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/CloudHub( 2700): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19953
,I/ActivityManager(  953): Killing 2700:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  280): 2700 died, releasing its sessions
V/AudioFlinger(  280):  pid 1750 @ 0
V/AudioFlinger(  280):  pid 3115 @ 1
,V/AudioFlinger(  280):  pid 3115 @ 2
W/libprocessgroup(  953): failed to open /acct/uid_10028/pid_2700/cgroup.procs: No such file or directory
,E/UEI.SmartControl( 6571): file observer is disposed!
,D/UEI.SmartControl( 6571): Internal timer expired: 2
,D/UEI.SmartControl( 6571): Service.onUnbind: IControl
D/UEI.SmartControl( 6571): Service.onDestroy
W/System.err( 6571): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@ce45379
W/System.err( 6571): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 6571): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 6571): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 6571): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 6571): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 6571): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 6571): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 6571): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 6571): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6571): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6571): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6571): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6571): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6571): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6571): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6571): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@ce45379
D/UEI.SmartControl( 6571): Shutdown IRRCPlayer... 
W/irrc_jni( 6571): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6571): ~IrrcClient ++ 
D/irrcClient( 6571): ~IrrcClient -- 
W/irrc_jni( 6571): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6571): Blaster closed
D/UEI.SmartControl( 6571): Blaster closed
D/UEI.SmartControl( 6571): Shut down QS...
I/UEI.SmartControl( 6571): QS lib stop result = true
D/UEI.SmartControl( 6571): QS shutdown complete
D/charger_monitor(  490): init target 500000
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  953): battery changed pluggedType: 2
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 133133371116; DSPS: 4461418; Offset : -3030377156
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,V/AlarmManager(  953): ELAPSED_WAKEUP set : Alarm{193721dc type 2 when 140477 com.google.android.gms} when 140477
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1732): Vacuum at: now=1457354250272 tag=VacuumService
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  953): ALS enabled for SRE
D/PowerManagerServiceEx(  953): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26477 ms ago)
,D/qdlights(  953): set_light_backlight: 254
,D/qdlights(  953): set_light_backlight: 251
D/qdlights(  953): set_light_backlight: 247
,D/qdlights(  953): set_light_backlight: 244
,D/qdlights(  953): set_light_backlight: 241
,D/qdlights(  953): set_light_backlight: 237
,D/qdlights(  953): set_light_backlight: 234
,D/qdlights(  953): set_light_backlight: 231
,D/qdlights(  953): set_light_backlight: 227
,D/qdlights(  953): set_light_backlight: 224
,D/qdlights(  953): set_light_backlight: 221
,D/qdlights(  953): set_light_backlight: 217
,D/qdlights(  953): set_light_backlight: 214
,D/qdlights(  953): set_light_backlight: 211
,D/qdlights(  953): set_light_backlight: 207
,D/qdlights(  953): set_light_backlight: 204
,D/qdlights(  953): set_light_backlight: 201
,D/qdlights(  953): set_light_backlight: 197
,D/qdlights(  953): set_light_backlight: 194
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/qdlights(  953): set_light_backlight: 191
,D/qdlights(  953): set_light_backlight: 187
,D/qdlights(  953): set_light_backlight: 184
,D/qdlights(  953): set_light_backlight: 181
,D/qdlights(  953): set_light_backlight: 177
,D/qdlights(  953): set_light_backlight: 174
,D/qdlights(  953): set_light_backlight: 171
,D/qdlights(  953): set_light_backlight: 167
,D/qdlights(  953): set_light_backlight: 164
,D/qdlights(  953): set_light_backlight: 161
,D/qdlights(  953): set_light_backlight: 157
,D/qdlights(  953): set_light_backlight: 154
,D/qdlights(  953): set_light_backlight: 151
,D/qdlights(  953): set_light_backlight: 147
,D/qdlights(  953): set_light_backlight: 144
,D/qdlights(  953): set_light_backlight: 141
,D/qdlights(  953): set_light_backlight: 137
,D/qdlights(  953): set_light_backlight: 134
,D/qdlights(  953): set_light_backlight: 131
,D/qdlights(  953): set_light_backlight: 127
,D/qdlights(  953): set_light_backlight: 124
,D/qdlights(  953): set_light_backlight: 121
,D/qdlights(  953): set_light_backlight: 117
,D/qdlights(  953): set_light_backlight: 114
,D/qdlights(  953): set_light_backlight: 111
,D/qdlights(  953): set_light_backlight: 107
,D/qdlights(  953): set_light_backlight: 104
,D/qdlights(  953): set_light_backlight: 101
,D/qdlights(  953): set_light_backlight: 97
,D/qdlights(  953): set_light_backlight: 94
,D/qdlights(  953): set_light_backlight: 91
,D/qdlights(  953): set_light_backlight: 87
,D/qdlights(  953): set_light_backlight: 84
,D/qdlights(  953): set_light_backlight: 81
,D/qdlights(  953): set_light_backlight: 77
,D/qdlights(  953): set_light_backlight: 74
,D/qdlights(  953): set_light_backlight: 71
,D/qdlights(  953): set_light_backlight: 67
,D/qdlights(  953): set_light_backlight: 64
,D/qdlights(  953): set_light_backlight: 61
,D/qdlights(  953): set_light_backlight: 57
,D/qdlights(  953): set_light_backlight: 54
,D/qdlights(  953): set_light_backlight: 51
,D/qdlights(  953): set_light_backlight: 47
,D/qdlights(  953): set_light_backlight: 44
,D/qdlights(  953): set_light_backlight: 41
,D/qdlights(  953): set_light_backlight: 37
,D/qdlights(  953): set_light_backlight: 34
,D/qdlights(  953): set_light_backlight: 31
,D/qdlights(  953): set_light_backlight: 27
,D/qdlights(  953): set_light_backlight: 24
,D/qdlights(  953): set_light_backlight: 21
,D/qdlights(  953): set_light_backlight: 17
,D/qdlights(  953): set_light_backlight: 14
,D/qdlights(  953): set_light_backlight: 11
,D/qdlights(  953): set_light_backlight: 10
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 153134450130; DSPS: 5116814; Offset : -3030396593
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,I/PowerManagerService(  953): ALS enabled for SRE
D/PowerManagerServiceEx(  953): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33466 ms ago)
I/PowerManagerService(  953): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  953): ALS enabled for SRE
,D/PowerManagerServiceEx(  953): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33488 ms ago)
W/ContextImpl(  953): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  953): Sleeping (uid 1000)...
D/LPWGController(  953): [updateScreenState] screen on = false
,D/LPWGController(  953): disable proximity sensor
D/LPWGController(  953): enable proximity sensor
I/SensorManager(  953): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@26fb499d] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  953): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  953): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  953): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  953): activate: handle is 48, enable
,V/sensors_hal_Ctx(  953): activate sensors is 1400000000000
D/sensors_hal_Thresh(  953): enable: handle=48
I/sensors_hal_SAM(  953): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  953): waitForResponse: timeout=1000
V/sensors_hal_SAM(  953): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  953): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  953): enable: Received response: 0
D/PowerManagerServiceEx(  953): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33536 ms ago)
I/Adreno-EGL(  953): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  953): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  953): Build Date: 03/02/15 Mon
I/Adreno-EGL(  953): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  953): Remote Branch: 
I/Adreno-EGL(  953): Local Patches: 
I/Adreno-EGL(  953): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (146 us)
,I/Sensors (  428): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  953): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  953): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  953): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  953): processInd: handle 48, count=1
V/sensors_hal_Thresh(  953): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  953): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  953): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  953): poll: count: 256
I/sensors_hal_Ctx(  953): poll: released wakelock sensor_ind
D/sensors_hal_Util(  953): waitForResponse: timeout=0
D/LPWGController(  953): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  953): current mode = 1  value = 1 1
I/LPWGController(  953): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  953): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  953): set_light_backlight: 0
,I/SensorManager(  953): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  953): activate: handle is 46, disable
V/sensors_hal_Ctx(  953): activate sensors is 1000000000000
D/sensors_hal_LP2(  953): enable: handle=46
,D/sensors_hal_LP2(  953): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  953): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  953): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  953): Display changed displayId=0
,V/sensors_hal_SAM(  953): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  953): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
D/DSDPConnection( 1750): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
D/SurfaceControl(  953): Excessive delay in setPowerMode(): 245ms
I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
,I/QCOM PowerHAL(  953): Got set_interactive hint
D/KeyguardViewMediator( 1374): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1329): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1374): notifyScreenOffLocked
D/SmartCoverViewMediator( 1329): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1329): handleNotifyScreenOFF
D/JX-Cordova( 5137): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5137): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5137): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e952ccc added. We now have 3 listener(s)
,D/BluetoothManagerService(  953): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/KeyguardViewMediator( 1374): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1374): handleNotifyScreenOff
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5137): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5137): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5137): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5137): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1af26b15 added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5137): addListener: New listener added - the number of listeners is now 1
D/BluetoothAdapterService(1051079380)( 2027): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@29a582ca
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5137): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 5137): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,D/ScreenTurnOffBySensor( 1374): unregisterProximitySensor
D/WifiServerServiceExt(  953): sendKtScanInterval  mRtspPlay : false
,D/StatusBarWindowView( 1374): onScreenTurnedOff why = 3
V/AudioFlinger(  280): setParameters(): io 0, keyvalue screen_state=on, calling pid 953
W/System.err( 5137): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 5137): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 5137): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 5137): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 5137): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 5137): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 5137): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 5137): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 5137): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 5137): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 5137): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5137): 	at android.os.Looper.loop(Looper.java:135)
,W/System.err( 5137): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/audio_hw_primary(  280): adev_set_parameters: enter: screen_state=on
V/voice   (  280): voice_set_parameters: enter: screen_state=on
V/compress_voip(  280): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  280): voice_extn_compress_voip_set_parameters: exit
V/voice   (  280): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  280): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  280): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  280): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  280): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  280): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  280): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  280): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/WifiServerServiceExt(  953): set CMD_KT_SCAN_INTERVAL
D/GpsLocationProvider(  953): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1838): |CORE| sendScreenState: state:true
I/LEDService( 1802): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1802): stopPatternFlashing()
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
,I/LEDService( 1802): updateLightsLocked : turn off led
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1802): RESTART MSG
D/SplitWindow(  953): check instance of lgWin Window{32677fe0 u0 SearchPanel}
,I/Cliptray Service( 1802): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1802): lockStatus = 0
D/LNfcService( 1785): action : android.intent.action.SCREEN_ON
,D/NfcServiceNXP( 1785): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1785): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1785): isRequireNfcCRouting() return true
D/LNfcService( 1785): isHCERoutingtoHost() return : true
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
D/InputDispatcher(  953): Window went away: Window{51811b8 u0 SearchPanel}
,I/[SystemUI]Clock( 1374): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1374): time changed, timezoneChanged : false
,D/Ulp_jni (  953): JNI:system_update. Event-0
,I/Sensors (  428): sns_pwr.c(301):releasing wakelock
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2683): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:37:44
,D/WeatherService( 2683): 2 : ACTION screen on
D/WeatherService( 2683): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2683): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2683): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:37:44
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): ACTION_SCREEN_ON
D/AppCleanupService( 4154): android.intent.action.SCREEN_ON
,V/AudioFlinger(  280): setParameters(): io 0, keyvalue screen_state=off, calling pid 953
,D/audio_hw_primary(  280): adev_set_parameters: enter: screen_state=off
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
D/WifiController(  953): CMD_SCREEN_OFF 
D/WifiController(  953): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  953): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1838): |CORE| sendScreenState: state:false
,I/LEDService( 1802): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1802): stopPatternFlashing()
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1802): clear
I/LEDService( 1802): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): updateLightsLocked : turn on led
E/LEDService( 1802): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1802): Can't handle this request of patternId:0
D/LEDHandler( 1802): RESTART MSG
I/Cliptray Service( 1802): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1785): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1785): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1875): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1750): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2683): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:37:45
D/WeatherService( 2683): 2 : ACTION screen off
D/WeatherService( 2683): 2 : TimeTick Receiver Unregister
,D/WeatherService( 2683): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:37:45
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  953): ACTION_SCREEN_OFF
D/AppCleanupService( 4154): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4154): AppUsageStatsSaveTask
,E/NxpNfcJni( 1785): getReconnectState = 0x0
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
D/LNfcService( 1785): isRequireNfcCRouting() return true
D/LNfcService( 1785): isHCERoutingtoHost() return : true
D/NfcService( 1785): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
,D/NfcService( 1785): newParams.techmask= mTechMask: 0
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): screenState= 1
E/NxpNfcJni( 1785): getReconnectState = 0x0
,I/ThermalEngine(  294): Sensor:pa_therm0:32000 mC
,D/KeyguardViewMediator( 1374): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  953): ELAPSED_WAKEUP set : Alarm{647e299 type 2 when 159425 com.android.systemui} when 159425
,D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1750): getCallState : 0
D/PhoneUtils( 1750): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1750): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1374): isHdmiPluggedIn :false
,D/KeyguardViewMediator( 1374): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 173136748430; DSPS: 5772248; Offset : -3030356723
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1732): disconnect managed GoogleApiClient
,D/PowerManagerServiceEx(  953): acquireWakeLockInternal: lock=475988134, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=953
,V/AlarmManager(  953): ELAPSED_WAKEUP set : Alarm{2efc495e type 2 when 185451 com.google.android.gms} when 185451
D/PowerManagerServiceEx(  953): releaseWakeLockInternal: lock=475988134 [*alarm*], flags=0x0
,I/PhenotypeConfigurator( 1732): Scheduling Phenotype for one-off execution 14005 seconds from now (1457354295374)
,I/PhenotypeFlagCommitter( 1732): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1732): Using platform SSLCertificateSocketFactory
,D/LocationManagerService(  953): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): init target 500000
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 293, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/art     ( 1732): Background sticky concurrent mark sweep GC freed 109410(6MB) AllocSpace objects, 13(231KB) LOS objects, 27% free, 16MB/22MB, paused 2.204ms total 104.262ms
,D/LocationManagerService(  953): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  953): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 188138957742; DSPS: 6263841; Offset : -3030375248
,D/LocationManagerService(  953): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  953): ELAPSED_WAKEUP set : Alarm{2e5fc82f type 2 when 193952 android} when 193952
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 205642805014; DSPS: 6837410; Offset : -3030464716
,I/ThermalEngine(  294): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 220645068615; DSPS: 7329002; Offset : -3030398538
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 240647374248; DSPS: 7984438; Offset : -3030412058
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): init target 500000
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  953): tsOffsetIs: Apps: 260649415950; DSPS: 8639867; Offset : -3030476252
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 275652098411; DSPS: 9131464; Offset : -3030143644
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
,I/[SystemUI]Clock( 1374): called onTimeUpdated()
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 298156683148; DSPS: 9868901; Offset : -3030350115
,I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 318158861065; DSPS: 10524326; Offset : -3030155710
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 333161197074; DSPS: 11015930; Offset : -3030383359
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/LocationManagerService(  953): remove 16255b95
,D/LocationManagerService(  953): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  953): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  953): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  953): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  953): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 348163437831; DSPS: 11507524; Offset : -3030400747
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  953): acquireWakeLockInternal: lock=475988134, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=953
,D/PowerManagerServiceEx(  953): releaseWakeLockInternal: lock=475988134 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 363166112199; DSPS: 11999120; Offset : -3030045716
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 385670663741; DSPS: 12736561; Offset : -3030407555
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 405673072717; DSPS: 13391996; Offset : -3030287528
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 420675475848; DSPS: 13883597; Offset : -3030356060
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 440677890776; DSPS: 14539037; Offset : -3030384361
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 460680718211; DSPS: 15194490; Offset : -3030393290
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 480682893562; DSPS: 15849925; Offset : -3030506965
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 495687916614; DSPS: 16341604; Offset : -3030336157
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 508820391674; DSPS: 16771930; Offset : -3030368448
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 521963888334; DSPS: 17202624; Offset : -3030609631
,I/ThermalEngine(  294): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 539635776546; DSPS: 17781682; Offset : -3030169122
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 557459924649; DSPS: 18365738; Offset : -3029995395
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 575284304828; DSPS: 18949818; Offset : -3030322455
,D/PowerManagerServiceEx(  953): acquireWakeLockInternal: lock=475988134, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=953
,V/AlarmManager(  953): ELAPSED_WAKEUP set : Alarm{3120be3c type 2 when 577412 android} when 577412
D/PowerManagerServiceEx(  953): releaseWakeLockInternal: lock=475988134 [*alarm*], flags=0x0
,I/NotificationManager(  953): android: cancelAsUser(-1874035846) by android
,I/NotificationManager(  953): android: cancelAsUser(-1548111331) by android
,I/NotificationManager(  953): android: cancelAsUser(2145784878) by android
,I/NotificationManager( 6608): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 590286551925; DSPS: 19441413; Offset : -3030364175
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  953): acquireWakeLockInternal: lock=475988134, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=953
,V/AlarmManager(  953): ELAPSED_WAKEUP set : Alarm{fa0f796 type 2 when 607646 android} when 607646
I/ActivityManager(  953): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6897 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/art     (  308): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 425us total 55.905ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 566us total 57.457ms
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 391us total 31.836ms
,I/DigitalAppWidgetProvider( 6897): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6897): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3b371f1a
I/ActivityManager(  953): Killing 6507:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/PowerManagerServiceEx(  953): releaseWakeLockInternal: lock=475988134 [*alarm*], flags=0x0
,W/libprocessgroup(  953): failed to open /acct/uid_10011/pid_6507/cgroup.procs: No such file or directory
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 610288855956; DSPS: 20096847; Offset : -3030318238
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 624830412678; DSPS: 20573342; Offset : -3030235113
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 638907506464; DSPS: 21034616; Offset : -3030106607
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 653296455235; DSPS: 21506122; Offset : -3030379078
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 667838700895; DSPS: 21982643; Offset : -3030400264
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 682841676613; DSPS: 22474260; Offset : -3030384778
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 697846621775; DSPS: 22965948; Offset : -3030566436
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 711918258316; DSPS: 23427040; Offset : -3030341161
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 729421588062; DSPS: 24000592; Offset : -3030429227
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 749423985270; DSPS: 24656028; Offset : -3030351772
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 769426009855; DSPS: 25311456; Offset : -3030402226
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 789428356327; DSPS: 25966892; Offset : -3030374986
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 809430664169; DSPS: 26622328; Offset : -3030386323
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 829432866442; DSPS: 27277761; Offset : -3030411963
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 849434544591; DSPS: 27933175; Offset : -3030381555
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 869436845543; DSPS: 28588611; Offset : -3030400043
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 884439040635; DSPS: 29080202; Offset : -3030371881
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 899452874158; DSPS: 29572177; Offset : -3030423752
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 919455041296; DSPS: 30227605; Offset : -3030331915
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 939457251077; DSPS: 30883039; Offset : -3030380408
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  953): acquireWakeLockInternal: lock=475988134, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=953
,V/AlarmManager(  953): ELAPSED_WAKEUP set : Alarm{6fd4f17 type 2 when 948132 com.android.bluetooth} when 948132
D/PowerManagerServiceEx(  953): releaseWakeLockInternal: lock=475988134 [*alarm*], flags=0x0
,W/bt-smp  ( 2027): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2027): Plain text(LSB ~ MSB) = 21 bb 61 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 2027): Encrypted text(LSB ~ MSB) = aa 24 4b 98 82 35 07 e6 0d bc 70 37 1e b1 b0 de 
W/bt-btm  ( 2027): Stopping oneshot timer
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 959458768565; DSPS: 31538451; Offset : -3030449833
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 979461094667; DSPS: 32193895; Offset : -3030687129
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 992597825953; DSPS: 32624352; Offset : -3030460893
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1009793638351; DSPS: 33187821; Offset : -3030357725
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1029796040025; DSPS: 33843262; Offset : -3030428077
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1044798662683; DSPS: 34334866; Offset : -3030368792
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1062302062680; DSPS: 34908416; Offset : -3030325834
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1077304306674; DSPS: 35400010; Offset : -3030340088
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1092306378455; DSPS: 35891600; Offset : -3030404563
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1109809698090; DSPS: 36465147; Offset : -3030350310
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1129812318414; DSPS: 37120605; Offset : -3030720759
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1152316691028; DSPS: 37858018; Offset : -3030406749
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1172318945574; DSPS: 38513452; Offset : -3030410686
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1192321601635; DSPS: 39168898; Offset : -3030379138
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1212323929787; DSPS: 39824334; Offset : -3030370296
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/UsageStatsService(  953): User[0] Flushing usage stats to disk
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1232326053702; DSPS: 40479763; Offset : -3030352171
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
,I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1252328289431; DSPS: 41135198; Offset : -3030405260
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1272330487759; DSPS: 41790629; Offset : -3030373655
,I/ThermalEngine(  294): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1292332653158; DSPS: 42446061; Offset : -3030405313
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
,I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1312334782200; DSPS: 43101490; Offset : -3030382140
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1332336953422; DSPS: 43756921; Offset : -3030377561
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1352339197720; DSPS: 44412354; Offset : -3030361178
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
,I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1372341817215; DSPS: 45067800; Offset : -3030366116
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2027): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  953): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  953): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  953): battery changed pluggedType: 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1392343992317; DSPS: 45723231; Offset : -3030357788
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1412346280888; DSPS: 46378667; Offset : -3030388578
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
,I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1432348607619; DSPS: 47034102; Offset : -3030350770
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  490): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1452350892723; DSPS: 47689538; Offset : -3030384794
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1472353193029; DSPS: 48344973; Offset : -3030373358
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
,I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/sensors_hal_Time(  953): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  953): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  953): tsOffsetIs: Apps: 1492355397072; DSPS: 49000407; Offset : -3030427538
,I/ThermalEngine(  294): Sensor:pa_therm0:27000 mC
,TIME-OUT KILL (timeout was 1400000ms)
```
