#### Test 60124347d4f5b03_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
V/JNIHelp ( 4883): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
--------- beginning of system
W/ActivityThread( 4883): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4883): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@120618b7: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4883): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 4883): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 4883): com.google.android.gms: cancel(39789) by com.google.android.gms
I/NotificationManager( 4811): com.google.android.music: cancel(1061) by com.google.android.music
I/GAv4-SVC( 4883): Google Analytics 8.4.89 is starting up.
I/ActivityManager(  842): Killing 4602:com.lge.qmemoplus/1000 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_1000/pid_4602/cgroup.procs: No such file or directory
D/eas_req ( 4862): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
D/NativeLibraryUtils( 4883): Install completed successfully. count=14 extracted=0
D/LGDMClient( 4637): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4637): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4637): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4637): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 4637): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 4637): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4637): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4637): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/HubEmail( 4862): JNI_OnLoad()
I/HubEmail( 4862): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4862): registerNatives()
I/HubEmail( 4862): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4862): registerNativeMethods()
I/HubEmail( 4862): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 4862): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  842): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=4931 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/Settings( 4862): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/ContextImpl( 4637): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4637): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 4637): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 4637): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 4637): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/AndroidRuntime( 4923): 
D/AndroidRuntime( 4923): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4923): CheckJNI is OFF
D/LGDMClient( 4637): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  842): Killing 4774:com.lge.bnr/1000 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_1000/pid_4774/cgroup.procs: No such file or directory
I/AppUp4:AppBoxCP( 4931): onCreate
W/AppUp4:DB( 4931):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 4931):  setFingerPrint start
I/AppUp4:DB( 4931):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 4931):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4931):  SDK version = 0
I/AppUp4:DB( 4931):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 4931): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 4931): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4931): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4931): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 4931): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 4931): onReceive
I/AppUp4:CustModeStarterReceiver( 4931): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 4931): Context : android.app.ReceiverRestrictedContext@352deacc
D/AppUp4:CustFacade( 4931): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4931): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 4931): begin check event
I/AppUp4:CustModeStarterReceiver( 4931): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4931): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4931): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 4931): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 4931): handleAsyncCustNotification do not startCustService
I/ActivityManager(  842): Killing 4713:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_1000/pid_4713/cgroup.procs: No such file or directory
I/LgeMiscReceiver( 3134): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3134): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3134): networkInfo.isConnected() = true
D/PhoneState( 3134): setPdpRejectCasuse : false
D/AndroidRuntime( 4923): Calling main entry com.android.commands.am.Am
I/ActivityManager(  842): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=4965 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  842): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  842): setTaskToReturnTo : TaskRecord{35776b23 #224 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  842): setTaskToReturnTo : TaskRecord{35776b23 #224 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  842): AppWindowTokenEx init.. 
D/ContextHelper(  842): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
D/InputDispatcher(  842): Focus left window: Window{217cc2d1 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 4923): Shutting down VM
I/PhoneWindow(  842): [generateLayout] setColorNavigationBar => color=0x ff000001
I/[LGHome]EVENT( 1877): [Launcher.java:986:onPause()]onPause
D/PhoneWindowEx(  842): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  842): [setNavigationBarColor2] color=0x fff5f5f5
D/SplitWindow(  842): check instance of lgWin Window{20d1b9b u0 Starting com.test.thalitest}
I/ActivityManager(  842): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4982 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1877): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/WindowStateAnimator(  842): Starting window displayed
D/WindowManager(  842): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/SystemUI[Framework](  842): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  842): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  842): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  842): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  842): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@14d3a93b,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  842): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1372): notify navigation bar color(0xfff5f5f5)
I/[SystemUI]NavigationThemeResource( 1372): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1372):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1372): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]EVENT( 1877): [Launcher.java:5214:onStop()]onStop
W/ActivityThread( 1877): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
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
I/HotwordDetector( 1936): Closing mic
I/MicrophoneInputStream( 1936): mic_close com.google.android.apps.gsa.speech.audio.u@55ed477
V/AudioRecord( 1936): stop()
D/AudioRecord( 1936): AudioRecord->stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): RecordThread::stop
V/AudioFlinger(  282): Record stopped OK
V/AudioPolicyManager(  282): stopInput() input 17
V/AudioPolicyService(  282): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  282): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  282): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  282): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  282): ThreadBase::setParameters() routing=0
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
,V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb4297000
D/audio_hw_primary(  282): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
I/ActivityManager(  842): Activity reported stop, but no longer stopping: ActivityRecord{2654338f u0 com.lge.launcher2/.Launcher t223}
V/audio_hw_primary(  282): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  282): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  282): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  282): disable_audio_route: reset and update mixer path: audio-record
,V/audio_hw_primary(  282): disable_audio_route: exit
E/audio_hw_primary(  282): disable_snd_device: enter 144
D/hardware_info(  282): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  282): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  282): stop_input_stream: exit: status(0)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyManager(  282): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  282): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  282): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  282): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioPolicyService(  282): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  282): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  282): setParameters(): io 17, keyvalue hotword_active=0, calling pid 282
V/AudioFlinger(  282): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  282): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  282): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  282): in_set_parameters: exit: status(0)
,V/AudioFlinger(  282): processConfigEvents_l() DONE thread 0xb4297000
V/AudioFlinger(  282): RecordThread: loop stopping
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
D/ContextHelper( 4982): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
V/AudioRecord( 1936): stop()
V/AudioRecord( 1936): stop()
V/AudioRecord( 1936): stop()
V/AudioFlinger(  282): RecordHandle::stop()
V/AudioFlinger(  282): releasing 16 from 1936 for -1
V/AudioFlinger(  282): RecordThread::stop
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/AudioPolicyManager(  282): releaseInput() 17
V/AudioPolicyManager(  282): closeInput(17)
V/AudioFlinger(  282): closeInput() 17
,V/AudioSystem(  282): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  842): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1936): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  282): ThreadBase::exit
V/AudioFlinger(  282): RecordThread: loop starting
V/AudioFlinger(  282): RecordThread 0xb4297000 exiting
D/audio_hw_primary(  282): adev_close_input_stream: enter:stream_handle(0xb4036520)
D/audio_hw_primary(  282): in_standby: enter: stream (0xb4036520) usecase(7: audio-record)
V/audio_hw_primary(  282): in_standby: exit:  status(0)
V/AudioSystem( 3134): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1372): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2726): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1989): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  282): AudioCommandThread() adding update audio port list
V/AudioSystem( 1751): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  282): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  282): releaseInput() exit
V/AudioPolicyService(  282): AudioCommandThread() waking up
V/AudioPolicyService(  282): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  282): AudioCommandThread() going to sleep
V/AudioFlinger(  282): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  282): removeClient_l() pid 1936, calling pid 282
I/HotwordRecognitionRnr( 1936): Stopping hotword detection.
I/HotwordRecognitionRnr( 1936): Hotword detection finished
D/PhoneMonitor( 4965): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 4965): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4965): onReceive CONNECTIVITY_CHANGE networkType=1
,I/WebViewFactory( 4982): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/ActivityManager(  842): Killing 4681:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 4660): android.os.DeadObjectException
,W/System.err( 4660): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4660): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4660): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 4660): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 4660): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4660): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4660): 	at android.os.Handler.handleCallback(Handler.java:739)
,W/System.err( 4660): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4660): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4660): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4660): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4660): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4660): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4660): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4660): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 4660): android.os.DeadObjectException
W/System.err( 4660): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4660): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4660): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 4660): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 4660): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4660): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4660): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4660): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4660): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4660): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4660): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4660): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4660): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4660): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4660): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
D/PhoneMonitor( 4965): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 4965): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 4965): [parse] Load xml
V/TelephonyAutoProfiling( 4965): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 4965): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 4965): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  842): failed to open /acct/uid_10089/pid_4681/cgroup.procs: No such file or directory
,W/ActivityManager(  842): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
V/DownloadManager( 3215): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,I/LibraryLoader( 4982): Time to load native libraries: 2 ms (timestamps 1100-1102)
I/LibraryLoader( 4982): Expected native library version number "",actual native library version number ""
,I/ActivityManager(  842): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5010 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
V/DownloadManager( 3215): DownloadService onCreate
,V/WebViewChromiumFactoryProvider( 4982): Binding Chromium to main looper Looper (main, tid 1) {352deacc}
I/DownloadManager( 3215): in removeSpuriousFiles
I/LibraryLoader( 4982): Expected native library version number "",actual native library version number ""
V/DownloadManager( 3215): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/chromium( 4982): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/NotificationManager( 3215): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3215): created cursor android.database.sqlite.SQLiteCursor@6cefdf5 on behalf of 3215
I/DownloadManager( 3215): in trimDatabase
V/DownloadManager( 3215): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3215): created cursor android.database.sqlite.SQLiteCursor@291a1fb on behalf of 3215
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/BrowserStartupController( 4982): Initializing chromium process, singleProcess=true
W/art     ( 4982): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 4982): ApplicationContext is null in ApplicationStatus
,I/ActivityManager(  842): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5031 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
V/DownloadManager( 3215): DownloadService onStartCommand
V/DownloadManager( 3215): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3215): created cursor android.database.sqlite.SQLiteCursor@33de8471 on behalf of 3215
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
,I/CheckinService( 4883): Checkin interval check for package: unspecified last checkin: 1457380272427 min interval config: 0 actual interval: 19287078
,I/CheckinService( 4883): Disabling old GoogleServicesFramework version
,D/UEI.SmartControl( 5010): Quickset Services start...
I/UEI.SmartControl( 5010): Manufacture = LGE
,D/UEI.SmartControl( 5010): File observer start...
E/UEI.SmartControl( 5010): IR Port is disabled: false
D/UEI.SmartControl( 5010): Starting file observer...
D/UEI.SmartControl( 5010): Extracting JNI libs...
D/UEI.SmartControl( 5010): --- this system supports 32-bit or 64-bit only
V/DownloadManager( 3215): DownloadService onDestroy
,D/DrmBroadcastReceiver( 5031): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 5031): 1  network is available. Sync DRM Time with NTP
V/DrmService( 5031): Service onCreate
D/DrmService( 5031): Received new request = 2
D/WeatherAncestor( 2708): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:12:39
D/UpdateThreadPoolManager( 2708): 2 : This is isUpdating : false
,I/DrmSntpClient( 5031): Start Sync process
D/DrmSntpClient( 5031): Server : 0
D/WeatherAncestor( 2708): connectivity changed - connection : true
D/libc-netbsd( 5031): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5031): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5031): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5031): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10051
I/CheckinService( 4883): Checking schedule, now: 1457399559618 next: 1457380302393
D/DnsProxyListener(  277): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
I/CheckinService( 4883): active receiver: enabled
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/Weather_cast( 2708): 2 : isUpdateNeedForAlarm : no city return false
,D/WeatherAncestor( 2708): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 2:12:39
D/WeatherService( 2708): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
,I/CheckinService( 4883): Preparing to send checkin request
V/AudioPolicyService(  282): registerClient() client 0xb4027040, uid 10316
D/BluetoothManagerService(  842): Message: 20
D/BluetoothManagerService(  842): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1c9d1bb2:true
I/EventLogService( 4883): Accumulating logs since 1457398185069
D/BluetoothAdapterService(512031259)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19ce39c9
,D/UEI.SmartControl( 5010): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5010): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5010): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 5031): propertyValue:false
,I/ActivityManager(  842): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5068 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  842): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2708): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2708): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
,D/WeatherService( 2708): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/UEI.SmartControl( 5010): --- Selecting new region: 2
I/UEI.SmartControl( 5010): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5010): Platform has CIR...
D/UEI.SmartControl( 5010): NO CIR support, need to check package...
I/UEI.SmartControl( 5010): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 5010): QS Service created
I/LGDrmClient( 5031): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  295): eDRM_SetDRMTime +++
I/LGDRM   (  295): [DRM] SET TIME : YR=2016, MON=3, DAY=8
I/LGDRM   (  295): [DRM] SET TIME : HR=1, MIN=12, SEC=38
,V/ILGDrmService(  295): eDRM_SetDRMTime ---
I/DrmSntpClient( 5031): Synched
D/DrmService( 5031): Completed !! request = 2
D/DrmService( 5031): Request count = 0
V/DrmService( 5031): Service onDestroy
E/UEI.SmartControl( 5010): QS start get config
,W/ResourcesManager( 5068): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/art     ( 4883): CheckpointMarkThreadRoots callback created = 0xaae7b690
,D/UEI.SmartControl( 5010): Loading JNI Libs...
,D/UEI.SmartControl( 5010):  configuring local db...
I/art     ( 4883): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 4883): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 4883): CheckpointMarkThreadRoots callback created = 0xb042d430
,I/ActivityManager(  842): Waited long enough for: ServiceRecord{340b388 u0 com.lge.springcleaning/.service.AppCleanupService}
,W/art     ( 4982): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 4982): onDetachedFromWindow called when already detached. Ignoring
,I/PhoneWindow( 4982): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 4982): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 4982): [setNavigationBarColor2] color=0x fff5f5f5
D/SystemWebViewEngine( 4982): CordovaWebView is running on device made by: LGE
W/art     ( 4982): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4982): Attempt to remove local handle scope entry from IRT, ignoring
,I/NotificationManager( 4883): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/Activity( 4982): Activity.onPostResume() called 
,D/OpenGLRenderer( 4982): Render dirty regions requested: true
I/OpenGLRenderer( 4982): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4982): Enabling debug mode 0
D/Atlas   ( 4982): Validating map...
,D/SplitWindow(  842): check instance of lgWin Window{705a4c8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 4982): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/UEI.SmartControl( 5010):  ---- Has DB8: true
D/UEI.SmartControl( 5010): QS start statue = true Error code = 0
D/UEI.SmartControl( 5010): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5010): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,D/UEI.SmartControl( 5010): IRRCDataComm has AudioManager!!!!.
D/InputDispatcher(  842): Focus entered window: Window{705a4c8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/irrc_jni( 5010): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5010): IrrcClient ++ 
D/irrcClient( 5010): getIrrcService ++ 
D/irrcClient( 5010): getIrrcService -- 
D/irrcClient( 5010): IrrcClient -- 
W/irrc_jni( 5010): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5010): Services init done
,I/UEI.SmartControl( 5010): Device manager: loading config....
D/UEI.SmartControl( 5010): QS Service init finished
D/UEI.SmartControl( 5010): QS Service version name: 0.1.73
D/UEI.SmartControl( 5010): QS Service version code: 1073
D/UEI.SmartControl( 5010): Service requested: Control
,D/UEI.SmartControl( 5010): Config is loaded...
I/ActivityManager(  842): Displayed com.test.thalitest/.MainActivity: +1s351ms
D/UEI.SmartControl( 5010):  ----- QS SDK is ready!!!
I/Timeline(  842): Timeline: Activity_windows_visible id: ActivityRecord{268f7820 u0 com.test.thalitest/.MainActivity t224} time:71972
D/UEI.SmartControl( 5010): Request IControl service: devices are loaded...
,I/UEI.SmartControl( 5010): Notify AllClients services are ready: 0
I/ActivityManager(  842): Killing 4738:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 5010): -----IControl: 11
W/InputMethodManagerService(  842): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
D/UEI.SmartControl( 5010): Caller: com.lge.qremote
D/UEI.SmartControl( 5010): ------------ IControl registerCallback...
,I/UEI.SmartControl( 5010): Registering callback...
D/UEI.SmartControl( 5010): -----IControl: 19
D/UEI.SmartControl( 5010): Caller: com.lge.qremote
I/UEI.SmartControl( 5010): Registering Services Ready callback...
I/UEI.SmartControl( 5010): Notify client services are ready...
D/UEI.SmartControl( 5010): -----IControl: 8
D/UEI.SmartControl( 5010): Caller: com.lge.qremote
I/Timeline( 4982): Timeline: Activity_idle id: android.os.BinderProxy@98063a6 time:72008
,D/UEI.SmartControl( 5010): Internal service binding...
,W/libprocessgroup(  842): failed to open /acct/uid_1000/pid_4738/cgroup.procs: No such file or directory
W/BindingManager( 4982): Cannot call determinedVisibility() - never saw a connection for the pid: 4982
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/Babel_SMS( 5068): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5068): MmsConfig.loadMmsSettings
I/Babel_SMS( 5068): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/Babel_SMS( 5068): MmsConfig.loadFromDatabase
I/CheckinRequestBuilder( 4883): Checkin reason type: 8 attempt count: 1
,I/art     ( 5068): CheckpointMarkThreadRoots callback created = 0xb042d6a0
,E/Babel_SMS( 5068): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5068): MmsConfig.loadFromResources
E/Babel_SMS( 5068): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5068): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,E/ActivityThread( 4883): Failed to find provider info for com.google.android.wearable.settings
,D/SensorManager( 5068): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5068): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5068): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5068): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5068): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5068): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5068): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5068): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5068): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5068): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5068): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5068): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5068): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5068): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5068): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5068): found sensor: Motion Accel, handle=46
I/art     ( 5068): CheckpointMarkThreadRoots callback created = 0xb042d680
W/art     ( 5068): Suspending all threads took: 8.280ms
,W/Settings( 5068): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5068): startup - clean
D/JsMessageQueue( 4982): Set native->JS mode to OnlineEventsBridgeMode
,I/Babel   ( 5068): deleted: false for 0
,I/art     ( 4035): Explicit concurrent mark sweep GC freed 2768(110KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 890us total 74.613ms
,I/ActivityManager(  842): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5122 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 5068): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5068): Unsupported mime audio/adpcm
,W/AudioCapabilities( 5068): Unsupported mime audio/g726
W/AudioCapabilities( 5068): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5068): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 5068): Unsupported mime video/mjpg
W/VideoCapabilities( 5068): Unsupported mime video/theora
,W/AudioCapabilities( 5068): Unsupported mime audio/evrc
,W/AudioCapabilities( 5068): Unsupported mime audio/qcelp
W/VideoCapabilities( 5068): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5068): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5068): Unsupported mime audio/qcelp
W/AudioCapabilities( 5068): Unsupported mime audio/evrc
W/VideoCapabilities( 5068): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5068): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5068): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5068): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5068): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5068): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 5068): onServiceConnected
,W/Babel   ( 5068): Attempted to change video mute state without an active call.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 5068): com.google.android.talk: cancel(10436) by com.google.android.talk
D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 72961164040; DSPS: 2482066; Offset : -2791047438
,W/art     ( 5068): Suspending all threads took: 15.778ms
,D/jxcore_app_log( 4982): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622882176
D/libc-netbsd( 5068): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5068): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5068): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5068): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  277): App 10061 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 5068): propertyValue:false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4982): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4982):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4982):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4982):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4982):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4982): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a7ea218 added. We now have 1 listener(s)
,I/ActivityManager(  842): Process com.google.android.music:main (pid 4811) has died
D/BluetoothManagerService(  842): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4982): setBluetoothMacAddress: F8:95:C7:87:85:54
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4982): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4982): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
,D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4982): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4982):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4982):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4982):     - Bluetooth MAC address: F8:95:C7:87:85:54
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4982):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4982):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4982):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4982):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4982):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4982):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4982): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27c7c7c4 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4982): addListener: New listener added - the number of listeners is now 1
D/BluetoothAdapterService(512031259)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19ce39c9
,I/Babel   ( 5068): connection state changed from UNKNOWN to CONNECTED
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4982): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4982): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4982): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4982): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4982): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
,W/System.err( 4982): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4982): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4982): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4982): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
,W/System.err( 4982): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4982): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4982): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4982): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4982): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/JX-Cordova( 4982): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4982): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4982): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1485f6ad added. We now have 2 listener(s)
D/BluetoothManagerService(  842): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4982): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4982): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4982): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4982): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@500ede2 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4982): addListener: New listener added - the number of listeners is now 1
,D/BluetoothAdapterService(512031259)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19ce39c9
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4982): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4982): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4982): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4982): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
,W/System.err( 4982): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4982): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4982): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4982): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4982): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4982): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4982): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4982): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4982): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4982): 	at android.os.HandlerThread.run(HandlerThread.java:61)
E/VoldCmdListener(  249): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  249): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5122): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  249): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  249): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5122): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
,E/VoldCmdListener(  249): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  249): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5122): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
E/VoldCmdListener(  249): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  249): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5122): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 5122): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5122):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5122):   adb logcat -s GAv4
W/GAv4    ( 5122): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
W/GAv4    ( 5122): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QPairHandler( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
W/GAv4    ( 5122): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
D/administrator(  842): Handling package changes for user 0
I/InputReader(  842): Reconfiguring input devices.  changes=0x00000010
,W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
,W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
W/ResourceType(  842): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/art     ( 1786): CheckpointMarkThreadRoots callback created = 0xaaf22bd0
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/art     ( 1786): CheckpointMarkThreadRoots callback created = 0xb042d7e0
I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/NotificationService(  842): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  842): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  842): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  842): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  842): applying state to connected service
,V/BackupManagerService(  842): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  842): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@37e6cd71
,I/NotificationManager(  842): android: cancelAsUser(2) by android
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  842): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5176 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/art     (  309): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 309us total 22.228ms
I/WebViewFactory( 5122): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 20.560ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 20.631ms
,I/ActivityManager(  842): Process com.lge.email (pid 4862) has died
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
,W/ResourcesManager( 5176): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5176): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/LibraryLoader( 5122): Time to load native libraries: 2 ms (timestamps 3744-3746)
,I/LibraryLoader( 5122): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5122): Binding Chromium to main looper Looper (main, tid 1) {3669b619}
I/LibraryLoader( 5122): Expected native library version number "",actual native library version number ""
I/chromium( 5122): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
I/BrowserStartupController( 5122): Initializing chromium process, singleProcess=true
,W/art     ( 5122): Attempt to remove local handle scope entry from IRT, ignoring
I/art     (  842): Explicit concurrent mark sweep GC freed 34327(1828KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.534ms total 189.624ms
E/SysUtils( 5122): ApplicationContext is null in ApplicationStatus
I/MultiDex( 5176): VM with version 2.1.0 has multidex support
I/MultiDex( 5176): install
I/MultiDex( 5176): VM has multidex support, MultiDex support library is disabled.
W/chromium( 5122): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5122): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5122): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5122): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5122): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5122): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5122): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5122): Remote Branch: 
I/Adreno-EGL( 5122): Local Patches: 
I/Adreno-EGL( 5122): Reconstruct Branch: 
V/JNIHelp ( 5176): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,V/AudioPolicyService(  282): registerClient() client 0xb4027080, uid 10079
,W/AudioManagerAndroid( 5122): Requires BLUETOOTH permission
I/NSApplication( 5122): Starting up...
,W/ActivityThread( 5176): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5176): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6b850a9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5176): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5176): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5176): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 5176): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5176): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/ActivityManager(  842): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5215 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/NativeLibraryUtils( 5176): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  282): Instantiating CDM.
,I/WVCdm   (  282): CdmEngine::OpenSession
,I/WVCdm   (  282): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  282): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  282): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  282): L1 library not specified. Falling Back to L3
,I/GoogleURLConnFactory( 5176): Using platform SSLCertificateSocketFactory
D/libc-netbsd( 5176): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5176): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5176): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5176): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
D/WVCdm   (  282): PrepareKeyRequest: nonce=1321867145
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 5176): propertyValue:false
,I/ActivityManager(  842): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5238 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  842): Killing 4660:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_10106/pid_4660/cgroup.procs: No such file or directory
,W/ResourcesManager( 5238): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/libc-netbsd( 5176): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5176): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5176): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5176): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 5176): CheckpointMarkThreadRoots callback created = 0xaaf45f70
,I/art     ( 5176): CheckpointMarkThreadRoots callback created = 0xaaf45f60
,I/ActivityManager(  842): Killing 3413:com.android.defcontainer/u0a4 (adj 15): empty #11
,W/libprocessgroup(  842): failed to open /acct/uid_10004/pid_3413/cgroup.procs: No such file or directory
,I/iu.SyncManager( 4883): SYNC; picasa accounts
,D/NetworkLogImpl( 4883): Loaded NetworkSpeedPredictor
I/iu.Environment( 4883): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 4883): num queued entries: 0
,I/iu.UploadsManager( 4883): num updated entries: 0
I/iu.SyncManager( 4883): NEXT; no task
I/ActivityManager(  842): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=5278 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 5278): onReceive: android.intent.action.ALARM_CHANGED
,I/ActivityManager(  842): Killing 4637:com.lge.lgdmsclient/1000 (adj 15): empty #11
I/WVCdm   (  282): CdmEngine::OpenSession
,D/WeatherAncestor( 2708): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 2:12:43
,W/libprocessgroup(  842): failed to open /acct/uid_1000/pid_4637/cgroup.procs: No such file or directory
D/UpdateThreadPoolManager( 2708): 2 : This is isUpdating : false
D/Weather_cast( 2708): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2708): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 2:12:43
D/WeatherService( 2708): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
I/ActivityManager(  842): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5300 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
W/ActivityManager(  842): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2708): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2708): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2708): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 5300): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  842): Message: 20
D/BluetoothManagerService(  842): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1cd3d851:true
,D/BluetoothAdapterService(512031259)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19ce39c9
D/BluetoothAdapterService(512031259)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19ce39c9
V/SmsReceiverService( 3134): onStart: #1 mResultCode: -1 = Activity.RESULT_OK
D/MmsConfig( 3134): isNotAllowedSms: currentUser:0
D/MmsConfig( 3134): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3134): isUserMode:false
D/SmsReceiverService( 3134): handleMessage isUserMode:false
,V/SmsReceiverService( 3134): handleMessage action: com.android.mms.transaction.SEND_MESSAGE error: 0
D/SmsReceiverService( 3134): [LGE] handleSendMessage Send messages in queue
V/AlarmManager(  842): RTC_WAKEUP set : Alarm{334c0a53 type 0 when 1457399564104 com.google.android.googlequicksearchbox} when 1457399564104
,I/[LGHome]LGNumberBadgeReceiver( 1877): [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = lge.intent.action.UNREAD_MESSAGES
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1877): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1877): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1877): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1877): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
,I/ActivityManager(  842): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=5329 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/ResourcesManager( 5329): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5329): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5329): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5329): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5329): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 5329): Using schema version: 115
I/IndexDatabaseHelper( 5329): Index is fine
,I/WVCdm   (  282): CdmEngine::CloseSession
,D/UsbSettingsReceiver( 5329): [AUTORUN] onReceive() : action = android.hardware.usb.action.USB_STATE
D/UsbSettingsReceiver( 5329): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 5329): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5329): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5329): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsReceiver( 5329): [AUTORUN] onReceive() : getDefaultFunction = ptp_only
D/UsbSettingsReceiver( 5329): [AUTORUN] onReceive() : USB_FUNCTION_CDROM_STORAGE = false
D/UsbSettingsReceiver( 5329): [AUTORUN] onReceive() : mDirectAutorun = true
D/UsbSettingsReceiver( 5329): [AUTORUN] onReceive() : mActivityUsbModeChange = false
D/UsbSettingsReceiver( 5329): [AUTORUN] onReceive() : mActivityFinish = false
D/UsbSettingsReceiver( 5329): [AUTORUN] onReceive() : ===== USB Configured =====
,D/UsbSettingsControl( 5329): [AUTORUN] setUsbConnected() : connected=true
D/UsbSettingsReceiver( 5329): [AUTORUN] onReceive() : checkQmicm = ptp_only,adb
I/WVCdm   (  282): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  282): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  282): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  282): CdmEngine::GenerateKeyRequest
D/UsbSettingsReceiver( 5329): [AUTORUN] : topPackageName=com.test.thalitest
D/UsbSettingsReceiver( 5329): [AUTORUN] : topClassName=com.test.thalitest.MainActivity
D/WVCdm   (  282): PrepareKeyRequest: nonce=3487204276
D/UsbSettingsReceiver( 5329): [AUTORUN] Not exist com.android.LGSetupWizard
D/UsbSettingsReceiver( 5329): [AUTORUN] setUsbConnect() : mUsbSettingsRun = false
,D/UsbSettingsReceiver( 5329): [AUTORUN] startUsbSettings() : deviceProvisioned=1
I/ActivityManager(  842): Killing 4931:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_10011/pid_4931/cgroup.procs: No such file or directory
,I/ActivityManager(  842): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5355 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/MtpService( 3215): updating state; isCurrentUser=true, mMtpLocked=false
,I/PCSuite ( 5355): [StartReceiver]USB CONNECTED ver UsbManger : ptp_only
I/PCSuite ( 5355): [StartReceiver]isUsbPCSuiteMode : false
,D/PCSuite ( 5355): [StartReceiver][checkEUTStatus] eutStatus = 
D/PCSuite ( 5355): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5355): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  842): Killing 4965:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_10038/pid_4965/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 5010): Internal timer expired: 1
D/UEI.SmartControl( 5010): Service.onUnbind: IControl
D/UEI.SmartControl( 5010): Service.onDestroy
W/System.err( 5010): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1e84fa1b
V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{11b7df90 type 2 when 76967 android} when 76967
,W/System.err( 5010): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 5010): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 5010): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 5010): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 5010): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 5010): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 5010): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 5010): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 5010): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5010): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5010): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5010): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5010): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5010): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5010): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5010): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1e84fa1b
D/UEI.SmartControl( 5010): Shutdown IRRCPlayer... 
,V/LGMDMManager( 5300): Create singleton instance
W/irrc_jni( 5010): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5010): ~IrrcClient ++ 
D/irrcClient( 5010): ~IrrcClient -- 
W/irrc_jni( 5010): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5010): Blaster closed
D/UEI.SmartControl( 5010): Blaster closed
D/UEI.SmartControl( 5010): Shut down QS...
,D/UEI.SmartControl( 5010): Stopped file observer...
I/UEI.SmartControl( 5010): QS lib stop result = true
D/UEI.SmartControl( 5010): QS shutdown complete
D/AlertReceiver( 3870): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 3870): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 3870): [updateWidgets] 
,D/MonthWidgetProvider( 3870): [onReceive]
D/CalendarWidgetProvider( 3870): [onReceive]
D/CalendarWidgetProvider( 3870): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 3870): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 3870): [onReceive]
D/CalendarWidgetProvider( 3870): [onReceive]
D/CalendarWidgetProvider( 3870): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,I/DigitalAppWidgetProvider( 5278): onReceive: android.intent.action.ALARM_CHANGED
D/WeatherAncestor( 2708): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 2:12:45
D/UpdateThreadPoolManager( 2708): 2 : This is isUpdating : false
D/Weather_cast( 2708): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2708): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 2:12:45
,D/WeatherService( 2708): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
W/ActivityManager(  842): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2708): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2708): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2708): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/CalendarTypeController( 3870): [onCreate] mContext.getPackageName() = com.android.calendar
I/[SystemUI]SafeModeBroadcastReceiver( 1372): onReceive = com.lge.statusbar.bootcompleted
,D/CalendarWeatherReceiver( 3870): Get action=com.lge.calendar.action.WEATHER_SERVICE_START
I/ActivityManager(  842): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.MediaScanReceiver: pid=5376 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,E/MediaScanReceiver( 5376): media scanning start or checking
,W/MainApplication( 5376): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ActivityManager(  842): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5399 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  842): Killing 5010:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/chromium( 4982): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
I/chromium( 4982): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,W/libprocessgroup(  842): failed to open /acct/uid_10089/pid_5010/cgroup.procs: No such file or directory
,I/MusicStore( 5399): Database version: 120
,E/VoldCmdListener(  249): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  249): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5399): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  249): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  249): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5399): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  249): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  249): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5399): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,W/ResourcesManager( 5399): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5399): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5399): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,W/ActivityThread( 5399): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5399): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2c0083a8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5399): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5399): GMSCore installation verified
I/ConfigStore( 5399): Config Database version: 1
,I/MediaRouter( 5399): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 5399): type=WIFI subType= reason=null isConnected=true
D/NightModeReceiver( 5329): [Nightmode] Enter receiver
,D/NightModeReceiver( 5329): [Nightmode] NIGHT_MODE_ACTION_START
D/NightModeInfo( 5329): [Nightmode] setNightNodeTabSettings
,D/NightModeInfo( 5329): [Nightmode] getAlreadyNightModeDB() : 0
D/NightModeInfo( 5329): [Nightmode] getUserBrightnessChange() : 0
D/NightModeInfo( 5329): [Nightmode] getUserBrightnessChangeNoNight() : 0
D/NightModeInfo( 5329): [Nightmode] getTabNightCheck
I/NetworkMonitor( 5399): type=WIFI subType= reason=null isConnected=true
,V/SettingsProvider(  842): call_put(system:already_night_mode=0) for 0 calling package = com.android.settings
V/SettingsProvider(  842): call_put(system:user_change_brightness=0) for 0 calling package = com.android.settings
V/SettingsProvider(  842): call_put(system:user_change_brightness_no_night=0) for 0 calling package = com.android.settings
V/SettingsProvider(  842): call_put(system:night_mode_enabled=0) for 0 calling package = com.android.settings
D/NightModeInfo( 5329): [Nightmode] setTabNightCheck : 0
V/SettingsProvider(  842): call_put(system:save_tab_night_check=0) for 0 calling package = com.android.settings
I/WVCdm   (  282): CdmEngine::CloseSession
,D/ToneMappingReceiver( 5278): Enter doAlarmRingToneUriMapping()
I/WVCdm   (  282): L3 Terminate.
I/GHttpClientFactory( 5399): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 5399): Using platform SSLCertificateSocketFactory
D/ToneMappingReceiver( 5278): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5278): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
,D/CommonUtil( 5278): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5278): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5278): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5278): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5278): Alarm Success count is 0
D/ToneMappingReceiver( 5278): Timer Success count is 0
,I/ActivityManager(  842): Killing 5031:com.lge.drmservice/u0a51 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_10051/pid_5031/cgroup.procs: No such file or directory
I/NotificationManager( 5399): com.google.android.music: cancel(1061) by com.google.android.music
,I/MediaScannerReceiver( 3870): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///system/media
I/InitNotificationRingtoneService( 3870): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3870): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
E/MediaScanReceiver( 5376): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 5376): android.intent.action.MEDIA_SCANNER_FINISHED
,I/AlertUtils( 3870): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
E/MediaScanReceiver( 5376): media scanning start or checking
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,D/ToneMappingReceiver( 5278): Enter doAlarmRingToneUriMapping()
D/ToneMappingReceiver( 5278): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5278): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5278): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5278): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5278): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5278): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5278): Alarm Success count is 0
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
D/ToneMappingReceiver( 5278): Timer Success count is 0
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/MediaScannerReceiver( 3870): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///storage/emulated/0
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
E/MediaScanReceiver( 5376): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 5376): android.intent.action.MEDIA_SCANNER_FINISHED
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/art     ( 5399): CheckpointMarkThreadRoots callback created = 0xb042d390
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3870): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,I/art     ( 5399): CheckpointMarkThreadRoots callback created = 0xb042d360
I/ActivityManager(  842): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5450 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AlertUtils( 3870): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3870): End InitializeAlertRingtoneService.onHandleIntent
,I/InitNotificationRingtoneService( 3870): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3870): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/AlertUtils( 3870): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
W/ResourcesManager( 5450): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3870): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
D/CalendarProvider2( 5450): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2194c4d2
,I/AlertUtils( 3870): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3870): End InitializeAlertRingtoneService.onHandleIntent
D/CalendarProvider2( 5450): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5450): Created com.android.providers.calendar.CalendarAlarmManager@338a8cff(com.android.providers.calendar.CalendarProvider2@2194c4d2)
I/art     (  842): Explicit concurrent mark sweep GC freed 19498(1061KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 4.769ms total 161.401ms
D/CalendarProviderBroadcastReceiver( 5450): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5450): [IntentService] WakeLock acquire, start IntentSerivce
,D/CalendarProvider2( 5450): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 5450): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5450): [getOrCreateCalendarAlarmManager]
I/MediaStoreImporter( 5399): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
D/LocationInitializer( 4883): Restart initialization of location
,E/MDM     ( 1733): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
I/dex2oat ( 5473): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ActivityManager(  842): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5479 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/CalendarProvider2( 5450): [IntentService] Release Lock
,D/CalendarProvider2( 5450): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  842): Killing 5068:com.google.android.talk/u0a61 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/dex2oat ( 5473): dex2oat took 131.997ms (threads: 4)
,W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
W/libprocessgroup(  842): failed to open /acct/uid_10061/pid_5068/cgroup.procs: No such file or directory
,I/Adreno-EGL( 5176): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5176): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5176): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5176): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5176): Remote Branch: 
I/Adreno-EGL( 5176): Local Patches: 
I/Adreno-EGL( 5176): Reconstruct Branch: 
,W/IcingInternalCorpora( 4883): getNumBytesRead when not calculated.
,I/Adreno-EGL( 5176): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5176): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5176): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5176): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5176): Remote Branch: 
I/Adreno-EGL( 5176): Local Patches: 
I/Adreno-EGL( 5176): Reconstruct Branch: 
,W/ActivityManager(  842): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Adreno-EGL( 5176): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5176): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5176): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5176): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5176): Remote Branch: 
I/Adreno-EGL( 5176): Local Patches: 
I/Adreno-EGL( 5176): Reconstruct Branch: 
,I/Gmail   ( 5479): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5479): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  842): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5479): Error finding the version of the Email provider.....
E/Gmail   ( 5479): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5479): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5479): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5479): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5479): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5479): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5479): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5479): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5479): We do not support migrating this version of the Email provider.
,I/Gmail   ( 5479): getAccountsCursor
I/ActivityManager(  842): Killing 5122:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/libprocessgroup(  842): failed to open /acct/uid_10079/pid_5122/cgroup.procs: No such file or directory
,W/ActivityManager(  842): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 5479): Observing account changes for notifications
,W/ActivityManager(  842): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/CheckinRequestBuilder( 4883): Classify the device as Phone.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,V/DownloadManager( 3215): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3215): created cursor android.database.sqlite.SQLiteCursor@274e62d7 on behalf of 4883
W/InstanceID/Rpc( 4883): Found 10006
,D/libc-netbsd( 4883): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4883): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4883): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4883): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 4883): propertyValue:false
I/ActivityManager(  842): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5545 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 21.264ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 327us total 20.155ms
,D/libc-netbsd( 4883): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4883): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 20.277ms
,I/Gmail   ( 5479): notifyAccountChanged
I/Gmail   ( 5479): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/DownloadManager( 3215): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3215): created cursor android.database.sqlite.SQLiteCursor@27c7c7c4 on behalf of 4883
V/DownloadManager( 3215): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,I/Gmail   ( 5479): getAccountsCursor
V/DownloadManager( 3215): created cursor android.database.sqlite.SQLiteCursor@1485f6ad on behalf of 4883
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5479): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5479): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5479): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/libc-netbsd( 4883): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4883): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4883): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4883): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4883): Sending checkin request (9933 bytes)
,D/PhoneMonitor( 5545): Register our PhoneStateListener
,I/ActivityManager(  842): Killing 5215:com.android.chrome/u0a48 (adj 15): empty #11
,I/art     ( 4035): Explicit concurrent mark sweep GC freed 3160(123KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 1.493ms total 37.489ms
W/libprocessgroup(  842): failed to open /acct/uid_10048/pid_5215/cgroup.procs: No such file or directory
,D/PhoneMonitor( 5545): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5545): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5545): [parse] Load xml
I/CheckinService( 4883): Checkin interval check for package: unspecified last checkin: 1457380272427 min interval config: 0 actual interval: 19296029
,V/TelephonyAutoProfiling( 5545): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5545): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Gmail   ( 5479): getAccountsCursor
D/PhoneMonitor( 5545): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  842): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5573 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5573): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/CheckinResponseProcessor( 4883): From server: 1 gservices updates and 0 deletes
,I/art     (  842): Explicit concurrent mark sweep GC freed 14373(668KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 14.138ms total 169.297ms
,I/art     ( 5573): CheckpointMarkThreadRoots callback created = 0xb042d430
,I/Babel_SMS( 5573): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5573): MmsConfig.loadMmsSettings
I/Babel_SMS( 5573): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5573): MmsConfig.loadFromDatabase
I/art     ( 5573): CheckpointMarkThreadRoots callback created = 0xb042d410
E/Babel_SMS( 5573): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5573): MmsConfig.loadFromResources
E/Babel_SMS( 5573): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5573): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5573): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5573): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5573): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5573): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5573): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5573): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5573): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5573): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5573): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5573): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5573): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5573): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5573): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5573): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5573): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5573): found sensor: Motion Accel, handle=46
W/Settings( 5573): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5573): startup - clean
I/CertBlacklister(  842): Certificate blacklist changed, updating...
I/Babel   ( 5573): deleted: false for 0
I/GservicesProvider( 4035): main difference update completed
I/CertBlacklister(  842): Certificate blacklist updated
I/CheckinRequestBuilder( 4883): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4883): Failed to find provider info for com.google.android.wearable.settings
W/AudioCapabilities( 5573): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5573): Unsupported mime audio/adpcm
W/AudioCapabilities( 5573): Unsupported mime audio/g726
W/AudioCapabilities( 5573): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5573): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5573): Unsupported mime video/mjpg
W/VideoCapabilities( 5573): Unsupported mime video/theora
W/AudioCapabilities( 5573): Unsupported mime audio/evrc
W/AudioCapabilities( 5573): Unsupported mime audio/qcelp
W/VideoCapabilities( 5573): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5573): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5573): Unsupported mime audio/qcelp
W/AudioCapabilities( 5573): Unsupported mime audio/evrc
W/VideoCapabilities( 5573): Unsupported mime video/mp4v-esdp
I/CheckinRequestBuilder( 4883): Classify the device as Phone.
I/VideoCapabilities( 5573): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 5573): Unrecognized profile 2130706433 for video/avc
I/CheckinTask( 4883): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
W/VideoCapabilities( 5573): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5573): Unrecognized profile 2130706433 for video/avc
I/CheckinService( 4883): Checking schedule, now: 1457399569646 next: 1457926818633
I/CheckinService( 4883): active receiver: disabled
W/VideoCapabilities( 5573): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 5573): onServiceConnected
W/Babel   ( 5573): Attempted to change video mute state without an active call.
I/CheckinService( 4883): Checking schedule, now: 1457399569698 next: 1457926818633
I/CheckinService( 4883): active receiver: disabled
,D/CheckinService( 4883): Recording last checkin time for package unspecified as 1457399569708
I/NotificationManager( 5573): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 5573): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5573): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  842): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5628 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AudioManager( 5300): getMode name:com.lge.qremote
,I/AudioManager( 5300): getMode name:com.lge.qremote
I/AudioManager( 5300): getMode name:com.lge.qremote
,V/JNIHelp ( 5573): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/AudioManager( 5300): getMode name:com.lge.qremote
,I/AudioManager( 5300): getMode name:com.lge.qremote
D/UEI.SmartControl( 5628): Quickset Services start...
,I/UEI.SmartControl( 5628): Manufacture = LGE
D/UEI.SmartControl( 5628): File observer start...
E/UEI.SmartControl( 5628): IR Port is disabled: false
D/UEI.SmartControl( 5628): Starting file observer...
D/UEI.SmartControl( 5628): Extracting JNI libs...
,D/UEI.SmartControl( 5628): --- this system supports 32-bit or 64-bit only
,I/ActivityManager(  842): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5647 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/System  ( 5573): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5573): Installed default security provider GmsCore_OpenSSL
,W/ResourcesManager( 5647): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5647): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5647): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5628): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5628): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5628): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/LGEmail ( 5647): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
I/UEI.SmartControl( 5628): --- Selecting new region: 2
,I/UEI.SmartControl( 5628): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5628): Platform has CIR...
D/UEI.SmartControl( 5628): NO CIR support, need to check package...
I/UEI.SmartControl( 5628): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5628): QS Service created
D/LGEmail ( 5647): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,E/UEI.SmartControl( 5628): QS start get config
D/UEI.SmartControl( 5628): Loading JNI Libs...
D/UEI.SmartControl( 5628):  configuring local db...
,I/PackageChangeReceiver( 5647): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  842): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5675 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  842): Killing 5238:com.google.android.apps.plus/u0a86 (adj 15): empty #11
D/AlertService( 3870): Beginning updateAlertNotification
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 5628):  ---- Has DB8: true
,D/UEI.SmartControl( 5628): QS start statue = true Error code = 0
W/libprocessgroup(  842): failed to open /acct/uid_10086/pid_5238/cgroup.procs: No such file or directory
D/UEI.SmartControl( 5628): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5628): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5628): IRRCDataComm has AudioManager!!!!.
,D/AlertService( 3870): No fired or scheduled alerts
I/NotificationManager( 3870): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(3) by com.android.calendar
,I/NotificationManager( 3870): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(5) by com.android.calendar
,I/NotificationManager( 3870): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(11) by com.android.calendar
W/irrc_jni( 5628): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5628): IrrcClient ++ 
D/irrcClient( 5628): getIrrcService ++ 
D/irrcClient( 5628): getIrrcService -- 
D/irrcClient( 5628): IrrcClient -- 
W/irrc_jni( 5628): IRRCPlayer_nativeInit -- 
I/NotificationManager( 3870): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(20) by com.android.calendar
,D/UEI.SmartControl( 5628): Services init done
I/UEI.SmartControl( 5628): Device manager: loading config....
D/UEI.SmartControl( 5628): QS Service init finished
D/UEI.SmartControl( 5628): QS Service version name: 0.1.73
D/UEI.SmartControl( 5628): Config is loaded...
D/UEI.SmartControl( 5628): QS Service version code: 1073
,D/UEI.SmartControl( 5628): Service requested: Control
D/UEI.SmartControl( 5628): Internal service binding...
D/UEI.SmartControl( 5628): -----IControl: 11
D/UEI.SmartControl( 5628): Caller: com.lge.qremote
D/UEI.SmartControl( 5628): ------------ IControl registerCallback...
I/UEI.SmartControl( 5628): Registering callback...
,D/UEI.SmartControl( 5628): -----IControl: 19
D/UEI.SmartControl( 5628): Caller: com.lge.qremote
I/UEI.SmartControl( 5628): Registering Services Ready callback...
I/UEI.SmartControl( 5628): Notify client services are ready...
D/UEI.SmartControl( 5628): -----IControl: 8
,D/UEI.SmartControl( 5628): Caller: com.lge.qremote
D/AlertService( 3870): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/UEI.SmartControl( 5628):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5628): Notify AllClients services are ready: 0
,I/ActivityManager(  842): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5703 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  842): Killing 5329:com.android.settings/1000 (adj 15): empty #11
,I/ActivityManager(  842): Killing 5355:com.lge.sync/1000 (adj 15): empty #12
,W/libprocessgroup(  842): failed to open /acct/uid_1000/pid_5329/cgroup.procs: No such file or directory
,W/libprocessgroup(  842): failed to open /acct/uid_1000/pid_5355/cgroup.procs: No such file or directory
D/AlarmScheduler( 3870): No events found starting within 1 week.
I/ActivityManager(  842): Killing 5278:com.lge.clock/u0a10 (adj 15): empty #11
,I/AppUp4:AppBoxCP( 5703): onCreate
,W/AppUp4:DB( 5703):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 5703):  setFingerPrint start
I/AppUp4:DB( 5703):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 5703):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5703):  SDK version = 0
I/AppUp4:DB( 5703):  beforefinger == newfinger no write in DB
W/libprocessgroup(  842): failed to open /acct/uid_10010/pid_5278/cgroup.procs: No such file or directory
,D/AppUp4:AppBoxApplication( 5703): AppBoxApplication onCreate()
D/AppUp4:PreloadHelper( 5703): removed from Exclude : com.test.thalitest : 1
,I/ActivityManager(  842): Killing 5376:com.lge.bnr/1000 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_1000/pid_5376/cgroup.procs: No such file or directory
,I/ActivityManager(  842): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5724 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 5724): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5724): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5724): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/AppConfig( 5724): Total System Memory = 906309632
,I/GalleryUtils( 5724): Application Heap = 96 MB
I/AppConfig( 5724): App Tier : NOT_DEF
D/SystemHelper( 5724): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  842): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5743 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  842): Killing 5399:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  842): failed to open /acct/uid_10081/pid_5399/cgroup.procs: No such file or directory
,W/ResourcesManager( 5743): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5743): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5743): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5743): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5743): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 5743): BUILD Country: EU
I/SystemConfig( 5743): BUILD Operator: OPEN
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ActivityManager(  842): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5763 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  842): Killing 5450:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_10014/pid_5450/cgroup.procs: No such file or directory
,I/SystemConfig( 5743): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5743): existFile = false
I/SystemConfig( 5743): canReadFile = false
I/SystemConfig( 5743): systemFeature RCS result false
D/SystemConfig( 5743): refreshRcsSupport() :false
,I/LockScreenSettings( 5763): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 5763): New app installed broadcast received ..
,I/LockScreenSettings( 5763): Number of installed packages  1
,I/ActivityManager(  842): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5780 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  842): Killing 5479:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_10053/pid_5479/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 5780): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5780): uri : package:com.test.thalitest
,I/ActivityManager(  842): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5797 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  842): Killing 5545:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_10038/pid_5545/cgroup.procs: No such file or directory
,D/InitAlarmsService( 3870): Clearing and rescheduling alarms.
,I/ActivityManager(  842): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5814 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  309): Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 415us total 24.040ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 277us total 20.910ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 26.490ms
,I/ThermalEngine(  301): Sensor:pa_therm0:32000 mC
,W/ResourcesManager( 5814): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/CalendarProvider2( 5814): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2194c4d2
D/[BNRAppListMgrReceiver]( 5797): android.intent.action.PACKAGE_ADDED : com.test.thalitest
,D/CalendarProvider2( 5814): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5814): Created com.android.providers.calendar.CalendarAlarmManager@338a8cff(com.android.providers.calendar.CalendarProvider2@2194c4d2)
,D/CalendarProvider2( 5814): Scheduling check of next Alarm
D/CalendarProvider2( 5814): SCHEDULE_ALARM_REMOVE
I/ActivityManager(  842): Killing 3870:com.android.calendar/u0a13 (adj 15): empty #11
,W/MainApplication( 5797): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/ActivityManager(  842): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5843 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  842): Killing 4035:com.google.process.gapps/u0a6 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_10013/pid_3870/cgroup.procs: No such file or directory
,W/libprocessgroup(  842): failed to open /acct/uid_10006/pid_4035/cgroup.procs: No such file or directory
I/ActivityManager(  842): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5868 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/GservicesProvider( 5868): Gservices pushing to system: true; secure/global: true
,I/GoogleHttpClient( 5868): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5868): GMS http client unavailable, use old client
,D/Finsky  ( 5843): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5843): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5843): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5843): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5843): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3215): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3215): created cursor android.database.sqlite.SQLiteCursor@500ede2 on behalf of 5843
,I/NotificationManager( 5843): com.android.vending: cancel(1003285959) by com.android.vending
,D/Ads     ( 5843): Skipping gmscore version check
,I/ActivityManager(  842): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5912 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  842): Killing 5628:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
D/Finsky  ( 5843): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 5843): [1] Libraries$2.run: Finished loading 1 libraries.
W/System.err( 5300): android.os.DeadObjectException
,W/System.err( 5300): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5300): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5300): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5300): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5300): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5300): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5300): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5300): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5300): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5300): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5300): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5300): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5300): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5300): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5300): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5300): android.os.DeadObjectException
W/System.err( 5300): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5300): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5300): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5300): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5300): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5300): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5300): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5300): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5300): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5300): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5300): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5300): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5300): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5300): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5300): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,W/libprocessgroup(  842): failed to open /acct/uid_10089/pid_5628/cgroup.procs: No such file or directory
D/Finsky  ( 5843): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/CalendarProvider2( 5814): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5814): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  842): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5930 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  842): Killing 5300:com.lge.qremote/u0a106 (adj 15): empty #11
,I/ActivityManager(  842): Killing 5647:com.lge.email/u0a21 (adj 15): empty #11
,D/Finsky  ( 5843): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,I/art     (  842): Explicit concurrent mark sweep GC freed 23708(1145KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/34MB, paused 2.915ms total 152.838ms
,W/libprocessgroup(  842): failed to open /acct/uid_10106/pid_5300/cgroup.procs: No such file or directory
W/libprocessgroup(  842): failed to open /acct/uid_10021/pid_5647/cgroup.procs: No such file or directory
I/ActivityManager(  842): Killing 5675:com.google.android.partnersetup/u0a9 (adj 15): empty #11
D/Finsky  ( 5843): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/UEI.SmartControl( 5930): Quickset Services start...
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/UEI.SmartControl( 5930): Manufacture = LGE
D/UEI.SmartControl( 5930): File observer start...
E/UEI.SmartControl( 5930): IR Port is disabled: false
D/UEI.SmartControl( 5930): Starting file observer...
D/UEI.SmartControl( 5930): Extracting JNI libs...
D/UEI.SmartControl( 5930): --- this system supports 32-bit or 64-bit only
W/libprocessgroup(  842): failed to open /acct/uid_10009/pid_5675/cgroup.procs: No such file or directory
,I/ActivityManager(  842): Killing 5703:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/UEI.SmartControl( 5930): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5930): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5930): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 5930): --- Selecting new region: 2
I/UEI.SmartControl( 5930): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5930): Platform has CIR...
D/UEI.SmartControl( 5930): NO CIR support, need to check package...
I/UEI.SmartControl( 5930): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5930): QS Service created
W/libprocessgroup(  842): failed to open /acct/uid_10011/pid_5703/cgroup.procs: No such file or directory
,E/UEI.SmartControl( 5930): QS start get config
,D/UEI.SmartControl( 5930): Loading JNI Libs...
,D/UEI.SmartControl( 5930):  configuring local db...
,D/UEI.SmartControl( 5930):  ---- Has DB8: true
,D/UEI.SmartControl( 5930): QS start statue = true Error code = 0
D/UEI.SmartControl( 5930): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5930): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5930): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5930): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5930): IrrcClient ++ 
D/irrcClient( 5930): getIrrcService ++ 
D/irrcClient( 5930): getIrrcService -- 
D/irrcClient( 5930): IrrcClient -- 
W/irrc_jni( 5930): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5930): Services init done
,I/UEI.SmartControl( 5930): Device manager: loading config....
D/UEI.SmartControl( 5930): QS Service init finished
D/UEI.SmartControl( 5930): QS Service version name: 0.1.73
D/UEI.SmartControl( 5930): Config is loaded...
D/UEI.SmartControl( 5930): QS Service version code: 1073
D/UEI.SmartControl( 5930): Service requested: Control
D/UEI.SmartControl( 5930): Service.onUnbind: IControl
D/UEI.SmartControl( 5930): Service.onDestroy
,D/UEI.SmartControl( 5930): Shutdown IRRCPlayer... 
W/irrc_jni( 5930): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5930): ~IrrcClient ++ 
D/irrcClient( 5930): ~IrrcClient -- 
W/irrc_jni( 5930): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5930): Blaster closed
D/UEI.SmartControl( 5930): Blaster closed
D/UEI.SmartControl( 5930): Shut down QS...
D/UEI.SmartControl( 5930): Stopped file observer...
I/UEI.SmartControl( 5930): QS lib stop result = true
,D/UEI.SmartControl( 5930): QS shutdown complete
D/UEI.SmartControl( 5930): QS Service created
E/UEI.SmartControl( 5930): QS start get config
I/UEI.SmartControl( 5930): Notify AllClients services are ready: 11
,D/UEI.SmartControl( 5930):  configuring local db...
I/GAv4    ( 5912): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5912):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5912):   adb logcat -s GAv4
,W/GAv4    ( 5912): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5912): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5912): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5912): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,D/UEI.SmartControl( 5930):  ---- Has DB8: true
,D/UEI.SmartControl( 5930): QS start statue = true Error code = 0
D/UEI.SmartControl( 5930): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5930): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5930): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5930): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5930): IrrcClient ++ 
D/irrcClient( 5930): getIrrcService ++ 
D/irrcClient( 5930): getIrrcService -- 
D/irrcClient( 5930): IrrcClient -- 
W/irrc_jni( 5930): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5930): Services init done
D/UEI.SmartControl( 5930): QS Service init finished
D/UEI.SmartControl( 5930): QS Service version name: 0.1.73
D/UEI.SmartControl( 5930): QS Service version code: 1073
D/UEI.SmartControl( 5930): Service requested: Control
I/UEI.SmartControl( 5930): Device manager: loading config....
,D/UEI.SmartControl( 5930): Config is loaded...
D/UEI.SmartControl( 5930):  ----- QS SDK is ready!!!
,E/VoldCmdListener(  249): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
I/UEI.SmartControl( 5930): Notify AllClients services are ready: 0
E/Vold    (  249): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  249): Returning OperationFailed - no handler for errno 0
D/UEI.SmartControl( 5930): Request IControl service: devices are loaded...
W/ContextImpl( 5912): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
I/ActivityManager(  842): Killing 5724:com.android.gallery3d/u0a23 (adj 15): empty #11
W/ResourcesManager( 5912): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5912): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,E/ActivityThread( 5930): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@1e84fa1b that was originally bound here
E/ActivityThread( 5930): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@1e84fa1b that was originally bound here
E/ActivityThread( 5930): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5930): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5930): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5930): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5930): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5930): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 5930): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 5930): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 5930): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5930): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5930): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5930): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5930): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5930): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5930): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5930): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5930): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5930): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,I/ActivityManager(  842): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5982 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  842): Killing 5743:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_10023/pid_5724/cgroup.procs: No such file or directory
,W/libprocessgroup(  842): failed to open /acct/uid_10018/pid_5743/cgroup.procs: No such file or directory
D/UEI.SmartControl( 5930): Internal service binding...
W/ResourcesManager( 5982): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 5912): CheckpointMarkThreadRoots callback created = 0xaaedc290
V/JNIHelp ( 5912): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 5912): CheckpointMarkThreadRoots callback created = 0xb050c9f0
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
W/System  ( 5912): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5912): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  842): Killing 5763:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  842): failed to open /acct/uid_10069/pid_5763/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 4883): Reading stored module config
,D/PackageBroadcastService( 4883): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 4883): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4883): Loading module APK com.google.android.play.games
W/ProcessCpuTracker(  842): Skipping unknown process pid 5955
W/ProcessCpuTracker(  842): Skipping unknown process pid 5958
I/UpdateIcingCorporaServi( 1936): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1936): UpdateCorporaTask done [took 137 ms] updated apps [took 137 ms] 
,D/UEI.SmartControl( 5930): Internal timer expired: 2
W/System.err( 5930): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1e84fa1b
,W/System.err( 5930): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 5930): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 5930): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 5930): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 5930): 	at com.uei.control.Service.a(Unknown Source)
W/System.err( 5930): 	at com.uei.control.l.run(Unknown Source)
W/System.err( 5930): 	at java.util.Timer$TimerImpl.run(Timer.java:284)
E/UEI.SmartControl( 5930): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1e84fa1b
D/ChimeraCfgMgr( 4883): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4883): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4883): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 4883): Submit a task: k
,D/ChimeraCfgMgr( 4883): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 4883): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 4883): Processing package: com.test.thalitest
D/GassUtils( 4883): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 4883): Found info for package com.test.thalitest in db.
,I/Icing   ( 4883): Storage manager: low false usage 1.70MB avail 2.37GB capacity 4.06GB
,W/BaseAppContext( 4883): Using Auth Proxy for data requests.
I/PeopleDatabaseHelper( 4883): cleanUpNonGplusAccounts done.
,E/BaseAppContext( 4883): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,W/BaseAppContext( 4883): Using Auth Proxy for data requests.
W/BaseAppContext( 4883): Using Auth Proxy for data requests.
W/BaseAppContext( 4883): Using Auth Proxy for data requests.
,W/BaseAppContext( 4883): Using Auth Proxy for data requests.
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 27847(1844KB) AllocSpace objects, 27(432KB) LOS objects, 40% free, 13MB/22MB, paused 1.366ms total 106.870ms
,D/WearableService( 1733): callingUid 10006, callindPid: 1733
,D/LocationInitializer( 4883): Restart initialization of location
E/MDM     ( 1733): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  842): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6050 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/GCoreFlp( 1733): No location to return for getLastLocation()
,W/FusedLocationProvider( 1733): location=null
I/ActivityManager(  842): Process com.google.android.talk (pid 5573) has died
,W/ResourcesManager( 6050): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  842): Message: 20
D/BluetoothManagerService(  842): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b6e62ea:true
,D/BluetoothAdapterService(512031259)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19ce39c9
D/BluetoothAdapterService(512031259)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19ce39c9
V/LGMDMManager( 6050): Create singleton instance
,I/Icing   ( 4883): updateResources: need to parse f{com.google.android.gms}
,I/AudioManager( 6050): getMode name:com.lge.qremote
,I/art     ( 4883): Background sticky concurrent mark sweep GC freed 6736(499KB) AllocSpace objects, 1(16KB) LOS objects, 4% free, 13MB/14MB, paused 5.804ms total 36.122ms
D/UEI.SmartControl( 5930): -----IControl: 11
D/UEI.SmartControl( 5930): File observer start...
E/UEI.SmartControl( 5930): IR Port is disabled: false
D/UEI.SmartControl( 5930): Starting file observer...
D/UEI.SmartControl( 5930): Caller: com.lge.qremote
,D/UEI.SmartControl( 5930): ------------ IControl registerCallback...
I/UEI.SmartControl( 5930): Registering callback...
D/UEI.SmartControl( 5930): -----IControl: 19
D/UEI.SmartControl( 5930): Caller: com.lge.qremote
I/UEI.SmartControl( 5930): Registering Services Ready callback...
I/UEI.SmartControl( 5930): Notify client services are ready...
D/UEI.SmartControl( 5930): -----IControl: 8
D/UEI.SmartControl( 5930): Caller: com.lge.qremote
I/ActivityManager(  842): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6072 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 6072): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Icing   ( 4883): Internal init done: storage state 0
,I/Icing   ( 4883): Post-init done
,D/ChimeraCfgMgr( 4883): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4883): Module APK com.google.android.play.games already loaded
,I/Babel_SMS( 6072): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6072): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6072): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6072): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6072): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6072): MmsConfig.loadFromResources
E/Babel_SMS( 6072): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6072): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6072): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6072): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6072): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6072): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 6072): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6072): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6072): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6072): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6072): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6072): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6072): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6072): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6072): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6072): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6072): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6072): found sensor: Motion Accel, handle=46
W/Settings( 6072): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6072): startup - clean
I/Babel   ( 6072): deleted: false for 0
,I/art     ( 6072): CheckpointMarkThreadRoots callback created = 0xaaf3e710
I/art     ( 6072): CheckpointMarkThreadRoots callback created = 0xaaf3e6f0
,W/AudioCapabilities( 6072): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6072): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6072): Unsupported mime audio/g726
W/AudioCapabilities( 6072): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6072): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6072): Unsupported mime video/mjpg
W/VideoCapabilities( 6072): Unsupported mime video/theora
W/AudioCapabilities( 6072): Unsupported mime audio/evrc
,W/AudioCapabilities( 6072): Unsupported mime audio/qcelp
W/VideoCapabilities( 6072): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  842): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6110 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/AudioCapabilities( 6072): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6072): Unsupported mime audio/qcelp
W/AudioCapabilities( 6072): Unsupported mime audio/evrc
W/VideoCapabilities( 6072): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6072): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6072): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6072): Unrecognized profile 2130706433 for video/avc
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/VideoCapabilities( 6072): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6072): Unrecognized profile 2130706433 for video/avc
,I/AppUp4:AppBoxCP( 6110): onCreate
W/AppUp4:DB( 6110):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6110):  setFingerPrint start
I/AppUp4:DB( 6110):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6110):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6110):  SDK version = 0
I/AppUp4:DB( 6110):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6110): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6110): onReceive
I/AppUp4:CustModeStarterReceiver( 6110): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6110): Context : android.app.ReceiverRestrictedContext@478859
D/AppUp4:CustFacade( 6110): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6110): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6110): begin check event
I/AppUp4:CustModeStarterReceiver( 6110): Event For Nothing, skip.
I/ActivityManager(  842): Killing 5780:com.lge.eula/1000 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_1000/pid_5780/cgroup.procs: No such file or directory
,I/ActivityManager(  842): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6131 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/vclib   ( 6072): onServiceConnected
W/Babel   ( 6072): Attempted to change video mute state without an active call.
I/NotificationManager( 6072): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6072): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6072): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6131): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6131): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6131): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,V/JNIHelp ( 6072): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/Finsky  ( 5843): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/AlarmManager(  842): RTC_WAKEUP set : Alarm{3ecb7a9f type 0 when 1457399576765 com.android.vending} when 1457399576765
,W/System  ( 6072): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6072): Installed default security provider GmsCore_OpenSSL
,I/AppConfig( 6131): Total System Memory = 906309632
I/GalleryUtils( 6131): Application Heap = 96 MB
I/AppConfig( 6131): App Tier : NOT_DEF
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 6072): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/SystemHelper( 6131): region [EU], country [EU], operator [OPEN], sub-operator []
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  842): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6154 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/NotificationManager(  842): android: cancelAsUser(2) by android
,D/libc-netbsd( 5843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 5843): propertyValue:false
D/libc-netbsd( 5843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ThermalEngine(  301): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{38764825 type 2 when 88824 com.android.providers.calendar} when 88824
,I/art     (  842): Explicit concurrent mark sweep GC freed 16227(751KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.406ms total 166.625ms
I/Icing   ( 4883): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,W/ResourcesManager( 6154): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6154): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6154): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6154): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6154): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/libc-netbsd( 5843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/Icing   ( 4883): Loaded CLD2 Version V2.0 - 20141016
,I/SystemConfig( 6154): BUILD Country: EU
I/SystemConfig( 6154): BUILD Operator: OPEN
I/Icing   ( 4883): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  842): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6177 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  842): Killing 5797:com.lge.bnr/1000 (adj 15): empty #11
I/art     (  309): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 286us total 22.070ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 20.628ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 20.874ms
,W/libprocessgroup(  842): failed to open /acct/uid_1000/pid_5797/cgroup.procs: No such file or directory
I/SystemConfig( 6154): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6154): existFile = false
I/SystemConfig( 6154): canReadFile = false
I/SystemConfig( 6154): systemFeature RCS result false
D/SystemConfig( 6154): refreshRcsSupport() :false
,I/LockScreenSettings( 6177): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6177): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 6177): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6177): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6177): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6177): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  842): Killing 5814:com.android.providers.calendar/u0a14 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  842): failed to open /acct/uid_10014/pid_5814/cgroup.procs: No such file or directory
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  842): android: cancelAsUser(2) by android
,I/UpdateIcingCorporaServi( 1936): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 4883): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4883): Null package name or gms related package.  Ignoreing.
E/MDM     ( 1733): [105] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/Icing   ( 4883): updateResources: need to parse f{com.google.android.gms}
,D/LocationInitializer( 4883): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 6050): getMode name:com.lge.qremote
,I/qtaguid ( 5843): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5843): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5843): untagSocket(41) failed with errno -22
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
I/AudioManager( 6050): getMode name:com.lge.qremote
,D/Finsky  ( 5843): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430700] >= Server Version [-1]
I/UpdateIcingCorporaServi( 1936): UpdateCorporaTask done [took 94 ms] updated apps [took 94 ms] 
,I/ActivityManager(  842): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6213 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  842): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6232 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  842): android: cancelAsUser(2) by android
,W/ResourcesManager( 6232): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6232): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6232): VM with version 2.1.0 has multidex support
I/MultiDex( 6232): install
,I/MultiDex( 6232): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6232): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6232): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6232): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6b850a9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6232): Installed default security provider GmsCore_OpenSSL
,W/ActivityManager(  842): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/NotificationManager( 6232): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6232): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 6232): Reading stored module config
,D/ChimeraCfgMgr( 6232): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/Gmail   ( 6213): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 5868): Explicit concurrent mark sweep GC freed 7970(400KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 1.121ms total 38.021ms
W/GAV2    ( 6213): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/CAR.SERVICE( 6232): Connecting to CarCallService...
,D/NativeLibraryUtils( 6232): Install completed successfully. count=14 extracted=0
I/art     ( 6232): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6232): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/ActivityManager(  842): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/qtaguid ( 5843): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5843): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5843): untagSocket(41) failed with errno -22
E/Gmail   ( 6213): Error finding the version of the Email provider.....
E/Gmail   ( 6213): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6213): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6213): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6213): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6213): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6213): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6213): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6213): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6213): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6213): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CAR.SERVICE( 6232): com.google.android.projection.gearhead isn't installed.
,I/ActivityManager(  842): Killing 5176:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/ActivityManager(  842): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/libprocessgroup(  842): failed to open /acct/uid_10006/pid_5176/cgroup.procs: No such file or directory
I/Gmail   ( 6213): Observing account changes for notifications
,W/ActivityManager(  842): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/CAR.TEL.Service( 6232): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6232): Creating a new PhoneAdapter instance
W/ActivityManager(  842): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6232): setListener: com.google.android.gms.car.dn@2bb1438c
,W/ActivityManager(  842): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6232): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6232): Starting CarCallService with initial phone null
E/UEI.SmartControl( 5930): file observer is disposed!
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 6232): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6232): Package validated; name: com.android.vending
,I/ActivityManager(  842): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6283 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/art     ( 5843): CheckpointMarkThreadRoots callback created = 0xb0568340
I/art     ( 5843): CheckpointMarkThreadRoots callback created = 0xb0568320
,I/Gmail   ( 6213): notifyAccountChanged
,I/NotificationManager( 5843): com.android.vending: cancel(10436) by com.android.vending
I/Gmail   ( 6213): getAccountsCursor
V/Finsky  ( 5843): [1] GearheadStateMonitor.access$100: mIsProjecting:false
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6213): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6213): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6213): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6213): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/ActivityManager(  842): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6311 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,I/Gmail   ( 6213): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Icing   ( 4883): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,E/UpdateRequestReceiver( 6311): Received malformed URL while handling Gservices.CHANGED_ACTION
,I/Icing   ( 4883): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/art     (  842): Explicit concurrent mark sweep GC freed 14793(695KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 3.994ms total 146.365ms
I/ActivityManager(  842): Process com.google.android.apps.docs (pid 5912) has died
,E/UpdateRequestReceiver( 6311): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 6311): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6311): Received malformed URL while handling Gservices.CHANGED_ACTION
I/ActivityManager(  842): Killing 6110:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_10011/pid_6110/cgroup.procs: No such file or directory
,I/CheckinService( 4883): Checkin interval check for package: unspecified last checkin: 1457399569708 min interval config: 0 actual interval: 9278
,I/SystemUpdateService( 4883): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,I/CheckinService( 4883): Checking schedule, now: 1457399579011 next: 1457926818633
I/CheckinService( 4883): active receiver: disabled
I/GservicesUpdateTask( 1936): Updating Gservices keys
D/SystemUpdateService( 4883): onCreate
D/SystemUpdateService( 4883): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/SystemUpdateService( 4883): cancelUpdate (empty URL)
I/SystemUpdateService( 4883): active receiver: disabled
,I/NotificationManager( 4883): com.google.android.gms: cancel(2130838165) by com.google.android.gms
,I/NotificationManager( 4883): com.google.android.gms: cancel(2130838166) by com.google.android.gms
,D/UEI.SmartControl( 5930): Internal timer expired: 3
,I/art     ( 5868): Explicit concurrent mark sweep GC freed 3632(157KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 775us total 28.841ms
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  842): android: cancelAsUser(2) by android
,I/art     ( 4883): Explicit concurrent mark sweep GC freed 28882(1737KB) AllocSpace objects, 9(144KB) LOS objects, 40% free, 13MB/22MB, paused 3.824ms total 84.295ms
,W/SQLiteConnectionPool( 4883): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/SystemUpdateService( 4883): onDestroy
,E/DynamiteModule( 4883): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 4883): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 4883): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 4883): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 4883): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 4883): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 4883): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 4883): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 4883): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 4883): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 4883): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 4883): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/DynamiteModule( 4883): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/DynamiteModule( 4883): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/DynamiteModule( 4883): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 4883): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 4883): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/DynamiteModule( 4883): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 4883): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 4883): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/DynamiteModule( 4883): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/DynamiteModule( 4883): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 4883): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 4883): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 4883): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 4883): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 4883): 		... 17 more
E/DynamiteModule( 4883): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
,I/DynamiteModule( 4883): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 4883): Selected local version of com.google.android.gms.flags
,I/art     ( 5868): Explicit concurrent mark sweep GC freed 2616(101KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.225ms total 26.526ms
,D/SystemEventReceiver( 4883): Received GSERVICES_CHANGED broadcast
I/OcrUtils( 4883): Updating ocr activity enabled=false
,I/CheckinService( 4883): Done disabling old GoogleServicesFramework version
,I/qtaguid ( 5843): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5843): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5843): untagSocket(41) failed with errno -22
,W/ActivityManager(  842): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/OcrModelManager( 4883): Updating downloaded model state (gservices changed)
I/[SystemUI]QPairHandler( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1877): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QSlideListController( 1372): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  842): Reconfiguring input devices.  changes=0x00000010
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1372): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1372): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,D/administrator(  842): Handling package changes for user 0
I/[LGHome]Launcher( 1877): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 17519(1033KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 13MB/22MB, paused 1.317ms total 84.800ms
,I/NotificationService(  842): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  842): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  842): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  842): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourcesManager( 5843): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
D/WeatherService( 2708): 2 : TimeTick Intent has been received, Time(hour:min:sec) 2:13:0
W/ResourcesManager( 5843): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/WeatherService( 2708): 2 : TimeTick Intent And Screen On
D/WeatherService( 2708): 2 : SDK version : 21
W/ActivityManager(  842): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2708): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2708): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2708): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2708): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2708): 2 : This is isUpdating : false
D/WeatherService( 2708): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2708): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2708): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2708): 2 : Fixed theme : optimus
,D/WeatherReflect( 2708): 2 : Map key string is -2
D/lim     ( 2708): 2 : time = 02:13
,I/WeatherReflect( 2708): Model Name : LG-D722
D/WeatherTheme( 2708): 2 : Different view - status_min_formatted : 12 != 13
D/WeatherTheme( 2708): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2708): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,D/Theme   ( 2708): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2708): currentPackage=com.lge.sizechangable.weather.theme.optimus
W/ResourcesManager( 5843): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 5868): Explicit concurrent mark sweep GC freed 2720(106KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.284ms total 26.501ms
D/Weather4x2_optimus( 2708): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2708): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2708): forecast size is 0
D/Theme   ( 2708): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/Theme   ( 2708): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2708): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2708): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2708): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2708): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2708): setTouchIntent, appWidgetId: 2
D/GCM     ( 1733): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
D/Theme_WeatherAncestor_optimus( 2708): url is : null
D/Theme   ( 2708): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2708): 2 : update view, appWidgetId: 2
D/WeatherService( 2708): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 2:13:0
,W/ResourcesManager(  842): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/BackupManagerService(  842): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  842): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@4b65df
D/Finsky  ( 5843): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  842): RTC_WAKEUP set : Alarm{12c8112e type 0 when 1457399580226 com.android.vending} when 1457399580226
,W/ResourceType(  842): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
,I/[SystemUI]Clock( 1372): called onTimeUpdated()
I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
,I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/Finsky  ( 5843): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5843): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  842): Killing 6131:com.android.gallery3d/u0a23 (adj 15): empty #11
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,W/libprocessgroup(  842): failed to open /acct/uid_10023/pid_6131/cgroup.procs: No such file or directory
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[LGHome]EVENT( 1877): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/NotificationManager(  842): android: cancelAsUser(-591465577) by android
,D/DeviceConnectionService( 1733): client connected with version: 8296000
,I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/LocationProviderProxy(  842): applying state to connected service
,I/GCoreUlr( 1733): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1733): DispatchingService.onCreate()
,I/ActivityManager(  842): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6377 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  842): Killing 6154:com.android.contacts/u0a18 (adj 15): empty #11
,W/GeofencerStateMachine( 1733): Ignoring removeGeofence because network location is disabled.
W/libprocessgroup(  842): failed to open /acct/uid_10018/pid_6154/cgroup.procs: No such file or directory
,E/ctxmgr  ( 1733): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
I/GCoreUlr( 1733): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,D/PhoneMonitor( 6377): Register our PhoneStateListener
,V/SetupWizard( 6377): Connected to Gservices successfully
,W/ctxmgr  ( 1733): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
E/ctxmgr  ( 1733): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
I/ActivityManager(  842): Killing 6177:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,D/PhoneMonitor( 6377): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6377): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6377): [parse] Load xml
V/TelephonyAutoProfiling( 6377): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6377): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6377): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  842): failed to open /acct/uid_10069/pid_6177/cgroup.procs: No such file or directory
,I/AudioManager( 6050): getMode name:com.lge.qremote
,I/GCoreUlr( 1733): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/ActivityManager(  842): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6401 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GCoreUlr( 1733): Unbound from all location providers
I/GCoreUlr( 1733): Place inference reporting - stopped
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/GCoreUlr( 1733): DispatchingService.onDestroy()
I/GCoreUlr( 1733): Stopping handler for UlrDispSvcFast
,I/GCoreUlr( 1733): Unbound from all location providers
I/GCoreUlr( 1733): Place inference reporting - stopped
,W/ResourcesManager( 6401): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6401): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6401): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6401): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@92b24a0, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@478859, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@37d65c1e, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@338a8cff, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@352deacc, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@7df5115, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@30081c2a, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@1e84fa1b, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@eb4e7b8, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@11f0e991, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@1e3d0f6, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@bef1cf7, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@dacc764, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@12a98dcd, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@14f40682, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@106e9193, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1a20f5d0, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@19ce39c9, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@ce008ce, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@1b66b3ef, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@f679efc, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@1477a985, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@e77e3da, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@514a00b, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@60daee8, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2e8e5901, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@98063a6, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@226b31e7, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@1082d194, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1006843d, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@133f1432, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3aaf0583, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@16857300, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@31dc2739, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@1dc6417e, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3ad276df, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3b4ebf2c, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@6cefdf5, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@1800f78a, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@291a1fb, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@3a7ea218, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@33de8471, lg_p
D/GeneralP,referenceUtils( 6401): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6401): [init]
I/Config  ( 6401): LGCalendar ver.4.40.17
I/Config  ( 6401): start check model
I/Config  ( 6401): start check native_ca
I/Config  ( 6401): Config Operator=OPEN, Country=EU
D/Config  ( 6401): [setDefaultValuesToPref]
D/Config  ( 6401): [parseProfiles]
D/ProfilesParser( 6401): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6401): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6401): [updateProfiletoCountryInfo]
D/GeneralPreference( 6401): [checkAndMigrateOldPreference]
D/AlertReceiver( 6401): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6401): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6401): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
W/HolidayIntentService( 6401): onHandleIntent
D/HolidayDataLoader( 6401): readJsonAsset : holiday.json
D/AlertService( 6401): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6401): [updateWidgets] 
D/MonthWidgetProvider( 6401): [onReceive]
D/CalendarWidgetProvider( 6401): [onReceive]
D/CalendarWidgetProvider( 6401): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6401): [onCreate] mContext.getPackageName() = com.android.calendar
I/AlertUtils( 6401): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,D/WeekWidgetProvider( 6401): [onReceive]
D/CalendarWidgetProvider( 6401): [onReceive]
D/CalendarWidgetProvider( 6401): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
I/AlertUtils( 6401): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6401): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 6401): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6401): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6401): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6401): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 6401): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6401): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6401): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6401): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6401): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6401): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6401): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 6401): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6401): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6401): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
E/HolidayIntentService( 6401): onHandleIntent:holiday data empty
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
,D/sensors_hal_Time(  842): tsOffsetIs: Apps: 92962025283; DSPS: 3137454; Offset : -2791040373
I/art     (  842): Explicit concurrent mark sweep GC freed 31300(1547KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 2.262ms total 151.717ms
I/AlertUtils( 6401): set default noti to content://media/internal/audio/media/38
,D/CalendarTypeController( 6401): [onCreate] mContext.getPackageName() = com.android.calendar
I/InitNotificationRingtoneService( 6401): End InitializeAlertRingtoneService.onHandleIntent
I/AudioManager( 6050): getMode name:com.lge.qremote
,I/AudioManager( 6050): getMode name:com.lge.qremote
I/ActivityManager(  842): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6436 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
W/ResourcesManager( 6436): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/CalendarProvider2( 6436): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2194c4d2
,D/CalendarProvider2( 6436): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6436): Created com.android.providers.calendar.CalendarAlarmManager@338a8cff(com.android.providers.calendar.CalendarProvider2@2194c4d2)
D/CalendarProviderBroadcastReceiver( 6436): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6436): [IntentService] WakeLock acquire, start IntentSerivce
I/AudioManager( 6050): getMode name:com.lge.qremote
,D/CalendarProvider2( 6436): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6436): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6436): [getOrCreateCalendarAlarmManager]
I/AudioManager( 6050): getMode name:com.lge.qremote
,E/MDM     ( 1733): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 4883): Restart initialization of location
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,D/CalendarProvider2( 6436): [IntentService] Release Lock
,D/CalendarProvider2( 6436): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  842): Killing 5982:com.google.android.apps.plus/u0a86 (adj 15): empty #11
I/art     ( 1733): Explicit concurrent mark sweep GC freed 21637(1314KB) AllocSpace objects, 6(96KB) LOS objects, 40% free, 13MB/23MB, paused 1.587ms total 92.478ms
,W/libprocessgroup(  842): failed to open /acct/uid_10086/pid_5982/cgroup.procs: No such file or directory
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/ActivityManager(  842): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6471 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/GCoreFlp( 1733): No location to return for getLastLocation()
,W/FusedLocationProvider( 1733): location=null
I/NotificationManager( 6072): com.google.android.talk: cancel(8) by com.google.android.talk
,I/AppUp4:AppBoxCP( 6471): onCreate
W/AppUp4:DB( 6471):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6471):  setFingerPrint start
I/AppUp4:DB( 6471):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6471):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6471):  SDK version = 0
I/AppUp4:DB( 6471):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6471): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 6471): onReceive
I/AppUp4:CustModeStarterReceiver( 6471): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6471): Context : android.app.ReceiverRestrictedContext@478859
D/AppUp4:CustFacade( 6471): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6471): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6471): begin check event
I/AppUp4:CustModeStarterReceiver( 6471): Event For Nothing, skip.
I/ActivityManager(  842): Killing 6283:com.google.android.partnersetup/u0a9 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_10009/pid_6283/cgroup.procs: No such file or directory
,I/ActivityManager(  842): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6496 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/ThermalEngine(  301): Sensor:pa_therm0:32000 mC
W/ResourcesManager( 6496): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6496): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6496): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 6496): Total System Memory = 906309632
,I/GalleryUtils( 6496): Application Heap = 96 MB
I/AppConfig( 6496): App Tier : NOT_DEF
D/SystemHelper( 6496): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  842): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6518 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  842): Killing 6311:com.google.android.configupdater/u0a3 (adj 15): empty #11
,W/libprocessgroup(  842): failed to open /acct/uid_10003/pid_6311/cgroup.procs: No such file or directory
,W/ResourcesManager( 6518): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6518): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6518): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6518): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6518): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6518): BUILD Country: EU
I/SystemConfig( 6518): BUILD Operator: OPEN
,I/ActivityManager(  842): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6537 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  842): Killing 6232:com.google.android.gms:car/u0a6 (adj 15): empty #11
I/art     (  309): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 25.144ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 268us total 23.517ms
,I/art     (  309): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 22.371ms
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  842): failed to open /acct/uid_10006/pid_6232/cgroup.procs: No such file or directory
W/ActivityManager(  842): Scheduling restart of crashed service com.google.android.gms/.car.CarService in 1000ms
I/SystemConfig( 6518): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6518): existFile = false
,I/SystemConfig( 6518): canReadFile = false
I/SystemConfig( 6518): systemFeature RCS result false
D/SystemConfig( 6518): refreshRcsSupport() :false
I/LockScreenSettings( 6537): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6537): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6537): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6537): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6537): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6537): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  842): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6559 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  842): Killing 5930:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 6050): android.os.DeadObjectException
,W/System.err( 6050): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6050): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6050): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6050): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6050): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6050): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6050): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6050): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6050): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6050): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6050): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6050): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6050): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6050): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6050): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6050): android.os.DeadObjectException
W/System.err( 6050): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6050): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6050): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6050): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6050): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6050): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6050): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6050): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6050): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6050): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6050): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6050): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6050): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6050): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6050): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
,W/libprocessgroup(  842): failed to open /acct/uid_10089/pid_5930/cgroup.procs: No such file or directory
,W/ActivityManager(  842): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 10799ms
W/ResourcesManager( 6559): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  842): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6578 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6578): Quickset Services start...
I/UEI.SmartControl( 6578): Manufacture = LGE
D/UEI.SmartControl( 6578): File observer start...
,E/UEI.SmartControl( 6578): IR Port is disabled: false
D/UEI.SmartControl( 6578): Starting file observer...
D/UEI.SmartControl( 6578): Extracting JNI libs...
D/UEI.SmartControl( 6578): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6578): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6578): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6578): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6578): --- Selecting new region: 2
,I/UEI.SmartControl( 6578): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6578): Platform has CIR...
D/UEI.SmartControl( 6578): NO CIR support, need to check package...
I/UEI.SmartControl( 6578): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6578): QS Service created
I/UpdateIcingCorporaServi( 1936): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
E/UEI.SmartControl( 6578): QS start get config
,D/PackageBroadcastService( 4883): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4883): Null package name or gms related package.  Ignoreing.
,I/AudioManager( 6050): getMode name:com.lge.qremote
,D/Finsky  ( 5843): [695] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
I/AudioManager( 6050): getMode name:com.lge.qremote
I/Icing   ( 4883): updateResources: need to parse f{com.google.android.gms}
I/AudioManager( 6050): getMode name:com.lge.qremote
I/AudioManager( 6050): getMode name:com.lge.qremote
,I/UpdateIcingCorporaServi( 1936): UpdateCorporaTask done [took 64 ms] updated apps [took 64 ms] 
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  842): android: cancelAsUser(2) by android
,D/UEI.SmartControl( 6578): Loading JNI Libs...
D/UEI.SmartControl( 6578):  configuring local db...
,D/libc-netbsd( 5843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5843): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5843): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  277): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
I/GAV2    ( 6213): Thread[GAThread,5,main]: No campaign data found.
,D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 5843): propertyValue:false
,D/UEI.SmartControl( 6578):  ---- Has DB8: true
,D/UEI.SmartControl( 6578): QS start statue = true Error code = 0
D/UEI.SmartControl( 6578): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6578): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6578): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6578): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6578): IrrcClient ++ 
D/irrcClient( 6578): getIrrcService ++ 
D/irrcClient( 6578): getIrrcService -- 
D/irrcClient( 6578): IrrcClient -- 
W/irrc_jni( 6578): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6578): Services init done
I/UEI.SmartControl( 6578): Device manager: loading config....
D/UEI.SmartControl( 6578): QS Service init finished
D/UEI.SmartControl( 6578): QS Service version name: 0.1.73
D/UEI.SmartControl( 6578): QS Service version code: 1073
D/UEI.SmartControl( 6578): Service requested: Control
D/UEI.SmartControl( 6578): Config is loaded...
D/UEI.SmartControl( 6578):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6578): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6578): Request IControl service: devices are loaded...
I/ActivityManager(  842): Killing 6436:com.android.providers.calendar/u0a14 (adj 15): empty #11
D/UEI.SmartControl( 6578): -----IControl: 11
D/UEI.SmartControl( 6578): Caller: com.lge.qremote
D/UEI.SmartControl( 6578): ------------ IControl registerCallback...
I/UEI.SmartControl( 6578): Registering callback...
D/UEI.SmartControl( 6578): -----IControl: 19
,D/UEI.SmartControl( 6578): Caller: com.lge.qremote
I/UEI.SmartControl( 6578): Registering Services Ready callback...
I/UEI.SmartControl( 6578): Notify client services are ready...
D/UEI.SmartControl( 6578): -----IControl: 8
D/UEI.SmartControl( 6578): Caller: com.lge.qremote,
W/libprocessgroup(  842): failed to open /acct/uid_10014/pid_6436/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6578): Internal service binding...
,I/AudioManager( 6050): getMode name:com.lge.qremote
I/AudioManager( 6050): getMode name:com.lge.qremote
,I/ActivityManager(  842): Killing 5868:com.google.process.gapps/u0a6 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_10006/pid_5868/cgroup.procs: No such file or directory
,I/AudioManager( 6050): getMode name:com.lge.qremote
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  842): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6630 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 6630): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6630): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6630): VM with version 2.1.0 has multidex support
I/MultiDex( 6630): install
I/MultiDex( 6630): VM has multidex support, MultiDex support library is disabled.
,I/ActivityManager(  842): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=6648 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/GservicesProvider( 6648): Gservices pushing to system: true; secure/global: true
,I/GoogleHttpClient( 6648): GMS http client unavailable, use old client
,I/GoogleHttpClient( 6648): GMS http client unavailable, use old client
,V/JNIHelp ( 6630): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6630): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6630): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@6b850a9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6630): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6630): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6630): com.google.android.gms: cancel(39789) by com.google.android.gms
E/MDM     ( 1733): [105] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/ChimeraCfgMgr( 6630): Reading stored module config
,D/LocationInitializer( 4883): Restart initialization of location
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1733): No location to return for getLastLocation()
,W/FusedLocationProvider( 1733): location=null
D/ChimeraCfgMgr( 6630): Loading module com.google.android.gms.car from APK com.google.android.gms
D/CAR.SERVICE( 6630): Connecting to CarCallService...
,I/art     ( 6630): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6630): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/Icing   ( 4883): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/NativeLibraryUtils( 6630): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6630): com.google.android.projection.gearhead isn't installed.
D/CAR.SERVICE( 6630): mConnectedToCar = false, abort
I/ActivityManager(  842): Killing 6377:com.google.android.setupwizard/u0a38 (adj 15): empty #11
D/Icing   ( 4883): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 4883): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,W/libprocessgroup(  842): failed to open /acct/uid_10038/pid_6377/cgroup.procs: No such file or directory
,D/CAR.TEL.Service( 6630): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 6630): Creating a new PhoneAdapter instance
W/ActivityManager(  842): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6630): setListener: com.google.android.gms.car.dn@2bb1438c
W/ActivityManager(  842): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6630): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6630): Starting CarCallService with initial phone null
I/ActivityManager(  842): Killing 6471:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  842): failed to open /acct/uid_10011/pid_6471/cgroup.procs: No such file or directory
,E/ActivityThread( 6630): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@330ea9f4 that was originally bound here
E/ActivityThread( 6630): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@330ea9f4 that was originally bound here
E/ActivityThread( 6630): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6630): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6630): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6630): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6630): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6630): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6630): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6630): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6630): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6630): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6630): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6630): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6630): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6630): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6630): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6630): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6630): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6630): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6630): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6630): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6630): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6630): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6630): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6630): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2a94d0bf that was originally bound here
E/ActivityThread( 6630): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@2a94d0bf that was originally bound here
E/ActivityThread( 6630): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6630): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6630): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6630): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6630): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6630): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6630): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6630): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6630): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6630): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6630): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6630): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6630): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6630): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6630): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6630): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6630): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6630): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6630): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6630): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6630): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6630): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  842): Unbind failed: could not find connection for android.os.BinderProxy@3fc1c6f1
I/NotificationManager( 6630): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/AlertService( 6401): Beginning updateAlertNotification
,I/ActivityManager(  842): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6692 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6692): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6692): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@2194c4d2
,D/CalendarProvider2( 6692): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6692): Created com.android.providers.calendar.CalendarAlarmManager@338a8cff(com.android.providers.calendar.CalendarProvider2@2194c4d2)
D/AlertService( 6401): No fired or scheduled alerts
,I/NotificationManager( 6401): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6401): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6401): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6401): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6401): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6401): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6401): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6401): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6401): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6401): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6401): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6401): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6401): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6401): com.android.calendar: cancel(13) by com.android.calendar
,I/NotificationManager( 6401): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6401): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6401): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6401): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6401): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6401): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6401): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6401): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
I/ActivityManager(  842): Killing 6496:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  842): failed to open /acct/uid_10023/pid_6496/cgroup.procs: No such file or directory
,D/AlarmScheduler( 6401): No events found starting within 1 week.
I/ActivityManager(  842): Killing 6401:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  842): failed to open /acct/uid_10013/pid_6401/cgroup.procs: No such file or directory
,I/ActivityManager(  842): Killing 6072:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  842): failed to open /acct/uid_10061/pid_6072/cgroup.procs: No such file or directory
,I/ThermalEngine(  301): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 6578): Internal timer expired: 1
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/PackageSettings(  842): Skipping PackageSetting{236829b9 com.example.hello/10317} due to missing metadata
,I/ActivityManager(  842): Killing 6518:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  842): failed to open /acct/uid_10018/pid_6518/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/rmt_storage(  274): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  274): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  274): wakelock acquired: 1, error no: 42
,I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  274): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  274): 
I/rmt_storage(  274): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  301): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/AlarmManager(  842): RTC_WAKEUP set : Alarm{2e716329 type 0 when 1457399593953 com.android.vending} when 1457399593953
,D/Finsky  ( 5843): [685] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5843): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  301): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,W/ContextImpl( 3665): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 112963539035; DSPS: 3792864; Offset : -2791054480
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
,I/MusicWidget( 2685): mDelayedStopHandler : unbind
,I/MusicBrowser( 2726): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2726): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2726): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2726): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2726): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2726): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2726): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2726): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  842):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@1477a985com.lge.music.MediaPlaybackService$6@e77e3da
,D/MusicBrowser( 2726): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2726): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2726): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2726): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2726): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@eb4e7b8
,I/MusicBrowser( 2726): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2726): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2726): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2726): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2726): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2726): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2726): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2726): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2726): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2726): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2726): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2726): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2726): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2726): reset
V/MediaPlayer[Native]( 2726): setListener
V/MediaPlayer[Native]( 2726): disconnect
V/MediaPlayer[Native]( 2726): destructor
,V/AudioFlinger(  282): releasing 19 from 2726 for -1
V/AudioFlinger(  282):  decremented refcount to 0
V/AudioFlinger(  282): purging stale effects
V/MediaPlayer[Native]( 2726): disconnect
D/MusicBrowser( 2726): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2726): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2726): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2726): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2726): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2726): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2726): [SmartShareManagerClient] unregisterListener: 85237771
W/SmartShareClient( 2726): [SmartShareManagerClient] unregisterListener invalid listener: 85237771
I/SmartShareClient( 2726): [SmartShareManagerClient] terminate service: 2726/MediaPlaybackService/936795166
E/HomeCloudIF( 2726): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2726): [SmartShareManagerClient] unbindService context:android.app.Application@60daee8
V/CloudHub( 2726): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2726): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2726): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2726): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2726): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  842): Killing 6537:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/CloudHub( 2726): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29978
,W/libprocessgroup(  842): failed to open /acct/uid_10069/pid_6537/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/CloudHub( 2726): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19938
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/charger_monitor(  493): init target 500000
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 132965847970; DSPS: 4448300; Offset : -2791063474
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{2d33e6ae type 2 when 140217 com.google.android.gms} when 140217
,I/art     (  842): Explicit concurrent mark sweep GC freed 33719(1912KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 8.975ms total 192.639ms
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1733): Vacuum at: now=1457399628878 tag=VacuumService
I/PhenotypeConfigurator( 1733): Scheduling Phenotype for one-off execution 9846 seconds from now (1457399629387)
,I/PhenotypeFlagCommitter( 1733): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1733): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  842): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  277): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  277): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  277): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  277): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  277): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  277): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  277): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  842): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  842): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  842): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/CloudHub( 2726): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
I/CloudHub( 2726): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  842): ALS enabled for SRE
D/PowerManagerServiceEx(  842): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26508 ms ago)
,D/qdlights(  842): set_light_backlight: 253
,D/qdlights(  842): set_light_backlight: 249
D/qdlights(  842): set_light_backlight: 246
,D/qdlights(  842): set_light_backlight: 243
,D/qdlights(  842): set_light_backlight: 239
,D/qdlights(  842): set_light_backlight: 236
,D/qdlights(  842): set_light_backlight: 233
,D/qdlights(  842): set_light_backlight: 229
,D/qdlights(  842): set_light_backlight: 226
,D/qdlights(  842): set_light_backlight: 223
,D/qdlights(  842): set_light_backlight: 219
,D/qdlights(  842): set_light_backlight: 216
,D/qdlights(  842): set_light_backlight: 213
,D/qdlights(  842): set_light_backlight: 209
,D/qdlights(  842): set_light_backlight: 206
,D/qdlights(  842): set_light_backlight: 203
,D/qdlights(  842): set_light_backlight: 199
,D/qdlights(  842): set_light_backlight: 196
,D/qdlights(  842): set_light_backlight: 193
,D/qdlights(  842): set_light_backlight: 189
,D/qdlights(  842): set_light_backlight: 186
,D/qdlights(  842): set_light_backlight: 183
,D/qdlights(  842): set_light_backlight: 179
,D/qdlights(  842): set_light_backlight: 176
,D/qdlights(  842): set_light_backlight: 173
,D/qdlights(  842): set_light_backlight: 169
,D/qdlights(  842): set_light_backlight: 166
,D/qdlights(  842): set_light_backlight: 162
,D/qdlights(  842): set_light_backlight: 159
,D/qdlights(  842): set_light_backlight: 156
,D/qdlights(  842): set_light_backlight: 152
,D/qdlights(  842): set_light_backlight: 149
,D/qdlights(  842): set_light_backlight: 146
,D/qdlights(  842): set_light_backlight: 142
,D/qdlights(  842): set_light_backlight: 139
,D/qdlights(  842): set_light_backlight: 136
,D/qdlights(  842): set_light_backlight: 132
,D/qdlights(  842): set_light_backlight: 129
,D/qdlights(  842): set_light_backlight: 126
,D/qdlights(  842): set_light_backlight: 122
,D/qdlights(  842): set_light_backlight: 119
,D/qdlights(  842): set_light_backlight: 116
,D/qdlights(  842): set_light_backlight: 112
,D/qdlights(  842): set_light_backlight: 109
,D/qdlights(  842): set_light_backlight: 106
,D/qdlights(  842): set_light_backlight: 102
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
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/PowerManagerServiceEx(  842): acquireWakeLockInternal: lock=479942138, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=842
,D/WeatherService( 2708): 2 : TimeTick Intent has been received, Time(hour:min:sec) 2:14:0
D/WeatherService( 2708): 2 : TimeTick Intent And Screen On
D/WeatherService( 2708): 2 : SDK version : 21
W/ActivityManager(  842): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2708): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2708): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2708): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2708): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2708): 2 : This is isUpdating : false
D/WeatherService( 2708): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2708): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2708): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2708): 2 : Fixed theme : optimus
D/WeatherReflect( 2708): 2 : Map key string is -2
,D/lim     ( 2708): 2 : time = 02:14
I/WeatherReflect( 2708): Model Name : LG-D722
D/WeatherTheme( 2708): 2 : Different view - status_min_formatted : 13 != 14
D/WeatherTheme( 2708): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2708): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2708): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2708): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/Weather4x2_optimus( 2708): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2708): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2708): forecast size is 0
D/Theme   ( 2708): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2708): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2708): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2708): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2708): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2708): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2708): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2708): url is : null
,D/Theme   ( 2708): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2708): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2708): 2 : update view, appWidgetId: 2
,D/WeatherService( 2708): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 2:14:0
D/PowerManagerServiceEx(  842): releaseWakeLockInternal: lock=479942138 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1877): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 152967359479; DSPS: 5103709; Offset : -2791047248
,I/PowerManagerService(  842): ALS enabled for SRE
D/PowerManagerServiceEx(  842): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33509 ms ago)
,I/PowerManagerService(  842): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  842): ALS enabled for SRE
D/PowerManagerServiceEx(  842): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33539 ms ago)
W/ContextImpl(  842): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  842): Sleeping (uid 1000)...
D/LPWGController(  842): [updateScreenState] screen on = false
D/LPWGController(  842): disable proximity sensor
D/LPWGController(  842): enable proximity sensor
,I/SensorManager(  842): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@15629f37] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  842): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  842): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  842): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  842): activate: handle is 48, enable
,V/sensors_hal_Ctx(  842): activate sensors is 1400000000000
D/sensors_hal_Thresh(  842): enable: handle=48
I/sensors_hal_SAM(  842): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  842): waitForResponse: timeout=1000
V/sensors_hal_SAM(  842): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  842): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  842): enable: Received response: 0
D/PowerManagerServiceEx(  842): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33607 ms ago)
I/Adreno-EGL(  842): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  842): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  842): Build Date: 03/02/15 Mon
I/Adreno-EGL(  842): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  842): Remote Branch: 
I/Adreno-EGL(  842): Local Patches: 
I/Adreno-EGL(  842): Reconstruct Branch: 
,D/PermissionCache(  250): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (159 us)
,I/Sensors (  433): sns_pwr.c(273):acquiring wakelock
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
I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
I/LPWGController(  842): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  842): set_light_backlight: 0
,I/SensorManager(  842): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  842): activate: handle is 46, disable
V/sensors_hal_Ctx(  842): activate sensors is 1000000000000
D/sensors_hal_LP2(  842): enable: handle=46
D/sensors_hal_LP2(  842): enable: Disabling sensor handle=46
,I/sensors_hal_SAM(  842): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  250): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  250): hwc_blank: Blanking display: 0
I/DisplayManagerService(  842): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  842): Display changed displayId=0
V/sensors_hal_SAM(  842): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  842): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1751): Display #0 changed.
,D/qdhwcomposer(  250): hwc_blank: Done blanking display: 0
D/SurfaceControl(  842): Excessive delay in setPowerMode(): 246ms
,I/qdhwcomposer(  250): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  842): Got set_interactive hint
,D/KeyguardViewMediator( 1372): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1331): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1331): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1331): handleNotifyScreenOFF
D/KeyguardViewMediator( 1372): notifyScreenOffLocked
,D/JX-Cordova( 4982): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4982): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4982): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8ac5573 added. We now have 3 listener(s)
D/BluetoothManagerService(  842): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/KeyguardViewMediator( 1372): setting alarm to turn off keyguard, seq = 1, timeout = 5000
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4982): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4982): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4982): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4982): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d5b9c30 added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4982): addListener: New listener added - the number of listeners is now 1
D/KeyguardViewMediator( 1372): handleNotifyScreenOff
D/BluetoothAdapterService(512031259)( 1989): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@19ce39c9
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4982): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4982): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 4982): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4982): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4982): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4982): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4982): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4982): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4982): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4982): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4982): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
,W/System.err( 4982): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4982): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4982): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4982): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ScreenTurnOffBySensor( 1372): unregisterProximitySensor
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/WifiServerServiceExt(  842): sendKtScanInterval  mRtspPlay : false
V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=on, calling pid 842
D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=on
,V/voice   (  282): voice_set_parameters: enter: screen_state=on
,V/compress_voip(  282): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: exit
V/voice   (  282): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  282): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=on
D/StatusBarWindowView( 1372): onScreenTurnedOff why = 3
V/msm8974_platform(  282): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  282): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  282): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  282): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  282): adev_set_parameters: exit with code(0)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1372): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/GpsLocationProvider(  842): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/WifiServerServiceExt(  842): set CMD_KT_SCAN_INTERVAL
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1840): |CORE| sendScreenState: state:true
I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
,D/Cliptray Service( 1803): lockStatus = 0
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): updateLightsLocked : turn off led
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1803): RESTART MSG
D/LNfcService( 1786): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1786): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1786): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1786): isRequireNfcCRouting() return true
D/LNfcService( 1786): isHCERoutingtoHost() return : true
D/NfcService( 1786): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): newParams.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): screenState= 3
,D/NfcService( 1786): Discovery configuration equal, not updating.
D/SplitWindow(  842): check instance of lgWin Window{30861dc2 u0 SearchPanel}
,D/InputDispatcher(  842): Window went away: Window{227b8c07 u0 SearchPanel}
,I/[SystemUI]Clock( 1372): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1372): time changed, timezoneChanged : false
,D/Ulp_jni (  842): JNI:system_update. Event-0
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2708): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 2:14:3
,D/WeatherService( 2708): 2 : ACTION screen on
,D/WeatherService( 2708): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2708): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2708): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 2:14:3
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  842): ACTION_SCREEN_ON
,D/AppCleanupService( 4153): android.intent.action.SCREEN_ON
,V/AudioFlinger(  282): setParameters(): io 0, keyvalue screen_state=off, calling pid 842
D/audio_hw_primary(  282): adev_set_parameters: enter: screen_state=off
V/voice   (  282): voice_set_parameters: enter: screen_state=off
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  282): voice_extn_compress_voip_set_parameters: exit
V/voice   (  282): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  282): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  282): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  282): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  282): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  282): adev_set_parameters: exit with code(0)
D/WifiController(  842): CMD_SCREEN_OFF 
,D/WifiController(  842): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  842): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:false
,I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1803): stopPatternFlashing()
,D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1803): clear
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1803): updateLightsLocked : turn on led
E/LEDService( 1803): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1803): Can't handle this request of patternId:0
D/LEDHandler( 1803): RESTART MSG
D/LNfcService( 1786): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1786): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1877): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2708): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 2:14:3
D/WeatherService( 2708): 2 : ACTION screen off
D/WeatherService( 2708): 2 : TimeTick Receiver Unregister
D/WeatherService( 2708): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 2:14:3
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  842): ACTION_SCREEN_OFF
D/AppCleanupService( 4153): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4153): AppUsageStatsSaveTask
E/NxpNfcJni( 1786): getReconnectState = 0x0
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
D/LNfcService( 1786): isRequireNfcCRouting() return true
D/LNfcService( 1786): isHCERoutingtoHost() return : true
,D/NfcService( 1786): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): newParams.techmask= mTechMask: 0
D/NfcService( 1786): mEnableLPD: true
D/NfcService( 1786): mEnableReader: false
D/NfcService( 1786): mEnableHostRouting: true
D/NfcService( 1786): screenState= 1
E/NxpNfcJni( 1786): getReconnectState = 0x0
,I/Sensors (  433): sns_pwr.c(301):releasing wakelock
,I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1372): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{c37f7d3 type 2 when 159495 com.android.systemui} when 159495
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1751): getCallState : 0
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1372): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1372): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  301): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 172969749131; DSPS: 5759148; Offset : -2791068563
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1733): disconnect managed GoogleApiClient
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{188ff10 type 2 when 184981 com.google.android.gms} when 184981
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  493): init target 500000
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{3b6baa09 type 2 when 191671 android} when 191671
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 195474491612; DSPS: 6496581; Offset : -2790995168
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,D/charger_monitor(  493): init target 500000
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
,I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 210477038185; DSPS: 6988184; Offset : -2790981397
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 224232615411; DSPS: 7438930; Offset : -2791080545
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 239234975183; DSPS: 7930527; Offset : -2791070471
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  493): init target 500000
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 259237454442; DSPS: 8585969; Offset : -2791093861
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 279239775543; DSPS: 9241403; Offset : -2791030827
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 299241633096; DSPS: 9896824; Offset : -2791034611
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  493): init target 500000
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 319243914673; DSPS: 10552259; Offset : -2791044197
,I/ThermalEngine(  301): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 339246241359; DSPS: 11207695; Offset : -2791036795
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/LocationManagerService(  842): remove 3cf29ee5
D/LocationManagerService(  842): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  842): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  842): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  842): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  842): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 359248597415; DSPS: 11863133; Offset : -2791059235
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 379250857139; DSPS: 12518564; Offset : -2790968107
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  842): acquireWakeLockInternal: lock=479942138, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=842
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{269c540e type 2 when 391515 android} when 391515
I/ActivityManager(  842): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6905 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/DigitalAppWidgetProvider( 6905): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 6905): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@478859
I/ActivityManager(  842): Killing 6559:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  842): failed to open /acct/uid_10086/pid_6559/cgroup.procs: No such file or directory
,D/PowerManagerServiceEx(  842): releaseWakeLockInternal: lock=479942138 [*alarm*], flags=0x0
I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 401754728391; DSPS: 13255974; Offset : -2791062265
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 421757445939; DSPS: 13911413; Offset : -2790755841
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 444261938922; DSPS: 14648849; Offset : -2791023288
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 459264209587; DSPS: 15140448; Offset : -2791163718
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 476148375901; DSPS: 15693705; Offset : -2791060918
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 496150976820; DSPS: 16349142; Offset : -2790809879
,D/PowerManagerServiceEx(  842): acquireWakeLockInternal: lock=479942138, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=842
,V/AlarmManager(  842): RTC_WAKEUP set : Alarm{23003e2f type 0 when 1457399985191 com.google.android.gms} when 1457399985191
D/PowerManagerServiceEx(  842): releaseWakeLockInternal: lock=479942138 [*alarm*], flags=0x0
,I/EventLogService( 4883): Aggregate from 1457399560186 (log), 1457398185069 (data)
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 518655539616; DSPS: 17086582; Offset : -2791131901
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 533657472495; DSPS: 17578165; Offset : -2791119649
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
,I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 553659982510; DSPS: 18233604; Offset : -2791020315
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 568662132617; DSPS: 18725199; Offset : -2791161214
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
,I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 583664404789; DSPS: 19216789; Offset : -2791023189
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 598666891563; DSPS: 19708387; Offset : -2790917021
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 613669182015; DSPS: 20199986; Offset : -2791037483
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 633672010935; DSPS: 20855439; Offset : -2791046333
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 653674377684; DSPS: 21510874; Offset : -2790968690
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 673676581808; DSPS: 22166313; Offset : -2791175245
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 696181572807; DSPS: 22903752; Offset : -2791036646
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 711183610861; DSPS: 23395339; Offset : -2791043374
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 728686362535; DSPS: 23968871; Offset : -2791098847
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 743688353281; DSPS: 24460457; Offset : -2791122756
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 759171657888; DSPS: 24967809; Offset : -2790974295
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 774173912537; DSPS: 25459406; Offset : -2791069501
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 789176264059; DSPS: 25951002; Offset : -2791037340
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 802932397434; DSPS: 26401760; Offset : -2790946341
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 817790747061; DSPS: 26888642; Offset : -2791056292
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 832793229126; DSPS: 27380237; Offset : -2790861144
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 847795224425; DSPS: 27871833; Offset : -2791185050
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 864679780889; DSPS: 28425110; Offset : -2791302397
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 882504188755; DSPS: 29009171; Offset : -2791024020
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 902506522177; DSPS: 29664609; Offset : -2791070971
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 267
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 267
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 267, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 922508678475; DSPS: 30320040; Offset : -2791081395
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 942511041575; DSPS: 30975475; Offset : -2791005082
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  842): acquireWakeLockInternal: lock=479942138, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=842
,V/AlarmManager(  842): ELAPSED_WAKEUP set : Alarm{36c5a028 type 2 when 948907 com.android.bluetooth} when 948907
D/PowerManagerServiceEx(  842): releaseWakeLockInternal: lock=479942138 [*alarm*], flags=0x0
,W/bt-smp  ( 1989): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 1989): Plain text(LSB ~ MSB) = cc d1 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 1989): Encrypted text(LSB ~ MSB) = 2d 14 fc 10 2e 32 41 29 05 2f a7 67 b7 aa 3a 9d 
W/bt-btm  ( 1989): Stopping oneshot timer
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 962512535826; DSPS: 31630886; Offset : -2791067409
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 266, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 982514764837; DSPS: 32286319; Offset : -2791068030
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1002517073782; DSPS: 32941754; Offset : -2791047903
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1022519222324; DSPS: 33597183; Offset : -2791005048
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 265
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 265, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1037521835298; DSPS: 34088789; Offset : -2791016587
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1057524452740; DSPS: 34744232; Offset : -2790930099
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1072527053145; DSPS: 35235840; Offset : -2791015371
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1087529015863; DSPS: 35727432; Offset : -2791251741
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1108785358487; DSPS: 36423954; Offset : -2791071792
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
,I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1128787686097; DSPS: 37079392; Offset : -2791124579
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1143790625343; DSPS: 37571005; Offset : -2791023286
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1158792818463; DSPS: 38062597; Offset : -2791027535
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
,I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1173794931959; DSPS: 38554195; Offset : -2791296442
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1186933205631; DSPS: 38984704; Offset : -2791112962
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1206784974786; DSPS: 39635203; Offset : -2790997782
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1221787286115; DSPS: 40126801; Offset : -2791068673
,I/UsageStatsService(  842): User[0] Flushing usage stats to disk
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
I/[SystemUI]DateView( 1372): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1372): handleTimeUpdate
I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1236789595680; DSPS: 40618396; Offset : -2791045791
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1251791783029; DSPS: 41109988; Offset : -2791055837
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1372): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1372): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1372): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  493): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 1989): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1372): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 264
I/[SystemUI]LGPowerUI( 1372): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1372): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 264
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 264, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1372): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  842): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  842): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  842): battery changed pluggedType: 2
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  842): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  842): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  842): tsOffsetIs: Apps: 1271793810614; DSPS: 41765414; Offset : -2791042725
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  301): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1372): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1372): called onTimeUpdated()
I/[SystemUI]Clock( 1372): called onTimeUpdated()
,TIME-OUT KILL (timeout was 1200000ms)
```
