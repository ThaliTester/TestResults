#### Test 61432979f791f6f_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/MusicStore( 4716): Database version: 120
,--------- beginning of system
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4716): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4716): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4716): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 4716): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4716): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 4716): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AndroidRuntime( 4750): 
D/AndroidRuntime( 4750): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4750): CheckJNI is OFF
W/ActivityThread( 4716): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4716): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bb4fd65: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4716): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4716): GMSCore installation verified
I/ConfigStore( 4716): Config Database version: 1
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/MediaRouter( 4716): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/MusicLeanback( 4716): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 4716): type=WIFI subType= reason=null isConnected=true
I/NetworkMonitor( 4716): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  839): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=4773 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/GHttpClientFactory( 4716): Using our fixed implementation of GMSCore's GoogleHttpClient
I/ThermalEngine(  289): Sensor:pa_therm0:33000 mC
D/AndroidRuntime( 4750): Calling main entry com.android.commands.am.Am
I/GoogleURLConnFactory( 4716): Using platform SSLCertificateSocketFactory
I/ActivityManager(  839): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  839): setTaskToReturnTo : TaskRecord{1a59a42c #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  839): setTaskToReturnTo : TaskRecord{1a59a42c #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  839): AppWindowTokenEx init.. 
D/ContextHelper(  839): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
D/InputDispatcher(  839): Focus left window: Window{6497908 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 4750): Shutting down VM
I/PhoneWindow(  839): [generateLayout] setColorNavigationBar => color=0x ff000001
I/[LGHome]EVENT( 1947): [Launcher.java:986:onPause()]onPause
D/PhoneWindowEx(  839): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  839): [setNavigationBarColor2] color=0x fff5f5f5
D/SplitWindow(  839): check instance of lgWin Window{16aa4cc4 u0 Starting com.test.thalitest}
I/ActivityManager(  839): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4799 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  839): Waited long enough for: ServiceRecord{8200ff3 u0 com.android.calendar/.alerts.InitAlarmsService}
I/WindowStateAnimator(  839): Starting window displayed
W/ResourcesManager( 4773): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4773): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4773): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/WindowManager(  839): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/SystemUI[Framework](  839): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
I/[SystemUI]NavigationThemeResource( 1371): notify navigation bar color(0xfff5f5f5)
I/[SystemUI]NavigationThemeResource( 1371): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1371):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1371): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx(  839): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  839): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  839): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  839): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@381a900a,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  839): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
,I/[LGHome]EVENT( 1947): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
,I/ActivityManager(  839): Killing 4512:com.lge.qmemoplus/1000 (adj 15): empty #11
,I/[LGHome]EVENT( 1947): [Launcher.java:5214:onStop()]onStop
W/ActivityThread( 1947): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1947): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1947): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3407)
W/ActivityThread( 1947): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3496)
W/ActivityThread( 1947): 	at android.app.ActivityThread.access$1100(ActivityThread.java:155)
W/ActivityThread( 1947): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1352)
W/ActivityThread( 1947): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 1947): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 1947): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/ActivityThread( 1947): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 1947): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 1947): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/ActivityThread( 1947): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_4512/cgroup.procs: No such file or directory
,I/NotificationManager( 4716): com.google.android.music: cancel(1061) by com.google.android.music
D/ContextHelper( 4799): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,I/ActivityManager(  839): Activity reported stop, but no longer stopping: ActivityRecord{24bc3e33 u0 com.lge.launcher2/.Launcher t221}
I/HotwordDetector( 2025): Closing mic
,I/MicrophoneInputStream( 2025): mic_close com.google.android.apps.gsa.speech.audio.u@dec319f
,V/AudioRecord( 2025): stop()
D/AudioRecord( 2025): AudioRecord->stop()
V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
V/AudioFlinger(  278): Record stopped OK
V/AudioPolicyManager(  278): stopInput() input 17
,V/AudioPolicyService(  278): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  278): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  278): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  278): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  278): ThreadBase::setParameters() routing=0
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb3855000
D/audio_hw_primary(  278): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  278): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  278): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  278): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  278): disable_audio_route: reset and update mixer path: audio-record
,V/audio_hw_primary(  278): disable_audio_route: exit
E/audio_hw_primary(  278): disable_snd_device: enter 144
D/hardware_info(  278): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  278): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  278): stop_input_stream: exit: status(0)
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
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb3855000
V/AudioFlinger(  278): RecordThread: loop stopping
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioRecord( 2025): stop()
V/AudioRecord( 2025): stop()
V/AudioRecord( 2025): stop()
,V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
V/AudioPolicyManager(  278): releaseInput() 17
V/AudioPolicyManager(  278): closeInput(17)
V/AudioFlinger(  278): releasing 16 from 2025 for -1
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
V/AudioFlinger(  278): closeInput() 17
V/AudioSystem(  278): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  839): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1371): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): ThreadBase::exit
V/AudioSystem( 2097): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1769): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): RecordThread: loop starting
V/AudioSystem( 2025): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2077): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): RecordThread 0xb3855000 exiting
V/AudioSystem( 3114): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  278): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  278): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  278): in_standby: exit:  status(0)
V/AudioPolicyService(  278): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  278): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  278): releaseInput() exit
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioFlinger(  278): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  278): AudioCommandThread() processing update audio port list
V/AudioFlinger(  278): removeClient_l() pid 2025, calling pid 278
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
I/WebViewFactory( 4799): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/HotwordRecognitionRnr( 2025): Hotword detection finished
,I/HotwordRecognitionRnr( 2025): Stopping hotword detection.
I/LGEmail ( 4773): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,I/LibraryLoader( 4799): Time to load native libraries: 2 ms (timestamps 8824-8826)
I/LibraryLoader( 4799): Expected native library version number "",actual native library version number ""
,D/LGEmail ( 4773): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
V/WebViewChromiumFactoryProvider( 4799): Binding Chromium to main looper Looper (main, tid 1) {2a7ad879}
,I/LibraryLoader( 4799): Expected native library version number "",actual native library version number ""
I/chromium( 4799): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4799): Initializing chromium process, singleProcess=true
,W/art     ( 4799): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4799): ApplicationContext is null in ApplicationStatus
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
W/chromium( 4799): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4799): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4799): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4799): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4799): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4799): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4799): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4799): Remote Branch: 
I/Adreno-EGL( 4799): Local Patches: 
I/Adreno-EGL( 4799): Reconstruct Branch: 
,V/AudioPolicyService(  278): registerClient() client 0xb57f3d20, uid 10316
,D/BluetoothManagerService(  839): Message: 20
D/BluetoothManagerService(  839): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@37dca0b6:true
,D/BluetoothAdapterService(434966892)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@8ee7222
D/eas_req ( 4773): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 4540): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4540): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4540): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4540): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 4540): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 4540): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4540): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4540): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/HubEmail( 4773): JNI_OnLoad()
I/HubEmail( 4773): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4773): registerNatives()
I/HubEmail( 4773): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4773): registerNativeMethods()
I/HubEmail( 4773): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 4773): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/ActivityManager(  839): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=4848 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 4540): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
W/Settings( 4773): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/LGDMClient( 4540): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 4540): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 4540): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 4540): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 4540): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
W/art     ( 4799): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4799): onDetachedFromWindow called when already detached. Ignoring
,I/PhoneWindow( 4799): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 4799): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 4799): [setNavigationBarColor2] color=0x fff5f5f5
D/SystemWebViewEngine( 4799): CordovaWebView is running on device made by: LGE
,W/art     ( 4799): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4799): Attempt to remove local handle scope entry from IRT, ignoring
I/AppUp4:AppBoxCP( 4848): onCreate
,W/AppUp4:DB( 4848):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 4848):  setFingerPrint start
I/AppUp4:DB( 4848):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 4848):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4848):  SDK version = 0
I/AppUp4:DB( 4848):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 4848): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 4848): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4848): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4848): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 4848): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 4848): onReceive
I/AppUp4:CustModeStarterReceiver( 4848): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 4848): Context : android.app.ReceiverRestrictedContext@2a7ad879
D/AppUp4:CustFacade( 4848): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4848): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 4848): begin check event
I/AppUp4:CustModeStarterReceiver( 4848): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4848): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4848): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 4848): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 4848): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  839): Killing 3324:com.android.defcontainer/u0a4 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10004/pid_3324/cgroup.procs: No such file or directory
,I/Activity( 4799): Activity.onPostResume() called 
D/OpenGLRenderer( 4799): Render dirty regions requested: true
I/OpenGLRenderer( 4799): Initialized EGL, version 1.4
D/OpenGLRenderer( 4799): Enabling debug mode 0
,I/LgeMiscReceiver( 3114): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 3114): action = android.net.conn.CONNECTIVITY_CHANGE
D/Atlas   ( 4799): Validating map...
I/LgeMiscReceiver( 3114): networkInfo.isConnected() = true
D/SplitWindow(  839): check instance of lgWin Window{3842b93e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/PhoneState( 3114): setPdpRejectCasuse : false
W/chromium( 4799): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/ActivityManager(  839): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=4873 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 4692:com.lge.bnr/1000 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_4692/cgroup.procs: No such file or directory
D/InputDispatcher(  839): Focus entered window: Window{3842b93e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  839): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  839): Displayed com.test.thalitest/.MainActivity: +1s494ms
I/Timeline(  839): Timeline: Activity_windows_visible id: ActivityRecord{2e387ef5 u0 com.test.thalitest/.MainActivity t222} time:69684
I/Timeline( 4799): Timeline: Activity_idle id: android.os.BinderProxy@f5a772b time:69696
,D/PhoneMonitor( 4873): Register our PhoneStateListener
,W/BindingManager( 4799): Cannot call determinedVisibility() - never saw a connection for the pid: 4799
,D/MobileConnectivityChangeReceiver( 4873): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4873): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  839): Killing 4621:com.android.settings/1000 (adj 15): empty #11
,D/PhoneMonitor( 4873): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 4873): [loadFeatureFromXml] *** start feature loading from xml
W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_4621/cgroup.procs: No such file or directory
D/TelephonyAutoProfiling( 4873): [parse] Load xml
,V/TelephonyAutoProfiling( 4873): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 4873): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3140): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3140): DownloadService onCreate
I/DownloadManager( 3140): in removeSpuriousFiles
V/DownloadManager( 3140): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3140): created cursor android.database.sqlite.SQLiteCursor@3e486f1e on behalf of 3140
D/PhoneMonitor( 4873): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/DownloadManager( 3140): in trimDatabase
V/DownloadManager( 3140): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3140): created cursor android.database.sqlite.SQLiteCursor@25e6a3ff on behalf of 3140
I/NotificationManager( 3140): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/ActivityManager(  839): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4906 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3140): DownloadService onStartCommand
V/DownloadManager( 3140): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3140): created cursor android.database.sqlite.SQLiteCursor@27085f2a on behalf of 3140
,I/CheckinService( 4266): Checkin interval check for package: unspecified last checkin: 1457078503557 min interval config: 0 actual interval: 212391
,I/CheckinService( 4266): Checking schedule, now: 1457078715965 next: 1457078533519
I/CheckinService( 4266): active receiver: enabled
,D/JsMessageQueue( 4799): Set native->JS mode to OnlineEventsBridgeMode
V/DownloadManager( 3140): DownloadService onDestroy
,I/CheckinService( 4266): Preparing to send checkin request
I/EventLogService( 4266): Accumulating logs since 1457078500281
D/DrmBroadcastReceiver( 4906): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 4906): 1  network is available. Sync DRM Time with NTP
V/DrmService( 4906): Service onCreate
D/DrmService( 4906): Received new request = 2
D/WeatherAncestor( 2657): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:5:16
D/UpdateThreadPoolManager( 2657): 2 : This is isUpdating : false
,D/WeatherAncestor( 2657): connectivity changed - connection : true
I/DrmSntpClient( 4906): Start Sync process
D/DrmSntpClient( 4906): Server : 0
D/Weather_cast( 2657): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2657): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 9:5:16
,D/WeatherService( 2657): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd( 4906): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4906): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4906): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4906): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  274): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  839): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4928 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  839): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2657): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2657): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2657): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 4928): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 4906): propertyValue:false
I/CheckinRequestBuilder( 4266): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4266): Failed to find provider info for com.google.android.wearable.settings
,I/LGDrmClient( 4906): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  283): eDRM_SetDRMTime +++
I/LGDRM   (  283): [DRM] SET TIME : YR=2016, MON=3, DAY=4
I/LGDRM   (  283): [DRM] SET TIME : HR=8, MIN=5, SEC=16
,V/ILGDrmService(  283): eDRM_SetDRMTime ---
,I/DrmSntpClient( 4906): Synched
D/DrmService( 4906): Completed !! request = 2
D/DrmService( 4906): Request count = 0
V/DrmService( 4906): Service onDestroy
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/jxcore_app_log( 4799): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426143104
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4799): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4799):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4799):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4799):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4799):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4799): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@237ac015 added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4799): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4799):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4799):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4799):     - Bluetooth MAC address: F8:95:C7:87:85:54
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4799):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4799):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4799):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4799):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4799):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4799):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4799): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c1e62b8 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4799): addListener: New listener added - the number of listeners is now 1
,D/BluetoothAdapterService(434966892)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@8ee7222
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4799): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4799): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 4799): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 4799): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4799): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4799): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4799): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4799): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4799): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4799): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4799): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4799): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4799): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4799): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4799): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/JX-Cordova( 4799): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4799): load: Already loaded
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4799): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d544891 added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4799): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4799): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c2543f6 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4799): addListener: New listener added - the number of listeners is now 1
D/BluetoothAdapterService(434966892)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@8ee7222
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4799): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4799): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4799): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 4799): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4799): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4799): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4799): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4799): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4799): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4799): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4799): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4799): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4799): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4799): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4799): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/UEI.SmartControl( 4589): Internal timer expired: 1
,I/Babel_SMS( 4928): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4928): MmsConfig.loadMmsSettings
,I/ActivityManager(  839): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4961 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/Babel_SMS( 4928): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4928): MmsConfig.loadFromDatabase
,D/SensorManager( 4928): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4928): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4928): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 4928): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4928): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4928): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4928): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4928): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4928): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4928): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4928): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4928): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4928): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4928): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4928): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4928): found sensor: Motion Accel, handle=46
E/Babel_SMS( 4928): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 4928): MmsConfig.loadFromResources
E/Babel_SMS( 4928): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4928): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
W/art     ( 4928): Suspending all threads took: 10.042ms
,W/ResourcesManager( 4961): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4961): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/Settings( 4928): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 4928): startup - clean
,I/art     ( 4928): CheckpointMarkThreadRoots callback created = 0xb042d8b0
,I/Babel   ( 4928): deleted: false for 0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/MultiDex( 4961): VM with version 2.1.0 has multidex support
I/MultiDex( 4961): install
I/MultiDex( 4961): VM has multidex support, MultiDex support library is disabled.
,I/art     ( 4928): CheckpointMarkThreadRoots callback created = 0xb042d890
V/JNIHelp ( 4961): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  839): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4982 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityThread( 4961): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4961): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d59a982: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4961): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 4961): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 4961): com.google.android.gms: cancel(39789) by com.google.android.gms
,W/AudioCapabilities( 4928): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 4928): Unsupported mime audio/adpcm
W/AudioCapabilities( 4928): Unsupported mime audio/g726
W/AudioCapabilities( 4928): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 4928): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4928): Unsupported mime video/mjpg
W/VideoCapabilities( 4928): Unsupported mime video/theora
,I/art     ( 4961): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 4961): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/AudioCapabilities( 4928): Unsupported mime audio/evrc
,W/AudioCapabilities( 4928): Unsupported mime audio/qcelp
W/VideoCapabilities( 4928): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4928): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 4928): Unsupported mime audio/qcelp
W/AudioCapabilities( 4928): Unsupported mime audio/evrc
,W/VideoCapabilities( 4928): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 4928): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4928): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4928): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4928): Unrecognized profile 2130706433 for video/avc
,I/art     (  839): Explicit concurrent mark sweep GC freed 27257(1419KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.073ms total 170.017ms
,W/VideoCapabilities( 4928): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  839): Process com.lge.qremote (pid 4568) has died
,I/ActivityManager(  839): Waited long enough for: ServiceRecord{c3c83d3 u0 com.lge.springcleaning/.service.AppCleanupService}
E/lowmemorykiller(  242): Error writing /proc/4716/oom_score_adj; errno=22
D/UEI.SmartControl( 4589): Service.onUnbind: IControl
D/UEI.SmartControl( 4589): Service.onDestroy
D/UEI.SmartControl( 4589): Shutdown IRRCPlayer... 
,W/irrc_jni( 4589): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 4589): ~IrrcClient ++ 
D/irrcClient( 4589): ~IrrcClient -- 
W/irrc_jni( 4589): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 4589): Blaster closed
D/UEI.SmartControl( 4589): Blaster closed
D/UEI.SmartControl( 4589): Shut down QS...
D/UEI.SmartControl( 4589): Stopped file observer...
I/ActivityManager(  839): Process com.google.android.music:main (pid 4716) has died
I/UEI.SmartControl( 4589): QS lib stop result = true
,D/UEI.SmartControl( 4589): QS shutdown complete
I/vclib   ( 4928): onServiceConnected
W/Babel   ( 4928): Attempted to change video mute state without an active call.
I/NotificationManager( 4928): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/WVCdm   (  278): Instantiating CDM.
I/WVCdm   (  278): CdmEngine::OpenSession
I/WVCdm   (  278): Level3 Library Dec 11 2014 16:13:16
,D/NativeLibraryUtils( 4961): Install completed successfully. count=14 extracted=0
D/libc-netbsd( 4928): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4928): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4928): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4928): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10061
,D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
W/WVCdm   (  278): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  278): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  278): L1 library not specified. Falling Back to L3
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4982): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4982): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 4928): propertyValue:false
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4982): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
I/GAv4    ( 4982): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 4982):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 4982):   adb logcat -s GAv4
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
W/ContextImpl( 4982): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
D/WVCdm   (  278): PrepareKeyRequest: nonce=2443175864
W/GAv4    ( 4982): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4982): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 4982): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/Babel   ( 4928): connection state changed from UNKNOWN to CONNECTED
,I/art     ( 4961): CheckpointMarkThreadRoots callback created = 0xb04cce30
,I/art     ( 4961): CheckpointMarkThreadRoots callback created = 0xb04cce10
,I/WebViewFactory( 4982): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/dex2oat ( 5026): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/LibraryLoader( 4982): Time to load native libraries: 5 ms (timestamps 1916-1921)
I/LibraryLoader( 4982): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4982): Binding Chromium to main looper Looper (main, tid 1) {dd37732}
I/LibraryLoader( 4982): Expected native library version number "",actual native library version number ""
,I/chromium( 4982): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4982): Initializing chromium process, singleProcess=true
,W/art     ( 4982): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4982): ApplicationContext is null in ApplicationStatus
W/chromium( 4982): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4982): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4982): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4982): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4982): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4982): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4982): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4982): Remote Branch: 
I/Adreno-EGL( 4982): Local Patches: 
I/Adreno-EGL( 4982): Reconstruct Branch: 
I/dex2oat ( 5026): dex2oat took 137.830ms (threads: 4)
,I/Adreno-EGL( 4961): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4961): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4961): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4961): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4961): Remote Branch: 
I/Adreno-EGL( 4961): Local Patches: 
I/Adreno-EGL( 4961): Reconstruct Branch: 
,V/AudioPolicyService(  278): registerClient() client 0xb4027880, uid 10079
,W/AudioManagerAndroid( 4982): Requires BLUETOOTH permission
I/ActivityManager(  839): Process com.uei.lg.quicksetsdk.lite (pid 4589) has died
,I/NSApplication( 4982): Starting up...
,I/ActivityManager(  839): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5051 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Adreno-EGL( 4961): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4961): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4961): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4961): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4961): Remote Branch: 
I/Adreno-EGL( 4961): Local Patches: 
I/Adreno-EGL( 4961): Reconstruct Branch: 
I/Adreno-EGL( 4961): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4961): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4961): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4961): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4961): Remote Branch: 
I/Adreno-EGL( 4961): Local Patches: 
I/Adreno-EGL( 4961): Reconstruct Branch: 
,I/ActivityManager(  839): Process com.lge.sync (pid 4653) has died
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 72440241592; DSPS: 2472399; Offset : -3023578695
,I/ActivityManager(  839): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5071 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5071): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]QPairHandler( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1908): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
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
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/InputReader(  839): Reconfiguring input devices.  changes=0x00000010
D/administrator(  839): Handling package changes for user 0
I/[LGHome]EVENT( 1947): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/art     ( 1823): CheckpointMarkThreadRoots callback created = 0xaaf1eb60
,I/art     ( 1823): CheckpointMarkThreadRoots callback created = 0xb042d710
,I/[LGHome]LGPlusHomeDBManager( 1947): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1947): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[LGHome]Launcher( 1947): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationService(  839): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  839): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  839): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  839): Process com.lge.email (pid 4773) has died
,I/ThermalEngine(  289): Sensor:pa_therm0:33000 mC
I/BackupManagerService(  839): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/BackupManagerService(  839): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  839): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3be99ca5
W/ResourcesManager(  839): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/LCardEmulationManager( 1823): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1823): getDefaultRoute
,I/CheckinRequestBuilder( 4266): Classify the device as Phone.
W/ResourceType(  839): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/art     ( 3971): Explicit concurrent mark sweep GC freed 2650(105KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 1.205ms total 37.138ms
,I/[LGHome]EVENT( 1947): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1739): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  839): applying state to connected service
,D/libc-netbsd( 4266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 4266): propertyValue:false
I/iu.SyncManager( 4266): SYNC; picasa accounts
,D/NetworkLogImpl( 4266): Loaded NetworkSpeedPredictor
I/iu.Environment( 4266): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 4266): num queued entries: 0
,I/iu.UploadsManager( 4266): num updated entries: 0
I/iu.SyncManager( 4266): NEXT; no task
D/libc-netbsd( 4266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  839): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5105 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ActivityManager(  839): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager(  839): RTC_WAKEUP set : Alarm{b67880b type 0 when 1456733079246 com.android.providers.contacts} when 1456733079246
V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{2a0a76e8 type 2 when 57888 com.google.android.talk} when 57888
D/libc-netbsd( 4266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 305us total 22.014ms
V/AlarmManager(  839): RTC_WAKEUP set : Alarm{2c7e6ba6 type 0 when 1457078719556 com.google.android.googlequicksearchbox} when 1457078719556
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 21.598ms
,I/CheckinTask( 4266): Sending checkin request (7807 bytes)
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 295us total 21.436ms
,W/ResourcesManager( 5105): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/WVCdm   (  278): CdmEngine::CloseSession
,I/WVCdm   (  278): L3 Terminate.
D/BluetoothManagerService(  839): Message: 20
D/BluetoothManagerService(  839): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@14533b00:true
,D/BluetoothAdapterService(434966892)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@8ee7222
D/BluetoothAdapterService(434966892)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@8ee7222
I/ActivityManager(  839): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=5129 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 5129): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 2657): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 9:5:19
D/UpdateThreadPoolManager( 2657): 2 : This is isUpdating : false
D/Weather_cast( 2657): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2657): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 9:5:19
D/WeatherService( 2657): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
W/ActivityManager(  839): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2657): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2657): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2657): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
V/SmsReceiverService( 3114): onStart: #1 mResultCode: -1 = Activity.RESULT_OK
,D/MmsConfig( 3114): isNotAllowedSms: currentUser:0
D/MmsConfig( 3114): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3114): isUserMode:false
D/SmsReceiverService( 3114): handleMessage isUserMode:false
V/SmsReceiverService( 3114): handleMessage action: com.android.mms.transaction.SEND_MESSAGE error: 0
D/SmsReceiverService( 3114): [LGE] handleSendMessage Send messages in queue
,I/[LGHome]LGNumberBadgeReceiver( 1947): [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = lge.intent.action.UNREAD_MESSAGES
I/[LGHome]NumberBadge.LGBroadCastBadge( 1947): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1947): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1947): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1947): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  839): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=5155 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  839): Process com.lge.appbox.client (pid 4848) has died
,I/CheckinRequestBuilder( 4266): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4266): Failed to find provider info for com.google.android.wearable.settings
,W/ResourcesManager( 5155): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5155): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5155): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5155): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5155): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/IndexDatabaseHelper( 5155): Using schema version: 115
I/IndexDatabaseHelper( 5155): Index is fine
,I/CheckinRequestBuilder( 4266): Classify the device as Phone.
I/CheckinTask( 4266): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4266): Checking schedule, now: 1457078720380 next: 1457605969375
I/CheckinService( 4266): active receiver: disabled
,D/CheckinService( 4266): Recording last checkin time for package unspecified as 1457078720413
,I/ActivityManager(  839): Killing 4540:com.lge.lgdmsclient/1000 (adj 15): empty #11
D/UsbSettingsReceiver( 5155): [AUTORUN] onReceive() : action = android.hardware.usb.action.USB_STATE
D/UsbSettingsReceiver( 5155): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5155): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 5155): [AUTORUN] persist.sys.usb.config = ptp_only,adb
W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_4540/cgroup.procs: No such file or directory
D/UsbSettingsReceiver( 5155): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsReceiver( 5155): [AUTORUN] onReceive() : getDefaultFunction = ptp_only
D/UsbSettingsReceiver( 5155): [AUTORUN] onReceive() : USB_FUNCTION_CDROM_STORAGE = false
D/UsbSettingsReceiver( 5155): [AUTORUN] onReceive() : mDirectAutorun = true
D/UsbSettingsReceiver( 5155): [AUTORUN] onReceive() : mActivityUsbModeChange = false
,D/UsbSettingsReceiver( 5155): [AUTORUN] onReceive() : mActivityFinish = false
D/UsbSettingsReceiver( 5155): [AUTORUN] onReceive() : ===== USB Configured =====
,D/UsbSettingsControl( 5155): [AUTORUN] setUsbConnected() : connected=true
D/UsbSettingsReceiver( 5155): [AUTORUN] onReceive() : checkQmicm = ptp_only,adb
D/UsbSettingsReceiver( 5155): [AUTORUN] : topPackageName=com.test.thalitest
D/UsbSettingsReceiver( 5155): [AUTORUN] : topClassName=com.test.thalitest.MainActivity
D/UsbSettingsReceiver( 5155): [AUTORUN] Not exist com.android.LGSetupWizard
D/UsbSettingsReceiver( 5155): [AUTORUN] setUsbConnect() : mUsbSettingsRun = false
D/UsbSettingsReceiver( 5155): [AUTORUN] startUsbSettings() : deviceProvisioned=1
I/ActivityManager(  839): Killing 4873:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10038/pid_4873/cgroup.procs: No such file or directory
,I/ActivityManager(  839): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5176 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/MtpService( 3140): updating state; isCurrentUser=true, mMtpLocked=false
,I/PCSuite ( 5176): [StartReceiver]USB CONNECTED ver UsbManger : ptp_only
I/PCSuite ( 5176): [StartReceiver]isUsbPCSuiteMode : false
,D/PCSuite ( 5176): [StartReceiver][checkEUTStatus] eutStatus = 
D/PCSuite ( 5176): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5176): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  839): Killing 4906:com.lge.drmservice/u0a51 (adj 15): empty #11
D/WeatherAncestor( 2657): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 9:5:20
W/libprocessgroup(  839): failed to open /acct/uid_10051/pid_4906/cgroup.procs: No such file or directory
,D/UpdateThreadPoolManager( 2657): 2 : This is isUpdating : false
D/WeatherAncestor( 2657): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 9:5:20
D/WeatherService( 2657): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
W/ActivityManager(  839): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2657): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2657): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2657): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2657): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2657): 2 : This is isUpdating : false
D/WeatherService( 2657): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2657): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2657): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2657): 2 : Fixed theme : optimus
V/UserPresentBroadcastReceiver( 1739): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/WeatherReflect( 2657): 2 : Map key string is -2
D/lim     ( 2657): 2 : time = 09:05
,I/WeatherReflect( 2657): Model Name : LG-D722
D/WeatherTheme( 2657): 2 : exactly same view!
D/WeatherTheme( 2657): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
W/ActivityManager(  839): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2657): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2657): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2657): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
V/LGMDMManager( 5105): Create singleton instance
,I/DigitalAppWidgetProvider( 5129): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 2657): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 9:5:20
D/UpdateThreadPoolManager( 2657): 2 : This is isUpdating : false
D/Weather_cast( 2657): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2657): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 9:5:20
D/WeatherService( 2657): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
W/ActivityManager(  839): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2657): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2657): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2657): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/AlertReceiver( 3821): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
D/AlertService( 3821): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 3821): [updateWidgets] 
,D/MonthWidgetProvider( 3821): [onReceive]
D/CalendarWidgetProvider( 3821): [onReceive]
D/CalendarWidgetProvider( 3821): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 3821): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 3821): [onReceive]
D/CalendarWidgetProvider( 3821): [onReceive]
D/CalendarWidgetProvider( 3821): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 3821): [onCreate] mContext.getPackageName() = com.android.calendar
I/[SystemUI]SafeModeBroadcastReceiver( 1371): onReceive = com.lge.statusbar.bootcompleted
,D/CalendarWeatherReceiver( 3821): Get action=com.lge.calendar.action.WEATHER_SERVICE_START
I/ActivityManager(  839): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.MediaScanReceiver: pid=5198 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,E/MediaScanReceiver( 5198): media scanning start or checking
W/MainApplication( 5198): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ActivityManager(  839): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5215 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 4928:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10061/pid_4928/cgroup.procs: No such file or directory
,I/chromium( 4799): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
I/chromium( 4799): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,I/MusicStore( 5215): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5215): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
,W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5215): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5215): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/art     (  839): Explicit concurrent mark sweep GC freed 27540(1490KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.184ms total 154.426ms
,W/ResourcesManager( 5215): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5215): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5215): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5215): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5215): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3bb4fd65: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5215): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5215): GMSCore installation verified
,I/ConfigStore( 5215): Config Database version: 1
,I/MediaRouter( 5215): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/ToneMappingReceiver( 5129): Enter doAlarmRingToneUriMapping()
,I/NetworkMonitor( 5215): type=WIFI subType= reason=null isConnected=true
D/ToneMappingReceiver( 5129): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5129): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
,D/CommonUtil( 5129): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5129): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5129): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5129): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5129): Alarm Success count is 0
D/ToneMappingReceiver( 5129): Timer Success count is 0
I/MediaScannerReceiver( 3821): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///system/media
I/NetworkMonitor( 5215): type=WIFI subType= reason=null isConnected=true
,I/InitNotificationRingtoneService( 3821): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3821): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
E/MediaScanReceiver( 5198): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 5198): android.intent.action.MEDIA_SCANNER_FINISHED
,I/AlertUtils( 3821): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/GHttpClientFactory( 5215): Using our fixed implementation of GMSCore's GoogleHttpClient
I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/GoogleURLConnFactory( 5215): Using platform SSLCertificateSocketFactory
I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
E/MediaScanReceiver( 5198): media scanning start or checking
,I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/NotificationManager( 5215): com.google.android.music: cancel(1061) by com.google.android.music
,D/ToneMappingReceiver( 5129): Enter doAlarmRingToneUriMapping()
D/ToneMappingReceiver( 5129): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5129): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5129): getFinededDefaultTone() -> backup ringtone value : null
,D/CommonUtil( 5129): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5129): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5129): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5129): Alarm Success count is 0
,D/ToneMappingReceiver( 5129): Timer Success count is 0
I/ActivityManager(  839): Killing 4982:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/art     ( 3140): Explicit concurrent mark sweep GC freed 15776(840KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/10MB, paused 400us total 46.914ms
,I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3821): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
W/libprocessgroup(  839): failed to open /acct/uid_10079/pid_4982/cgroup.procs: No such file or directory
,I/MediaScannerReceiver( 3821): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///storage/emulated/0
I/AlertUtils( 3821): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3821): End InitializeAlertRingtoneService.onHandleIntent
E/MediaScanReceiver( 5198): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 5198): android.intent.action.MEDIA_SCANNER_FINISHED
I/InitNotificationRingtoneService( 3821): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3821): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/AlertUtils( 3821): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/ActivityManager(  839): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5259 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3821): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3821): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,W/ResourcesManager( 5259): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AlertUtils( 3821): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3821): End InitializeAlertRingtoneService.onHandleIntent
,D/CalendarProvider2( 5259): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@24743d27
,D/CalendarProvider2( 5259): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5259): Created com.android.providers.calendar.CalendarAlarmManager@31172140(com.android.providers.calendar.CalendarProvider2@24743d27)
D/CalendarProviderBroadcastReceiver( 5259): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5259): [IntentService] WakeLock acquire, start IntentSerivce
I/art     ( 5215): CheckpointMarkThreadRoots callback created = 0xb042d3f0
,D/CalendarProvider2( 5259): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 5259): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5259): [getOrCreateCalendarAlarmManager]
I/art     ( 5215): CheckpointMarkThreadRoots callback created = 0xb042d3b0
,D/WearableService( 1739): callingUid 10006, callindPid: 1739
,D/LocationInitializer( 4266): Restart initialization of location
D/CalendarProvider2( 5259): [IntentService] Release Lock
D/CalendarProvider2( 5259): CalendarProviderIntentService.onDestroy()
D/AuthorizationBluetoothService( 1739): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1739): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1739): com.google.android.gms: cancel(0) by com.google.android.gms
,I/MediaStoreImporter( 5215): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  839): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5288 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1739): No location to return for getLastLocation()
W/FusedLocationProvider( 1739): location=null
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{3b18d4a2 type 2 when 76678 android} when 76678
,W/IcingInternalCorpora( 4266): getNumBytesRead when not calculated.
,W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5288): getAccountsCursor
,W/GAV2    ( 5288): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  839): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
E/Gmail   ( 5288): Error finding the version of the Email provider.....
E/Gmail   ( 5288): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5288): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5288): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5288): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5288): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5288): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5288): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5288): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5288): We do not support migrating this version of the Email provider.
,I/Gmail   ( 5288): Observing account changes for notifications
,W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/art     (  839): Explicit concurrent mark sweep GC freed 12352(671KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 3.365ms total 148.567ms
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1739): No location to return for getLastLocation()
W/FusedLocationProvider( 1739): location=null
,I/Gmail   ( 5288): getAccountsCursor
V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  839): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5338 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 4266): Explicit concurrent mark sweep GC freed 18657(1443KB) AllocSpace objects, 29(464KB) LOS objects, 40% free, 12MB/20MB, paused 5.597ms total 96.729ms
,V/DownloadManager( 3140): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3140): created cursor android.database.sqlite.SQLiteCursor@2c1e62b8 on behalf of 4266
D/PhoneMonitor( 5338): Register our PhoneStateListener
,I/ActivityManager(  839): Killing 5051:com.android.chrome/u0a48 (adj 15): empty #11
,D/PhoneMonitor( 5338): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/Gmail   ( 5288): notifyAccountChanged
I/Gmail   ( 5288): getAccountsCursor
I/Gmail   ( 5288): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5288): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5288): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5288): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/libprocessgroup(  839): failed to open /acct/uid_10048/pid_5051/cgroup.procs: No such file or directory
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/TelephonyAutoProfiling( 5338): [loadFeatureFromXml] *** start feature loading from xml
V/DownloadManager( 3140): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3140): created cursor android.database.sqlite.SQLiteCursor@1d544891 on behalf of 4266
D/TelephonyAutoProfiling( 5338): [parse] Load xml
,V/DownloadManager( 3140): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3140): created cursor android.database.sqlite.SQLiteCursor@1c2543f6 on behalf of 4266
V/TelephonyAutoProfiling( 5338): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5338): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/CheckinService( 4266): Checkin interval check for package: unspecified last checkin: 1457078720413 min interval config: 0 actual interval: 2999
,D/PhoneMonitor( 5338): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/GCM     ( 1739): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/CheckinService( 4266): Checking schedule, now: 1457078723422 next: 1457078750375
I/CheckinService( 4266): active receiver: disabled
I/ActivityManager(  839): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5370 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/Gmail   ( 5288): getAccountsCursor
V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 5370): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/art     ( 3971): Explicit concurrent mark sweep GC freed 3378(132KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 372us total 25.447ms
I/Babel_SMS( 5370): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5370): MmsConfig.loadMmsSettings
I/Babel_SMS( 5370): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5370): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5370): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5370): MmsConfig.loadFromResources
E/Babel_SMS( 5370): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5370): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5370): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5370): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5370): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5370): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 5370): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5370): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5370): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5370): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5370): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5370): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5370): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5370): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5370): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5370): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5370): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5370): found sensor: Motion Accel, handle=46
W/Settings( 5370): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5370): startup - clean
I/Babel   ( 5370): deleted: false for 0
,I/art     ( 5370): CheckpointMarkThreadRoots callback created = 0xb042d8e0
,I/art     ( 5370): CheckpointMarkThreadRoots callback created = 0xb042d8c0
,I/ThermalEngine(  289): Sensor:pa_therm0:33000 mC
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,W/art     ( 5370): Suspending all threads took: 28.670ms
,I/ActivityManager(  839): Killing 5071:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/AudioCapabilities( 5370): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5370): Unsupported mime audio/adpcm
W/AudioCapabilities( 5370): Unsupported mime audio/g726
W/AudioCapabilities( 5370): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5370): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5370): Unsupported mime video/mjpg
W/VideoCapabilities( 5370): Unsupported mime video/theora
,W/AudioCapabilities( 5370): Unsupported mime audio/evrc
,W/AudioCapabilities( 5370): Unsupported mime audio/qcelp
W/VideoCapabilities( 5370): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5370): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5370): Unsupported mime audio/qcelp
W/AudioCapabilities( 5370): Unsupported mime audio/evrc
W/VideoCapabilities( 5370): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5370): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5370): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5370): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5370): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5370): Unrecognized profile 2130706433 for video/avc
W/libprocessgroup(  839): failed to open /acct/uid_10086/pid_5071/cgroup.procs: No such file or directory
,I/ActivityManager(  839): Killing 5155:com.android.settings/1000 (adj 15): empty #11
I/vclib   ( 5370): onServiceConnected
W/Babel   ( 5370): Attempted to change video mute state without an active call.
,I/NotificationManager( 5370): com.google.android.talk: cancel(10436) by com.google.android.talk
I/ActivityManager(  839): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5402 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_5155/cgroup.procs: No such file or directory
,I/AudioManager( 5105): getMode name:com.lge.qremote
,I/AudioManager( 5105): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5402): Quickset Services start...
I/UEI.SmartControl( 5402): Manufacture = LGE
I/ActivityManager(  839): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5420 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,D/UEI.SmartControl( 5402): File observer start...
E/UEI.SmartControl( 5402): IR Port is disabled: false
D/UEI.SmartControl( 5402): Starting file observer...
D/UEI.SmartControl( 5402): Extracting JNI libs...
D/UEI.SmartControl( 5402): --- this system supports 32-bit or 64-bit only
I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 21.211ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 20.946ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.695ms
W/ResourcesManager( 5420): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5420): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5420): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/NotificationManager( 2025): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,I/LGEmail ( 5420): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 5420): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/UEI.SmartControl( 5402): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5402): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5402): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 5402): --- Selecting new region: 2
I/UEI.SmartControl( 5402): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5402): Platform has CIR...
,D/UEI.SmartControl( 5402): NO CIR support, need to check package...
I/UEI.SmartControl( 5402): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5402): QS Service created
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PackageChangeReceiver( 5420): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,E/UEI.SmartControl( 5402): QS start get config
,I/ActivityManager(  839): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5445 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  839): Killing 5176:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 5402): Loading JNI Libs...
D/UEI.SmartControl( 5402):  configuring local db...
W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_5176/cgroup.procs: No such file or directory
,I/ActivityManager(  839): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5468 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 5129:com.lge.clock/u0a10 (adj 15): empty #11
,D/UEI.SmartControl( 5402):  ---- Has DB8: true
,W/libprocessgroup(  839): failed to open /acct/uid_10010/pid_5129/cgroup.procs: No such file or directory
D/UEI.SmartControl( 5402): QS start statue = true Error code = 0
,D/UEI.SmartControl( 5402): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5402): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5402): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5402): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5402): IrrcClient ++ 
D/irrcClient( 5402): getIrrcService ++ 
D/irrcClient( 5402): getIrrcService -- 
D/irrcClient( 5402): IrrcClient -- 
W/irrc_jni( 5402): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 5402): Services init done
I/UEI.SmartControl( 5402): Device manager: loading config....
D/UEI.SmartControl( 5402): Config is loaded...
,I/AppUp4:AppBoxCP( 5468): onCreate
D/UEI.SmartControl( 5402): QS Service init finished
W/AppUp4:DB( 5468):  [AppBoxDatabaseHelper] construct
D/UEI.SmartControl( 5402): QS Service version name: 0.1.73
D/UEI.SmartControl( 5402): QS Service version code: 1073
D/UEI.SmartControl( 5402): Service requested: Control
I/AppUp4:DB( 5468):  setFingerPrint start
I/AppUp4:DB( 5468):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
D/UEI.SmartControl( 5402): Internal service binding...
,D/UEI.SmartControl( 5402): -----IControl: 11
I/AppUp4:DB( 5468):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5468):  SDK version = 0
D/UEI.SmartControl( 5402): Caller: com.lge.qremote
I/AppUp4:DB( 5468):  beforefinger == newfinger no write in DB
D/UEI.SmartControl( 5402): ------------ IControl registerCallback...
D/AppUp4:AppBoxApplication( 5468): AppBoxApplication onCreate()
I/UEI.SmartControl( 5402): Registering callback...
,D/UEI.SmartControl( 5402): -----IControl: 19
D/UEI.SmartControl( 5402): Caller: com.lge.qremote
I/UEI.SmartControl( 5402): Registering Services Ready callback...
I/UEI.SmartControl( 5402): Notify client services are ready...
D/UEI.SmartControl( 5402):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5402): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5402): -----IControl: 8
D/UEI.SmartControl( 5402): Caller: com.lge.qremote
,I/ActivityManager(  839): Killing 5215:com.google.android.music:main/u0a81 (adj 15): empty #11
D/AppUp4:PreloadHelper( 5468): removed from Exclude : com.test.thalitest : 1
,I/ActivityManager(  839): Killing 5198:com.lge.bnr/1000 (adj 15): empty #12
,W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_5198/cgroup.procs: No such file or directory
,W/libprocessgroup(  839): failed to open /acct/uid_10081/pid_5215/cgroup.procs: No such file or directory
I/ActivityManager(  839): Killing 5259:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10014/pid_5259/cgroup.procs: No such file or directory
,I/ActivityManager(  839): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5488 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 5488): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5488): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5488): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 5488): Total System Memory = 906309632
,I/GalleryUtils( 5488): Application Heap = 96 MB
I/AppConfig( 5488): App Tier : NOT_DEF
D/SystemHelper( 5488): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  839): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5507 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  839): Killing 5288:com.google.android.gm/u0a53 (adj 15): empty #11
,D/AlertService( 3821): Beginning updateAlertNotification
,I/ActivityManager(  839): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5524 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/libprocessgroup(  839): failed to open /acct/uid_10053/pid_5288/cgroup.procs: No such file or directory
,W/ResourcesManager( 5507): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5507): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5507): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5524): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5524): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@24743d27
,D/CalendarProvider2( 5524): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5524): Created com.android.providers.calendar.CalendarAlarmManager@31172140(com.android.providers.calendar.CalendarProvider2@24743d27)
,D/AlertService( 3821): No fired or scheduled alerts
I/NotificationManager( 3821): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3821): com.android.calendar: cancel(1) by com.android.calendar
,I/NotificationManager( 3821): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3821): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3821): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3821): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3821): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3821): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3821): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3821): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3821): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3821): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3821): com.android.calendar: cancel(12) by com.android.calendar
,I/NotificationManager( 3821): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3821): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3821): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3821): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3821): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3821): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3821): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3821): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 3821): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,I/ActivityManager(  839): Killing 5338:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10038/pid_5338/cgroup.procs: No such file or directory
,D/AlarmScheduler( 3821): No events found starting within 1 week.
I/SystemConfig( 5507): BUILD Country: EU
I/SystemConfig( 5507): BUILD Operator: OPEN
,I/SystemConfig( 5507): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5507): existFile = false
,I/SystemConfig( 5507): canReadFile = false
I/SystemConfig( 5507): systemFeature RCS result false
D/SystemConfig( 5507): refreshRcsSupport() :false
I/ActivityManager(  839): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5551 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  839): Killing 3971:com.google.process.gapps/u0a6 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10006/pid_3971/cgroup.procs: No such file or directory
,I/LockScreenSettings( 5551): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 5551): New app installed broadcast received ..
,I/LockScreenSettings( 5551): Number of installed packages  1
I/ActivityManager(  839): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5568 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  839): Killing 5370:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10061/pid_5370/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 5568): action : android.intent.action.PACKAGE_ADDED
,D/EulaProviderUpdateObserver( 5568): uri : package:com.test.thalitest
I/ActivityManager(  839): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5588 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  839): Killing 4961:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10006/pid_4961/cgroup.procs: No such file or directory
,D/[BNRAppListMgrReceiver]( 5588): android.intent.action.PACKAGE_ADDED : com.test.thalitest
,W/MainApplication( 5588): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ActivityManager(  839): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5605 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 5105:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10106/pid_5105/cgroup.procs: No such file or directory
,I/art     (  839): Explicit concurrent mark sweep GC freed 18032(853KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 3.149ms total 200.321ms
,I/GAv4    ( 5605): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5605):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5605):   adb logcat -s GAv4
,W/GAv4    ( 5605): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5605): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5605): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5605): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5605): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 5605): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5605): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  839): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5638 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  839): Killing 5402:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10089/pid_5402/cgroup.procs: No such file or directory
,W/ResourcesManager( 5638): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 5605): CheckpointMarkThreadRoots callback created = 0xb050fa30
,V/JNIHelp ( 5605): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 5605): CheckpointMarkThreadRoots callback created = 0xb050fa00
,I/ActivityManager(  839): Killing 5420:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10021/pid_5420/cgroup.procs: No such file or directory
,W/System  ( 5605): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5605): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  839): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5671 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 25.055ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.716ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 20.937ms
,I/CheckinService( 4266): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  839): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5691 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 2025): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/GservicesProvider( 5671): Gservices pushing to system: true; secure/global: true
I/UpdateIcingCorporaServi( 2025): UpdateCorporaTask done [took 150 ms] updated apps [took 149 ms] 
,I/GoogleHttpClient( 5671): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5671): GMS http client unavailable, use old client
,I/ActivityManager(  839): Killing 5445:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10009/pid_5445/cgroup.procs: No such file or directory
,D/Finsky  ( 5691): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5691): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,I/ThermalEngine(  289): Sensor:pa_therm0:33000 mC
,W/Settings( 5691): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5691): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5691): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3140): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3140): created cursor android.database.sqlite.SQLiteCursor@1cd713f7 on behalf of 5691
I/NotificationManager( 5691): com.android.vending: cancel(1003285959) by com.android.vending
D/Ads     ( 5691): Skipping gmscore version check
,D/Finsky  ( 5691): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5691): [1] Libraries$2.run: Finished loading 1 libraries.
D/ChimeraCfgMgr( 4266): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/PackageBroadcastService( 4266): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/ChimeraModuleLdr( 4266): Loading module APK com.google.android.play.games
D/Finsky  ( 5691): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/InitAlarmsService( 3821): Clearing and rescheduling alarms.
D/Finsky  ( 5691): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/CalendarProvider2( 5524): Scheduling check of next Alarm
D/CalendarProvider2( 5524): SCHEDULE_ALARM_REMOVE
D/Finsky  ( 5691): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  839): Killing 3821:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10013/pid_3821/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 4266): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4266): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4266): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 4266): Submit a task: k
,D/ChimeraCfgMgr( 4266): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 4266): Loading module com.google.android.gms.vision from APK com.google.android.gms
,I/Icing   ( 4266): Storage manager: low false usage 1.74MB avail 2.37GB capacity 4.06GB
D/k       ( 4266): Processing package: com.test.thalitest
,D/GassUtils( 4266): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 4266): Found info for package com.test.thalitest in db.
,I/ActivityManager(  839): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5764 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/BaseAppContext( 4266): Using Auth Proxy for data requests.
W/BaseAppContext( 4266): Using Auth Proxy for data requests.
,W/BaseAppContext( 4266): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 4266): cleanUpNonGplusAccounts done.
W/BaseAppContext( 4266): Using Auth Proxy for data requests.
,W/ResourcesManager( 5764): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/BaseAppContext( 4266): Using Auth Proxy for data requests.
,D/BluetoothManagerService(  839): Message: 20
D/BluetoothManagerService(  839): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@acb837a:true
,D/BluetoothAdapterService(434966892)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@8ee7222
D/BluetoothAdapterService(434966892)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@8ee7222
,I/AudioManager( 5764): getMode name:com.lge.qremote
I/AudioManager( 5764): getMode name:com.lge.qremote
,I/AudioManager( 5764): getMode name:com.lge.qremote
D/WearableService( 1739): callingUid 10006, callindPid: 1739
,E/MDM     ( 1739): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1739): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4266): Restart initialization of location
V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1739): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  839): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=5789 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/GCoreFlp( 1739): No location to return for getLastLocation()
,W/FusedLocationProvider( 1739): location=null
,W/ResourcesManager( 5789): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Icing   ( 4266): updateResources: need to parse f{com.google.android.gms}
,I/Babel_SMS( 5789): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5789): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5789): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5789): MmsConfig.loadFromDatabase
I/CalendarProvider2( 5524): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5524): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/Icing   ( 4266): Internal init done: storage state 0
,E/Babel_SMS( 5789): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5789): MmsConfig.loadFromResources
,E/Babel_SMS( 5789): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5789): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Icing   ( 4266): Post-init done
,D/SensorManager( 5789): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5789): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5789): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5789): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5789): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5789): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5789): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5789): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5789): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5789): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5789): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
,D/SensorManager( 5789): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5789): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5789): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5789): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5789): found sensor: Motion Accel, handle=46
D/ChimeraCfgMgr( 4266): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4266): Module APK com.google.android.play.games already loaded
,W/Settings( 5789): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5789): startup - clean
I/art     ( 5789): CheckpointMarkThreadRoots callback created = 0xb042d8c0
,I/Babel   ( 5789): deleted: false for 0
I/art     ( 5789): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,I/ActivityManager(  839): Killing 5468:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/[SystemUI]QPairHandler( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1908): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[LGHome]EVENT( 1947): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
W/AudioCapabilities( 5789): Unsupported mime audio/x-lg-flac
I/InputReader(  839): Reconfiguring input devices.  changes=0x00000010
W/AudioCapabilities( 5789): Unsupported mime audio/adpcm
,W/AudioCapabilities( 5789): Unsupported mime audio/g726
W/AudioCapabilities( 5789): Unsupported mime audio/x-ms-wma
I/[LGHome]LGPlusHomeDBManager( 1947): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
W/AudioCapabilities( 5789): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5789): Unsupported mime video/mjpg
I/[LGHome]LGPlusHomeDBManager( 1947): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
W/VideoCapabilities( 5789): Unsupported mime video/theora
W/BroadcastQueue(  839): Exception when sending broadcast to ComponentInfo{com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper}
W/BroadcastQueue(  839): android.os.DeadObjectException
W/BroadcastQueue(  839): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue(  839): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue(  839): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:857)
W/BroadcastQueue(  839): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:270)
W/BroadcastQueue(  839): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1002)
W/BroadcastQueue(  839): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16810)
W/BroadcastQueue(  839): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:473)
W/BroadcastQueue(  839): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2625)
W/BroadcastQueue(  839): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:457)
W/BroadcastQueue(  839): 	at android.os.Binder.execTransact(Binder.java:446)
W/libprocessgroup(  839): failed to open /acct/uid_10011/pid_5468/cgroup.procs: No such file or directory
,D/administrator(  839): Handling package changes for user 0
W/AudioCapabilities( 5789): Unsupported mime audio/evrc
W/AudioCapabilities( 5789): Unsupported mime audio/qcelp
W/VideoCapabilities( 5789): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5789): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5789): Unsupported mime audio/qcelp
,I/[LGHome]Launcher( 1947): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  839): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5823 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ActivityManager(  839): Spurious death for ProcessRecord{2074a5ad 5823:com.lge.appbox.client/u0a11}, curProc for 5468: null
,I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
W/AudioCapabilities( 5789): Unsupported mime audio/evrc
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
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,W/VideoCapabilities( 5789): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5789): Unsupported profile 4 for video/mp4v-es
,I/NotificationService(  839): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  839): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  839): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  839): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/VideoCapabilities( 5789): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5789): Unrecognized profile 2130706433 for video/avc
,V/BackupManagerService(  839): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  839): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@22cbf6cb
W/VideoCapabilities( 5789): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5789): Unrecognized profile 2130706433 for video/avc
,I/AppUp4:AppBoxCP( 5823): onCreate
W/AppUp4:DB( 5823):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5823):  setFingerPrint start
I/AppUp4:DB( 5823):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5823):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5823):  SDK version = 0
,I/AppUp4:DB( 5823):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5823): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 5823): onReceive
,I/AppUp4:CustModeStarterReceiver( 5823): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5823): Context : android.app.ReceiverRestrictedContext@26270872
D/AppUp4:CustFacade( 5823): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5823): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 5823): begin check event
I/AppUp4:CustModeStarterReceiver( 5823): Event For Nothing, skip.
I/ActivityManager(  839): Killing 5488:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10023/pid_5488/cgroup.procs: No such file or directory
,W/ResourcesManager(  839): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  839): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5844 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
W/ResourceType(  839): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/vclib   ( 5789): onServiceConnected
,W/Babel   ( 5789): Attempted to change video mute state without an active call.
I/NotificationManager( 5789): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 5789): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5789): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1947): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1739): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,W/ResourcesManager( 5844): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5844): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5844): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,V/JNIHelp ( 5789): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/LCardEmulationManager( 1823): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1823): getDefaultRoute
,I/AppConfig( 5844): Total System Memory = 906309632
,I/GalleryUtils( 5844): Application Heap = 96 MB
I/AppConfig( 5844): App Tier : NOT_DEF
W/System  ( 5789): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5789): Installed default security provider GmsCore_OpenSSL
D/SystemHelper( 5844): region [EU], country [EU], operator [OPEN], sub-operator []
,I/NotificationManager( 5789): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/art     (  839): Explicit concurrent mark sweep GC freed 30774(1511KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 3.716ms total 172.897ms
D/LockScreenSettings( 5551): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5551): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5551): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5551): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5551): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,D/LocationProviderProxy(  839): applying state to connected service
I/ActivityManager(  839): Killing 5568:com.lge.eula/1000 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 2025): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/UpdateIcingCorporaServi( 2025): UpdateCorporaTask done [took 49 ms] updated apps [took 49 ms] 
,W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_5568/cgroup.procs: No such file or directory
,I/Icing   ( 4266): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
D/PackageBroadcastService( 4266): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4266): Null package name or gms related package.  Ignoreing.
D/Icing   ( 4266): Loaded CLD2 Version V2.0 - 20141016
,I/ActivityManager(  839): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5880 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 4266): updateResources: need to parse f{com.google.android.gms}
,V/LGMDMManager( 5764): Create singleton instance
,D/UEI.SmartControl( 5880): Quickset Services start...
,I/UEI.SmartControl( 5880): Manufacture = LGE
D/UEI.SmartControl( 5880): File observer start...
E/UEI.SmartControl( 5880): IR Port is disabled: false
D/UEI.SmartControl( 5880): Starting file observer...
D/UEI.SmartControl( 5880): Extracting JNI libs...
D/UEI.SmartControl( 5880): --- this system supports 32-bit or 64-bit only
,I/Icing   ( 4266): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/AudioManager( 5764): getMode name:com.lge.qremote
I/ActivityManager(  839): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5899 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/UEI.SmartControl( 5880): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5880): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5880): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 5880): --- Selecting new region: 2
I/UEI.SmartControl( 5880): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5880): Platform has CIR...
D/UEI.SmartControl( 5880): NO CIR support, need to check package...
I/UEI.SmartControl( 5880): Model: LG-D722 uses JNI
D/PhoneMonitor( 5899): Register our PhoneStateListener
D/UEI.SmartControl( 5880): QS Service created
E/UEI.SmartControl( 5880): QS start get config
,V/SetupWizard( 5899): Connected to Gservices successfully
I/ActivityManager(  839): Killing 5588:com.lge.bnr/1000 (adj 15): empty #11
,D/PhoneMonitor( 5899): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5899): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5899): [parse] Load xml
V/TelephonyAutoProfiling( 5899): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5899): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5899): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/UEI.SmartControl( 5880): Loading JNI Libs...
,D/UEI.SmartControl( 5880):  configuring local db...
W/libprocessgroup(  839): failed to open /acct/uid_1000/pid_5588/cgroup.procs: No such file or directory
,I/AudioManager( 5764): getMode name:com.lge.qremote
,I/ActivityManager(  839): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5923 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GCM     ( 1739): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/UEI.SmartControl( 5880):  ---- Has DB8: true
,D/UEI.SmartControl( 5880): QS start statue = true Error code = 0
D/UEI.SmartControl( 5880): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5880): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5880): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5880): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5880): IrrcClient ++ 
D/irrcClient( 5880): getIrrcService ++ 
,D/irrcClient( 5880): getIrrcService -- 
D/irrcClient( 5880): IrrcClient -- 
W/irrc_jni( 5880): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5880): Services init done
I/UEI.SmartControl( 5880): Device manager: loading config....
D/UEI.SmartControl( 5880): QS Service init finished
,D/UEI.SmartControl( 5880): Config is loaded...
D/UEI.SmartControl( 5880): QS Service version name: 0.1.73
D/UEI.SmartControl( 5880): QS Service version code: 1073
D/UEI.SmartControl( 5880): Service requested: Control
D/UEI.SmartControl( 5880): Internal service binding...
D/UEI.SmartControl( 5880): -----IControl: 11
,D/UEI.SmartControl( 5880): Caller: com.lge.qremote
D/UEI.SmartControl( 5880): ------------ IControl registerCallback...
I/UEI.SmartControl( 5880): Registering callback...
D/UEI.SmartControl( 5880): -----IControl: 19
D/UEI.SmartControl( 5880): Caller: com.lge.qremote
I/UEI.SmartControl( 5880): Registering Services Ready callback...
I/UEI.SmartControl( 5880): Notify client services are ready...
D/UEI.SmartControl( 5880): -----IControl: 8
D/UEI.SmartControl( 5880): Caller: com.lge.qremote
,I/ActivityManager(  839): Killing 5524:com.android.providers.calendar/u0a14 (adj 15): empty #11
D/UEI.SmartControl( 5880):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5880): Notify AllClients services are ready: 0
,I/ActivityManager(  839): Killing 5605:com.google.android.apps.docs/u0a58 (adj 15): empty #12
,W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/libprocessgroup(  839): failed to open /acct/uid_10014/pid_5524/cgroup.procs: No such file or directory
W/libprocessgroup(  839): failed to open /acct/uid_10058/pid_5605/cgroup.procs: No such file or directory
I/Gmail   ( 5923): getAccountsCursor
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5923): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5923): Error finding the version of the Email provider.....
E/Gmail   ( 5923): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5923): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5923): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5923): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5923): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5923): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5923): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5923): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5923): We do not support migrating this version of the Email provider.
,I/Gmail   ( 5923): getAccountsCursor
V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  839): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  839): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  839): Killing 5823:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/Gmail   ( 5923): Observing account changes for notifications
,W/libprocessgroup(  839): failed to open /acct/uid_10011/pid_5823/cgroup.procs: No such file or directory
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1739): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/AudioManager( 5764): getMode name:com.lge.qremote
I/AudioManager( 5764): getMode name:com.lge.qremote
,I/Icing   ( 4266): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/Icing   ( 4266): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  839): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=5969 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 5923): notifyAccountChanged
,I/Gmail   ( 5923): getAccountsCursor
I/Gmail   ( 5923): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/ResourcesManager( 5969): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5923): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5923): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5923): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/CalendarApplication( 5969): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 5969): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 5969): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3500a17d, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@26270872, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@1d5d84c3, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@31172140, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2a7ad879, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2ad939be, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1509aa1f, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@19ed116c, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2ac78335, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@30eb33ca, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1628c93b, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3b4fd858, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@fa1db1, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@770c296, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@1c50be17, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@5162204, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@3be1e3ed, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@8ee7222, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1c9924b3, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2bd55a70, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@e05d1e9, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@1a58e6e, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@3bf7590f, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@160dad9c, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@3160a3a5, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2ea0237a, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@f5a772b, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@30160788, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@adcd521, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@217cfd46, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@1875b07, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@12c81434, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@990a25d, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@14fba7d2, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@3ab4a0a3, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@28ec3fa0, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3dba0759, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@3e486f1e, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@25e6a3ff, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3f65b5cc, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@237ac015, lg_preferences_recent,_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@27085f2a,
D/GeneralPreferenceUtils( 5969): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 5969): [init]
I/Config  ( 5969): LGCalendar ver.4.40.17
I/Config  ( 5969): start check model
I/Config  ( 5969): start check native_ca
I/Config  ( 5969): Config Operator=OPEN, Country=EU
D/Config  ( 5969): [setDefaultValuesToPref]
D/Config  ( 5969): [parseProfiles]
D/ProfilesParser( 5969): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 5969): [debug_displayParseInfos] profile.operator = null
D/Config  ( 5969): [updateProfiletoCountryInfo]
D/GeneralPreference( 5969): [checkAndMigrateOldPreference]
D/AlertReceiver( 5969): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 5969): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 5969): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/art     ( 1739): Explicit concurrent mark sweep GC freed 32943(2MB) AllocSpace objects, 23(368KB) LOS objects, 40% free, 13MB/22MB, paused 1.409ms total 95.402ms
I/AlertUtils( 5969): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 5969): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 5969): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 5969): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 5969): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 5969): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 5969): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 5969): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 5969): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 5969): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 5969): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 5969): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 5969): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 5969): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 5969): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 5969): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 5969): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 5969): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 5969): End InitializeAlertRingtoneService.onHandleIntent
I/Gmail   ( 5923): getAccountsCursor
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/HolidayIntentService( 5969): onHandleIntent
,D/HolidayDataLoader( 5969): readJsonAsset : holiday.json
E/AgendaWidgetManager( 5969): [updateWidgets] 
,D/AlertService( 5969): 0 Action = android.intent.action.PROVIDER_CHANGED
D/MonthWidgetProvider( 5969): [onReceive]
D/CalendarWidgetProvider( 5969): [onReceive]
D/CalendarWidgetProvider( 5969): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 5969): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 5969): [onReceive]
D/CalendarWidgetProvider( 5969): [onReceive]
D/CalendarWidgetProvider( 5969): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,D/CalendarTypeController( 5969): [onCreate] mContext.getPackageName() = com.android.calendar
E/HolidayIntentService( 5969): onHandleIntent:holiday data empty
,I/art     (  839): Explicit concurrent mark sweep GC freed 14441(676KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 1.912ms total 145.316ms
,I/ActivityManager(  839): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6014 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 5789): com.google.android.talk: cancel(8) by com.google.android.talk
,I/AppUp4:AppBoxCP( 6014): onCreate
W/AppUp4:DB( 6014):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6014):  setFingerPrint start
I/AppUp4:DB( 6014):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6014):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6014):  SDK version = 0
,I/AppUp4:DB( 6014):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6014): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6014): onReceive
I/AppUp4:CustModeStarterReceiver( 6014): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6014): Context : android.app.ReceiverRestrictedContext@26270872
D/AppUp4:CustFacade( 6014): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6014): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6014): begin check event
I/AppUp4:CustModeStarterReceiver( 6014): Event For Nothing, skip.
I/ActivityManager(  839): Killing 5844:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10023/pid_5844/cgroup.procs: No such file or directory
,I/ActivityManager(  839): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6037 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/art     (  303): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 21.725ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 20.803ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 21.670ms
,W/ResourcesManager( 6037): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6037): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6037): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 6037): Total System Memory = 906309632
,I/GalleryUtils( 6037): Application Heap = 96 MB
I/AppConfig( 6037): App Tier : NOT_DEF
D/SystemHelper( 6037): region [EU], country [EU], operator [OPEN], sub-operator []
D/LockScreenSettings( 5551): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5551): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5551): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5551): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5551): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  839): Killing 5691:com.android.vending/u0a36 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 2025): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/UpdateIcingCorporaServi( 2025): UpdateCorporaTask done [took 42 ms] updated apps [took 42 ms] 
,W/libprocessgroup(  839): failed to open /acct/uid_10036/pid_5691/cgroup.procs: No such file or directory
,I/ActivityManager(  839): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6059 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 6059): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6059): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6059): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6059): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6059): com.android.vending: cancel(-1050172287) by com.android.vending
I/ThermalEngine(  289): Sensor:pa_therm0:33000 mC
,V/DownloadManager( 3140): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3140): created cursor android.database.sqlite.SQLiteCursor@37b2f264 on behalf of 6059
,D/Finsky  ( 6059): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6059): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 6059): Skipping gmscore version check
D/Finsky  ( 6059): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 4266): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4266): Null package name or gms related package.  Ignoreing.
,I/AudioManager( 5764): getMode name:com.lge.qremote
I/Icing   ( 4266): updateResources: need to parse f{com.google.android.gms}
D/Finsky  ( 6059): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/AudioManager( 5764): getMode name:com.lge.qremote
,I/AudioManager( 5764): getMode name:com.lge.qremote
V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{14a1ffd3 type 2 when 88154 com.android.providers.calendar} when 88154
,I/ActivityManager(  839): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6119 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  839): Killing 5899:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10038/pid_5899/cgroup.procs: No such file or directory
,W/ResourcesManager( 6119): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6119): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@24743d27
,D/CalendarProvider2( 6119): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6119): Created com.android.providers.calendar.CalendarAlarmManager@31172140(com.android.providers.calendar.CalendarProvider2@24743d27)
D/CalendarProviderBroadcastReceiver( 6119): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,D/CalendarProviderBroadcastReceiver( 6119): [IntentService] WakeLock acquire, start IntentSerivce
I/AudioManager( 5764): getMode name:com.lge.qremote
D/CalendarProvider2( 6119): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6119): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6119): [getOrCreateCalendarAlarmManager]
I/AudioManager( 5764): getMode name:com.lge.qremote
D/CalendarProvider2( 6119): [IntentService] Release Lock
,D/CalendarProvider2( 6119): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  839): Killing 6014:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10011/pid_6014/cgroup.procs: No such file or directory
,I/Icing   ( 4266): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4266): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  839): Killing 6037:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10023/pid_6037/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 5880): Internal timer expired: 1
,I/GAV2    ( 5923): Thread[GAThread,5,main]: No campaign data found.
,D/Finsky  ( 6059): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  839): RTC_WAKEUP set : Alarm{1eba83c3 type 0 when 1457078737614 com.android.vending} when 1457078737614
V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  839): android: cancelAsUser(2) by android
,D/libc-netbsd( 6059): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6059): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6059): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6059): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6059): propertyValue:false
D/libc-netbsd( 6059): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6059): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6059): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6059): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/AlertService( 5969): Beginning updateAlertNotification
D/AlertService( 5969): No fired or scheduled alerts
,I/NotificationManager( 5969): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 5969): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 5969): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5969): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 5969): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 5969): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 5969): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 5969): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 5969): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 5969): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 5969): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 5969): com.android.calendar: cancel(11) by com.android.calendar
,I/NotificationManager( 5969): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 5969): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 5969): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 5969): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 5969): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 5969): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 5969): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 5969): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 5969): com.android.calendar: cancel(20) by com.android.calendar
,D/AlertService( 5969): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 5969): No events found starting within 1 week.
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  839): android: cancelAsUser(2) by android
,I/ActivityManager(  839): Killing 5969:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10013/pid_5969/cgroup.procs: No such file or directory
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 92441791270; DSPS: 3127809; Offset : -3023556119
,I/qtaguid ( 6059): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6059): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6059): untagSocket(41) failed with errno -22
D/Finsky  ( 6059): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  839): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6164 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  839): android: cancelAsUser(2) by android
,W/ResourcesManager( 6164): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6164): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6164): VM with version 2.1.0 has multidex support
I/MultiDex( 6164): install
I/MultiDex( 6164): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6164): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6164): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6164): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d59a982: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6164): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6164): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6164): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1739): callingUid 10006, callindPid: 1739
,E/MDM     ( 1739): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1739): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 4266): Restart initialization of location
D/ChimeraCfgMgr( 6164): Reading stored module config
V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1739): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1739): No location to return for getLastLocation()
,W/FusedLocationProvider( 1739): location=null
D/ChimeraCfgMgr( 6164): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/CAR.SERVICE( 6164): Connecting to CarCallService...
,I/art     ( 6164): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6164): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/NativeLibraryUtils( 6164): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6164): com.google.android.projection.gearhead isn't installed.
,I/qtaguid ( 6059): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6059): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6059): untagSocket(41) failed with errno -22
I/ThermalEngine(  289): Sensor:pa_therm0:34000 mC
D/CAR.TEL.Service( 6164): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6164): Creating a new PhoneAdapter instance
W/ActivityManager(  839): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6164): setListener: com.google.android.gms.car.dn@2c7a2639
W/ActivityManager(  839): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6164): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6164): Starting CarCallService with initial phone null
I/NotificationManager( 6164): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6164): Package validated; name: com.android.vending
,I/NotificationManager( 6059): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6059): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/art     ( 6059): CheckpointMarkThreadRoots callback created = 0xb042d960
,I/art     ( 6059): CheckpointMarkThreadRoots callback created = 0xb042d940
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  839): android: cancelAsUser(2) by android
,I/qtaguid ( 6059): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6059): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6059): untagSocket(41) failed with errno -22
,W/ResourcesManager( 6059): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6059): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6059): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6059): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  839): RTC_WAKEUP set : Alarm{520f7e7 type 0 when 1457078740392 com.android.vending} when 1457078740392
D/DeviceConnectionService( 1739): client connected with version: 8296000
,D/Finsky  ( 6059): [749] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  839): android: cancelAsUser(2) by android
D/Finsky  ( 6059): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6059): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/libc-netbsd( 6059): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6059): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6059): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6059): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6059): propertyValue:false
,I/ActivityManager(  839): Killing 5789:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10061/pid_5789/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ActivityManager(  839): Killing 5507:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  839): failed to open /acct/uid_10018/pid_5507/cgroup.procs: No such file or directory
,I/ThermalEngine(  289): Sensor:pa_therm0:34000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/CAR.SERVICE( 6164): mConnectedToCar = false, abort
,E/ActivityThread( 6164): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@15077801 that was originally bound here
E/ActivityThread( 6164): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@15077801 that was originally bound here
E/ActivityThread( 6164): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6164): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6164): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6164): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6164): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6164): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6164): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6164): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6164): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6164): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6164): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6164): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6164): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6164): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6164): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6164): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6164): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6164): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6164): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6164): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6164): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6164): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6164): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6164): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@6f00e00 that was originally bound here
E/ActivityThread( 6164): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@6f00e00 that was originally bound here
E/ActivityThread( 6164): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6164): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6164): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6164): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6164): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6164): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6164): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6164): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6164): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6164): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6164): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6164): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6164): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6164): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6164): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6164): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6164): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6164): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6164): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6164): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6164): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6164): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/ActivityManager(  839): Unbind failed: could not find connection for android.os.BinderProxy@123cd2c
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/SQLiteConnectionPool( 4266): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/ThermalEngine(  289): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  289): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/AlarmManager(  839): RTC_WAKEUP set : Alarm{c9f3f5 type 0 when 1457078750375 com.google.android.gms} when 1457078750375
,V/AlarmManager(  839): RTC_WAKEUP set : Alarm{2e7c87fb type 0 when 1457078754585 com.android.vending} when 1457078754585
I/CheckinService( 4266): Checkin interval check for package: unspecified last checkin: 1457078720413 min interval config: 0 actual interval: 35635
,W/ContextImpl( 3616): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/CheckinService( 4266): Checking schedule, now: 1457078756127 next: 1457078750375
I/CheckinService( 4266): active receiver: enabled
,I/CheckinService( 4266): Preparing to send checkin request
I/EventLogService( 4266): Accumulating logs since 1457078716159
,I/CheckinRequestBuilder( 4266): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4266): Failed to find provider info for com.google.android.wearable.settings
,D/Finsky  ( 6059): [740] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
D/Finsky  ( 6059): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/art     (  839): Explicit concurrent mark sweep GC freed 29476(1367KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.411ms total 158.557ms
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  839): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6259 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 6259): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6259): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6259): VM with version 2.1.0 has multidex support
I/MultiDex( 6259): install
I/MultiDex( 6259): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6259): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6259): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6259): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d59a982: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6259): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6259): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6259): com.google.android.gms: cancel(39789) by com.google.android.gms
D/LocationInitializer( 4266): Restart initialization of location
,D/WearableService( 1739): callingUid 10006, callindPid: 1739
D/AuthorizationBluetoothService( 1739): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1739): com.google.android.gms: cancel(0) by com.google.android.gms
E/MDM     ( 1739): [142] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/GCoreFlp( 1739): No location to return for getLastLocation()
W/FusedLocationProvider( 1739): location=null
,I/art     ( 6259): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6259): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/NativeLibraryUtils( 6259): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): CdmEngine::OpenSession
I/WVCdm   (  278): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  278): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  278): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  278): L1 library not specified. Falling Back to L3
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  278): PrepareKeyRequest: nonce=571662531
I/art     ( 6259): CheckpointMarkThreadRoots callback created = 0xb042d5f0
,I/art     ( 6259): CheckpointMarkThreadRoots callback created = 0xb042d5e0
,I/dex2oat ( 6305): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6305): dex2oat took 114.175ms (threads: 4)
,I/Adreno-EGL( 6259): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6259): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6259): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6259): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6259): Remote Branch: 
I/Adreno-EGL( 6259): Local Patches: 
I/Adreno-EGL( 6259): Reconstruct Branch: 
,I/Adreno-EGL( 6259): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6259): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6259): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6259): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6259): Remote Branch: 
I/Adreno-EGL( 6259): Local Patches: 
I/Adreno-EGL( 6259): Reconstruct Branch: 
,I/Adreno-EGL( 6259): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6259): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6259): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6259): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6259): Remote Branch: 
I/Adreno-EGL( 6259): Local Patches: 
I/Adreno-EGL( 6259): Reconstruct Branch: 
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 112443260378; DSPS: 3783217; Offset : -3023551464
,I/CheckinRequestBuilder( 4266): Classify the device as Phone.
,D/libc-netbsd( 4266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 4266): propertyValue:false
D/libc-netbsd( 4266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4266): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4266): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4266): Sending checkin request (7778 bytes)
,I/ThermalEngine(  289): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinRequestBuilder( 4266): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4266): Failed to find provider info for com.google.android.wearable.settings
I/WVCdm   (  278): CdmEngine::CloseSession
I/WVCdm   (  278): L3 Terminate.
,I/CheckinRequestBuilder( 4266): Classify the device as Phone.
,I/CheckinTask( 4266): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4266): Checking schedule, now: 1457078759283 next: 1457606008280
I/CheckinService( 4266): active receiver: disabled
,D/CheckinService( 4266): Recording last checkin time for package unspecified as 1457078759307
I/ActivityManager(  839): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6330 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6330): Register our PhoneStateListener
,V/SetupWizard( 6330): Connected to Gservices successfully
,D/PhoneMonitor( 6330): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6330): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6330): [parse] Load xml
V/TelephonyAutoProfiling( 6330): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6330): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6330): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/GCM     ( 1739): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/MusicWidget( 2636): mDelayedStopHandler : unbind
,I/MusicBrowser( 2097): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2097): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2097): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2097): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2097): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2097): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2097): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2097): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,D/PowerManagerServiceEx(  839): acquireWakeLockInternal: lock=61186011, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=839
,I/MediaFocusControl(  839):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1a58e6ecom.lge.music.MediaPlaybackService$6@3bf7590f
,D/WeatherService( 2657): 2 : TimeTick Intent has been received, Time(hour:min:sec) 9:6:0
D/WeatherService( 2657): 2 : TimeTick Intent And Screen On
D/WeatherService( 2657): 2 : SDK version : 21
W/ActivityManager(  839): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2657): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2657): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2657): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2657): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2657): 2 : This is isUpdating : false
D/WeatherService( 2657): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2657): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2657): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2657): 2 : Fixed theme : optimus
,D/MusicBrowser( 2097): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
D/WeatherReflect( 2657): 2 : Map key string is -2
D/lim     ( 2657): 2 : time = 09:06
,I/WeatherReflect( 2657): Model Name : LG-D722
D/WeatherTheme( 2657): 2 : Different view - status_min_formatted : 05 != 06
D/WeatherTheme( 2657): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2657): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2657): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2657): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2657): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2657): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/MusicBrowser( 2097): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2097): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2097): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
,I/MusicBrowser( 2097): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@2ac78335
I/[SystemUI]Clock( 1371): called onTimeUpdated()
I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
,I/MusicBrowser( 2097): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/Weather4x2_optimus( 2657): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2657): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2657): forecast size is 0
D/Theme   ( 2657): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2657): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2657): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/Theme   ( 2657): strTheme: com.lge.launcher2.theme.optimus
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
,I/MusicBrowser( 2097): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2097): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2097): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2097): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2097): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2097): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2097): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2097): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
D/WeatherService( 2657): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 9:6:0
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/MusicBrowser( 2097): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,D/PowerManagerServiceEx(  839): releaseWakeLockInternal: lock=61186011 [*alarm*], flags=0x0
I/MusicBrowser( 2097): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2097): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2097): [MediaPlaybackService.java:6706:stop()] oooooo 
,I/MediaPlayer[Native]( 2097): reset
V/MediaPlayer[Native]( 2097): setListener
V/MediaPlayer[Native]( 2097): disconnect
V/MediaPlayer[Native]( 2097): destructor
V/AudioFlinger(  278): releasing 19 from 2097 for -1
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
V/MediaPlayer[Native]( 2097): disconnect
,D/MusicBrowser( 2097): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2097): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2097): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2097): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
,I/MusicBrowser( 2097): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2097): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2097): [SmartShareManagerClient] unregisterListener: 369995164
W/SmartShareClient( 2097): [SmartShareManagerClient] unregisterListener invalid listener: 369995164
,I/SmartShareClient( 2097): [SmartShareManagerClient] terminate service: 2097/MediaPlaybackService/492668099
E/HomeCloudIF( 2097): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2097): [SmartShareManagerClient] unbindService context:android.app.Application@3160a3a5
V/CloudHub( 2097): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2097): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2097): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2097): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,D/MusicBrowser( 2097): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  839): Killing 5551:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/CloudHub( 2097): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29995
W/libprocessgroup(  839): failed to open /acct/uid_10069/pid_5551/cgroup.procs: No such file or directory
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1947): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1947): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ActivityManager(  839): Killing 6119:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/ActivityManager(  839): Killing 5638:com.google.android.apps.plus/u0a86 (adj 15): empty #12
,W/libprocessgroup(  839): failed to open /acct/uid_10014/pid_6119/cgroup.procs: No such file or directory
,W/libprocessgroup(  839): failed to open /acct/uid_10086/pid_5638/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/ThermalEngine(  289): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/InputReader(  839): Reconfiguring input devices.  changes=0x00000010
,I/QCNEJ   ( 1908): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QPairHandler( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 1947): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1947): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,D/administrator(  839): Handling package changes for user 0
I/[LGHome]LGPlusHomeDBManager( 1947): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/ActivityManager(  839): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6384 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
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
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]Launcher( 1947): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/ResourcesManager( 6384): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationService(  839): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  839): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  839): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  839): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  839): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  839): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3d6c1f9b
,W/ResourcesManager(  839): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  839): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1947): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1739): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  839): applying state to connected service
,I/Babel_SMS( 6384): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6384): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6384): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6384): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6384): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6384): MmsConfig.loadFromResources
E/Babel_SMS( 6384): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6384): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6384): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6384): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6384): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6384): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6384): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6384): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6384): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6384): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6384): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6384): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6384): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6384): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6384): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6384): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6384): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6384): found sensor: Motion Accel, handle=46
,W/Settings( 6384): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6384): startup - clean
,I/Babel   ( 6384): deleted: false for 0
,D/LCardEmulationManager( 1823): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1823): getDefaultRoute
,I/art     ( 6384): CheckpointMarkThreadRoots callback created = 0xaaf36960
,I/art     ( 6384): CheckpointMarkThreadRoots callback created = 0xaaf36940
,W/AudioCapabilities( 6384): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6384): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6384): Unsupported mime audio/g726
,W/AudioCapabilities( 6384): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6384): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6384): Unsupported mime video/mjpg
,I/ActivityManager(  839): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6416 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/VideoCapabilities( 6384): Unsupported mime video/theora
,I/AppUp4:AppBoxCP( 6416): onCreate
,W/AudioCapabilities( 6384): Unsupported mime audio/evrc
W/AppUp4:DB( 6416):  [AppBoxDatabaseHelper] construct
W/AudioCapabilities( 6384): Unsupported mime audio/qcelp
W/VideoCapabilities( 6384): Unrecognized profile 2130706433 for video/avc
I/AppUp4:DB( 6416):  setFingerPrint start
I/AppUp4:DB( 6416):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
W/AudioCapabilities( 6384): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6384): Unsupported mime audio/qcelp
W/AudioCapabilities( 6384): Unsupported mime audio/evrc
I/AppUp4:DB( 6416):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6416):  SDK version = 0
I/AppUp4:DB( 6416):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6416): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6416): onReceive
,I/AppUp4:CustModeStarterReceiver( 6416): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6416): Context : android.app.ReceiverRestrictedContext@26270872
D/AppUp4:CustFacade( 6416): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6416): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6416): begin check event
I/AppUp4:CustModeStarterReceiver( 6416): Event For Nothing, skip.
I/ActivityManager(  839): Killing 5923:com.google.android.gm/u0a53 (adj 15): empty #11
W/VideoCapabilities( 6384): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6384): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6384): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6384): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6384): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6384): Unrecognized profile 2130706433 for video/avc
W/libprocessgroup(  839): failed to open /acct/uid_10053/pid_5923/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/ActivityManager(  839): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6437 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/vclib   ( 6384): onServiceConnected
W/Babel   ( 6384): Attempted to change video mute state without an active call.
,I/NotificationManager( 6384): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6384): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6384): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 6437): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6437): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6437): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
V/JNIHelp ( 6384): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppConfig( 6437): Total System Memory = 906309632
I/GalleryUtils( 6437): Application Heap = 96 MB
,I/AppConfig( 6437): App Tier : NOT_DEF
D/SystemHelper( 6437): region [EU], country [EU], operator [OPEN], sub-operator []
W/System  ( 6384): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6384): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6384): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager(  839): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6459 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  839): Killing 5880:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5764): android.os.DeadObjectException
,W/System.err( 5764): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5764): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5764): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5764): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5764): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5764): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5764): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5764): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5764): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5764): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5764): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5764): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5764): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5764): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5764): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5764): android.os.DeadObjectException
W/System.err( 5764): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5764): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5764): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5764): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5764): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5764): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5764): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5764): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5764): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5764): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5764): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5764): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5764): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5764): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5764): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  839): failed to open /acct/uid_10089/pid_5880/cgroup.procs: No such file or directory
,W/ActivityManager(  839): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
W/ResourcesManager( 6459): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6459): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  839): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6480 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6459): BUILD Country: EU
I/SystemConfig( 6459): BUILD Operator: OPEN
,D/UEI.SmartControl( 6480): Quickset Services start...
I/UEI.SmartControl( 6480): Manufacture = LGE
D/UEI.SmartControl( 6480): File observer start...
E/UEI.SmartControl( 6480): IR Port is disabled: false
D/UEI.SmartControl( 6480): Starting file observer...
D/UEI.SmartControl( 6480): Extracting JNI libs...
D/UEI.SmartControl( 6480): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6480): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6480): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6480): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6480): --- Selecting new region: 2
,I/UEI.SmartControl( 6480): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6480): Platform has CIR...
D/UEI.SmartControl( 6480): NO CIR support, need to check package...
I/UEI.SmartControl( 6480): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6480): QS Service created
I/ActivityManager(  839): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6501 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 5764:com.lge.qremote/u0a106 (adj 15): empty #11
,I/art     (  303): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 21.676ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 20.557ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.600ms
,W/libprocessgroup(  839): failed to open /acct/uid_10106/pid_5764/cgroup.procs: No such file or directory
,I/SystemConfig( 6459): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 6459): existFile = false
I/SystemConfig( 6459): canReadFile = false
I/SystemConfig( 6459): systemFeature RCS result false
D/SystemConfig( 6459): refreshRcsSupport() :false
E/UEI.SmartControl( 6480): QS start get config
,I/LockScreenSettings( 6501): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
D/LockScreenSettings( 6501): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6501): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6501): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6501): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6501): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,D/UEI.SmartControl( 6480): Loading JNI Libs...
,D/UEI.SmartControl( 6480):  configuring local db...
I/ActivityManager(  839): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6518 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  839): Killing 6164:com.google.android.gms:car/u0a6 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10006/pid_6164/cgroup.procs: No such file or directory
,W/ResourcesManager( 6518): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6480):  ---- Has DB8: true
,D/UEI.SmartControl( 6480): QS start statue = true Error code = 0
,D/UEI.SmartControl( 6480): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6480): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6480): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6480): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6480): IrrcClient ++ 
D/irrcClient( 6480): getIrrcService ++ 
,D/irrcClient( 6480): getIrrcService -- 
D/irrcClient( 6480): IrrcClient -- 
W/irrc_jni( 6480): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6480): Services init done
I/UEI.SmartControl( 6480): Device manager: loading config....
D/UEI.SmartControl( 6480): Config is loaded...
,D/UEI.SmartControl( 6480):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6480): Notify AllClients services are ready: 0
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/art     (  839): Explicit concurrent mark sweep GC freed 27343(1433KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 1.818ms total 149.170ms
,D/UEI.SmartControl( 6480): QS Service init finished
D/UEI.SmartControl( 6480): QS Service version name: 0.1.73
D/UEI.SmartControl( 6480): QS Service version code: 1073
D/UEI.SmartControl( 6480): Service requested: Control
D/UEI.SmartControl( 6480): Service.onUnbind: IControl
D/UEI.SmartControl( 6480): Service.onDestroy
,D/UEI.SmartControl( 6480): Shutdown IRRCPlayer... 
,W/irrc_jni( 6480): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6480): ~IrrcClient ++ 
D/irrcClient( 6480): ~IrrcClient -- 
W/irrc_jni( 6480): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6480): Blaster closed
D/UEI.SmartControl( 6480): Blaster closed
D/UEI.SmartControl( 6480): Shut down QS...
D/UEI.SmartControl( 6480): Stopped file observer...
,I/UEI.SmartControl( 6480): QS lib stop result = true
D/UEI.SmartControl( 6480): QS shutdown complete
D/UEI.SmartControl( 6480): QS Service created
E/UEI.SmartControl( 6480): QS start get config
,D/UEI.SmartControl( 6480):  configuring local db...
,I/UpdateIcingCorporaServi( 2025): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 4266): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4266): Null package name or gms related package.  Ignoreing.
I/Icing   ( 4266): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 2025): UpdateCorporaTask done [took 54 ms] updated apps [took 54 ms] 
D/UEI.SmartControl( 6480):  ---- Has DB8: true
D/UEI.SmartControl( 6480): QS start statue = true Error code = 0
,D/UEI.SmartControl( 6480): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 6480): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6480): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6480): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6480): IrrcClient ++ 
D/irrcClient( 6480): getIrrcService ++ 
D/irrcClient( 6480): getIrrcService -- 
D/irrcClient( 6480): IrrcClient -- 
W/irrc_jni( 6480): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6480): Services init done
I/UEI.SmartControl( 6480): Device manager: loading config....
D/UEI.SmartControl( 6480): QS Service init finished
D/UEI.SmartControl( 6480): QS Service version name: 0.1.73
D/UEI.SmartControl( 6480): QS Service version code: 1073
D/UEI.SmartControl( 6480): Config is loaded...
D/UEI.SmartControl( 6480): Service requested: Control
I/ActivityManager(  839): Killing 6330:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10038/pid_6330/cgroup.procs: No such file or directory
E/ActivityThread( 6480): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@19ed116c that was originally bound here
E/ActivityThread( 6480): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@19ed116c that was originally bound here
E/ActivityThread( 6480): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6480): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6480): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6480): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6480): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6480): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6480): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6480): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6480): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6480): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6480): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6480): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6480): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6480): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6480): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6480): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6480): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,D/UEI.SmartControl( 6480): Internal service binding...
,D/UEI.SmartControl( 6480):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6480): Notify AllClients services are ready: 0
,I/ThermalEngine(  289): Sensor:pa_therm0:33000 mC
,I/Icing   ( 4266): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4266): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  839): Killing 6259:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10006/pid_6259/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/CloudHub( 2097): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19955
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  839): Killing 2097:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  278): 2097 died, releasing its sessions
V/AudioFlinger(  278):  pid 1769 @ 0
V/AudioFlinger(  278):  pid 3114 @ 1
V/AudioFlinger(  278):  pid 3114 @ 2
,W/libprocessgroup(  839): failed to open /acct/uid_10028/pid_2097/cgroup.procs: No such file or directory
,E/UEI.SmartControl( 6480): file observer is disposed!
,D/charger_monitor(  472): init target 500000
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 304
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 304
,W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
D/charger_monitor(  472): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 304, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 6480): Internal timer expired: 2
,D/UEI.SmartControl( 6480): Service.onUnbind: IControl
D/UEI.SmartControl( 6480): Service.onDestroy
D/UEI.SmartControl( 6480): Shutdown IRRCPlayer... 
W/irrc_jni( 6480): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6480): ~IrrcClient ++ 
D/irrcClient( 6480): ~IrrcClient -- 
W/irrc_jni( 6480): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6480): Blaster closed
D/UEI.SmartControl( 6480): Blaster closed
D/UEI.SmartControl( 6480): Shut down QS...
I/UEI.SmartControl( 6480): QS lib stop result = true
D/UEI.SmartControl( 6480): QS shutdown complete
I/ThermalEngine(  289): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 132444955057; DSPS: 4438633; Offset : -3023565484
,I/ThermalEngine(  289): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{6e8db28 type 2 when 137493 com.google.android.gms} when 137493
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1739): Vacuum at: now=1457078783656 tag=VacuumService
I/ThermalEngine(  289): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  289): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  839): ALS enabled for SRE
D/PowerManagerServiceEx(  839): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26160 ms ago)
,D/qdlights(  839): set_light_backlight: 251
,D/qdlights(  839): set_light_backlight: 248
,D/qdlights(  839): set_light_backlight: 245
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/qdlights(  839): set_light_backlight: 242
D/qdlights(  839): set_light_backlight: 238
,D/qdlights(  839): set_light_backlight: 235
,D/qdlights(  839): set_light_backlight: 232
,D/qdlights(  839): set_light_backlight: 228
,D/qdlights(  839): set_light_backlight: 224
,D/qdlights(  839): set_light_backlight: 221
,D/qdlights(  839): set_light_backlight: 217
,D/qdlights(  839): set_light_backlight: 214
,D/qdlights(  839): set_light_backlight: 211
,D/qdlights(  839): set_light_backlight: 207
,D/qdlights(  839): set_light_backlight: 204
,D/qdlights(  839): set_light_backlight: 201
,D/qdlights(  839): set_light_backlight: 197
,D/qdlights(  839): set_light_backlight: 194
,D/qdlights(  839): set_light_backlight: 191
,D/qdlights(  839): set_light_backlight: 187
,D/qdlights(  839): set_light_backlight: 184
,D/qdlights(  839): set_light_backlight: 181
,D/qdlights(  839): set_light_backlight: 177
,D/qdlights(  839): set_light_backlight: 174
,D/qdlights(  839): set_light_backlight: 171
,D/qdlights(  839): set_light_backlight: 167
,D/qdlights(  839): set_light_backlight: 164
,D/qdlights(  839): set_light_backlight: 161
,D/qdlights(  839): set_light_backlight: 157
,D/qdlights(  839): set_light_backlight: 154
,D/qdlights(  839): set_light_backlight: 151
,D/qdlights(  839): set_light_backlight: 147
,D/qdlights(  839): set_light_backlight: 144
,D/qdlights(  839): set_light_backlight: 140
,D/qdlights(  839): set_light_backlight: 137
,D/qdlights(  839): set_light_backlight: 134
,D/qdlights(  839): set_light_backlight: 130
,D/qdlights(  839): set_light_backlight: 127
,D/qdlights(  839): set_light_backlight: 124
,D/qdlights(  839): set_light_backlight: 120
,D/qdlights(  839): set_light_backlight: 117
,D/qdlights(  839): set_light_backlight: 114
,D/qdlights(  839): set_light_backlight: 110
,D/qdlights(  839): set_light_backlight: 107
,D/qdlights(  839): set_light_backlight: 104
,D/qdlights(  839): set_light_backlight: 100
,D/qdlights(  839): set_light_backlight: 97
,D/qdlights(  839): set_light_backlight: 94
,D/qdlights(  839): set_light_backlight: 90
,D/qdlights(  839): set_light_backlight: 87
,D/qdlights(  839): set_light_backlight: 84
,D/qdlights(  839): set_light_backlight: 80
,D/qdlights(  839): set_light_backlight: 77
,D/qdlights(  839): set_light_backlight: 74
,D/qdlights(  839): set_light_backlight: 70
,D/qdlights(  839): set_light_backlight: 67
,D/qdlights(  839): set_light_backlight: 64
,D/qdlights(  839): set_light_backlight: 60
,D/qdlights(  839): set_light_backlight: 57
,D/qdlights(  839): set_light_backlight: 54
,D/qdlights(  839): set_light_backlight: 50
,D/qdlights(  839): set_light_backlight: 47
,D/qdlights(  839): set_light_backlight: 44
,D/qdlights(  839): set_light_backlight: 40
,D/qdlights(  839): set_light_backlight: 37
,D/qdlights(  839): set_light_backlight: 34
,D/qdlights(  839): set_light_backlight: 30
,D/qdlights(  839): set_light_backlight: 27
,D/qdlights(  839): set_light_backlight: 24
,D/qdlights(  839): set_light_backlight: 20
,D/qdlights(  839): set_light_backlight: 17
,D/qdlights(  839): set_light_backlight: 14
,D/qdlights(  839): set_light_backlight: 10
,I/ThermalEngine(  289): Sensor:pa_therm0:33000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 152446423709; DSPS: 5094041; Offset : -3023561702
,I/ThermalEngine(  289): Sensor:pa_therm0:33000 mC
,I/PowerManagerService(  839): ALS enabled for SRE
,D/PowerManagerServiceEx(  839): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33142 ms ago)
,I/PowerManagerService(  839): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  839): ALS enabled for SRE
D/PowerManagerServiceEx(  839): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33152 ms ago)
W/ContextImpl(  839): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  839): Sleeping (uid 1000)...
D/LPWGController(  839): [updateScreenState] screen on = false
D/LPWGController(  839): disable proximity sensor
D/LPWGController(  839): enable proximity sensor
I/SensorManager(  839): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@b152679] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  839): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  839): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  839): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  839): activate: handle is 48, enable
V/sensors_hal_Ctx(  839): activate sensors is 1400000000000
D/sensors_hal_Thresh(  839): enable: handle=48
I/sensors_hal_SAM(  839): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  839): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  839): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  839): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  839): enable: Received response: 0
D/PowerManagerServiceEx(  839): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33187 ms ago)
I/Adreno-EGL(  839): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  839): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  839): Build Date: 03/02/15 Mon
I/Adreno-EGL(  839): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  839): Remote Branch: 
I/Adreno-EGL(  839): Local Patches: 
I/Adreno-EGL(  839): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (134 us)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Sensors (  419): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  839): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  839): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  839): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  839): processInd: handle 48, count=1
V/sensors_hal_Thresh(  839): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  839): processInd : proximity state changed - FAR
,D/sensors_hal_Ctx(  839): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  839): poll: count: 256
I/sensors_hal_Ctx(  839): poll: released wakelock sensor_ind
D/sensors_hal_Util(  839): waitForResponse: timeout=0
D/LPWGController(  839): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  839): current mode = 1  value = 1 1
I/LPWGController(  839): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
,I/LPWGController(  839): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  839): set_light_backlight: 0
,I/SensorManager(  839): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  839): activate: handle is 46, disable
V/sensors_hal_Ctx(  839): activate sensors is 1000000000000
D/sensors_hal_LP2(  839): enable: handle=46
D/sensors_hal_LP2(  839): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  839): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
I/DisplayManagerService(  839): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  839): Display changed displayId=0
,V/sensors_hal_SAM(  839): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  839): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1769): Display #0 changed.
,D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  839): Excessive delay in setPowerMode(): 177ms
I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  839): Got set_interactive hint
,D/KeyguardViewMediator( 1371): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1330): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1330): notifyScreenOffLocked
D/SmartCoverViewMediator( 1330): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1371): notifyScreenOffLocked
,D/JX-Cordova( 4799): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4799): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4799): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cd713f7 added. We now have 3 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4799): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4799): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37b2f264 added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4799): addListener: New listener added - the number of listeners is now 1
D/BluetoothAdapterService(434966892)( 2077): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@8ee7222
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4799): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
D/KeyguardViewMediator( 1371): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,W/System.err( 4799): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
D/KeyguardViewMediator( 1371): handleNotifyScreenOff
W/System.err( 4799): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 4799): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4799): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4799): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4799): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4799): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4799): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4799): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4799): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4799): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4799): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4799): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4799): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ScreenTurnOffBySensor( 1371): unregisterProximitySensor
D/StatusBarWindowView( 1371): onScreenTurnedOff why = 3
,D/WifiServerServiceExt(  839): sendKtScanInterval  mRtspPlay : false
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=on, calling pid 839
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=on
V/voice   (  278): voice_set_parameters: enter: screen_state=on
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: exit
V/voice   (  278): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  278): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  278): platform_set_parameters: exit with code(0)
,V/lge_audio_loopback(  278): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  278): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  278): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.SCREEN_ON
I/WifiServerServiceExt(  839): set CMD_KT_SCAN_INTERVAL
I/Sensors (  419): sns_pwr.c(301):releasing wakelock
,D/GpsLocationProvider(  839): receive broadcast intent, action: android.intent.action.SCREEN_ON
,D/SplitWindow(  839): check instance of lgWin Window{e4e376c u0 SearchPanel}
,I/QCNEJ   ( 1908): |CORE| sendScreenState: state:true
I/LEDService( 1854): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1854): stopPatternFlashing()
D/qdlights( 1854): set_light_notifications: 0,0,0,0,3
I/LEDService( 1854): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1854): set_light_notifications: 0,0,0,0,3
I/LEDService( 1854): updateLightsLocked : turn off led
D/qdlights( 1854): set_light_notifications: 0,0,0,0,3
,D/LEDHandler( 1854): RESTART MSG
D/InputDispatcher(  839): Window went away: Window{1347bfcb u0 SearchPanel}
I/[SystemUI]Clock( 1371): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1371): time changed, timezoneChanged : false
,I/Cliptray Service( 1854): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1854): lockStatus = 0
D/LNfcService( 1823): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1823): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1823): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1823): isRequireNfcCRouting() return true
D/LNfcService( 1823): isHCERoutingtoHost() return : true
D/NfcService( 1823): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1823): mEnableLPD: true
D/NfcService( 1823): mEnableReader: false
D/NfcService( 1823): mEnableHostRouting: true
D/NfcService( 1823): newParams.techmask= mTechMask: default
D/NfcService( 1823): mEnableLPD: true
D/NfcService( 1823): mEnableReader: false
D/NfcService( 1823): mEnableHostRouting: true
D/NfcService( 1823): screenState= 3
D/NfcService( 1823): Discovery configuration equal, not updating.
,D/Ulp_jni (  839): JNI:system_update. Event-0
,V/PhoneApp( 1769): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2657): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 9:6:41
D/WeatherService( 2657): 2 : ACTION screen on
D/WeatherService( 2657): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2657): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherService( 2657): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 9:6:41
,W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): ACTION_SCREEN_ON
D/AppCleanupService( 4098): android.intent.action.SCREEN_ON
,V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=off, calling pid 839
D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=off
V/voice   (  278): voice_set_parameters: enter: screen_state=off
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: exit
V/voice   (  278): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  278): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: exit with code(0)
,V/lge_audio_loopback(  278): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  278): adev_set_parameters: exit with code(0)
,D/WifiController(  839): CMD_SCREEN_OFF 
D/WifiController(  839): shouldWifiStayAwake TRUE
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.SCREEN_OFF
D/GpsLocationProvider(  839): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1908): |CORE| sendScreenState: state:false
I/LEDService( 1854): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1854): stopPatternFlashing()
D/qdlights( 1854): set_light_notifications: 0,0,0,0,3
I/LEDService( 1854): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1854): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1854): clear
I/LEDService( 1854): updateLightsLocked : turn on led
I/Cliptray Service( 1854): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
E/LEDService( 1854): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1854): Can't handle this request of patternId:0
D/LEDHandler( 1854): RESTART MSG
D/LNfcService( 1823): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1823): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1947): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1769): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2657): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 9:6:41
,D/WeatherService( 2657): 2 : ACTION screen off
D/WeatherService( 2657): 2 : TimeTick Receiver Unregister
D/WeatherService( 2657): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 9:6:41
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  839): ACTION_SCREEN_OFF
D/AppCleanupService( 4098): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4098): AppUsageStatsSaveTask
,E/NxpNfcJni( 1823): getReconnectState = 0x0
,D/LCardEmulationManager( 1823): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1823): getDefaultRoute
D/LNfcService( 1823): isRequireNfcCRouting() return true
D/LNfcService( 1823): isHCERoutingtoHost() return : true
D/NfcService( 1823): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1823): mEnableLPD: true
D/NfcService( 1823): mEnableReader: false
D/NfcService( 1823): mEnableHostRouting: true
D/NfcService( 1823): newParams.techmask= mTechMask: 0
D/NfcService( 1823): mEnableLPD: true
D/NfcService( 1823): mEnableReader: false
D/NfcService( 1823): mEnableHostRouting: true
D/NfcService( 1823): screenState= 1
E/NxpNfcJni( 1823): getReconnectState = 0x0
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,D/KeyguardViewMediator( 1371): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{35b8b135 type 2 when 159004 com.android.systemui} when 159004
,D/PhoneUtils( 1769): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1769): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1769): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1769): getCallState : 0
,D/PhoneUtils( 1769): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1769): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1769): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1371): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1371): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 172448776730; DSPS: 5749478; Offset : -3023560148
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,D/PowerManagerServiceEx(  839): acquireWakeLockInternal: lock=61186011, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=839
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{299fc9ca type 2 when 185326 com.google.android.gms} when 185326
,D/PowerManagerServiceEx(  839): releaseWakeLockInternal: lock=61186011 [*alarm*], flags=0x0
I/PhenotypeConfigurator( 1739): Scheduling Phenotype for one-off execution 9605 seconds from now (1457078831664)
,I/PhenotypeFlagCommitter( 1739): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1739): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1739): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1739): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1739): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1739): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
,D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1739): propertyValue:false
D/libc-netbsd( 1739): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1739): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1739): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1739): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  472): init target 500000
D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 300, mChargingStatus=5, mChargingStop=false
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1739): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{1aa5d52b type 2 when 189047 android} when 189047
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 192450425249; DSPS: 6404893; Offset : -3023588637
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:32000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/ClearcutLoggerApiImpl( 1739): disconnect managed GoogleApiClient
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 212452123290; DSPS: 7060308; Offset : -3023568803
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 232454428551; DSPS: 7715745; Offset : -3023613605
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,D/charger_monitor(  472): init target 500000
,D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
,D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 296, mChargingStatus=5, mChargingStop=false
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  472): init target 500000
D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 252456549635; DSPS: 8371169; Offset : -3023445673
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 272458820890; DSPS: 9026607; Offset : -3023554762
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 292461221662; DSPS: 9682044; Offset : -3023503790
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  472): init target 500000
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
,D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 293, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 312463529792; DSPS: 10337476; Offset : -3023392875
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 326534855072; DSPS: 10798569; Offset : -3023509401
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 339666731213; DSPS: 11228876; Offset : -3023560672
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/LocationManagerService(  839): remove fcc8149
,D/LocationManagerService(  839): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  839): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  839): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  839): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  839): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  839): acquireWakeLockInternal: lock=61186011, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=839
,D/PowerManagerServiceEx(  839): releaseWakeLockInternal: lock=61186011 [*alarm*], flags=0x0
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 358421838458; DSPS: 11843443; Offset : -3023549967
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  472): init target 500000
D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 378424120377; DSPS: 12498879; Offset : -3023587357
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 393425589523; DSPS: 12990445; Offset : -3023521917
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 413427884096; DSPS: 13645885; Offset : -3023668723
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
,I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  839): battery changed pluggedType: 2
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
,I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 435932829427; DSPS: 14383328; Offset : -3023697912
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 458437579359; DSPS: 15120758; Offset : -3023525463
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 473439974543; DSPS: 15612369; Offset : -3023907455
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
,I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 488442316381; DSPS: 16103954; Offset : -3023549312
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 501575070344; DSPS: 16534284; Offset : -3023424744
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 514713715861; DSPS: 16964815; Offset : -3023542680
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 534100840403; DSPS: 17600093; Offset : -3023563639
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 549103278461; DSPS: 18091693; Offset : -3023567301
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 566606539033; DSPS: 18665234; Offset : -3023389005
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 589111917607; DSPS: 19402700; Offset : -3023686802
,I/ThermalEngine(  289): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 611616763074; DSPS: 20140130; Offset : -3023418974
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 626619029073; DSPS: 20631728; Offset : -3023533476
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 641620538368; DSPS: 21123301; Offset : -3023641456
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 659124100260; DSPS: 21696855; Offset : -3023558673
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 679126261613; DSPS: 22352281; Offset : -3023411403
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 694130886388; DSPS: 22843946; Offset : -3023211729
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 707749327357; DSPS: 23290207; Offset : -3023575663
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 721199283669; DSPS: 23730930; Offset : -3023417780
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 735270892063; DSPS: 24192034; Offset : -3023586886
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 756526031564; DSPS: 24888541; Offset : -3024154170
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 771530829428; DSPS: 25380197; Offset : -3023506673
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 790285381117; DSPS: 25994748; Offset : -3023563085
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 810287716876; DSPS: 26650184; Offset : -3023546741
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 830289996659; DSPS: 27305619; Offset : -3023555515
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 850292270264; DSPS: 27961053; Offset : -3023540341
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 870294617051; DSPS: 28616490; Offset : -3023543487
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 890296856800; DSPS: 29271923; Offset : -3023531625
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  839): acquireWakeLockInternal: lock=61186011, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=839
,V/AlarmManager(  839): RTC_WAKEUP set : Alarm{29d10d88 type 0 when 1457079554354 com.google.android.gms} when 1457079554354
I/ActivityManager(  839): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6844 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/EventLogService( 4266): Aggregate from 1457078756158 (log), 1457077754262 (data)
,I/DigitalAppWidgetProvider( 6844): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6844): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@26270872
D/PowerManagerServiceEx(  839): releaseWakeLockInternal: lock=61186011 [*alarm*], flags=0x0
I/ActivityManager(  839): Killing 6416:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  839): failed to open /acct/uid_10011/pid_6416/cgroup.procs: No such file or directory
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 910299205360; DSPS: 29927361; Offset : -3023563384
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 930301741026; DSPS: 30582803; Offset : -3023530211
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,V/AlarmManager(  839): ELAPSED_WAKEUP set : Alarm{2ad1105d type 2 when 949676 com.android.bluetooth} when 949676
,W/bt-smp  ( 2077): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2077): Plain text(LSB ~ MSB) = 1e 01 43 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 2077): Encrypted text(LSB ~ MSB) = 3f 54 d4 1b 5f 88 7d df 1d 39 f3 8d f9 30 59 4a 
W/bt-btm  ( 2077): Stopping oneshot timer
D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 950303208572; DSPS: 31238212; Offset : -3023558079
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
,I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 970305485462; DSPS: 31893646; Offset : -3023539411
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 990307781792; DSPS: 32549082; Offset : -3023562365
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1010310362222; DSPS: 33204525; Offset : -3023514531
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1030312651634; DSPS: 33859961; Offset : -3023544817
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1050314938193; DSPS: 34515396; Offset : -3023547078
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1070317222976; DSPS: 35170833; Offset : -3023612043
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1085319457705; DSPS: 35662419; Offset : -3023393324
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1099391100737; DSPS: 36123527; Offset : -3023647987
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1114393397795; DSPS: 36615120; Offset : -3023578686
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1129395692879; DSPS: 37106708; Offset : -3023358825
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:28000 mC
,D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  839): battery changed pluggedType: 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1143474884267; DSPS: 37568062; Offset : -3023574173
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1158477054630; DSPS: 38059654; Offset : -3023601024
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1173488622999; DSPS: 38551541; Offset : -3023232737
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1187560689272; DSPS: 39012675; Offset : -3023859047
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1204445953348; DSPS: 39565959; Offset : -3023482902
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,I/UsageStatsService(  839): User[0] Flushing usage stats to disk
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1224448276729; DSPS: 40221398; Offset : -3023570409
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1244450655809; DSPS: 40876835; Offset : -3023541132
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1264453182214; DSPS: 41532277; Offset : -3023517167
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1854): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  472): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2077): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/QCNEJ   ( 1908): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1908): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1854): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1854): Battery Level Remaining: 100%
D/LEDHandler( 1854): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  839): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  839): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  839): battery changed pluggedType: 2
I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  839): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  839): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  839): tsOffsetIs: Apps: 1279455476489; DSPS: 42023872; Offset : -3023511738
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  289): Sensor:pa_therm0:27000 mC
,TIME-OUT KILL (timeout was 1200000ms)
```
