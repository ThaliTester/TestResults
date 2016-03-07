#### Test 6012434797f7ca7_thali02_LGE-LG-D722 Logs


```
--------- beginning of system
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
--------- beginning of main
W/ContextImpl( 4754): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4754): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4754): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 4754): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4754): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 4754): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 4754): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/AndroidRuntime( 4789): 
D/AndroidRuntime( 4789): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/System  ( 4754): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@395100c6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4754): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4754): GMSCore installation verified
D/AndroidRuntime( 4789): CheckJNI is OFF
I/ConfigStore( 4754): Config Database version: 1
I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
I/ActivityManager(  945): Waited long enough for: ServiceRecord{8c1435d u0 com.android.calendar/.alerts.InitAlarmsService}
I/MediaRouter( 4754): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/MusicLeanback( 4754): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 4754): type=WIFI subType= reason=null isConnected=true
I/NetworkMonitor( 4754): type=WIFI subType= reason=null isConnected=true
D/AndroidRuntime( 4789): Calling main entry com.android.commands.am.Am
I/ActivityManager(  945): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=4813 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/ActivityManager(  945): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  945): setTaskToReturnTo : TaskRecord{21a7ddb4 #224 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  945): setTaskToReturnTo : TaskRecord{21a7ddb4 #224 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  945): AppWindowTokenEx init.. 
D/ContextHelper(  945): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
D/InputDispatcher(  945): Focus left window: Window{186df462 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 4789): Shutting down VM
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
I/PhoneWindow(  945): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx(  945): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  945): [setNavigationBarColor2] color=0x fff5f5f5
D/SplitWindow(  945): check instance of lgWin Window{e452f4c u0 Starting com.test.thalitest}
I/ActivityManager(  945): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4830 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/WindowStateAnimator(  945): Starting window displayed
D/WindowManager(  945): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/SystemUI[Framework](  945): PhoneWindowManager.updateSystemUiVisibilityLw() :win == null
W/PhoneWindowManagerEx(  945): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  945): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  945): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  945): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@29eb66e9,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  945): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1374): notify navigation bar color(0xfff5f5f5)
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
W/ResourcesManager( 4813): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4813): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4813): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/GHttpClientFactory( 4754): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 4754): Using platform SSLCertificateSocketFactory
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
,W/ActivityThread( 1877): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1877): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1877): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3407)
W/ActivityThread( 1877): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3496)
W/ActivityThread( 1877): 	at android.app.ActivityThread.access$1100(ActivityThread.java:155)
W/ActivityThread( 1877): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1352)
W/ActivityThread( 1877): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 1877): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 1877): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/ActivityThread( 1877): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 1877): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 1877): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/ActivityThread( 1877): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/HotwordDetector( 1939): Closing mic
,I/MicrophoneInputStream( 1939): mic_close com.google.android.apps.gsa.speech.audio.u@2c9e6c62
V/AudioRecord( 1939): stop()
D/AudioRecord( 1939): AudioRecord->stop()
,V/AudioFlinger(  284): RecordHandle::stop()
V/AudioFlinger(  284): RecordThread::stop
I/ActivityManager(  945): Activity reported stop, but no longer stopping: ActivityRecord{164c5813 u0 com.lge.launcher2/.Launcher t223}
,V/AudioFlinger(  284): Record stopped OK
V/AudioPolicyManager(  284): stopInput() input 17
V/AudioPolicyService(  284): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  284): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  284): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  284): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  284): ThreadBase::setParameters() routing=0
V/AudioFlinger(  284): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  284): processConfigEvents_l() remaining events 1
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb397c000
D/audio_hw_primary(  284): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
,I/ActivityManager(  945): Killing 4546:com.lge.qmemoplus/1000 (adj 15): empty #11
V/audio_hw_primary(  284): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  284): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  284): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  284): disable_audio_route: reset and update mixer path: audio-record
,V/audio_hw_primary(  284): disable_audio_route: exit
E/audio_hw_primary(  284): disable_snd_device: enter 144
D/hardware_info(  284): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  284): disable_snd_device: snd_device(144: lg-vr-handset-mic)
W/libprocessgroup(  945): failed to open /acct/uid_1000/pid_4546/cgroup.procs: No such file or directory
V/audio_hw_primary(  284): stop_input_stream: exit: status(0)
V/audio_hw_primary(  284): in_standby: exit:  status(0)
V/AudioFlinger(  284): RecordThread: loop stopping
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
V/AudioPolicyManager(  284): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  284): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  284): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  284): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
V/AudioPolicyService(  284): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  284): inserting command: 3 at index 0, num commands 0
,V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  284): setParameters(): io 17, keyvalue hotword_active=0, calling pid 284
V/AudioFlinger(  284): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  284): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  284): RecordThread: loop starting
V/AudioFlinger(  284): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  284): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  284): in_set_parameters: exit: status(0)
V/AudioFlinger(  284): processConfigEvents_l() DONE thread 0xb397c000
V/AudioFlinger(  284): RecordThread: loop stopping
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
,I/NotificationManager( 4754): com.google.android.music: cancel(1061) by com.google.android.music
D/ContextHelper( 4830): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,V/AudioRecord( 1939): stop()
,V/AudioRecord( 1939): stop()
V/AudioRecord( 1939): stop()
V/AudioFlinger(  284): RecordHandle::stop()
V/AudioFlinger(  284): RecordThread::stop
V/AudioPolicyManager(  284): releaseInput() 17
V/AudioPolicyManager(  284): closeInput(17)
V/AudioFlinger(  284): releasing 16 from 1939 for -1
V/AudioFlinger(  284):  decremented refcount to 0
V/AudioFlinger(  284): purging stale effects
V/AudioFlinger(  284): closeInput() 17
V/AudioSystem(  284): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  945): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1374): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  284): ThreadBase::exit
V/AudioSystem( 1751): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2675): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1939): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3185): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  284): RecordThread: loop starting
V/AudioFlinger(  284): RecordThread 0xb397c000 exiting
V/AudioSystem( 2010): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  284): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  284): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  284): in_standby: exit:  status(0)
V/AudioPolicyService(  284): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  284): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  284): releaseInput() exit
V/AudioFlinger(  284): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  284): removeClient_l() pid 1939, calling pid 284
V/AudioPolicyService(  284): AudioCommandThread() waking up
V/AudioPolicyService(  284): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  284): AudioCommandThread() going to sleep
I/HotwordRecognitionRnr( 1939): Hotword detection finished
,I/HotwordRecognitionRnr( 1939): Stopping hotword detection.
I/WebViewFactory( 4830): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LGEmail ( 4813): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,I/LibraryLoader( 4830): Time to load native libraries: 2 ms (timestamps 9614-9616)
I/LibraryLoader( 4830): Expected native library version number "",actual native library version number ""
,D/LGEmail ( 4813): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
V/WebViewChromiumFactoryProvider( 4830): Binding Chromium to main looper Looper (main, tid 1) {4c5d88a}
,I/LibraryLoader( 4830): Expected native library version number "",actual native library version number ""
I/chromium( 4830): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4830): Initializing chromium process, singleProcess=true
,W/art     ( 4830): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4830): ApplicationContext is null in ApplicationStatus
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,W/chromium( 4830): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4830): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4830): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4830): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4830): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4830): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4830): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4830): Remote Branch: 
I/Adreno-EGL( 4830): Local Patches: 
I/Adreno-EGL( 4830): Reconstruct Branch: 
,D/eas_req ( 4813): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 4587): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4587): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4587): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/AudioPolicyService(  284): registerClient() client 0xb381bf20, uid 10316
,W/ContextImpl( 4587): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/BluetoothManagerService(  945): Message: 20
D/BluetoothManagerService(  945): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2519d662:true
,D/LGDMClient( 4587): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/HubEmail( 4813): JNI_OnLoad()
I/HubEmail( 4813): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4813): registerNatives()
I/HubEmail( 4813): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4813): registerNativeMethods()
I/HubEmail( 4813): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 4813): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
D/LGDMClient( 4587): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4587): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/BluetoothAdapterService(223189361)( 2010): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@51512cf
,I/LGDMClient( 4587): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  945): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=4883 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/Settings( 4813): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/ContextImpl( 4587): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4587): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 4587): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 4587): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 4587): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 4587): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/AppUp4:AppBoxCP( 4883): onCreate
,W/AppUp4:DB( 4883):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 4883):  setFingerPrint start
I/AppUp4:DB( 4883):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 4883):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4883):  SDK version = 0
I/AppUp4:DB( 4883):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 4883): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 4883): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4883): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4883): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 4883): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 4883): onReceive
I/AppUp4:CustModeStarterReceiver( 4883): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
,D/AppUp4:CustFacade( 4883): Context : android.app.ReceiverRestrictedContext@4c5d88a
D/AppUp4:CustFacade( 4883): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4883): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 4883): begin check event
I/AppUp4:CustModeStarterReceiver( 4883): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4883): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4883): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 4883): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 4883): handleAsyncCustNotification do not startCustService
I/ActivityManager(  945): Killing 3336:com.android.defcontainer/u0a4 (adj 15): empty #11
,W/art     ( 4830): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 4830): onDetachedFromWindow called when already detached. Ignoring
,I/PhoneWindow( 4830): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 4830): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 4830): [setNavigationBarColor2] color=0x fff5f5f5
D/SystemWebViewEngine( 4830): CordovaWebView is running on device made by: LGE
,W/libprocessgroup(  945): failed to open /acct/uid_10004/pid_3336/cgroup.procs: No such file or directory
W/art     ( 4830): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4830): Attempt to remove local handle scope entry from IRT, ignoring
I/LgeMiscReceiver( 3185): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3185): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3185): networkInfo.isConnected() = true
D/PhoneState( 3185): setPdpRejectCasuse : false
I/ActivityManager(  945): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=4915 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/Activity( 4830): Activity.onPostResume() called 
,D/OpenGLRenderer( 4830): Render dirty regions requested: true
I/OpenGLRenderer( 4830): Initialized EGL, version 1.4
D/OpenGLRenderer( 4830): Enabling debug mode 0
,D/Atlas   ( 4830): Validating map...
D/SplitWindow(  945): check instance of lgWin Window{218aede0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 4830): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  945): Killing 4730:com.lge.bnr/1000 (adj 15): empty #11
W/libprocessgroup(  945): failed to open /acct/uid_1000/pid_4730/cgroup.procs: No such file or directory
,D/InputDispatcher(  945): Focus entered window: Window{218aede0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  945): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  945): Displayed com.test.thalitest/.MainActivity: +1s383ms
I/Timeline(  945): Timeline: Activity_windows_visible id: ActivityRecord{273e6ddd u0 com.test.thalitest/.MainActivity t224} time:70525
,I/Timeline( 4830): Timeline: Activity_idle id: android.os.BinderProxy@2cacc2f4 time:70528
D/PhoneMonitor( 4915): Register our PhoneStateListener
W/BindingManager( 4830): Cannot call determinedVisibility() - never saw a connection for the pid: 4830
,D/MobileConnectivityChangeReceiver( 4915): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4915): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  945): Killing 4655:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  945): failed to open /acct/uid_1000/pid_4655/cgroup.procs: No such file or directory
,I/CheckinService( 4296): Checkin interval check for package: unspecified last checkin: 1457362963525 min interval config: 0 actual interval: 15968227
V/DownloadManager( 3229): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3229): DownloadService onCreate
I/DownloadManager( 3229): in removeSpuriousFiles
V/DownloadManager( 3229): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/NotificationManager( 3229): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@11e7d578 on behalf of 3229
,I/DownloadManager( 3229): in trimDatabase
V/DownloadManager( 3229): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@284cd4b6 on behalf of 3229
I/ActivityManager(  945): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4955 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3229): DownloadService onStartCommand
I/CheckinService( 4296): Checking schedule, now: 1457378931812 next: 1457362993437
I/CheckinService( 4296): active receiver: enabled
D/PhoneMonitor( 4915): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
V/TelephonyAutoProfiling( 4915): [loadFeatureFromXml] *** start feature loading from xml
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/TelephonyAutoProfiling( 4915): [parse] Load xml
,V/DownloadManager( 3229): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@1a80d124 on behalf of 3229
V/TelephonyAutoProfiling( 4915): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 4915): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 4915): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/CheckinService( 4296): Preparing to send checkin request
,I/EventLogService( 4296): Accumulating logs since 1457377376373
D/JsMessageQueue( 4830): Set native->JS mode to OnlineEventsBridgeMode
,V/DownloadManager( 3229): DownloadService onDestroy
,D/DrmBroadcastReceiver( 4955): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 4955): 1  network is available. Sync DRM Time with NTP
V/DrmService( 4955): Service onCreate
D/DrmService( 4955): Received new request = 2
,D/WeatherAncestor( 2656): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:28:51
I/DrmSntpClient( 4955): Start Sync process
D/DrmSntpClient( 4955): Server : 0
D/UpdateThreadPoolManager( 2656): 2 : This is isUpdating : false
D/libc-netbsd( 4955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4955): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4955): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/WeatherAncestor( 2656): connectivity changed - connection : true
E/BandwidthController(  278): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  278): App 10051 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/Weather_cast( 2656): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2656): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 20:28:51
D/WeatherService( 2656): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,D/UEI.SmartControl( 4630): Internal timer expired: 1
I/ActivityManager(  945): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4977 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  945): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2656): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2656): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2656): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 4955): propertyValue:false
,I/CheckinRequestBuilder( 4296): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4296): Failed to find provider info for com.google.android.wearable.settings
W/ResourcesManager( 4977): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/LGDrmClient( 4955): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  292): eDRM_SetDRMTime +++
I/LGDRM   (  292): [DRM] SET TIME : YR=2016, MON=3, DAY=7
I/LGDRM   (  292): [DRM] SET TIME : HR=19, MIN=28, SEC=52
,V/ILGDrmService(  292): eDRM_SetDRMTime ---
,I/DrmSntpClient( 4955): Synched
D/DrmService( 4955): Completed !! request = 2
D/DrmService( 4955): Request count = 0
V/DrmService( 4955): Service onDestroy
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  945): Process com.google.android.music:main (pid 4754) has died
,D/jxcore_app_log( 4830): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622897024
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4830): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4830):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4830):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4830):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4830):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4830): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@284cd4b6 added. We now have 1 listener(s)
,D/BluetoothManagerService(  945): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4830): setBluetoothMacAddress: F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4830): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4830): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4830): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4830):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4830):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4830):     - Bluetooth MAC address: F8:95:C7:87:85:54
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4830):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4830):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4830):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4830):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4830):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4830):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4830): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11498642 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4830): addListener: New listener added - the number of listeners is now 1
,D/BluetoothAdapterService(223189361)( 2010): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@51512cf
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4830): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4830): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4830): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4830): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4830): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4830): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4830): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4830): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4830): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4830): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4830): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4830): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4830): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4830): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4830): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Babel_SMS( 4977): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4977): MmsConfig.loadMmsSettings
I/Babel_SMS( 4977): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4977): MmsConfig.loadFromDatabase
D/JX-Cordova( 4830): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4830): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4830): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c427653 added. We now have 2 listener(s)
D/BluetoothManagerService(  945): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4830): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4830): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4830): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4830): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f8bdb90 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4830): addListener: New listener added - the number of listeners is now 1
D/BluetoothAdapterService(223189361)( 2010): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@51512cf
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4830): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4830): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4830): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4830): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4830): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4830): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4830): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4830): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4830): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4830): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4830): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4830): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4830): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4830): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4830): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,E/Babel_SMS( 4977): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4977): MmsConfig.loadFromResources
E/Babel_SMS( 4977): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4977): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 4977): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4977): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4977): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 4977): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4977): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4977): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4977): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4977): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4977): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4977): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4977): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4977): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4977): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4977): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4977): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4977): found sensor: Motion Accel, handle=46
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
W/Settings( 4977): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4977): startup - clean
I/art     ( 4977): CheckpointMarkThreadRoots callback created = 0xb042d920
,D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
I/Babel   ( 4977): deleted: false for 0
I/ActivityManager(  945): Waited long enough for: ServiceRecord{3a8ac194 u0 com.lge.springcleaning/.service.AppCleanupService}
,I/art     ( 4977): CheckpointMarkThreadRoots callback created = 0xb042d900
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  945): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5014 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/AudioCapabilities( 4977): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 4977): Unsupported mime audio/adpcm
W/AudioCapabilities( 4977): Unsupported mime audio/g726
W/AudioCapabilities( 4977): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4977): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4977): Unsupported mime video/mjpg
W/VideoCapabilities( 4977): Unsupported mime video/theora
,W/AudioCapabilities( 4977): Unsupported mime audio/evrc
,W/AudioCapabilities( 4977): Unsupported mime audio/qcelp
W/VideoCapabilities( 4977): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4977): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 4977): Unsupported mime audio/qcelp
,W/AudioCapabilities( 4977): Unsupported mime audio/evrc
W/VideoCapabilities( 4977): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 4977): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4977): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4977): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4977): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4977): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 4977): onServiceConnected
W/Babel   ( 4977): Attempted to change video mute state without an active call.
,I/NotificationManager( 4977): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 4977): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4977): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4977): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4977): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  278): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 4977): propertyValue:false
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5014): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5014): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/Babel   ( 4977): connection state changed from UNKNOWN to CONNECTED
I/NotificationManager(  945): android: cancelAsUser(2) by android
,I/GAv4    ( 5014): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5014):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5014):   adb logcat -s GAv4
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5014): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5014): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
W/GAv4    ( 5014): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5014): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/art     (  945): Explicit concurrent mark sweep GC freed 26294(1387KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.195ms total 160.318ms
W/GAv4    ( 5014): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  945): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5044 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 5044): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5044): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 5044): VM with version 2.1.0 has multidex support
I/MultiDex( 5044): install
I/MultiDex( 5044): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 5044): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5044): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5044): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f7424af: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5044): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  945): Process com.lge.qremote (pid 4609) has died
D/UEI.SmartControl( 4630): Service.onUnbind: IControl
D/UEI.SmartControl( 4630): Service.onDestroy
,I/NotificationManager( 5044): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5044): com.google.android.gms: cancel(39789) by com.google.android.gms
D/UEI.SmartControl( 4630): Shutdown IRRCPlayer... 
W/irrc_jni( 4630): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 4630): ~IrrcClient ++ 
D/irrcClient( 4630): ~IrrcClient -- 
W/irrc_jni( 4630): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 4630): Blaster closed
D/UEI.SmartControl( 4630): Blaster closed
D/UEI.SmartControl( 4630): Shut down QS...
D/UEI.SmartControl( 4630): Stopped file observer...
,I/UEI.SmartControl( 4630): QS lib stop result = true
D/UEI.SmartControl( 4630): QS shutdown complete
,I/WebViewFactory( 5014): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/art     ( 5044): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5044): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/LibraryLoader( 5014): Time to load native libraries: 3 ms (timestamps 2661-2664)
I/LibraryLoader( 5014): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5014): Binding Chromium to main looper Looper (main, tid 1) {2c7d979f}
,I/LibraryLoader( 5014): Expected native library version number "",actual native library version number ""
I/chromium( 5014): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5014): Initializing chromium process, singleProcess=true
,W/art     ( 5014): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5014): ApplicationContext is null in ApplicationStatus
W/chromium( 5014): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
D/NativeLibraryUtils( 5044): Install completed successfully. count=14 extracted=0
,E/libEGL  ( 5014): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5014): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5014): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5014): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5014): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5014): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5014): Remote Branch: 
I/Adreno-EGL( 5014): Local Patches: 
I/Adreno-EGL( 5014): Reconstruct Branch: 
I/ActivityManager(  945): Process com.uei.lg.quicksetsdk.lite (pid 4630) has died
,V/AudioPolicyService(  284): registerClient() client 0xb3a57140, uid 10079
W/AudioManagerAndroid( 5014): Requires BLUETOOTH permission
,I/art     ( 4031): Explicit concurrent mark sweep GC freed 2709(108KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 396us total 25.933ms
D/WVCdm   (  284): Instantiating CDM.
,I/NSApplication( 5014): Starting up...
I/WVCdm   (  284): CdmEngine::OpenSession
I/WVCdm   (  284): Level3 Library Dec 11 2014 16:13:16
D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 72885160654; DSPS: 2486961; Offset : -3024663377
,W/WVCdm   (  284): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  284): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  284): L1 library not specified. Falling Back to L3
,I/ActivityManager(  945): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5102 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 35.489ms
,I/WVCdm   (  284): CdmEngine::QueryKeyControlInfo
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.710ms
W/WVCdm   (  284): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  284): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  284): CdmEngine::GenerateKeyRequest
D/WVCdm   (  284): PrepareKeyRequest: nonce=974998760
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 21.136ms
I/GoogleURLConnFactory( 5044): Using platform SSLCertificateSocketFactory
,D/libc-netbsd( 5044): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5044): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5044): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5044): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 5044): propertyValue:false
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  945): Reconfiguring input devices.  changes=0x00000010
,D/administrator(  945): Handling package changes for user 0
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
I/art     ( 1786): CheckpointMarkThreadRoots callback created = 0xaaf1fb70
,I/art     ( 1786): CheckpointMarkThreadRoots callback created = 0xaaf54530
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  945): Process com.lge.email (pid 4813) has died
,D/libc-netbsd( 5044): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5044): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5044): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5044): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationService(  945): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  945): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  945): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  945): Process com.lge.lgdmsclient (pid 4587) has died
,W/ResourcesManager(  945): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  945): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  945): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5129 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/BackupManagerService(  945): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/BackupManagerService(  945): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  945): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1b1d66d
I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/ResourcesManager( 5129): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/LocationProviderProxy(  945): applying state to connected service
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
,I/art     ( 5044): CheckpointMarkThreadRoots callback created = 0xb042dd00
,I/art     ( 5044): CheckpointMarkThreadRoots callback created = 0xb042dcf0
,I/ActivityManager(  945): Process com.lge.appbox.client (pid 4883) has died
,I/iu.SyncManager( 4296): SYNC; picasa accounts
,D/NetworkLogImpl( 4296): Loaded NetworkSpeedPredictor
I/iu.Environment( 4296): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 4296): num queued entries: 0
,I/iu.UploadsManager( 4296): num updated entries: 0
,I/iu.SyncManager( 4296): NEXT; no task
I/ActivityManager(  945): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=5159 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
I/dex2oat ( 5157): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 5157): dex2oat took 90.890ms (threads: 4)
,I/ActivityManager(  945): Process com.google.android.setupwizard (pid 4915) has died
I/Adreno-EGL( 5044): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5044): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5044): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5044): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5044): Remote Branch: 
I/Adreno-EGL( 5044): Local Patches: 
I/Adreno-EGL( 5044): Reconstruct Branch: 
,V/AlarmManager(  945): RTC_WAKEUP set : Alarm{34a23fa1 type 0 when 1457378935506 com.google.android.googlequicksearchbox} when 1457378935506
I/DigitalAppWidgetProvider( 5159): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 2656): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 20:28:55
D/UpdateThreadPoolManager( 2656): 2 : This is isUpdating : false
D/Weather_cast( 2656): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2656): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 20:28:55
D/WeatherService( 2656): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
I/ActivityManager(  945): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5185 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
W/ActivityManager(  945): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2656): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2656): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2656): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/Adreno-EGL( 5044): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5044): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5044): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5044): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5044): Remote Branch: 
I/Adreno-EGL( 5044): Local Patches: 
I/Adreno-EGL( 5044): Reconstruct Branch: 
,W/ResourcesManager( 5185): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
I/Adreno-EGL( 5044): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5044): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5044): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5044): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5044): Remote Branch: 
I/Adreno-EGL( 5044): Local Patches: 
I/Adreno-EGL( 5044): Reconstruct Branch: 
D/BluetoothManagerService(  945): Message: 20
,D/BluetoothManagerService(  945): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@38eab723:true
D/BluetoothAdapterService(223189361)( 2010): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@51512cf
D/BluetoothAdapterService(223189361)( 2010): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@51512cf
V/SmsReceiverService( 3185): onStart: #1 mResultCode: -1 = Activity.RESULT_OK
D/MmsConfig( 3185): isNotAllowedSms: currentUser:0
,D/MmsConfig( 3185): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3185): isUserMode:false
D/SmsReceiverService( 3185): handleMessage isUserMode:false
V/SmsReceiverService( 3185): handleMessage action: com.android.mms.transaction.SEND_MESSAGE error: 0
D/SmsReceiverService( 3185): [LGE] handleSendMessage Send messages in queue
,I/[LGHome]LGNumberBadgeReceiver( 1877): [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = lge.intent.action.UNREAD_MESSAGES
D/WeatherAncestor( 2656): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 20:28:55
,D/UpdateThreadPoolManager( 2656): 2 : This is isUpdating : false
D/WeatherAncestor( 2656): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 20:28:55
D/WeatherService( 2656): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
W/ActivityManager(  945): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2656): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2656): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2656): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2656): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2656): 2 : This is isUpdating : false
D/WeatherService( 2656): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2656): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2656): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2656): 2 : Fixed theme : optimus
,V/UserPresentBroadcastReceiver( 1733): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
I/[LGHome]NumberBadge.LGBroadCastBadge( 1877): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1877): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1877): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
D/WeatherReflect( 2656): 2 : Map key string is -2
I/[LGHome]NumberBadge.LGBroadCastBadge( 1877): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
D/lim     ( 2656): 2 : time = 20:28
,I/WeatherReflect( 2656): Model Name : LG-D722
D/WeatherTheme( 2656): 2 : exactly same view!
D/WeatherTheme( 2656): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
I/ActivityManager(  945): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=5207 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  945): Process com.lge.sync (pid 4690) has died
,W/ActivityManager(  945): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2656): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2656): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2656): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/WVCdm   (  284): CdmEngine::OpenSession
,W/ResourcesManager( 5207): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5207): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5207): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5207): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5207): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/ActivityManager(  945): Process com.lge.drmservice (pid 4955) has died
I/WVCdm   (  284): CdmEngine::CloseSession
,I/IndexDatabaseHelper( 5207): Using schema version: 115
,I/IndexDatabaseHelper( 5207): Index is fine
I/WVCdm   (  284): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  284): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  284): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  284): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  284): PrepareKeyRequest: nonce=675306077
D/UsbSettingsReceiver( 5207): [AUTORUN] onReceive() : action = android.hardware.usb.action.USB_STATE
D/UsbSettingsReceiver( 5207): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5207): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5207): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 5207): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsReceiver( 5207): [AUTORUN] onReceive() : getDefaultFunction = ptp_only
D/UsbSettingsReceiver( 5207): [AUTORUN] onReceive() : USB_FUNCTION_CDROM_STORAGE = false
D/UsbSettingsReceiver( 5207): [AUTORUN] onReceive() : mDirectAutorun = true
D/UsbSettingsReceiver( 5207): [AUTORUN] onReceive() : mActivityUsbModeChange = false
D/UsbSettingsReceiver( 5207): [AUTORUN] onReceive() : mActivityFinish = false
D/UsbSettingsReceiver( 5207): [AUTORUN] onReceive() : ===== USB Configured =====
,D/UsbSettingsControl( 5207): [AUTORUN] setUsbConnected() : connected=true
D/UsbSettingsReceiver( 5207): [AUTORUN] onReceive() : checkQmicm = ptp_only,adb
D/UsbSettingsReceiver( 5207): [AUTORUN] : topPackageName=com.test.thalitest
D/UsbSettingsReceiver( 5207): [AUTORUN] : topClassName=com.test.thalitest.MainActivity
,D/UsbSettingsReceiver( 5207): [AUTORUN] Not exist com.android.LGSetupWizard
D/UsbSettingsReceiver( 5207): [AUTORUN] setUsbConnect() : mUsbSettingsRun = false
D/UsbSettingsReceiver( 5207): [AUTORUN] startUsbSettings() : deviceProvisioned=1
,I/ActivityManager(  945): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5232 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/MtpService( 3229): updating state; isCurrentUser=true, mMtpLocked=false
,I/ActivityManager(  945): Process com.google.android.talk (pid 4977) has died
,I/PCSuite ( 5232): [StartReceiver]USB CONNECTED ver UsbManger : ptp_only
I/PCSuite ( 5232): [StartReceiver]isUsbPCSuiteMode : false
,D/PCSuite ( 5232): [StartReceiver][checkEUTStatus] eutStatus = 
D/PCSuite ( 5232): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5232): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
V/LGMDMManager( 5185): Create singleton instance
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/DigitalAppWidgetProvider( 5159): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 2656): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 20:28:56
D/UpdateThreadPoolManager( 2656): 2 : This is isUpdating : false
D/Weather_cast( 2656): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2656): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 20:28:56
D/WeatherService( 2656): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
W/ActivityManager(  945): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2656): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2656): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2656): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/AlertReceiver( 3870): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
D/AlertService( 3870): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 3870): [updateWidgets] 
,D/MonthWidgetProvider( 3870): [onReceive]
D/CalendarWidgetProvider( 3870): [onReceive]
D/CalendarWidgetProvider( 3870): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 3870): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 3870): [onReceive]
D/CalendarWidgetProvider( 3870): [onReceive]
D/CalendarWidgetProvider( 3870): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 3870): [onCreate] mContext.getPackageName() = com.android.calendar
I/[SystemUI]SafeModeBroadcastReceiver( 1374): onReceive = com.lge.statusbar.bootcompleted
,D/CalendarWeatherReceiver( 3870): Get action=com.lge.calendar.action.WEATHER_SERVICE_START
,I/ActivityManager(  945): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.MediaScanReceiver: pid=5253 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/chromium( 4830): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
I/chromium( 4830): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,E/MediaScanReceiver( 5253): media scanning start or checking
,W/MainApplication( 5253): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ActivityManager(  945): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5270 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 5270): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5270): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5270): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5270): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/ResourcesManager( 5270): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5270): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5270): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5270): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5270): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@395100c6: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5270): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5270): GMSCore installation verified
I/ConfigStore( 5270): Config Database version: 1
,E/libprocessgroup(  945): failed to kill 1 processes for processgroup 5014
I/ActivityManager(  945): Process com.google.android.apps.magazines (pid 5014) has died
,I/MediaRouter( 5270): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/ToneMappingReceiver( 5159): Enter doAlarmRingToneUriMapping()
I/NetworkMonitor( 5270): type=WIFI subType= reason=null isConnected=true
,D/ToneMappingReceiver( 5159): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
,D/CommonUtil( 5159): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5159): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5159): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5159): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5159): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5159): Alarm Success count is 0
D/ToneMappingReceiver( 5159): Timer Success count is 0
,I/WVCdm   (  284): CdmEngine::CloseSession
,I/WVCdm   (  284): L3 Terminate.
I/art     (  945): Explicit concurrent mark sweep GC freed 25984(1353KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.608ms total 167.208ms
,I/MediaScannerReceiver( 3870): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///system/media
I/InitNotificationRingtoneService( 3870): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3870): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,E/MediaScanReceiver( 5253): media scanning finished
,I/com.lge.bnr.receiver.MediaScanReceiver( 5253): android.intent.action.MEDIA_SCANNER_FINISHED
I/NetworkMonitor( 5270): type=WIFI subType= reason=null isConnected=true
,I/AlertUtils( 3870): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/GHttpClientFactory( 5270): Using our fixed implementation of GMSCore's GoogleHttpClient
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/GoogleURLConnFactory( 5270): Using platform SSLCertificateSocketFactory
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3870): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,E/MediaScanReceiver( 5253): media scanning start or checking
I/NotificationManager( 5270): com.google.android.music: cancel(1061) by com.google.android.music
,D/ToneMappingReceiver( 5159): Enter doAlarmRingToneUriMapping()
,D/ToneMappingReceiver( 5159): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5159): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5159): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5159): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5159): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5159): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5159): Alarm Success count is 0
D/ToneMappingReceiver( 5159): Timer Success count is 0
I/AlertUtils( 3870): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3870): End InitializeAlertRingtoneService.onHandleIntent
,I/MediaScannerReceiver( 3870): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///storage/emulated/0
I/InitNotificationRingtoneService( 3870): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3870): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
E/MediaScanReceiver( 5253): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 5253): android.intent.action.MEDIA_SCANNER_FINISHED
,I/art     ( 5270): CheckpointMarkThreadRoots callback created = 0xb042d3f0
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/ActivityManager(  945): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5322 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     ( 3229): Explicit concurrent mark sweep GC freed 13827(938KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/10MB, paused 433us total 64.563ms
,I/art     ( 5270): CheckpointMarkThreadRoots callback created = 0xb042d3c0
,I/AlertUtils( 3870): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/CheckinRequestBuilder( 4296): Classify the device as Phone.
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
W/ResourcesManager( 5322): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3870): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
D/CalendarProvider2( 5322): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@26239c00
,I/AlertUtils( 3870): set default noti to content://media/internal/audio/media/38
,D/CalendarProvider2( 5322): [getOrCreateCalendarAlarmManager]
I/InitNotificationRingtoneService( 3870): End InitializeAlertRingtoneService.onHandleIntent
D/libc-netbsd( 4296): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4296): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4296): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4296): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
I/CalendarProvider2( 5322): Created com.android.providers.calendar.CalendarAlarmManager@406c2f5(com.android.providers.calendar.CalendarProvider2@26239c00)
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 4296): propertyValue:false
D/CalendarProviderBroadcastReceiver( 5322): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,D/CalendarProviderBroadcastReceiver( 5322): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 5322): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 5322): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
,D/CalendarProvider2( 5322): [getOrCreateCalendarAlarmManager]
I/MediaStoreImporter( 5270): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
E/MDM     ( 1733): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4296): Restart initialization of location
D/CalendarProvider2( 5322): [IntentService] Release Lock
,D/CalendarProvider2( 5322): CalendarProviderIntentService.onDestroy()
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
D/libc-netbsd( 4296): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4296): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  945): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5354 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,D/libc-netbsd( 4296): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4296): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4296): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4296): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 4296): Sending checkin request (9924 bytes)
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
I/art     ( 4296): Explicit concurrent mark sweep GC freed 19053(1576KB) AllocSpace objects, 28(448KB) LOS objects, 40% free, 12MB/20MB, paused 1.365ms total 89.071ms
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
W/IcingInternalCorpora( 4296): getNumBytesRead when not calculated.
W/ActivityManager(  945): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5354): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5354): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  945): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   ( 5354): Observing account changes for notifications
W/ActivityManager(  945): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  945): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5354): Error finding the version of the Email provider.....
E/Gmail   ( 5354): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5354): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5354): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5354): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5354): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5354): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5354): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5354): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5354): We do not support migrating this version of the Email provider.
,I/art     (  945): Explicit concurrent mark sweep GC freed 11703(627KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.047ms total 140.445ms
,I/Gmail   ( 5354): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1733): No location to return for getLastLocation()
,W/FusedLocationProvider( 1733): location=null
I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,I/CheckinResponseProcessor( 4296): From server: 0 gservices updates and 1 deletes
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/DownloadManager( 3229): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@11498642 on behalf of 4296
I/ActivityManager(  945): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5411 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/Gmail   ( 5354): notifyAccountChanged
,I/Gmail   ( 5354): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5354): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5354): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/WeatherService( 2656): 2 : TimeTick Intent has been received, Time(hour:min:sec) 20:29:0
D/WeatherService( 2656): 2 : TimeTick Intent And Screen On
I/Gmail   ( 5354): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5354): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/WeatherService( 2656): 2 : SDK version : 21
,W/ActivityManager(  945): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2656): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2656): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2656): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2656): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2656): 2 : This is isUpdating : false
D/WeatherService( 2656): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2656): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2656): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2656): 2 : Fixed theme : optimus
D/WeatherReflect( 2656): 2 : Map key string is -2
,D/lim     ( 2656): 2 : time = 20:29
I/WeatherReflect( 2656): Model Name : LG-D722
D/WeatherTheme( 2656): 2 : Different view - status_min_formatted : 28 != 29
D/WeatherTheme( 2656): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2656): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2656): strTheme: com.lge.launcher2.theme.optimus
,D/Theme   ( 2656): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2656): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
,I/[SystemUI]Clock( 1374): called onTimeUpdated()
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/Gmail   ( 5354): getAccountsCursor
,I/CertBlacklister(  945): Certificate blacklist changed, updating...
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Weather4x2_optimus( 2656): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2656): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2656): forecast size is 0
D/Theme   ( 2656): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2656): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2656): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2656): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2656): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2656): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2656): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2656): url is : null
,V/DownloadManager( 3229): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
D/Theme   ( 2656): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/CertBlacklister(  945): Certificate blacklist updated
D/WeatherAncestor( 2656): 2 : update view, appWidgetId: 2
V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@1c427653 on behalf of 4296
D/WeatherService( 2656): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 20:29:0
V/DownloadManager( 3229): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@1f8bdb90 on behalf of 4296
I/GservicesProvider( 4031): main difference update completed
,I/CheckinRequestBuilder( 4296): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4296): Failed to find provider info for com.google.android.wearable.settings
,D/PhoneMonitor( 5411): Register our PhoneStateListener
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/CheckinService( 4296): Checkin interval check for package: unspecified last checkin: 1457362963525 min interval config: 0 actual interval: 15976684
,D/PhoneMonitor( 5411): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5411): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5411): [parse] Load xml
V/TelephonyAutoProfiling( 5411): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5411): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5411): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/AlarmManager(  945): ELAPSED_WAKEUP set : Alarm{21d2985d type 2 when 79163 android} when 79163
I/art     ( 4031): Explicit concurrent mark sweep GC freed 9753(477KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 11.007ms total 53.564ms
,I/ActivityManager(  945): Killing 5102:com.android.chrome/u0a48 (adj 15): empty #11
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/libprocessgroup(  945): failed to open /acct/uid_10048/pid_5102/cgroup.procs: No such file or directory
E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/ActivityManager(  945): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5435 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/art     (  312): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 20.971ms
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.499ms
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.540ms
W/ResourcesManager( 5435): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/CheckinRequestBuilder( 4296): Classify the device as Phone.
I/CheckinTask( 4296): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 4296): Checking schedule, now: 1457378940616 next: 1457906189606
I/CheckinService( 4296): active receiver: disabled
I/CheckinService( 4296): Checking schedule, now: 1457378940665 next: 1457906189606
I/CheckinService( 4296): active receiver: disabled
D/CheckinService( 4296): Recording last checkin time for package unspecified as 1457378940673
I/NotificationManager( 1939): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Babel_SMS( 5435): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5435): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5435): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5435): MmsConfig.loadFromDatabase
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 24564(1416KB) AllocSpace objects, 7(112KB) LOS objects, 39% free, 13MB/22MB, paused 2.253ms total 105.278ms
E/Babel_SMS( 5435): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5435): MmsConfig.loadFromResources
E/Babel_SMS( 5435): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5435): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5435): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5435): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5435): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5435): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5435): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5435): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5435): found sensor: LGE Rotation Vector Sensor, handle=36
,D/SensorManager( 5435): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5435): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5435): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5435): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5435): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5435): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5435): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5435): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5435): found sensor: Motion Accel, handle=46
W/art     ( 5435): Suspending all threads took: 6.645ms
,I/art     ( 5435): CheckpointMarkThreadRoots callback created = 0xb042d8c0
,W/Settings( 5435): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5435): startup - clean
I/art     ( 5435): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,I/Babel   ( 5435): deleted: false for 0
,W/AudioCapabilities( 5435): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5435): Unsupported mime audio/adpcm
W/AudioCapabilities( 5435): Unsupported mime audio/g726
W/AudioCapabilities( 5435): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5435): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5435): Unsupported mime video/mjpg
W/VideoCapabilities( 5435): Unsupported mime video/theora
,W/AudioCapabilities( 5435): Unsupported mime audio/evrc
,W/AudioCapabilities( 5435): Unsupported mime audio/qcelp
W/VideoCapabilities( 5435): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5435): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5435): Unsupported mime audio/qcelp
W/AudioCapabilities( 5435): Unsupported mime audio/evrc
W/VideoCapabilities( 5435): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5435): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5435): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5435): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5435): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5435): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 5435): onServiceConnected
,W/Babel   ( 5435): Attempted to change video mute state without an active call.
I/NotificationManager( 5435): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 5435): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5435): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  945): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5473 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AudioManager( 5185): getMode name:com.lge.qremote
,I/AudioManager( 5185): getMode name:com.lge.qremote
V/JNIHelp ( 5435): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  945): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5490 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/System  ( 5435): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5435): Installed default security provider GmsCore_OpenSSL
,D/UEI.SmartControl( 5473): Quickset Services start...
,I/UEI.SmartControl( 5473): Manufacture = LGE
D/UEI.SmartControl( 5473): File observer start...
E/UEI.SmartControl( 5473): IR Port is disabled: false
D/UEI.SmartControl( 5473): Starting file observer...
D/UEI.SmartControl( 5473): Extracting JNI libs...
W/ResourcesManager( 5490): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5490): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5473): --- this system supports 32-bit or 64-bit only
W/ResourcesManager( 5490): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LGEmail ( 5490): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 5490): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ActivityManager(  945): Process com.lge.bnr (pid 5253) has died
,D/AlertService( 3870): Beginning updateAlertNotification
,D/AlertService( 3870): No fired or scheduled alerts
I/NotificationManager( 3870): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(2) by com.android.calendar
,I/NotificationManager( 3870): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(8) by com.android.calendar
D/UEI.SmartControl( 5473): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5473): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5473): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/NotificationManager( 3870): com.android.calendar: cancel(9) by com.android.calendar
,I/NotificationManager( 3870): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(14) by com.android.calendar
,I/NotificationManager( 3870): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(20) by com.android.calendar
,I/UEI.SmartControl( 5473): --- Selecting new region: 2
I/UEI.SmartControl( 5473): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5473): Platform has CIR...
,D/UEI.SmartControl( 5473): NO CIR support, need to check package...
I/UEI.SmartControl( 5473): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5473): QS Service created
D/AlertService( 3870): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,E/UEI.SmartControl( 5473): QS start get config
I/PackageChangeReceiver( 5490): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager(  945): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5525 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,D/UEI.SmartControl( 5473): Loading JNI Libs...
,D/UEI.SmartControl( 5473):  configuring local db...
D/AlarmScheduler( 3870): No events found starting within 1 week.
,I/ActivityManager(  945): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5545 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  945): Killing 5129:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,D/UEI.SmartControl( 5473):  ---- Has DB8: true
,D/UEI.SmartControl( 5473): QS start statue = true Error code = 0
D/UEI.SmartControl( 5473): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5473): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5473): IRRCDataComm has AudioManager!!!!.
,W/libprocessgroup(  945): failed to open /acct/uid_10086/pid_5129/cgroup.procs: No such file or directory
W/irrc_jni( 5473): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5473): IrrcClient ++ 
D/irrcClient( 5473): getIrrcService ++ 
,D/irrcClient( 5473): getIrrcService -- 
D/irrcClient( 5473): IrrcClient -- 
W/irrc_jni( 5473): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5473): Services init done
I/UEI.SmartControl( 5473): Device manager: loading config....
,D/UEI.SmartControl( 5473): Config is loaded...
D/UEI.SmartControl( 5473):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5473): Notify AllClients services are ready: 0
,I/art     (  945): Explicit concurrent mark sweep GC freed 20443(989KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/34MB, paused 1.896ms total 158.099ms
,D/UEI.SmartControl( 5473): QS Service init finished
D/UEI.SmartControl( 5473): QS Service version name: 0.1.73
D/UEI.SmartControl( 5473): QS Service version code: 1073
D/UEI.SmartControl( 5473): Service requested: Control
D/UEI.SmartControl( 5473): Internal service binding...
,D/UEI.SmartControl( 5473): -----IControl: 11
D/UEI.SmartControl( 5473): Caller: com.lge.qremote
D/UEI.SmartControl( 5473): ------------ IControl registerCallback...
I/UEI.SmartControl( 5473): Registering callback...
D/UEI.SmartControl( 5473): -----IControl: 19
D/UEI.SmartControl( 5473): Caller: com.lge.qremote
I/UEI.SmartControl( 5473): Registering Services Ready callback...
I/UEI.SmartControl( 5473): Notify client services are ready...
D/UEI.SmartControl( 5473): -----IControl: 8
D/UEI.SmartControl( 5473): Caller: com.lge.qremote
,I/ActivityManager(  945): Killing 5232:com.lge.sync/1000 (adj 15): empty #11
I/ActivityManager(  945): Killing 5207:com.android.settings/1000 (adj 15): empty #12
,I/AppUp4:AppBoxCP( 5545): onCreate
,W/AppUp4:DB( 5545):  [AppBoxDatabaseHelper] construct
W/libprocessgroup(  945): failed to open /acct/uid_1000/pid_5232/cgroup.procs: No such file or directory
W/libprocessgroup(  945): failed to open /acct/uid_1000/pid_5207/cgroup.procs: No such file or directory
I/AppUp4:DB( 5545):  setFingerPrint start
,I/AppUp4:DB( 5545):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5545):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5545):  SDK version = 0
I/AppUp4:DB( 5545):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5545): AppBoxApplication onCreate()
D/AppUp4:PreloadHelper( 5545): removed from Exclude : com.test.thalitest : 1
,I/ActivityManager(  945): Killing 5159:com.lge.clock/u0a10 (adj 15): empty #11
W/libprocessgroup(  945): failed to open /acct/uid_10010/pid_5159/cgroup.procs: No such file or directory
,I/ActivityManager(  945): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5568 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 5568): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5568): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5568): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 5568): Total System Memory = 906309632
,I/GalleryUtils( 5568): Application Heap = 96 MB
I/AppConfig( 5568): App Tier : NOT_DEF
D/SystemHelper( 5568): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  945): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5588 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  945): Killing 5270:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  945): failed to open /acct/uid_10081/pid_5270/cgroup.procs: No such file or directory
,W/ResourcesManager( 5588): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5588): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5588): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5588): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5588): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 5588): BUILD Country: EU
I/SystemConfig( 5588): BUILD Operator: OPEN
,I/SystemConfig( 5588): pm.hasSystemFeature(com.lge.ims.rcs) = false
,I/SystemConfig( 5588): existFile = false
I/SystemConfig( 5588): canReadFile = false
I/SystemConfig( 5588): systemFeature RCS result false
D/SystemConfig( 5588): refreshRcsSupport() :false
I/ActivityManager(  945): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5607 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  945): Killing 5322:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  945): failed to open /acct/uid_10014/pid_5322/cgroup.procs: No such file or directory
,I/LockScreenSettings( 5607): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 5607): New app installed broadcast received ..
,I/LockScreenSettings( 5607): Number of installed packages  1
I/ActivityManager(  945): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5624 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  945): Killing 5354:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  945): failed to open /acct/uid_10053/pid_5354/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 5624): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5624): uri : package:com.test.thalitest
,I/ActivityManager(  945): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5641 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  945): Killing 5411:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  945): failed to open /acct/uid_10038/pid_5411/cgroup.procs: No such file or directory
,D/[BNRAppListMgrReceiver]( 5641): android.intent.action.PACKAGE_ADDED : com.test.thalitest
,W/MainApplication( 5641): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ActivityManager(  945): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5659 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  945): Killing 4031:com.google.process.gapps/u0a6 (adj 15): empty #11
W/libprocessgroup(  945): failed to open /acct/uid_10006/pid_4031/cgroup.procs: No such file or directory
,I/ActivityManager(  945): Killing 5185:com.lge.qremote/u0a106 (adj 15): empty #11
,W/libprocessgroup(  945): failed to open /acct/uid_10106/pid_5185/cgroup.procs: No such file or directory
,I/ActivityManager(  945): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5678 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/art     (  312): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 287us total 22.800ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 21.083ms
I/CheckinService( 4296): Done disabling old GoogleServicesFramework version
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 21.552ms
,I/GservicesProvider( 5678): Gservices pushing to system: true; secure/global: true
I/GoogleHttpClient( 5678): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5678): GMS http client unavailable, use old client
,D/Finsky  ( 5659): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5659): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5659): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5659): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5659): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3229): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3229): created cursor android.database.sqlite.SQLiteCursor@2cd28c89 on behalf of 5659
I/NotificationManager( 5659): com.android.vending: cancel(1003285959) by com.android.vending
D/Ads     ( 5659): Skipping gmscore version check
,I/ActivityManager(  945): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5722 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,D/Finsky  ( 5659): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5659): [1] Libraries$2.run: Finished loading 1 libraries.
I/ActivityManager(  945): Killing 5473:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/libprocessgroup(  945): failed to open /acct/uid_10089/pid_5473/cgroup.procs: No such file or directory
,D/Finsky  ( 5659): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,D/Finsky  ( 5659): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  945): Killing 5490:com.lge.email/u0a21 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/InitAlarmsService( 3870): Clearing and rescheduling alarms.
,W/libprocessgroup(  945): failed to open /acct/uid_10021/pid_5490/cgroup.procs: No such file or directory
,D/Finsky  ( 5659): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  945): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5751 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  945): Killing 5525:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/libprocessgroup(  945): failed to open /acct/uid_10009/pid_5525/cgroup.procs: No such file or directory
W/ResourcesManager( 5751): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5751): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@26239c00
,D/CalendarProvider2( 5751): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5751): Created com.android.providers.calendar.CalendarAlarmManager@406c2f5(com.android.providers.calendar.CalendarProvider2@26239c00)
D/CalendarProvider2( 5751): Scheduling check of next Alarm
D/CalendarProvider2( 5751): SCHEDULE_ALARM_REMOVE
I/ActivityManager(  945): Killing 3870:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  945): failed to open /acct/uid_10013/pid_3870/cgroup.procs: No such file or directory
,I/GAv4    ( 5722): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5722):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5722):   adb logcat -s GAv4
,W/GAv4    ( 5722): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5722): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5722): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5722): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5722): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
I/ActivityManager(  945): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5791 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  945): Killing 5545:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/ResourcesManager( 5722): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5722): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  945): failed to open /acct/uid_10011/pid_5545/cgroup.procs: No such file or directory
,I/art     ( 5722): CheckpointMarkThreadRoots callback created = 0xaaef2210
,W/ResourcesManager( 5791): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/JNIHelp ( 5722): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/art     ( 5722): CheckpointMarkThreadRoots callback created = 0xaaef2b20
,W/System  ( 5722): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5722): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CalendarProvider2( 5751): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5751): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  945): Killing 5568:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  945): failed to open /acct/uid_10023/pid_5568/cgroup.procs: No such file or directory
,I/ActivityManager(  945): Killing 5588:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  945): failed to open /acct/uid_10018/pid_5588/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 4296): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,I/UpdateIcingCorporaServi( 1939): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
D/ChimeraCfgMgr( 4296): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4296): Loading module APK com.google.android.play.games
I/UpdateIcingCorporaServi( 1939): UpdateCorporaTask done [took 112 ms] updated apps [took 112 ms] 
,D/ChimeraCfgMgr( 4296): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4296): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4296): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/AsyncTaskServiceImpl( 4296): Submit a task: k
,I/Icing   ( 4296): Storage manager: low false usage 1.70MB avail 2.37GB capacity 4.06GB
D/ChimeraCfgMgr( 4296): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 4296): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 4296): Processing package: com.test.thalitest
D/GassUtils( 4296): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,D/k       ( 4296): Found info for package com.test.thalitest in db.
I/ActivityManager(  945): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5850 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,I/PeopleDatabaseHelper( 4296): cleanUpNonGplusAccounts done.
,W/BaseAppContext( 4296): Using Auth Proxy for data requests.
W/BaseAppContext( 4296): Using Auth Proxy for data requests.
,W/BaseAppContext( 4296): Using Auth Proxy for data requests.
W/BaseAppContext( 4296): Using Auth Proxy for data requests.
,W/BaseAppContext( 4296): Using Auth Proxy for data requests.
W/ResourcesManager( 5850): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/BluetoothManagerService(  945): Message: 20
D/BluetoothManagerService(  945): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1737ccb5:true
,D/BluetoothAdapterService(223189361)( 2010): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@51512cf
,D/BluetoothAdapterService(223189361)( 2010): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@51512cf
I/AudioManager( 5850): getMode name:com.lge.qremote
I/AudioManager( 5850): getMode name:com.lge.qremote
,I/AudioManager( 5850): getMode name:com.lge.qremote
D/WearableService( 1733): callingUid 10006, callindPid: 1733
,D/LocationInitializer( 4296): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1733): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,I/Icing   ( 4296): updateResources: need to parse f{com.google.android.gms}
,I/art     (  945): Explicit concurrent mark sweep GC freed 22318(1047KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.520ms total 162.724ms
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
I/NotificationManager( 5435): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 5435): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5435): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  945): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5884 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/Icing   ( 4296): Internal init done: storage state 0
,I/AppUp4:AppBoxCP( 5884): onCreate
W/AppUp4:DB( 5884):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5884):  setFingerPrint start
I/AppUp4:DB( 5884):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 5884):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5884):  SDK version = 0
I/AppUp4:DB( 5884):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5884): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 5884): onReceive
I/AppUp4:CustModeStarterReceiver( 5884): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 5884): Context : android.app.ReceiverRestrictedContext@30c173df
D/AppUp4:CustFacade( 5884): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5884): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5884): begin check event
I/AppUp4:CustModeStarterReceiver( 5884): Event For Nothing, skip.
I/ActivityManager(  945): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5903 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/art     ( 4296): Explicit concurrent mark sweep GC freed 39048(2MB) AllocSpace objects, 25(400KB) LOS objects, 40% free, 13MB/22MB, paused 7.220ms total 125.375ms
,I/Icing   ( 4296): Post-init done
,W/SQLiteConnectionPool( 4296): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,W/ResourcesManager( 5903): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5903): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5903): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/AppConfig( 5903): Total System Memory = 906309632
I/GalleryUtils( 5903): Application Heap = 96 MB
,I/AppConfig( 5903): App Tier : NOT_DEF
D/SystemHelper( 5903): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  945): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5923 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  945): Killing 5607:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,D/ChimeraCfgMgr( 4296): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4296): Module APK com.google.android.play.games already loaded
,W/libprocessgroup(  945): failed to open /acct/uid_10069/pid_5607/cgroup.procs: No such file or directory
,W/ResourcesManager( 5923): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5923): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5923): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5923): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5923): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 5923): BUILD Country: EU
I/SystemConfig( 5923): BUILD Operator: OPEN
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ActivityManager(  945): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5951 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  945): Killing 5624:com.lge.eula/1000 (adj 15): empty #11
W/libprocessgroup(  945): failed to open /acct/uid_1000/pid_5624/cgroup.procs: No such file or directory
,I/SystemConfig( 5923): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5923): existFile = false
I/SystemConfig( 5923): canReadFile = false
I/SystemConfig( 5923): systemFeature RCS result false
D/SystemConfig( 5923): refreshRcsSupport() :false
,I/LockScreenSettings( 5951): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 5951): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5951): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5951): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5951): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5951): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/UpdateIcingCorporaServi( 1939): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  945): Killing 5641:com.lge.bnr/1000 (adj 15): empty #11
D/PackageBroadcastService( 4296): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/UpdateIcingCorporaServi( 1939): UpdateCorporaTask done [took 62 ms] updated apps [took 62 ms] 
,W/libprocessgroup(  945): failed to open /acct/uid_1000/pid_5641/cgroup.procs: No such file or directory
,I/PackageBroadcastService( 4296): Null package name or gms related package.  Ignoreing.
I/Icing   ( 4296): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  945): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5976 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 5850): Create singleton instance
,D/UEI.SmartControl( 5976): Quickset Services start...
,I/UEI.SmartControl( 5976): Manufacture = LGE
D/UEI.SmartControl( 5976): File observer start...
E/UEI.SmartControl( 5976): IR Port is disabled: false
D/UEI.SmartControl( 5976): Starting file observer...
D/UEI.SmartControl( 5976): Extracting JNI libs...
D/UEI.SmartControl( 5976): --- this system supports 32-bit or 64-bit only
I/AudioManager( 5850): getMode name:com.lge.qremote
,I/AudioManager( 5850): getMode name:com.lge.qremote
I/ActivityManager(  945): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6006 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 5976): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5976): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5976): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 5976): --- Selecting new region: 2
I/UEI.SmartControl( 5976): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5976): Platform has CIR...
D/UEI.SmartControl( 5976): NO CIR support, need to check package...
I/UEI.SmartControl( 5976): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5976): QS Service created
I/Icing   ( 4296): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,E/UEI.SmartControl( 5976): QS start get config
,D/UEI.SmartControl( 5976): Loading JNI Libs...
D/UEI.SmartControl( 5976):  configuring local db...
,W/ActivityManager(  945): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/Icing   ( 4296): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 4296): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/Gmail   ( 6006): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6006): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  945): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6006): Error finding the version of the Email provider.....
E/Gmail   ( 6006): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6006): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6006): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6006): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6006): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6006): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6006): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6006): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6006): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6006): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  945): Killing 5044:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/UEI.SmartControl( 5976):  ---- Has DB8: true
W/libprocessgroup(  945): failed to open /acct/uid_10006/pid_5044/cgroup.procs: No such file or directory
,W/ActivityManager(  945): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
D/UEI.SmartControl( 5976): QS start statue = true Error code = 0
D/UEI.SmartControl( 5976): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5976): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5976): IRRCDataComm has AudioManager!!!!.
,W/ActivityManager(  945): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6006): Observing account changes for notifications
W/irrc_jni( 5976): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 5976): IrrcClient ++ 
D/irrcClient( 5976): getIrrcService ++ 
D/irrcClient( 5976): getIrrcService -- 
D/irrcClient( 5976): IrrcClient -- 
W/irrc_jni( 5976): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5976): Services init done
I/UEI.SmartControl( 5976): Device manager: loading config....
D/UEI.SmartControl( 5976): QS Service init finished
,D/UEI.SmartControl( 5976): Config is loaded...
D/UEI.SmartControl( 5976): QS Service version name: 0.1.73
D/UEI.SmartControl( 5976): QS Service version code: 1073
D/UEI.SmartControl( 5976): Service requested: Control
D/UEI.SmartControl( 5976): Internal service binding...
D/UEI.SmartControl( 5976): -----IControl: 11
D/UEI.SmartControl( 5976): Caller: com.lge.qremote
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/UEI.SmartControl( 5976): ------------ IControl registerCallback...
I/UEI.SmartControl( 5976): Registering callback...
D/UEI.SmartControl( 5976): -----IControl: 19
D/UEI.SmartControl( 5976): Caller: com.lge.qremote
I/UEI.SmartControl( 5976): Registering Services Ready callback...
I/UEI.SmartControl( 5976): Notify client services are ready...
D/UEI.SmartControl( 5976): -----IControl: 8
D/UEI.SmartControl( 5976): Caller: com.lge.qremote
I/ActivityManager(  945): Killing 5751:com.android.providers.calendar/u0a14 (adj 15): empty #11
,D/UEI.SmartControl( 5976):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 5976): Notify AllClients services are ready: 0
I/ActivityManager(  945): Killing 5722:com.google.android.apps.docs/u0a58 (adj 15): empty #12
,W/libprocessgroup(  945): failed to open /acct/uid_10014/pid_5751/cgroup.procs: No such file or directory
,W/libprocessgroup(  945): failed to open /acct/uid_10058/pid_5722/cgroup.procs: No such file or directory
I/Gmail   ( 6006): notifyAccountChanged
,I/Gmail   ( 6006): getAccountsCursor
I/Gmail   ( 6006): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6006): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6006): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6006): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager(  945): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6049 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  312): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 298us total 21.247ms
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 274us total 20.999ms
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 21.021ms
,I/ActivityManager(  945): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6075 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,I/Icing   ( 4296): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4296): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/art     ( 5678): Explicit concurrent mark sweep GC freed 8935(451KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 716us total 78.600ms
,I/Gmail   ( 6006): getAccountsCursor
,E/UpdateRequestReceiver( 6075): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6075): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 6075): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6075): Received malformed URL while handling Gservices.CHANGED_ACTION
I/ActivityManager(  945): Killing 5884:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/art     (  945): Explicit concurrent mark sweep GC freed 14929(709KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.265ms total 155.753ms
,W/libprocessgroup(  945): failed to open /acct/uid_10011/pid_5884/cgroup.procs: No such file or directory
D/Finsky  ( 5659): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  945): RTC_WAKEUP set : Alarm{2cbcc6b type 0 when 1457378949429 com.android.vending} when 1457378949429
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinService( 4296): Checkin interval check for package: unspecified last checkin: 1457378940673 min interval config: 0 actual interval: 8872
,I/CheckinService( 4296): Checking schedule, now: 1457378949553 next: 1457906189606
I/CheckinService( 4296): active receiver: disabled
I/GservicesUpdateTask( 1939): Updating Gservices keys
,I/SystemUpdateService( 4296): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/SystemUpdateService( 4296): onCreate
D/SystemUpdateService( 4296): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
I/SystemUpdateService( 4296): cancelUpdate (empty URL)
I/SystemUpdateService( 4296): active receiver: disabled
,I/NotificationManager( 4296): com.google.android.gms: cancel(2130838165) by com.google.android.gms
I/NotificationManager( 4296): com.google.android.gms: cancel(2130838166) by com.google.android.gms
I/NotificationManager(  945): android: cancelAsUser(2) by android
,I/art     ( 5678): Explicit concurrent mark sweep GC freed 2798(110KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.155ms total 38.031ms
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/art     ( 4296): Explicit concurrent mark sweep GC freed 34834(2MB) AllocSpace objects, 8(128KB) LOS objects, 40% free, 14MB/23MB, paused 2.167ms total 109.344ms
,V/AlarmManager(  945): ELAPSED_WAKEUP set : Alarm{2e1ca65b type 2 when 88916 com.android.providers.calendar} when 88916
,D/SystemUpdateService( 4296): onDestroy
,E/DynamiteModule( 4296): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 4296): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 4296): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 4296): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 4296): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 4296): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 4296): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 4296): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 4296): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 4296): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 4296): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 4296): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/DynamiteModule( 4296): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/DynamiteModule( 4296): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/DynamiteModule( 4296): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 4296): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 4296): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/DynamiteModule( 4296): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 4296): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 4296): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/DynamiteModule( 4296): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/DynamiteModule( 4296): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 4296): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 4296): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 4296): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 4296): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 4296): 		... 17 more
E/DynamiteModule( 4296): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
I/DynamiteModule( 4296): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 4296): Selected local version of com.google.android.gms.flags
,D/libc-netbsd( 5659): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5659): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5659): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5659): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/System.out( 5659): propertyValue:false
D/libc-netbsd( 5659): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5659): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/SystemEventReceiver( 4296): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 4296): Updating ocr activity enabled=false
,W/ActivityManager(  945): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 4296): Updating downloaded model state (gservices changed)
,I/art     ( 5678): Explicit concurrent mark sweep GC freed 2595(102KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.755ms total 31.670ms
,I/NotificationManager(  945): android: cancelAsUser(-591465577) by android
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 15541(1057KB) AllocSpace objects, 18(288KB) LOS objects, 40% free, 13MB/22MB, paused 1.249ms total 69.220ms
,D/libc-netbsd( 5659): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5659): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/GCM     ( 1733): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  945): Reconfiguring input devices.  changes=0x00000010
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
D/administrator(  945): Handling package changes for user 0
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/GCoreUlr( 1733): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1733): DispatchingService.onCreate(),
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/GCoreUlr( 1733): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,I/NotificationService(  945): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  945): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  945): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  945): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/BackupManagerService(  945): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  945): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@316ed38a
W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
,I/NotificationManager(  945): android: cancelAsUser(2) by android
,I/ActivityManager(  945): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6162 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
W/ResourcesManager(  945): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/ctxmgr  ( 1733): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,I/art     ( 5678): Explicit concurrent mark sweep GC freed 2925(115KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.701ms total 35.879ms
W/ResourceType(  945): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/ctxmgr  ( 1733): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
,E/ctxmgr  ( 1733): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
,I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/qtaguid ( 5659): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5659): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5659): untagSocket(41) failed with errno -22
,D/Finsky  ( 5659): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430700] >= Server Version [-1]
I/GCoreUlr( 1733): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/GCoreUlr( 1733): Unbound from all location providers
I/GCoreUlr( 1733): Place inference reporting - stopped
D/LocationProviderProxy(  945): applying state to connected service
I/GCoreUlr( 1733): DispatchingService.onDestroy()
I/GCoreUlr( 1733): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1733): Unbound from all location providers
I/GCoreUlr( 1733): Place inference reporting - stopped
D/PhoneMonitor( 6162): Register our PhoneStateListener
,I/ActivityManager(  945): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6182 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a,
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  945): android: cancelAsUser(2) by android
V/SetupWizard( 6162): Connected to Gservices successfully
,I/ActivityManager(  945): Killing 5903:com.android.gallery3d/u0a23 (adj 15): empty #11
,D/PhoneMonitor( 6162): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6162): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6162): [parse] Load xml
V/TelephonyAutoProfiling( 6162): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6162): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6162): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  945): failed to open /acct/uid_10023/pid_5903/cgroup.procs: No such file or directory
,I/AudioManager( 5850): getMode name:com.lge.qremote
,W/ResourcesManager( 6182): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6182): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  945): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6204 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/MultiDex( 6182): VM with version 2.1.0 has multidex support
I/MultiDex( 6182): install
I/MultiDex( 6182): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6182): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ResourcesManager( 6204): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ActivityThread( 6182): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6182): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1f7424af: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6182): Installed default security provider GmsCore_OpenSSL
D/CalendarApplication( 6204): CalendarApplication.onCreate()
I/NotificationManager( 6182): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6182): com.google.android.gms: cancel(39789) by com.google.android.gms
D/PreferenceKeysParser( 6204): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6204): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@1c4f127e, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@30c173df, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@3126782c, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@406c2f5, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@4c5d88a, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@14f36efb, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@2898eb18, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@d4d9971, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2d30f356, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@327fffd7, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@37bda0c4, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1e515bad, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@760eee2, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@11dac273, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@19560530, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@325505a9, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1fa3172e, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@51512cf, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@30ce445c, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@1bcf5365, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@27cd783a, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@3fa0ceb, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@a294a48, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@23e6c0e1, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@270ade06, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2dea8cc7, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@2cacc2f4, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@25ad8a1d, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@1a66d492, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@d792e63, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@2c4d1a60, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@211dab19, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@1219a7de, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@39c64dbf, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@25d97c8c, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1d4dfd5, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@179463ea, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@319c06db, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@11e7d578, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1590a451, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@284cd4b6, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@c4a35b7
D/ChimeraC,fgMgr( 6182): Reading stored module config
D/GeneralPreferenceUtils( 6204): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6204): [init]
I/Config  ( 6204): LGCalendar ver.4.40.17
I/Config  ( 6204): start check model
I/Config  ( 6204): start check native_ca
I/Config  ( 6204): Config Operator=OPEN, Country=EU
,D/Config  ( 6204): [setDefaultValuesToPref]
D/Config  ( 6204): [parseProfiles]
D/ProfilesParser( 6204): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6204): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6204): [updateProfiletoCountryInfo]
D/GeneralPreference( 6204): [checkAndMigrateOldPreference]
,I/qtaguid ( 5659): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5659): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5659): untagSocket(41) failed with errno -22
D/NativeLibraryUtils( 6182): Install completed successfully. count=14 extracted=0
,I/art     (  945): Explicit concurrent mark sweep GC freed 28967(1442KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.368ms total 148.900ms
,D/ChimeraCfgMgr( 6182): Loading module com.google.android.gms.car from APK com.google.android.gms
D/AlertReceiver( 6204): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/InitNotificationRingtoneService( 6204): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6204): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/AlertUtils( 6204): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 6204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 6204): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6204): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6204): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6204): End InitializeAlertRingtoneService.onHandleIntent
,D/CAR.SERVICE( 6182): Connecting to CarCallService...
,W/HolidayIntentService( 6204): onHandleIntent
,D/HolidayDataLoader( 6204): readJsonAsset : holiday.json
I/art     ( 6182): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6182): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/AlertService( 6204): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6204): [updateWidgets] 
,D/MonthWidgetProvider( 6204): [onReceive]
D/CalendarWidgetProvider( 6204): [onReceive]
D/CalendarWidgetProvider( 6204): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6204): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6204): [onReceive]
D/CalendarWidgetProvider( 6204): [onReceive]
D/CalendarWidgetProvider( 6204): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6204): [onCreate] mContext.getPackageName() = com.android.calendar
I/AudioManager( 5850): getMode name:com.lge.qremote
,I/AudioManager( 5850): getMode name:com.lge.qremote
,D/CAR.SERVICE( 6182): com.google.android.projection.gearhead isn't installed.
I/ActivityManager(  945): Killing 5923:com.android.contacts/u0a18 (adj 15): empty #11
,D/CAR.TEL.Service( 6182): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 6182): Creating a new PhoneAdapter instance
,I/art     ( 5659): CheckpointMarkThreadRoots callback created = 0xb0584450
,E/HolidayIntentService( 6204): onHandleIntent:holiday data empty
I/art     ( 5659): CheckpointMarkThreadRoots callback created = 0xb0584410
,W/ActivityManager(  945): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,W/libprocessgroup(  945): failed to open /acct/uid_10018/pid_5923/cgroup.procs: No such file or directory
D/CAR.TEL.PhoneAdapter( 6182): setListener: com.google.android.gms.car.dn@1fcc1f4a
W/ActivityManager(  945): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6182): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6182): Starting CarCallService with initial phone null
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/NotificationManager( 6182): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/ActivityManager(  945): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6254 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  945): Killing 5435:com.google.android.talk/u0a61 (adj 15): empty #11
,D/CAR.SERVICE( 6182): Package validated; name: com.android.vending
,W/libprocessgroup(  945): failed to open /acct/uid_10061/pid_5435/cgroup.procs: No such file or directory
,W/ResourcesManager( 6254): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/NotificationManager( 5659): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5659): [1] GearheadStateMonitor.access$100: mIsProjecting:false
D/CalendarProvider2( 6254): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@26239c00
,D/CalendarProvider2( 6254): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6254): Created com.android.providers.calendar.CalendarAlarmManager@406c2f5(com.android.providers.calendar.CalendarProvider2@26239c00)
D/CalendarProviderBroadcastReceiver( 6254): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6254): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6254): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6254): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
,D/CalendarProvider2( 6254): [getOrCreateCalendarAlarmManager]
I/ActivityManager(  945): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6278 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/CalendarProvider2( 6254): [IntentService] Release Lock
,D/CalendarProvider2( 6254): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  945): Killing 5951:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/libprocessgroup(  945): failed to open /acct/uid_10069/pid_5951/cgroup.procs: No such file or directory
,W/ResourcesManager( 6278): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  945): android: cancelAsUser(2) by android
,I/Babel_SMS( 6278): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6278): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6278): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6278): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6278): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6278): MmsConfig.loadFromResources
E/Babel_SMS( 6278): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6278): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 6278): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6278): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6278): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6278): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6278): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6278): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6278): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6278): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6278): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6278): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6278): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6278): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6278): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6278): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6278): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6278): found sensor: Motion Accel, handle=46
,W/Settings( 6278): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6278): startup - clean
I/qtaguid ( 5659): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5659): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5659): untagSocket(41) failed with errno -22
,I/art     ( 6278): CheckpointMarkThreadRoots callback created = 0xb042d920
I/Babel   ( 6278): deleted: false for 0
,I/art     ( 6278): CheckpointMarkThreadRoots callback created = 0xb042d900
,W/AudioCapabilities( 6278): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6278): Unsupported mime audio/adpcm
W/AudioCapabilities( 6278): Unsupported mime audio/g726
W/AudioCapabilities( 6278): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6278): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6278): Unsupported mime video/mjpg
W/VideoCapabilities( 6278): Unsupported mime video/theora
I/ActivityManager(  945): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6305 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/AudioCapabilities( 6278): Unsupported mime audio/evrc
,W/AudioCapabilities( 6278): Unsupported mime audio/qcelp
W/VideoCapabilities( 6278): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6278): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6278): Unsupported mime audio/qcelp
W/AudioCapabilities( 6278): Unsupported mime audio/evrc
I/AppUp4:AppBoxCP( 6305): onCreate
W/AppUp4:DB( 6305):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6305):  setFingerPrint start
I/AppUp4:DB( 6305):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6305):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6305):  SDK version = 0
I/AppUp4:DB( 6305):  beforefinger == newfinger no write in DB
W/VideoCapabilities( 6278): Unsupported mime video/mp4v-esdp
D/AppUp4:AppBoxApplication( 6305): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 6305): onReceive
I/AppUp4:CustModeStarterReceiver( 6305): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,I/VideoCapabilities( 6278): Unsupported profile 4 for video/mp4v-es
D/AppUp4:CustFacade( 6305): Context : android.app.ReceiverRestrictedContext@30c173df
D/AppUp4:CustFacade( 6305): isCustomizationCompleted : false
W/VideoCapabilities( 6278): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6278): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6278): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6278): Unrecognized profile 2130706433 for video/avc
D/AppUp4:CustFacade( 6305): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6305): begin check event
I/AppUp4:CustModeStarterReceiver( 6305): Event For Nothing, skip.
I/ActivityManager(  945): Killing 5791:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/ResourcesManager( 5659): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5659): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5659): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/libprocessgroup(  945): failed to open /acct/uid_10086/pid_5791/cgroup.procs: No such file or directory
,I/ActivityManager(  945): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6332 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/vclib   ( 6278): onServiceConnected
W/Babel   ( 6278): Attempted to change video mute state without an active call.
I/NotificationManager( 6278): com.google.android.talk: cancel(8) by com.google.android.talk
,D/Finsky  ( 5659): [1] DailyHygiene.access$600: Logging device features
W/ResourcesManager( 6278): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6278): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/AlarmManager(  945): RTC_WAKEUP set : Alarm{ba6c76f type 0 when 1457378953637 com.android.vending} when 1457378953637
,W/ResourcesManager( 6332): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
D/DeviceConnectionService( 1733): client connected with version: 8296000
,W/ResourcesManager( 6332): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6332): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
D/WearableService( 1733): callingUid 10006, callindPid: 1733
V/JNIHelp ( 6278): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/Finsky  ( 5659): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5659): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  945): Killing 6075:com.google.android.configupdater/u0a3 (adj 15): empty #11
W/System  ( 6278): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6278): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  945): Killing 6049:com.google.android.partnersetup/u0a9 (adj 15): empty #12
,W/libprocessgroup(  945): failed to open /acct/uid_10003/pid_6075/cgroup.procs: No such file or directory
,W/libprocessgroup(  945): failed to open /acct/uid_10009/pid_6049/cgroup.procs: No such file or directory
I/NotificationManager( 6278): com.google.android.talk: cancel(10436) by com.google.android.talk
I/AppConfig( 6332): Total System Memory = 906309632
I/GAV2    ( 6006): Thread[GAThread,5,main]: No campaign data found.
,I/GalleryUtils( 6332): Application Heap = 96 MB
I/AppConfig( 6332): App Tier : NOT_DEF
D/SystemHelper( 6332): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  945): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6357 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  945): Killing 5976:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5850): android.os.DeadObjectException
,W/System.err( 5850): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5850): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5850): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5850): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5850): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5850): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5850): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5850): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5850): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5850): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5850): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5850): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5850): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5850): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5850): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5850): android.os.DeadObjectException
W/System.err( 5850): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5850): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5850): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5850): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5850): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5850): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5850): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5850): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5850): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5850): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5850): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5850): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5850): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5850): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5850): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  945): failed to open /acct/uid_10089/pid_5976/cgroup.procs: No such file or directory
,W/ActivityManager(  945): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
W/ResourcesManager( 6357): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6357): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 92885939865; DSPS: 3142346; Offset : -3024646688
W/ResourcesManager( 6357): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6357): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6357): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  945): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6376 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6357): BUILD Country: EU
I/SystemConfig( 6357): BUILD Operator: OPEN
D/UEI.SmartControl( 6376): Quickset Services start...
,I/UEI.SmartControl( 6376): Manufacture = LGE
D/UEI.SmartControl( 6376): File observer start...
E/UEI.SmartControl( 6376): IR Port is disabled: false
D/UEI.SmartControl( 6376): Starting file observer...
D/UEI.SmartControl( 6376): Extracting JNI libs...
D/UEI.SmartControl( 6376): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6376): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6376): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6376): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/ActivityManager(  945): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6399 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  945): Killing 6006:com.google.android.gm/u0a53 (adj 15): empty #11
I/art     (  312): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 21.620ms
,I/UEI.SmartControl( 6376): --- Selecting new region: 2
I/UEI.SmartControl( 6376): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6376): Platform has CIR...
D/UEI.SmartControl( 6376): NO CIR support, need to check package...
I/UEI.SmartControl( 6376): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6376): QS Service created
I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 23.265ms
,W/libprocessgroup(  945): failed to open /acct/uid_10053/pid_6006/cgroup.procs: No such file or directory
,I/art     (  312): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 22.568ms
I/SystemConfig( 6357): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6357): existFile = false
I/SystemConfig( 6357): canReadFile = false
I/SystemConfig( 6357): systemFeature RCS result false
D/SystemConfig( 6357): refreshRcsSupport() :false
,E/UEI.SmartControl( 6376): QS start get config
,I/LockScreenSettings( 6399): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
D/LockScreenSettings( 6399): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6399): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6399): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6399): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6399): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,D/UEI.SmartControl( 6376): Loading JNI Libs...
,D/UEI.SmartControl( 6376):  configuring local db...
I/ActivityManager(  945): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6416 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  945): Killing 5850:com.lge.qremote/u0a106 (adj 15): empty #11
,W/libprocessgroup(  945): failed to open /acct/uid_10106/pid_5850/cgroup.procs: No such file or directory
,W/ResourcesManager( 6416): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6376):  ---- Has DB8: true
,D/UEI.SmartControl( 6376): QS start statue = true Error code = 0
,D/UEI.SmartControl( 6376): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6376): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6376): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6376): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6376): IrrcClient ++ 
D/irrcClient( 6376): getIrrcService ++ 
D/irrcClient( 6376): getIrrcService -- 
D/irrcClient( 6376): IrrcClient -- 
W/irrc_jni( 6376): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6376): Services init done
,I/UEI.SmartControl( 6376): Device manager: loading config....
D/UEI.SmartControl( 6376): QS Service init finished
D/UEI.SmartControl( 6376): QS Service version name: 0.1.73
D/UEI.SmartControl( 6376): QS Service version code: 1073
D/UEI.SmartControl( 6376): Service requested: Control
D/UEI.SmartControl( 6376): Config is loaded...
D/UEI.SmartControl( 6376):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6376): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6376): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 6376): Service.onUnbind: IControl
D/UEI.SmartControl( 6376): Service.onDestroy
D/UEI.SmartControl( 6376): Shutdown IRRCPlayer... 
W/irrc_jni( 6376): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6376): ~IrrcClient ++ 
D/irrcClient( 6376): ~IrrcClient -- 
,W/irrc_jni( 6376): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6376): Blaster closed
D/UEI.SmartControl( 6376): Blaster closed
D/UEI.SmartControl( 6376): Shut down QS...
D/UEI.SmartControl( 6376): Stopped file observer...
I/UEI.SmartControl( 6376): QS lib stop result = true
D/UEI.SmartControl( 6376): QS shutdown complete
D/UEI.SmartControl( 6376): QS Service created
E/UEI.SmartControl( 6376): QS start get config
,D/UEI.SmartControl( 6376):  configuring local db...
I/art     (  945): Explicit concurrent mark sweep GC freed 17814(903KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.079ms total 136.438ms
,I/UpdateIcingCorporaServi( 1939): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 4296): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  945): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6445 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
I/PackageBroadcastService( 4296): Null package name or gms related package.  Ignoreing.
I/UpdateIcingCorporaServi( 1939): UpdateCorporaTask done [took 59 ms] updated apps [took 59 ms] 
,D/UEI.SmartControl( 6376):  ---- Has DB8: true
,D/UEI.SmartControl( 6376): QS start statue = true Error code = 0
D/UEI.SmartControl( 6376): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6376): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6376): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6376): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6376): IrrcClient ++ 
D/irrcClient( 6376): getIrrcService ++ 
D/irrcClient( 6376): getIrrcService -- 
D/irrcClient( 6376): IrrcClient -- 
W/irrc_jni( 6376): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6376): Services init done
I/Icing   ( 4296): updateResources: need to parse f{com.google.android.gms}
D/UEI.SmartControl( 6376): QS Service init finished
I/UEI.SmartControl( 6376): Device manager: loading config....
D/UEI.SmartControl( 6376): QS Service version name: 0.1.73
D/UEI.SmartControl( 6376): QS Service version code: 1073
D/UEI.SmartControl( 6376): Service requested: Control
D/UEI.SmartControl( 6376): Config is loaded...
,W/ResourcesManager( 6445): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6376):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6376): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6376): Request IControl service: devices are loaded...
I/ActivityManager(  945): Killing 6162:com.google.android.setupwizard/u0a38 (adj 15): empty #11
D/BluetoothManagerService(  945): Message: 20
D/BluetoothManagerService(  945): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2000e774:true
,W/libprocessgroup(  945): failed to open /acct/uid_10038/pid_6162/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
E/ActivityThread( 6376): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@d4d9971 that was originally bound here
E/ActivityThread( 6376): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@d4d9971 that was originally bound here
E/ActivityThread( 6376): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6376): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6376): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6376): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6376): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6376): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6376): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6376): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6376): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6376): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6376): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6376): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6376): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6376): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6376): Internal service binding...
D/BluetoothAdapterService(223189361)( 2010): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@51512cf
D/BluetoothAdapterService(223189361)( 2010): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@51512cf
I/AudioManager( 6445): getMode name:com.lge.qremote
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 25599(1555KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 13MB/23MB, paused 1.687ms total 84.390ms
,I/AudioManager( 6445): getMode name:com.lge.qremote
E/MDM     ( 1733): [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 4296): Restart initialization of location
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  945): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6480 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,W/ActivityManager(  945): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6480): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6480): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  945): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/AudioManager( 6445): getMode name:com.lge.qremote
I/AudioManager( 6445): getMode name:com.lge.qremote
I/AudioManager( 6445): getMode name:com.lge.qremote
D/Finsky  ( 5659): [685] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,E/Gmail   ( 6480): Error finding the version of the Email provider.....
E/Gmail   ( 6480): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6480): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6480): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6480): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6480): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6480): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6480): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6480): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6480): We do not support migrating this version of the Email provider.
I/Gmail   ( 6480): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  945): android: cancelAsUser(2) by android
,W/ActivityManager(  945): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  945): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6480): Observing account changes for notifications
V/LGMDMManager( 6445): Create singleton instance
,D/libc-netbsd( 5659): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5659): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5659): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5659): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  278): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
,I/AudioManager( 6445): getMode name:com.lge.qremote
I/System.out( 5659): propertyValue:false
D/UEI.SmartControl( 6376): -----IControl: 11
D/UEI.SmartControl( 6376): File observer start...
E/UEI.SmartControl( 6376): IR Port is disabled: false
D/UEI.SmartControl( 6376): Starting file observer...
I/Gmail   ( 6480): notifyAccountChanged
D/UEI.SmartControl( 6376): Caller: com.lge.qremote
D/UEI.SmartControl( 6376): ------------ IControl registerCallback...
I/UEI.SmartControl( 6376): Registering callback...
D/UEI.SmartControl( 6376): -----IControl: 19
D/UEI.SmartControl( 6376): Caller: com.lge.qremote
I/UEI.SmartControl( 6376): Registering Services Ready callback...
,I/UEI.SmartControl( 6376): Notify client services are ready...
D/UEI.SmartControl( 6376): -----IControl: 8
D/UEI.SmartControl( 6376): Caller: com.lge.qremote
I/Gmail   ( 6480): getAccountsCursor
I/Gmail   ( 6480): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/AudioManager( 6445): getMode name:com.lge.qremote
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6480): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6480): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6480): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/AudioManager( 6445): getMode name:com.lge.qremote
I/AudioManager( 6445): getMode name:com.lge.qremote
,I/Gmail   ( 6480): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  945): Killing 6305:com.lge.appbox.client/u0a11 (adj 15): empty #11
,I/ActivityManager(  945): Killing 6254:com.android.providers.calendar/u0a14 (adj 15): empty #12
,W/libprocessgroup(  945): failed to open /acct/uid_10011/pid_6305/cgroup.procs: No such file or directory
,W/libprocessgroup(  945): failed to open /acct/uid_10014/pid_6254/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Icing   ( 4296): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 4296): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 4296): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/AlertService( 6204): Beginning updateAlertNotification
,I/ActivityManager(  945): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6545 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6545): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6545): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@26239c00
,D/CalendarProvider2( 6545): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6545): Created com.android.providers.calendar.CalendarAlarmManager@406c2f5(com.android.providers.calendar.CalendarProvider2@26239c00)
D/AlertService( 6204): No fired or scheduled alerts
,I/NotificationManager( 6204): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6204): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6204): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6204): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6204): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6204): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6204): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6204): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6204): com.android.calendar: cancel(8) by com.android.calendar
,I/NotificationManager( 6204): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6204): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6204): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6204): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6204): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6204): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6204): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6204): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6204): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6204): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6204): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6204): com.android.calendar: cancel(20) by com.android.calendar
,I/ActivityManager(  945): Killing 6332:com.android.gallery3d/u0a23 (adj 15): empty #11
,D/AlertService( 6204): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
W/libprocessgroup(  945): failed to open /acct/uid_10023/pid_6332/cgroup.procs: No such file or directory
,D/AlarmScheduler( 6204): No events found starting within 1 week.
I/ActivityManager(  945): Killing 6204:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  945): failed to open /acct/uid_10013/pid_6204/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 6182): mConnectedToCar = false, abort
E/ActivityThread( 6182): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@32d403f2 that was originally bound here
E/ActivityThread( 6182): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@32d403f2 that was originally bound here
E/ActivityThread( 6182): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6182): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6182): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6182): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6182): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6182): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6182): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6182): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6182): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6182): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6182): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6182): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6182): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6182): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6182): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6182): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6182): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6182): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6182): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6182): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6182): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6182): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6182): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6182): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1132ecb5 that was originally bound here
E/ActivityThread( 6182): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1132ecb5 that was originally bound here
E/ActivityThread( 6182): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6182): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6182): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6182): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6182): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6182): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6182): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6182): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6182): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6182): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6182): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6182): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6182): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6182): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6182): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6182): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6182): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6182): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6182): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6182): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6182): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6182): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  945): Unbind failed: could not find connection for android.os.BinderProxy@18461921
I/ActivityManager(  945): Killing 6278:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  945): failed to open /acct/uid_10061/pid_6278/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,E/UEI.SmartControl( 6376): file observer is disposed!
,W/PackageSettings(  945): Skipping PackageSetting{1317943f com.example.hello/10317} due to missing metadata
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,D/UEI.SmartControl( 6376): Internal timer expired: 2
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ActivityManager(  945): Killing 6357:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  945): failed to open /acct/uid_10018/pid_6357/cgroup.procs: No such file or directory
,I/GAV2    ( 6480): Thread[GAThread,5,main]: No campaign data found.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/rmt_storage(  276): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  276): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  276): wakelock acquired: 1, error no: 42
,I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  276): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  276): 
I/rmt_storage(  276): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/AlarmManager(  945): RTC_WAKEUP set : Alarm{2630dbd2 type 0 when 1457378967635 com.android.vending} when 1457378967635
,W/ContextImpl( 3697): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 5659): [675] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5659): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 112888340333; DSPS: 3797785; Offset : -3024657578
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,I/MusicWidget( 2600): mDelayedStopHandler : unbind
,I/MusicBrowser( 2675): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2675): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2675): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2675): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2675): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2675): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2675): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2675): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  945):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3fa0cebcom.lge.music.MediaPlaybackService$6@a294a48
,D/MusicBrowser( 2675): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2675): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2675): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2675): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2675): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@2d30f356
,I/MusicBrowser( 2675): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2675): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2675): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2675): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2675): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2675): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2675): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2675): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2675): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2675): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2675): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2675): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2675): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2675): reset
,V/MediaPlayer[Native]( 2675): setListener
V/MediaPlayer[Native]( 2675): disconnect
V/MediaPlayer[Native]( 2675): destructor
,V/AudioFlinger(  284): releasing 19 from 2675 for -1
V/AudioFlinger(  284):  decremented refcount to 0
V/AudioFlinger(  284): purging stale effects
V/MediaPlayer[Native]( 2675): disconnect
D/MusicBrowser( 2675): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2675): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2675): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2675): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2675): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2675): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2675): [SmartShareManagerClient] unregisterListener: 602325217
W/SmartShareClient( 2675): [SmartShareManagerClient] unregisterListener invalid listener: 602325217
I/SmartShareClient( 2675): [SmartShareManagerClient] terminate service: 2675/MediaPlaybackService/824604716
E/HomeCloudIF( 2675): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2675): [SmartShareManagerClient] unbindService context:android.app.Application@270ade06
V/CloudHub( 2675): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
,V/CloudHub( 2675): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2675): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2675): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2675): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  945): Killing 6399:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/CloudHub( 2675): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29993
W/libprocessgroup(  945): failed to open /acct/uid_10069/pid_6399/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,I/CloudHub( 2675): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19952
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/charger_monitor(  492): init target 500000
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 293, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  945): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  300): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 132890663349; DSPS: 4453221; Offset : -3024653845
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
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
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  945): acquireWakeLockInternal: lock=1010025635, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=945
,D/WeatherService( 2656): 2 : TimeTick Intent has been received, Time(hour:min:sec) 20:30:0
D/WeatherService( 2656): 2 : TimeTick Intent And Screen On
D/WeatherService( 2656): 2 : SDK version : 21
W/ActivityManager(  945): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2656): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2656): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2656): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2656): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2656): 2 : This is isUpdating : false
D/WeatherService( 2656): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2656): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2656): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2656): 2 : Fixed theme : optimus
D/WeatherReflect( 2656): 2 : Map key string is -2
,D/lim     ( 2656): 2 : time = 20:30
I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/WeatherReflect( 2656): Model Name : LG-D722
D/WeatherTheme( 2656): 2 : Different view - status_min_formatted : 29 != 30
D/WeatherTheme( 2656): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2656): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,I/[SystemUI]Clock( 1374): called onTimeUpdated()
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
D/Theme   ( 2656): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2656): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/Weather4x2_optimus( 2656): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2656): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2656): forecast size is 0
D/Theme   ( 2656): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2656): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2656): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2656): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2656): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2656): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2656): setTouchIntent, appWidgetId: 2
,D/Theme_WeatherAncestor_optimus( 2656): url is : null
D/Theme   ( 2656): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2656): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2656): 2 : update view, appWidgetId: 2
D/WeatherService( 2656): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 20:30:0
D/PowerManagerServiceEx(  945): releaseWakeLockInternal: lock=1010025635 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,V/AlarmManager(  945): ELAPSED_WAKEUP set : Alarm{210693a0 type 2 when 139170 com.google.android.gms} when 139170
E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1733): Vacuum at: now=1457379000422 tag=VacuumService
,I/art     (  945): Explicit concurrent mark sweep GC freed 31382(1691KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.397ms total 147.766ms
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  945): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6639 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 6639): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6639): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@30c173df
I/ActivityManager(  945): Killing 6416:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  945): failed to open /acct/uid_10086/pid_6416/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,I/CloudHub( 2675): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
I/CloudHub( 2675): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  945): ALS enabled for SRE
D/PowerManagerServiceEx(  945): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (28293 ms ago)
,D/qdlights(  945): set_light_backlight: 253
,D/qdlights(  945): set_light_backlight: 249
,D/qdlights(  945): set_light_backlight: 246
,D/qdlights(  945): set_light_backlight: 243
,D/qdlights(  945): set_light_backlight: 239
,D/qdlights(  945): set_light_backlight: 236
,D/qdlights(  945): set_light_backlight: 233
,D/qdlights(  945): set_light_backlight: 229
,D/qdlights(  945): set_light_backlight: 226
,D/qdlights(  945): set_light_backlight: 223
,D/qdlights(  945): set_light_backlight: 219
,D/qdlights(  945): set_light_backlight: 216
,D/qdlights(  945): set_light_backlight: 213
,D/qdlights(  945): set_light_backlight: 209
,D/qdlights(  945): set_light_backlight: 206
,D/qdlights(  945): set_light_backlight: 203
,D/qdlights(  945): set_light_backlight: 199
,D/qdlights(  945): set_light_backlight: 196
,D/qdlights(  945): set_light_backlight: 193
,D/qdlights(  945): set_light_backlight: 189
,D/qdlights(  945): set_light_backlight: 186
,D/qdlights(  945): set_light_backlight: 183
,D/qdlights(  945): set_light_backlight: 179
,D/qdlights(  945): set_light_backlight: 176
,D/qdlights(  945): set_light_backlight: 173
,D/qdlights(  945): set_light_backlight: 169
,D/qdlights(  945): set_light_backlight: 166
,D/qdlights(  945): set_light_backlight: 163
,D/qdlights(  945): set_light_backlight: 159
,D/qdlights(  945): set_light_backlight: 156
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
D/qdlights(  945): set_light_backlight: 153
,D/qdlights(  945): set_light_backlight: 149
,D/qdlights(  945): set_light_backlight: 146
,D/qdlights(  945): set_light_backlight: 143
,D/qdlights(  945): set_light_backlight: 139
,D/qdlights(  945): set_light_backlight: 136
,D/qdlights(  945): set_light_backlight: 133
,D/qdlights(  945): set_light_backlight: 129
,D/qdlights(  945): set_light_backlight: 126
,D/qdlights(  945): set_light_backlight: 123
,D/qdlights(  945): set_light_backlight: 119
,D/qdlights(  945): set_light_backlight: 116
,D/qdlights(  945): set_light_backlight: 113
,D/qdlights(  945): set_light_backlight: 109
,D/qdlights(  945): set_light_backlight: 106
,D/qdlights(  945): set_light_backlight: 103
,D/qdlights(  945): set_light_backlight: 99
,D/qdlights(  945): set_light_backlight: 96
,D/qdlights(  945): set_light_backlight: 93
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  945): set_light_backlight: 89
,D/qdlights(  945): set_light_backlight: 86
,D/qdlights(  945): set_light_backlight: 83
,D/qdlights(  945): set_light_backlight: 79
,D/qdlights(  945): set_light_backlight: 76
,D/qdlights(  945): set_light_backlight: 73
,D/qdlights(  945): set_light_backlight: 69
,D/qdlights(  945): set_light_backlight: 66
,D/qdlights(  945): set_light_backlight: 63
,D/qdlights(  945): set_light_backlight: 59
,D/qdlights(  945): set_light_backlight: 56
,D/qdlights(  945): set_light_backlight: 53
,D/qdlights(  945): set_light_backlight: 49
,D/qdlights(  945): set_light_backlight: 46
,D/qdlights(  945): set_light_backlight: 43
,D/qdlights(  945): set_light_backlight: 39
,D/qdlights(  945): set_light_backlight: 36
,D/qdlights(  945): set_light_backlight: 33
,D/qdlights(  945): set_light_backlight: 29
,D/qdlights(  945): set_light_backlight: 26
,D/qdlights(  945): set_light_backlight: 23
,D/qdlights(  945): set_light_backlight: 19
,D/qdlights(  945): set_light_backlight: 16
,D/qdlights(  945): set_light_backlight: 13
,D/qdlights(  945): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 152892159705; DSPS: 5108630; Offset : -3024652721
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  945): ALS enabled for SRE
D/PowerManagerServiceEx(  945): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (35283 ms ago)
I/PowerManagerService(  945): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  945): ALS enabled for SRE
D/PowerManagerServiceEx(  945): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (35295 ms ago)
W/ContextImpl(  945): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  945): Sleeping (uid 1000)...
D/LPWGController(  945): [updateScreenState] screen on = false
D/LPWGController(  945): disable proximity sensor
D/LPWGController(  945): enable proximity sensor
I/SensorManager(  945): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@9968c91] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  945): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  945): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  945): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  945): activate: handle is 48, enable
V/sensors_hal_Ctx(  945): activate sensors is 1400000000000
D/sensors_hal_Thresh(  945): enable: handle=48
I/sensors_hal_SAM(  945): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  945): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  945): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  945): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  945): enable: Received response: 0
D/PowerManagerServiceEx(  945): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35328 ms ago)
I/Adreno-EGL(  945): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  945): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  945): Build Date: 03/02/15 Mon
I/Adreno-EGL(  945): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  945): Remote Branch: 
I/Adreno-EGL(  945): Local Patches: 
I/Adreno-EGL(  945): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1050 us)
,I/Sensors (  430): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  945): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  945): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  945): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  945): processInd: handle 48, count=1
V/sensors_hal_Thresh(  945): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  945): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  945): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  945): poll: count: 256
I/sensors_hal_Ctx(  945): poll: released wakelock sensor_ind
D/sensors_hal_Util(  945): waitForResponse: timeout=0
D/LPWGController(  945): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  945): current mode = 1  value = 1 1
I/LPWGController(  945): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  945): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  945): set_light_backlight: 0
,I/SensorManager(  945): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  945): activate: handle is 46, disable
V/sensors_hal_Ctx(  945): activate sensors is 1000000000000
D/sensors_hal_LP2(  945): enable: handle=46
D/sensors_hal_LP2(  945): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  945): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  945): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  945): Display changed displayId=0
V/sensors_hal_SAM(  945): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  945): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1751): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
,I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  945): Excessive delay in setPowerMode(): 207ms
I/QCOM PowerHAL(  945): Got set_interactive hint
,D/KeyguardViewMediator( 1374): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1330): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1374): notifyScreenOffLocked
D/SmartCoverViewMediator( 1330): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1330): handleNotifyScreenOFF
D/JX-Cordova( 4830): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4830): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4830): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cd28c89 added. We now have 3 listener(s)
,D/BluetoothManagerService(  945): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4830): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4830): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4830): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4830): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@376dc48e added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4830): addListener: New listener added - the number of listeners is now 1
D/KeyguardViewMediator( 1374): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/BluetoothAdapterService(223189361)( 2010): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@51512cf
D/KeyguardViewMediator( 1374): handleNotifyScreenOff
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4830): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4830): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4830): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4830): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
,W/System.err( 4830): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4830): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4830): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4830): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4830): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4830): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4830): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4830): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4830): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4830): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4830): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/ScreenTurnOffBySensor( 1374): unregisterProximitySensor
,D/StatusBarWindowView( 1374): onScreenTurnedOff why = 3
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/WifiServerServiceExt(  945): sendKtScanInterval  mRtspPlay : false
,V/AudioFlinger(  284): setParameters(): io 0, keyvalue screen_state=on, calling pid 945
D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=on
V/voice   (  284): voice_set_parameters: enter: screen_state=on
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: exit
V/voice   (  284): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  284): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  284): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  284): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  284): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  284): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  284): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
,I/WifiServerServiceExt(  945): set CMD_KT_SCAN_INTERVAL
D/GpsLocationProvider(  945): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/Sensors (  430): sns_pwr.c(301):releasing wakelock
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:true
,I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/LEDService( 1803): updateLightsLocked : turn off led
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/Cliptray Service( 1803): lockStatus = 0
D/LNfcService( 1786): action : android.intent.action.SCREEN_ON
,D/LEDHandler( 1803): RESTART MSG
D/NfcServiceNXP( 1786): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1786): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1786): isRequireNfcCRouting() return true
D/LNfcService( 1786): isHCERoutingtoHost() return : true
,D/NfcService( 1786): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): newParams.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): screenState= 3
D/NfcService( 1786): Discovery configuration equal, not updating.
D/SplitWindow(  945): check instance of lgWin Window{207d0664 u0 SearchPanel}
,D/InputDispatcher(  945): Window went away: Window{65eff9f u0 SearchPanel}
,I/[SystemUI]Clock( 1374): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1374): time changed, timezoneChanged : false
,D/Ulp_jni (  945): JNI:system_update. Event-0
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2656): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 20:30:18
,D/WeatherService( 2656): 2 : ACTION screen on
D/WeatherService( 2656): 2 : shouldTimeTickRegistered : false
,D/Weather_cast( 2656): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2656): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 20:30:18
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  945): ACTION_SCREEN_ON
,D/AppCleanupService( 4143): android.intent.action.SCREEN_ON
V/AudioFlinger(  284): setParameters(): io 0, keyvalue screen_state=off, calling pid 945
,D/audio_hw_primary(  284): adev_set_parameters: enter: screen_state=off
V/voice   (  284): voice_set_parameters: enter: screen_state=off
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  284): voice_extn_compress_voip_set_parameters: exit
V/voice   (  284): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  284): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  284): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  284): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  284): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  284): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  284): adev_set_parameters: exit with code(0)
D/WifiController(  945): CMD_SCREEN_OFF 
D/WifiController(  945): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  945): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1839): |CORE| sendScreenState: state:false
,I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1803): clear
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/LNfcService( 1786): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1786): mScreenState : 1, mInProvisionMode : false
I/LEDService( 1803): updateLightsLocked : turn on led
E/LEDService( 1803): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1803): Can't handle this request of patternId:0
D/LEDHandler( 1803): RESTART MSG
,I/[LGHome]EVENT( 1877): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2656): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 20:30:18
D/WeatherService( 2656): 2 : ACTION screen off
D/WeatherService( 2656): 2 : TimeTick Receiver Unregister
D/WeatherService( 2656): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 20:30:18
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  945): ACTION_SCREEN_OFF
D/AppCleanupService( 4143): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4143): AppUsageStatsSaveTask
E/NxpNfcJni( 1786): getReconnectState = 0x0
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
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
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1374): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  945): ELAPSED_WAKEUP set : Alarm{28660cd type 2 when 161163 com.android.systemui} when 161163
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1751): getCallState : 0
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1374): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1374): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 172894395606; DSPS: 5764065; Offset : -3024705742
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:31000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): init target 500000
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  945): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,V/AlarmManager(  945): ELAPSED_WAKEUP set : Alarm{3043dd82 type 2 when 187392 com.google.android.gms} when 187392
,I/PhenotypeConfigurator( 1733): Scheduling Phenotype for one-off execution 3275 seconds from now (1457379048813)
,I/PhenotypeFlagCommitter( 1733): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1733): Using platform SSLCertificateSocketFactory
D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 187895898213; DSPS: 6255632; Offset : -3024637227
,D/LocationManagerService(  945): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  278): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  278): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  278): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  278): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  278): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  278): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  278): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,D/LocationManagerService(  945): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  945): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  945): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/AlarmManager(  945): ELAPSED_WAKEUP set : Alarm{1be85083 type 2 when 190244 android} when 190244
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1733): disconnect managed GoogleApiClient
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 207898132803; DSPS: 6911063; Offset : -3024569569
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 222900475894; DSPS: 7402662; Offset : -3024637365
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 242902734560; DSPS: 8058097; Offset : -3024667518
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): init target 500000
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  945): battery changed pluggedType: 2
I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 262904484093; DSPS: 8713514; Offset : -3024657591
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 277906891391; DSPS: 9205112; Offset : -3024630585
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 295410685312; DSPS: 9778677; Offset : -3024651050
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/WifiController(  945): battery changed pluggedType: 2
,W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  945): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  945): battery changed pluggedType: 2
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 315412897160; DSPS: 10434110; Offset : -3024667114
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 330415166794; DSPS: 10925706; Offset : -3024716972
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/LocationManagerService(  945): remove 8be45e6
D/LocationManagerService(  945): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  945): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  945): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  945): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  945): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 347918576437; DSPS: 11499254; Offset : -3024603333
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  945): acquireWakeLockInternal: lock=1010025635, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=945
,V/AlarmManager(  945): RTC_WAKEUP set : Alarm{32c46200 type 0 when 1457379176453 com.google.android.gms} when 1457379176453
D/PowerManagerServiceEx(  945): releaseWakeLockInternal: lock=1010025635 [*alarm*], flags=0x0
,I/EventLogService( 4296): Aggregate from 1457378931968 (log), 1457377376373 (data)
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  945): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  945): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 362920807746; DSPS: 11990849; Offset : -3024660764
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  945): battery changed pluggedType: 2
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 382923130192; DSPS: 12646284; Offset : -3024627083
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 397925636629; DSPS: 13137887; Offset : -3024653788
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 415429098016; DSPS: 13711441; Offset : -3024671274
,I/ThermalEngine(  300): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  945): battery changed pluggedType: 2
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 435431693277; DSPS: 14366885; Offset : -3024639438
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 450434069303; DSPS: 14858483; Offset : -3024643810
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 464506629993; DSPS: 15319614; Offset : -3024684490
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 481866326020; DSPS: 15888462; Offset : -3024851691
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  945): battery changed pluggedType: 2
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 496870941183; DSPS: 16380117; Offset : -3024356715
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 510626822330; DSPS: 16830878; Offset : -3024609290
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 526882752185; DSPS: 17363547; Offset : -3024447308
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 540954308104; DSPS: 17824649; Offset : -3024607698
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  945): battery changed pluggedType: 2
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 554093300562; DSPS: 18255189; Offset : -3024653299
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 570974973952; DSPS: 18808372; Offset : -3024785433
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 585046459120; DSPS: 19269453; Offset : -3024375626
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 600057565786; DSPS: 19761355; Offset : -3024926624
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  945): battery changed pluggedType: 2
I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 614129357928; DSPS: 20222448; Offset : -3024576210
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
,I/[SystemUI]Clock( 1374): called onTimeUpdated()
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 629300679885; DSPS: 20719585; Offset : -3024671176
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 645556274408; DSPS: 21252261; Offset : -3025058410
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 660256984831; DSPS: 21733961; Offset : -3024665450
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  945): battery changed pluggedType: 2
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  945): tsOffsetIs: Apps: 675259397203; DSPS: 22225558; Offset : -3024602801
I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 690261601399; DSPS: 22717150; Offset : -3024595924
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 710263959144; DSPS: 23372591; Offset : -3024710101
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  945): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 730266168358; DSPS: 24028020; Offset : -3024606705
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 750268496944; DSPS: 24683457; Offset : -3024627919
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 770270750700; DSPS: 25338890; Offset : -3024601921
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  945): battery changed pluggedType: 2
I/art     ( 1733): Background sticky concurrent mark sweep GC freed 108803(5MB) AllocSpace objects, 14(224KB) LOS objects, 27% free, 16MB/23MB, paused 2.207ms total 116.503ms
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 790273150105; DSPS: 25994330; Offset : -3024643793
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 810275467235; DSPS: 26649766; Offset : -3024646075
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 830277683466; DSPS: 27305202; Offset : -3024749206
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  945): battery changed pluggedType: 2
I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 845279961932; DSPS: 27796793; Offset : -3024637176
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 865282143512; DSPS: 28452227; Offset : -3024714105
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 880284497732; DSPS: 28943822; Offset : -3024648782
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 900286776529; DSPS: 29599258; Offset : -3024689270
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  945): battery changed pluggedType: 2
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 920289033125; DSPS: 30254691; Offset : -3024660483
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 940291577103; DSPS: 30910135; Offset : -3024680006
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  945): acquireWakeLockInternal: lock=1010025635, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=945
,V/AlarmManager(  945): ELAPSED_WAKEUP set : Alarm{405f0f5 type 2 when 950536 com.android.bluetooth} when 950536
D/PowerManagerServiceEx(  945): releaseWakeLockInternal: lock=1010025635 [*alarm*], flags=0x0
,W/bt-smp  ( 2010): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2010): Plain text(LSB ~ MSB) = bd e4 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 2010): Encrypted text(LSB ~ MSB) = de bf 6b 75 27 80 60 7f 60 2a 95 1e ef 73 1b 2a 
W/bt-btm  ( 2010): Stopping oneshot timer
I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 960293856996; DSPS: 31565569; Offset : -3024658519
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
,I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  945): battery changed pluggedType: 2
I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 980296143023; DSPS: 32221003; Offset : -3024630663
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 1000298511988; DSPS: 32876441; Offset : -3024642042
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 1020300844568; DSPS: 33531878; Offset : -3024659393
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  945): acquireWakeLockInternal: lock=1010025635, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=945
,V/AlarmManager(  945): ELAPSED_WAKEUP set : Alarm{18706e8a type 2 when 1025971 android} when 1025971
D/PowerManagerServiceEx(  945): releaseWakeLockInternal: lock=1010025635 [*alarm*], flags=0x0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 1040303092090; DSPS: 34187313; Offset : -3024700638
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 1060305383492; DSPS: 34842746; Offset : -3024637020
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 1080307712673; DSPS: 35498184; Offset : -3024688183
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  945): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 1100310451258; DSPS: 36153633; Offset : -3024665455
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 1120312242337; DSPS: 36809052; Offset : -3024675121
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 1140314605482; DSPS: 37464489; Offset : -3024661907
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  945): battery changed pluggedType: 2
I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 1160316908473; DSPS: 38119924; Offset : -3024647683
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 1180319290699; DSPS: 38775363; Offset : -3024676215
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 1200321609151; DSPS: 39430798; Offset : -3024646686
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 1220323901226; DSPS: 40086233; Offset : -3024643377
,I/UsageStatsService(  945): User[0] Flushing usage stats to disk
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 1240326288046; DSPS: 40741673; Offset : -3024698067
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 1260328539239; DSPS: 41397105; Offset : -3024644166
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  492): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2010): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
I/QCNEJ   ( 1839): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1839): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  945): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  945): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  945): battery changed pluggedType: 2
I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  945): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  945): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  945): tsOffsetIs: Apps: 1280330828015; DSPS: 42052540; Offset : -3024644157
,I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
,TIME-OUT KILL (timeout was 1200000ms),I/ThermalEngine(  300): Sensor:pa_therm0:27000 mC
D/AndroidRuntime( 7008): 
D/AndroidRuntime( 7008): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 7008): CheckJNI is OFF
D/AndroidRuntime( 7008): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  945): Force stopping com.test.thalitest appid=10316 user=-1: uninstall pkg
I/ActivityManager(  945): Killing 4830:com.test.thalitest/u0a316 (adj 0): stop com.test.thalitest
I/WindowState(  945): WIN DEATH: Window{218aede0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  945): Focus left window: Window{218aede0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
D/InputDispatcher(  945): Window went away: Window{218aede0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/PackageSettings(  945): Skipping PackageSetting{1317943f com.example.hello/10317} due to missing metadata
I/ActivityManager(  945):   Force finishing activity ActivityRecord{273e6ddd u0 com.test.thalitest/.MainActivity t224}
V/ActivityManager(  945): Display changed displayId=0
D/DSDPConnection( 1751): Display #0 changed.
W/ActivityManager(  945): Spurious death for ProcessRecord{32494cfb 4830:com.test.thalitest/u0a316}, curProc for 4830: null
I/ActivityManager(  945): Force stopping com.test.thalitest appid=10316 user=0: pkg removed
I/ActivityManager(  945):   Force finishing activity ActivityRecord{273e6ddd u0 com.test.thalitest/.MainActivity t224 f}
W/ActivityManager(  945): Duplicate finish request for ActivityRecord{273e6ddd u0 com.test.thalitest/.MainActivity t224 f}
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/InputReader(  945): Reconfiguring input devices.  changes=0x00000010
I/art     ( 4296): Explicit concurrent mark sweep GC freed 5991(326KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 14MB/19MB, paused 780us total 93.654ms
I/QCNEJ   ( 1839): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/art     ( 1939): Explicit concurrent mark sweep GC freed 22181(1384KB) AllocSpace objects, 3(71KB) LOS objects, 40% free, 12MB/21MB, paused 2.115ms total 110.926ms
W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
W/System.err( 3697): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/System.err( 3697): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
W/System.err( 3697): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 3697): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
W/System.err( 3697): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 3697): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 3697): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 3697): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 3697): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 3697): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 3697): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 3697): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/ActivityManager(  945): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7040 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/[LGHome]EVENT( 1877): [Launcher.java:5203:onStart()]onStart
I/[LGHome]EVENT( 1877): [Launcher.java:776:onResume()]onResume
I/ActivityManager(  945): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7056 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1877): [LauncherModel.java:1353:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:1470:loadAndBindWorkspace()]loadAndBindWorkspace=2ms
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_REMOVED
I/[LGHome]LGActivityUtil( 1877): [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/[LGHome]EVENT( 1877): [Launcher.java:929:onResume()]onResume end
I/Activity( 1877): Activity.onPostResume() called 
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
I/art     (  945): Explicit concurrent mark sweep GC freed 54539(3MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 23MB/34MB, paused 2.372ms total 262.131ms
I/art     (  945): WaitForGcToComplete blocked for 216.488ms for cause Explicit
W/[LGHome]LGWallpaperInfo( 1877): [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
D/WallpaperManager( 1877): suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
W/ResourcesManager( 7040): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 7040): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
D/KeyguardModel( 1374): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/WindowManager(  945): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
I/SystemUI[Framework](  945): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
I/[SystemUI]NavigationThemeResource( 1374): notify navigation bar color(0x0)
W/PhoneWindowManagerEx(  945): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  945): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  945): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  945): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@29eb66e9,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  945): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
D/InputDispatcher(  945): Focus entered window: Window{186df462 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/administrator(  945): Handling package changes for user 0
I/LockScreenSettings( 7056): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
W/ResourcesManager( 7040): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PhoneWindow( 1877): [setNavigationBarColor] color=0x 0
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
W/InputMethodManagerService(  945): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
W/InputMethodManagerService(  945): Got RemoteException sending setActive(false) notification to pid 4830 uid 10316
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): handleShortcutListChanged...
D/KeyguardModel( 1374): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1374): createShortcutInfo...
D/KeyguardModel( 1374): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.mms: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
D/KeyguardModel( 1374): package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
D/KeyguardModel( 1374): createShortcutInfo...
W/ResourceType( 1374): No package identifier when getting value for resource number 0x00000000
W/PackageManager( 1374): Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
D/KeyguardModel( 1374): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1374): createShortcutInfo...
I/ActivityManager(  945): Killing 6182:com.google.android.gms:car/u0a6 (adj 15): empty #11
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2231:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/NotificationService(  945): action=android.intent.action.PACKAGE_REMOVED queryReplace=false
D/BackupManagerService(  945): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService(  945): Receieved: android.intent.action.PACKAGE_REMOVED
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
D/KeyguardModel( 1374): handleShortcutListChanged...
W/libprocessgroup(  945): failed to open /acct/uid_10006/pid_6182/cgroup.procs: No such file or directory
D/TaskPersister(  945): removeObsoleteFile: deleting file=224_task.xml
I/Timeline(  945): Timeline: Activity_windows_visible id: ActivityRecord{164c5813 u0 com.lge.launcher2/.Launcher t223} time:1292948
W/IInputConnectionWrapper( 1877): getTextBeforeCursor on inactive InputConnection
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2245:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1877): [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
E/b       ( 1606): Unable to connect to the editor to retrieve text... will retry later
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf74 "0.6f" a=5 r=0x7f0c017c}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7c "0.72f" a=5 r=0x7f0c017d}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c017e}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf76 "0.3f" a=5 r=0x7f0c017f}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf77 "0.7f" a=5 r=0x7f0c0180}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0181}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7e "0.70f" a=5 r=0x7f0c0182}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7f "0.30f" a=5 r=0x7f0c0183}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf7d "0.28f" a=5 r=0x7f0c0184}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0185}
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf6e "0.5f" a=5 r=0x7f0c0186}
I/art     (  945): Explicit concurrent mark sweep GC freed 6516(366KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 3.167ms total 368.608ms
W/Resources( 1877): Converting to float: TypedValue{t=0x3/d=0xf75 "0.4f" a=5 r=0x7f0c0187}
I/LGEmail ( 7040): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 7040): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
D/AndroidRuntime( 7008): Shutting down VM
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/PackageChangeReceiver( 7040): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 1 [0, 0]
I/[LGHome]Launcher.Model( 1877): [LauncherModel.java:2257:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
W/IInputConnectionWrapper( 1877): getTextAfterCursor on inactive InputConnection
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
I/ActivityManager(  945): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7083 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [FM Radio] in screen 2 [1, 4]
I/ActivityManager(  945): Killing 6480:com.google.android.gm/u0a53 (adj 15): empty #11
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [QuickRemote] in screen 2 [3, 4]
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add Shortcut [Calendar] in screen 2 [4, 4]
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
W/libprocessgroup(  945): failed to open /acct/uid_10053/pid_6480/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 7083): onCreate
W/AppUp4:DB( 7083):  [AppBoxDatabaseHelper] construct
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/AppUp4:DB( 7083):  setFingerPrint start
I/AppUp4:DB( 7083):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
I/[LGHome]EVENT( 1877): [Workspace.java:917:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
I/AppUp4:DB( 7083):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 7083):  SDK version = 0
I/AppUp4:DB( 7083):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 7083): AppBoxApplication onCreate()
D/AppUp4:PreloadHelper( 7083): added Exclude : com.test.thalitest
I/Timeline( 1877): Timeline: Activity_idle id: android.os.BinderProxy@3e7c1cab time:1293539
I/ActivityManager(  945): Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7102 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  945): Killing 6545:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/art     ( 1877): Explicit concurrent mark sweep GC freed 31259(1711KB) AllocSpace objects, 22(2MB) LOS objects, 39% free, 15MB/25MB, paused 1.249ms total 63.819ms
W/libprocessgroup(  945): failed to open /acct/uid_10014/pid_6545/cgroup.procs: No such file or directory

```
