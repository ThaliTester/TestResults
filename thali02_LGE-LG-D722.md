#### Test 6177688874f8189_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
,I/MusicStore( 4787): Database version: 120
--------- beginning of system
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4787): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4787): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4787): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 4787): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4787): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 4787): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/AndroidRuntime( 4817): 
D/AndroidRuntime( 4817): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4817): CheckJNI is OFF
W/ActivityThread( 4787): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4787): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@21fb7031: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4787): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4787): GMSCore installation verified
I/ConfigStore( 4787): Config Database version: 1
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/MediaRouter( 4787): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/MusicLeanback( 4787): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 4787): type=WIFI subType= reason=null isConnected=true
I/NetworkMonitor( 4787): type=WIFI subType= reason=null isConnected=true
D/AndroidRuntime( 4817): Calling main entry com.android.commands.am.Am
I/ActivityManager(  916): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=4841 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  916): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  916): setTaskToReturnTo : TaskRecord{f3d8d11 #224 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  916): setTaskToReturnTo : TaskRecord{f3d8d11 #224 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  916): AppWindowTokenEx init.. 
D/ContextHelper(  916): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
D/InputDispatcher(  916): Focus left window: Window{ba79c6e u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 4817): Shutting down VM
I/PhoneWindow(  916): [generateLayout] setColorNavigationBar => color=0x ff000001
I/[LGHome]EVENT( 1875): [Launcher.java:986:onPause()]onPause
D/PhoneWindowEx(  916): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  916): [setNavigationBarColor2] color=0x fff5f5f5
D/SplitWindow(  916): check instance of lgWin Window{492e87c u0 Starting com.test.thalitest}
I/ActivityManager(  916): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4861 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1875): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/GHttpClientFactory( 4787): Using our fixed implementation of GMSCore's GoogleHttpClient
I/[LGHome]EVENT( 1875): [Launcher.java:5214:onStop()]onStop
W/ActivityThread( 1875): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1875): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1875): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3407)
W/ActivityThread( 1875): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3496)
W/ActivityThread( 1875): 	at android.app.ActivityThread.access$1100(ActivityThread.java:155)
W/ActivityThread( 1875): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1352)
W/ActivityThread( 1875): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 1875): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 1875): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/ActivityThread( 1875): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 1875): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 1875): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/ActivityThread( 1875): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/WindowStateAnimator(  916): Starting window displayed
W/ResourcesManager( 4841): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4841): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4841): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/WindowManager(  916): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/SystemUI[Framework](  916): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
I/[SystemUI]NavigationThemeResource( 1370): notify navigation bar color(0xfff5f5f5)
I/GoogleURLConnFactory( 4787): Using platform SSLCertificateSocketFactory
I/[SystemUI]NavigationThemeResource( 1370): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1370):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1370): , Keyguard show=false, IME shown=false, Panel expanded=false
W/PhoneWindowManagerEx(  916): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  916): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  916): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  916): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@dec02cd,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  916): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/HotwordDetector( 1945): Closing mic
,I/ActivityManager(  916): Activity reported stop, but no longer stopping: ActivityRecord{149f0f50 u0 com.lge.launcher2/.Launcher t223}
I/ActivityManager(  916): Killing 4599:com.lge.qmemoplus/1000 (adj 15): empty #11
,I/MicrophoneInputStream( 1945): mic_close com.google.android.apps.gsa.speech.audio.u@35896dbd
V/AudioRecord( 1945): stop()
D/AudioRecord( 1945): AudioRecord->stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioFlinger(  279): Record stopped OK
V/AudioPolicyManager(  279): stopInput() input 17
V/AudioPolicyService(  279): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  279): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch handle 18
,V/AudioFlinger::PatchPanel(  279): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  279): ThreadBase::setParameters() routing=0
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb3851000
D/audio_hw_primary(  279): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
W/libprocessgroup(  916): failed to open /acct/uid_1000/pid_4599/cgroup.procs: No such file or directory
,I/NotificationManager( 4787): com.google.android.music: cancel(1061) by com.google.android.music
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
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyManager(  279): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  279): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  279): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  279): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
,V/AudioPolicyService(  279): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
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
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb3851000
,V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
D/ContextHelper( 4861): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
V/AudioRecord( 1945): stop()
V/AudioRecord( 1945): stop()
V/AudioRecord( 1945): stop()
,V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioPolicyManager(  279): releaseInput() 17
V/AudioPolicyManager(  279): closeInput(17)
V/AudioFlinger(  279): releasing 16 from 1945 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/AudioFlinger(  279): closeInput() 17
V/AudioSystem(  279): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1370): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1945): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): ThreadBase::exit
V/AudioSystem( 2715): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioSystem(  916): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1749): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): RecordThread 0xb3851000 exiting
V/AudioSystem( 2055): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3158): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  279): adev_close_input_stream: enter:stream_handle(0xb546e1a0)
D/audio_hw_primary(  279): in_standby: enter: stream (0xb546e1a0) usecase(7: audio-record)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioPolicyService(  279): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  279): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyManager(  279): releaseInput() exit
V/AudioFlinger(  279): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  279): removeClient_l() pid 1945, calling pid 279
I/HotwordRecognitionRnr( 1945): Hotword detection finished
,I/HotwordRecognitionRnr( 1945): Stopping hotword detection.
I/WebViewFactory( 4861): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4861): Time to load native libraries: 2 ms (timestamps 9912-9914)
,I/LibraryLoader( 4861): Expected native library version number "",actual native library version number ""
I/LGEmail ( 4841): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,V/WebViewChromiumFactoryProvider( 4861): Binding Chromium to main looper Looper (main, tid 1) {33a6af85}
,D/LGEmail ( 4841): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/LibraryLoader( 4861): Expected native library version number "",actual native library version number ""
I/chromium( 4861): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4861): Initializing chromium process, singleProcess=true
W/art     ( 4861): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4861): ApplicationContext is null in ApplicationStatus
W/chromium( 4861): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4861): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4861): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4861): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4861): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4861): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4861): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4861): Remote Branch: 
I/Adreno-EGL( 4861): Local Patches: 
I/Adreno-EGL( 4861): Reconstruct Branch: 
,V/AudioPolicyService(  279): registerClient() client 0xb551c6e0, uid 10316
,D/BluetoothManagerService(  916): Message: 20
D/BluetoothManagerService(  916): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6a454dc:true
D/BluetoothAdapterService(146074856)( 2055): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a0a6f7e
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/eas_req ( 4841): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 4625): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4625): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4625): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4625): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 4625): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/HubEmail( 4841): JNI_OnLoad()
I/HubEmail( 4841): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4841): registerNatives()
I/HubEmail( 4841): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4841): registerNativeMethods()
I/HubEmail( 4841): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 4841): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/LGDMClient( 4625): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4625): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4625): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/ActivityManager(  916): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=4914 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/Settings( 4841): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ContextImpl( 4625): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4625): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 4625): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 4625): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 4625): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 4625): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
W/art     ( 4861): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4861): onDetachedFromWindow called when already detached. Ignoring
,I/PhoneWindow( 4861): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 4861): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 4861): [setNavigationBarColor2] color=0x fff5f5f5
D/SystemWebViewEngine( 4861): CordovaWebView is running on device made by: LGE
,I/AppUp4:AppBoxCP( 4914): onCreate
W/art     ( 4861): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4861): Attempt to remove local handle scope entry from IRT, ignoring
W/AppUp4:DB( 4914):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 4914):  setFingerPrint start
I/AppUp4:DB( 4914):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 4914):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4914):  SDK version = 0
,I/AppUp4:DB( 4914):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 4914): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 4914): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4914): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4914): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 4914): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 4914): onReceive
I/AppUp4:CustModeStarterReceiver( 4914): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 4914): Context : android.app.ReceiverRestrictedContext@33a6af85
D/AppUp4:CustFacade( 4914): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4914): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 4914): begin check event
I/AppUp4:CustModeStarterReceiver( 4914): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4914): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4914): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 4914): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 4914): handleAsyncCustNotification do not startCustService
I/ActivityManager(  916): Killing 3342:com.android.defcontainer/u0a4 (adj 15): empty #11
I/Activity( 4861): Activity.onPostResume() called 
,D/OpenGLRenderer( 4861): Render dirty regions requested: true
I/OpenGLRenderer( 4861): Initialized EGL, version 1.4
D/OpenGLRenderer( 4861): Enabling debug mode 0
,D/Atlas   ( 4861): Validating map...
,D/SplitWindow(  916): check instance of lgWin Window{396191a4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/libprocessgroup(  916): failed to open /acct/uid_10004/pid_3342/cgroup.procs: No such file or directory
,W/chromium( 4861): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/ActivityManager(  916): Killing 4764:com.lge.bnr/1000 (adj 15): empty #11
I/LgeMiscReceiver( 3158): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3158): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3158): networkInfo.isConnected() = true
W/libprocessgroup(  916): failed to open /acct/uid_1000/pid_4764/cgroup.procs: No such file or directory
D/PhoneState( 3158): setPdpRejectCasuse : false
D/InputDispatcher(  916): Focus entered window: Window{396191a4 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/ActivityManager(  916): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=4943 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  916): Displayed com.test.thalitest/.MainActivity: +1s194ms
I/Timeline(  916): Timeline: Activity_windows_visible id: ActivityRecord{2a566e76 u0 com.test.thalitest/.MainActivity t224} time:70689
W/InputMethodManagerService(  916): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/Timeline( 4861): Timeline: Activity_idle id: android.os.BinderProxy@176b8d7 time:70718
,W/BindingManager( 4861): Cannot call determinedVisibility() - never saw a connection for the pid: 4861
,D/PhoneMonitor( 4943): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 4943): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4943): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  916): Killing 4702:com.android.settings/1000 (adj 15): empty #11
D/JsMessageQueue( 4861): Set native->JS mode to OnlineEventsBridgeMode
,W/libprocessgroup(  916): failed to open /acct/uid_1000/pid_4702/cgroup.procs: No such file or directory
,V/DownloadManager( 3199): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3199): DownloadService onCreate
I/DownloadManager( 3199): in removeSpuriousFiles
I/NotificationManager( 3199): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3199): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@a46e53a on behalf of 3199
I/DownloadManager( 3199): in trimDatabase
V/DownloadManager( 3199): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@3388ff48 on behalf of 3199
D/PhoneMonitor( 4943): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 4943): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 4943): [parse] Load xml
I/ActivityManager(  916): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4978 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3199): DownloadService onStartCommand
V/TelephonyAutoProfiling( 4943): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 4943): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
V/DownloadManager( 3199): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@3c2e1b06 on behalf of 3199
I/CheckinService( 4344): Checkin interval check for package: unspecified last checkin: 1457103966949 min interval config: 0 actual interval: 26185905
,I/CheckinService( 4344): Checking schedule, now: 1457130152871 next: 1457103996919
I/CheckinService( 4344): active receiver: enabled
D/PhoneMonitor( 4943): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/CheckinService( 4344): Preparing to send checkin request
I/EventLogService( 4344): Accumulating logs since 1457129177846
V/DownloadManager( 3199): DownloadService onDestroy
,D/DrmBroadcastReceiver( 4978): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 4978): 1  network is available. Sync DRM Time with NTP
,V/DrmService( 4978): Service onCreate
D/DrmService( 4978): Received new request = 2
D/WeatherAncestor( 2698): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:22:32
D/UpdateThreadPoolManager( 2698): 2 : This is isUpdating : false
D/WeatherAncestor( 2698): connectivity changed - connection : true
,I/DrmSntpClient( 4978): Start Sync process
D/DrmSntpClient( 4978): Server : 0
D/libc-netbsd( 4978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4978): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4978): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/Weather_cast( 2698): 2 : isUpdateNeedForAlarm : no city return false
E/BandwidthController(  274): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  274): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
,D/WeatherAncestor( 2698): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 23:22:32
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/WeatherService( 2698): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/ActivityManager(  916): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5000 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  916): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2698): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2698): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2698): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 5000): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 4344): Checkin reason type: 8 attempt count: 1
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 4978): propertyValue:false
E/ActivityThread( 4344): Failed to find provider info for com.google.android.wearable.settings
,I/LGDrmClient( 4978): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  286): eDRM_SetDRMTime +++
I/LGDRM   (  286): [DRM] SET TIME : YR=2016, MON=3, DAY=4
I/LGDRM   (  286): [DRM] SET TIME : HR=22, MIN=22, SEC=33
V/ILGDrmService(  286): eDRM_SetDRMTime ---
,I/DrmSntpClient( 4978): Synched
D/DrmService( 4978): Completed !! request = 2
D/DrmService( 4978): Request count = 0
V/DrmService( 4978): Service onDestroy
D/jxcore_app_log( 4861): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426410880
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4861): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4861):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4861):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4861):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4861):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4861): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28ccd1e1 added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4861): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4861):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4861):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4861):     - Bluetooth MAC address: F8:95:C7:87:85:54
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4861):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4861):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4861):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4861):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4861):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4861):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4861): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24d2c7f4 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4861): addListener: New listener added - the number of listeners is now 1
D/BluetoothAdapterService(146074856)( 2055): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a0a6f7e
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4861): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4861): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4861): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4861): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4861): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4861): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4861): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4861): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4861): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4861): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4861): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4861): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4861): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4861): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4861): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/JX-Cordova( 4861): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4861): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4861): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@163ab1d added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4861): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4861): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b00e192 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4861): addListener: New listener added - the number of listeners is now 1
,D/BluetoothAdapterService(146074856)( 2055): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a0a6f7e
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4861): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4861): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4861): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4861): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4861): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4861): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4861): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4861): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4861): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4861): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4861): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4861): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4861): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4861): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4861): 	at android.os.HandlerThread.run(HandlerThread.java:61)
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/Babel_SMS( 5000): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5000): MmsConfig.loadMmsSettings
I/Babel_SMS( 5000): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5000): MmsConfig.loadFromDatabase
D/UEI.SmartControl( 4671): Internal timer expired: 1
,E/Babel_SMS( 5000): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5000): MmsConfig.loadFromResources
E/Babel_SMS( 5000): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5000): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5000): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5000): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5000): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5000): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5000): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5000): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5000): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5000): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5000): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5000): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5000): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5000): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5000): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5000): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5000): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5000): found sensor: Motion Accel, handle=46
,W/Settings( 5000): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5000): startup - clean
I/art     ( 5000): CheckpointMarkThreadRoots callback created = 0xb042d8c0
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
I/Babel   ( 5000): deleted: false for 0
,I/art     ( 5000): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,I/ActivityManager(  916): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5034 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  916): Waited long enough for: ServiceRecord{3476cbd7 u0 com.lge.springcleaning/.service.AppCleanupService}
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/AudioCapabilities( 5000): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5000): Unsupported mime audio/adpcm
W/AudioCapabilities( 5000): Unsupported mime audio/g726
W/AudioCapabilities( 5000): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5000): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5000): Unsupported mime video/mjpg
,W/VideoCapabilities( 5000): Unsupported mime video/theora
,W/AudioCapabilities( 5000): Unsupported mime audio/evrc
,W/AudioCapabilities( 5000): Unsupported mime audio/qcelp
W/VideoCapabilities( 5000): Unrecognized profile 2130706433 for video/avc
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/AudioCapabilities( 5000): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5000): Unsupported mime audio/qcelp
W/AudioCapabilities( 5000): Unsupported mime audio/evrc
W/VideoCapabilities( 5000): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5000): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5000): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5000): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5000): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5000): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 5000): onServiceConnected
W/Babel   ( 5000): Attempted to change video mute state without an active call.
,I/NotificationManager( 5000): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5000): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5000): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 5000): propertyValue:false
I/ActivityManager(  916): Process com.google.android.music:main (pid 4787) has died
,I/Babel   ( 5000): connection state changed from UNKNOWN to CONNECTED
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5034): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5034): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5034): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5034): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/GAv4    ( 5034): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5034):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5034):   adb logcat -s GAv4
W/GAv4    ( 5034): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5034): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5034): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 72595236696; DSPS: 2477236; Offset : -3015370216
,I/NotificationManager(  916): android: cancelAsUser(2) by android
I/art     (  916): Explicit concurrent mark sweep GC freed 28379(1474KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 3.310ms total 171.206ms
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  916): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5076 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.265ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.301ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 303us total 21.182ms
,W/ResourcesManager( 5076): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5076): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/WebViewFactory( 5034): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5034): Time to load native libraries: 2 ms (timestamps 2918-2920)
I/LibraryLoader( 5034): Expected native library version number "",actual native library version number ""
,I/MultiDex( 5076): VM with version 2.1.0 has multidex support
I/MultiDex( 5076): install
I/MultiDex( 5076): VM has multidex support, MultiDex support library is disabled.
V/WebViewChromiumFactoryProvider( 5034): Binding Chromium to main looper Looper (main, tid 1) {25cce18e}
I/LibraryLoader( 5034): Expected native library version number "",actual native library version number ""
I/chromium( 5034): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5034): Initializing chromium process, singleProcess=true
,W/art     ( 5034): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5034): ApplicationContext is null in ApplicationStatus
V/JNIHelp ( 5076): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/chromium( 5034): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5034): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5034): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5034): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5034): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5034): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5034): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5034): Remote Branch: 
I/Adreno-EGL( 5034): Local Patches: 
I/Adreno-EGL( 5034): Reconstruct Branch: 
,W/ActivityThread( 5076): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5076): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@26c784de: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5076): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  916): Process com.lge.qremote (pid 4648) has died
,D/UEI.SmartControl( 4671): Service.onUnbind: IControl
D/UEI.SmartControl( 4671): Service.onDestroy
I/NotificationManager( 5076): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5076): com.google.android.gms: cancel(39789) by com.google.android.gms
D/UEI.SmartControl( 4671): Shutdown IRRCPlayer... 
W/irrc_jni( 4671): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 4671): ~IrrcClient ++ 
D/irrcClient( 4671): ~IrrcClient -- 
W/irrc_jni( 4671): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 4671): Blaster closed
D/UEI.SmartControl( 4671): Blaster closed
D/UEI.SmartControl( 4671): Shut down QS...
D/UEI.SmartControl( 4671): Stopped file observer...
,I/UEI.SmartControl( 4671): QS lib stop result = true
D/UEI.SmartControl( 4671): QS shutdown complete
,I/NSApplication( 5034): Starting up...,
,I/art     ( 5076): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 5076): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 4060): Explicit concurrent mark sweep GC freed 2709(108KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 3.541ms total 30.244ms
V/AudioPolicyService(  279): registerClient() client 0xb551c800, uid 10079
,W/AudioManagerAndroid( 5034): Requires BLUETOOTH permission
,I/ActivityManager(  916): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5123 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NativeLibraryUtils( 5076): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): CdmEngine::OpenSession
I/WVCdm   (  279): Level3 Library Dec 11 2014 16:13:16
I/GoogleURLConnFactory( 5076): Using platform SSLCertificateSocketFactory
,W/WVCdm   (  279): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  279): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  279): L1 library not specified. Falling Back to L3
D/libc-netbsd( 5076): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5076): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5076): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5076): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 5076): propertyValue:false
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/WVCdm   (  279): PrepareKeyRequest: nonce=1681423339
I/ActivityManager(  916): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5147 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  916): Killing 4671:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
D/libc-netbsd( 5076): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5076): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5076): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5076): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/libprocessgroup(  916): failed to open /acct/uid_10089/pid_4671/cgroup.procs: No such file or directory
,I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QPairHandler( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]QSlideListController( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1370): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/InputReader(  916): Reconfiguring input devices.  changes=0x00000010
W/ResourcesManager( 5147): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/art     ( 1785): CheckpointMarkThreadRoots callback created = 0xaaf21b60
,D/administrator(  916): Handling package changes for user 0
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/art     ( 1785): CheckpointMarkThreadRoots callback created = 0xb042d650
,W/ResourcesManager(  916): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/NotificationService(  916): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  916): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  916): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  916): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourceType(  916): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
V/BackupManagerService(  916): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  916): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@79ae433
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/art     ( 5076): CheckpointMarkThreadRoots callback created = 0xb042dc70
,I/GCoreNlp( 1730): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/art     ( 5076): CheckpointMarkThreadRoots callback created = 0xaae47e20
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
I/ActivityManager(  916): Process com.lge.email (pid 4841) has died
,D/LocationProviderProxy(  916): applying state to connected service
,D/NetworkLogImpl( 4344): Loaded NetworkSpeedPredictor
I/iu.Environment( 4344): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.SyncManager( 4344): SYNC; picasa accounts
I/iu.UploadsManager( 4344): num queued entries: 0
I/iu.UploadsManager( 4344): num updated entries: 0
,I/iu.SyncManager( 4344): NEXT; no task
I/ActivityManager(  916): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=5177 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/dex2oat ( 5184): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=37 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,W/ActivityManager(  916): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager(  916): RTC_WAKEUP set : Alarm{17b1fcaa type 0 when 1456784515281 com.android.providers.contacts} when 1456784515281
,V/AlarmManager(  916): ELAPSED_WAKEUP set : Alarm{2740909b type 2 when 58697 com.google.android.talk} when 58697
V/AlarmManager(  916): RTC_WAKEUP set : Alarm{3c6aa411 type 0 when 1457130156472 com.google.android.googlequicksearchbox} when 1457130156472
I/dex2oat ( 5184): dex2oat took 135.839ms (threads: 4)
,I/Adreno-EGL( 5076): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5076): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5076): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5076): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5076): Remote Branch: 
I/Adreno-EGL( 5076): Local Patches: 
I/Adreno-EGL( 5076): Reconstruct Branch: 
,I/DigitalAppWidgetProvider( 5177): onReceive: android.intent.action.ALARM_CHANGED
,I/ActivityManager(  916): Killing 4731:com.lge.sync/1000 (adj 15): empty #11
D/WeatherAncestor( 2698): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 23:22:36
W/libprocessgroup(  916): failed to open /acct/uid_1000/pid_4731/cgroup.procs: No such file or directory
,D/UpdateThreadPoolManager( 2698): 2 : This is isUpdating : false
D/Weather_cast( 2698): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2698): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 23:22:36
D/WeatherService( 2698): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
I/NotificationManager(  916): android: cancelAsUser(2) by android
,I/Adreno-EGL( 5076): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5076): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5076): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5076): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5076): Remote Branch: 
I/Adreno-EGL( 5076): Local Patches: 
I/Adreno-EGL( 5076): Reconstruct Branch: 
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  916): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5206 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
W/ActivityManager(  916): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2698): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2698): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2698): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 5206): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/Adreno-EGL( 5076): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5076): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5076): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5076): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5076): Remote Branch: 
I/Adreno-EGL( 5076): Local Patches: 
I/Adreno-EGL( 5076): Reconstruct Branch: 
,D/BluetoothManagerService(  916): Message: 20
,D/BluetoothManagerService(  916): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5367813:true
D/BluetoothAdapterService(146074856)( 2055): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a0a6f7e
D/BluetoothAdapterService(146074856)( 2055): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a0a6f7e
I/[LGHome]LGNumberBadgeReceiver( 1875): [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = lge.intent.action.UNREAD_MESSAGES
,V/SmsReceiverService( 3158): onStart: #1 mResultCode: -1 = Activity.RESULT_OK
D/MmsConfig( 3158): isNotAllowedSms: currentUser:0
D/MmsConfig( 3158): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3158): isUserMode:false
D/SmsReceiverService( 3158): handleMessage isUserMode:false
V/SmsReceiverService( 3158): handleMessage action: com.android.mms.transaction.SEND_MESSAGE error: 0
,D/SmsReceiverService( 3158): [LGE] handleSendMessage Send messages in queue
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1875): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1875): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1875): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1875): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
I/ActivityManager(  916): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=5227 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/ResourcesManager( 5227): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5227): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5227): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5227): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5227): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/IndexDatabaseHelper( 5227): Using schema version: 115
,I/IndexDatabaseHelper( 5227): Index is fine
I/CheckinRequestBuilder( 4344): Classify the device as Phone.
D/UsbSettingsReceiver( 5227): [AUTORUN] onReceive() : action = android.hardware.usb.action.USB_STATE
D/UsbSettingsReceiver( 5227): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5227): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5227): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 5227): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/WVCdm   (  279): CdmEngine::CloseSession
I/WVCdm   (  279): L3 Terminate.
D/UsbSettingsReceiver( 5227): [AUTORUN] onReceive() : getDefaultFunction = ptp_only
D/UsbSettingsReceiver( 5227): [AUTORUN] onReceive() : USB_FUNCTION_CDROM_STORAGE = false
D/UsbSettingsReceiver( 5227): [AUTORUN] onReceive() : mDirectAutorun = true
D/UsbSettingsReceiver( 5227): [AUTORUN] onReceive() : mActivityUsbModeChange = false
D/UsbSettingsReceiver( 5227): [AUTORUN] onReceive() : mActivityFinish = false
D/UsbSettingsReceiver( 5227): [AUTORUN] onReceive() : ===== USB Configured =====
,D/UsbSettingsControl( 5227): [AUTORUN] setUsbConnected() : connected=true
D/UsbSettingsReceiver( 5227): [AUTORUN] onReceive() : checkQmicm = ptp_only,adb
D/UsbSettingsReceiver( 5227): [AUTORUN] : topPackageName=com.test.thalitest
D/UsbSettingsReceiver( 5227): [AUTORUN] : topClassName=com.test.thalitest.MainActivity
,D/UsbSettingsReceiver( 5227): [AUTORUN] Not exist com.android.LGSetupWizard
D/UsbSettingsReceiver( 5227): [AUTORUN] setUsbConnect() : mUsbSettingsRun = false
D/UsbSettingsReceiver( 5227): [AUTORUN] startUsbSettings() : deviceProvisioned=1
I/ActivityManager(  916): Killing 4625:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  916): failed to open /acct/uid_1000/pid_4625/cgroup.procs: No such file or directory
,I/ActivityManager(  916): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5252 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/MtpService( 3199): updating state; isCurrentUser=true, mMtpLocked=false
,D/libc-netbsd( 4344): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4344): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4344): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4344): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 4344): propertyValue:false
,I/PCSuite ( 5252): [StartReceiver]USB CONNECTED ver UsbManger : ptp_only
I/PCSuite ( 5252): [StartReceiver]isUsbPCSuiteMode : false
,D/PCSuite ( 5252): [StartReceiver][checkEUTStatus] eutStatus = 
D/PCSuite ( 5252): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5252): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  916): Killing 4914:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/libc-netbsd( 4344): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4344): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/libprocessgroup(  916): failed to open /acct/uid_10011/pid_4914/cgroup.procs: No such file or directory
,V/LGMDMManager( 5206): Create singleton instance
,D/libc-netbsd( 4344): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4344): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4344): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4344): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4344): Sending checkin request (7895 bytes)
,I/DigitalAppWidgetProvider( 5177): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 2698): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 23:22:37
D/UpdateThreadPoolManager( 2698): 2 : This is isUpdating : false
D/Weather_cast( 2698): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2698): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 23:22:37
D/WeatherService( 2698): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
W/ActivityManager(  916): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2698): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2698): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2698): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/AlertReceiver( 3882): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
D/AlertService( 3882): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 3882): [updateWidgets] 
,D/MonthWidgetProvider( 3882): [onReceive]
D/CalendarWidgetProvider( 3882): [onReceive]
D/CalendarWidgetProvider( 3882): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 3882): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 3882): [onReceive]
D/CalendarWidgetProvider( 3882): [onReceive]
D/CalendarWidgetProvider( 3882): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 3882): [onCreate] mContext.getPackageName() = com.android.calendar
,D/CalendarWeatherReceiver( 3882): Get action=com.lge.calendar.action.WEATHER_SERVICE_START
I/[SystemUI]SafeModeBroadcastReceiver( 1370): onReceive = com.lge.statusbar.bootcompleted
,I/ActivityManager(  916): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.MediaScanReceiver: pid=5275 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/chromium( 4861): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 4861): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,V/AlarmManager(  916): ELAPSED_WAKEUP set : Alarm{a2bb381 type 2 when 76355 android} when 76355
,E/MediaScanReceiver( 5275): media scanning start or checking
W/MainApplication( 5275): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ActivityManager(  916): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5292 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  916): Killing 4943:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  916): failed to open /acct/uid_10038/pid_4943/cgroup.procs: No such file or directory
,I/MusicStore( 5292): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5292): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/CheckinRequestBuilder( 4344): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4344): Failed to find provider info for com.google.android.wearable.settings
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5292): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5292): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,W/ResourcesManager( 5292): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5292): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5292): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5292): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5292): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@21fb7031: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5292): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5292): GMSCore installation verified
,I/art     (  916): Explicit concurrent mark sweep GC freed 25872(1357KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.521ms total 162.311ms
I/ConfigStore( 5292): Config Database version: 1
,I/CheckinRequestBuilder( 4344): Classify the device as Phone.
,I/CheckinTask( 4344): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4344): Checking schedule, now: 1457130158904 next: 1457657407898
I/CheckinService( 4344): active receiver: disabled
,D/CheckinService( 4344): Recording last checkin time for package unspecified as 1457130158940
I/MediaRouter( 5292): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 5292): type=WIFI subType= reason=null isConnected=true
D/ToneMappingReceiver( 5177): Enter doAlarmRingToneUriMapping()
,D/ToneMappingReceiver( 5177): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5177): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
I/ActivityManager(  916): Killing 4978:com.lge.drmservice/u0a51 (adj 15): empty #11
,D/CommonUtil( 5177): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5177): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5177): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5177): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5177): Alarm Success count is 0
D/ToneMappingReceiver( 5177): Timer Success count is 0
I/ActivityManager(  916): Killing 5000:com.google.android.talk/u0a61 (adj 15): empty #11
,I/NetworkMonitor( 5292): type=WIFI subType= reason=null isConnected=true
W/libprocessgroup(  916): failed to open /acct/uid_10051/pid_4978/cgroup.procs: No such file or directory
,I/MediaScannerReceiver( 3882): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///system/media
I/InitNotificationRingtoneService( 3882): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3882): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
W/libprocessgroup(  916): failed to open /acct/uid_10061/pid_5000/cgroup.procs: No such file or directory
E/MediaScanReceiver( 5275): media scanning finished
,I/GHttpClientFactory( 5292): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 5292): Using platform SSLCertificateSocketFactory
I/com.lge.bnr.receiver.MediaScanReceiver( 5275): android.intent.action.MEDIA_SCANNER_FINISHED
,I/AlertUtils( 3882): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
E/MediaScanReceiver( 5275): media scanning start or checking
I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/NotificationManager( 5292): com.google.android.music: cancel(1061) by com.google.android.music
I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
D/ToneMappingReceiver( 5177): Enter doAlarmRingToneUriMapping()
I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
D/ToneMappingReceiver( 5177): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5177): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5177): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5177): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5177): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5177): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5177): Alarm Success count is 0
D/ToneMappingReceiver( 5177): Timer Success count is 0
,I/ActivityManager(  916): Killing 5034:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/art     ( 3199): Explicit concurrent mark sweep GC freed 16258(865KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/10MB, paused 399us total 43.107ms
,I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3882): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,W/libprocessgroup(  916): failed to open /acct/uid_10079/pid_5034/cgroup.procs: No such file or directory
I/MediaScannerReceiver( 3882): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///storage/emulated/0
,I/AlertUtils( 3882): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3882): End InitializeAlertRingtoneService.onHandleIntent
I/InitNotificationRingtoneService( 3882): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3882): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
E/MediaScanReceiver( 5275): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 5275): android.intent.action.MEDIA_SCANNER_FINISHED
I/art     ( 5292): CheckpointMarkThreadRoots callback created = 0xb042d3f0
,I/ActivityManager(  916): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5341 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AlertUtils( 3882): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/art     ( 5292): CheckpointMarkThreadRoots callback created = 0xb042d3c0
,I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
W/ResourcesManager( 5341): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 3882): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3882): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 3882): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3882): End InitializeAlertRingtoneService.onHandleIntent
D/CalendarProvider2( 5341): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1f334793
,D/CalendarProvider2( 5341): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5341): Created com.android.providers.calendar.CalendarAlarmManager@1d76fcfc(com.android.providers.calendar.CalendarProvider2@1f334793)
I/MediaStoreImporter( 5292): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
D/CalendarProviderBroadcastReceiver( 5341): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5341): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 5341): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 5341): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5341): [getOrCreateCalendarAlarmManager]
D/WearableService( 1730): callingUid 10006, callindPid: 1730
,D/LocationInitializer( 4344): Restart initialization of location
D/CalendarProvider2( 5341): [IntentService] Release Lock
D/CalendarProvider2( 5341): CalendarProviderIntentService.onDestroy()
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1730): [141] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  916): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5374 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
,W/IcingInternalCorpora( 4344): getNumBytesRead when not calculated.
,W/ActivityManager(  916): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5374): getAccountsCursor
,I/art     (  916): Explicit concurrent mark sweep GC freed 11912(670KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/34MB, paused 2.401ms total 157.117ms
,W/ActivityManager(  916): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5374): Observing account changes for notifications
,W/ActivityManager(  916): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/GAV2    ( 5374): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,W/ActivityManager(  916): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5374): getAccountsCursor
,E/Gmail   ( 5374): Error finding the version of the Email provider.....
E/Gmail   ( 5374): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5374): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5374): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5374): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5374): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5374): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5374): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5374): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5374): We do not support migrating this version of the Email provider.
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5374): notifyAccountChanged
,I/Gmail   ( 5374): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 4344): Explicit concurrent mark sweep GC freed 19087(1470KB) AllocSpace objects, 29(464KB) LOS objects, 40% free, 12MB/20MB, paused 1.239ms total 131.573ms
I/Gmail   ( 5374): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
I/Gmail   ( 5374): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5374): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5374): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager(  916): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5430 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 353us total 22.366ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.821ms
,V/DownloadManager( 3199): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@24d2c7f4 on behalf of 4344
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 23.817ms
,I/art     ( 4060): Explicit concurrent mark sweep GC freed 3318(131KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.002ms total 34.551ms
I/Gmail   ( 5374): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PhoneMonitor( 5430): Register our PhoneStateListener
,I/ActivityManager(  916): Killing 5123:com.android.chrome/u0a48 (adj 15): empty #11
,W/libprocessgroup(  916): failed to open /acct/uid_10048/pid_5123/cgroup.procs: No such file or directory
,V/DownloadManager( 3199): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@163ab1d on behalf of 4344
,V/DownloadManager( 3199): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@2b00e192 on behalf of 4344
I/CheckinService( 4344): Checkin interval check for package: unspecified last checkin: 1457130158940 min interval config: 0 actual interval: 1862
D/PhoneMonitor( 5430): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,V/TelephonyAutoProfiling( 5430): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5430): [parse] Load xml
I/CheckinService( 4344): Checking schedule, now: 1457130160814 next: 1457130188898
I/CheckinService( 4344): active receiver: disabled
V/TelephonyAutoProfiling( 5430): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 5430): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5430): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  916): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5453 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
W/ResourcesManager( 5453): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5453): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5453): MmsConfig.loadMmsSettings
I/Babel_SMS( 5453): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5453): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5453): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5453): MmsConfig.loadFromResources
E/Babel_SMS( 5453): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 5453): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5453): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5453): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5453): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5453): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 5453): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5453): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5453): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5453): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5453): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5453): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5453): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5453): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5453): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5453): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5453): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5453): found sensor: Motion Accel, handle=46
W/Settings( 5453): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5453): startup - clean
I/art     ( 5453): CheckpointMarkThreadRoots callback created = 0xb042d920
,I/Babel   ( 5453): deleted: false for 0
,I/art     ( 5453): CheckpointMarkThreadRoots callback created = 0xb042d900
,W/AudioCapabilities( 5453): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5453): Unsupported mime audio/adpcm
W/AudioCapabilities( 5453): Unsupported mime audio/g726
W/AudioCapabilities( 5453): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5453): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5453): Unsupported mime video/mjpg
,W/VideoCapabilities( 5453): Unsupported mime video/theora
W/AudioCapabilities( 5453): Unsupported mime audio/evrc
,W/AudioCapabilities( 5453): Unsupported mime audio/qcelp
I/NotificationManager( 1945): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,W/VideoCapabilities( 5453): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5453): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5453): Unsupported mime audio/qcelp
W/AudioCapabilities( 5453): Unsupported mime audio/evrc
W/VideoCapabilities( 5453): Unsupported mime video/mp4v-esdp
,I/ActivityManager(  916): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5492 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AudioManager( 5206): getMode name:com.lge.qremote
,I/AudioManager( 5206): getMode name:com.lge.qremote
I/VideoCapabilities( 5453): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5453): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5453): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5453): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5453): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  916): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5510 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager(  916): Killing 5147:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/vclib   ( 5453): onServiceConnected
W/Babel   ( 5453): Attempted to change video mute state without an active call.
I/NotificationManager( 5453): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/UEI.SmartControl( 5492): Quickset Services start...
,I/UEI.SmartControl( 5492): Manufacture = LGE
D/UEI.SmartControl( 5492): File observer start...
E/UEI.SmartControl( 5492): IR Port is disabled: false
D/UEI.SmartControl( 5492): Starting file observer...
D/UEI.SmartControl( 5492): Extracting JNI libs...
D/UEI.SmartControl( 5492): --- this system supports 32-bit or 64-bit only
W/libprocessgroup(  916): failed to open /acct/uid_10086/pid_5147/cgroup.procs: No such file or directory
,W/ResourcesManager( 5510): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5510): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5510): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/LGEmail ( 5510): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 5510): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/UEI.SmartControl( 5492): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5492): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5492): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 5492): --- Selecting new region: 2
I/UEI.SmartControl( 5492): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5492): Platform has CIR...
D/UEI.SmartControl( 5492): NO CIR support, need to check package...
I/UEI.SmartControl( 5492): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5492): QS Service created
E/UEI.SmartControl( 5492): QS start get config
,I/PackageChangeReceiver( 5510): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager(  916): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5537 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  916): Killing 5227:com.android.settings/1000 (adj 15): empty #11
D/UEI.SmartControl( 5492): Loading JNI Libs...
D/UEI.SmartControl( 5492):  configuring local db...
W/libprocessgroup(  916): failed to open /acct/uid_1000/pid_5227/cgroup.procs: No such file or directory
I/ActivityManager(  916): Killing 5252:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 5492):  ---- Has DB8: true
W/libprocessgroup(  916): failed to open /acct/uid_1000/pid_5252/cgroup.procs: No such file or directory
D/UEI.SmartControl( 5492): QS start statue = true Error code = 0
D/UEI.SmartControl( 5492): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5492): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5492): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5492): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5492): IrrcClient ++ 
D/irrcClient( 5492): getIrrcService ++ 
D/irrcClient( 5492): getIrrcService -- 
D/irrcClient( 5492): IrrcClient -- 
W/irrc_jni( 5492): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5492): Services init done
I/UEI.SmartControl( 5492): Device manager: loading config....
I/ActivityManager(  916): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5557 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/UEI.SmartControl( 5492): QS Service init finished
D/UEI.SmartControl( 5492): QS Service version name: 0.1.73
D/UEI.SmartControl( 5492): QS Service version code: 1073
D/UEI.SmartControl( 5492): Config is loaded...
I/ActivityManager(  916): Killing 5177:com.lge.clock/u0a10 (adj 15): empty #11
D/UEI.SmartControl( 5492): Service requested: Control
D/UEI.SmartControl( 5492):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5492): Notify AllClients services are ready: 0
W/libprocessgroup(  916): failed to open /acct/uid_10010/pid_5177/cgroup.procs: No such file or directory
D/UEI.SmartControl( 5492): Internal service binding...
D/UEI.SmartControl( 5492): -----IControl: 11
D/UEI.SmartControl( 5492): Caller: com.lge.qremote
D/UEI.SmartControl( 5492): ------------ IControl registerCallback...
I/UEI.SmartControl( 5492): Registering callback...
D/UEI.SmartControl( 5492): -----IControl: 19
D/UEI.SmartControl( 5492): Caller: com.lge.qremote
I/UEI.SmartControl( 5492): Registering Services Ready callback...
I/UEI.SmartControl( 5492): Notify client services are ready...
D/UEI.SmartControl( 5492): -----IControl: 8
D/UEI.SmartControl( 5492): Caller: com.lge.qremote
I/ActivityManager(  916): Killing 5292:com.google.android.music:main/u0a81 (adj 15): empty #11
I/AppUp4:AppBoxCP( 5557): onCreate
W/AppUp4:DB( 5557):  [AppBoxDatabaseHelper] construct
I/ActivityManager(  916): Killing 5275:com.lge.bnr/1000 (adj 15): empty #12
I/AppUp4:DB( 5557):  setFingerPrint start
I/AppUp4:DB( 5557):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5557):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5557):  SDK version = 0
I/AppUp4:DB( 5557):  beforefinger == newfinger no write in DB
W/libprocessgroup(  916): failed to open /acct/uid_10081/pid_5292/cgroup.procs: No such file or directory
W/libprocessgroup(  916): failed to open /acct/uid_1000/pid_5275/cgroup.procs: No such file or directory
D/AppUp4:AppBoxApplication( 5557): AppBoxApplication onCreate()
D/AppUp4:PreloadHelper( 5557): removed from Exclude : com.test.thalitest : 1
I/ActivityManager(  916): Killing 5341:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  916): failed to open /acct/uid_10014/pid_5341/cgroup.procs: No such file or directory
,D/AlertService( 3882): Beginning updateAlertNotification
,I/ActivityManager(  916): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5577 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ActivityManager(  916): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5594 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 5577): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5577): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1f334793
,D/CalendarProvider2( 5577): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5577): Created com.android.providers.calendar.CalendarAlarmManager@1d76fcfc(com.android.providers.calendar.CalendarProvider2@1f334793)
W/ResourcesManager( 5594): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5594): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5594): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/AlertService( 3882): No fired or scheduled alerts
I/NotificationManager( 3882): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3882): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3882): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3882): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3882): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3882): com.android.calendar: cancel(5) by com.android.calendar
,I/NotificationManager( 3882): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3882): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3882): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3882): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3882): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3882): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3882): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3882): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3882): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3882): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3882): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3882): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3882): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3882): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3882): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 3882): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/ActivityManager(  916): Killing 5374:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  916): failed to open /acct/uid_10053/pid_5374/cgroup.procs: No such file or directory
,D/AlarmScheduler( 3882): No events found starting within 1 week.
I/AppConfig( 5594): Total System Memory = 906309632
,I/GalleryUtils( 5594): Application Heap = 96 MB
I/AppConfig( 5594): App Tier : NOT_DEF
D/SystemHelper( 5594): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  916): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5617 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  916): Killing 5430:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  916): failed to open /acct/uid_10038/pid_5430/cgroup.procs: No such file or directory
,W/ResourcesManager( 5617): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5617): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5617): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5617): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5617): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 5617): BUILD Country: EU
I/SystemConfig( 5617): BUILD Operator: OPEN
,I/SystemConfig( 5617): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5617): existFile = false
,I/SystemConfig( 5617): canReadFile = false
I/SystemConfig( 5617): systemFeature RCS result false
D/SystemConfig( 5617): refreshRcsSupport() :false
,I/ActivityManager(  916): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5636 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  916): Killing 4060:com.google.process.gapps/u0a6 (adj 15): empty #11
W/libprocessgroup(  916): failed to open /acct/uid_10006/pid_4060/cgroup.procs: No such file or directory
,I/LockScreenSettings( 5636): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/art     (  916): Explicit concurrent mark sweep GC freed 19504(930KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.672ms total 136.230ms
,I/LockScreenSettings( 5636): New app installed broadcast received ..
I/LockScreenSettings( 5636): Number of installed packages  1
,I/ActivityManager(  916): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5653 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  916): Killing 5453:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  916): failed to open /acct/uid_10061/pid_5453/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 5653): action : android.intent.action.PACKAGE_ADDED
,D/EulaProviderUpdateObserver( 5653): uri : package:com.test.thalitest
,I/ActivityManager(  916): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5670 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  916): Killing 5206:com.lge.qremote/u0a106 (adj 15): empty #11
I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 28.093ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 21.127ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 21.423ms
,W/libprocessgroup(  916): failed to open /acct/uid_10106/pid_5206/cgroup.procs: No such file or directory
D/[BNRAppListMgrReceiver]( 5670): android.intent.action.PACKAGE_ADDED : com.test.thalitest
,W/MainApplication( 5670): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ActivityManager(  916): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5688 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  916): Killing 5492:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/libprocessgroup(  916): failed to open /acct/uid_10089/pid_5492/cgroup.procs: No such file or directory
,I/GAv4    ( 5688): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5688):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5688):   adb logcat -s GAv4
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/GAv4    ( 5688): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5688): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5688): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 5688): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,D/InitAlarmsService( 3882): Clearing and rescheduling alarms.
,D/CalendarProvider2( 5577): Scheduling check of next Alarm
D/CalendarProvider2( 5577): SCHEDULE_ALARM_REMOVE
I/CheckinService( 4344): Done disabling old GoogleServicesFramework version
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5688): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
I/ActivityManager(  916): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5721 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  916): Killing 3882:com.android.calendar/u0a13 (adj 15): empty #11
I/art     ( 5688): CheckpointMarkThreadRoots callback created = 0xaaf2c220
,W/ResourcesManager( 5688): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5688): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/art     ( 5688): CheckpointMarkThreadRoots callback created = 0xb050fa70
W/libprocessgroup(  916): failed to open /acct/uid_10013/pid_3882/cgroup.procs: No such file or directory
,W/ResourcesManager( 5721): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  916): Killing 5510:com.lge.email/u0a21 (adj 15): empty #11
,I/NotificationManager( 5688): com.google.android.apps.docs: cancel(10436) by com.google.android.apps.docs
V/JNIHelp ( 5688): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 5688): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5688): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  916): failed to open /acct/uid_10021/pid_5510/cgroup.procs: No such file or directory
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  916): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5766 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/GservicesProvider( 5766): Gservices pushing to system: true; secure/global: true
,I/ActivityManager(  916): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5785 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1945): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1945): UpdateCorporaTask done [took 99 ms] updated apps [took 99 ms] 
,I/GoogleHttpClient( 5766): GMS http client unavailable, use old client
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/GoogleHttpClient( 5766): GMS http client unavailable, use old client
,I/ActivityManager(  916): Killing 5076:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  916): failed to open /acct/uid_10006/pid_5076/cgroup.procs: No such file or directory
,I/ActivityManager(  916): Killing 5537:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/libprocessgroup(  916): failed to open /acct/uid_10009/pid_5537/cgroup.procs: No such file or directory
,D/Finsky  ( 5785): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/CalendarProvider2( 5577): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5577): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/Finsky  ( 5785): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5785): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5785): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5785): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3199): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@1d06b763 on behalf of 5785
I/NotificationManager( 5785): com.android.vending: cancel(1003285959) by com.android.vending
D/Finsky  ( 5785): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5785): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 5785): Skipping gmscore version check
D/ChimeraCfgMgr( 4344): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4344): Loading module APK com.google.android.play.games
D/Finsky  ( 5785): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/PackageBroadcastService( 4344): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/Finsky  ( 5785): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 5785): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  916): Killing 5557:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  916): failed to open /acct/uid_10011/pid_5557/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 4344): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4344): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4344): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/Icing   ( 4344): Storage manager: low false usage 1.76MB avail 2.37GB capacity 4.06GB
D/AsyncTaskServiceImpl( 4344): Submit a task: k
,D/ChimeraCfgMgr( 4344): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 4344): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 4344): Processing package: com.test.thalitest
I/PeopleDatabaseHelper( 4344): cleanUpNonGplusAccounts done.
,D/GassUtils( 4344): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 4344): Found info for package com.test.thalitest in db.
,I/ActivityManager(  916): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5862 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/BaseAppContext( 4344): Using Auth Proxy for data requests.
W/BaseAppContext( 4344): Using Auth Proxy for data requests.
,W/BaseAppContext( 4344): Using Auth Proxy for data requests.
W/BaseAppContext( 4344): Using Auth Proxy for data requests.
,W/BaseAppContext( 4344): Using Auth Proxy for data requests.
,W/ResourcesManager( 5862): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/BluetoothManagerService(  916): Message: 20
D/BluetoothManagerService(  916): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fee5031:true
D/BluetoothAdapterService(146074856)( 2055): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a0a6f7e
,D/BluetoothAdapterService(146074856)( 2055): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a0a6f7e
I/AudioManager( 5862): getMode name:com.lge.qremote
,I/AudioManager( 5862): getMode name:com.lge.qremote
,I/AudioManager( 5862): getMode name:com.lge.qremote
,D/WearableService( 1730): callingUid 10006, callindPid: 1730
,E/MDM     ( 1730): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4344): Restart initialization of location
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  916): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=5888 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
,W/ResourcesManager( 5888): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Icing   ( 4344): updateResources: need to parse f{com.google.android.gms}
,I/Babel_SMS( 5888): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5888): MmsConfig.loadMmsSettings
I/Babel_SMS( 5888): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5888): MmsConfig.loadFromDatabase
,I/Icing   ( 4344): Internal init done: storage state 0
,E/Babel_SMS( 5888): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5888): MmsConfig.loadFromResources
E/Babel_SMS( 5888): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5888): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5888): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5888): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5888): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5888): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5888): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5888): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5888): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5888): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5888): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5888): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5888): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5888): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5888): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5888): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5888): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5888): found sensor: Motion Accel, handle=46
,I/Icing   ( 4344): Post-init done
W/Settings( 5888): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5888): startup - clean
I/art     ( 1730): Explicit concurrent mark sweep GC freed 39519(2MB) AllocSpace objects, 31(496KB) LOS objects, 39% free, 13MB/22MB, paused 1.546ms total 99.278ms
,D/ChimeraCfgMgr( 4344): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4344): Module APK com.google.android.play.games already loaded
,I/art     ( 5888): CheckpointMarkThreadRoots callback created = 0xb042d910
,I/Babel   ( 5888): deleted: false for 0
,I/art     ( 5888): CheckpointMarkThreadRoots callback created = 0xb042d8f0
,W/AudioCapabilities( 5888): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5888): Unsupported mime audio/adpcm
W/AudioCapabilities( 5888): Unsupported mime audio/g726
W/AudioCapabilities( 5888): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5888): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5888): Unsupported mime video/mjpg
W/VideoCapabilities( 5888): Unsupported mime video/theora
W/AudioCapabilities( 5888): Unsupported mime audio/evrc
,W/AudioCapabilities( 5888): Unsupported mime audio/qcelp
W/VideoCapabilities( 5888): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  916): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5925 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/AudioCapabilities( 5888): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5888): Unsupported mime audio/qcelp
W/AudioCapabilities( 5888): Unsupported mime audio/evrc
,W/VideoCapabilities( 5888): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5888): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5888): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5888): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5888): Unrecognized profile 2130706433 for video/avc
,I/AppUp4:AppBoxCP( 5925): onCreate
W/AppUp4:DB( 5925):  [AppBoxDatabaseHelper] construct
W/VideoCapabilities( 5888): Unrecognized profile 2130706433 for video/avc
I/AppUp4:DB( 5925):  setFingerPrint start
,I/AppUp4:DB( 5925):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5925):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5925):  SDK version = 0
I/AppUp4:DB( 5925):  beforefinger == newfinger no write in DB
,W/art     ( 5888): Suspending all threads took: 29.114ms
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/art     (  916): Explicit concurrent mark sweep GC freed 20895(948KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.459ms total 149.206ms
,D/AppUp4:AppBoxApplication( 5925): AppBoxApplication onCreate()
I/vclib   ( 5888): onServiceConnected
W/Babel   ( 5888): Attempted to change video mute state without an active call.
I/AppUp4:CustModeStarterReceiver( 5925): onReceive
I/AppUp4:CustModeStarterReceiver( 5925): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,I/NotificationManager( 5888): com.google.android.talk: cancel(8) by com.google.android.talk
D/AppUp4:CustFacade( 5925): Context : android.app.ReceiverRestrictedContext@119cb6ce
D/AppUp4:CustFacade( 5925): isCustomizationCompleted : false
W/ResourcesManager( 5888): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5888): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/AppUp4:CustFacade( 5925): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5925): begin check event
I/AppUp4:CustModeStarterReceiver( 5925): Event For Nothing, skip.
I/ActivityManager(  916): Killing 5594:com.android.gallery3d/u0a23 (adj 15): empty #11
V/JNIHelp ( 5888): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/libprocessgroup(  916): failed to open /acct/uid_10023/pid_5594/cgroup.procs: No such file or directory
,W/System  ( 5888): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5888): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  916): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5948 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/NotificationManager( 5888): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 5948): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5948): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5948): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 5948): Total System Memory = 906309632
,I/GalleryUtils( 5948): Application Heap = 96 MB
I/AppConfig( 5948): App Tier : NOT_DEF
D/SystemHelper( 5948): region [EU], country [EU], operator [OPEN], sub-operator []
D/LockScreenSettings( 5636): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5636): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true,
D/LockScreenSettings( 5636): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5636): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5636): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  916): Killing 5653:com.lge.eula/1000 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1945): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
W/libprocessgroup(  916): failed to open /acct/uid_1000/pid_5653/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1945): UpdateCorporaTask done [took 71 ms] updated apps [took 71 ms] 
D/PackageBroadcastService( 4344): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4344): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 4344): updateResources: need to parse f{com.google.android.gms}
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,I/ActivityManager(  916): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5982 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 5862): Create singleton instance
,I/Icing   ( 4344): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
D/UEI.SmartControl( 5982): Quickset Services start...
,I/UEI.SmartControl( 5982): Manufacture = LGE
D/UEI.SmartControl( 5982): File observer start...
E/UEI.SmartControl( 5982): IR Port is disabled: false
D/UEI.SmartControl( 5982): Starting file observer...
D/UEI.SmartControl( 5982): Extracting JNI libs...
D/UEI.SmartControl( 5982): --- this system supports 32-bit or 64-bit only
,I/AudioManager( 5862): getMode name:com.lge.qremote
I/AudioManager( 5862): getMode name:com.lge.qremote
D/UEI.SmartControl( 5982): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5982): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5982): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/ActivityManager(  916): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6001 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
D/Icing   ( 4344): Loaded CLD2 Version V2.0 - 20141016
I/UEI.SmartControl( 5982): --- Selecting new region: 2
I/UEI.SmartControl( 5982): -- Running on KitKat(19) and above! JNI will be used.
,I/Icing   ( 4344): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
D/UEI.SmartControl( 5982): Platform has CIR...
D/UEI.SmartControl( 5982): NO CIR support, need to check package...
I/UEI.SmartControl( 5982): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 5982): QS Service created
E/UEI.SmartControl( 5982): QS start get config
,D/UEI.SmartControl( 5982): Loading JNI Libs...
,D/UEI.SmartControl( 5982):  configuring local db...
I/[SystemUI]QPairHandler( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
D/PhoneMonitor( 6001): Register our PhoneStateListener
,I/[SystemUI]QSlideListController( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  916): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
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
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/administrator(  916): Handling package changes for user 0
V/SetupWizard( 6001): Connected to Gservices successfully
,I/ActivityManager(  916): Killing 5670:com.lge.bnr/1000 (adj 15): empty #11
,D/PhoneMonitor( 6001): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6001): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6001): [parse] Load xml
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
V/TelephonyAutoProfiling( 6001): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6001): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6001): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/NotificationService(  916): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  916): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  916): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,W/libprocessgroup(  916): failed to open /acct/uid_1000/pid_5670/cgroup.procs: No such file or directory
I/BackupManagerService(  916): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  916): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  916): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2c563804
W/ResourcesManager(  916): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  916): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6027 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourceType(  916): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/art     (  311): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.427ms
I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 20.480ms
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 20.948ms
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/GCoreNlp( 1730): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  916): applying state to connected service
,D/UEI.SmartControl( 5982):  ---- Has DB8: true
,D/UEI.SmartControl( 5982): QS start statue = true Error code = 0
D/UEI.SmartControl( 5982): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5982): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5982): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5982): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5982): IrrcClient ++ 
D/irrcClient( 5982): getIrrcService ++ 
D/irrcClient( 5982): getIrrcService -- 
D/irrcClient( 5982): IrrcClient -- 
W/irrc_jni( 5982): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5982): Services init done
,I/UEI.SmartControl( 5982): Device manager: loading config....
D/UEI.SmartControl( 5982): QS Service init finished
D/UEI.SmartControl( 5982): QS Service version name: 0.1.73
D/UEI.SmartControl( 5982): QS Service version code: 1073
D/UEI.SmartControl( 5982): Service requested: Control
D/UEI.SmartControl( 5982): Config is loaded...
D/UEI.SmartControl( 5982): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 5982):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5982): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5982): Internal service binding...
D/UEI.SmartControl( 5982): -----IControl: 11
D/UEI.SmartControl( 5982): Caller: com.lge.qremote
D/UEI.SmartControl( 5982): ------------ IControl registerCallback...
I/UEI.SmartControl( 5982): Registering callback...
D/UEI.SmartControl( 5982): -----IControl: 19
,D/UEI.SmartControl( 5982): Caller: com.lge.qremote
I/UEI.SmartControl( 5982): Registering Services Ready callback...
I/UEI.SmartControl( 5982): Notify client services are ready...
D/UEI.SmartControl( 5982): -----IControl: 8
D/UEI.SmartControl( 5982): Caller: com.lge.qremote
I/ActivityManager(  916): Killing 5577:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/ActivityManager(  916): Killing 5688:com.google.android.apps.docs/u0a58 (adj 15): empty #12
,W/libprocessgroup(  916): failed to open /acct/uid_10014/pid_5577/cgroup.procs: No such file or directory
,W/ActivityManager(  916): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
W/libprocessgroup(  916): failed to open /acct/uid_10058/pid_5688/cgroup.procs: No such file or directory
D/LCardEmulationManager( 1785): getDefaultRoute
I/Gmail   ( 6027): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6027): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  916): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6027): Error finding the version of the Email provider.....
E/Gmail   ( 6027): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6027): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6027): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6027): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6027): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6027): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6027): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6027): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6027): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6027): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  916): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/ActivityManager(  916): Killing 5925:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/Gmail   ( 6027): Observing account changes for notifications
I/Icing   ( 4344): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4344): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
W/ActivityManager(  916): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/libprocessgroup(  916): failed to open /acct/uid_10011/pid_5925/cgroup.procs: No such file or directory
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/AudioManager( 5862): getMode name:com.lge.qremote
I/ActivityManager(  916): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6072 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 6027): notifyAccountChanged
,I/Gmail   ( 6027): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6027): getAccountsCursor
,I/Gmail   ( 6027): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6027): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/ResourcesManager( 6072): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Gmail   ( 6027): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CalendarApplication( 6072): CalendarApplication.onCreate()
,I/Gmail   ( 6027): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PreferenceKeysParser( 6072): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6072): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@29f8dfc9, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@119cb6ce, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@30c0c9ef, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1d76fcfc, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@33a6af85, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@d5171da, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@24fa160b, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@8b4ece8, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@38a7bf01, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@3764d1a6, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1a3207e7, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@295fef94, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@39504a3d, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@5fc6232, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@170d3b83, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@23167100, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2cfc4d39, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3a0a6f7e, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1dde0cdf, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@32f19d2c, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@acb83f5, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@1f5a058a, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@19c097fb, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@2c716018, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@221d6a71, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@15af056, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@176b8d7, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@192865c4, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@3ecd3cad, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@20adbbe2, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@c040b73, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@27281a30, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@152df6a9, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@356fb42e, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@1309ebcf, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@122ca95c, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@31c65465, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@a46e53a, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3ee375eb, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3388ff48, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@28ccd1e1, lg_preferences_rec,ent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@3c2e1b
D/GeneralPreferenceUtils( 6072): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6072): [init]
I/Config  ( 6072): LGCalendar ver.4.40.17
I/Config  ( 6072): start check model
I/Config  ( 6072): start check native_ca
I/Config  ( 6072): Config Operator=OPEN, Country=EU
D/Config  ( 6072): [setDefaultValuesToPref]
D/Config  ( 6072): [parseProfiles]
D/ProfilesParser( 6072): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6072): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6072): [updateProfiletoCountryInfo]
D/GeneralPreference( 6072): [checkAndMigrateOldPreference]
,D/AlertReceiver( 6072): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/art     (  916): Explicit concurrent mark sweep GC freed 24087(1207KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 1.868ms total 153.625ms
,V/AlarmManager(  916): ELAPSED_WAKEUP set : Alarm{1f91ca73 type 2 when 88495 com.android.providers.calendar} when 88495
I/InitNotificationRingtoneService( 6072): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6072): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 6072): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6072): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6072): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6072): set default noti to content://media/internal/audio/media/38
,I/InitNotificationRingtoneService( 6072): End InitializeAlertRingtoneService.onHandleIntent
W/HolidayIntentService( 6072): onHandleIntent
,D/HolidayDataLoader( 6072): readJsonAsset : holiday.json
D/AlertService( 6072): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6072): [updateWidgets] 
D/MonthWidgetProvider( 6072): [onReceive]
D/CalendarWidgetProvider( 6072): [onReceive]
D/CalendarWidgetProvider( 6072): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6072): [onCreate] mContext.getPackageName() = com.android.calendar
,D/WeekWidgetProvider( 6072): [onReceive]
D/CalendarWidgetProvider( 6072): [onReceive]
D/CalendarWidgetProvider( 6072): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
I/AudioManager( 5862): getMode name:com.lge.qremote
,D/CalendarTypeController( 6072): [onCreate] mContext.getPackageName() = com.android.calendar
E/HolidayIntentService( 6072): onHandleIntent:holiday data empty
,I/ActivityManager(  916): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6120 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/NotificationManager( 5888): com.google.android.talk: cancel(8) by com.google.android.talk
,I/AppUp4:AppBoxCP( 6120): onCreate
,W/AppUp4:DB( 6120):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6120):  setFingerPrint start
I/AppUp4:DB( 6120):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6120):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6120):  SDK version = 0
I/AppUp4:DB( 6120):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6120): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6120): onReceive
I/AppUp4:CustModeStarterReceiver( 6120): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6120): Context : android.app.ReceiverRestrictedContext@119cb6ce
D/AppUp4:CustFacade( 6120): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6120): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6120): begin check event
I/AppUp4:CustModeStarterReceiver( 6120): Event For Nothing, skip.
I/ActivityManager(  916): Killing 5948:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  916): failed to open /acct/uid_10023/pid_5948/cgroup.procs: No such file or directory
,I/ActivityManager(  916): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6142 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 6142): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6142): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6142): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 6142): Total System Memory = 906309632
,I/GalleryUtils( 6142): Application Heap = 96 MB
I/AppConfig( 6142): App Tier : NOT_DEF
D/SystemHelper( 6142): region [EU], country [EU], operator [OPEN], sub-operator []
D/LockScreenSettings( 5636): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5636): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5636): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5636): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5636): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  916): Killing 5785:com.android.vending/u0a36 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1945): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/UpdateIcingCorporaServi( 1945): UpdateCorporaTask done [took 36 ms] updated apps [took 36 ms] 
,W/BroadcastQueue(  916): Exception when sending broadcast to ComponentInfo{com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver}
W/BroadcastQueue(  916): android.os.DeadObjectException
W/BroadcastQueue(  916): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue(  916): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue(  916): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:857)
W/BroadcastQueue(  916): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:270)
W/BroadcastQueue(  916): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1002)
W/BroadcastQueue(  916): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16810)
W/BroadcastQueue(  916): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:473)
W/BroadcastQueue(  916): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2625)
W/BroadcastQueue(  916): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:457)
W/BroadcastQueue(  916): 	at android.os.Binder.execTransact(Binder.java:446)
W/libprocessgroup(  916): failed to open /acct/uid_10036/pid_5785/cgroup.procs: No such file or directory
,I/ActivityManager(  916): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6170 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ActivityManager(  916): Spurious death for ProcessRecord{21935daf 6170:com.android.vending/u0a36}, curProc for 5785: null
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/Finsky  ( 6170): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6170): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6170): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6170): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6170): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3199): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3199): created cursor android.database.sqlite.SQLiteCursor@214e6f60 on behalf of 6170
D/Ads     ( 6170): Skipping gmscore version check
,D/Finsky  ( 6170): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6170): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 6170): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 4344): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/AudioManager( 5862): getMode name:com.lge.qremote
I/PackageBroadcastService( 4344): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 6170): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 4344): updateResources: need to parse f{com.google.android.gms}
I/AudioManager( 5862): getMode name:com.lge.qremote
,I/AudioManager( 5862): getMode name:com.lge.qremote
I/ActivityManager(  916): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6224 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  916): Killing 6001:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  916): failed to open /acct/uid_10038/pid_6001/cgroup.procs: No such file or directory
,W/ResourcesManager( 6224): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6224): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1f334793
,D/CalendarProvider2( 6224): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6224): Created com.android.providers.calendar.CalendarAlarmManager@1d76fcfc(com.android.providers.calendar.CalendarProvider2@1f334793)
D/CalendarProviderBroadcastReceiver( 6224): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6224): [IntentService] WakeLock acquire, start IntentSerivce
I/AudioManager( 5862): getMode name:com.lge.qremote
,D/CalendarProvider2( 6224): CalendarProviderIntentService.onCreate()
I/AudioManager( 5862): getMode name:com.lge.qremote
D/CalendarProvider2( 6224): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6224): [getOrCreateCalendarAlarmManager]
I/AudioManager( 5862): getMode name:com.lge.qremote
,I/AudioManager( 5862): getMode name:com.lge.qremote
D/CalendarProvider2( 6224): [IntentService] Release Lock
,D/CalendarProvider2( 6224): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  916): Killing 6120:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  916): failed to open /acct/uid_10011/pid_6120/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/Icing   ( 4344): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4344): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  916): Killing 6142:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  916): failed to open /acct/uid_10023/pid_6142/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/Finsky  ( 6170): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 92597785051; DSPS: 3132679; Offset : -3015356644
V/AlarmManager(  916): RTC_WAKEUP set : Alarm{21d7e53 type 0 when 1457130174345 com.android.vending} when 1457130174345
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 5982): Internal timer expired: 1
,I/NotificationManager(  916): android: cancelAsUser(2) by android
,D/libc-netbsd( 6170): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6170): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6170): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6170): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 6170): propertyValue:false
D/libc-netbsd( 6170): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6170): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/GAV2    ( 6027): Thread[GAThread,5,main]: No campaign data found.
,D/libc-netbsd( 6170): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6170): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  916): android: cancelAsUser(2) by android
D/AlertService( 6072): Beginning updateAlertNotification
,D/AlertService( 6072): No fired or scheduled alerts
,I/NotificationManager( 6072): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(8) by com.android.calendar
,I/NotificationManager( 6072): com.android.calendar: cancel(9) by com.android.calendar
I/qtaguid ( 6170): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6170): Untagging socket 41 failed errno=-22
I/NotificationManager( 6072): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(14) by com.android.calendar
W/NetworkManagementSocketTagger( 6170): untagSocket(41) failed with errno -22
I/NotificationManager( 6072): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(16) by com.android.calendar
,I/NotificationManager( 6072): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6072): com.android.calendar: cancel(20) by com.android.calendar
D/Finsky  ( 6170): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,D/AlertService( 6072): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 6072): No events found starting within 1 week.
,I/ActivityManager(  916): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6274 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  916): android: cancelAsUser(2) by android
,I/ActivityManager(  916): Killing 6072:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  916): failed to open /acct/uid_10013/pid_6072/cgroup.procs: No such file or directory
W/ResourcesManager( 6274): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6274): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6274): VM with version 2.1.0 has multidex support
I/MultiDex( 6274): install
,I/MultiDex( 6274): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6274): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6274): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6274): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@26c784de: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6274): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6274): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6274): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1730): callingUid 10006, callindPid: 1730
,D/ChimeraCfgMgr( 6274): Reading stored module config
E/MDM     ( 1730): [146] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4344): Restart initialization of location
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
D/ChimeraCfgMgr( 6274): Loading module com.google.android.gms.car from APK com.google.android.gms
W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
,D/CAR.SERVICE( 6274): Connecting to CarCallService...
,I/art     ( 6274): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6274): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/NativeLibraryUtils( 6274): Install completed successfully. count=14 extracted=0
D/CAR.SERVICE( 6274): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6274): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6274): Creating a new PhoneAdapter instance
W/ActivityManager(  916): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6274): setListener: com.google.android.gms.car.dn@38d9e945
W/ActivityManager(  916): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6274): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6274): Starting CarCallService with initial phone null
I/qtaguid ( 6170): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6170): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6170): untagSocket(41) failed with errno -22
I/NotificationManager( 6274): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6274): Package validated; name: com.android.vending
,I/art     ( 6170): CheckpointMarkThreadRoots callback created = 0xb056f440
,I/art     ( 6170): CheckpointMarkThreadRoots callback created = 0xb056f420
,I/art     (  916): Explicit concurrent mark sweep GC freed 21643(994KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.548ms total 139.412ms
,I/NotificationManager( 6170): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6170): [1] GearheadStateMonitor.access$100: mIsProjecting:false
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  916): android: cancelAsUser(2) by android
,I/qtaguid ( 6170): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6170): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6170): untagSocket(41) failed with errno -22
,W/ResourcesManager( 6170): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6170): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6170): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6170): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  916): RTC_WAKEUP set : Alarm{12877e4d type 0 when 1457130177617 com.android.vending} when 1457130177617
D/DeviceConnectionService( 1730): client connected with version: 8296000
,D/Finsky  ( 6170): [764] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  916): android: cancelAsUser(2) by android
,D/Finsky  ( 6170): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 6170): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/libc-netbsd( 6170): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6170): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6170): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6170): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 6170): propertyValue:false
I/ActivityManager(  916): Killing 5888:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  916): failed to open /acct/uid_10061/pid_5888/cgroup.procs: No such file or directory
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
,I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
,I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
D/PowerManagerServiceEx(  916): acquireWakeLockInternal: lock=340021543, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=916
,D/WeatherService( 2698): 2 : TimeTick Intent has been received, Time(hour:min:sec) 23:23:0
,D/WeatherService( 2698): 2 : TimeTick Intent And Screen On
D/WeatherService( 2698): 2 : SDK version : 21
W/ActivityManager(  916): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2698): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2698): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2698): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2698): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2698): 2 : This is isUpdating : false
D/WeatherService( 2698): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2698): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2698): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2698): 2 : Fixed theme : optimus
D/WeatherReflect( 2698): 2 : Map key string is -2
,D/lim     ( 2698): 2 : time = 23:23
I/WeatherReflect( 2698): Model Name : LG-D722
D/WeatherTheme( 2698): 2 : Different view - status_min_formatted : 22 != 23
D/WeatherTheme( 2698): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2698): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2698): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2698): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2698): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2698): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
D/Weather4x2_optimus( 2698): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2698): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2698): forecast size is 0
D/Theme   ( 2698): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2698): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2698): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2698): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2698): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2698): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2698): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2698): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2698): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2698): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2698): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2698): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2698): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2698): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2698): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2698): url is : null
D/Theme   ( 2698): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2698): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2698): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2698): 2 : update view, appWidgetId: 2
D/WeatherService( 2698): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 23:23:0
,D/PowerManagerServiceEx(  916): releaseWakeLockInternal: lock=340021543 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ActivityManager(  916): Killing 5617:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  916): failed to open /acct/uid_10018/pid_5617/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/CAR.SERVICE( 6274): mConnectedToCar = false, abort
,E/ActivityThread( 6274): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@286a958d that was originally bound here
E/ActivityThread( 6274): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@286a958d that was originally bound here
E/ActivityThread( 6274): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6274): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6274): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6274): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6274): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6274): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6274): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6274): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6274): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6274): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6274): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6274): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6274): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6274): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6274): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6274): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6274): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6274): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6274): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6274): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6274): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6274): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6274): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6274): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2c7005bc that was originally bound here
E/ActivityThread( 6274): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2c7005bc that was originally bound here
E/ActivityThread( 6274): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6274): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6274): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6274): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6274): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6274): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6274): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6274): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6274): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6274): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6274): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6274): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6274): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6274): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6274): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6274): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6274): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6274): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6274): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6274): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6274): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6274): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/ActivityManager(  916): Unbind failed: could not find connection for android.os.BinderProxy@2ad49a5a
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
W/SQLiteConnectionPool( 4344): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
V/AlarmManager(  916): RTC_WAKEUP set : Alarm{3f29548b type 0 when 1457130188898 com.google.android.gms} when 1457130188898
,V/AlarmManager(  916): RTC_WAKEUP set : Alarm{2ea16181 type 0 when 1457130191785 com.android.vending} when 1457130191785
,I/CheckinService( 4344): Checkin interval check for package: unspecified last checkin: 1457130158940 min interval config: 0 actual interval: 33217
,W/ContextImpl( 3675): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/CheckinService( 4344): Checking schedule, now: 1457130192226 next: 1457130188898
I/CheckinService( 4344): active receiver: enabled
,I/CheckinService( 4344): Preparing to send checkin request
I/EventLogService( 4344): Accumulating logs since 1457130152999
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/CheckinRequestBuilder( 4344): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4344): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6170): [755] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6170): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  916): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6392 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 6392): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6392): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6392): VM with version 2.1.0 has multidex support
I/MultiDex( 6392): install
I/MultiDex( 6392): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6392): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6392): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6392): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@26c784de: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6392): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6392): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6392): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1730): callingUid 10006, callindPid: 1730
,E/MDM     ( 1730): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4344): Restart initialization of location
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1730): No location to return for getLastLocation()
,W/FusedLocationProvider( 1730): location=null
I/art     ( 6392): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6392): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/NativeLibraryUtils( 6392): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): CdmEngine::OpenSession
I/WVCdm   (  279): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  279): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  279): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  279): L1 library not specified. Falling Back to L3
I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/WVCdm   (  279): PrepareKeyRequest: nonce=2223026765
I/art     ( 6392): CheckpointMarkThreadRoots callback created = 0xb0542070
,I/art     ( 6392): CheckpointMarkThreadRoots callback created = 0xb0542060
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/dex2oat ( 6429): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6429): dex2oat took 97.482ms (threads: 4)
,I/Adreno-EGL( 6392): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6392): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6392): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6392): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6392): Remote Branch: 
I/Adreno-EGL( 6392): Local Patches: 
I/Adreno-EGL( 6392): Reconstruct Branch: 
I/Adreno-EGL( 6392): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6392): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6392): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6392): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6392): Remote Branch: 
I/Adreno-EGL( 6392): Local Patches: 
I/Adreno-EGL( 6392): Reconstruct Branch: 
,I/Adreno-EGL( 6392): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6392): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6392): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6392): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6392): Remote Branch: 
I/Adreno-EGL( 6392): Local Patches: 
I/Adreno-EGL( 6392): Reconstruct Branch: 
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 112599245326; DSPS: 3788087; Offset : -3015359961
,I/CheckinRequestBuilder( 4344): Classify the device as Phone.
,D/libc-netbsd( 4344): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4344): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4344): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4344): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 4344): propertyValue:false
D/libc-netbsd( 4344): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4344): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4344): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4344): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4344): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4344): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4344): Sending checkin request (7716 bytes)
I/WVCdm   (  279): CdmEngine::CloseSession
,I/WVCdm   (  279): L3 Terminate.
I/CheckinRequestBuilder( 4344): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4344): Failed to find provider info for com.google.android.wearable.settings
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinRequestBuilder( 4344): Classify the device as Phone.
,I/CheckinTask( 4344): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4344): Checking schedule, now: 1457130195332 next: 1457657444326
,I/CheckinService( 4344): active receiver: disabled
,D/CheckinService( 4344): Recording last checkin time for package unspecified as 1457130195363
I/ActivityManager(  916): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6461 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6461): Register our PhoneStateListener
,V/SetupWizard( 6461): Connected to Gservices successfully
,D/PhoneMonitor( 6461): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6461): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6461): [parse] Load xml
V/TelephonyAutoProfiling( 6461): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6461): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6461): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/MusicWidget( 2613): mDelayedStopHandler : unbind
,I/MusicBrowser( 2715): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2715): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2715): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2715): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2715): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2715): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2715): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2715): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  916):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1f5a058acom.lge.music.MediaPlaybackService$6@19c097fb
,D/MusicBrowser( 2715): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2715): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2715): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2715): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2715): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@38a7bf01
I/MusicBrowser( 2715): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2715): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2715): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2715): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2715): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2715): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2715): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2715): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2715): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2715): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2715): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2715): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2715): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2715): reset
V/MediaPlayer[Native]( 2715): setListener
,V/MediaPlayer[Native]( 2715): disconnect
V/MediaPlayer[Native]( 2715): destructor
V/AudioFlinger(  279): releasing 19 from 2715 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/MediaPlayer[Native]( 2715): disconnect
D/MusicBrowser( 2715): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2715): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2715): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2715): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2715): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2715): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2715): [SmartShareManagerClient] unregisterListener: 745627672
,W/SmartShareClient( 2715): [SmartShareManagerClient] unregisterListener invalid listener: 745627672
I/SmartShareClient( 2715): [SmartShareManagerClient] terminate service: 2715/MediaPlaybackService/817940975
E/HomeCloudIF( 2715): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2715): [SmartShareManagerClient] unbindService context:android.app.Application@221d6a71
V/CloudHub( 2715): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2715): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2715): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2715): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,D/MusicBrowser( 2715): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  916): Killing 5636:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/CloudHub( 2715): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29994
W/libprocessgroup(  916): failed to open /acct/uid_10069/pid_5636/cgroup.procs: No such file or directory
,W/ProcessCpuTracker(  916): Skipping unknown process pid 6487
,W/ProcessCpuTracker(  916): Skipping unknown process pid 6490
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ActivityManager(  916): Killing 5721:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  916): failed to open /acct/uid_10086/pid_5721/cgroup.procs: No such file or directory
,I/ActivityManager(  916): Killing 6224:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  916): failed to open /acct/uid_10014/pid_6224/cgroup.procs: No such file or directory
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[SystemUI]QPairHandler( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  916): Reconfiguring input devices.  changes=0x00000010
,I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/administrator(  916): Handling package changes for user 0
,I/ActivityManager(  916): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6510 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/[SystemUI]QSlideListController( 1370): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1370): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
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
,W/ResourcesManager( 6510): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationService(  916): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  916): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  916): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  916): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  916): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  916): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@39949088
,W/ResourcesManager(  916): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  916): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1730): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  916): applying state to connected service
,I/Babel_SMS( 6510): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6510): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6510): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6510): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6510): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6510): MmsConfig.loadFromResources
E/Babel_SMS( 6510): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6510): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6510): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6510): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6510): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6510): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6510): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6510): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6510): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6510): found sensor: LGE Step Detector Sensor, handle=43
,D/SensorManager( 6510): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6510): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6510): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6510): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6510): found sensor: LGE Tilt Detector Sensor, handle=55
,D/SensorManager( 6510): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6510): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6510): found sensor: Motion Accel, handle=46
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
W/Settings( 6510): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6510): startup - clean
,I/art     ( 6510): CheckpointMarkThreadRoots callback created = 0xb042d920
,I/Babel   ( 6510): deleted: false for 0
,I/art     ( 6510): CheckpointMarkThreadRoots callback created = 0xb042d900
,W/AudioCapabilities( 6510): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6510): Unsupported mime audio/adpcm
W/AudioCapabilities( 6510): Unsupported mime audio/g726
W/AudioCapabilities( 6510): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6510): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6510): Unsupported mime video/mjpg
W/VideoCapabilities( 6510): Unsupported mime video/theora
,I/ActivityManager(  916): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6541 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/AudioCapabilities( 6510): Unsupported mime audio/evrc
,W/AudioCapabilities( 6510): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6510): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6510): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6510): Unsupported mime audio/qcelp
W/AudioCapabilities( 6510): Unsupported mime audio/evrc
,W/VideoCapabilities( 6510): Unsupported mime video/mp4v-esdp
,I/AppUp4:AppBoxCP( 6541): onCreate
W/AppUp4:DB( 6541):  [AppBoxDatabaseHelper] construct
I/VideoCapabilities( 6510): Unsupported profile 4 for video/mp4v-es
,I/AppUp4:DB( 6541):  setFingerPrint start
I/AppUp4:DB( 6541):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
W/VideoCapabilities( 6510): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6510): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6510): Unrecognized profile 2130706433 for video/avc
I/AppUp4:DB( 6541):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6541):  SDK version = 0
I/AppUp4:DB( 6541):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6541): AppBoxApplication onCreate()
,W/VideoCapabilities( 6510): Unrecognized profile 2130706433 for video/avc
,I/AppUp4:CustModeStarterReceiver( 6541): onReceive
I/AppUp4:CustModeStarterReceiver( 6541): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6541): Context : android.app.ReceiverRestrictedContext@119cb6ce
D/AppUp4:CustFacade( 6541): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6541): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6541): begin check event
I/AppUp4:CustModeStarterReceiver( 6541): Event For Nothing, skip.
I/ActivityManager(  916): Killing 6027:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  916): failed to open /acct/uid_10053/pid_6027/cgroup.procs: No such file or directory
,I/ActivityManager(  916): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6563 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/art     (  311): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 294us total 21.884ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 343us total 24.991ms
,I/art     (  311): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 22.662ms
,I/art     (  916): Explicit concurrent mark sweep GC freed 32899(1642KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.085ms total 153.282ms
,I/vclib   ( 6510): onServiceConnected
W/Babel   ( 6510): Attempted to change video mute state without an active call.
I/NotificationManager( 6510): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6510): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6510): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6563): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6563): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6563): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,V/JNIHelp ( 6510): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppConfig( 6563): Total System Memory = 906309632
I/GalleryUtils( 6563): Application Heap = 96 MB
I/AppConfig( 6563): App Tier : NOT_DEF
,W/System  ( 6510): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6510): Installed default security provider GmsCore_OpenSSL
D/SystemHelper( 6563): region [EU], country [EU], operator [OPEN], sub-operator []
I/NotificationManager( 6510): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager(  916): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6589 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  916): Killing 5982:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5862): android.os.DeadObjectException
W/System.err( 5862): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5862): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5862): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5862): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5862): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5862): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5862): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5862): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5862): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5862): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
,W/System.err( 5862): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5862): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5862): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5862): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5862): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5862): android.os.DeadObjectException
,W/System.err( 5862): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5862): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5862): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5862): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5862): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5862): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5862): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5862): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5862): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5862): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5862): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5862): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5862): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5862): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5862): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  916): failed to open /acct/uid_10089/pid_5982/cgroup.procs: No such file or directory
,W/ActivityManager(  916): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,W/ResourcesManager( 6589): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6589): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  916): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6606 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6589): BUILD Country: EU
I/SystemConfig( 6589): BUILD Operator: OPEN
,D/UEI.SmartControl( 6606): Quickset Services start...
,I/UEI.SmartControl( 6606): Manufacture = LGE
D/UEI.SmartControl( 6606): File observer start...
E/UEI.SmartControl( 6606): IR Port is disabled: false
D/UEI.SmartControl( 6606): Starting file observer...
D/UEI.SmartControl( 6606): Extracting JNI libs...
D/UEI.SmartControl( 6606): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6606): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6606): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6606): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/ActivityManager(  916): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6626 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  916): Killing 5862:com.lge.qremote/u0a106 (adj 15): empty #11
I/UEI.SmartControl( 6606): --- Selecting new region: 2
I/UEI.SmartControl( 6606): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6606): Platform has CIR...
D/UEI.SmartControl( 6606): NO CIR support, need to check package...
I/UEI.SmartControl( 6606): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6606): QS Service created
,W/libprocessgroup(  916): failed to open /acct/uid_10106/pid_5862/cgroup.procs: No such file or directory
I/SystemConfig( 6589): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6589): existFile = false
I/SystemConfig( 6589): canReadFile = false
I/SystemConfig( 6589): systemFeature RCS result false
D/SystemConfig( 6589): refreshRcsSupport() :false
,E/UEI.SmartControl( 6606): QS start get config
,I/LockScreenSettings( 6626): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/UEI.SmartControl( 6606): Loading JNI Libs...
D/UEI.SmartControl( 6606):  configuring local db...
D/LockScreenSettings( 6626): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6626): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6626): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6626): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6626): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  916): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6643 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  916): Killing 6274:com.google.android.gms:car/u0a6 (adj 15): empty #11
W/libprocessgroup(  916): failed to open /acct/uid_10006/pid_6274/cgroup.procs: No such file or directory
,W/ResourcesManager( 6643): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 6606):  ---- Has DB8: true
D/UEI.SmartControl( 6606): QS start statue = true Error code = 0
D/UEI.SmartControl( 6606): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6606): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 6606): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6606): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6606): IrrcClient ++ 
D/irrcClient( 6606): getIrrcService ++ 
,D/irrcClient( 6606): getIrrcService -- 
D/irrcClient( 6606): IrrcClient -- 
W/irrc_jni( 6606): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6606): Services init done
I/UEI.SmartControl( 6606): Device manager: loading config....
D/UEI.SmartControl( 6606): QS Service init finished
,D/UEI.SmartControl( 6606): QS Service version name: 0.1.73
D/UEI.SmartControl( 6606): QS Service version code: 1073
D/UEI.SmartControl( 6606): Service requested: Control
D/UEI.SmartControl( 6606): Config is loaded...
D/UEI.SmartControl( 6606):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6606): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6606): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6606): Service.onUnbind: IControl
D/UEI.SmartControl( 6606): Service.onDestroy
,D/UEI.SmartControl( 6606): Shutdown IRRCPlayer... 
W/irrc_jni( 6606): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6606): ~IrrcClient ++ 
D/irrcClient( 6606): ~IrrcClient -- 
W/irrc_jni( 6606): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6606): Blaster closed
D/UEI.SmartControl( 6606): Blaster closed
D/UEI.SmartControl( 6606): Shut down QS...
D/UEI.SmartControl( 6606): Stopped file observer...
,I/UEI.SmartControl( 6606): QS lib stop result = true
D/UEI.SmartControl( 6606): QS shutdown complete
D/UEI.SmartControl( 6606): QS Service created
E/UEI.SmartControl( 6606): QS start get config
,D/UEI.SmartControl( 6606):  configuring local db...
,I/UpdateIcingCorporaServi( 1945): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 4344): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4344): Null package name or gms related package.  Ignoreing.
,I/Icing   ( 4344): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 1945): UpdateCorporaTask done [took 51 ms] updated apps [took 51 ms] 
,D/UEI.SmartControl( 6606):  ---- Has DB8: true
,D/UEI.SmartControl( 6606): QS start statue = true Error code = 0
D/UEI.SmartControl( 6606): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6606): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6606): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6606): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6606): IrrcClient ++ 
D/irrcClient( 6606): getIrrcService ++ 
D/irrcClient( 6606): getIrrcService -- 
D/irrcClient( 6606): IrrcClient -- 
W/irrc_jni( 6606): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6606): Services init done
I/UEI.SmartControl( 6606): Device manager: loading config....
D/UEI.SmartControl( 6606): QS Service init finished
D/UEI.SmartControl( 6606): QS Service version name: 0.1.73
D/UEI.SmartControl( 6606): QS Service version code: 1073
D/UEI.SmartControl( 6606): Service requested: Control
,D/UEI.SmartControl( 6606): Config is loaded...
D/UEI.SmartControl( 6606): Request IControl service: devices are loaded...
,I/ActivityManager(  916): Killing 6461:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,D/UEI.SmartControl( 6606):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6606): Notify AllClients services are ready: 0
,W/libprocessgroup(  916): failed to open /acct/uid_10038/pid_6461/cgroup.procs: No such file or directory
E/ActivityThread( 6606): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@8b4ece8 that was originally bound here
E/ActivityThread( 6606): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@8b4ece8 that was originally bound here
E/ActivityThread( 6606): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6606): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6606): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6606): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6606): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6606): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6606): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6606): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6606): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6606): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6606): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6606): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6606): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6606): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6606): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6606): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6606): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6606): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6606): Internal service binding...
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/Icing   ( 4344): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4344): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  916): Killing 2715:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  279): 2715 died, releasing its sessions
V/AudioFlinger(  279):  pid 1749 @ 0
V/AudioFlinger(  279):  pid 3158 @ 1
,V/AudioFlinger(  279):  pid 3158 @ 2
W/libprocessgroup(  916): failed to open /acct/uid_10028/pid_2715/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ActivityManager(  916): Killing 6392:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  916): failed to open /acct/uid_10006/pid_6392/cgroup.procs: No such file or directory
,D/charger_monitor(  489): init target 500000
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  916): battery changed pluggedType: 2
E/UEI.SmartControl( 6606): file observer is disposed!
,D/UEI.SmartControl( 6606): Internal timer expired: 2
,D/UEI.SmartControl( 6606): Service.onUnbind: IControl
D/UEI.SmartControl( 6606): Service.onDestroy
W/System.err( 6606): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@39504a3d
W/System.err( 6606): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 6606): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 6606): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 6606): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 6606): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 6606): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 6606): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 6606): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 6606): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6606): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6606): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6606): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6606): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6606): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6606): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6606): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@39504a3d
D/UEI.SmartControl( 6606): Shutdown IRRCPlayer... 
W/irrc_jni( 6606): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6606): ~IrrcClient ++ 
D/irrcClient( 6606): ~IrrcClient -- 
W/irrc_jni( 6606): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6606): Blaster closed
D/UEI.SmartControl( 6606): Blaster closed
D/UEI.SmartControl( 6606): Shut down QS...
I/UEI.SmartControl( 6606): QS lib stop result = true
D/UEI.SmartControl( 6606): QS shutdown complete
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 132600742599; DSPS: 4443496; Offset : -3015357165
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/AlarmManager(  916): ELAPSED_WAKEUP set : Alarm{21c80351 type 2 when 139088 com.google.android.gms} when 139088
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1730): Vacuum at: now=1457130221045 tag=VacuumService
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  916): ALS enabled for SRE
D/PowerManagerServiceEx(  916): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (27206 ms ago)
,D/qdlights(  916): set_light_backlight: 253
,D/qdlights(  916): set_light_backlight: 250
,D/qdlights(  916): set_light_backlight: 247
,D/qdlights(  916): set_light_backlight: 243
,D/qdlights(  916): set_light_backlight: 240
,D/qdlights(  916): set_light_backlight: 237
,D/qdlights(  916): set_light_backlight: 233
,D/qdlights(  916): set_light_backlight: 230
,D/qdlights(  916): set_light_backlight: 227
,D/qdlights(  916): set_light_backlight: 223
,D/qdlights(  916): set_light_backlight: 220
,D/qdlights(  916): set_light_backlight: 217
,D/qdlights(  916): set_light_backlight: 213
,D/qdlights(  916): set_light_backlight: 210
,D/qdlights(  916): set_light_backlight: 207
,D/qdlights(  916): set_light_backlight: 203
,D/qdlights(  916): set_light_backlight: 200
,D/qdlights(  916): set_light_backlight: 197
,D/qdlights(  916): set_light_backlight: 193
,D/qdlights(  916): set_light_backlight: 190
,D/qdlights(  916): set_light_backlight: 187
,D/qdlights(  916): set_light_backlight: 183
,D/qdlights(  916): set_light_backlight: 180
,D/qdlights(  916): set_light_backlight: 177
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/qdlights(  916): set_light_backlight: 173
,D/qdlights(  916): set_light_backlight: 170
,D/qdlights(  916): set_light_backlight: 167
,D/qdlights(  916): set_light_backlight: 163
,D/qdlights(  916): set_light_backlight: 160
,D/qdlights(  916): set_light_backlight: 157
,D/qdlights(  916): set_light_backlight: 153
,D/qdlights(  916): set_light_backlight: 150
,D/qdlights(  916): set_light_backlight: 147
,D/qdlights(  916): set_light_backlight: 143
,D/qdlights(  916): set_light_backlight: 140
,D/qdlights(  916): set_light_backlight: 137
,D/qdlights(  916): set_light_backlight: 133
,D/qdlights(  916): set_light_backlight: 130
,D/qdlights(  916): set_light_backlight: 127
,D/qdlights(  916): set_light_backlight: 123
,D/qdlights(  916): set_light_backlight: 120
,D/qdlights(  916): set_light_backlight: 117
,D/qdlights(  916): set_light_backlight: 113
,D/qdlights(  916): set_light_backlight: 110
,D/qdlights(  916): set_light_backlight: 107
,D/qdlights(  916): set_light_backlight: 103
,D/qdlights(  916): set_light_backlight: 100
,D/qdlights(  916): set_light_backlight: 97
,D/qdlights(  916): set_light_backlight: 93
,D/qdlights(  916): set_light_backlight: 90
,D/qdlights(  916): set_light_backlight: 87
,D/qdlights(  916): set_light_backlight: 83
,D/qdlights(  916): set_light_backlight: 80
,D/qdlights(  916): set_light_backlight: 77
,D/qdlights(  916): set_light_backlight: 73
,D/qdlights(  916): set_light_backlight: 70
,D/qdlights(  916): set_light_backlight: 67
,D/qdlights(  916): set_light_backlight: 63
,D/qdlights(  916): set_light_backlight: 60
,D/qdlights(  916): set_light_backlight: 57
,D/qdlights(  916): set_light_backlight: 53
,D/qdlights(  916): set_light_backlight: 50
,D/qdlights(  916): set_light_backlight: 47
,D/qdlights(  916): set_light_backlight: 43
,D/qdlights(  916): set_light_backlight: 40
,D/qdlights(  916): set_light_backlight: 37
,D/qdlights(  916): set_light_backlight: 33
,D/qdlights(  916): set_light_backlight: 30
,D/qdlights(  916): set_light_backlight: 27
,D/qdlights(  916): set_light_backlight: 23
,D/qdlights(  916): set_light_backlight: 20
,D/qdlights(  916): set_light_backlight: 17
,D/qdlights(  916): set_light_backlight: 13
,D/qdlights(  916): set_light_backlight: 10
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 152601473156; DSPS: 5098881; Offset : -3015389989
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/PowerManagerService(  916): ALS enabled for SRE
D/PowerManagerServiceEx(  916): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (34203 ms ago)
,I/PowerManagerService(  916): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  916): ALS enabled for SRE
D/PowerManagerServiceEx(  916): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (34212 ms ago)
W/ContextImpl(  916): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  916): Sleeping (uid 1000)...
D/LPWGController(  916): [updateScreenState] screen on = false
,D/LPWGController(  916): disable proximity sensor
D/LPWGController(  916): enable proximity sensor
I/SensorManager(  916): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@1ace978e] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  916): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  916): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  916): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  916): activate: handle is 48, enable
V/sensors_hal_Ctx(  916): activate sensors is 1400000000000
D/sensors_hal_Thresh(  916): enable: handle=48
I/sensors_hal_SAM(  916): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  916): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  916): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  916): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  916): enable: Received response: 0
D/PowerManagerServiceEx(  916): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (34248 ms ago)
I/Adreno-EGL(  916): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  916): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  916): Build Date: 03/02/15 Mon
I/Adreno-EGL(  916): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  916): Remote Branch: 
I/Adreno-EGL(  916): Local Patches: 
I/Adreno-EGL(  916): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (195 us)
,I/Sensors (  411): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  916): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  916): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  916): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  916): processInd: handle 48, count=1
,V/sensors_hal_Thresh(  916): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  916): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  916): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  916): poll: count: 256
I/sensors_hal_Ctx(  916): poll: released wakelock sensor_ind
D/sensors_hal_Util(  916): waitForResponse: timeout=0
D/LPWGController(  916): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  916): current mode = 1  value = 1 1
I/LPWGController(  916): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  916): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  916): set_light_backlight: 0
,I/SensorManager(  916): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  916): activate: handle is 46, disable
V/sensors_hal_Ctx(  916): activate sensors is 1000000000000
D/sensors_hal_LP2(  916): enable: handle=46
D/sensors_hal_LP2(  916): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  916): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  916): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  916): Display changed displayId=0
,V/sensors_hal_SAM(  916): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  916): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
D/DSDPConnection( 1749): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
,I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  916): Excessive delay in setPowerMode(): 244ms
I/QCOM PowerHAL(  916): Got set_interactive hint
,D/KeyguardViewMediator( 1370): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1331): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1370): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1331): notifyScreenOffLocked
D/SmartCoverViewMediator( 1331): handleNotifyScreenOFF
,D/KeyguardViewMediator( 1370): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1370): handleNotifyScreenOff
D/JX-Cordova( 4861): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4861): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4861): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d06b763 added. We now have 3 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4861): load: Already loaded
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4861): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@214e6f60 added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4861): addListener: New listener added - the number of listeners is now 1
,D/BluetoothAdapterService(146074856)( 2055): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a0a6f7e
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4861): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
D/ScreenTurnOffBySensor( 1370): unregisterProximitySensor
,D/StatusBarWindowView( 1370): onScreenTurnedOff why = 3
,D/WifiServerServiceExt(  916): sendKtScanInterval  mRtspPlay : false
V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=on, calling pid 916
D/audio_hw_primary(  279): adev_set_parameters: enter: screen_state=on
V/voice   (  279): voice_set_parameters: enter: screen_state=on
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1370): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/System.err( 4861): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
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
W/System.err( 4861): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4861): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4861): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4861): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4861): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4861): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4861): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
,W/System.err( 4861): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4861): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4861): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4861): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4861): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4861): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/WifiServerServiceExt(  916): set CMD_KT_SCAN_INTERVAL
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
,D/GpsLocationProvider(  916): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:true
I/LEDService( 1802): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1802): stopPatternFlashing()
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): getCurrentHighestLGLedRecord : size = 1
,D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): updateLightsLocked : turn off led
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1802): RESTART MSG
D/SplitWindow(  916): check instance of lgWin Window{12b79745 u0 SearchPanel}
,D/LNfcService( 1785): action : android.intent.action.SCREEN_ON
I/Cliptray Service( 1802): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1802): lockStatus = 0
D/NfcServiceNXP( 1785): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1785): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1785): isRequireNfcCRouting() return true
D/LNfcService( 1785): isHCERoutingtoHost() return : true
D/NfcService( 1785): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
,D/NfcService( 1785): newParams.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): screenState= 3
D/NfcService( 1785): Discovery configuration equal, not updating.
D/InputDispatcher(  916): Window went away: Window{3300e98e u0 SearchPanel}
I/[SystemUI]Clock( 1370): onReceive = android.intent.action.SCREEN_ON
I/Sensors (  411): sns_pwr.c(301):releasing wakelock
,I/LgeClockWidgetControlView( 1370): time changed, timezoneChanged : false
,D/Ulp_jni (  916): JNI:system_update. Event-0
,V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
D/WeatherService( 2698): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 23:23:57
,D/WeatherService( 2698): 2 : ACTION screen on
D/WeatherService( 2698): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2698): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2698): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 23:23:57
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  916): ACTION_SCREEN_ON
D/AppCleanupService( 4180): android.intent.action.SCREEN_ON
,V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=off, calling pid 916
,D/audio_hw_primary(  279): adev_set_parameters: enter: screen_state=off
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
D/WifiController(  916): CMD_SCREEN_OFF 
D/WifiController(  916): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  916): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:false
,I/LEDService( 1802): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1802): stopPatternFlashing()
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
I/LEDService( 1802): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1802): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1802): clear
I/LEDService( 1802): updateLightsLocked : turn on led
E/LEDService( 1802): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1802): Can't handle this request of patternId:0
D/LEDHandler( 1802): RESTART MSG
D/LNfcService( 1785): action : android.intent.action.SCREEN_OFF
I/Cliptray Service( 1802): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/NfcServiceNXP( 1785): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1875): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2698): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 23:23:57
D/WeatherService( 2698): 2 : ACTION screen off
,D/WeatherService( 2698): 2 : TimeTick Receiver Unregister
D/WeatherService( 2698): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 23:23:57
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  916): ACTION_SCREEN_OFF
D/AppCleanupService( 4180): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4180): AppUsageStatsSaveTask
,E/NxpNfcJni( 1785): getReconnectState = 0x0
,D/LCardEmulationManager( 1785): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1785): getDefaultRoute
D/LNfcService( 1785): isRequireNfcCRouting() return true
D/LNfcService( 1785): isHCERoutingtoHost() return : true
D/NfcService( 1785): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): newParams.techmask= mTechMask: 0
D/NfcService( 1785): mEnableLPD: true
D/NfcService( 1785): mEnableReader: false
D/NfcService( 1785): mEnableHostRouting: true
D/NfcService( 1785): screenState= 1
E/NxpNfcJni( 1785): getReconnectState = 0x0
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  916): acquireWakeLockInternal: lock=340021543, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=916
,V/AlarmManager(  916): ELAPSED_WAKEUP set : Alarm{2ca09e9a type 2 when 160142 com.android.systemui} when 160142
D/KeyguardViewMediator( 1370): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1749): getCallState : 0
D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
,D/KeyguardUpdateMonitor( 1370): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1370): doKeyguard: not showing because lockscreen is off
D/PowerManagerServiceEx(  916): releaseWakeLockInternal: lock=340021543 [*alarm*], flags=0x0
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 172603764812; DSPS: 5754316; Offset : -3015387047
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  489): init target 500000
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1730): disconnect managed GoogleApiClient
,V/AlarmManager(  916): ELAPSED_WAKEUP set : Alarm{35d2a3cb type 2 when 186175 com.google.android.gms} when 186175
,I/PhenotypeConfigurator( 1730): Scheduling Phenotype for one-off execution 1909 seconds from now (1457130268287)
,I/PhenotypeFlagCommitter( 1730): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1730): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  916): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 50406(3MB) AllocSpace objects, 16(256KB) LOS objects, 39% free, 13MB/23MB, paused 8.109ms total 130.826ms
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/charger_monitor(  489): init target 500000
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
D/LocationManagerService(  916): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/LocationManagerService(  916): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  916): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  916): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  916): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  916): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  916): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/AlarmManager(  916): ELAPSED_WAKEUP set : Alarm{5a26ad8 type 2 when 190554 android} when 190554
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 192606047595; DSPS: 6409750; Offset : -3015362643
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 212608447727; DSPS: 7065189; Offset : -3015375406
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 232610496335; DSPS: 7720617; Offset : -3015399570
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  489): init target 500000
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 252612738686; DSPS: 8376050; Offset : -3015387398
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 272615202134; DSPS: 9031488; Offset : -3015302291
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
,I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 292617319620; DSPS: 9686924; Offset : -3015504114
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  489): init target 500000
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 307618851505; DSPS: 10178490; Offset : -3015375986
,D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 327621138257; DSPS: 10833925; Offset : -3015379875
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/LocationManagerService(  916): remove 2923d45b
D/LocationManagerService(  916): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  916): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  916): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  916): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  916): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 347623492230; DSPS: 11489361; Offset : -3015343415
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  916): acquireWakeLockInternal: lock=340021543, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=916
,D/PowerManagerServiceEx(  916): releaseWakeLockInternal: lock=340021543 [*alarm*], flags=0x0
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 367625853411; DSPS: 12144798; Offset : -3015332193
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
,D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  916): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 387628169670; DSPS: 12800236; Offset : -3015396225
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 407630547570; DSPS: 13455674; Offset : -3015398645
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 427632845655; DSPS: 14111109; Offset : -3015389665
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 447635227102; DSPS: 14766553; Offset : -3015572032
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 462646874437; DSPS: 15258446; Offset : -3015307417
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 485151578934; DSPS: 15995882; Offset : -3015363583
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 500153862179; DSPS: 16487477; Offset : -3015369156
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 517657287173; DSPS: 17061029; Offset : -3015362340
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 537659586892; DSPS: 17716465; Offset : -3015381592
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 557662301586; DSPS: 18371912; Offset : -3015322136
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 577664558694; DSPS: 19027347; Offset : -3015353845
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 597666869373; DSPS: 19682784; Offset : -3015393021
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 617669115407; DSPS: 20338216; Offset : -3015344227
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 637671805694; DSPS: 20993666; Offset : -3015400547
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 657674094852; DSPS: 21649099; Offset : -3015339173
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 677676347427; DSPS: 22304534; Offset : -3015375442
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 697678536428; DSPS: 22959957; Offset : -3015109050
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 711749670875; DSPS: 23421049; Offset : -3015385473
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 726751958046; DSPS: 23912643; Offset : -3015356786
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 746754321466; DSPS: 24568080; Offset : -3015343297
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 761756021841; DSPS: 25059658; Offset : -3015412915
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 775828059772; DSPS: 25520769; Offset : -3015365900
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 789900483068; DSPS: 25981896; Offset : -3015421616
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 803655681337; DSPS: 26432627; Offset : -3015442166
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 826160490473; DSPS: 27170063; Offset : -3015393746
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 846162571266; DSPS: 27825490; Offset : -3015357631
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 267, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 267
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 267
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 866164694000; DSPS: 28480923; Offset : -3015462680
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 886166853215; DSPS: 29136350; Offset : -3015348040
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  916): acquireWakeLockInternal: lock=340021543, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=916
,V/AlarmManager(  916): RTC_WAKEUP set : Alarm{246fd916 type 0 when 1457130977931 com.google.android.gms} when 1457130977931
I/ActivityManager(  916): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6933 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/EventLogService( 4344): Aggregate from 1457130192260 (log), 1457129177846 (data)
,I/DigitalAppWidgetProvider( 6933): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6933): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@119cb6ce
I/ActivityManager(  916): Killing 6541:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/PowerManagerServiceEx(  916): releaseWakeLockInternal: lock=340021543 [*alarm*], flags=0x0
,W/libprocessgroup(  916): failed to open /acct/uid_10011/pid_6541/cgroup.procs: No such file or directory
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 901168953804; DSPS: 29627938; Offset : -3015322724
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 266, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 918672520562; DSPS: 30201504; Offset : -3015600972
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 934928492475; DSPS: 30734171; Offset : -3015337956
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  916): acquireWakeLockInternal: lock=340021543, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=916
,V/AlarmManager(  916): ELAPSED_WAKEUP set : Alarm{2a358133 type 2 when 948399 com.android.bluetooth} when 948399
D/PowerManagerServiceEx(  916): releaseWakeLockInternal: lock=340021543 [*alarm*], flags=0x0
,W/bt-smp  ( 2055): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2055): Plain text(LSB ~ MSB) = b8 c2 5c 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 2055): Encrypted text(LSB ~ MSB) = 2d 65 bd 7b ff 50 0b 4d 52 1c bd 4a e0 26 5d e6 
W/bt-btm  ( 2055): Stopping oneshot timer
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 954931049833; DSPS: 31389616; Offset : -3015374591
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 265
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 265, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 974933513651; DSPS: 32045056; Offset : -3015352155
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 994935881373; DSPS: 32700492; Offset : -3015301736
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 1014938315411; DSPS: 33355935; Offset : -3015402688
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 1034940521729; DSPS: 34011366; Offset : -3015360958
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 1054942817177; DSPS: 34666802; Offset : -3015386980
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 1069945003832; DSPS: 35158392; Offset : -3015336609
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 1087448501569; DSPS: 35731948; Offset : -3015378859
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 1102451147486; DSPS: 36223554; Offset : -3015355604
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 1119954711662; DSPS: 36797111; Offset : -3015363860
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 1139956965910; DSPS: 37452545; Offset : -3015367860
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 264
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 264
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 264, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 1159959250850; DSPS: 38107980; Offset : -3015371817
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 1179961523730; DSPS: 38763414; Offset : -3015357055
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 1199963742334; DSPS: 39418844; Offset : -3015274812
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
,D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 263, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 263
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 263
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 1214965361073; DSPS: 39910420; Offset : -3015365084
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/UsageStatsService(  916): User[0] Flushing usage stats to disk
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 1229970643709; DSPS: 40402114; Offset : -3015390215
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1370): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1370): called onTimeUpdated()
I/[SystemUI]Clock( 1370): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
I/[SystemUI]DateView( 1370): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1370): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 1249972934828; DSPS: 41057549; Offset : -3015390179
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 1269975210839; DSPS: 41712966; Offset : -3014853696
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1370): onReceive = com.lge.android.intent.action.BATTERYEX
,D/charger_monitor(  489): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1802): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1370): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1370): On Skip Timer : true
D/HeadsetStateMachine( 2055): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1370): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 263
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1802): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1802): Battery Level Remaining: 100%
D/LEDHandler( 1802): Battery Temp: 263, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1370): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1370): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 263
I/[SystemUI]BatterySaverHandler( 1370): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  916): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  916): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  916): battery changed pluggedType: 2
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  916): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  916): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  916): tsOffsetIs: Apps: 1286230778845; DSPS: 42245644; Offset : -3015326062
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,TIME-OUT KILL (timeout was 1200000ms)
```
