#### Test 616581981d889bb_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
,I/MusicStore( 4782): Database version: 120
--------- beginning of system
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4782): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4782): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4782): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 4782): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4782): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 4782): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ActivityThread( 4782): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4782): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@369d4763: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4782): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4782): GMSCore installation verified
I/ConfigStore( 4782): Config Database version: 1
D/AndroidRuntime( 4814): 
D/AndroidRuntime( 4814): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4814): CheckJNI is OFF
I/MediaRouter( 4782): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
V/MusicLeanback( 4782): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 4782): type=WIFI subType= reason=null isConnected=true
I/NetworkMonitor( 4782): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  857): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=4831 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
I/GHttpClientFactory( 4782): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 4782): Using platform SSLCertificateSocketFactory
D/AndroidRuntime( 4814): Calling main entry com.android.commands.am.Am
I/ActivityManager(  857): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
W/ResourcesManager( 4831): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4831): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4831): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/ActivityManager(  857): setTaskToReturnTo : TaskRecord{2e924faf #224 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  857): setTaskToReturnTo : TaskRecord{2e924faf #224 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  857): AppWindowTokenEx init.. 
D/ContextHelper(  857): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
D/InputDispatcher(  857): Focus left window: Window{23a79162 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 4814): Shutting down VM
I/PhoneWindow(  857): [generateLayout] setColorNavigationBar => color=0x ff000001
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
I/ActivityManager(  857): Killing 4590:com.lge.qmemoplus/1000 (adj 15): empty #11
D/PhoneWindowEx(  857): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  857): [setNavigationBarColor2] color=0x fff5f5f5
D/SplitWindow(  857): check instance of lgWin Window{c7685a7 u0 Starting com.test.thalitest}
I/ActivityManager(  857): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4858 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/libprocessgroup(  857): failed to open /acct/uid_1000/pid_4590/cgroup.procs: No such file or directory
I/NotificationManager( 4782): com.google.android.music: cancel(1061) by com.google.android.music
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/LGEmail ( 4831): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
D/LGEmail ( 4831): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/WindowStateAnimator(  857): Starting window displayed
I/HotwordDetector( 1945): Closing mic
D/WindowManager(  857): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
,I/SystemUI[Framework](  857): PhoneWindowManager.updateSystemUiVisibilityLw() :win == null
W/PhoneWindowManagerEx(  857): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  857): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  857): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  857): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3a5b2ac3,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  857): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1373): notify navigation bar color(0xfff5f5f5)
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/MicrophoneInputStream( 1945): mic_close com.google.android.apps.gsa.speech.audio.u@97c0eee
V/AudioRecord( 1945): stop()
D/AudioRecord( 1945): AudioRecord->stop()
V/AudioFlinger(  276): RecordHandle::stop()
V/AudioFlinger(  276): RecordThread::stop
,V/AudioFlinger(  276): Record stopped OK
,V/AudioPolicyManager(  276): stopInput() input 17
V/AudioPolicyService(  276): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  276): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  276): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  276): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  276): ThreadBase::setParameters() routing=0
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb4393000
D/audio_hw_primary(  276): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  276): stop_input_stream: enter: usecase(7: audio-record)
,V/audio_hw_primary(  276): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  276): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  276): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  276): disable_audio_route: exit
E/audio_hw_primary(  276): disable_snd_device: enter 144
D/hardware_info(  276): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  276): disable_snd_device: snd_device(144: lg-vr-handset-mic)
D/ContextHelper( 4858): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
V/audio_hw_primary(  276): stop_input_stream: exit: status(0)
V/audio_hw_primary(  276): in_standby: exit:  status(0)
V/AudioFlinger(  276): RecordThread: loop stopping
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioPolicyManager(  276): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  276): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  276): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  276): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioPolicyService(  276): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  276): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  276): setParameters(): io 17, keyvalue hotword_active=0, calling pid 276
V/AudioFlinger(  276): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  276): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  276): RecordThread: loop starting
V/AudioFlinger(  276): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  276): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  276): in_set_parameters: exit: status(0)
V/AudioFlinger(  276): processConfigEvents_l() DONE thread 0xb4393000
V/AudioFlinger(  276): RecordThread: loop stopping
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioRecord( 1945): stop()
,V/AudioRecord( 1945): stop()
V/AudioRecord( 1945): stop()
V/AudioFlinger(  276): RecordHandle::stop()
V/AudioFlinger(  276): RecordThread::stop
V/AudioPolicyManager(  276): releaseInput() 17
V/AudioPolicyManager(  276): closeInput(17)
V/AudioFlinger(  276): closeInput() 17
V/AudioSystem(  276): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  857): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1751): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  276): ThreadBase::exit
V/AudioSystem( 1373): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1994): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  276): RecordThread: loop starting
V/AudioSystem( 1945): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  276): RecordThread 0xb4393000 exiting
V/AudioSystem( 3142): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  276): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  276): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/AudioSystem( 2721): ioConfigChanged() event 4, ioHandle 17
V/audio_hw_primary(  276): in_standby: exit:  status(0)
V/AudioPolicyService(  276): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  276): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  276): AudioCommandThread() waking up
V/AudioPolicyService(  276): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  276): AudioCommandThread() going to sleep
V/AudioFlinger(  276): releasing 16 from 1945 for -1
V/AudioFlinger(  276):  decremented refcount to 0
V/AudioFlinger(  276): purging stale effects
V/AudioPolicyManager(  276): releaseInput() exit
V/AudioFlinger(  276): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  276): removeClient_l() pid 1945, calling pid 276
I/HotwordRecognitionRnr( 1945): Stopping hotword detection.
,I/HotwordRecognitionRnr( 1945): Hotword detection finished
,I/WebViewFactory( 4858): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 4858): Time to load native libraries: 1 ms (timestamps 418-419)
I/LibraryLoader( 4858): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 4858): Binding Chromium to main looper Looper (main, tid 1) {1c8c2d17}
,I/LibraryLoader( 4858): Expected native library version number "",actual native library version number ""
I/chromium( 4858): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4858): Initializing chromium process, singleProcess=true
W/art     ( 4858): Attempt to remove local handle scope entry from IRT, ignoring
,D/eas_req ( 4831): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
E/SysUtils( 4858): ApplicationContext is null in ApplicationStatus
D/LGDMClient( 4620): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4620): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4620): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4620): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 4620): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 4620): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4620): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4620): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,W/chromium( 4858): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4858): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4858): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/HubEmail( 4831): JNI_OnLoad()
I/HubEmail( 4831): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4831): registerNatives()
I/HubEmail( 4831): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4831): registerNativeMethods()
I/HubEmail( 4831): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 4831): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,I/Adreno-EGL( 4858): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4858): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4858): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4858): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4858): Remote Branch: 
I/Adreno-EGL( 4858): Local Patches: 
I/Adreno-EGL( 4858): Reconstruct Branch: 
I/ActivityManager(  857): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=4888 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ContextImpl( 4620): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 4620): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
W/Settings( 4831): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/LGDMClient( 4620): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 4620): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,D/LGDMClient( 4620): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 4620): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  857): Killing 3340:com.android.defcontainer/u0a4 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10004/pid_3340/cgroup.procs: No such file or directory
,V/AudioPolicyService(  276): registerClient() client 0xb4027340, uid 10316
,I/AppUp4:AppBoxCP( 4888): onCreate
D/BluetoothManagerService(  857): Message: 20
D/BluetoothManagerService(  857): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@342a2a52:true
W/AppUp4:DB( 4888):  [AppBoxDatabaseHelper] construct
D/BluetoothAdapterService(192408866)( 1994): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3ad2da88
,I/AppUp4:DB( 4888):  setFingerPrint start
,I/AppUp4:DB( 4888):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 4888):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4888):  SDK version = 0
I/AppUp4:DB( 4888):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 4888): AppBoxApplication onCreate()
,I/NetworkStateForAutoUpdateMonitor( 4888): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4888): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4888): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 4888): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 4888): onReceive
I/AppUp4:CustModeStarterReceiver( 4888): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 4888): Context : android.app.ReceiverRestrictedContext@1c8c2d17
D/AppUp4:CustFacade( 4888): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4888): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 4888): begin check event
I/AppUp4:CustModeStarterReceiver( 4888): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4888): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4888): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 4888): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 4888): handleAsyncCustNotification do not startCustService
,I/LgeMiscReceiver( 3142): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3142): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3142): networkInfo.isConnected() = true
D/PhoneState( 3142): setPdpRejectCasuse : false
,I/ActivityManager(  857): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=4921 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,W/art     ( 4858): Attempt to remove local handle scope entry from IRT, ignoring
W/AwContents( 4858): onDetachedFromWindow called when already detached. Ignoring
,I/PhoneWindow( 4858): [generateLayout] setColorNavigationBar => color=0x ff000001
,D/PhoneWindowEx( 4858): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 4858): [setNavigationBarColor2] color=0x fff5f5f5
D/SystemWebViewEngine( 4858): CordovaWebView is running on device made by: LGE
,W/art     ( 4858): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4858): Attempt to remove local handle scope entry from IRT, ignoring
I/Activity( 4858): Activity.onPostResume() called 
D/PhoneMonitor( 4921): Register our PhoneStateListener
,D/OpenGLRenderer( 4858): Render dirty regions requested: true
I/OpenGLRenderer( 4858): Initialized EGL, version 1.4
D/OpenGLRenderer( 4858): Enabling debug mode 0
D/Atlas   ( 4858): Validating map...
,D/MobileConnectivityChangeReceiver( 4921): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4921): onReceive CONNECTIVITY_CHANGE networkType=1
D/SplitWindow(  857): check instance of lgWin Window{14610505 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  857): Killing 4758:com.lge.bnr/1000 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_1000/pid_4758/cgroup.procs: No such file or directory
,W/chromium( 4858): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
I/ActivityManager(  857): Killing 4701:com.android.settings/1000 (adj 15): empty #11
V/DownloadManager( 3196): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,W/libprocessgroup(  857): failed to open /acct/uid_1000/pid_4701/cgroup.procs: No such file or directory
,V/DownloadManager( 3196): DownloadService onCreate
I/NotificationManager( 3196): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3196): in removeSpuriousFiles
V/DownloadManager( 3196): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3196): created cursor android.database.sqlite.SQLiteCursor@1f5c3d0 on behalf of 3196
D/PhoneMonitor( 4921): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 4921): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 4921): [parse] Load xml
I/DownloadManager( 3196): in trimDatabase
V/DownloadManager( 3196): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3196): created cursor android.database.sqlite.SQLiteCursor@31486ce on behalf of 3196
V/TelephonyAutoProfiling( 4921): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 4921): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/InputDispatcher(  857): Focus entered window: Window{14610505 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/ActivityManager(  857): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4953 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3196): DownloadService onStartCommand
I/CheckinService( 4317): Checkin interval check for package: unspecified last checkin: 1457131490183 min interval config: 0 actual interval: 6952369
,V/DownloadManager( 3196): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3196): created cursor android.database.sqlite.SQLiteCursor@1abb4cfc on behalf of 3196
D/PhoneMonitor( 4921): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
W/InputMethodManagerService(  857): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  857): Displayed com.test.thalitest/.MainActivity: +1s210ms
I/Timeline(  857): Timeline: Activity_windows_visible id: ActivityRecord{38ed6fbc u0 com.test.thalitest/.MainActivity t224} time:71235
I/CheckinService( 4317): Checking schedule, now: 1457138442633 next: 1457131520143
I/CheckinService( 4317): active receiver: enabled
I/Timeline( 4858): Timeline: Activity_idle id: android.os.BinderProxy@27adbe59 time:71250
,V/DownloadManager( 3196): DownloadService onDestroy
,I/CheckinService( 4317): Preparing to send checkin request
I/EventLogService( 4317): Accumulating logs since 1457137596386
D/DrmBroadcastReceiver( 4953): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 4953): 1  network is available. Sync DRM Time with NTP
W/BindingManager( 4858): Cannot call determinedVisibility() - never saw a connection for the pid: 4858
D/WeatherAncestor( 2712): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:40:42
D/UpdateThreadPoolManager( 2712): 2 : This is isUpdating : false
V/DrmService( 4953): Service onCreate
D/DrmService( 4953): Received new request = 2
D/WeatherAncestor( 2712): connectivity changed - connection : true
,D/Weather_cast( 2712): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2712): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 1:40:42
I/DrmSntpClient( 4953): Start Sync process
D/DrmSntpClient( 4953): Server : 0
D/WeatherService( 2712): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd( 4953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4953): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4953): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  272): App 10051 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  857): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=4986 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  857): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2712): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2712): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2712): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 4986): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 4953): propertyValue:false
,I/LGDrmClient( 4953): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  288): eDRM_SetDRMTime +++
D/JsMessageQueue( 4858): Set native->JS mode to OnlineEventsBridgeMode
I/LGDRM   (  288): [DRM] SET TIME : YR=2016, MON=3, DAY=5
I/LGDRM   (  288): [DRM] SET TIME : HR=0, MIN=40, SEC=41
,V/ILGDrmService(  288): eDRM_SetDRMTime ---
,I/DrmSntpClient( 4953): Synched
D/DrmService( 4953): Completed !! request = 2
D/DrmService( 4953): Request count = 0
V/DrmService( 4953): Service onDestroy
I/CheckinRequestBuilder( 4317): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4317): Failed to find provider info for com.google.android.wearable.settings
,I/art     ( 4024): Explicit concurrent mark sweep GC freed 2533(101KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 703us total 47.812ms
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  857): Waited long enough for: ServiceRecord{2fc72b6c u0 com.lge.springcleaning/.service.AppCleanupService}
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Babel_SMS( 4986): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4986): MmsConfig.loadMmsSettings
,I/Babel_SMS( 4986): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4986): MmsConfig.loadFromDatabase
,E/Babel_SMS( 4986): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4986): MmsConfig.loadFromResources
E/Babel_SMS( 4986): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 4986): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/art     ( 4986): CheckpointMarkThreadRoots callback created = 0xb042d870
,D/jxcore_app_log( 4858): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426134912
I/ActivityManager(  857): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5016 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4858): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4858):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4858):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4858):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4858):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4858): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e7dd793 added. We now have 1 listener(s)
I/art     ( 4986): CheckpointMarkThreadRoots callback created = 0xb042d860
D/UEI.SmartControl( 4666): Internal timer expired: 1
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4858): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4858):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4858):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4858):     - Bluetooth MAC address: F8:95:C7:87:85:54
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4858):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4858):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4858):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4858):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4858):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4858):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4858): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@31486ce added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4858): addListener: New listener added - the number of listeners is now 1
W/art     ( 4986): Suspending all threads took: 5.058ms
D/SensorManager( 4986): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4986): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4986): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 4986): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4986): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 4986): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4986): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 4986): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4986): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4986): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4986): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4986): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4986): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4986): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4986): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4986): found sensor: Motion Accel, handle=46
,D/BluetoothAdapterService(192408866)( 1994): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3ad2da88
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4858): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4858): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4858): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4858): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4858): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4858): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4858): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4858): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4858): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4858): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4858): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4858): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4858): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4858): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4858): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ActivityManager(  857): Process com.lge.qremote (pid 4644) has died
D/JX-Cordova( 4858): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4858): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4858): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@222459ef added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4858): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4858): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1abb4cfc added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4858): addListener: New listener added - the number of listeners is now 1
,D/BluetoothAdapterService(192408866)( 1994): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3ad2da88
D/UEI.SmartControl( 4666): Service.onUnbind: IControl
D/UEI.SmartControl( 4666): Service.onDestroy
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4858): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
D/UEI.SmartControl( 4666): Shutdown IRRCPlayer... 
W/System.err( 4858): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4858): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4858): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4858): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4858): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4858): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4858): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4858): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4858): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4858): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4858): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4858): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4858): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4858): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/irrc_jni( 4666): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 4666): ~IrrcClient ++ 
D/irrcClient( 4666): ~IrrcClient -- 
W/irrc_jni( 4666): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 4666): Blaster closed
D/UEI.SmartControl( 4666): Blaster closed
D/UEI.SmartControl( 4666): Shut down QS...
D/UEI.SmartControl( 4666): Stopped file observer...
I/UEI.SmartControl( 4666): QS lib stop result = true
D/UEI.SmartControl( 4666): QS shutdown complete
W/Settings( 4986): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 4986): startup - clean
W/ResourcesManager( 5016): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5016): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/Babel   ( 4986): deleted: false for 0
,I/MultiDex( 5016): VM with version 2.1.0 has multidex support
I/MultiDex( 5016): install
I/MultiDex( 5016): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  857): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5040 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 4986): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 4986): Unsupported mime audio/adpcm
W/AudioCapabilities( 4986): Unsupported mime audio/g726
W/AudioCapabilities( 4986): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4986): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4986): Unsupported mime video/mjpg
V/JNIHelp ( 5016): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/VideoCapabilities( 4986): Unsupported mime video/theora
W/AudioCapabilities( 4986): Unsupported mime audio/evrc
,W/AudioCapabilities( 4986): Unsupported mime audio/qcelp
W/VideoCapabilities( 4986): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 4986): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 4986): Unsupported mime audio/qcelp
W/AudioCapabilities( 4986): Unsupported mime audio/evrc
,W/VideoCapabilities( 4986): Unsupported mime video/mp4v-esdp
,W/ActivityThread( 5016): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5016): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1dee3ce8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5016): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5016): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5016): com.google.android.gms: cancel(39789) by com.google.android.gms
I/VideoCapabilities( 4986): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 4986): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4986): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4986): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 4986): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 4986): onServiceConnected
W/Babel   ( 4986): Attempted to change video mute state without an active call.
,I/NotificationManager( 4986): com.google.android.talk: cancel(10436) by com.google.android.talk
I/art     ( 5016): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5016): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  857): Process com.uei.lg.quicksetsdk.lite (pid 4666) has died
,D/libc-netbsd( 4986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4986): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4986): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  272): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 4986): propertyValue:false
D/NativeLibraryUtils( 5016): Install completed successfully. count=14 extracted=0
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,I/Babel   ( 4986): connection state changed from UNKNOWN to CONNECTED
W/ContextImpl( 5040): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5040): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5040): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5040): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 5040): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5040):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5040):   adb logcat -s GAv4
,D/WVCdm   (  276): Instantiating CDM.
,I/WVCdm   (  276): CdmEngine::OpenSession
I/WVCdm   (  276): Level3 Library Dec 11 2014 16:13:16
I/ActivityManager(  857): Process com.google.android.music:main (pid 4782) has died
,W/WVCdm   (  276): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  276): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  276): L1 library not specified. Falling Back to L3
W/GAv4    ( 5040): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 72878195758; DSPS: 2486597; Offset : -3018672243
,W/GAv4    ( 5040): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  276): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  276): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
W/GAv4    ( 5040): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/WVCdm   (  276): PrepareKeyRequest: nonce=3472395647
I/art     (  857): Explicit concurrent mark sweep GC freed 27332(1417KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 3.851ms total 180.605ms
,I/WebViewFactory( 5040): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5040): Time to load native libraries: 2 ms (timestamps 3258-3260)
I/LibraryLoader( 5040): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5040): Binding Chromium to main looper Looper (main, tid 1) {2a9eb018}
I/LibraryLoader( 5040): Expected native library version number "",actual native library version number ""
I/chromium( 5040): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5040): Initializing chromium process, singleProcess=true
W/art     ( 5040): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5040): ApplicationContext is null in ApplicationStatus
I/art     ( 5016): CheckpointMarkThreadRoots callback created = 0xb04d3ec0
,W/chromium( 5040): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5040): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5040): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5040): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5040): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5040): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5040): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5040): Remote Branch: 
I/Adreno-EGL( 5040): Local Patches: 
I/Adreno-EGL( 5040): Reconstruct Branch: 
I/art     ( 5016): CheckpointMarkThreadRoots callback created = 0xb04d3eb0
,V/AudioPolicyService(  276): registerClient() client 0xb4027840, uid 10079
,W/AudioManagerAndroid( 5040): Requires BLUETOOTH permission
I/NSApplication( 5040): Starting up...
I/dex2oat ( 5091): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ActivityManager(  857): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5106 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/dex2oat ( 5091): dex2oat took 114.821ms (threads: 4)
,I/Adreno-EGL( 5016): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5016): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5016): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5016): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5016): Remote Branch: 
I/Adreno-EGL( 5016): Local Patches: 
I/Adreno-EGL( 5016): Reconstruct Branch: 
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/InputReader(  857): Reconfiguring input devices.  changes=0x00000010
D/administrator(  857): Handling package changes for user 0
,I/art     ( 1787): CheckpointMarkThreadRoots callback created = 0xb042d360
,I/Adreno-EGL( 5016): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5016): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5016): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5016): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5016): Remote Branch: 
I/Adreno-EGL( 5016): Local Patches: 
I/Adreno-EGL( 5016): Reconstruct Branch: 
,I/art     ( 1787): CheckpointMarkThreadRoots callback created = 0xaaf4a560
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/art     ( 1787): Background partial concurrent mark sweep GC freed 53362(3MB) AllocSpace objects, 0(0B) LOS objects, 39% free, 9MB/15MB, paused 8.910ms total 112.467ms
I/NotificationService(  857): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  857): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  857): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/ActivityManager(  857): Process com.lge.email (pid 4831) has died
,I/BackupManagerService(  857): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  857): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  857): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1360ee00
I/Adreno-EGL( 5016): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5016): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5016): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5016): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5016): Remote Branch: 
I/Adreno-EGL( 5016): Local Patches: 
I/Adreno-EGL( 5016): Reconstruct Branch: 
,W/ResourcesManager(  857): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  857): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5129 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 22.682ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.635ms
,W/ResourceType(  857): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.560ms
,I/ActivityManager(  857): Process com.lge.lgdmsclient (pid 4620) has died
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
W/ResourcesManager( 5129): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/LocationProviderProxy(  857): applying state to connected service
,I/ActivityManager(  857): Process com.lge.sync (pid 4726) has died
,I/ActivityManager(  857): Process com.lge.appbox.client (pid 4888) has died
,I/iu.SyncManager( 4317): SYNC; picasa accounts
,I/CheckinRequestBuilder( 4317): Classify the device as Phone.
D/NetworkLogImpl( 4317): Loaded NetworkSpeedPredictor
,I/iu.Environment( 4317): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 4317): num queued entries: 0
I/iu.UploadsManager( 4317): num updated entries: 0
I/iu.SyncManager( 4317): NEXT; no task
I/ActivityManager(  857): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5159 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/libc-netbsd( 4317): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4317): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4317): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4317): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  272): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 4317): propertyValue:false
W/ResourcesManager( 5159): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/BluetoothManagerService(  857): Message: 20
D/BluetoothManagerService(  857): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@316e6778:true
,D/BluetoothAdapterService(192408866)( 1994): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3ad2da88
,D/BluetoothAdapterService(192408866)( 1994): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3ad2da88
D/libc-netbsd( 4317): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4317): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  857): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=5182 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
I/WVCdm   (  276): CdmEngine::CloseSession
I/WVCdm   (  276): L3 Terminate.
,D/libc-netbsd( 4317): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4317): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4317): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4317): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4317): Sending checkin request (7752 bytes)
,I/DigitalAppWidgetProvider( 5182): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 2712): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 1:40:46
D/UpdateThreadPoolManager( 2712): 2 : This is isUpdating : false
,D/Weather_cast( 2712): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2712): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 1:40:46
D/WeatherService( 2712): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
W/ActivityManager(  857): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2712): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2712): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2712): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,V/SmsReceiverService( 3142): onStart: #1 mResultCode: -1 = Activity.RESULT_OK
,D/MmsConfig( 3142): isNotAllowedSms: currentUser:0
D/MmsConfig( 3142): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3142): isUserMode:false
D/SmsReceiverService( 3142): handleMessage isUserMode:false
V/AlarmManager(  857): RTC_WAKEUP set : Alarm{2ecb8842 type 0 when 1457138446625 com.google.android.googlequicksearchbox} when 1457138446625
V/SmsReceiverService( 3142): handleMessage action: com.android.mms.transaction.SEND_MESSAGE error: 0
,D/SmsReceiverService( 3142): [LGE] handleSendMessage Send messages in queue
,I/[LGHome]LGNumberBadgeReceiver( 1877): [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = lge.intent.action.UNREAD_MESSAGES
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1877): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1877): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1877): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1877): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,I/ActivityManager(  857): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=5207 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,W/ResourcesManager( 5207): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5207): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5207): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5207): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5207): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/IndexDatabaseHelper( 5207): Using schema version: 115
,I/IndexDatabaseHelper( 5207): Index is fine
I/CheckinRequestBuilder( 4317): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4317): Failed to find provider info for com.google.android.wearable.settings
,D/UsbSettingsReceiver( 5207): [AUTORUN] onReceive() : action = android.hardware.usb.action.USB_STATE
,D/UsbSettingsReceiver( 5207): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5207): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5207): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5207): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/CheckinRequestBuilder( 4317): Classify the device as Phone.
D/UsbSettingsReceiver( 5207): [AUTORUN] onReceive() : getDefaultFunction = ptp_only
,D/UsbSettingsReceiver( 5207): [AUTORUN] onReceive() : USB_FUNCTION_CDROM_STORAGE = false
D/UsbSettingsReceiver( 5207): [AUTORUN] onReceive() : mDirectAutorun = true
D/UsbSettingsReceiver( 5207): [AUTORUN] onReceive() : mActivityUsbModeChange = false
D/UsbSettingsReceiver( 5207): [AUTORUN] onReceive() : mActivityFinish = false
D/UsbSettingsReceiver( 5207): [AUTORUN] onReceive() : ===== USB Configured =====
D/UsbSettingsControl( 5207): [AUTORUN] setUsbConnected() : connected=true
D/UsbSettingsReceiver( 5207): [AUTORUN] onReceive() : checkQmicm = ptp_only,adb
I/CheckinTask( 4317): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 4317): Checking schedule, now: 1457138447157 next: 1457665696151
,I/CheckinService( 4317): active receiver: disabled
D/UsbSettingsReceiver( 5207): [AUTORUN] : topPackageName=com.test.thalitest
D/UsbSettingsReceiver( 5207): [AUTORUN] : topClassName=com.test.thalitest.MainActivity
,D/UsbSettingsReceiver( 5207): [AUTORUN] Not exist com.android.LGSetupWizard
D/UsbSettingsReceiver( 5207): [AUTORUN] setUsbConnect() : mUsbSettingsRun = false
D/CheckinService( 4317): Recording last checkin time for package unspecified as 1457138447184
D/UsbSettingsReceiver( 5207): [AUTORUN] startUsbSettings() : deviceProvisioned=1
I/ActivityManager(  857): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5228 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  857): Killing 4921:com.google.android.setupwizard/u0a38 (adj 15): empty #11
D/MtpService( 3196): updating state; isCurrentUser=true, mMtpLocked=false
W/libprocessgroup(  857): failed to open /acct/uid_10038/pid_4921/cgroup.procs: No such file or directory
,I/PCSuite ( 5228): [StartReceiver]USB CONNECTED ver UsbManger : ptp_only
,I/PCSuite ( 5228): [StartReceiver]isUsbPCSuiteMode : false
D/PCSuite ( 5228): [StartReceiver][checkEUTStatus] eutStatus = 
D/PCSuite ( 5228): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5228): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  857): Killing 4953:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10051/pid_4953/cgroup.procs: No such file or directory
,V/LGMDMManager( 5159): Create singleton instance
,I/DigitalAppWidgetProvider( 5182): onReceive: android.intent.action.ALARM_CHANGED,
,D/WeatherAncestor( 2712): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 1:40:47
D/UpdateThreadPoolManager( 2712): 2 : This is isUpdating : false
D/Weather_cast( 2712): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2712): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 1:40:47
D/WeatherService( 2712): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
W/ActivityManager(  857): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2712): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2712): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2712): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/AlertReceiver( 3847): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
D/AlertService( 3847): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 3847): [updateWidgets] 
,D/MonthWidgetProvider( 3847): [onReceive]
D/CalendarWidgetProvider( 3847): [onReceive]
D/CalendarWidgetProvider( 3847): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 3847): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 3847): [onReceive]
D/CalendarWidgetProvider( 3847): [onReceive]
D/CalendarWidgetProvider( 3847): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 3847): [onCreate] mContext.getPackageName() = com.android.calendar
,I/[SystemUI]SafeModeBroadcastReceiver( 1373): onReceive = com.lge.statusbar.bootcompleted
,D/CalendarWeatherReceiver( 3847): Get action=com.lge.calendar.action.WEATHER_SERVICE_START
,I/ActivityManager(  857): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.MediaScanReceiver: pid=5252 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  857): Process com.google.android.apps.magazines (pid 5040) has died
,E/MediaScanReceiver( 5252): media scanning start or checking
W/MainApplication( 5252): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/ActivityManager(  857): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5269 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/MusicStore( 5269): Database version: 120
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5269): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/chromium( 4858): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
,I/chromium( 4858): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5269): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5269): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 5269): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5269): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5269): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5269): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5269): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@369d4763: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5269): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5269): GMSCore installation verified
,I/ConfigStore( 5269): Config Database version: 1
,I/MediaRouter( 5269): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/NightModeReceiver( 5207): [Nightmode] Enter receiver
I/NetworkMonitor( 5269): type=WIFI subType= reason=null isConnected=true
D/NightModeReceiver( 5207): [Nightmode] NIGHT_MODE_ACTION_START
,D/NightModeInfo( 5207): [Nightmode] setNightNodeTabSettings
D/NightModeInfo( 5207): [Nightmode] getAlreadyNightModeDB() : 0
D/NightModeInfo( 5207): [Nightmode] getUserBrightnessChange() : 0
,D/NightModeInfo( 5207): [Nightmode] getUserBrightnessChangeNoNight() : 0
D/NightModeInfo( 5207): [Nightmode] getTabNightCheck
,V/SettingsProvider(  857): call_put(system:already_night_mode=0) for 0 calling package = com.android.settings
,V/SettingsProvider(  857): call_put(system:user_change_brightness=0) for 0 calling package = com.android.settings
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
V/SettingsProvider(  857): call_put(system:user_change_brightness_no_night=0) for 0 calling package = com.android.settings
V/SettingsProvider(  857): call_put(system:night_mode_enabled=0) for 0 calling package = com.android.settings
D/NightModeInfo( 5207): [Nightmode] setTabNightCheck : 0
V/SettingsProvider(  857): call_put(system:save_tab_night_check=0) for 0 calling package = com.android.settings
I/art     (  857): Explicit concurrent mark sweep GC freed 24389(1334KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.165ms total 180.044ms
,D/ToneMappingReceiver( 5182): Enter doAlarmRingToneUriMapping()
,I/NetworkMonitor( 5269): type=WIFI subType= reason=null isConnected=true
I/GHttpClientFactory( 5269): Using our fixed implementation of GMSCore's GoogleHttpClient
,D/ToneMappingReceiver( 5182): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5182): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
I/GoogleURLConnFactory( 5269): Using platform SSLCertificateSocketFactory
D/CommonUtil( 5182): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5182): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5182): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5182): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5182): Alarm Success count is 0
D/ToneMappingReceiver( 5182): Timer Success count is 0
,I/MediaScannerReceiver( 3847): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///system/media
E/MediaScanReceiver( 5252): media scanning finished
,I/InitNotificationRingtoneService( 3847): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3847): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/com.lge.bnr.receiver.MediaScanReceiver( 5252): android.intent.action.MEDIA_SCANNER_FINISHED
,I/AlertUtils( 3847): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,E/MediaScanReceiver( 5252): media scanning start or checking
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,D/ToneMappingReceiver( 5182): Enter doAlarmRingToneUriMapping()
D/ToneMappingReceiver( 5182): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5182): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5182): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5182): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5182): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5182): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5182): Alarm Success count is 0
,D/ToneMappingReceiver( 5182): Timer Success count is 0
I/NotificationManager( 5269): com.google.android.music: cancel(1061) by com.google.android.music
I/ActivityManager(  857): Killing 4986:com.google.android.talk/u0a61 (adj 15): empty #11
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,W/libprocessgroup(  857): failed to open /acct/uid_10061/pid_4986/cgroup.procs: No such file or directory
I/MediaScannerReceiver( 3847): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///storage/emulated/0
,E/MediaScanReceiver( 5252): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 5252): android.intent.action.MEDIA_SCANNER_FINISHED
I/art     ( 3196): Explicit concurrent mark sweep GC freed 14629(953KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/10MB, paused 399us total 47.877ms
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/art     ( 5269): CheckpointMarkThreadRoots callback created = 0xb042d400
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3847): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 3847): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3847): End InitializeAlertRingtoneService.onHandleIntent
I/InitNotificationRingtoneService( 3847): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3847): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/AlertUtils( 3847): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/art     ( 5269): CheckpointMarkThreadRoots callback created = 0xb042d3d0
,I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/ActivityManager(  857): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5315 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 3847): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3847): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 3847): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3847): End InitializeAlertRingtoneService.onHandleIntent
,W/ResourcesManager( 5315): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5315): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2a602a35
,D/CalendarProvider2( 5315): [getOrCreateCalendarAlarmManager]
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{a2db411 type 2 when 77780 android} when 77780
I/CalendarProvider2( 5315): Created com.android.providers.calendar.CalendarAlarmManager@24c88d96(com.android.providers.calendar.CalendarProvider2@2a602a35)
D/CalendarProviderBroadcastReceiver( 5315): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5315): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 5315): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 5315): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
,D/CalendarProvider2( 5315): [getOrCreateCalendarAlarmManager]
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,E/MDM     ( 1732): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/CalendarProvider2( 5315): [IntentService] Release Lock
,D/CalendarProvider2( 5315): CalendarProviderIntentService.onDestroy()
D/LocationInitializer( 4317): Restart initialization of location
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,I/MediaStoreImporter( 5269): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
I/ActivityManager(  857): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5340 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,W/IcingInternalCorpora( 4317): getNumBytesRead when not calculated.
,W/ActivityManager(  857): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5340): getAccountsCursor
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 5340): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  857): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5340): Error finding the version of the Email provider.....
E/Gmail   ( 5340): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5340): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5340): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5340): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5340): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5340): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5340): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5340): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5340): We do not support migrating this version of the Email provider.
,W/ActivityManager(  857): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 5340): getAccountsCursor
I/Gmail   ( 5340): Observing account changes for notifications
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/art     (  857): Explicit concurrent mark sweep GC freed 10993(597KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.273ms total 154.851ms
W/ActivityManager(  857): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1732): location=null
,I/Gmail   ( 5340): notifyAccountChanged
,I/Gmail   ( 5340): getAccountsCursor
I/Gmail   ( 5340): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5340): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/art     ( 4024): Explicit concurrent mark sweep GC freed 3271(127KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 875us total 37.728ms
I/Gmail   ( 5340): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5340): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/art     ( 4317): Explicit concurrent mark sweep GC freed 16095(1296KB) AllocSpace objects, 25(400KB) LOS objects, 39% free, 12MB/20MB, paused 4.209ms total 108.621ms
,V/DownloadManager( 3196): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3196): created cursor android.database.sqlite.SQLiteCursor@267641da on behalf of 4317
I/ActivityManager(  857): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5390 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/Gmail   ( 5340): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PhoneMonitor( 5390): Register our PhoneStateListener
,I/ActivityManager(  857): Killing 5106:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10048/pid_5106/cgroup.procs: No such file or directory
,V/DownloadManager( 3196): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3196): created cursor android.database.sqlite.SQLiteCursor@3106a60b on behalf of 4317
V/DownloadManager( 3196): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3196): created cursor android.database.sqlite.SQLiteCursor@1dee3ce8 on behalf of 4317
D/PhoneMonitor( 5390): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
I/CheckinService( 4317): Checkin interval check for package: unspecified last checkin: 1457138447184 min interval config: 0 actual interval: 3145
V/TelephonyAutoProfiling( 5390): [loadFeatureFromXml] *** start feature loading from xml
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/TelephonyAutoProfiling( 5390): [parse] Load xml
V/TelephonyAutoProfiling( 5390): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5390): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/CheckinService( 4317): Checking schedule, now: 1457138450342 next: 1457138477151
I/CheckinService( 4317): active receiver: disabled
,D/PhoneMonitor( 5390): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  857): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5414 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5414): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Babel_SMS( 5414): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5414): MmsConfig.loadMmsSettings
I/Babel_SMS( 5414): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5414): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5414): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5414): MmsConfig.loadFromResources
E/Babel_SMS( 5414): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5414): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5414): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5414): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5414): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 5414): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5414): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5414): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5414): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5414): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5414): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5414): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5414): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5414): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5414): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5414): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5414): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5414): found sensor: Motion Accel, handle=46
W/Settings( 5414): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5414): startup - clean
I/art     ( 5414): CheckpointMarkThreadRoots callback created = 0xb042d870
I/art     ( 5414): CheckpointMarkThreadRoots callback created = 0xb042d850
,I/Babel   ( 5414): deleted: false for 0
,W/AudioCapabilities( 5414): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5414): Unsupported mime audio/adpcm
W/AudioCapabilities( 5414): Unsupported mime audio/g726
W/AudioCapabilities( 5414): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5414): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 5414): Unsupported mime video/mjpg
W/VideoCapabilities( 5414): Unsupported mime video/theora
,W/AudioCapabilities( 5414): Unsupported mime audio/evrc
W/AudioCapabilities( 5414): Unsupported mime audio/qcelp
,W/VideoCapabilities( 5414): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5414): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5414): Unsupported mime audio/qcelp
W/AudioCapabilities( 5414): Unsupported mime audio/evrc
W/VideoCapabilities( 5414): Unsupported mime video/mp4v-esdp
,I/ActivityManager(  857): Killing 5129:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/VideoCapabilities( 5414): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5414): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5414): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5414): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5414): Unrecognized profile 2130706433 for video/avc
W/libprocessgroup(  857): failed to open /acct/uid_10086/pid_5129/cgroup.procs: No such file or directory
,I/vclib   ( 5414): onServiceConnected
W/Babel   ( 5414): Attempted to change video mute state without an active call.
,W/art     ( 5159): Suspending all threads took: 10.360ms
,W/ResourcesManager( 5414): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5414): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 5414): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  857): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5448 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AudioManager( 5159): getMode name:com.lge.qremote
,I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 30.157ms
I/AudioManager( 5159): getMode name:com.lge.qremote
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 21.763ms
,W/System  ( 5414): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5414): Installed default security provider GmsCore_OpenSSL
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 22.565ms
,I/ActivityManager(  857): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5470 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
D/UEI.SmartControl( 5448): Quickset Services start...
I/UEI.SmartControl( 5448): Manufacture = LGE
D/UEI.SmartControl( 5448): File observer start...
E/UEI.SmartControl( 5448): IR Port is disabled: false
D/UEI.SmartControl( 5448): Starting file observer...
D/UEI.SmartControl( 5448): Extracting JNI libs...
D/UEI.SmartControl( 5448): --- this system supports 32-bit or 64-bit only
I/NotificationManager( 5414): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 5470): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5470): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5470): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ActivityManager(  857): Process com.google.android.music:main (pid 5269) has died
,I/LGEmail ( 5470): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 5470): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/UEI.SmartControl( 5448): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5448): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5448): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 5448): --- Selecting new region: 2
I/UEI.SmartControl( 5448): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5448): Platform has CIR...
D/UEI.SmartControl( 5448): NO CIR support, need to check package...
I/UEI.SmartControl( 5448): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5448): QS Service created
,E/UEI.SmartControl( 5448): QS start get config
,I/PackageChangeReceiver( 5470): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,D/UEI.SmartControl( 5448): Loading JNI Libs...
D/UEI.SmartControl( 5448):  configuring local db...
,I/ActivityManager(  857): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5498 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  857): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5518 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/UEI.SmartControl( 5448):  ---- Has DB8: true
D/UEI.SmartControl( 5448): QS start statue = true Error code = 0
D/UEI.SmartControl( 5448): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5448): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5448): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5448): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5448): IrrcClient ++ 
D/irrcClient( 5448): getIrrcService ++ 
D/irrcClient( 5448): getIrrcService -- 
D/irrcClient( 5448): IrrcClient -- 
W/irrc_jni( 5448): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5448): Services init done
I/UEI.SmartControl( 5448): Device manager: loading config....
I/ActivityManager(  857): Killing 5228:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 5448): QS Service init finished
D/UEI.SmartControl( 5448): QS Service version name: 0.1.73
D/UEI.SmartControl( 5448): QS Service version code: 1073
D/UEI.SmartControl( 5448): Service requested: Control
D/UEI.SmartControl( 5448): Config is loaded...
W/libprocessgroup(  857): failed to open /acct/uid_1000/pid_5228/cgroup.procs: No such file or directory
D/UEI.SmartControl( 5448):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5448): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5448): Request IControl service: devices are loaded...
D/UEI.SmartControl( 5448): Internal service binding...
D/UEI.SmartControl( 5448): -----IControl: 11
D/UEI.SmartControl( 5448): Caller: com.lge.qremote
D/UEI.SmartControl( 5448): ------------ IControl registerCallback...
I/UEI.SmartControl( 5448): Registering callback...
D/UEI.SmartControl( 5448): -----IControl: 19
D/UEI.SmartControl( 5448): Caller: com.lge.qremote
I/UEI.SmartControl( 5448): Registering Services Ready callback...
I/UEI.SmartControl( 5448): Notify client services are ready...
D/UEI.SmartControl( 5448): -----IControl: 8
D/UEI.SmartControl( 5448): Caller: com.lge.qremote
I/ActivityManager(  857): Killing 5182:com.lge.clock/u0a10 (adj 15): empty #11
I/AppUp4:AppBoxCP( 5518): onCreate
W/AppUp4:DB( 5518):  [AppBoxDatabaseHelper] construct
I/ActivityManager(  857): Killing 5207:com.android.settings/1000 (adj 15): empty #12
I/AppUp4:DB( 5518):  setFingerPrint start
I/AppUp4:DB( 5518):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5518):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5518):  SDK version = 0
I/AppUp4:DB( 5518):  beforefinger == newfinger no write in DB
W/libprocessgroup(  857): failed to open /acct/uid_10010/pid_5182/cgroup.procs: No such file or directory
W/libprocessgroup(  857): failed to open /acct/uid_1000/pid_5207/cgroup.procs: No such file or directory
D/AppUp4:AppBoxApplication( 5518): AppBoxApplication onCreate()
D/AppUp4:PreloadHelper( 5518): removed from Exclude : com.test.thalitest : 1
I/ActivityManager(  857): Killing 5252:com.lge.bnr/1000 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_1000/pid_5252/cgroup.procs: No such file or directory
D/AlertService( 3847): Beginning updateAlertNotification
I/ActivityManager(  857): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5545 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
D/AlertService( 3847): No fired or scheduled alerts
I/NotificationManager( 3847): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3847): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3847): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3847): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3847): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3847): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3847): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3847): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3847): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3847): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3847): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3847): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3847): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3847): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3847): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3847): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3847): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3847): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3847): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3847): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3847): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 3847): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 3847): No events found starting within 1 week.
,W/ResourcesManager( 5545): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5545): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5545): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/AppConfig( 5545): Total System Memory = 906309632
,I/GalleryUtils( 5545): Application Heap = 96 MB
I/AppConfig( 5545): App Tier : NOT_DEF
D/SystemHelper( 5545): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  857): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5564 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  857): Killing 5315:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10014/pid_5315/cgroup.procs: No such file or directory
,W/ResourcesManager( 5564): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5564): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5564): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5564): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5564): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 5564): BUILD Country: EU
I/SystemConfig( 5564): BUILD Operator: OPEN
,I/ActivityManager(  857): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5583 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  857): Killing 5340:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10053/pid_5340/cgroup.procs: No such file or directory
,I/SystemConfig( 5564): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5564): existFile = false
I/SystemConfig( 5564): canReadFile = false
I/SystemConfig( 5564): systemFeature RCS result false
,D/SystemConfig( 5564): refreshRcsSupport() :false
I/LockScreenSettings( 5583): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 5583): New app installed broadcast received ..
,I/LockScreenSettings( 5583): Number of installed packages  1
I/ActivityManager(  857): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5600 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  857): Killing 5390:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10038/pid_5390/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 5600): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5600): uri : package:com.test.thalitest
,I/ActivityManager(  857): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5617 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  857): Killing 4024:com.google.process.gapps/u0a6 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10006/pid_4024/cgroup.procs: No such file or directory
,D/[BNRAppListMgrReceiver]( 5617): android.intent.action.PACKAGE_ADDED : com.test.thalitest
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/MainApplication( 5617): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ActivityManager(  857): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5634 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  857): Killing 5016:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10006/pid_5016/cgroup.procs: No such file or directory
,I/art     (  857): Explicit concurrent mark sweep GC freed 19155(918KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.347ms total 138.862ms
,I/GAv4    ( 5634): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5634):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5634):   adb logcat -s GAv4
,W/GAv4    ( 5634): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5634): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5634): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5634): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5634): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 5634): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5634): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  857): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5666 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  857): Killing 5159:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10106/pid_5159/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/art     ( 5634): CheckpointMarkThreadRoots callback created = 0xaaf2a350
,W/ResourcesManager( 5666): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 5634): CheckpointMarkThreadRoots callback created = 0xaaf2a330
,V/JNIHelp ( 5634): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/art     ( 5634): Suspending all threads took: 5.077ms
,W/System  ( 5634): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5634): Installed default security provider GmsCore_OpenSSL
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/InitAlarmsService( 3847): Clearing and rescheduling alarms.
,I/ActivityManager(  857): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5702 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 21.165ms
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.236ms
,I/CheckinService( 4317): Done disabling old GoogleServicesFramework version
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 306us total 21.310ms
,W/ResourcesManager( 5702): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/ActivityManager(  857): Killing 5448:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,D/CalendarProvider2( 5702): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2a602a35
,W/libprocessgroup(  857): failed to open /acct/uid_10089/pid_5448/cgroup.procs: No such file or directory
,D/CalendarProvider2( 5702): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5702): Created com.android.providers.calendar.CalendarAlarmManager@24c88d96(com.android.providers.calendar.CalendarProvider2@2a602a35)
D/CalendarProvider2( 5702): Scheduling check of next Alarm
D/CalendarProvider2( 5702): SCHEDULE_ALARM_REMOVE
,I/ActivityManager(  857): Killing 3847:com.android.calendar/u0a13 (adj 15): empty #11
I/ActivityManager(  857): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5726 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/libprocessgroup(  857): failed to open /acct/uid_10013/pid_3847/cgroup.procs: No such file or directory
I/ActivityManager(  857): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5751 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1945): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/GservicesProvider( 5726): Gservices pushing to system: true; secure/global: true
,I/ActivityManager(  857): Process com.lge.email (pid 5470) has died
,I/UpdateIcingCorporaServi( 1945): UpdateCorporaTask done [took 192 ms] updated apps [took 192 ms] 
,I/GoogleHttpClient( 5726): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5726): GMS http client unavailable, use old client
,D/Finsky  ( 5751): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5751): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5751): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5751): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5751): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3196): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3196): created cursor android.database.sqlite.SQLiteCursor@186ecf01 on behalf of 5751
I/NotificationManager( 5751): com.android.vending: cancel(1003285959) by com.android.vending
,D/Ads     ( 5751): Skipping gmscore version check
,D/Finsky  ( 5751): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5751): [1] Libraries$2.run: Finished loading 1 libraries.
D/PackageBroadcastService( 4317): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/Finsky  ( 5751): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/ChimeraCfgMgr( 4317): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4317): Loading module APK com.google.android.play.games
,D/Finsky  ( 5751): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/Finsky  ( 5751): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  857): Killing 5498:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10009/pid_5498/cgroup.procs: No such file or directory
,I/CalendarProvider2( 5702): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5702): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  857): Killing 5518:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10011/pid_5518/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 4317): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4317): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4317): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/Icing   ( 4317): Storage manager: low false usage 1.76MB avail 2.37GB capacity 4.06GB
D/AsyncTaskServiceImpl( 4317): Submit a task: k
,D/ChimeraCfgMgr( 4317): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 4317): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 4317): Processing package: com.test.thalitest
D/GassUtils( 4317): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 4317): Found info for package com.test.thalitest in db.
,I/ActivityManager(  857): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5827 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/BaseAppContext( 4317): Using Auth Proxy for data requests.
,W/BaseAppContext( 4317): Using Auth Proxy for data requests.
I/PeopleDatabaseHelper( 4317): cleanUpNonGplusAccounts done.
W/BaseAppContext( 4317): Using Auth Proxy for data requests.
,W/BaseAppContext( 4317): Using Auth Proxy for data requests.
W/ResourcesManager( 5827): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/BaseAppContext( 4317): Using Auth Proxy for data requests.
,E/Icing   ( 4317): Array storage bad crc 1189023362 vs 1159839097
,E/Icing   ( 4317): Array storage bad crc 494972884 vs 546422064
E/Icing   ( 4317): Array storage bad crc 2324530457 vs 618992776
E/Icing   ( 4317): Trie mmap suffix failed
,D/BluetoothManagerService(  857): Message: 20
D/BluetoothManagerService(  857): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@258a73f5:true
I/ActivityManager(  857): Killing 5414:com.google.android.talk/u0a61 (adj 15): empty #11
,W/Icing   ( 4317): Docstore bad crc 0x7aafad55 vs 0x6a501db5
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  857): failed to open /acct/uid_10061/pid_5414/cgroup.procs: No such file or directory
,D/BluetoothAdapterService(192408866)( 1994): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3ad2da88
D/BluetoothAdapterService(192408866)( 1994): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3ad2da88
I/AudioManager( 5827): getMode name:com.lge.qremote
,I/AudioManager( 5827): getMode name:com.lge.qremote
,I/AudioManager( 5827): getMode name:com.lge.qremote
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,D/LocationInitializer( 4317): Restart initialization of location
E/MDM     ( 1732): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
E/Icing   ( 4317): Array storage bad crc 3956344901 vs 0
E/Icing   ( 4317): Trie mmap node failed
,I/ActivityManager(  857): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=5852 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
,W/ResourcesManager( 5852): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Icing   ( 4317): updateResources: need to parse f{com.google.android.gms}
,I/Babel_SMS( 5852): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5852): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5852): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5852): MmsConfig.loadFromDatabase
E/Babel_SMS( 5852): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5852): MmsConfig.loadFromResources
,E/Babel_SMS( 5852): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5852): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5852): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5852): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5852): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5852): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5852): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5852): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5852): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5852): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5852): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5852): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5852): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5852): found sensor: LGE Orientation Sensor, handle=49
,D/SensorManager( 5852): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5852): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5852): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5852): found sensor: Motion Accel, handle=46
W/Settings( 5852): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5852): startup - clean
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/InputReader(  857): Reconfiguring input devices.  changes=0x00000010
D/administrator(  857): Handling package changes for user 0
I/Babel   ( 5852): deleted: false for 0
,I/art     ( 5852): CheckpointMarkThreadRoots callback created = 0xaaf3e690
D/ChimeraCfgMgr( 4317): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4317): Module APK com.google.android.play.games already loaded
I/Icing   ( 4317): Internal init done: storage state 0
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/Icing   ( 4317): 22 corpora need re-polling
I/art     ( 5852): CheckpointMarkThreadRoots callback created = 0xaaf3e660
I/Icing   ( 4317): Post-init done
,I/Icing   ( 4317): Indexing 1612944C7007A012B1C904336C8580EC6DBD4F91 from com.google.android.music
I/NotificationService(  857): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  857): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  857): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/ActivityManager(  857): Start proc com.google.android.music:main for content provider com.google.android.music/.icing.IcingContentProvider: pid=5888 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ResourcesManager(  857): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/BackupManagerService(  857): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  857): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  857): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3dcf36e4
,W/AudioCapabilities( 5852): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5852): Unsupported mime audio/adpcm
W/AudioCapabilities( 5852): Unsupported mime audio/g726
W/AudioCapabilities( 5852): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5852): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5852): Unsupported mime video/mjpg
W/VideoCapabilities( 5852): Unsupported mime video/theora
W/ResourceType(  857): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
I/ActivityManager(  857): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5905 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/LocationProviderProxy(  857): applying state to connected service
,W/AudioCapabilities( 5852): Unsupported mime audio/evrc
W/AudioCapabilities( 5852): Unsupported mime audio/qcelp
W/VideoCapabilities( 5852): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 5852): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5852): Unsupported mime audio/qcelp
W/AudioCapabilities( 5852): Unsupported mime audio/evrc
,I/AppUp4:AppBoxCP( 5905): onCreate
W/AppUp4:DB( 5905):  [AppBoxDatabaseHelper] construct
I/art     (  857): Explicit concurrent mark sweep GC freed 28915(1418KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.987ms total 177.048ms
,W/VideoCapabilities( 5852): Unsupported mime video/mp4v-esdp
I/AppUp4:DB( 5905):  setFingerPrint start
I/AppUp4:DB( 5905):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 5905):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5905):  SDK version = 0
I/AppUp4:DB( 5905):  beforefinger == newfinger no write in DB
D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
D/AppUp4:AppBoxApplication( 5905): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 5905): onReceive
I/AppUp4:CustModeStarterReceiver( 5905): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
I/VideoCapabilities( 5852): Unsupported profile 4 for video/mp4v-es
D/AppUp4:CustFacade( 5905): Context : android.app.ReceiverRestrictedContext@17e1eb58
D/AppUp4:CustFacade( 5905): isCustomizationCompleted : false
I/MusicStore( 5888): Database version: 120
D/AppUp4:CustFacade( 5905): isSimDevice : true
,W/VideoCapabilities( 5852): Unrecognized profile 2130706433 for video/avc
D/AppUp4:CustModeStarterReceiver( 5905): begin check event
I/AppUp4:CustModeStarterReceiver( 5905): Event For Nothing, skip.
W/VideoCapabilities( 5852): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  857): Killing 5545:com.android.gallery3d/u0a23 (adj 15): empty #11
W/VideoCapabilities( 5852): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5852): Unrecognized profile 2130706433 for video/avc
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 30188(2MB) AllocSpace objects, 36(576KB) LOS objects, 39% free, 13MB/22MB, paused 1.390ms total 297.025ms
,W/libprocessgroup(  857): failed to open /acct/uid_10023/pid_5545/cgroup.procs: No such file or directory
,I/ActivityManager(  857): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5933 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5888): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,W/ResourcesManager( 5933): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5933): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5933): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/vclib   ( 5852): onServiceConnected
W/Babel   ( 5852): Attempted to change video mute state without an active call.
I/NotificationManager( 5852): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 5852): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5852): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
V/JNIHelp ( 5852): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ContextImpl( 5888): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5888): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 5888): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5888): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/AppConfig( 5933): Total System Memory = 906309632
,I/GalleryUtils( 5933): Application Heap = 96 MB
I/AppConfig( 5933): App Tier : NOT_DEF
V/JNIHelp ( 5888): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/SystemHelper( 5933): region [EU], country [EU], operator [OPEN], sub-operator []
W/System  ( 5852): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5852): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 5852): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/LockScreenSettings( 5583): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5583): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5583): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5583): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5583): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,W/ActivityThread( 5888): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5888): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@9f5ec19: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5888): Installed default security provider GmsCore_OpenSSL
,D/AndroidMusic( 5888): GMSCore installation verified
I/UpdateIcingCorporaServi( 1945): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/ConfigStore( 5888): Config Database version: 1
,I/art     ( 5888): Background sticky concurrent mark sweep GC freed 23295(1163KB) AllocSpace objects, 4(64KB) LOS objects, 8% free, 10MB/11MB, paused 10.947ms total 69.296ms
D/PackageBroadcastService( 4317): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4317): Null package name or gms related package.  Ignoreing.
I/Icing   ( 4317): Indexing done 1612944C7007A012B1C904336C8580EC6DBD4F91
I/Icing   ( 4317): Indexing 1F53EECCEBEB5877C2973BC154C132777EB605A6 from com.google.android.apps.books
,W/ActivityManager(  857): Permission Denial: opening provider com.google.android.apps.books.provider.BooksProvider from ProcessRecord{602591c 4317:com.google.android.gms/u0a6} (pid=4317, uid=10006) that is not exported from uid 10046
E/Icing   ( 4317): Cursor call threw an exception: Permission Denial: opening provider com.google.android.apps.books.provider.BooksProvider from ProcessRecord{602591c 4317:com.google.android.gms/u0a6} (pid=4317, uid=10006) that is not exported from uid 10046
,I/Icing   ( 4317): Indexing done 1F53EECCEBEB5877C2973BC154C132777EB605A6
E/Icing   ( 4317): Aborting indexing of corpus volumes__id
I/Icing   ( 4317): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/UpdateIcingCorporaServi( 1945): UpdateCorporaTask done [took 82 ms] updated apps [took 82 ms] 
,I/ActivityManager(  857): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5967 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/LGMDMManager( 5827): Create singleton instance
,I/MediaRouter( 5888): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
I/NetworkMonitor( 5888): type=WIFI subType= reason=null isConnected=true
I/AudioManager( 5827): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5967): Quickset Services start...
,I/UEI.SmartControl( 5967): Manufacture = LGE
D/UEI.SmartControl( 5967): File observer start...
E/UEI.SmartControl( 5967): IR Port is disabled: false
D/UEI.SmartControl( 5967): Starting file observer...
D/UEI.SmartControl( 5967): Extracting JNI libs...
D/UEI.SmartControl( 5967): --- this system supports 32-bit or 64-bit only
I/ActivityManager(  857): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5987 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  857): Killing 5600:com.lge.eula/1000 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_1000/pid_5600/cgroup.procs: No such file or directory
,I/NetworkMonitor( 5888): type=WIFI subType= reason=null isConnected=true
I/ActivityManager(  857): Process com.google.android.apps.docs (pid 5634) has died
,D/UEI.SmartControl( 5967): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5967): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5967): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/GHttpClientFactory( 5888): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 5888): Using platform SSLCertificateSocketFactory
,I/UEI.SmartControl( 5967): --- Selecting new region: 2
,I/UEI.SmartControl( 5967): -- Running on KitKat(19) and above! JNI will be used.
I/NotificationManager( 5888): com.google.android.music: cancel(1061) by com.google.android.music
D/UEI.SmartControl( 5967): Platform has CIR...
,D/UEI.SmartControl( 5967): NO CIR support, need to check package...
I/UEI.SmartControl( 5967): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5967): QS Service created
D/PhoneMonitor( 5987): Register our PhoneStateListener
,E/UEI.SmartControl( 5967): QS start get config
,V/SetupWizard( 5987): Connected to Gservices successfully
,I/ActivityManager(  857): Killing 5617:com.lge.bnr/1000 (adj 15): empty #11
,D/PhoneMonitor( 5987): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 5987): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5987): [parse] Load xml
D/UEI.SmartControl( 5967): Loading JNI Libs...
D/UEI.SmartControl( 5967):  configuring local db...
V/TelephonyAutoProfiling( 5987): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5987): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5987): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  857): failed to open /acct/uid_1000/pid_5617/cgroup.procs: No such file or directory
,I/AudioManager( 5827): getMode name:com.lge.qremote
I/ActivityManager(  857): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6010 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/UEI.SmartControl( 5967):  ---- Has DB8: true
,D/UEI.SmartControl( 5967): QS start statue = true Error code = 0
D/UEI.SmartControl( 5967): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5967): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5967): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5967): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 5967): IrrcClient ++ 
D/irrcClient( 5967): getIrrcService ++ 
D/irrcClient( 5967): getIrrcService -- 
D/irrcClient( 5967): IrrcClient -- 
W/irrc_jni( 5967): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 5967): Services init done
I/UEI.SmartControl( 5967): Device manager: loading config....
D/UEI.SmartControl( 5967): QS Service init finished
D/UEI.SmartControl( 5967): QS Service version name: 0.1.73
D/UEI.SmartControl( 5967): QS Service version code: 1073
D/UEI.SmartControl( 5967): Service requested: Control
D/UEI.SmartControl( 5967): Config is loaded...
,D/UEI.SmartControl( 5967):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5967): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 5967): Request IControl service: devices are loaded...
D/UEI.SmartControl( 5967): Internal service binding...
D/UEI.SmartControl( 5967): -----IControl: 11
,D/UEI.SmartControl( 5967): Caller: com.lge.qremote
D/UEI.SmartControl( 5967): ------------ IControl registerCallback...
I/UEI.SmartControl( 5967): Registering callback...
D/UEI.SmartControl( 5967): -----IControl: 19
D/UEI.SmartControl( 5967): Caller: com.lge.qremote
I/UEI.SmartControl( 5967): Registering Services Ready callback...
I/UEI.SmartControl( 5967): Notify client services are ready...
D/UEI.SmartControl( 5967): -----IControl: 8
D/UEI.SmartControl( 5967): Caller: com.lge.qremote
,I/ActivityManager(  857): Killing 5905:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/Icing   ( 4317): Loaded CLD2 Version V2.0 - 20141016
,I/ActivityManager(  857): Killing 5702:com.android.providers.calendar/u0a14 (adj 15): empty #12
W/ActivityManager(  857): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/libprocessgroup(  857): failed to open /acct/uid_10011/pid_5905/cgroup.procs: No such file or directory
,W/libprocessgroup(  857): failed to open /acct/uid_10014/pid_5702/cgroup.procs: No such file or directory
I/Gmail   ( 6010): getAccountsCursor
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 6010): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  857): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6010): Error finding the version of the Email provider.....
E/Gmail   ( 6010): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6010): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6010): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6010): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6010): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6010): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6010): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6010): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6010): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6010): getAccountsCursor
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  857): Killing 5933:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/ActivityManager(  857): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/libprocessgroup(  857): failed to open /acct/uid_10023/pid_5933/cgroup.procs: No such file or directory
W/ActivityManager(  857): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6010): Observing account changes for notifications
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/AudioManager( 5827): getMode name:com.lge.qremote
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  857): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6056 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 304us total 22.453ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.643ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 21.393ms
,D/WeatherService( 2712): 2 : TimeTick Intent has been received, Time(hour:min:sec) 1:41:0
D/WeatherService( 2712): 2 : TimeTick Intent And Screen On
D/WeatherService( 2712): 2 : SDK version : 21
W/ActivityManager(  857): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2712): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2712): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2712): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2712): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2712): 2 : This is isUpdating : false
D/WeatherService( 2712): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2712): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2712): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
D/WeatherTheme( 2712): 2 : Fixed theme : optimus
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
D/WeatherReflect( 2712): 2 : Map key string is -2
,D/lim     ( 2712): 2 : time = 01:41
I/[SystemUI]Clock( 1373): called onTimeUpdated()
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/WeatherReflect( 2712): Model Name : LG-D722
D/WeatherTheme( 2712): 2 : Different view - status_min_formatted : 40 != 41
D/WeatherTheme( 2712): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2712): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,D/Theme   ( 2712): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2712): currentPackage=com.lge.sizechangable.weather.theme.optimus
W/ResourcesManager( 6056): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{1654fdd2 type 2 when 88680 com.android.providers.calendar} when 88680
,I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/Weather4x2_optimus( 2712): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2712): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2712): forecast size is 0
D/Theme   ( 2712): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(home): com.lge.launcher2.theme.optimus
,D/Theme   ( 2712): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2712): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2712): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2712): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2712): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2712): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2712): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2712): url is : null
I/art     (  857): Explicit concurrent mark sweep GC freed 16468(808KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 8.971ms total 190.139ms
I/Gmail   ( 6010): notifyAccountChanged
D/Theme   ( 2712): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Gmail   ( 6010): getAccountsCursor
D/WeatherAncestor( 2712): 2 : update view, appWidgetId: 2
,I/Gmail   ( 6010): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WeatherService( 2712): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 1:41:0
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6010): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
D/CalendarApplication( 6056): CalendarApplication.onCreate()
,I/Gmail   ( 6010): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6010): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/PreferenceKeysParser( 6056): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6056): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@2e3b483b, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@17e1eb58, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@1ef634b1, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@24c88d96, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1c8c2d17, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@14366504, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@13086aed, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@b77ed22, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@369c83b3, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@36cd70, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1e8dc8e9, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2cbb96e, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@1c51a80f, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@3a93509c, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@7f10aa5, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@337dfe7a, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1c8ab62b, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3ad2da88, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@178cac21, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@25dd8846, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@afc8a07, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@27ff1734, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@26e6e95d, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@659e2d2, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@17cdbfa3, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2e1072a0, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@27adbe59, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@26cf5a1e, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@4f2b2ff, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3e1a18cc, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@1e72e715, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@892fa2a, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@1549801b, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@2535f5b8, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@d27df91, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3b3e8ef6, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@117602f7, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@2630b564, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@959e3cd, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1c3ca482, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3e7dd793, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@1f5c3d0, 
D/GeneralP,referenceUtils( 6056): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6056): [init]
I/Config  ( 6056): LGCalendar ver.4.40.17
I/Config  ( 6056): start check model
I/Config  ( 6056): start check native_ca
I/Config  ( 6056): Config Operator=OPEN, Country=EU
D/Config  ( 6056): [setDefaultValuesToPref]
D/Config  ( 6056): [parseProfiles]
D/ProfilesParser( 6056): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6056): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6056): [updateProfiletoCountryInfo]
D/GeneralPreference( 6056): [checkAndMigrateOldPreference]
D/AlertReceiver( 6056): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/InitNotificationRingtoneService( 6056): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6056): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 6056): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6056): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
,I/AlertUtils( 6056): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6056): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
I/AlertUtils( 6056): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6056): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 6056): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6056): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6056): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6056): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6056): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 6056): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6056): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 6056): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6056): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6056): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6056): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6056): set default noti to content://media/internal/audio/media/38
I/Gmail   ( 6010): getAccountsCursor
,I/InitNotificationRingtoneService( 6056): End InitializeAlertRingtoneService.onHandleIntent
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/HolidayIntentService( 6056): onHandleIntent
,D/HolidayDataLoader( 6056): readJsonAsset : holiday.json
D/AlertService( 6056): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6056): [updateWidgets] 
D/MonthWidgetProvider( 6056): [onReceive]
D/CalendarWidgetProvider( 6056): [onReceive]
D/CalendarWidgetProvider( 6056): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6056): [onCreate] mContext.getPackageName() = com.android.calendar
,D/WeekWidgetProvider( 6056): [onReceive]
D/CalendarWidgetProvider( 6056): [onReceive]
D/CalendarWidgetProvider( 6056): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6056): [onCreate] mContext.getPackageName() = com.android.calendar
I/AudioManager( 5827): getMode name:com.lge.qremote
E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,E/HolidayIntentService( 6056): onHandleIntent:holiday data empty
,I/ActivityManager(  857): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6094 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 5852): com.google.android.talk: cancel(8) by com.google.android.talk
,I/Icing   ( 4317): Indexing B2F716F68058802BDD4E913C0921699984AB1871 from com.google.android.videos
,I/AppUp4:AppBoxCP( 6094): onCreate
W/AppUp4:DB( 6094):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6094):  setFingerPrint start
I/AppUp4:DB( 6094):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6094):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6094):  SDK version = 0
I/AppUp4:DB( 6094):  beforefinger == newfinger no write in DB
,I/ActivityManager(  857): Start proc com.google.android.videos for content provider com.google.android.videos/.search.IcingContentProvider: pid=6112 uid=10099 gids={50099, 9997, 3003, 1028, 1015, 3002} abi=armeabi
D/AppUp4:AppBoxApplication( 6094): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6094): onReceive
I/AppUp4:CustModeStarterReceiver( 6094): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6094): Context : android.app.ReceiverRestrictedContext@17e1eb58
D/AppUp4:CustFacade( 6094): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6094): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6094): begin check event
I/AppUp4:CustModeStarterReceiver( 6094): Event For Nothing, skip.
I/ActivityManager(  857): Killing 5564:com.android.contacts/u0a18 (adj 15): empty #11
,W/ResourcesManager( 6112): Asset path '/system/framework/com.google.widevine.software.drm.jar' does not exist or contains no resources.
,W/libprocessgroup(  857): failed to open /acct/uid_10018/pid_5564/cgroup.procs: No such file or directory
,I/ActivityManager(  857): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6131 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 6131): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6131): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6131): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/ActivityManager(  857): Process com.google.android.apps.plus (pid 5666) has died
,I/AppConfig( 6131): Total System Memory = 906309632
I/GalleryUtils( 6131): Application Heap = 96 MB
I/AppConfig( 6131): App Tier : NOT_DEF
,D/SystemHelper( 6131): region [EU], country [EU], operator [OPEN], sub-operator []
I/art     ( 5726): Explicit concurrent mark sweep GC freed 8203(412KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.197ms total 44.709ms
,I/ActivityManager(  857): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6158 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 6158): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6158): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6158): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6158): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6158): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 6158): BUILD Country: EU
,I/SystemConfig( 6158): BUILD Operator: OPEN
D/LockScreenSettings( 5583): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5583): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 5583): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5583): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5583): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/SystemConfig( 6158): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6158): existFile = false
I/SystemConfig( 6158): canReadFile = false
I/SystemConfig( 6158): systemFeature RCS result false
D/SystemConfig( 6158): refreshRcsSupport() :false
I/ActivityManager(  857): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6207 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  857): Process com.google.android.music:main (pid 5888) has died
,I/Icing   ( 4317): Indexing done B2F716F68058802BDD4E913C0921699984AB1871
I/Icing   ( 4317): Indexing FC5805F301A6400196925772B79FE617968B1409 from com.google.android.videos
I/ActivityManager(  857): Killing 5751:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10036/pid_5751/cgroup.procs: No such file or directory
W/PlayMovies( 6112): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 6112): 
,W/ResourcesManager( 6207): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Icing   ( 4317): Indexing done FC5805F301A6400196925772B79FE617968B1409
I/Icing   ( 4317): Indexing 568CE8700B788EF0A23FB149BDEF8EE9F7A56DE9 from com.google.android.gms
,I/Icing   ( 4317): Indexing done 568CE8700B788EF0A23FB149BDEF8EE9F7A56DE9
,I/Icing   ( 4317): Indexing 261F31C44790DA98645222D6E4244392E5409193 from com.google.android.gms
I/Icing   ( 4317): Indexing done 261F31C44790DA98645222D6E4244392E5409193
I/Icing   ( 4317): Indexing AC7CA1348821615DDDE9D587591668A8B8E68A6F from com.google.android.googlequicksearchbox
I/ActivityManager(  857): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentFiltersService: pid=6230 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/PlayMovies( 6112): SyncCallback.getResponse:78 SyncCallback from main thread might cause ANR
W/PlayMovies( 6112): 
,D/PlayMovies( 6112): PersistentCache.cleanup:94 Cache is below limit, no need to shrink: [size=0, limit=5242880]
D/PlayMovies( 6112): 
,D/PlayMovies( 6112): TransferService.onCreate:60 creating transfer service
D/PlayMovies( 6112): 
I/Icing   ( 4317): Indexing done AC7CA1348821615DDDE9D587591668A8B8E68A6F
I/Icing   ( 4317): Indexing 83A00FDEBC70CD82044D41C3D8A6BD97ECE0C652 from com.google.android.googlequicksearchbox
,W/AudioCapabilities( 6112): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6112): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6112): Unsupported mime audio/g726
W/AudioCapabilities( 6112): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6112): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6112): Unsupported mime video/mjpg
I/Icing   ( 4317): Indexing done 83A00FDEBC70CD82044D41C3D8A6BD97ECE0C652
W/VideoCapabilities( 6112): Unsupported mime video/theora
,I/Icing   ( 4317): Indexing 736B0110C483B1C6D43A79F22BB0C3E0A2D6B16D from com.google.android.gm
,W/AudioCapabilities( 6112): Unsupported mime audio/evrc
,W/AudioCapabilities( 6112): Unsupported mime audio/qcelp
W/VideoCapabilities( 6112): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6112): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6112): Unsupported mime audio/qcelp
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.videos/files/Movies/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6112): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.videos/files/Movies
W/AudioCapabilities( 6112): Unsupported mime audio/evrc
I/Icing   ( 4317): Indexing done 736B0110C483B1C6D43A79F22BB0C3E0A2D6B16D
,W/VideoCapabilities( 6112): Unsupported mime video/mp4v-esdp
I/Icing   ( 4317): Indexing 59716A40DEE00805E4208F1709FD830CA906A723 from com.google.android.music
,D/WVCdm   (  276): Instantiating CDM.
I/WVCdm   (  276): CdmEngine::QueryStatus
I/WVCdm   (  276): Level3 Library Dec 11 2014 16:13:16
D/Finsky  ( 6230): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/VideoCapabilities( 6112): Unsupported profile 4 for video/mp4v-es
,W/WVCdm   (  276): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  276): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  276): L1 library not specified. Falling Back to L3
I/WVCdm   (  276): L3 Terminate.
I/ActivityManager(  857): Start proc com.google.android.music:main for content provider com.google.android.music/.icing.IcingContentProvider: pid=6257 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 1945): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1945): UpdateCorporaTask done [took 44 ms] updated apps [took 44 ms] 
,I/MusicStore( 6257): Database version: 120
,D/Finsky  ( 6230): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6230): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6230): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 6230): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3196): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3196): created cursor android.database.sqlite.SQLiteCursor@606a1a6 on behalf of 6230
D/Finsky  ( 6230): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6230): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 6230): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 6230): [745] SignatureUtils.faultInOtherSignatures: Will not allow first-party apps signed by test keys
D/Ads     ( 6230): Skipping gmscore version check
D/Finsky  ( 6230): [745] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.videos
,I/art     (  857): Explicit concurrent mark sweep GC freed 21978(1396KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 12.245ms total 169.243ms
,D/PackageBroadcastService( 4317): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4317): Null package name or gms related package.  Ignoreing.
I/AudioManager( 5827): getMode name:com.lge.qremote
D/Finsky  ( 6230): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6257): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/ActivityManager(  857): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6315 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  857): Killing 5987:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10038/pid_5987/cgroup.procs: No such file or directory
,W/ResourcesManager( 6315): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6315): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2a602a35
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6257): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 6257): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/CalendarProvider2( 6315): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6315): Created com.android.providers.calendar.CalendarAlarmManager@24c88d96(com.android.providers.calendar.CalendarProvider2@2a602a35)
D/CalendarProviderBroadcastReceiver( 6315): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6315): [IntentService] WakeLock acquire, start IntentSerivce
I/AudioManager( 5827): getMode name:com.lge.qremote
,W/ResourcesManager( 6257): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6257): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/CalendarProvider2( 6315): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6315): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
I/AudioManager( 5827): getMode name:com.lge.qremote
D/CalendarProvider2( 6315): [getOrCreateCalendarAlarmManager]
I/AudioManager( 5827): getMode name:com.lge.qremote
I/AudioManager( 5827): getMode name:com.lge.qremote
,I/AudioManager( 5827): getMode name:com.lge.qremote
I/AudioManager( 5827): getMode name:com.lge.qremote
,V/JNIHelp ( 6257): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/Icing   ( 4317): Indexing done 59716A40DEE00805E4208F1709FD830CA906A723
,D/CalendarProvider2( 6315): [IntentService] Release Lock
I/Icing   ( 4317): Not indexing corpus from package com.android.chrome as it has never connected
E/Icing   ( 4317): Aborting indexing of corpus omnibox
,D/CalendarProvider2( 6315): CalendarProviderIntentService.onDestroy()
I/Icing   ( 4317): Indexing 24AE284E02EC07BD7845C2A57E58BAA08F2A03E3 from com.google.android.gms
I/ActivityManager(  857): Killing 6094:com.lge.appbox.client/u0a11 (adj 15): empty #11
I/Icing   ( 4317): Indexing done 24AE284E02EC07BD7845C2A57E58BAA08F2A03E3
I/Icing   ( 4317): Indexing F200CD067697391E5BA8387C554D1EADCF480F28 from com.google.android.gms
W/ActivityThread( 6257): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6257): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@9f5ec19: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/Icing   ( 4317): Indexing done F200CD067697391E5BA8387C554D1EADCF480F28
I/Icing   ( 4317): Indexing 8E811E0C18BDD106917E39D7CA94D72D22D4A1B5 from com.google.android.music
I/ProviderInstaller( 6257): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 6257): GMSCore installation verified
W/libprocessgroup(  857): failed to open /acct/uid_10011/pid_6094/cgroup.procs: No such file or directory
,I/ConfigStore( 6257): Config Database version: 1
I/Icing   ( 4317): Indexing done 8E811E0C18BDD106917E39D7CA94D72D22D4A1B5
I/Icing   ( 4317): Indexing 98E736199A4D0A3DAA0BBDB44355DD80A1943A96 from com.google.android.googlequicksearchbox
,I/Icing   ( 4317): Indexing done 98E736199A4D0A3DAA0BBDB44355DD80A1943A96
I/Icing   ( 4317): Indexing 0A5267A505F47CB39AEB664724AACA2991DAA8A8 from com.google.android.googlequicksearchbox
,I/Icing   ( 4317): Indexing done 0A5267A505F47CB39AEB664724AACA2991DAA8A8
,I/Icing   ( 4317): Indexing 47A5FE9A32182B9012C8EBBEC9FB6699B7BD9AC4 from com.google.android.googlequicksearchbox
I/MediaRouter( 6257): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 6257): type=WIFI subType= reason=null isConnected=true
I/Icing   ( 4317): Indexing done 47A5FE9A32182B9012C8EBBEC9FB6699B7BD9AC4
,I/Icing   ( 4317): Indexing BC9EFFA8FB4EBD74F2B7898FFA6492656D342420 from com.google.android.music
I/Icing   ( 4317): Indexing done BC9EFFA8FB4EBD74F2B7898FFA6492656D342420
,I/Icing   ( 4317): Indexing D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E from com.google.android.gm
I/NetworkMonitor( 6257): type=WIFI subType= reason=null isConnected=true
,I/GHttpClientFactory( 6257): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 6257): Using platform SSLCertificateSocketFactory
I/Icing   ( 4317): Indexing done D5FAA4CC7B77CE1CF3A47D8A751643B189A42F2E
I/Icing   ( 4317): Indexing B7CDD2A0D3DB11D9F7572112AFD71A44FC4A5839 from com.google.android.gms
,I/Icing   ( 4317): Indexing done B7CDD2A0D3DB11D9F7572112AFD71A44FC4A5839
I/Icing   ( 4317): Indexing 67F95B901D405C76FD2CE1ACA2CB152B1EA2BD15 from com.google.android.googlequicksearchbox
I/Icing   ( 4317): Indexing done 67F95B901D405C76FD2CE1ACA2CB152B1EA2BD15
I/ActivityManager(  857): Killing 6158:com.android.contacts/u0a18 (adj 15): empty #11
,I/ActivityManager(  857): Killing 6131:com.android.gallery3d/u0a23 (adj 15): empty #12
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/Icing   ( 4317): updateResources: need to parse f{com.google.android.gms}
W/libprocessgroup(  857): failed to open /acct/uid_10018/pid_6158/cgroup.procs: No such file or directory
,I/NotificationManager( 6257): com.google.android.music: cancel(1061) by com.google.android.music
W/libprocessgroup(  857): failed to open /acct/uid_10023/pid_6131/cgroup.procs: No such file or directory
I/Icing   ( 4317): updateResources: need to parse f{com.google.android.gms}
,I/Icing   ( 4317): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/Icing   ( 4317): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/Icing   ( 4317): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/Icing   ( 4317): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/Icing   ( 4317): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/Icing   ( 4317): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4317): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/ActivityManager(  857): Killing 5583:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10069/pid_5583/cgroup.procs: No such file or directory
,D/Finsky  ( 6230): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  857): RTC_WAKEUP set : Alarm{3542e6fa type 0 when 1457138464023 com.android.vending} when 1457138464023
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  857): android: cancelAsUser(2) by android
,D/libc-netbsd( 6230): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6230): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6230): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6230): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  272): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 6230): propertyValue:false
D/libc-netbsd( 6230): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6230): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 92878953406; DSPS: 3141982; Offset : -3018676338
,D/UEI.SmartControl( 5967): Internal timer expired: 1
,D/libc-netbsd( 6230): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6230): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/GAV2    ( 6010): Thread[GAThread,5,main]: No campaign data found.
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  857): android: cancelAsUser(2) by android
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/qtaguid ( 6230): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6230): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6230): untagSocket(41) failed with errno -22
D/Finsky  ( 6230): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  857): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6376 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  857): android: cancelAsUser(2) by android
,W/ResourcesManager( 6376): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6376): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6376): VM with version 2.1.0 has multidex support
I/MultiDex( 6376): install
I/MultiDex( 6376): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6376): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6376): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6376): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1dee3ce8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6376): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6376): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6376): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,E/MDM     ( 1732): [139] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/ChimeraCfgMgr( 6376): Reading stored module config
,D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
D/LocationInitializer( 4317): Restart initialization of location
,D/ChimeraCfgMgr( 6376): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/GCoreFlp( 1732): No location to return for getLastLocation()
W/FusedLocationProvider( 1732): location=null
I/qtaguid ( 6230): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6230): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6230): untagSocket(41) failed with errno -22
,D/AlertService( 6056): Beginning updateAlertNotification
,D/AlertService( 6056): No fired or scheduled alerts
I/NotificationManager( 6056): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6056): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6056): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6056): com.android.calendar: cancel(3) by com.android.calendar
,I/NotificationManager( 6056): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6056): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6056): com.android.calendar: cancel(6) by com.android.calendar
,I/NotificationManager( 6056): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6056): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6056): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6056): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6056): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6056): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6056): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6056): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6056): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6056): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6056): com.android.calendar: cancel(17) by com.android.calendar
,I/NotificationManager( 6056): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6056): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6056): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6056): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 6056): No events found starting within 1 week.
,D/NativeLibraryUtils( 6376): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6376): Connecting to CarCallService...
,I/art     ( 6376): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6376): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE( 6376): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6376): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6376): Creating a new PhoneAdapter instance
I/art     ( 6230): CheckpointMarkThreadRoots callback created = 0xaae7b5e0
W/ActivityManager(  857): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6376): setListener: com.google.android.gms.car.dn@e4048d7
W/ActivityManager(  857): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6376): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6376): Starting CarCallService with initial phone null
I/art     ( 6230): CheckpointMarkThreadRoots callback created = 0xb042dac0
,I/NotificationManager( 6376): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6376): Package validated; name: com.android.vending
,I/art     ( 5726): Explicit concurrent mark sweep GC freed 2777(108KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 397us total 25.565ms
,I/NotificationManager( 6230): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6230): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/ActivityManager(  857): Process com.google.android.talk (pid 5852) has died
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  857): android: cancelAsUser(2) by android
,I/qtaguid ( 6230): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6230): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6230): untagSocket(41) failed with errno -22
,W/ResourcesManager( 6230): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6230): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6230): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6230): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  857): RTC_WAKEUP set : Alarm{8fd0ddc type 0 when 1457138466892 com.android.vending} when 1457138466892
D/DeviceConnectionService( 1732): client connected with version: 8296000
,D/Finsky  ( 6230): [775] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  857): android: cancelAsUser(2) by android
,D/Finsky  ( 6230): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6230): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/libc-netbsd( 6230): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6230): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6230): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6230): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10036
,D/DnsProxyListener(  272): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
,I/System.out( 6230): propertyValue:false
I/ActivityManager(  857): Killing 6056:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10013/pid_6056/cgroup.procs: No such file or directory
,I/art     (  857): Explicit concurrent mark sweep GC freed 20899(1156KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.014ms total 144.772ms
,I/MusicLeanback( 6257): Conditions not met for autocaching. okToAttempt=false
I/MusicLeanback( 6257): Stop autocaching.
,E/GmsUtils( 6257): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils( 6257): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  857): Killing 6112:com.google.android.videos/u0a99 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10099/pid_6112/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/CAR.SERVICE( 6376): mConnectedToCar = false, abort
,E/ActivityThread( 6376): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@37459cdf that was originally bound here
E/ActivityThread( 6376): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@37459cdf that was originally bound here
E/ActivityThread( 6376): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6376): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6376): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6376): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6376): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6376): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6376): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6376): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6376): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6376): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6376): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6376): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6376): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
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
,E/ActivityThread( 6376): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2410c056 that was originally bound here
E/ActivityThread( 6376): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2410c056 that was originally bound here
E/ActivityThread( 6376): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6376): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6376): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6376): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6376): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6376): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6376): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6376): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6376): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6376): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6376): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6376): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6376): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6376): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6376): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6376): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6376): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6376): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6376): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6376): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6376): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6376): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/ActivityManager(  857): Unbind failed: could not find connection for android.os.BinderProxy@12438537
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/rmt_storage(  270): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  270): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  270): wakelock acquired: 1, error no: 42
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  270): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  270): 
I/rmt_storage(  270): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
W/SQLiteConnectionPool( 4317): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/AlarmManager(  857): RTC_WAKEUP set : Alarm{18e0aaa4 type 0 when 1457138477151 com.google.android.gms} when 1457138477151
,V/AlarmManager(  857): RTC_WAKEUP set : Alarm{3270bbc2 type 0 when 1457138481043 com.android.vending} when 1457138481043
,I/CheckinService( 4317): Checkin interval check for package: unspecified last checkin: 1457138447184 min interval config: 0 actual interval: 35132
,W/ContextImpl( 3668): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/CheckinService( 4317): Checking schedule, now: 1457138482385 next: 1457138477151
I/CheckinService( 4317): active receiver: enabled
,I/CheckinService( 4317): Preparing to send checkin request
I/EventLogService( 4317): Accumulating logs since 1457138442891
,I/CheckinRequestBuilder( 4317): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4317): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 6230): [765] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6230): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  857): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6484 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 6484): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6484): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6484): VM with version 2.1.0 has multidex support
I/MultiDex( 6484): install
I/MultiDex( 6484): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6484): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6484): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6484): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1dee3ce8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6484): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6484): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6484): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1732): callingUid 10006, callindPid: 1732
,E/MDM     ( 1732): [144] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1732): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/art     ( 6484): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6484): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/LocationInitializer( 4317): Restart initialization of location
V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1732): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1732): No location to return for getLastLocation()
,W/FusedLocationProvider( 1732): location=null
D/NativeLibraryUtils( 6484): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  276): Instantiating CDM.
,I/WVCdm   (  276): CdmEngine::OpenSession
I/WVCdm   (  276): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  276): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  276): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  276): L1 library not specified. Falling Back to L3
I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  276): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  276): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
D/WVCdm   (  276): PrepareKeyRequest: nonce=2379906628
I/art     ( 6484): CheckpointMarkThreadRoots callback created = 0xb04d4e40
,I/art     ( 6484): CheckpointMarkThreadRoots callback created = 0xb04d4e30
,I/dex2oat ( 6529): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/dex2oat ( 6529): dex2oat took 111.972ms (threads: 4)
,I/Adreno-EGL( 6484): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6484): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6484): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6484): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6484): Remote Branch: 
I/Adreno-EGL( 6484): Local Patches: 
I/Adreno-EGL( 6484): Reconstruct Branch: 
I/Adreno-EGL( 6484): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6484): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6484): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6484): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6484): Remote Branch: 
I/Adreno-EGL( 6484): Local Patches: 
I/Adreno-EGL( 6484): Reconstruct Branch: 
,I/Adreno-EGL( 6484): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6484): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6484): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6484): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6484): Remote Branch: 
I/Adreno-EGL( 6484): Local Patches: 
I/Adreno-EGL( 6484): Reconstruct Branch: 
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 112890171576; DSPS: 3797709; Offset : -3018658691
,I/CheckinRequestBuilder( 4317): Classify the device as Phone.
,D/libc-netbsd( 4317): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4317): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4317): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4317): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  272): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  272): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 4317): propertyValue:false
D/libc-netbsd( 4317): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4317): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4317): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4317): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4317): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4317): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinTask( 4317): Sending checkin request (7719 bytes)
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/CheckinRequestBuilder( 4317): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4317): Failed to find provider info for com.google.android.wearable.settings
I/WVCdm   (  276): CdmEngine::CloseSession
,I/WVCdm   (  276): L3 Terminate.
,I/CheckinRequestBuilder( 4317): Classify the device as Phone.
,I/CheckinTask( 4317): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4317): Checking schedule, now: 1457138485265 next: 1457665734260
I/CheckinService( 4317): active receiver: disabled
,D/CheckinService( 4317): Recording last checkin time for package unspecified as 1457138485289
I/ActivityManager(  857): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6546 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  305): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 21.846ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 29.586ms
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 24.179ms
,D/PhoneMonitor( 6546): Register our PhoneStateListener
,V/SetupWizard( 6546): Connected to Gservices successfully
,D/PhoneMonitor( 6546): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6546): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6546): [parse] Load xml
V/TelephonyAutoProfiling( 6546): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6546): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6546): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/GCM     ( 1732): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/MusicWidget( 2615): mDelayedStopHandler : unbind
,I/MusicBrowser( 2721): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2721): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2721): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2721): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2721): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2721): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2721): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2721): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  857):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@26e6e95dcom.lge.music.MediaPlaybackService$6@659e2d2
,D/MusicBrowser( 2721): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2721): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2721): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2721): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2721): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@369c83b3
,I/MusicBrowser( 2721): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2721): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2721): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2721): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2721): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2721): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2721): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2721): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2721): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2721): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2721): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2721): [MediaPlaybackService.java:6745:release()] oooooo 
,I/MusicBrowser( 2721): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2721): reset
V/MediaPlayer[Native]( 2721): setListener
,V/MediaPlayer[Native]( 2721): disconnect
V/MediaPlayer[Native]( 2721): destructor
V/AudioFlinger(  276): releasing 19 from 2721 for -1
V/AudioFlinger(  276):  decremented refcount to 0
V/AudioFlinger(  276): purging stale effects
V/MediaPlayer[Native]( 2721): disconnect
D/MusicBrowser( 2721): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2721): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2721): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2721): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
,I/MusicBrowser( 2721): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2721): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2721): [SmartShareManagerClient] unregisterListener: 399359907
W/SmartShareClient( 2721): [SmartShareManagerClient] unregisterListener invalid listener: 399359907
I/SmartShareClient( 2721): [SmartShareManagerClient] terminate service: 2721/MediaPlaybackService/519451825
E/HomeCloudIF( 2721): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2721): [SmartShareManagerClient] unbindService context:android.app.Application@2e1072a0
,V/CloudHub( 2721): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2721): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2721): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2721): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2721): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  857): Killing 6207:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/CloudHub( 2721): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29994
W/libprocessgroup(  857): failed to open /acct/uid_10086/pid_6207/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ActivityManager(  857): Killing 6010:com.google.android.gm/u0a53 (adj 15): empty #11
,I/ActivityManager(  857): Killing 6315:com.android.providers.calendar/u0a14 (adj 15): empty #12
,W/libprocessgroup(  857): failed to open /acct/uid_10053/pid_6010/cgroup.procs: No such file or directory
,W/libprocessgroup(  857): failed to open /acct/uid_10014/pid_6315/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  857): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/ActivityManager(  857): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6578 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,D/administrator(  857): Handling package changes for user 0
,I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/ResourcesManager( 6578): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationService(  857): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  857): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  857): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  857): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  857): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  857): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@25f6b656
,W/ResourcesManager(  857): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourceType(  857): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/Babel_SMS( 6578): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6578): MmsConfig.loadMmsSettings
I/Babel_SMS( 6578): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6578): MmsConfig.loadFromDatabase
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1732): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,E/Babel_SMS( 6578): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6578): MmsConfig.loadFromResources
E/Babel_SMS( 6578): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6578): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
,D/SensorManager( 6578): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6578): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6578): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6578): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6578): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6578): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6578): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6578): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6578): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6578): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6578): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6578): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6578): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6578): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6578): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6578): found sensor: Motion Accel, handle=46
,D/LocationProviderProxy(  857): applying state to connected service
,W/Settings( 6578): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 6578): startup - clean
,I/Babel   ( 6578): deleted: false for 0
,I/art     ( 6578): CheckpointMarkThreadRoots callback created = 0xb042d940
,I/art     ( 6578): CheckpointMarkThreadRoots callback created = 0xb042d910
,W/AudioCapabilities( 6578): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6578): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6578): Unsupported mime audio/g726
W/AudioCapabilities( 6578): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6578): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6578): Unsupported mime video/mjpg
W/VideoCapabilities( 6578): Unsupported mime video/theora
I/ActivityManager(  857): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6626 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/AudioCapabilities( 6578): Unsupported mime audio/evrc
,W/AudioCapabilities( 6578): Unsupported mime audio/qcelp
W/VideoCapabilities( 6578): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6578): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6578): Unsupported mime audio/qcelp
W/AudioCapabilities( 6578): Unsupported mime audio/evrc
,W/VideoCapabilities( 6578): Unsupported mime video/mp4v-esdp
,I/AppUp4:AppBoxCP( 6626): onCreate
W/AppUp4:DB( 6626):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6626):  setFingerPrint start
I/AppUp4:DB( 6626):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/VideoCapabilities( 6578): Unsupported profile 4 for video/mp4v-es
I/AppUp4:DB( 6626):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6626):  SDK version = 0
I/AppUp4:DB( 6626):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6626): AppBoxApplication onCreate()
W/VideoCapabilities( 6578): Unrecognized profile 2130706433 for video/avc
I/AppUp4:CustModeStarterReceiver( 6626): onReceive
I/AppUp4:CustModeStarterReceiver( 6626): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
W/VideoCapabilities( 6578): Unrecognized profile 2130706433 for video/avc
D/AppUp4:CustFacade( 6626): Context : android.app.ReceiverRestrictedContext@17e1eb58
D/AppUp4:CustFacade( 6626): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6626): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6626): begin check event
I/AppUp4:CustModeStarterReceiver( 6626): Event For Nothing, skip.
I/ActivityManager(  857): Killing 5967:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/VideoCapabilities( 6578): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6578): Unrecognized profile 2130706433 for video/avc
W/System.err( 5827): android.os.DeadObjectException
,W/System.err( 5827): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5827): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5827): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5827): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5827): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5827): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5827): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5827): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5827): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5827): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5827): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5827): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5827): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5827): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5827): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5827): android.os.DeadObjectException
W/System.err( 5827): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5827): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5827): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5827): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5827): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5827): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5827): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5827): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5827): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5827): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5827): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5827): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5827): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5827): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5827): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
E/lowmemorykiller(  244): Error opening /proc/5967/oom_score_adj; errno=2
,W/ActivityManager(  857): Exception when unbinding service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  857): android.os.DeadObjectException
W/ActivityManager(  857): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  857): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  857): 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
W/ActivityManager(  857): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1788)
W/ActivityManager(  857): 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:907)
W/ActivityManager(  857): 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15651)
W/ActivityManager(  857): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
W/ActivityManager(  857): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2625)
W/ActivityManager(  857): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:457)
W/ActivityManager(  857): 	at android.os.Binder.execTransact(Binder.java:446)
,W/ActivityManager(  857): Exception when destroying service com.uei.lg.quicksetsdk.lite/com.uei.control.Service
W/ActivityManager(  857): android.os.DeadObjectException
W/ActivityManager(  857): 	at android.os.BinderProxy.transactNative(Native Method)
W/ActivityManager(  857): 	at android.os.BinderProxy.transact(Binder.java:496)
W/ActivityManager(  857): 	at android.app.ApplicationThreadProxy.scheduleStopService(ApplicationThreadNative.java:946)
W/ActivityManager(  857): 	at com.android.server.am.ActiveServices.bringDownServiceLocked(ActiveServices.java:1693)
W/ActivityManager(  857): 	at com.android.server.am.ActiveServices.bringDownServiceIfNeededLocked(ActiveServices.java:1605)
W/ActivityManager(  857): 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1805)
W/ActivityManager(  857): 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:907)
W/ActivityManager(  857): 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15651)
W/ActivityManager(  857): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
W/ActivityManager(  857): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2625)
W/ActivityManager(  857): 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:457)
W/ActivityManager(  857): 	at android.os.Binder.execTransact(Binder.java:446)
W/libprocessgroup(  857): failed to open /acct/uid_10089/pid_5967/cgroup.procs: No such file or directory
I/ActivityManager(  857): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6648 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ActivityManager(  857): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6665 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/vclib   ( 6578): onServiceConnected
,W/Babel   ( 6578): Attempted to change video mute state without an active call.
I/NotificationManager( 6578): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6648): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6648): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6648): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
W/ResourcesManager( 6578): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6578): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6665): Quickset Services start...
I/UEI.SmartControl( 6665): Manufacture = LGE
D/UEI.SmartControl( 6665): File observer start...
E/UEI.SmartControl( 6665): IR Port is disabled: false
D/UEI.SmartControl( 6665): Starting file observer...
D/UEI.SmartControl( 6665): Extracting JNI libs...
D/UEI.SmartControl( 6665): --- this system supports 32-bit or 64-bit only
,V/JNIHelp ( 6578): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppConfig( 6648): Total System Memory = 906309632
I/GalleryUtils( 6648): Application Heap = 96 MB
I/AppConfig( 6648): App Tier : NOT_DEF
D/SystemHelper( 6648): region [EU], country [EU], operator [OPEN], sub-operator []
D/UEI.SmartControl( 6665): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6665): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6665): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,W/System  ( 6578): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6578): Installed default security provider GmsCore_OpenSSL
,I/UEI.SmartControl( 6665): --- Selecting new region: 2
I/UEI.SmartControl( 6665): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6665): Platform has CIR...
,D/UEI.SmartControl( 6665): NO CIR support, need to check package...
I/UEI.SmartControl( 6665): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6665): QS Service created
I/ActivityManager(  857): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6687 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  857): Killing 5827:com.lge.qremote/u0a106 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10106/pid_5827/cgroup.procs: No such file or directory
,E/UEI.SmartControl( 6665): QS start get config
W/ResourcesManager( 6687): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6687): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6687): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 6687): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6687): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6665): Loading JNI Libs...
,D/UEI.SmartControl( 6665):  configuring local db...
I/SystemConfig( 6687): BUILD Country: EU
,I/SystemConfig( 6687): BUILD Operator: OPEN
I/art     (  857): Explicit concurrent mark sweep GC freed 30060(1604KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.099ms total 154.067ms
,I/ActivityManager(  857): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6707 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  857): Killing 6376:com.google.android.gms:car/u0a6 (adj 15): empty #11
D/UEI.SmartControl( 6665):  ---- Has DB8: true
,D/UEI.SmartControl( 6665): QS start statue = true Error code = 0
,D/UEI.SmartControl( 6665): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6665): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6665): IRRCDataComm has AudioManager!!!!.
,I/NotificationManager( 6578): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/SystemConfig( 6687): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6687): existFile = false
I/SystemConfig( 6687): canReadFile = false
I/SystemConfig( 6687): systemFeature RCS result false
D/SystemConfig( 6687): refreshRcsSupport() :false
W/libprocessgroup(  857): failed to open /acct/uid_10006/pid_6376/cgroup.procs: No such file or directory
W/irrc_jni( 6665): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6665): IrrcClient ++ 
D/irrcClient( 6665): getIrrcService ++ 
D/irrcClient( 6665): getIrrcService -- 
D/irrcClient( 6665): IrrcClient -- 
W/irrc_jni( 6665): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6665): Services init done
I/UEI.SmartControl( 6665): Device manager: loading config....
,D/UEI.SmartControl( 6665): QS Service init finished
D/UEI.SmartControl( 6665): QS Service version name: 0.1.73
D/UEI.SmartControl( 6665): QS Service version code: 1073
D/UEI.SmartControl( 6665): Config is loaded...
I/LockScreenSettings( 6707): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
D/UEI.SmartControl( 6665): Service requested: Control
,D/UEI.SmartControl( 6665): Service.onUnbind: IControl
D/UEI.SmartControl( 6665): Service.onDestroy
D/UEI.SmartControl( 6665): Shutdown IRRCPlayer... 
,W/irrc_jni( 6665): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6665): ~IrrcClient ++ 
D/irrcClient( 6665): ~IrrcClient -- 
W/irrc_jni( 6665): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6665):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 6665): Blaster closed
D/UEI.SmartControl( 6665): Blaster closed
D/UEI.SmartControl( 6665): Shut down QS...
D/UEI.SmartControl( 6665): Stopped file observer...
I/UEI.SmartControl( 6665): Notify AllClients services are ready: 0
,I/UEI.SmartControl( 6665): QS lib stop result = true
D/UEI.SmartControl( 6665): QS shutdown complete
,D/UEI.SmartControl( 6665): QS Service created
D/LockScreenSettings( 6707): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6707): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6707): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6707): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6707): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,E/UEI.SmartControl( 6665): QS start get config
D/UEI.SmartControl( 6665):  configuring local db...
,I/ActivityManager(  857): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6730 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  857): Killing 6257:com.google.android.music:main/u0a81 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10081/pid_6257/cgroup.procs: No such file or directory
,W/ResourcesManager( 6730): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6665):  ---- Has DB8: true
,D/UEI.SmartControl( 6665): QS start statue = true Error code = 0
D/UEI.SmartControl( 6665): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6665): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6665): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6665): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6665): IrrcClient ++ 
D/irrcClient( 6665): getIrrcService ++ 
,D/irrcClient( 6665): getIrrcService -- 
D/irrcClient( 6665): IrrcClient -- 
W/irrc_jni( 6665): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6665): Services init done
I/UEI.SmartControl( 6665): Device manager: loading config....
D/UEI.SmartControl( 6665): QS Service init finished
D/UEI.SmartControl( 6665): QS Service version name: 0.1.73
D/UEI.SmartControl( 6665): QS Service version code: 1073
D/UEI.SmartControl( 6665): Service requested: Control
,D/UEI.SmartControl( 6665): Config is loaded...
D/UEI.SmartControl( 6665):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6665): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6665): Request IControl service: devices are loaded...
I/ActivityManager(  857): Killing 6230:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10036/pid_6230/cgroup.procs: No such file or directory
,E/ActivityThread( 6665): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@b77ed22 that was originally bound here
E/ActivityThread( 6665): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@b77ed22 that was originally bound here
E/ActivityThread( 6665): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6665): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6665): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6665): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6665): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6665): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6665): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6665): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6665): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6665): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6665): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6665): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6665): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6665): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6665): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6665): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6665): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6665): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6665): Internal service binding...
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/UpdateIcingCorporaServi( 1945): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  857): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6761 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1945): UpdateCorporaTask done [took 84 ms] updated apps [took 83 ms] 
,I/ActivityManager(  857): Killing 6546:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,W/libprocessgroup(  857): failed to open /acct/uid_10038/pid_6546/cgroup.procs: No such file or directory
D/Finsky  ( 6761): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6761): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6761): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6761): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6761): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3196): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3196): created cursor android.database.sqlite.SQLiteCursor@27797e7 on behalf of 6761
D/Finsky  ( 6761): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6761): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 6761): Skipping gmscore version check
D/Finsky  ( 6761): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 4317): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4317): Null package name or gms related package.  Ignoreing.
D/UEI.SmartControl( 6665): Internal timer expired: 2
W/System.err( 6665): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@b77ed22
,D/Finsky  ( 6761): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/Icing   ( 4317): updateResources: need to parse f{com.google.android.gms}
W/System.err( 6665): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 6665): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 6665): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 6665): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 6665): 	at com.uei.control.Service.a(Unknown Source)
W/System.err( 6665): 	at com.uei.control.l.run(Unknown Source)
,W/System.err( 6665): 	at java.util.Timer$TimerImpl.run(Timer.java:284)
E/UEI.SmartControl( 6665): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@b77ed22
I/Icing   ( 4317): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4317): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  857): Killing 6484:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10006/pid_6484/cgroup.procs: No such file or directory
,I/CloudHub( 2721): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19954
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  857): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,E/UEI.SmartControl( 6665): file observer is disposed!
,I/ActivityManager(  857): Killing 2721:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  276): 2721 died, releasing its sessions
V/AudioFlinger(  276):  pid 1751 @ 0
V/AudioFlinger(  276):  pid 3142 @ 1
V/AudioFlinger(  276):  pid 3142 @ 2
,W/libprocessgroup(  857): failed to open /acct/uid_10028/pid_2721/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6665): Internal timer expired: 3
,D/UEI.SmartControl( 6665): Service.onUnbind: IControl
D/UEI.SmartControl( 6665): Service.onDestroy
W/System.err( 6665): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1c51a80f
W/System.err( 6665): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 6665): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 6665): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 6665): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 6665): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 6665): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 6665): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 6665): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 6665): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6665): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6665): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6665): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6665): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6665): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6665): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6665): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1c51a80f
D/UEI.SmartControl( 6665): Shutdown IRRCPlayer... 
W/irrc_jni( 6665): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6665): ~IrrcClient ++ 
D/irrcClient( 6665): ~IrrcClient -- 
W/irrc_jni( 6665): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6665): Blaster closed
D/UEI.SmartControl( 6665): Blaster closed
D/UEI.SmartControl( 6665): Shut down QS...
I/UEI.SmartControl( 6665): QS lib stop result = true
D/UEI.SmartControl( 6665): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 132891629522; DSPS: 4453117; Offset : -3018666761
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{1b2e459e type 2 when 138964 com.google.android.gms} when 138964
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1732): Vacuum at: now=1457138510556 tag=VacuumService
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  857): ALS enabled for SRE
D/PowerManagerServiceEx(  857): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26531 ms ago)
,D/qdlights(  857): set_light_backlight: 251
,D/qdlights(  857): set_light_backlight: 248
,D/qdlights(  857): set_light_backlight: 245
,D/qdlights(  857): set_light_backlight: 241
,D/qdlights(  857): set_light_backlight: 238
,D/qdlights(  857): set_light_backlight: 235
,D/qdlights(  857): set_light_backlight: 231
,D/qdlights(  857): set_light_backlight: 228
,D/qdlights(  857): set_light_backlight: 225
,D/qdlights(  857): set_light_backlight: 221
,D/qdlights(  857): set_light_backlight: 218
,D/qdlights(  857): set_light_backlight: 215
,D/qdlights(  857): set_light_backlight: 211
,D/qdlights(  857): set_light_backlight: 208
,D/qdlights(  857): set_light_backlight: 205
,D/qdlights(  857): set_light_backlight: 201
,D/qdlights(  857): set_light_backlight: 198
,D/qdlights(  857): set_light_backlight: 195
,D/qdlights(  857): set_light_backlight: 191
,D/qdlights(  857): set_light_backlight: 188
,D/qdlights(  857): set_light_backlight: 185
,D/qdlights(  857): set_light_backlight: 181
,D/qdlights(  857): set_light_backlight: 178
,D/qdlights(  857): set_light_backlight: 175
,D/qdlights(  857): set_light_backlight: 171
,D/qdlights(  857): set_light_backlight: 168
,D/qdlights(  857): set_light_backlight: 164
,D/qdlights(  857): set_light_backlight: 161
,D/qdlights(  857): set_light_backlight: 158
,D/qdlights(  857): set_light_backlight: 154
,D/qdlights(  857): set_light_backlight: 151
,D/qdlights(  857): set_light_backlight: 148
,D/qdlights(  857): set_light_backlight: 144
,D/qdlights(  857): set_light_backlight: 141
,D/qdlights(  857): set_light_backlight: 138
,D/qdlights(  857): set_light_backlight: 134
,D/qdlights(  857): set_light_backlight: 131
,D/qdlights(  857): set_light_backlight: 128
,D/qdlights(  857): set_light_backlight: 124
,D/qdlights(  857): set_light_backlight: 121
,D/qdlights(  857): set_light_backlight: 118
,D/qdlights(  857): set_light_backlight: 114
,D/qdlights(  857): set_light_backlight: 111
,D/qdlights(  857): set_light_backlight: 108
,D/qdlights(  857): set_light_backlight: 104
,D/qdlights(  857): set_light_backlight: 101
,D/qdlights(  857): set_light_backlight: 98
,D/qdlights(  857): set_light_backlight: 94
,D/qdlights(  857): set_light_backlight: 91
,D/qdlights(  857): set_light_backlight: 88
,D/qdlights(  857): set_light_backlight: 84
,D/qdlights(  857): set_light_backlight: 81
,D/qdlights(  857): set_light_backlight: 78
,D/qdlights(  857): set_light_backlight: 74
,D/qdlights(  857): set_light_backlight: 71
,D/qdlights(  857): set_light_backlight: 68
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/qdlights(  857): set_light_backlight: 64
D/qdlights(  857): set_light_backlight: 61
,D/qdlights(  857): set_light_backlight: 58
,D/qdlights(  857): set_light_backlight: 54
,D/qdlights(  857): set_light_backlight: 52
,D/qdlights(  857): set_light_backlight: 48
,D/qdlights(  857): set_light_backlight: 45
,D/qdlights(  857): set_light_backlight: 42
,D/qdlights(  857): set_light_backlight: 38
,D/qdlights(  857): set_light_backlight: 35
,D/qdlights(  857): set_light_backlight: 32
,D/qdlights(  857): set_light_backlight: 28
,D/qdlights(  857): set_light_backlight: 25
,D/qdlights(  857): set_light_backlight: 22
,D/qdlights(  857): set_light_backlight: 18
,D/qdlights(  857): set_light_backlight: 15
,D/qdlights(  857): set_light_backlight: 12
,D/qdlights(  857): set_light_backlight: 10
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  857): acquireWakeLockInternal: lock=85227639, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,D/WeatherService( 2712): 2 : TimeTick Intent has been received, Time(hour:min:sec) 1:42:0
D/WeatherService( 2712): 2 : TimeTick Intent And Screen On
D/WeatherService( 2712): 2 : SDK version : 21
W/ActivityManager(  857): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2712): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2712): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2712): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2712): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2712): 2 : This is isUpdating : false
D/WeatherService( 2712): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2712): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2712): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2712): 2 : Fixed theme : optimus
,D/WeatherReflect( 2712): 2 : Map key string is -2
D/lim     ( 2712): 2 : time = 01:42
I/WeatherReflect( 2712): Model Name : LG-D722
D/WeatherTheme( 2712): 2 : Different view - status_min_formatted : 41 != 42
D/WeatherTheme( 2712): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2712): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2712): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2712): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2712): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2712): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2712): forecast size is 0
D/Theme   ( 2712): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2712): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2712): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2712): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2712): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2712): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2712): setTouchIntent, appWidgetId: 2
,D/Theme_WeatherAncestor_optimus( 2712): url is : null
D/Theme   ( 2712): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2712): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2712): 2 : update view, appWidgetId: 2
D/WeatherService( 2712): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 1:42:0
D/PowerManagerServiceEx(  857): releaseWakeLockInternal: lock=85227639 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 152893878994; DSPS: 5108551; Offset : -3018675825
,I/PowerManagerService(  857): ALS enabled for SRE
D/PowerManagerServiceEx(  857): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33529 ms ago)
,I/PowerManagerService(  857): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  857): ALS enabled for SRE
D/PowerManagerServiceEx(  857): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33556 ms ago)
W/ContextImpl(  857): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  857): Sleeping (uid 1000)...
D/LPWGController(  857): [updateScreenState] screen on = false
D/LPWGController(  857): disable proximity sensor
,D/LPWGController(  857): enable proximity sensor
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
I/SensorManager(  857): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@975bce4] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  857): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  857): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  857): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  857): activate: handle is 48, enable
,V/sensors_hal_Ctx(  857): activate sensors is 1400000000000
D/sensors_hal_Thresh(  857): enable: handle=48
I/sensors_hal_SAM(  857): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  857): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  857): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  857): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
,D/sensors_hal_Thresh(  857): enable: Received response: 0
D/PowerManagerServiceEx(  857): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33655 ms ago)
I/Adreno-EGL(  857): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  857): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  857): Build Date: 03/02/15 Mon
I/Adreno-EGL(  857): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  857): Remote Branch: 
I/Adreno-EGL(  857): Local Patches: 
I/Adreno-EGL(  857): Reconstruct Branch: 
,D/PermissionCache(  247): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (145 us)
,I/Sensors (  407): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  857): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,I/sensors_hal_SAM(  857): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  857): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  857): processInd: handle 48, count=1
V/sensors_hal_Thresh(  857): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  857): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  857): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  857): poll: count: 256
I/sensors_hal_Ctx(  857): poll: released wakelock sensor_ind
D/sensors_hal_Util(  857): waitForResponse: timeout=0
D/LPWGController(  857): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  857): current mode = 1  value = 1 1
I/LPWGController(  857): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
,I/LPWGController(  857): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  857): set_light_backlight: 0
,I/SensorManager(  857): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  857): activate: handle is 46, disable
V/sensors_hal_Ctx(  857): activate sensors is 1000000000000
D/sensors_hal_LP2(  857): enable: handle=46
D/sensors_hal_LP2(  857): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  857): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  247): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  247): hwc_blank: Blanking display: 0
V/sensors_hal_SAM(  857): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  857): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
I/DisplayManagerService(  857): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  857): Display changed displayId=0
,D/DSDPConnection( 1751): Display #0 changed.
,D/qdhwcomposer(  247): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  857): Excessive delay in setPowerMode(): 203ms
I/qdhwcomposer(  247): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  857): Got set_interactive hint
,D/KeyguardViewMediator( 1373): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1332): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1373): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1332): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): handleNotifyScreenOFF
D/KeyguardViewMediator( 1373): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,D/KeyguardViewMediator( 1373): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1373): unregisterProximitySensor
,D/WifiServerServiceExt(  857): sendKtScanInterval  mRtspPlay : false
D/JX-Cordova( 4858): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4858): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4858): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a1cbf85 added. We now have 3 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4858): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4858): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@267641da added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4858): addListener: New listener added - the number of listeners is now 1
V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=on, calling pid 857
D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=on
V/voice   (  276): voice_set_parameters: enter: screen_state=on
D/StatusBarWindowView( 1373): onScreenTurnedOff why = 3
D/BluetoothAdapterService(192408866)( 1994): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3ad2da88
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: exit
V/voice   (  276): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  276): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  276): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  276): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  276): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  276): adev_set_parameters: exit with code(0)
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4858): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
,W/System.err( 4858): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4858): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4858): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4858): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4858): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4858): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4858): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4858): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4858): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4858): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4858): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4858): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4858): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4858): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/WifiServerServiceExt(  857): set CMD_KT_SCAN_INTERVAL
D/GpsLocationProvider(  857): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1840): |CORE| sendScreenState: state:true
I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDService( 1804): stopPatternFlashing()
D/Cliptray Service( 1804): lockStatus = 0
,D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): updateLightsLocked : turn off led
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1804): RESTART MSG
D/SplitWindow(  857): check instance of lgWin Window{94e2513 u0 SearchPanel}
,D/LNfcService( 1787): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1787): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1787): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1787): isRequireNfcCRouting() return true
D/LNfcService( 1787): isHCERoutingtoHost() return : true
D/NfcService( 1787): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): newParams.techmask= mTechMask: default
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): screenState= 3
D/NfcService( 1787): Discovery configuration equal, not updating.
,D/Ulp_jni (  857): JNI:system_update. Event-0
D/InputDispatcher(  857): Window went away: Window{32b81aff u0 SearchPanel}
,I/[SystemUI]Clock( 1373): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1373): time changed, timezoneChanged : false
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,I/Sensors (  407): sns_pwr.c(301):releasing wakelock
D/WeatherService( 2712): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:42:6
,D/WeatherService( 2712): 2 : ACTION screen on
D/WeatherService( 2712): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2712): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2712): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 1:42:6
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): ACTION_SCREEN_ON
D/AppCleanupService( 4142): android.intent.action.SCREEN_ON
,V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=off, calling pid 857
,D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: enter: screen_state=off
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  276): voice_extn_compress_voip_set_parameters: exit
V/voice   (  276): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  276): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  276): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  276): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  276): adev_set_parameters: exit with code(0)
D/WifiController(  857): CMD_SCREEN_OFF 
D/WifiController(  857): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  857): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:false
,I/LEDService( 1804): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1804): stopPatternFlashing()
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1804): set_light_notifications: 0,0,0,0,3
I/LEDService( 1804): updateLightsLocked : turn on led
D/VolumeVibrator( 1804): clear
E/LEDService( 1804): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1804): Can't handle this request of patternId:0
D/LEDHandler( 1804): RESTART MSG
I/Cliptray Service( 1804): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/LNfcService( 1787): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1787): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1877): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2712): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:42:6
D/WeatherService( 2712): 2 : ACTION screen off
D/WeatherService( 2712): 2 : TimeTick Receiver Unregister
D/WeatherService( 2712): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 1:42:6
,W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): ACTION_SCREEN_OFF
D/AppCleanupService( 4142): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4142): AppUsageStatsSaveTask
E/NxpNfcJni( 1787): getReconnectState = 0x0
,D/LCardEmulationManager( 1787): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1787): getDefaultRoute
D/LNfcService( 1787): isRequireNfcCRouting() return true
D/LNfcService( 1787): isHCERoutingtoHost() return : true
D/NfcService( 1787): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): newParams.techmask= mTechMask: 0
D/NfcService( 1787): mEnableLPD: true
D/NfcService( 1787): mEnableReader: false
D/NfcService( 1787): mEnableHostRouting: true
D/NfcService( 1787): screenState= 1
E/NxpNfcJni( 1787): getReconnectState = 0x0
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{543c350 type 2 when 159513 com.android.systemui} when 159513
,D/KeyguardViewMediator( 1373): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1751): getCallState : 0
D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1373): isHdmiPluggedIn :false
,D/KeyguardViewMediator( 1373): doKeyguard: not showing because lockscreen is off
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 172896130927; DSPS: 5763986; Offset : -3018712631
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1732): disconnect managed GoogleApiClient
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{33cb949 type 2 when 185575 com.google.android.gms} when 185575
,I/PhenotypeConfigurator( 1732): Scheduling Phenotype for one-off execution 5912 seconds from now (1457138557291)
,I/PhenotypeFlagCommitter( 1732): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1732): Using platform SSLCertificateSocketFactory
,I/art     ( 1732): Explicit concurrent mark sweep GC freed 48040(2MB) AllocSpace objects, 12(192KB) LOS objects, 40% free, 13MB/22MB, paused 1.610ms total 90.143ms
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  272): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 1732): propertyValue:false
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1732): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1732): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1732): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{50eafe type 2 when 190706 android} when 190706
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 192898386864; DSPS: 6419418; Offset : -3018654012
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 212900609884; DSPS: 7074852; Offset : -3018689267
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 232902761350; DSPS: 7730281; Offset : -3018643487
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 252904978459; DSPS: 8385715; Offset : -3018684679
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 272907220091; DSPS: 9041148; Offset : -3018670856
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 292908722146; DSPS: 9696560; Offset : -3018753371
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 312910732442; DSPS: 10351987; Offset : -3018790097
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  857): acquireWakeLockInternal: lock=85227639, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{881a25f type 2 when 315607 android} when 315607
D/PowerManagerServiceEx(  857): releaseWakeLockInternal: lock=85227639 [*alarm*], flags=0x0
,I/NotificationManager(  857): android: cancelAsUser(-1548111331) by android
,I/NotificationManager( 6730): com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
,I/NotificationManager(  857): android: cancelAsUser(2145784878) by android
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 327913067035; DSPS: 10843580; Offset : -3018683340
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/LocationManagerService(  857): remove 1a526a8b
D/LocationManagerService(  857): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  857): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  857): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  857): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/PowerManagerServiceEx(  857): acquireWakeLockInternal: lock=85227639, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{e0c0fae type 2 when 345918 android} when 345918
I/ActivityManager(  857): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6982 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 6982): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6982): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@17e1eb58
,D/PowerManagerServiceEx(  857): releaseWakeLockInternal: lock=85227639 [*alarm*], flags=0x0
I/ActivityManager(  857): Killing 6626:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10011/pid_6626/cgroup.procs: No such file or directory
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 347915405808; DSPS: 11499015; Offset : -3018633125
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 362917552818; DSPS: 11990606; Offset : -3018653071
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 380421063152; DSPS: 12564165; Offset : -3018774355
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 395423395862; DSPS: 13055761; Offset : -3018760928
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 410425726318; DSPS: 13547355; Offset : -3018688799
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 430427997797; DSPS: 14202788; Offset : -3018645104
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 445430657335; DSPS: 14694396; Offset : -3018668691
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 465433097770; DSPS: 15349835; Offset : -3018641333
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 485435463893; DSPS: 16005273; Offset : -3018654018
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 505437705246; DSPS: 16660703; Offset : -3018548947
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 520442924814; DSPS: 17152401; Offset : -3018761637
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 535450439018; DSPS: 17644166; Offset : -3018723849
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 554205005235; DSPS: 18258714; Offset : -3018674679
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 574207325491; DSPS: 18914152; Offset : -3018734636
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 589209724037; DSPS: 19405749; Offset : -3018686125
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 606713323910; DSPS: 19979305; Offset : -3018626188
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 621716026622; DSPS: 20470915; Offset : -3018670032
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 639219469366; DSPS: 21044476; Offset : -3018920070
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 654230735972; DSPS: 21536352; Offset : -3018517463
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 667363181170; DSPS: 21966677; Offset : -3018549072
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 680499162775; DSPS: 22397120; Offset : -3018645478
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 693945519766; DSPS: 22837730; Offset : -3018638454
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 711448694132; DSPS: 23411272; Offset : -3018576829
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 726450692344; DSPS: 23902858; Offset : -3018592908
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 267
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 267, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 267
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 741455222155; DSPS: 24394522; Offset : -3018457525
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 756467359250; DSPS: 24886433; Offset : -3018252855
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 770545165097; DSPS: 25347747; Offset : -3018633042
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 266, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 790865626220; DSPS: 26013609; Offset : -3018667576
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 810867933613; DSPS: 26669045; Offset : -3018679519
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 830870742216; DSPS: 27324495; Offset : -3018617212
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 265, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 265
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 850873006001; DSPS: 27979932; Offset : -3018703489
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 870875244023; DSPS: 28635364; Offset : -3018662836
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 890877590644; DSPS: 29290801; Offset : -3018666043
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 910879862905; DSPS: 29946236; Offset : -3018682391
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 930882029774; DSPS: 30601668; Offset : -3018712997
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  857): acquireWakeLockInternal: lock=85227639, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{367de14f type 2 when 949187 com.android.bluetooth} when 949187
D/PowerManagerServiceEx(  857): releaseWakeLockInternal: lock=85227639 [*alarm*], flags=0x0
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/art     (  857): Explicit concurrent mark sweep GC freed 73031(3MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 23MB/34MB, paused 3.216ms total 256.657ms
,W/bt-smp  ( 1994): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1994): Plain text(LSB ~ MSB) = ca 27 72 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 1994): Encrypted text(LSB ~ MSB) = fb ce ea 71 83 b4 b8 07 6e 0d 8d 5f 41 6d 10 bc 
,W/bt-btm  ( 1994): Stopping oneshot timer
D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 950883563917; DSPS: 31257077; Offset : -3018674449
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 264
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 264, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 264
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 970885927508; DSPS: 31912514; Offset : -3018660374
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 990888225133; DSPS: 32567950; Offset : -3018682137
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1010890470100; DSPS: 33223384; Offset : -3018695522
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1030892805262; DSPS: 33878820; Offset : -3018679617
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1050895089674; DSPS: 34534255; Offset : -3018683998
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1070897351054; DSPS: 35189687; Offset : -3018619832
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1085899700326; DSPS: 35681286; Offset : -3018681682
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 263, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 263
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 263
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1099655275491; DSPS: 36132024; Offset : -3018538517
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1115914159958; DSPS: 36664795; Offset : -3018534639
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1129045906194; DSPS: 37095100; Offset : -3018654858
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1149366009086; DSPS: 37760952; Offset : -3018742395
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 262
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 262
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 262, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1164368347218; DSPS: 38252546; Offset : -3018662538
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1179370750937; DSPS: 38744150; Offset : -3018822113
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 262
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 262
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 262, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  857): battery changed pluggedType: 2
D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 262
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 262, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 262
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1194373107507; DSPS: 39235744; Offset : -3018723974
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 261
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 261, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 261
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1214375616422; DSPS: 39891183; Offset : -3018626079
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/UsageStatsService(  857): User[0] Flushing usage stats to disk
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1229377924513; DSPS: 40382778; Offset : -3018606755
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1244379759452; DSPS: 40874346; Offset : -3018236789
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1257522707163; DSPS: 41305027; Offset : -3018630011
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1804): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  477): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1994): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 261
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1804): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1804): Battery Level Remaining: 100%
D/LEDHandler( 1804): Battery Temp: 261, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 261
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1275026145613; DSPS: 41878580; Offset : -3018639997
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:26000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1290028424350; DSPS: 42370176; Offset : -3018680621
,TIME-OUT KILL (timeout was 1200000ms)
```
