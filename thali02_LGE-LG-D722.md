#### Test 614329799926788_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/GHttpClientFactory( 4781): Using our fixed implementation of GMSCore's GoogleHttpClient
I/GoogleURLConnFactory( 4781): Using platform SSLCertificateSocketFactory
--------- beginning of system
I/ActivityManager(  972): Killing 4571:com.lge.qmemoplus/1000 (adj 15): empty #11
,W/ResourcesManager( 4838): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4838): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4838): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  972): failed to open /acct/uid_1000/pid_4571/cgroup.procs: No such file or directory
I/NotificationManager( 4781): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 4838): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 4838): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/AndroidRuntime( 4869): 
D/AndroidRuntime( 4869): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4869): CheckJNI is OFF
D/eas_req ( 4838): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
D/LGDMClient( 4604): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4604): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 4604): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
I/LGDMClient( 4604): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4604): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
I/HubEmail( 4838): JNI_OnLoad()
I/HubEmail( 4838): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4838): registerNatives()
I/HubEmail( 4838): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4838): registerNativeMethods()
I/HubEmail( 4838): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/art     ( 4838): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
I/ActivityManager(  972): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=4901 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/LGDMClient( 4604): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
W/ContextImpl( 4604): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
W/Settings( 4838): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/LGDMClient( 4604): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 4604): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 4604): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 4604): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 4604): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
I/ActivityManager(  972): Killing 4749:com.lge.bnr/1000 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_1000/pid_4749/cgroup.procs: No such file or directory
D/AndroidRuntime( 4869): Calling main entry com.android.commands.am.Am
I/ActivityManager(  972): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/AppUp4:AppBoxCP( 4901): onCreate
W/AppUp4:DB( 4901):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 4901):  setFingerPrint start
I/AppUp4:DB( 4901):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
D/ActivityManager(  972): setTaskToReturnTo : TaskRecord{378995b4 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  972): setTaskToReturnTo : TaskRecord{378995b4 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
I/AppUp4:DB( 4901):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4901):  SDK version = 0
I/AppUp4:DB( 4901):  beforefinger == newfinger no write in DB
D/WindowStateEx(  972): AppWindowTokenEx init.. 
D/ContextHelper(  972): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
D/InputDispatcher(  972): Focus left window: Window{24d5e221 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 4869): Shutting down VM
D/AppUp4:AppBoxApplication( 4901): AppBoxApplication onCreate()
I/[LGHome]EVENT( 1880): [Launcher.java:986:onPause()]onPause
I/PhoneWindow(  972): [generateLayout] setColorNavigationBar => color=0x ff000001
I/NetworkStateForAutoUpdateMonitor( 4901): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4901): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4901): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 4901): [onReceive] request level :IDLE....
D/PhoneWindowEx(  972): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  972): [setNavigationBarColor2] color=0x fff5f5f5
D/SplitWindow(  972): check instance of lgWin Window{17a5e74c u0 Starting com.test.thalitest}
I/ActivityManager(  972): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4921 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1880): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/AppUp4:CustModeStarterReceiver( 4901): onReceive
I/AppUp4:CustModeStarterReceiver( 4901): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 4901): Context : android.app.ReceiverRestrictedContext@7bdcffc
D/AppUp4:CustFacade( 4901): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4901): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 4901): begin check event
I/AppUp4:CustModeStarterReceiver( 4901): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4901): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
I/[LGHome]EVENT( 1880): [Launcher.java:5214:onStop()]onStop
D/AppUp4:CustModeStarterReceiver( 4901): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 4901): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 4901): handleAsyncCustNotification do not startCustService
I/WindowStateAnimator(  972): Starting window displayed
I/HotwordDetector( 1966): Closing mic
D/WindowManager(  972): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/ActivityManager(  972): Killing 4676:com.android.settings/1000 (adj 15): empty #11
I/SystemUI[Framework](  972): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
I/[SystemUI]NavigationThemeResource( 1375): notify navigation bar color(0xfff5f5f5)
I/[SystemUI]NavigationThemeResource( 1375): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1375):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1375): , Keyguard show=false, IME shown=false, Panel expanded=false
,W/PhoneWindowManagerEx(  972): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  972): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  972): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  972): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@347d9fa6,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  972): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/MicrophoneInputStream( 1966): mic_close com.google.android.apps.gsa.speech.audio.u@3176ea5a
V/AudioRecord( 1966): stop()
D/AudioRecord( 1966): AudioRecord->stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioFlinger(  279): Record stopped OK
W/libprocessgroup(  972): failed to open /acct/uid_1000/pid_4676/cgroup.procs: No such file or directory
V/AudioPolicyManager(  279): stopInput() input 17
V/AudioPolicyService(  279): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  279): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  279): ThreadBase::setParameters() routing=0
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb39e9000
D/audio_hw_primary(  279): in_standby: enter: stream (0xb546e9c0) usecase(7: audio-record)
I/LgeMiscReceiver( 3178): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3178): action = android.net.conn.CONNECTIVITY_CHANGE
D/ContextHelper( 4921): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
I/LgeMiscReceiver( 3178): networkInfo.isConnected() = true
D/PhoneState( 3178): setPdpRejectCasuse : false
V/audio_hw_primary(  279): stop_input_stream: enter: usecase(7: audio-record)
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
I/ActivityManager(  972): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=4946 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
V/AudioPolicyService(  279): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
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
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb39e9000
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioRecord( 1966): stop()
V/AudioRecord( 1966): stop()
V/AudioRecord( 1966): stop()
V/AudioFlinger(  279): releasing 16 from 1966 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioPolicyManager(  279): releaseInput() 17
V/AudioPolicyManager(  279): closeInput(17)
V/AudioFlinger(  279): closeInput() 17
V/AudioSystem(  279): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1375): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1966): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): ThreadBase::exit
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioSystem(  972): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2692): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): RecordThread 0xb39e9000 exiting
V/AudioSystem( 1753): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3178): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2050): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  279): adev_close_input_stream: enter:stream_handle(0xb546e9c0)
D/audio_hw_primary(  279): in_standby: enter: stream (0xb546e9c0) usecase(7: audio-record)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioPolicyService(  279): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  279): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyManager(  279): releaseInput() exit
V/AudioFlinger(  279): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  279): removeClient_l() pid 1966, calling pid 279
I/HotwordRecognitionRnr( 1966): Stopping hotword detection.
I/HotwordRecognitionRnr( 1966): Hotword detection finished
I/WebViewFactory( 4921): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 4921): Time to load native libraries: 2 ms (timestamps 441-443)
I/LibraryLoader( 4921): Expected native library version number "",actual native library version number ""
D/PhoneMonitor( 4946): Register our PhoneStateListener
V/WebViewChromiumFactoryProvider( 4921): Binding Chromium to main looper Looper (main, tid 1) {7bdcffc}
I/LibraryLoader( 4921): Expected native library version number "",actual native library version number ""
I/chromium( 4921): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
D/MobileConnectivityChangeReceiver( 4946): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4946): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  972): Killing 4650:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 4629): android.os.DeadObjectException
I/BrowserStartupController( 4921): Initializing chromium process, singleProcess=true
W/art     ( 4921): Attempt to remove local handle scope entry from IRT, ignoring
W/System.err( 4629): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4629): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4629): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 4629): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 4629): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4629): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4629): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4629): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SysUtils( 4921): ApplicationContext is null in ApplicationStatus
W/System.err( 4629): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4629): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4629): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4629): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4629): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4629): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4629): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 4629): android.os.DeadObjectException
W/System.err( 4629): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4629): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4629): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 4629): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 4629): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4629): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4629): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4629): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4629): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4629): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4629): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4629): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4629): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4629): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4629): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
D/PhoneMonitor( 4946): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 4946): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 4946): [parse] Load xml
V/TelephonyAutoProfiling( 4946): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 4946): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 4946): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  972): failed to open /acct/uid_10089/pid_4650/cgroup.procs: No such file or directory
W/ActivityManager(  972): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
V/DownloadManager( 3228): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3228): DownloadService onCreate
I/NotificationManager( 3228): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3228): in removeSpuriousFiles
V/DownloadManager( 3228): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3228): created cursor android.database.sqlite.SQLiteCursor@37efab65 on behalf of 3228
I/DownloadManager( 3228): in trimDatabase
V/DownloadManager( 3228): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3228): created cursor android.database.sqlite.SQLiteCursor@322e24eb on behalf of 3228
W/chromium( 4921): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
I/ActivityManager(  972): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4979 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/libEGL  ( 4921): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4921): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 4921): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4921): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4921): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4921): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4921): Remote Branch: 
I/Adreno-EGL( 4921): Local Patches: 
I/Adreno-EGL( 4921): Reconstruct Branch: 
I/ActivityManager(  972): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4996 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3228): DownloadService onStartCommand
,I/CheckinService( 4309): Checkin interval check for package: unspecified last checkin: 1457038156642 min interval config: 0 actual interval: 39018919
V/DownloadManager( 3228): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3228): created cursor android.database.sqlite.SQLiteCursor@1db498e1 on behalf of 3228
I/CheckinService( 4309): Checking schedule, now: 1457077175601 next: 1457038186611
I/CheckinService( 4309): active receiver: enabled
,D/UEI.SmartControl( 4979): Quickset Services start...
I/CheckinService( 4309): Preparing to send checkin request
I/EventLogService( 4309): Accumulating logs since 1457075836022
I/UEI.SmartControl( 4979): Manufacture = LGE
D/UEI.SmartControl( 4979): File observer start...
E/UEI.SmartControl( 4979): IR Port is disabled: false
D/UEI.SmartControl( 4979): Starting file observer...
D/UEI.SmartControl( 4979): Extracting JNI libs...
D/UEI.SmartControl( 4979): --- this system supports 32-bit or 64-bit only
,V/AudioPolicyService(  279): registerClient() client 0xb3811e00, uid 10316
D/BluetoothManagerService(  972): Message: 20
D/BluetoothManagerService(  972): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3ee3d55f:true
D/BluetoothAdapterService(318850315)( 2050): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16167439
V/DownloadManager( 3228): DownloadService onDestroy
,D/DrmBroadcastReceiver( 4996): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 4996): 1  network is available. Sync DRM Time with NTP
D/WeatherAncestor( 2675): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:39:35
V/DrmService( 4996): Service onCreate
D/DrmService( 4996): Received new request = 2
I/ActivityManager(  972): Waited long enough for: ServiceRecord{34cc9059 u0 com.lge.springcleaning/.service.AppCleanupService}
D/UpdateThreadPoolManager( 2675): 2 : This is isUpdating : false
,D/WeatherAncestor( 2675): connectivity changed - connection : true
,I/DrmSntpClient( 4996): Start Sync process
D/DrmSntpClient( 4996): Server : 0
D/libc-netbsd( 4996): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4996): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4996): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4996): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  271): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  271): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/Weather_cast( 2675): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2675): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 8:39:35
D/WeatherService( 2675): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
,D/UEI.SmartControl( 4979): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 4979): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4979): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/ActivityManager(  972): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5036 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  972): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2675): 2 : Utils getTopActivity com.lge.launcher2 / true
I/UEI.SmartControl( 4979): --- Selecting new region: 2
I/UEI.SmartControl( 4979): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 4979): Platform has CIR...
D/WeatherService( 2675): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2675): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/UEI.SmartControl( 4979): NO CIR support, need to check package...
I/UEI.SmartControl( 4979): Model: LG-D722 uses JNI
D/UEI.SmartControl( 4979): QS Service created
,D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 4996): propertyValue:false
W/art     ( 4921): Attempt to remove local handle scope entry from IRT, ignoring
,I/CheckinRequestBuilder( 4309): Checkin reason type: 8 attempt count: 1
E/UEI.SmartControl( 4979): QS start get config
,E/ActivityThread( 4309): Failed to find provider info for com.google.android.wearable.settings
W/AwContents( 4921): onDetachedFromWindow called when already detached. Ignoring
I/PhoneWindow( 4921): [generateLayout] setColorNavigationBar => color=0x ff000001
,D/PhoneWindowEx( 4921): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 4921): [setNavigationBarColor2] color=0x fff5f5f5
W/ResourcesManager( 5036): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/SystemWebViewEngine( 4921): CordovaWebView is running on device made by: LGE
,W/art     ( 4921): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4921): Attempt to remove local handle scope entry from IRT, ignoring
,D/UEI.SmartControl( 4979): Loading JNI Libs...
D/UEI.SmartControl( 4979):  configuring local db...
I/LGDrmClient( 4996): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  284): eDRM_SetDRMTime +++
I/LGDRM   (  284): [DRM] SET TIME : YR=2016, MON=3, DAY=4
I/LGDRM   (  284): [DRM] SET TIME : HR=7, MIN=39, SEC=34
,V/ILGDrmService(  284): eDRM_SetDRMTime ---
,I/DrmSntpClient( 4996): Synched
D/DrmService( 4996): Completed !! request = 2
D/DrmService( 4996): Request count = 0
V/DrmService( 4996): Service onDestroy
I/Activity( 4921): Activity.onPostResume() called 
,D/OpenGLRenderer( 4921): Render dirty regions requested: true
I/OpenGLRenderer( 4921): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4921): Enabling debug mode 0
,D/Atlas   ( 4921): Validating map...
,D/SplitWindow(  972): check instance of lgWin Window{188ab0e5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 4921): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  972): Focus entered window: Window{188ab0e5 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/InputMethodManagerService(  972): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  972): Displayed com.test.thalitest/.MainActivity: +1s517ms
I/Timeline(  972): Timeline: Activity_windows_visible id: ActivityRecord{e69c5dd u0 com.test.thalitest/.MainActivity t222} time:71387
I/Timeline( 4921): Timeline: Activity_idle id: android.os.BinderProxy@35f7eb56 time:71399
,D/UEI.SmartControl( 4979):  ---- Has DB8: true
,D/UEI.SmartControl( 4979): QS start statue = true Error code = 0
D/UEI.SmartControl( 4979): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4979): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4979): IRRCDataComm has AudioManager!!!!.
,W/BindingManager( 4921): Cannot call determinedVisibility() - never saw a connection for the pid: 4921
,W/irrc_jni( 4979): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4979): IrrcClient ++ 
D/irrcClient( 4979): getIrrcService ++ 
,D/irrcClient( 4979): getIrrcService -- 
D/irrcClient( 4979): IrrcClient -- 
W/irrc_jni( 4979): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 4979): Services init done
D/UEI.SmartControl( 4979): QS Service init finished
,D/UEI.SmartControl( 4979): QS Service version name: 0.1.73
D/UEI.SmartControl( 4979): QS Service version code: 1073
D/UEI.SmartControl( 4979): Service requested: Control
I/UEI.SmartControl( 4979): Device manager: loading config....
,D/UEI.SmartControl( 4979): Config is loaded...
D/UEI.SmartControl( 4979): Request IControl service: devices are loaded...
,D/UEI.SmartControl( 4979): Internal service binding...
D/UEI.SmartControl( 4979): -----IControl: 11
D/UEI.SmartControl( 4979): Caller: com.lge.qremote
D/UEI.SmartControl( 4979): ------------ IControl registerCallback...
D/UEI.SmartControl( 4979):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 4979): Registering callback...
D/UEI.SmartControl( 4979): -----IControl: 19
I/UEI.SmartControl( 4979): Notify AllClients services are ready: 0
D/UEI.SmartControl( 4979): Caller: com.lge.qremote
,I/UEI.SmartControl( 4979): Registering Services Ready callback...
I/UEI.SmartControl( 4979): Notify client services are ready...
D/UEI.SmartControl( 4979): -----IControl: 8
D/UEI.SmartControl( 4979): Caller: com.lge.qremote
I/Babel_SMS( 5036): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5036): MmsConfig.loadMmsSettings
I/Babel_SMS( 5036): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5036): MmsConfig.loadFromDatabase
,D/JsMessageQueue( 4921): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  972): Process com.google.android.music:main (pid 4781) has died
E/Babel_SMS( 5036): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5036): MmsConfig.loadFromResources
E/Babel_SMS( 5036): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5036): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
I/art     ( 5036): CheckpointMarkThreadRoots callback created = 0xb042d890
D/SensorManager( 5036): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5036): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5036): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5036): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5036): found sensor: LGE Gravity Sensor, handle=29
,D/SensorManager( 5036): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5036): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5036): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5036): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5036): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5036): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5036): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5036): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5036): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5036): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5036): found sensor: Motion Accel, handle=46
I/art     ( 5036): CheckpointMarkThreadRoots callback created = 0xb042d880
,D/libc-netbsd(  271): res_queryN name = xxxxx succeed
,I/System.out( 1735): propertyValue:false
W/Settings( 5036): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5036): startup - clean
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Babel   ( 5036): deleted: false for 0
D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  972): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5087 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 5036): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5036): Unsupported mime audio/adpcm
,W/AudioCapabilities( 5036): Unsupported mime audio/g726
W/AudioCapabilities( 5036): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5036): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5036): Unsupported mime video/mjpg
,W/VideoCapabilities( 5036): Unsupported mime video/theora
W/AudioCapabilities( 5036): Unsupported mime audio/evrc
,W/AudioCapabilities( 5036): Unsupported mime audio/qcelp
W/VideoCapabilities( 5036): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5036): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5036): Unsupported mime audio/qcelp
W/AudioCapabilities( 5036): Unsupported mime audio/evrc
,W/VideoCapabilities( 5036): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5036): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5036): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5036): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5036): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5036): Unrecognized profile 2130706433 for video/avc
D/jxcore_app_log( 4921): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426137472
I/vclib   ( 5036): onServiceConnected
,W/Babel   ( 5036): Attempted to change video mute state without an active call.
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4921): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4921):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4921):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4921):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4921):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4921): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a78248 added. We now have 1 listener(s)
I/NotificationManager( 5036): com.google.android.talk: cancel(10436) by com.google.android.talk
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4921): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4921):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4921):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4921):     - Bluetooth MAC address: F8:95:C7:87:85:54
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4921):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4921):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4921):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4921):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4921):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4921):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4921): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@274824c7 added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4921): addListener: New listener added - the number of listeners is now 1
D/libc-netbsd( 5036): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5036): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5036): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5036): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  271): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 5036): propertyValue:false
D/BluetoothAdapterService(318850315)( 2050): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16167439
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4921): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4921): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4921): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 4921): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4921): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4921): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4921): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4921): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4921): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4921): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4921): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4921): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4921): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4921): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4921): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 4921): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4921): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4921): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2dd67af4 added. We now have 2 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4921): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4921): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a80e21d added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4921): addListener: New listener added - the number of listeners is now 1
D/BluetoothAdapterService(318850315)( 2050): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16167439
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4921): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4921): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4921): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 4921): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4921): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4921): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4921): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4921): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4921): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4921): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4921): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4921): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4921): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4921): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4921): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/NotificationManager(  972): android: cancelAsUser(2) by android
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
,I/Babel   ( 5036): connection state changed from UNKNOWN to CONNECTED
I/ActivityManager(  972): Killing 4703:com.lge.sync/1000 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_1000/pid_4703/cgroup.procs: No such file or directory
,I/art     ( 3998): Explicit concurrent mark sweep GC freed 2730(109KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 676us total 30.380ms
,I/ActivityManager(  972): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5117 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5087): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5087): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 5087): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5087):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5087):   adb logcat -s GAv4
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5087): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5087): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
W/ResourcesManager( 5117): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5117): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/GAv4    ( 5087): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5087): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5087): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/MultiDex( 5117): VM with version 2.1.0 has multidex support
I/MultiDex( 5117): install
I/MultiDex( 5117): VM has multidex support, MultiDex support library is disabled.
,I/art     (  972): Explicit concurrent mark sweep GC freed 25406(1364KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 22MB/34MB, paused 4.008ms total 170.334ms
,I/ActivityManager(  972): Process com.lge.email (pid 4838) has died
V/JNIHelp ( 5117): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5117): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 5117): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1bce8319: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5117): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5117): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5117): com.google.android.gms: cancel(39789) by com.google.android.gms
I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QPairHandler( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  972): Reconfiguring input devices.  changes=0x00000010
I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
I/art     ( 5117): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5117): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/administrator(  972): Handling package changes for user 0
,I/art     ( 1789): CheckpointMarkThreadRoots callback created = 0xaaf21b80
D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 73174860499; DSPS: 2496429; Offset : -3014900630
,I/art     ( 1789): CheckpointMarkThreadRoots callback created = 0xaaf48560
,I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/WebViewFactory( 5087): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/NotificationService(  972): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  972): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  972): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  972): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  972): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  972): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@237446a9
,D/WVCdm   (  279): Instantiating CDM.
I/WVCdm   (  279): CdmEngine::OpenSession
I/WVCdm   (  279): Level3 Library Dec 11 2014 16:13:16
,I/LibraryLoader( 5087): Time to load native libraries: 9 ms (timestamps 3392-3401)
I/LibraryLoader( 5087): Expected native library version number "",actual native library version number ""
,W/ResourcesManager(  972): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/WebViewChromiumFactoryProvider( 5087): Binding Chromium to main looper Looper (main, tid 1) {1696489}
I/LibraryLoader( 5087): Expected native library version number "",actual native library version number ""
I/chromium( 5087): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/WVCdm   (  279): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
I/BrowserStartupController( 5087): Initializing chromium process, singleProcess=true
W/WVCdm   (  279): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  279): L1 library not specified. Falling Back to L3
W/art     ( 5087): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5087): ApplicationContext is null in ApplicationStatus
W/chromium( 5087): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,W/ResourceType(  972): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/GoogleURLConnFactory( 5117): Using platform SSLCertificateSocketFactory
E/libEGL  ( 5087): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5087): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
D/NativeLibraryUtils( 5117): Install completed successfully. count=14 extracted=0
I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/Adreno-EGL( 5087): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5087): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5087): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5087): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5087): Remote Branch: 
I/Adreno-EGL( 5087): Local Patches: 
I/Adreno-EGL( 5087): Reconstruct Branch: 
I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/libc-netbsd( 5117): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5117): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5117): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5117): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/WVCdm   (  279): PrepareKeyRequest: nonce=2479749110
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
I/GCoreNlp( 1735): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
,D/LCardEmulationManager( 1789): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1789): getDefaultRoute
,V/AudioPolicyService(  279): registerClient() client 0xb3811e40, uid 10079
,W/AudioManagerAndroid( 5087): Requires BLUETOOTH permission
D/LocationProviderProxy(  972): applying state to connected service
,I/NSApplication( 5087): Starting up...
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 5117): propertyValue:false
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  972): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5185 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 21.578ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 20.409ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 270us total 20.774ms
D/libc-netbsd( 5117): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5117): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5117): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5117): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/art     ( 5117): CheckpointMarkThreadRoots callback created = 0xb04cbef0
,I/art     ( 5117): CheckpointMarkThreadRoots callback created = 0xaae47e20
I/ActivityManager(  972): Process com.lge.qremote (pid 4629) has died
,I/ActivityManager(  972): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5207 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5207): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  972): Process com.lge.appbox.client (pid 4901) has died
,I/dex2oat ( 5224): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=37 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 5224): dex2oat took 111.149ms (threads: 4)
,I/Adreno-EGL( 5117): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5117): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5117): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5117): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5117): Remote Branch: 
I/Adreno-EGL( 5117): Local Patches: 
I/Adreno-EGL( 5117): Reconstruct Branch: 
I/Adreno-EGL( 5117): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5117): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5117): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5117): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5117): Remote Branch: 
I/Adreno-EGL( 5117): Local Patches: 
I/Adreno-EGL( 5117): Reconstruct Branch: 
,I/Adreno-EGL( 5117): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5117): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5117): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5117): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5117): Remote Branch: 
I/Adreno-EGL( 5117): Local Patches: 
I/Adreno-EGL( 5117): Reconstruct Branch: 
,I/ActivityManager(  972): Process com.lge.lgdmsclient (pid 4604) has died
,I/art     ( 5207): CheckpointMarkThreadRoots callback created = 0xb042d6f0
,I/art     ( 5207): CheckpointMarkThreadRoots callback created = 0xb042d6d0
,W/ActivityManager(  972): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
,V/AlarmManager(  972): RTC_WAKEUP set : Alarm{345eadc0 type 0 when 1456731536963 com.android.providers.contacts} when 1456731536963
V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{7c0aaf9 type 2 when 58242 com.google.android.talk} when 58242
D/ActivityManager(  972): enqueue in BackgroundQueue #51 Intent=Intent { act=com.google.android.apps.hangouts.RENEW_ACCOUNT_REGISTRATION flg=0x14 (has extras) }
V/AlarmManager(  972): RTC_WAKEUP set : Alarm{c4e009f type 0 when 1457077179978 com.google.android.googlequicksearchbox} when 1457077179978
I/iu.SyncManager( 4309): SYNC; picasa accounts
,D/NetworkLogImpl( 4309): Loaded NetworkSpeedPredictor
I/iu.Environment( 4309): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 4309): num queued entries: 0
,I/iu.UploadsManager( 4309): num updated entries: 0
I/iu.SyncManager( 4309): NEXT; no task
,I/ActivityManager(  972): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=5251 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/DigitalAppWidgetProvider( 5251): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 2675): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 8:39:40
D/UpdateThreadPoolManager( 2675): 2 : This is isUpdating : false
D/Weather_cast( 2675): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2675): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 8:39:40
D/WeatherService( 2675): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
I/ActivityManager(  972): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5268 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/ActivityManager(  972): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2675): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2675): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2675): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 5268): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 4309): Classify the device as Phone.
,I/WVCdm   (  279): CdmEngine::CloseSession
,I/WVCdm   (  279): L3 Terminate.
D/BluetoothManagerService(  972): Message: 20
D/BluetoothManagerService(  972): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11d7c031:true
,D/BluetoothAdapterService(318850315)( 2050): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16167439
D/BluetoothAdapterService(318850315)( 2050): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16167439
D/libc-netbsd( 4309): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4309): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4309): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4309): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 4309): propertyValue:false
V/SmsReceiverService( 3178): onStart: #1 mResultCode: -1 = Activity.RESULT_OK
,D/MmsConfig( 3178): isNotAllowedSms: currentUser:0
D/MmsConfig( 3178): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3178): isUserMode:false
D/SmsReceiverService( 3178): handleMessage isUserMode:false
V/SmsReceiverService( 3178): handleMessage action: com.android.mms.transaction.SEND_MESSAGE error: 0
I/[LGHome]LGNumberBadgeReceiver( 1880): [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = lge.intent.action.UNREAD_MESSAGES
D/SmsReceiverService( 3178): [LGE] handleSendMessage Send messages in queue
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1880): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1880): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1880): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1880): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
D/libc-netbsd( 4309): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4309): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  972): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=5294 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/libc-netbsd( 4309): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4309): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4309): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4309): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4309): Sending checkin request (7959 bytes)
,W/ResourcesManager( 5294): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5294): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5294): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5294): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5294): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 5294): Using schema version: 115
,I/IndexDatabaseHelper( 5294): Index is fine
D/UsbSettingsReceiver( 5294): [AUTORUN] onReceive() : action = android.hardware.usb.action.USB_STATE
D/UsbSettingsReceiver( 5294): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5294): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5294): [AUTORUN] persist.sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 5294): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsReceiver( 5294): [AUTORUN] onReceive() : getDefaultFunction = ptp_only
D/UsbSettingsReceiver( 5294): [AUTORUN] onReceive() : USB_FUNCTION_CDROM_STORAGE = false
D/UsbSettingsReceiver( 5294): [AUTORUN] onReceive() : mDirectAutorun = true
D/UsbSettingsReceiver( 5294): [AUTORUN] onReceive() : mActivityUsbModeChange = false
D/UsbSettingsReceiver( 5294): [AUTORUN] onReceive() : mActivityFinish = false
D/UsbSettingsReceiver( 5294): [AUTORUN] onReceive() : ===== USB Configured =====
,D/UsbSettingsControl( 5294): [AUTORUN] setUsbConnected() : connected=true
D/UsbSettingsReceiver( 5294): [AUTORUN] onReceive() : checkQmicm = ptp_only,adb
D/UsbSettingsReceiver( 5294): [AUTORUN] : topPackageName=com.test.thalitest
D/UsbSettingsReceiver( 5294): [AUTORUN] : topClassName=com.test.thalitest.MainActivity
,D/UsbSettingsReceiver( 5294): [AUTORUN] Not exist com.android.LGSetupWizard
D/UsbSettingsReceiver( 5294): [AUTORUN] setUsbConnect() : mUsbSettingsRun = false
D/UsbSettingsReceiver( 5294): [AUTORUN] startUsbSettings() : deviceProvisioned=1
I/ActivityManager(  972): Killing 3577:com.android.defcontainer/u0a4 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10004/pid_3577/cgroup.procs: No such file or directory
,I/ActivityManager(  972): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5319 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/MtpService( 3228): updating state; isCurrentUser=true, mMtpLocked=false
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/PCSuite ( 5319): [StartReceiver]USB CONNECTED ver UsbManger : ptp_only
,I/PCSuite ( 5319): [StartReceiver]isUsbPCSuiteMode : false
D/PCSuite ( 5319): [StartReceiver][checkEUTStatus] eutStatus = 
D/PCSuite ( 5319): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5319): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  972): Killing 4946:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10038/pid_4946/cgroup.procs: No such file or directory
,V/LGMDMManager( 5268): Create singleton instance
,D/AlertReceiver( 3827): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 3827): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 3827): [updateWidgets] 
,D/MonthWidgetProvider( 3827): [onReceive]
D/CalendarWidgetProvider( 3827): [onReceive]
D/CalendarWidgetProvider( 3827): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,D/CalendarTypeController( 3827): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 3827): [onReceive]
D/CalendarWidgetProvider( 3827): [onReceive]
D/CalendarWidgetProvider( 3827): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 3827): [onCreate] mContext.getPackageName() = com.android.calendar
I/DigitalAppWidgetProvider( 5251): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 2675): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 8:39:41
D/UpdateThreadPoolManager( 2675): 2 : This is isUpdating : false
D/Weather_cast( 2675): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2675): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 8:39:41
D/WeatherService( 2675): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
W/ActivityManager(  972): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2675): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2675): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2675): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/[SystemUI]SafeModeBroadcastReceiver( 1375): onReceive = com.lge.statusbar.bootcompleted
,D/CalendarWeatherReceiver( 3827): Get action=com.lge.calendar.action.WEATHER_SERVICE_START
I/CheckinResponseProcessor( 4309): From server: 3 gservices updates and 0 deletes
,I/ActivityManager(  972): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.MediaScanReceiver: pid=5340 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,D/UEI.SmartControl( 4979): Internal timer expired: 1
,D/UEI.SmartControl( 4979): Service.onUnbind: IControl
D/UEI.SmartControl( 4979): Service.onDestroy
D/UEI.SmartControl( 4979): Shutdown IRRCPlayer... 
W/irrc_jni( 4979): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 4979): ~IrrcClient ++ 
D/irrcClient( 4979): ~IrrcClient -- 
W/irrc_jni( 4979): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 4979): Blaster closed
D/UEI.SmartControl( 4979): Blaster closed
D/UEI.SmartControl( 4979): Shut down QS...
D/UEI.SmartControl( 4979): Stopped file observer...
I/UEI.SmartControl( 4979): QS lib stop result = true
D/UEI.SmartControl( 4979): QS shutdown complete
,I/ActivityManager(  972): Process com.google.android.talk (pid 5036) has died
,V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{2a3e4f8f type 2 when 76817 android} when 76817
,E/MediaScanReceiver( 5340): media scanning start or checking
W/MainApplication( 5340): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/CertBlacklister(  972): Certificate blacklist changed, updating...
,I/ActivityManager(  972): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5357 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/CertBlacklister(  972): Certificate blacklist updated
,I/GservicesProvider( 3998): main difference update completed
,I/CheckinRequestBuilder( 4309): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4309): Failed to find provider info for com.google.android.wearable.settings
,I/chromium( 4921): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
I/chromium( 4921): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,I/CheckinRequestBuilder( 4309): Classify the device as Phone.
,I/CheckinTask( 4309): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4309): Checking schedule, now: 1457077182010 next: 1457604431001
I/CheckinService( 4309): active receiver: disabled
,I/MusicStore( 5357): Database version: 120
,D/CheckinService( 4309): Recording last checkin time for package unspecified as 1457077182040
,I/ActivityManager(  972): Killing 4996:com.lge.drmservice/u0a51 (adj 15): empty #11
,I/ActivityManager(  972): Killing 4979:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #12
,W/libprocessgroup(  972): failed to open /acct/uid_10051/pid_4996/cgroup.procs: No such file or directory
,W/libprocessgroup(  972): failed to open /acct/uid_10089/pid_4979/cgroup.procs: No such file or directory
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5357): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5357): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5357): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,I/art     (  972): Explicit concurrent mark sweep GC freed 26788(1411KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.136ms total 145ms
,W/ResourcesManager( 5357): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5357): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5357): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5357): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5357): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@33a7d8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5357): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5357): GMSCore installation verified
,I/ConfigStore( 5357): Config Database version: 1
,I/MediaRouter( 5357): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 5357): type=WIFI subType= reason=null isConnected=true
D/ToneMappingReceiver( 5251): Enter doAlarmRingToneUriMapping()
,D/ToneMappingReceiver( 5251): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5251): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
,D/CommonUtil( 5251): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5251): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5251): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5251): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5251): Alarm Success count is 0
D/ToneMappingReceiver( 5251): Timer Success count is 0
,I/MediaScannerReceiver( 3827): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///system/media
I/NetworkMonitor( 5357): type=WIFI subType= reason=null isConnected=true
E/MediaScanReceiver( 5340): media scanning finished
I/InitNotificationRingtoneService( 3827): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3827): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/com.lge.bnr.receiver.MediaScanReceiver( 5340): android.intent.action.MEDIA_SCANNER_FINISHED
I/GHttpClientFactory( 5357): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/AlertUtils( 3827): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/GoogleURLConnFactory( 5357): Using platform SSLCertificateSocketFactory
I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
E/MediaScanReceiver( 5340): media scanning start or checking
,I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
D/ToneMappingReceiver( 5251): Enter doAlarmRingToneUriMapping()
,D/ToneMappingReceiver( 5251): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5251): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5251): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5251): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5251): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5251): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5251): Alarm Success count is 0
D/ToneMappingReceiver( 5251): Timer Success count is 0
I/MediaScannerReceiver( 3827): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///storage/emulated/0
E/MediaScanReceiver( 5340): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 5340): android.intent.action.MEDIA_SCANNER_FINISHED
,I/NotificationManager( 5357): com.google.android.music: cancel(1061) by com.google.android.music
I/art     ( 3228): Explicit concurrent mark sweep GC freed 15849(843KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/10MB, paused 403us total 52.358ms
,I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3827): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/ActivityManager(  972): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5414 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AlertUtils( 3827): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3827): End InitializeAlertRingtoneService.onHandleIntent
I/InitNotificationRingtoneService( 3827): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3827): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 3827): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
W/ResourcesManager( 5414): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3827): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3827): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,I/AlertUtils( 3827): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3827): End InitializeAlertRingtoneService.onHandleIntent
D/CalendarProvider2( 5414): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@521ff82
,I/art     ( 5357): CheckpointMarkThreadRoots callback created = 0xb042d440
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/CalendarProvider2( 5414): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5414): Created com.android.providers.calendar.CalendarAlarmManager@1d6308ef(com.android.providers.calendar.CalendarProvider2@521ff82)
D/CalendarProviderBroadcastReceiver( 5414): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5414): [IntentService] WakeLock acquire, start IntentSerivce
,D/CalendarProvider2( 5414): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 5414): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
,D/CalendarProvider2( 5414): [getOrCreateCalendarAlarmManager]
I/art     ( 5357): CheckpointMarkThreadRoots callback created = 0xb042d410
,D/CalendarProvider2( 5414): [IntentService] Release Lock
,D/CalendarProvider2( 5414): CalendarProviderIntentService.onDestroy()
I/art     ( 3998): Explicit concurrent mark sweep GC freed 9606(470KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.448ms total 33.574ms
,I/ActivityManager(  972): Killing 5087:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10079/pid_5087/cgroup.procs: No such file or directory
,D/WearableService( 1735): callingUid 10006, callindPid: 1735
,D/LocationInitializer( 4309): Restart initialization of location
,D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1735): [137] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/MediaStoreImporter( 5357): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  972): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5442 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/art     ( 4309): Explicit concurrent mark sweep GC freed 17911(1368KB) AllocSpace objects, 25(400KB) LOS objects, 40% free, 11MB/19MB, paused 1.141ms total 87.657ms
,W/IcingInternalCorpora( 4309): getNumBytesRead when not calculated.
,W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5442): getAccountsCursor
,I/art     (  972): Explicit concurrent mark sweep GC freed 11005(596KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.227ms total 142.183ms
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager(  972): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/GAV2    ( 5442): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/Gmail   ( 5442): Observing account changes for notifications
,W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 5442): Error finding the version of the Email provider.....
E/Gmail   ( 5442): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5442): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5442): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5442): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5442): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5442): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5442): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5442): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5442): We do not support migrating this version of the Email provider.
,I/Gmail   ( 5442): getAccountsCursor
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1735): No location to return for getLastLocation()
,W/FusedLocationProvider( 1735): location=null
V/DownloadManager( 3228): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3228): created cursor android.database.sqlite.SQLiteCursor@274824c7 on behalf of 4309
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  972): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5506 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/Gmail   ( 5442): notifyAccountChanged
,I/Gmail   ( 5442): getAccountsCursor
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5442): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5442): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5442): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5442): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 5442): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PhoneMonitor( 5506): Register our PhoneStateListener
,V/DownloadManager( 3228): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3228): created cursor android.database.sqlite.SQLiteCursor@2dd67af4 on behalf of 4309
V/DownloadManager( 3228): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3228): created cursor android.database.sqlite.SQLiteCursor@2a80e21d on behalf of 4309
I/ActivityManager(  972): Killing 5185:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10048/pid_5185/cgroup.procs: No such file or directory
,D/PhoneMonitor( 5506): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
V/TelephonyAutoProfiling( 5506): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5506): [parse] Load xml
I/CheckinService( 4309): Checkin interval check for package: unspecified last checkin: 1457077182040 min interval config: 0 actual interval: 2418
,V/TelephonyAutoProfiling( 5506): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5506): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 5506): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/CheckinService( 4309): Checking schedule, now: 1457077184473 next: 1457077212001
I/CheckinService( 4309): active receiver: disabled
,I/ActivityManager(  972): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5531 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 416us total 33.514ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 25.304ms
,W/ResourcesManager( 5531): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 344us total 20.608ms
,I/Babel_SMS( 5531): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5531): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5531): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5531): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5531): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5531): MmsConfig.loadFromResources
E/Babel_SMS( 5531): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5531): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 5531): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5531): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5531): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5531): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5531): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5531): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5531): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5531): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5531): found sensor: LGE Step Counter Sensor, handle=44
,D/SensorManager( 5531): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5531): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5531): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5531): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5531): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5531): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5531): found sensor: Motion Accel, handle=46
I/art     ( 5531): CheckpointMarkThreadRoots callback created = 0xb042d550
,I/NotificationManager( 1966): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,W/Settings( 5531): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5531): startup - clean
,I/art     ( 5531): CheckpointMarkThreadRoots callback created = 0xb042d530
I/Babel   ( 5531): deleted: false for 0
,W/AudioCapabilities( 5531): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5531): Unsupported mime audio/adpcm
W/AudioCapabilities( 5531): Unsupported mime audio/g726
,W/AudioCapabilities( 5531): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5531): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5531): Unsupported mime video/mjpg
W/VideoCapabilities( 5531): Unsupported mime video/theora
,W/AudioCapabilities( 5531): Unsupported mime audio/evrc
,W/AudioCapabilities( 5531): Unsupported mime audio/qcelp
W/VideoCapabilities( 5531): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5531): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5531): Unsupported mime audio/qcelp
W/AudioCapabilities( 5531): Unsupported mime audio/evrc
W/VideoCapabilities( 5531): Unsupported mime video/mp4v-esdp
,I/ActivityManager(  972): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5579 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AudioManager( 5268): getMode name:com.lge.qremote
,I/AudioManager( 5268): getMode name:com.lge.qremote
,I/VideoCapabilities( 5531): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 5531): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5531): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5531): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5531): Unrecognized profile 2130706433 for video/avc
I/art     ( 1735): Explicit concurrent mark sweep GC freed 23579(1342KB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 13MB/22MB, paused 19.360ms total 135.975ms
I/ActivityManager(  972): Process com.google.android.apps.plus (pid 5207) has died
,I/ActivityManager(  972): Killing 5294:com.android.settings/1000 (adj 15): empty #11
,I/vclib   ( 5531): onServiceConnected
W/Babel   ( 5531): Attempted to change video mute state without an active call.
I/NotificationManager( 5531): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/UEI.SmartControl( 5579): Quickset Services start...
,I/UEI.SmartControl( 5579): Manufacture = LGE
D/UEI.SmartControl( 5579): File observer start...
E/UEI.SmartControl( 5579): IR Port is disabled: false
D/UEI.SmartControl( 5579): Starting file observer...
D/UEI.SmartControl( 5579): Extracting JNI libs...
D/UEI.SmartControl( 5579): --- this system supports 32-bit or 64-bit only
W/libprocessgroup(  972): failed to open /acct/uid_1000/pid_5294/cgroup.procs: No such file or directory
I/AudioManager( 5268): getMode name:com.lge.qremote
,I/AudioManager( 5268): getMode name:com.lge.qremote
,I/AudioManager( 5268): getMode name:com.lge.qremote
I/ActivityManager(  972): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5598 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5598): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5598): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5598): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5579): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5579): --- Checking lib: libqs_armeabi-v7a.zip
,D/UEI.SmartControl( 5579): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 5579): --- Selecting new region: 2
I/UEI.SmartControl( 5579): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5579): Platform has CIR...
D/UEI.SmartControl( 5579): NO CIR support, need to check package...
,I/UEI.SmartControl( 5579): Model: LG-D722 uses JNI
I/LGEmail ( 5598): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/UEI.SmartControl( 5579): QS Service created
D/LGEmail ( 5598): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,E/UEI.SmartControl( 5579): QS start get config
D/UEI.SmartControl( 5579): Loading JNI Libs...
,D/UEI.SmartControl( 5579):  configuring local db...
,I/PackageChangeReceiver( 5598): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  972): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5622 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  972): Killing 5319:com.lge.sync/1000 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_1000/pid_5319/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/UEI.SmartControl( 5579):  ---- Has DB8: true
,D/UEI.SmartControl( 5579): QS start statue = true Error code = 0
D/UEI.SmartControl( 5579): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5579): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5579): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5579): IRRCPlayer_nativeInit ++ 
,D/irrcClient( 5579): IrrcClient ++ 
D/irrcClient( 5579): getIrrcService ++ 
D/irrcClient( 5579): getIrrcService -- 
D/irrcClient( 5579): IrrcClient -- 
W/irrc_jni( 5579): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5579): Services init done
I/UEI.SmartControl( 5579): Device manager: loading config....
D/UEI.SmartControl( 5579): Config is loaded...
,I/ActivityManager(  972): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5645 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/UEI.SmartControl( 5579): QS Service init finished
D/UEI.SmartControl( 5579): QS Service version name: 0.1.73
I/ActivityManager(  972): Killing 5251:com.lge.clock/u0a10 (adj 15): empty #11
D/UEI.SmartControl( 5579): QS Service version code: 1073
D/UEI.SmartControl( 5579): Service requested: Control
D/UEI.SmartControl( 5579):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 5579): Notify AllClients services are ready: 0
D/UEI.SmartControl( 5579): Internal service binding...
,W/libprocessgroup(  972): failed to open /acct/uid_10010/pid_5251/cgroup.procs: No such file or directory
D/UEI.SmartControl( 5579): -----IControl: 11
D/UEI.SmartControl( 5579): Caller: com.lge.qremote
D/UEI.SmartControl( 5579): ------------ IControl registerCallback...
I/UEI.SmartControl( 5579): Registering callback...
D/UEI.SmartControl( 5579): -----IControl: 19
D/UEI.SmartControl( 5579): Caller: com.lge.qremote
I/UEI.SmartControl( 5579): Registering Services Ready callback...
I/UEI.SmartControl( 5579): Notify client services are ready...
D/UEI.SmartControl( 5579): -----IControl: 8
,D/UEI.SmartControl( 5579): Caller: com.lge.qremote
I/ActivityManager(  972): Killing 5357:com.google.android.music:main/u0a81 (adj 15): empty #11
,I/ActivityManager(  972): Killing 5340:com.lge.bnr/1000 (adj 15): empty #12
,D/AlertService( 3827): Beginning updateAlertNotification
I/AppUp4:AppBoxCP( 5645): onCreate
,W/AppUp4:DB( 5645):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5645):  setFingerPrint start
I/AppUp4:DB( 5645):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 5645):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5645):  SDK version = 0
I/AppUp4:DB( 5645):  beforefinger == newfinger no write in DB
W/libprocessgroup(  972): failed to open /acct/uid_10081/pid_5357/cgroup.procs: No such file or directory
W/libprocessgroup(  972): failed to open /acct/uid_1000/pid_5340/cgroup.procs: No such file or directory
D/AppUp4:AppBoxApplication( 5645): AppBoxApplication onCreate()
,D/AlertService( 3827): No fired or scheduled alerts
I/NotificationManager( 3827): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3827): com.android.calendar: cancel(1) by com.android.calendar
,I/NotificationManager( 3827): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3827): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3827): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3827): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3827): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3827): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3827): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3827): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3827): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3827): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3827): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3827): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3827): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3827): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3827): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3827): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3827): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3827): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3827): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 3827): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AppUp4:PreloadHelper( 5645): removed from Exclude : com.test.thalitest : 1
,D/AlarmScheduler( 3827): No events found starting within 1 week.
I/ActivityManager(  972): Killing 5414:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10014/pid_5414/cgroup.procs: No such file or directory
,I/ActivityManager(  972): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5665 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 5665): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5665): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5665): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 5665): Total System Memory = 906309632
,I/GalleryUtils( 5665): Application Heap = 96 MB
I/AppConfig( 5665): App Tier : NOT_DEF
D/SystemHelper( 5665): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  972): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5684 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  972): Killing 5442:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10053/pid_5442/cgroup.procs: No such file or directory
,W/ResourcesManager( 5684): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5684): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5684): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5684): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5684): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 5684): BUILD Country: EU
I/SystemConfig( 5684): BUILD Operator: OPEN
,I/ActivityManager(  972): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5704 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  972): Killing 5506:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/libprocessgroup(  972): failed to open /acct/uid_10038/pid_5506/cgroup.procs: No such file or directory
,I/SystemConfig( 5684): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5684): existFile = false
I/SystemConfig( 5684): canReadFile = false
I/SystemConfig( 5684): systemFeature RCS result false
D/SystemConfig( 5684): refreshRcsSupport() :false
I/LockScreenSettings( 5704): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/art     (  972): Explicit concurrent mark sweep GC freed 19435(928KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.141ms total 134.041ms
,I/LockScreenSettings( 5704): New app installed broadcast received ..
I/LockScreenSettings( 5704): Number of installed packages  1
I/ActivityManager(  972): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5721 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  972): Killing 5531:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10061/pid_5531/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 5721): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5721): uri : package:com.test.thalitest
,I/ActivityManager(  972): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5738 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  972): Killing 5117:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10006/pid_5117/cgroup.procs: No such file or directory
D/InitAlarmsService( 3827): Clearing and rescheduling alarms.
,D/[BNRAppListMgrReceiver]( 5738): android.intent.action.PACKAGE_ADDED : com.test.thalitest
W/MainApplication( 5738): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ActivityManager(  972): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5755 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  972): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5772 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  972): Killing 3998:com.google.process.gapps/u0a6 (adj 15): empty #11
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 25.055ms
,I/CheckinService( 4309): Done disabling old GoogleServicesFramework version
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 261us total 24.348ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 21.226ms
,W/libprocessgroup(  972): failed to open /acct/uid_10006/pid_3998/cgroup.procs: No such file or directory
W/ResourcesManager( 5755): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5755): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@521ff82
,D/CalendarProvider2( 5755): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5755): Created com.android.providers.calendar.CalendarAlarmManager@1d6308ef(com.android.providers.calendar.CalendarProvider2@521ff82)
D/CalendarProvider2( 5755): Scheduling check of next Alarm
D/CalendarProvider2( 5755): SCHEDULE_ALARM_REMOVE
,I/ActivityManager(  972): Killing 3827:com.android.calendar/u0a13 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10013/pid_3827/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/GAv4    ( 5772): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5772):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5772):   adb logcat -s GAv4
,W/GAv4    ( 5772): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5772): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5772): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5772): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,E/VoldCmdListener(  246): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  246): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  246): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5772): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
,W/ResourcesManager( 5772): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5772): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  972): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5815 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  972): Killing 5579:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 5268): android.os.DeadObjectException
,W/System.err( 5268): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5268): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5268): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5268): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5268): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5268): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5268): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5268): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5268): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5268): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5268): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5268): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5268): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5268): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5268): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5268): android.os.DeadObjectException
W/System.err( 5268): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5268): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5268): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5268): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5268): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5268): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5268): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5268): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5268): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5268): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5268): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5268): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5268): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5268): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5268): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  972): failed to open /acct/uid_10089/pid_5579/cgroup.procs: No such file or directory
W/ActivityManager(  972): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/CalendarProvider2( 5755): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5755): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/art     ( 5772): CheckpointMarkThreadRoots callback created = 0xaaf2a220
I/ActivityManager(  972): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5833 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     ( 5772): CheckpointMarkThreadRoots callback created = 0xb050fa70
,I/ActivityManager(  972): Killing 5268:com.lge.qremote/u0a106 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/ResourcesManager( 5815): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 5772): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/ActivityManager(  972): Killing 5598:com.lge.email/u0a21 (adj 15): empty #11
,W/System  ( 5772): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5772): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  972): failed to open /acct/uid_10106/pid_5268/cgroup.procs: No such file or directory
W/libprocessgroup(  972): failed to open /acct/uid_10021/pid_5598/cgroup.procs: No such file or directory
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/UEI.SmartControl( 5833): Quickset Services start...
,I/UEI.SmartControl( 5833): Manufacture = LGE
D/UEI.SmartControl( 5833): File observer start...
E/UEI.SmartControl( 5833): IR Port is disabled: false
D/UEI.SmartControl( 5833): Starting file observer...
D/UEI.SmartControl( 5833): Extracting JNI libs...
D/UEI.SmartControl( 5833): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 5833): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5833): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5833): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 5833): --- Selecting new region: 2
,I/UEI.SmartControl( 5833): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5833): Platform has CIR...
D/UEI.SmartControl( 5833): NO CIR support, need to check package...
I/UEI.SmartControl( 5833): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 5833): QS Service created
E/UEI.SmartControl( 5833): QS start get config
,D/UEI.SmartControl( 5833): Loading JNI Libs...
,D/UEI.SmartControl( 5833):  configuring local db...
I/ActivityManager(  972): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5868 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  972): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5886 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1966): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/UEI.SmartControl( 5833):  ---- Has DB8: true
I/GservicesProvider( 5868): Gservices pushing to system: true; secure/global: true
D/UEI.SmartControl( 5833): QS start statue = true Error code = 0
D/UEI.SmartControl( 5833): QS version = v2.7.11.1_RC1
,D/UEI.SmartControl( 5833): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5833): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5833): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5833): IrrcClient ++ 
D/irrcClient( 5833): getIrrcService ++ 
D/irrcClient( 5833): getIrrcService -- 
D/irrcClient( 5833): IrrcClient -- 
W/irrc_jni( 5833): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5833): Services init done
I/UEI.SmartControl( 5833): Device manager: loading config....
,D/UEI.SmartControl( 5833): QS Service init finished
D/UEI.SmartControl( 5833): Config is loaded...
D/UEI.SmartControl( 5833): QS Service version name: 0.1.73
D/UEI.SmartControl( 5833): QS Service version code: 1073
D/UEI.SmartControl( 5833): Service requested: Control
D/UEI.SmartControl( 5833): Service.onUnbind: IControl
D/UEI.SmartControl( 5833): Service.onDestroy
D/UEI.SmartControl( 5833): Shutdown IRRCPlayer... 
,W/irrc_jni( 5833): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5833): ~IrrcClient ++ 
D/irrcClient( 5833): ~IrrcClient -- 
W/irrc_jni( 5833): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5833): Blaster closed
D/UEI.SmartControl( 5833): Blaster closed
D/UEI.SmartControl( 5833): Shut down QS...
D/UEI.SmartControl( 5833): Stopped file observer...
,I/UEI.SmartControl( 5833): QS lib stop result = true
D/UEI.SmartControl( 5833): QS shutdown complete
D/UEI.SmartControl( 5833): QS Service created
I/UpdateIcingCorporaServi( 1966): UpdateCorporaTask done [took 140 ms] updated apps [took 140 ms] 
I/UEI.SmartControl( 5833): Notify AllClients services are ready: 11
,E/UEI.SmartControl( 5833): QS start get config
D/UEI.SmartControl( 5833):  configuring local db...
,I/GoogleHttpClient( 5868): GMS http client unavailable, use old client
,I/GoogleHttpClient( 5868): GMS http client unavailable, use old client
,I/ActivityManager(  972): Killing 5622:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10009/pid_5622/cgroup.procs: No such file or directory
,D/Finsky  ( 5886): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 5833):  ---- Has DB8: true
,D/UEI.SmartControl( 5833): QS start statue = true Error code = 0
D/UEI.SmartControl( 5833): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5833): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5833): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5833): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5833): IrrcClient ++ 
D/irrcClient( 5833): getIrrcService ++ 
D/irrcClient( 5833): getIrrcService -- 
D/irrcClient( 5833): IrrcClient -- 
W/irrc_jni( 5833): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5833): Services init done
I/UEI.SmartControl( 5833): Device manager: loading config....
D/UEI.SmartControl( 5833): QS Service init finished
D/UEI.SmartControl( 5833): QS Service version name: 0.1.73
D/UEI.SmartControl( 5833): QS Service version code: 1073
D/UEI.SmartControl( 5833): Service requested: Control
,D/UEI.SmartControl( 5833): Config is loaded...
,D/UEI.SmartControl( 5833):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5833): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 5833): Request IControl service: devices are loaded...
I/ActivityManager(  972): Killing 5645:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10011/pid_5645/cgroup.procs: No such file or directory
,E/ActivityThread( 5833): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@1301450b that was originally bound here
E/ActivityThread( 5833): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@1301450b that was originally bound here
E/ActivityThread( 5833): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5833): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5833): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5833): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5833): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5833): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 5833): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 5833): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 5833): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5833): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5833): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5833): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5833): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5833): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5833): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5833): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5833): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5833): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 5833): Internal service binding...
,D/Finsky  ( 5886): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5886): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5886): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5886): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3228): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,I/NotificationManager( 5886): com.android.vending: cancel(1003285959) by com.android.vending
V/DownloadManager( 3228): created cursor android.database.sqlite.SQLiteCursor@1d334c92 on behalf of 5886
,D/Ads     ( 5886): Skipping gmscore version check
,D/Finsky  ( 5886): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5886): [1] Libraries$2.run: Finished loading 1 libraries.
D/ChimeraCfgMgr( 4309): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4309): Loading module APK com.google.android.play.games
D/PackageBroadcastService( 4309): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/Finsky  ( 5886): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Finsky  ( 5886): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 5886): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/ChimeraCfgMgr( 4309): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4309): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4309): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/Icing   ( 4309): Storage manager: low false usage 1.74MB avail 2.37GB capacity 4.06GB
D/AsyncTaskServiceImpl( 4309): Submit a task: k
,I/ActivityManager(  972): Killing 5665:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10023/pid_5665/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 4309): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 4309): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/k       ( 4309): Processing package: com.test.thalitest
,D/GassUtils( 4309): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 4309): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 4309): Using Auth Proxy for data requests.
W/BaseAppContext( 4309): Using Auth Proxy for data requests.
W/BaseAppContext( 4309): Using Auth Proxy for data requests.
,D/UEI.SmartControl( 5833): Internal timer expired: 2
W/System.err( 5833): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1301450b
,W/System.err( 5833): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 5833): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 5833): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 5833): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 5833): 	at com.uei.control.Service.a(Unknown Source)
W/System.err( 5833): 	at com.uei.control.l.run(Unknown Source)
W/System.err( 5833): 	at java.util.Timer$TimerImpl.run(Timer.java:284)
E/UEI.SmartControl( 5833): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1301450b
I/ActivityManager(  972): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5976 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/BaseAppContext( 4309): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 4309): cleanUpNonGplusAccounts done.
,W/BaseAppContext( 4309): Using Auth Proxy for data requests.
,W/ResourcesManager( 5976): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  972): Message: 20
D/BluetoothManagerService(  972): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2e55fedb:true
,D/BluetoothAdapterService(318850315)( 2050): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16167439
,D/BluetoothAdapterService(318850315)( 2050): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16167439
I/Icing   ( 4309): updateResources: need to parse f{com.google.android.gms}
,V/LGMDMManager( 5976): Create singleton instance
,I/AudioManager( 5976): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5833): -----IControl: 11
D/UEI.SmartControl( 5833): File observer start...
E/UEI.SmartControl( 5833): IR Port is disabled: false
D/UEI.SmartControl( 5833): Starting file observer...
D/UEI.SmartControl( 5833): Caller: com.lge.qremote
D/UEI.SmartControl( 5833): ------------ IControl registerCallback...
I/UEI.SmartControl( 5833): Registering callback...
D/UEI.SmartControl( 5833): -----IControl: 19
D/UEI.SmartControl( 5833): Caller: com.lge.qremote
I/UEI.SmartControl( 5833): Registering Services Ready callback...
I/UEI.SmartControl( 5833): Notify client services are ready...
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/UEI.SmartControl( 5833): -----IControl: 8
D/UEI.SmartControl( 5833): Caller: com.lge.qremote
D/WearableService( 1735): callingUid 10006, callindPid: 1735
E/MDM     ( 1735): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
I/ActivityManager(  972): Killing 5684:com.android.contacts/u0a18 (adj 15): empty #11
,D/LocationInitializer( 4309): Restart initialization of location
,W/libprocessgroup(  972): failed to open /acct/uid_10018/pid_5684/cgroup.procs: No such file or directory
D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  972): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6005 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
I/Icing   ( 4309): Internal init done: storage state 0
,I/Icing   ( 4309): Post-init done
,W/ResourcesManager( 6005): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6005): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6005): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6005): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6005): MmsConfig.loadFromDatabase
D/ChimeraCfgMgr( 4309): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4309): Module APK com.google.android.play.games already loaded
,E/Babel_SMS( 6005): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6005): MmsConfig.loadFromResources
E/Babel_SMS( 6005): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6005): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,D/SensorManager( 6005): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6005): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6005): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6005): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6005): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6005): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6005): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6005): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6005): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6005): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6005): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6005): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6005): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6005): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6005): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6005): found sensor: Motion Accel, handle=46
,W/Settings( 6005): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6005): startup - clean
I/art     ( 6005): CheckpointMarkThreadRoots callback created = 0xb042d8e0
,I/art     ( 6005): CheckpointMarkThreadRoots callback created = 0xb042d8c0
,I/Babel   ( 6005): deleted: false for 0
,I/art     (  972): Explicit concurrent mark sweep GC freed 21977(1022KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.007ms total 154.080ms
,W/AudioCapabilities( 6005): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6005): Unsupported mime audio/adpcm
W/AudioCapabilities( 6005): Unsupported mime audio/g726
W/AudioCapabilities( 6005): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6005): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6005): Unsupported mime video/mjpg
W/VideoCapabilities( 6005): Unsupported mime video/theora
W/AudioCapabilities( 6005): Unsupported mime audio/evrc
,W/AudioCapabilities( 6005): Unsupported mime audio/qcelp
W/VideoCapabilities( 6005): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  972): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6037 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/AudioCapabilities( 6005): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6005): Unsupported mime audio/qcelp
W/AudioCapabilities( 6005): Unsupported mime audio/evrc
W/VideoCapabilities( 6005): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 6005): Unsupported profile 4 for video/mp4v-es
,I/AppUp4:AppBoxCP( 6037): onCreate
W/AppUp4:DB( 6037):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6037):  setFingerPrint start
I/AppUp4:DB( 6037):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6037):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6037):  SDK version = 0
I/AppUp4:DB( 6037):  beforefinger == newfinger no write in DB
W/VideoCapabilities( 6005): Unrecognized profile 2130706433 for video/avc
D/AppUp4:AppBoxApplication( 6037): AppBoxApplication onCreate()
W/VideoCapabilities( 6005): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6005): Unrecognized profile 2130706433 for video/avc
I/[SystemUI]QPairHandler( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
,W/VideoCapabilities( 6005): Unrecognized profile 2130706433 for video/avc
I/InputReader(  972): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/AppUp4:CustModeStarterReceiver( 6037): onReceive
I/AppUp4:CustModeStarterReceiver( 6037): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,D/AppUp4:CustFacade( 6037): Context : android.app.ReceiverRestrictedContext@22b46c9
D/AppUp4:CustFacade( 6037): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6037): isSimDevice : true
D/administrator(  972): Handling package changes for user 0
D/AppUp4:CustModeStarterReceiver( 6037): begin check event
I/AppUp4:CustModeStarterReceiver( 6037): Event For Nothing, skip.
,I/ActivityManager(  972): Killing 5704:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/libprocessgroup(  972): failed to open /acct/uid_10069/pid_5704/cgroup.procs: No such file or directory
I/ActivityManager(  972): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6058 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/NotificationService(  972): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  972): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  972): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  972): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/BackupManagerService(  972): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  972): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@35e6972d
I/vclib   ( 6005): onServiceConnected
W/Babel   ( 6005): Attempted to change video mute state without an active call.
I/NotificationManager( 6005): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6005): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6005): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6058): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6058): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6058): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/ResourcesManager(  972): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/JNIHelp ( 6005): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/ResourceType(  972): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1735): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/AppConfig( 6058): Total System Memory = 906309632
,I/GalleryUtils( 6058): Application Heap = 96 MB
I/AppConfig( 6058): App Tier : NOT_DEF
W/System  ( 6005): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6005): Installed default security provider GmsCore_OpenSSL
,D/SystemHelper( 6058): region [EU], country [EU], operator [OPEN], sub-operator []
D/LocationProviderProxy(  972): applying state to connected service
I/NotificationManager( 6005): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/Icing   ( 4309): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/ActivityManager(  972): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6081 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  972): Killing 5721:com.lge.eula/1000 (adj 15): empty #11
,D/Icing   ( 4309): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 4309): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
W/libprocessgroup(  972): failed to open /acct/uid_1000/pid_5721/cgroup.procs: No such file or directory
,D/LCardEmulationManager( 1789): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1789): getDefaultRoute
W/ResourcesManager( 6081): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6081): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6081): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6081): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6081): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6081): BUILD Country: EU
I/SystemConfig( 6081): BUILD Operator: OPEN
,I/ActivityManager(  972): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6103 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  972): Killing 5738:com.lge.bnr/1000 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_1000/pid_5738/cgroup.procs: No such file or directory
,I/SystemConfig( 6081): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6081): existFile = false
I/SystemConfig( 6081): canReadFile = false
I/SystemConfig( 6081): systemFeature RCS result false
D/SystemConfig( 6081): refreshRcsSupport() :false
,I/LockScreenSettings( 6103): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6103): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6103): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6103): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6103): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6103): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  972): Killing 5772:com.google.android.apps.docs/u0a58 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1966): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/UpdateIcingCorporaServi( 1966): UpdateCorporaTask done [took 59 ms] updated apps [took 59 ms] 
,W/libprocessgroup(  972): failed to open /acct/uid_10058/pid_5772/cgroup.procs: No such file or directory
V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{edff44b type 2 when 88228 com.android.providers.calendar} when 88228
D/PackageBroadcastService( 4309): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4309): Null package name or gms related package.  Ignoreing.
I/AudioManager( 5976): getMode name:com.lge.qremote
,I/Icing   ( 4309): updateResources: need to parse f{com.google.android.gms}
I/AudioManager( 5976): getMode name:com.lge.qremote
,I/ActivityManager(  972): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=6135 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 21.498ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 288us total 21.134ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 21.219ms
,I/ActivityManager(  972): Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=6171 uid=10003 gids={50003, 9997, 3003} abi=armeabi-v7a
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ActivityManager(  972): Killing 5755:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10014/pid_5755/cgroup.procs: No such file or directory
,E/UpdateRequestReceiver( 6171): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6171): Received malformed URL while handling Gservices.CHANGED_ACTION
E/UpdateRequestReceiver( 6171): Received malformed URL while handling Gservices.CHANGED_ACTION
,E/UpdateRequestReceiver( 6171): Received malformed URL while handling Gservices.CHANGED_ACTION
I/ActivityManager(  972): Killing 6037:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10011/pid_6037/cgroup.procs: No such file or directory
,I/CheckinService( 4309): Checkin interval check for package: unspecified last checkin: 1457077182040 min interval config: 0 actual interval: 11661
,I/GservicesUpdateTask( 1966): Updating Gservices keys
,I/CheckinService( 4309): Checking schedule, now: 1457077193725 next: 1457077212001
I/CheckinService( 4309): active receiver: disabled
I/SystemUpdateService( 4309): receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
,D/SystemUpdateService( 4309): onCreate
D/SystemUpdateService( 4309): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,I/art     ( 5868): Explicit concurrent mark sweep GC freed 9086(458KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 804us total 52.998ms
,I/art     ( 4309): Explicit concurrent mark sweep GC freed 57212(3MB) AllocSpace objects, 29(464KB) LOS objects, 40% free, 14MB/23MB, paused 1.206ms total 90.814ms
,W/SQLiteConnectionPool( 4309): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/SystemUpdateService( 4309): cancelUpdate (empty URL)
I/SystemUpdateService( 4309): active receiver: disabled
I/NotificationManager( 4309): com.google.android.gms: cancel(2130838165) by com.google.android.gms
,I/NotificationManager( 4309): com.google.android.gms: cancel(2130838166) by com.google.android.gms
,I/art     ( 5868): Explicit concurrent mark sweep GC freed 2491(96KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 734us total 25.620ms
,D/SystemUpdateService( 4309): onDestroy
,E/DynamiteModule( 4309): Failed to load IDynamiteLoader from GmsCore
E/DynamiteModule( 4309): java.lang.ClassNotFoundException: Didn't find class "com.google.android.gms.chimera.container.DynamiteLoaderImpl" on path: DexPathList[[zip file "/system/framework/com.android.location.provider.jar", zip file "/system/framework/com.android.media.remotedisplay.jar", zip file "/data/app/com.google.android.gms-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /data/app/com.google.android.gms-1/lib/arm, /vendor/lib, /system/lib]]
E/DynamiteModule( 4309): 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
E/DynamiteModule( 4309): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
E/DynamiteModule( 4309): 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
E/DynamiteModule( 4309): 	at com.google.android.gms.dynamite.a.a(SourceFile:212)
E/DynamiteModule( 4309): 	at com.google.android.gms.dynamite.a.a(SourceFile:169)
E/DynamiteModule( 4309): 	at com.google.android.gms.dynamite.a.a(SourceFile:122)
E/DynamiteModule( 4309): 	at com.google.android.gms.flags.a.a.a(SourceFile:58)
E/DynamiteModule( 4309): 	at com.google.android.gms.flags.h.a(SourceFile:16)
E/DynamiteModule( 4309): 	at com.google.android.gms.flags.GServicesChangedReceiver.onReceive(SourceFile:11)
E/DynamiteModule( 4309): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2663)
E/DynamiteModule( 4309): 	at android.app.ActivityThread.access$1700(ActivityThread.java:155)
E/DynamiteModule( 4309): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1400)
E/DynamiteModule( 4309): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/DynamiteModule( 4309): 	at android.os.Looper.loop(Looper.java:135)
E/DynamiteModule( 4309): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/DynamiteModule( 4309): 	at java.lang.reflect.Method.invoke(Native Method)
E/DynamiteModule( 4309): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/DynamiteModule( 4309): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/DynamiteModule( 4309): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/DynamiteModule( 4309): 	Suppressed: java.lang.ClassNotFoundException: com.google.android.gms.chimera.container.DynamiteLoaderImpl
E/DynamiteModule( 4309): 		at java.lang.Class.classForName(Native Method)
E/DynamiteModule( 4309): 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
E/DynamiteModule( 4309): 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
E/DynamiteModule( 4309): 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
E/DynamiteModule( 4309): 		... 17 more
E/DynamiteModule( 4309): 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
I/DynamiteModule( 4309): Considering local module com.google.android.gms.flags:1 and remote module com.google.android.gms.flags:0
I/DynamiteModule( 4309): Selected local version of com.google.android.gms.flags
,D/SystemEventReceiver( 4309): Received GSERVICES_CHANGED broadcast
,I/OcrUtils( 4309): Updating ocr activity enabled=false
,E/UEI.SmartControl( 5833): file observer is disposed!
,I/Icing   ( 4309): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/art     ( 4309): Explicit concurrent mark sweep GC freed 12125(744KB) AllocSpace objects, 7(112KB) LOS objects, 40% free, 14MB/24MB, paused 1.444ms total 92.328ms
,W/ActivityManager(  972): Unable to start service Intent { cmp=com.google.android.gms/.measurement.service.b } U=0: not found
,D/Icing   ( 4309): Loaded CLD2 Version V2.0 - 20141016
D/OcrModelManager( 4309): Updating downloaded model state (gservices changed)
,I/Icing   ( 4309): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/art     ( 5868): Explicit concurrent mark sweep GC freed 2588(102KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 1.098ms total 26.215ms
,I/NotificationManager(  972): android: cancelAsUser(-591465577) by android
,I/art     ( 1735): Explicit concurrent mark sweep GC freed 13235(956KB) AllocSpace objects, 21(336KB) LOS objects, 39% free, 13MB/22MB, paused 1.198ms total 68.182ms
,D/GCM     ( 1735): GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
,I/art     (  972): Explicit concurrent mark sweep GC freed 27485(1350KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.911ms total 153.896ms
,I/GCoreUlr( 1735): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,I/GCoreUlr( 1735): DispatchingService.onCreate()
D/UEI.SmartControl( 5833): Internal timer expired: 3
,I/ActivityManager(  972): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6230 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,W/GeofencerStateMachine( 1735): Ignoring removeGeofence because network location is disabled.
,E/ctxmgr  ( 1735): [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,I/GCoreUlr( 1735): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,W/ctxmgr  ( 1735): [AclManager]checkPermissionTypeStatus: no inject permission for { uid=10006, packageName=com.google.android.gms }. Returned permission was: PACKAGE_NOT_WHITELISTED for context name=POWER_CONNECTION, account=account#-517948760#
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
E/ctxmgr  ( 1735): [PowerConnectionProducer]Could not write powerInfo=Plug state: 2 BatteryLevel: 1.0, status=Status{statusCode=unknown status code: 7503, resolution=null}
I/art     ( 5868): Explicit concurrent mark sweep GC freed 2827(111KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.025ms total 33.063ms
,D/PhoneMonitor( 6230): Register our PhoneStateListener
,V/SetupWizard( 6230): Connected to Gservices successfully
,I/ActivityManager(  972): Killing 6058:com.android.gallery3d/u0a23 (adj 15): empty #11
I/GCoreUlr( 1735): WorldUpdater:com.google.gservices.intent.action.GSERVICES_CHANGED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
D/PhoneMonitor( 6230): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6230): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6230): [parse] Load xml
V/TelephonyAutoProfiling( 6230): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6230): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6230): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  972): failed to open /acct/uid_10023/pid_6058/cgroup.procs: No such file or directory
I/GCoreUlr( 1735): Unbound from all location providers
I/GCoreUlr( 1735): Place inference reporting - stopped
,I/GCoreUlr( 1735): DispatchingService.onDestroy()
I/GCoreUlr( 1735): Stopping handler for UlrDispSvcFast
I/ActivityManager(  972): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6263 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GCoreUlr( 1735): Unbound from all location providers
I/GCoreUlr( 1735): Place inference reporting - stopped
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6263): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6263): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6263): Error finding the version of the Email provider.....
E/Gmail   ( 6263): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6263): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6263): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6263): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6263): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6263): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6263): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6263): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6263): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6263): getAccountsCursor
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  972): Killing 6081:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10018/pid_6081/cgroup.procs: No such file or directory
,W/ActivityManager(  972): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 6263): Observing account changes for notifications
,W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/AudioManager( 5976): getMode name:com.lge.qremote
,I/ActivityManager(  972): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6315 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/Gmail   ( 6263): notifyAccountChanged
I/Gmail   ( 6263): getAccountsCursor
,I/Gmail   ( 6263): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6263): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6263): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6263): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/ResourcesManager( 6315): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6315): CalendarApplication.onCreate()
,I/Gmail   ( 6263): getAccountsCursor
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/PreferenceKeysParser( 6315): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6315): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@16c616d0, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@22b46c9, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@247491ce, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1d6308ef, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@7bdcffc, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3a188685, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@54bfcda, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@1301450b, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2c15efe8, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@29e00601, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@3bfd0ca6, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@12fd26e7, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@354e2294, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@1346013d, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3b5d4d32, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@1aeb4a83, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@b34d400, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@16167439, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1c0f0a7e, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@230e0bdf, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@213302c, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@28e11af5, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@c8d508a, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@3b7186fb, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@7992318, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@21757171, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@35f7eb56, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@1ec797d7, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@328958c4, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@91eb3ad, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@219f66e2, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1703da73, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@21253d30, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@389fdda9, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@2b510f2e, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@fb7aacf, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1258fc5c, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@37efab65, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@c62f03a, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@322e24eb, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@25a78248, lg_preferences_recen,t_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@1db498e1
D/GeneralPreferenceUtils( 6315): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6315): [init]
I/Config  ( 6315): LGCalendar ver.4.40.17
I/Config  ( 6315): start check model
I/Config  ( 6315): start check native_ca
I/Config  ( 6315): Config Operator=OPEN, Country=EU
D/Config  ( 6315): [setDefaultValuesToPref]
D/Config  ( 6315): [parseProfiles]
D/ProfilesParser( 6315): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6315): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6315): [updateProfiletoCountryInfo]
D/GeneralPreference( 6315): [checkAndMigrateOldPreference]
D/AlertReceiver( 6315): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/InitNotificationRingtoneService( 6315): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6315): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/AlertUtils( 6315): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6315): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6315): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6315): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6315): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6315): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6315): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6315): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6315): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6315): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/ActivityManager(  972): Killing 6103:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/HolidayIntentService( 6315): onHandleIntent
,D/HolidayDataLoader( 6315): readJsonAsset : holiday.json
D/AlertService( 6315): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/HolidayIntentService( 6315): onHandleIntent:holiday data empty
,W/libprocessgroup(  972): failed to open /acct/uid_10069/pid_6103/cgroup.procs: No such file or directory
E/AgendaWidgetManager( 6315): [updateWidgets] 
D/MonthWidgetProvider( 6315): [onReceive]
D/CalendarWidgetProvider( 6315): [onReceive]
D/CalendarWidgetProvider( 6315): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6315): [onCreate] mContext.getPackageName() = com.android.calendar
I/art     (  972): Explicit concurrent mark sweep GC freed 15569(830KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.374ms total 143.767ms
I/AlertUtils( 6315): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,D/WeekWidgetProvider( 6315): [onReceive]
D/CalendarWidgetProvider( 6315): [onReceive]
D/CalendarWidgetProvider( 6315): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
I/AlertUtils( 6315): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
D/CalendarTypeController( 6315): [onCreate] mContext.getPackageName() = com.android.calendar
I/AlertUtils( 6315): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6315): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AudioManager( 5976): getMode name:com.lge.qremote
,I/AlertUtils( 6315): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AudioManager( 5976): getMode name:com.lge.qremote
I/AlertUtils( 6315): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6315): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6315): set default noti to content://media/internal/audio/media/38
,I/InitNotificationRingtoneService( 6315): End InitializeAlertRingtoneService.onHandleIntent
I/ActivityManager(  972): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6347 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/NotificationManager( 6005): com.google.android.talk: cancel(8) by com.google.android.talk
,I/AppUp4:AppBoxCP( 6347): onCreate
W/AppUp4:DB( 6347):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6347):  setFingerPrint start
,I/AppUp4:DB( 6347):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6347):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6347):  SDK version = 0
I/AppUp4:DB( 6347):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 6347): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 6347): onReceive
I/AppUp4:CustModeStarterReceiver( 6347): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6347): Context : android.app.ReceiverRestrictedContext@22b46c9
,D/AppUp4:CustFacade( 6347): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6347): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6347): begin check event
I/AppUp4:CustModeStarterReceiver( 6347): Event For Nothing, skip.
I/ActivityManager(  972): Killing 5815:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10086/pid_5815/cgroup.procs: No such file or directory
,I/ActivityManager(  972): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6370 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,V/AlarmManager(  972): RTC_WAKEUP set : Alarm{1895b3c7 type 0 when 1457077196829 com.android.vending} when 1457077196829
D/Finsky  ( 5886): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ResourcesManager( 6370): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6370): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6370): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/NotificationManager(  972): android: cancelAsUser(2) by android
,I/AppConfig( 6370): Total System Memory = 906309632
,I/GalleryUtils( 6370): Application Heap = 96 MB
I/AppConfig( 6370): App Tier : NOT_DEF
D/SystemHelper( 6370): region [EU], country [EU], operator [OPEN], sub-operator []
D/libc-netbsd( 5886): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5886): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5886): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5886): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  271): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 5886): propertyValue:false
D/libc-netbsd( 5886): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5886): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  972): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6395 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,W/ResourcesManager( 6395): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6395): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6395): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6395): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6395): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/SystemConfig( 6395): BUILD Country: EU
I/SystemConfig( 6395): BUILD Operator: OPEN
,I/ActivityManager(  972): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6415 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  972): Killing 6135:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10009/pid_6135/cgroup.procs: No such file or directory
,I/SystemConfig( 6395): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6395): existFile = false
I/SystemConfig( 6395): canReadFile = false
I/SystemConfig( 6395): systemFeature RCS result false
D/SystemConfig( 6395): refreshRcsSupport() :false
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/libc-netbsd( 5886): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5886): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/LockScreenSettings( 6415): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6415): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6415): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6415): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6415): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6415): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  972): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6435 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  972): Killing 6171:com.google.android.configupdater/u0a3 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10003/pid_6171/cgroup.procs: No such file or directory
,W/ResourcesManager( 6435): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  972): android: cancelAsUser(2) by android
I/UpdateIcingCorporaServi( 1966): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 4309): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/qtaguid ( 5886): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5886): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5886): untagSocket(41) failed with errno -22
,I/UpdateIcingCorporaServi( 1966): UpdateCorporaTask done [took 59 ms] updated apps [took 59 ms] 
,I/ActivityManager(  972): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6461 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/Finsky  ( 5886): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
I/PackageBroadcastService( 4309): Null package name or gms related package.  Ignoreing.
I/Icing   ( 4309): updateResources: need to parse f{com.google.android.gms}
,W/ResourcesManager( 6461): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6461): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@521ff82
,I/ActivityManager(  972): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6491 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
D/CalendarProvider2( 6461): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6461): Created com.android.providers.calendar.CalendarAlarmManager@1d6308ef(com.android.providers.calendar.CalendarProvider2@521ff82)
I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 21.135ms
,D/CalendarProviderBroadcastReceiver( 6461): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6461): [IntentService] WakeLock acquire, start IntentSerivce
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AudioManager( 5976): getMode name:com.lge.qremote
,I/NotificationManager(  972): android: cancelAsUser(2) by android
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 311us total 21.452ms
D/CalendarProvider2( 6461): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6461): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6461): [getOrCreateCalendarAlarmManager]
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 93176640231; DSPS: 3151847; Offset : -3014889719
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 21.360ms
W/ResourcesManager( 6491): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6491): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/AudioManager( 5976): getMode name:com.lge.qremote
D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/MultiDex( 6491): VM with version 2.1.0 has multidex support
I/MultiDex( 6491): install
,I/MultiDex( 6491): VM has multidex support, MultiDex support library is disabled.
D/CalendarProvider2( 6461): [IntentService] Release Lock
D/CalendarProvider2( 6461): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  972): Killing 6263:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10053/pid_6263/cgroup.procs: No such file or directory
,V/JNIHelp ( 6491): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  972): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6516 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/ActivityThread( 6491): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6491): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1bce8319: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6491): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6491): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 6491): com.google.android.gms: cancel(39789) by com.google.android.gms
D/ChimeraCfgMgr( 6491): Reading stored module config
,D/ChimeraCfgMgr( 6491): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/qtaguid ( 5886): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5886): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5886): untagSocket(41) failed with errno -22
D/CAR.SERVICE( 6491): Connecting to CarCallService...
W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/art     ( 6491): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6491): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/NativeLibraryUtils( 6491): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6491): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6491): Creating a new CarCallService.
,I/Gmail   ( 6516): getAccountsCursor
D/CAR.TEL.PhoneAdapter( 6491): Creating a new PhoneAdapter instance
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  972): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6491): setListener: com.google.android.gms.car.dn@2341d8bc
W/ActivityManager(  972): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6491): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6491): Starting CarCallService with initial phone null
W/GAV2    ( 6516): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/NotificationManager( 6491): com.google.android.gms: cancel(10436) by com.google.android.gms
I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6516): Error finding the version of the Email provider.....
E/Gmail   ( 6516): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6516): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6516): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6516): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6516): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6516): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6516): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6516): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6516): We do not support migrating this version of the Email provider.
,D/CAR.SERVICE( 6491): Package validated; name: com.android.vending
W/ActivityManager(  972): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 6516): getAccountsCursor
,I/Gmail   ( 6516): Observing account changes for notifications
I/art     ( 5886): CheckpointMarkThreadRoots callback created = 0xb05804c0
,I/art     ( 5886): CheckpointMarkThreadRoots callback created = 0xb0580480
,I/art     (  972): Explicit concurrent mark sweep GC freed 12966(615KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 1.945ms total 141.875ms
,W/ActivityManager(  972): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AudioManager( 5976): getMode name:com.lge.qremote
I/AudioManager( 5976): getMode name:com.lge.qremote
,I/NotificationManager( 5886): com.android.vending: cancel(10436) by com.android.vending
I/AudioManager( 5976): getMode name:com.lge.qremote
V/Finsky  ( 5886): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/AudioManager( 5976): getMode name:com.lge.qremote
,I/ActivityManager(  972): Killing 6347:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10011/pid_6347/cgroup.procs: No such file or directory
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/WearableService( 1735): callingUid 10006, callindPid: 1735
,E/MDM     ( 1735): [84] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4309): Restart initialization of location
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1735): No location to return for getLastLocation()
,W/FusedLocationProvider( 1735): location=null
I/Gmail   ( 6516): notifyAccountChanged
,I/Gmail   ( 6516): getAccountsCursor
I/Gmail   ( 6516): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6516): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6516): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6516): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Icing   ( 4309): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/art     ( 1735): Explicit concurrent mark sweep GC freed 29766(1759KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 13MB/23MB, paused 1.430ms total 75.002ms
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 4309): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/Gmail   ( 6516): getAccountsCursor
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  972): android: cancelAsUser(2) by android
,I/qtaguid ( 5886): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5886): Untagging socket 41 failed errno=-22
,W/NetworkManagementSocketTagger( 5886): untagSocket(41) failed with errno -22
W/ResourcesManager( 5886): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5886): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5886): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5886): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  972): RTC_WAKEUP set : Alarm{31d7657b type 0 when 1457077199795 com.android.vending} when 1457077199795
D/DeviceConnectionService( 1735): client connected with version: 8296000
,D/Finsky  ( 5886): [709] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 5886): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/NotificationManager(  972): android: cancelAsUser(2) by android
D/Finsky  ( 5886): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/libc-netbsd( 5886): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5886): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5886): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5886): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  271): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/PowerManagerServiceEx(  972): acquireWakeLockInternal: lock=650098705, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=972
,D/WeatherService( 2675): 2 : TimeTick Intent has been received, Time(hour:min:sec) 8:40:0
D/WeatherService( 2675): 2 : TimeTick Intent And Screen On
,D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 5886): propertyValue:false
,D/WeatherService( 2675): 2 : SDK version : 21
W/ActivityManager(  972): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2675): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2675): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2675): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2675): 2 : requestRefreshAppWidget, isUpdateStart : false
,D/UpdateThreadPoolManager( 2675): 2 : This is isUpdating : false
D/WeatherService( 2675): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2675): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2675): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2675): 2 : Fixed theme : optimus
D/WeatherReflect( 2675): 2 : Map key string is -2
,D/lim     ( 2675): 2 : time = 08:40
I/WeatherReflect( 2675): Model Name : LG-D722
D/WeatherTheme( 2675): 2 : Different view - status_min_formatted : 39 != 40
D/WeatherTheme( 2675): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2675): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
,D/Theme   ( 2675): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2675): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2675): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2675): currentPackage=com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2675): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2675): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2675): forecast size is 0
D/Theme   ( 2675): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2675): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2675): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2675): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2675): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2675): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2675): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2675): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2675): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2675): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2675): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2675): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2675): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2675): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2675): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2675): url is : null
,D/Theme   ( 2675): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2675): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2675): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2675): 2 : update view, appWidgetId: 2
D/WeatherService( 2675): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 8:40:0
D/PowerManagerServiceEx(  972): releaseWakeLockInternal: lock=650098705 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1880): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ActivityManager(  972): Killing 6395:com.android.contacts/u0a18 (adj 15): empty #11
,I/ActivityManager(  972): Killing 6370:com.android.gallery3d/u0a23 (adj 15): empty #12
,W/libprocessgroup(  972): failed to open /acct/uid_10018/pid_6395/cgroup.procs: No such file or directory
,W/libprocessgroup(  972): failed to open /acct/uid_10023/pid_6370/cgroup.procs: No such file or directory
I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
,I/[SystemUI]Clock( 1375): called onTimeUpdated()
I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
,I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/AlertService( 6315): Beginning updateAlertNotification
,D/AlertService( 6315): No fired or scheduled alerts
,I/NotificationManager( 6315): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6315): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6315): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6315): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6315): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6315): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6315): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6315): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6315): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6315): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6315): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6315): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6315): com.android.calendar: cancel(12) by com.android.calendar
,I/NotificationManager( 6315): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6315): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6315): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6315): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6315): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6315): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6315): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6315): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6315): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 6315): No events found starting within 1 week.
,I/ActivityManager(  972): Killing 6315:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10013/pid_6315/cgroup.procs: No such file or directory
,I/ActivityManager(  972): Killing 6005:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10061/pid_6005/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,W/PackageSettings(  972): Skipping PackageSetting{25af8029 com.example.hello/10317} due to missing metadata
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/GAV2    ( 6516): Thread[GAThread,5,main]: No campaign data found.
,D/CAR.SERVICE( 6491): mConnectedToCar = false, abort
,E/ActivityThread( 6491): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@35888924 that was originally bound here
E/ActivityThread( 6491): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@35888924 that was originally bound here
E/ActivityThread( 6491): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6491): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6491): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6491): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6491): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6491): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6491): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6491): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6491): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6491): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6491): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6491): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6491): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6491): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6491): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6491): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6491): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6491): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6491): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6491): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6491): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6491): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6491): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6491): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3f42bcaf that was originally bound here
E/ActivityThread( 6491): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3f42bcaf that was originally bound here
E/ActivityThread( 6491): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6491): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6491): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6491): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6491): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6491): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6491): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6491): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6491): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6491): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6491): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6491): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6491): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6491): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6491): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6491): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6491): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6491): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6491): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6491): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6491): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6491): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  972): Unbind failed: could not find connection for android.os.BinderProxy@36c565e5
I/ActivityManager(  972): Killing 6415:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,W/libprocessgroup(  972): failed to open /acct/uid_10069/pid_6415/cgroup.procs: No such file or directory
,I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-58 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.114 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-03-04 08:40:04.114 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-55 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.114 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-03-04 08:40:07.145 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/rmt_storage(  267): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  267): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  267): wakelock acquired: 1, error no: 42
,I/rmt_storage(  267): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  267): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  267): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  267): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  267): 
I/rmt_storage(  267): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  290): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  972): RTC_WAKEUP set : Alarm{2b3658ba type 0 when 1457077212001 com.google.android.gms} when 1457077212001
,V/AlarmManager(  972): RTC_WAKEUP set : Alarm{183a5ec8 type 0 when 1457077214122 com.android.vending} when 1457077214122
I/CheckinService( 4309): Checkin interval check for package: unspecified last checkin: 1457077182040 min interval config: 0 actual interval: 32137
,W/ContextImpl( 3662): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/CheckinService( 4309): Checking schedule, now: 1457077214230 next: 1457077212001
I/CheckinService( 4309): active receiver: enabled
,I/CheckinService( 4309): Preparing to send checkin request
I/EventLogService( 4309): Accumulating logs since 1457077175818
,I/CheckinRequestBuilder( 4309): Checkin reason type: 3 attempt count: 1
,E/ActivityThread( 4309): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5886): [700] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5886): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/ActivityManager(  972): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6636 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 6636): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6636): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6636): VM with version 2.1.0 has multidex support
I/MultiDex( 6636): install
I/MultiDex( 6636): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6636): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6636): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6636): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1bce8319: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6636): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6636): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6636): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1735): callingUid 10006, callindPid: 1735
,E/MDM     ( 1735): [102] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1735): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 4309): Restart initialization of location
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1735): com.google.android.gms: cancel(0) by com.google.android.gms,
W/GCoreFlp( 1735): No location to return for getLastLocation()
W/FusedLocationProvider( 1735): location=null
,I/art     ( 6636): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6636): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6636): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  279): Instantiating CDM.
I/WVCdm   (  279): CdmEngine::OpenSession
,I/WVCdm   (  279): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  279): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  279): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  279): L1 library not specified. Falling Back to L3
I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/WVCdm   (  279): PrepareKeyRequest: nonce=2797487092
I/art     ( 6636): CheckpointMarkThreadRoots callback created = 0xb042d5e0
,I/art     ( 6636): CheckpointMarkThreadRoots callback created = 0xb042d5d0
,I/dex2oat ( 6684): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6684): dex2oat took 126.193ms (threads: 4)
,I/Adreno-EGL( 6636): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6636): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6636): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6636): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6636): Remote Branch: 
I/Adreno-EGL( 6636): Local Patches: 
I/Adreno-EGL( 6636): Reconstruct Branch: 
,I/Adreno-EGL( 6636): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6636): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6636): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6636): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6636): Remote Branch: 
I/Adreno-EGL( 6636): Local Patches: 
I/Adreno-EGL( 6636): Reconstruct Branch: 
,I/Adreno-EGL( 6636): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6636): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6636): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6636): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6636): Remote Branch: 
I/Adreno-EGL( 6636): Local Patches: 
I/Adreno-EGL( 6636): Reconstruct Branch: 
,I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.114 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-03-04 08:40:16.202 DNS addrs= 192.168.1.1, 0.0.0.0, 
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/CheckinRequestBuilder( 4309): Classify the device as Phone.
,D/libc-netbsd( 4309): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4309): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4309): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4309): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 4309): propertyValue:false
D/libc-netbsd( 4309): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4309): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4309): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4309): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4309): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4309): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4309): Sending checkin request (7786 bytes)
,I/CheckinRequestBuilder( 4309): Checkin reason type: 3 attempt count: 1
,E/ActivityThread( 4309): Failed to find provider info for com.google.android.wearable.settings
I/WVCdm   (  279): CdmEngine::CloseSession
I/WVCdm   (  279): L3 Terminate.
,I/CheckinRequestBuilder( 4309): Classify the device as Phone.
,I/CheckinTask( 4309): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4309): Checking schedule, now: 1457077217350 next: 1457604466346
I/CheckinService( 4309): active receiver: disabled
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/CheckinService( 4309): Recording last checkin time for package unspecified as 1457077217386
,D/GCM     ( 1735): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 113177417678; DSPS: 3807233; Offset : -3014906328
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/MusicWidget( 2624): mDelayedStopHandler : unbind
,I/MusicBrowser( 2692): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2692): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2692): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2692): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2692): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2692): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2692): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2692): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  972):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@28e11af5com.lge.music.MediaPlaybackService$6@c8d508a
,D/MusicBrowser( 2692): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2692): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2692): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2692): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2692): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@2c15efe8
I/MusicBrowser( 2692): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2692): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2692): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2692): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2692): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2692): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2692): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2692): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2692): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2692): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2692): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
I/MusicBrowser( 2692): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2692): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2692): reset
,V/MediaPlayer[Native]( 2692): setListener
,V/MediaPlayer[Native]( 2692): disconnect
V/MediaPlayer[Native]( 2692): destructor
V/AudioFlinger(  279): releasing 19 from 2692 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/MediaPlayer[Native]( 2692): disconnect
D/MusicBrowser( 2692): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2692): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2692): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2692): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2692): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
,V/MusicBrowser( 2692): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2692): [SmartShareManagerClient] unregisterListener: 997295867
W/SmartShareClient( 2692): [SmartShareManagerClient] unregisterListener invalid listener: 997295867
I/SmartShareClient( 2692): [SmartShareManagerClient] terminate service: 2692/MediaPlaybackService/611619278
E/HomeCloudIF( 2692): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2692): [SmartShareManagerClient] unbindService context:android.app.Application@7992318
V/CloudHub( 2692): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2692): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2692): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2692): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2692): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/CloudHub( 2692): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29992
W/ProcessCpuTracker(  972): Skipping unknown process pid 6710
,W/ProcessCpuTracker(  972): Skipping unknown process pid 6713
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-54 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.114 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-03-04 08:40:19.228 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/ActivityManager(  972): Killing 6461:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/ActivityManager(  972): Killing 6435:com.google.android.apps.plus/u0a86 (adj 15): empty #12
,W/libprocessgroup(  972): failed to open /acct/uid_10014/pid_6461/cgroup.procs: No such file or directory
,W/libprocessgroup(  972): failed to open /acct/uid_10086/pid_6435/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/[SystemUI]QPairHandler( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1842): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/InputReader(  972): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1880): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/ActivityManager(  972): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6717 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/administrator(  972): Handling package changes for user 0
,I/[SystemUI]QSlideListController( 1375): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]Launcher( 1880): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1375): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1375): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,W/ResourcesManager( 6717): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationService(  972): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  972): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  972): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  972): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/ResourcesManager(  972): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/BackupManagerService(  972): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  972): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@234512da
,W/ResourceType(  972): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1880): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1735): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  972): applying state to connected service
,I/art     (  972): Explicit concurrent mark sweep GC freed 37185(2034KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/35MB, paused 2.337ms total 177.749ms
,I/Babel_SMS( 6717): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6717): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6717): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6717): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6717): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6717): MmsConfig.loadFromResources
E/Babel_SMS( 6717): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6717): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6717): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6717): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6717): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6717): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6717): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6717): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6717): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6717): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6717): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6717): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6717): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6717): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6717): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6717): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6717): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6717): found sensor: Motion Accel, handle=46
,W/Settings( 6717): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     ( 6717): CheckpointMarkThreadRoots callback created = 0xb042d4d0
,I/Babel_Crash( 6717): startup - clean
,I/art     ( 6717): CheckpointMarkThreadRoots callback created = 0xb042d4b0
,I/Babel   ( 6717): deleted: false for 0
,W/AudioCapabilities( 6717): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6717): Unsupported mime audio/adpcm
I/ActivityManager(  972): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6761 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/LCardEmulationManager( 1789): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1789): getDefaultRoute
W/AudioCapabilities( 6717): Unsupported mime audio/g726
,W/AudioCapabilities( 6717): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6717): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6717): Unsupported mime video/mjpg
W/VideoCapabilities( 6717): Unsupported mime video/theora
W/AudioCapabilities( 6717): Unsupported mime audio/evrc
,W/AudioCapabilities( 6717): Unsupported mime audio/qcelp
W/VideoCapabilities( 6717): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6717): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6717): Unsupported mime audio/qcelp
W/AudioCapabilities( 6717): Unsupported mime audio/evrc
W/VideoCapabilities( 6717): Unsupported mime video/mp4v-esdp
,I/AppUp4:AppBoxCP( 6761): onCreate
,W/AppUp4:DB( 6761):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6761):  setFingerPrint start
I/AppUp4:DB( 6761):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6761):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6761):  SDK version = 0
I/AppUp4:DB( 6761):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6761): AppBoxApplication onCreate()
,I/AppUp4:CustModeStarterReceiver( 6761): onReceive
I/AppUp4:CustModeStarterReceiver( 6761): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6761): Context : android.app.ReceiverRestrictedContext@22b46c9
D/AppUp4:CustFacade( 6761): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6761): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6761): begin check event
I/AppUp4:CustModeStarterReceiver( 6761): Event For Nothing, skip.
I/ActivityManager(  972): Killing 5833:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/VideoCapabilities( 6717): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 6717): Unrecognized profile 2130706433 for video/avc
W/System.err( 5976): android.os.DeadObjectException
W/VideoCapabilities( 6717): Unrecognized profile 2130706433 for video/avc
,W/System.err( 5976): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5976): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5976): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5976): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5976): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5976): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5976): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5976): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5976): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5976): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5976): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5976): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5976): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5976): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5976): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5976): android.os.DeadObjectException
W/System.err( 5976): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5976): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5976): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5976): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5976): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5976): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5976): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5976): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5976): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5976): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5976): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5976): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5976): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5976): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5976): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/VideoCapabilities( 6717): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6717): Unrecognized profile 2130706433 for video/avc
W/libprocessgroup(  972): failed to open /acct/uid_10089/pid_5833/cgroup.procs: No such file or directory
W/ActivityManager(  972): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  972): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6785 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  972): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6802 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/vclib   ( 6717): onServiceConnected
W/Babel   ( 6717): Attempted to change video mute state without an active call.
I/NotificationManager( 6717): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6717): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6717): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6785): Quickset Services start...
I/UEI.SmartControl( 6785): Manufacture = LGE
,D/UEI.SmartControl( 6785): File observer start...
E/UEI.SmartControl( 6785): IR Port is disabled: false
D/UEI.SmartControl( 6785): Starting file observer...
D/UEI.SmartControl( 6785): Extracting JNI libs...
D/UEI.SmartControl( 6785): --- this system supports 32-bit or 64-bit only
W/ResourcesManager( 6802): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6802): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6802): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
V/JNIHelp ( 6717): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/UEI.SmartControl( 6785): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6785): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6785): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6785): --- Selecting new region: 2
,I/UEI.SmartControl( 6785): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6785): Platform has CIR...
D/UEI.SmartControl( 6785): NO CIR support, need to check package...
I/UEI.SmartControl( 6785): Model: LG-D722 uses JNI
I/AppConfig( 6802): Total System Memory = 906309632
D/UEI.SmartControl( 6785): QS Service created
I/GalleryUtils( 6802): Application Heap = 96 MB
W/System  ( 6717): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6717): Installed default security provider GmsCore_OpenSSL
I/AppConfig( 6802): App Tier : NOT_DEF
D/SystemHelper( 6802): region [EU], country [EU], operator [OPEN], sub-operator []
,I/NotificationManager( 6717): com.google.android.talk: cancel(10436) by com.google.android.talk
E/UEI.SmartControl( 6785): QS start get config
D/UEI.SmartControl( 6785): Loading JNI Libs...
D/UEI.SmartControl( 6785):  configuring local db...
I/ActivityManager(  972): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6826 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  972): Killing 5976:com.lge.qremote/u0a106 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10106/pid_5976/cgroup.procs: No such file or directory
,W/ResourcesManager( 6826): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6826): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6826): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6826): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6826): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6785):  ---- Has DB8: true
,D/UEI.SmartControl( 6785): QS start statue = true Error code = 0
D/UEI.SmartControl( 6785): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6785): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
I/SystemConfig( 6826): BUILD Country: EU
,I/SystemConfig( 6826): BUILD Operator: OPEN
D/UEI.SmartControl( 6785): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6785): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6785): IrrcClient ++ 
D/irrcClient( 6785): getIrrcService ++ 
D/irrcClient( 6785): getIrrcService -- 
D/irrcClient( 6785): IrrcClient -- 
W/irrc_jni( 6785): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6785): Services init done
I/UEI.SmartControl( 6785): Device manager: loading config....
,D/UEI.SmartControl( 6785): Config is loaded...
D/UEI.SmartControl( 6785): QS Service init finished
D/UEI.SmartControl( 6785): QS Service version name: 0.1.73
D/UEI.SmartControl( 6785): QS Service version code: 1073
D/UEI.SmartControl( 6785): Service requested: Control
D/UEI.SmartControl( 6785): Service.onUnbind: IControl
D/UEI.SmartControl( 6785): Service.onDestroy
D/UEI.SmartControl( 6785): Shutdown IRRCPlayer... 
W/irrc_jni( 6785): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6785): ~IrrcClient ++ 
D/irrcClient( 6785): ~IrrcClient -- 
W/irrc_jni( 6785): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6785): Blaster closed
D/UEI.SmartControl( 6785): Blaster closed
D/UEI.SmartControl( 6785): Shut down QS...
D/UEI.SmartControl( 6785): Stopped file observer...
I/UEI.SmartControl( 6785): QS lib stop result = true
D/UEI.SmartControl( 6785): QS shutdown complete
D/UEI.SmartControl( 6785): QS Service created
,E/UEI.SmartControl( 6785): QS start get config
,I/UEI.SmartControl( 6785): Notify AllClients services are ready: 11
D/UEI.SmartControl( 6785):  configuring local db...
,I/ActivityManager(  972): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6852 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  972): Killing 6516:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10053/pid_6516/cgroup.procs: No such file or directory
,I/SystemConfig( 6826): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6826): existFile = false
I/SystemConfig( 6826): canReadFile = false
I/SystemConfig( 6826): systemFeature RCS result false
D/SystemConfig( 6826): refreshRcsSupport() :false
I/LockScreenSettings( 6852): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6852): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6852): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6852): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6852): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6852): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  972): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6869 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  972): Killing 6491:com.google.android.gms:car/u0a6 (adj 15): empty #11
,D/UEI.SmartControl( 6785):  ---- Has DB8: true
,D/UEI.SmartControl( 6785): QS start statue = true Error code = 0
D/UEI.SmartControl( 6785): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6785): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6785): IRRCDataComm has AudioManager!!!!.
W/libprocessgroup(  972): failed to open /acct/uid_10006/pid_6491/cgroup.procs: No such file or directory
W/irrc_jni( 6785): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6785): IrrcClient ++ 
D/irrcClient( 6785): getIrrcService ++ 
D/irrcClient( 6785): getIrrcService -- 
D/irrcClient( 6785): IrrcClient -- 
W/irrc_jni( 6785): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6785): Services init done
D/UEI.SmartControl( 6785): QS Service init finished
D/UEI.SmartControl( 6785): QS Service version name: 0.1.73
D/UEI.SmartControl( 6785): QS Service version code: 1073
D/UEI.SmartControl( 6785): Service requested: Control
I/UEI.SmartControl( 6785): Device manager: loading config....
I/ActivityManager(  972): Killing 5886:com.android.vending/u0a36 (adj 15): empty #11
,D/UEI.SmartControl( 6785): Config is loaded...
W/ResourcesManager( 6869): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6785):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6785): Notify AllClients services are ready: 0
,W/libprocessgroup(  972): failed to open /acct/uid_10036/pid_5886/cgroup.procs: No such file or directory
E/ActivityThread( 6785): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@1301450b that was originally bound here
E/ActivityThread( 6785): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@1301450b that was originally bound here
E/ActivityThread( 6785): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6785): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6785): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6785): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6785): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6785): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6785): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6785): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6785): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6785): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6785): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6785): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6785): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6785): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6785): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6785): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6785): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6785): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6785): Internal service binding...
I/UpdateIcingCorporaServi( 1966): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  972): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6897 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/UpdateIcingCorporaServi( 1966): UpdateCorporaTask done [took 36 ms] updated apps [took 36 ms] 
,I/ActivityManager(  972): Killing 6636:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10006/pid_6636/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/Finsky  ( 6897): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6897): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6897): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6897): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 6897): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3228): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3228): created cursor android.database.sqlite.SQLiteCursor@1b184663 on behalf of 6897
D/Finsky  ( 6897): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6897): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Ads     ( 6897): Skipping gmscore version check
D/Finsky  ( 6897): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/PackageBroadcastService( 4309): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4309): Null package name or gms related package.  Ignoreing.
D/UEI.SmartControl( 6785): Internal timer expired: 2
W/System.err( 6785): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1301450b
W/System.err( 6785): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 6785): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 6785): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 6785): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 6785): 	at com.uei.control.Service.a(Unknown Source)
W/System.err( 6785): 	at com.uei.control.l.run(Unknown Source)
W/System.err( 6785): 	at java.util.Timer$TimerImpl.run(Timer.java:284)
E/UEI.SmartControl( 6785): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@1301450b
,I/Icing   ( 4309): updateResources: need to parse f{com.google.android.gms}
,D/Finsky  ( 6897): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/Icing   ( 4309): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4309): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  972): Killing 6230:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  972): failed to open /acct/uid_10038/pid_6230/cgroup.procs: No such file or directory
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/CloudHub( 2692): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19952
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,E/UEI.SmartControl( 6785): file observer is disposed!
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ActivityManager(  972): Killing 2692:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  279): 2692 died, releasing its sessions
V/AudioFlinger(  279):  pid 1753 @ 0
V/AudioFlinger(  279):  pid 3178 @ 1
V/AudioFlinger(  279):  pid 3178 @ 2
,W/libprocessgroup(  972): failed to open /acct/uid_10028/pid_2692/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6785): Internal timer expired: 3
,D/UEI.SmartControl( 6785): Service.onUnbind: IControl
D/UEI.SmartControl( 6785): Service.onDestroy
W/System.err( 6785): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@354e2294
W/System.err( 6785): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 6785): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 6785): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 6785): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 6785): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 6785): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 6785): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 6785): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 6785): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6785): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6785): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6785): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6785): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6785): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6785): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6785): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@354e2294
D/UEI.SmartControl( 6785): Shutdown IRRCPlayer... 
W/irrc_jni( 6785): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6785): ~IrrcClient ++ 
D/irrcClient( 6785): ~IrrcClient -- 
W/irrc_jni( 6785): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6785): Blaster closed
D/UEI.SmartControl( 6785): Blaster closed
D/UEI.SmartControl( 6785): Shut down QS...
I/UEI.SmartControl( 6785): QS lib stop result = true
D/UEI.SmartControl( 6785): QS shutdown complete
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  972): battery changed pluggedType: 2
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.114 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-03-04 08:40:37.318 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 133178911909; DSPS: 4462641; Offset : -3014878894
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-53 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.114 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-03-04 08:40:40.348 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{372804bb type 2 when 139653 com.google.android.gms} when 139653
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/VacuumService( 1735): Vacuum at: now=1457077244682 tag=VacuumService
V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  972): ALS enabled for SRE
D/PowerManagerServiceEx(  972): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26637 ms ago)
,D/qdlights(  972): set_light_backlight: 254
,D/qdlights(  972): set_light_backlight: 250
,D/qdlights(  972): set_light_backlight: 247
,D/qdlights(  972): set_light_backlight: 244
,D/qdlights(  972): set_light_backlight: 240
,D/qdlights(  972): set_light_backlight: 237
,D/qdlights(  972): set_light_backlight: 234
,D/qdlights(  972): set_light_backlight: 230
,D/qdlights(  972): set_light_backlight: 227
,D/qdlights(  972): set_light_backlight: 224
,D/qdlights(  972): set_light_backlight: 220
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/qdlights(  972): set_light_backlight: 217
,D/qdlights(  972): set_light_backlight: 214
,D/qdlights(  972): set_light_backlight: 210
,D/qdlights(  972): set_light_backlight: 207
,D/qdlights(  972): set_light_backlight: 204
,D/qdlights(  972): set_light_backlight: 200
,D/qdlights(  972): set_light_backlight: 197
,D/qdlights(  972): set_light_backlight: 194
,D/qdlights(  972): set_light_backlight: 190
,D/qdlights(  972): set_light_backlight: 187
,D/qdlights(  972): set_light_backlight: 184
,D/qdlights(  972): set_light_backlight: 180
,D/qdlights(  972): set_light_backlight: 177
,D/qdlights(  972): set_light_backlight: 174
,D/qdlights(  972): set_light_backlight: 170
,D/qdlights(  972): set_light_backlight: 167
,D/qdlights(  972): set_light_backlight: 164
,D/qdlights(  972): set_light_backlight: 160
,D/qdlights(  972): set_light_backlight: 157
,D/qdlights(  972): set_light_backlight: 154
,D/qdlights(  972): set_light_backlight: 150
,D/qdlights(  972): set_light_backlight: 147
,D/qdlights(  972): set_light_backlight: 144
,D/qdlights(  972): set_light_backlight: 140
,D/qdlights(  972): set_light_backlight: 137
,D/qdlights(  972): set_light_backlight: 134
,D/qdlights(  972): set_light_backlight: 130
,D/qdlights(  972): set_light_backlight: 127
,D/qdlights(  972): set_light_backlight: 124
,D/qdlights(  972): set_light_backlight: 120
,D/qdlights(  972): set_light_backlight: 117
,D/qdlights(  972): set_light_backlight: 114
,D/qdlights(  972): set_light_backlight: 110
,D/qdlights(  972): set_light_backlight: 107
,D/qdlights(  972): set_light_backlight: 104
,D/qdlights(  972): set_light_backlight: 100
,D/qdlights(  972): set_light_backlight: 97
,D/qdlights(  972): set_light_backlight: 94
,D/qdlights(  972): set_light_backlight: 90
,D/qdlights(  972): set_light_backlight: 87
,D/qdlights(  972): set_light_backlight: 84
,D/qdlights(  972): set_light_backlight: 80
,D/qdlights(  972): set_light_backlight: 77
,D/qdlights(  972): set_light_backlight: 74
,D/qdlights(  972): set_light_backlight: 70
,D/qdlights(  972): set_light_backlight: 67
,D/qdlights(  972): set_light_backlight: 64
,D/qdlights(  972): set_light_backlight: 60
,D/qdlights(  972): set_light_backlight: 57
,D/qdlights(  972): set_light_backlight: 53
,D/qdlights(  972): set_light_backlight: 50
,D/qdlights(  972): set_light_backlight: 47
,D/qdlights(  972): set_light_backlight: 43
,D/qdlights(  972): set_light_backlight: 40
,D/qdlights(  972): set_light_backlight: 37
,D/qdlights(  972): set_light_backlight: 33
,D/qdlights(  972): set_light_backlight: 30
,D/qdlights(  972): set_light_backlight: 27
,D/qdlights(  972): set_light_backlight: 23
,D/qdlights(  972): set_light_backlight: 20
,D/qdlights(  972): set_light_backlight: 17
,D/qdlights(  972): set_light_backlight: 13
,D/qdlights(  972): set_light_backlight: 10
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/QCNEJ   ( 1842): |CORE| CNE received action RSSI/Link Changed events: android.net.wifi.RSSI_CHANGED
,I/QCNEJ   ( 1842): |CORE| sendWifiStatus - subType: 21 networkState: 1 softApState: 11 rssi=-56 ssid=NG700 bssid=f4:f2:6d:22:99:3e ipV4Addr=192.168.1.114 ifNameV4=wlan0 ipAddrV6= ifNameV6= timeStamp:2016-03-04 08:40:55.442 DNS addrs= 192.168.1.1, 0.0.0.0, 
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 153180884296; DSPS: 5118066; Offset : -3014887962
,I/PowerManagerService(  972): ALS enabled for SRE
D/PowerManagerServiceEx(  972): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33633 ms ago)
,I/PowerManagerService(  972): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  972): ALS enabled for SRE
,D/PowerManagerServiceEx(  972): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33665 ms ago)
W/ContextImpl(  972): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  972): Sleeping (uid 1000)...
D/LPWGController(  972): [updateScreenState] screen on = false
D/LPWGController(  972): disable proximity sensor
,D/LPWGController(  972): enable proximity sensor
I/SensorManager(  972): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2847dff0] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  972): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  972): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  972): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  972): activate: handle is 48, enable
,V/sensors_hal_Ctx(  972): activate sensors is 1400000000000
D/sensors_hal_Thresh(  972): enable: handle=48
I/sensors_hal_SAM(  972): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  972): waitForResponse: timeout=1000
V/sensors_hal_SAM(  972): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  972): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  972): enable: Received response: 0
D/PowerManagerServiceEx(  972): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33721 ms ago)
I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/Adreno-EGL(  972): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  972): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  972): Build Date: 03/02/15 Mon
I/Adreno-EGL(  972): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  972): Remote Branch: 
I/Adreno-EGL(  972): Local Patches: 
I/Adreno-EGL(  972): Reconstruct Branch: 
D/PermissionCache(  247): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (146 us)
,I/Sensors (  421): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  972): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  972): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  972): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  972): processInd: handle 48, count=1
V/sensors_hal_Thresh(  972): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  972): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  972): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  972): poll: count: 256
I/sensors_hal_Ctx(  972): poll: released wakelock sensor_ind
D/sensors_hal_Util(  972): waitForResponse: timeout=0
D/LPWGController(  972): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  972): current mode = 1  value = 1 1
I/LPWGController(  972): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
,I/LPWGController(  972): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  972): set_light_backlight: 0
,I/SensorManager(  972): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  972): activate: handle is 46, disable
V/sensors_hal_Ctx(  972): activate sensors is 1000000000000
D/sensors_hal_LP2(  972): enable: handle=46
D/sensors_hal_LP2(  972): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  972): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,D/SurfaceFlinger(  247): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  247): hwc_blank: Blanking display: 0
I/DisplayManagerService(  972): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  972): Display changed displayId=0
V/sensors_hal_SAM(  972): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  972): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1753): Display #0 changed.
,D/qdhwcomposer(  247): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  972): Excessive delay in setPowerMode(): 234ms
I/qdhwcomposer(  247): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  972): Got set_interactive hint
,D/KeyguardViewMediator( 1375): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1332): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1332): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): handleNotifyScreenOFF
D/KeyguardViewMediator( 1375): notifyScreenOffLocked
D/JX-Cordova( 4921): jxcore cordova android initializing
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4921): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4921): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d334c92 added. We now have 3 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4921): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4921): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b184663 added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4921): addListener: New listener added - the number of listeners is now 1
,D/BluetoothAdapterService(318850315)( 2050): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@16167439
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4921): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4921): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4921): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 4921): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4921): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4921): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4921): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4921): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4921): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4921): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
,W/System.err( 4921): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4921): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4921): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4921): 	at android.os.Looper.loop(Looper.java:135)
,W/System.err( 4921): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/KeyguardViewMediator( 1375): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1375): handleNotifyScreenOff
D/ScreenTurnOffBySensor( 1375): unregisterProximitySensor
,D/StatusBarWindowView( 1375): onScreenTurnedOff why = 3
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/WifiServerServiceExt(  972): sendKtScanInterval  mRtspPlay : false
V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=on, calling pid 972
D/audio_hw_primary(  279): adev_set_parameters: enter: screen_state=on
V/voice   (  279): voice_set_parameters: enter: screen_state=on
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
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
,I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.SCREEN_ON
I/WifiServerServiceExt(  972): set CMD_KT_SCAN_INTERVAL
D/PowerManagerServiceEx(  972): acquireWakeLockInternal: lock=650098705, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=972
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/Sensors (  421): sns_pwr.c(301):releasing wakelock
,I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1375): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_3_fully mWifiActivityIconId=(null)
,D/GpsLocationProvider(  972): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1842): |CORE| sendScreenState: state:true
I/LEDService( 1806): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1806): stopPatternFlashing()
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): updateLightsLocked : turn off led
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1806): RESTART MSG
,D/SplitWindow(  972): check instance of lgWin Window{279bc8f u0 SearchPanel}
,I/Cliptray Service( 1806): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/Cliptray Service( 1806): lockStatus = 0
D/InputDispatcher(  972): Window went away: Window{2947cf3c u0 SearchPanel}
,I/[SystemUI]Clock( 1375): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1375): time changed, timezoneChanged : false
,D/LNfcService( 1789): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1789): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1789): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1789): isRequireNfcCRouting() return true
D/LNfcService( 1789): isHCERoutingtoHost() return : true
D/NfcService( 1789): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1789): mEnableLPD: true
D/NfcService( 1789): mEnableReader: false
D/NfcService( 1789): mEnableHostRouting: true
,D/NfcService( 1789): newParams.techmask= mTechMask: default
D/NfcService( 1789): mEnableLPD: true
D/NfcService( 1789): mEnableReader: false
D/NfcService( 1789): mEnableHostRouting: true
D/NfcService( 1789): screenState= 3
D/NfcService( 1789): Discovery configuration equal, not updating.
D/Ulp_jni (  972): JNI:system_update. Event-0
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2675): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 8:41:0
,D/WeatherService( 2675): 2 : ACTION screen on
D/WeatherService( 2675): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2675): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2675): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 8:41:0
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): ACTION_SCREEN_ON
D/AppCleanupService( 4123): android.intent.action.SCREEN_ON
,D/WeatherService( 2675): 2 : TimeTick Intent has been received, Time(hour:min:sec) 8:41:0
,D/WeatherService( 2675): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 8:41:0
D/PowerManagerServiceEx(  972): releaseWakeLockInternal: lock=650098705 [*alarm*], flags=0x0
,V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=off, calling pid 972
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
D/WifiController(  972): CMD_SCREEN_OFF 
D/WifiController(  972): shouldWifiStayAwake TRUE
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.SCREEN_OFF
,D/GpsLocationProvider(  972): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1842): |CORE| sendScreenState: state:false
,I/LEDService( 1806): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1806): stopPatternFlashing()
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1806): set_light_notifications: 0,0,0,0,3
I/LEDService( 1806): updateLightsLocked : turn on led
E/LEDService( 1806): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1806): Can't handle this request of patternId:0
D/LEDHandler( 1806): RESTART MSG
D/VolumeVibrator( 1806): clear
I/Cliptray Service( 1806): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/LNfcService( 1789): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1789): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1880): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1753): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2675): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 8:41:0
D/WeatherService( 2675): 2 : ACTION screen off
D/WeatherService( 2675): 2 : TimeTick Receiver Unregister
,D/WeatherService( 2675): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 8:41:0
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  972): ACTION_SCREEN_OFF
E/NxpNfcJni( 1789): getReconnectState = 0x0
,D/AppCleanupService( 4123): android.intent.action.SCREEN_OFF
D/LCardEmulationManager( 1789): getHceAppCount hostAppNum : 0
,D/AppCleanupService( 4123): AppUsageStatsSaveTask
D/LCardEmulationManager( 1789): getDefaultRoute
D/LNfcService( 1789): isRequireNfcCRouting() return true
D/LNfcService( 1789): isHCERoutingtoHost() return : true
D/NfcService( 1789): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1789): mEnableLPD: true
D/NfcService( 1789): mEnableReader: false
D/NfcService( 1789): mEnableHostRouting: true
D/NfcService( 1789): newParams.techmask= mTechMask: 0
D/NfcService( 1789): mEnableLPD: true
D/NfcService( 1789): mEnableReader: false
D/NfcService( 1789): mEnableHostRouting: true
D/NfcService( 1789): screenState= 1
E/NxpNfcJni( 1789): getReconnectState = 0x0
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1375): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{ae30b1c type 2 when 159640 com.android.systemui} when 159640
,D/PhoneUtils( 1753): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1753): getCallState : 0
D/PhoneUtils( 1753): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1753): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1375): isHdmiPluggedIn :false
,D/KeyguardViewMediator( 1375): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 173183200872; DSPS: 5773501; Offset : -3014862444
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1735): disconnect managed GoogleApiClient
,V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{3b67325 type 2 when 186135 com.google.android.gms} when 186135
,I/PhenotypeConfigurator( 1735): Scheduling Phenotype for one-off execution 5451 seconds from now (1457077291284)
,I/PhenotypeFlagCommitter( 1735): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1735): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  972): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  271): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  271): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  271): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  271): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  271): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  271): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  271): res_queryN name = xxxxx succeed
I/System.out( 1735): propertyValue:false
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1735): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1735): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
D/LocationManagerService(  972): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     ( 1735): Background sticky concurrent mark sweep GC freed 110187(6MB) AllocSpace objects, 13(231KB) LOS objects, 26% free, 17MB/23MB, paused 2.026ms total 103.420ms
,D/LocationManagerService(  972): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/LocationManagerService(  972): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1735): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  972): Explicit concurrent mark sweep GC freed 52036(2MB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/34MB, paused 2.885ms total 194.250ms
,V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{7d418aa type 2 when 190897 android} when 190897
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 193185530203; DSPS: 6428938; Offset : -3014882811
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 213187834905; DSPS: 7084375; Offset : -3014928092
,I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 233190539890; DSPS: 7739822; Offset : -3014875897
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 253192830751; DSPS: 8395257; Offset : -3014876119
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 273195045184; DSPS: 9050690; Offset : -3014889419
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
,I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 293197477829; DSPS: 9706129; Offset : -3014867635
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 313199764098; DSPS: 10361565; Offset : -3014898515
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 333208018151; DSPS: 11017195; Offset : -3014886499
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
,W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  972): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:29000 mC
,I/LocationManagerService(  972): remove 8fba37
D/LocationManagerService(  972): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  972): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  972): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  972): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  972): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  972): acquireWakeLockInternal: lock=650098705, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=972
,D/PowerManagerServiceEx(  972): releaseWakeLockInternal: lock=650098705 [*alarm*], flags=0x0
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 353210800560; DSPS: 11672647; Offset : -3014909599
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 373213139162; DSPS: 12328083; Offset : -3014890566
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{324e7c9b type 2 when 382172 android} when 382172
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 393215709950; DSPS: 12983520; Offset : -3014669815
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
,I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 409471189578; DSPS: 13516187; Offset : -3014896557
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 429473570986; DSPS: 14171624; Offset : -3014865237
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 449475787433; DSPS: 14827059; Offset : -3014937556
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 469479882763; DSPS: 15482551; Offset : -3014870598
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 489482269156; DSPS: 16137989; Offset : -3014864550
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 509484603830; DSPS: 16793426; Offset : -3014879783
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 529488679966; DSPS: 17448920; Offset : -3014892820
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  972): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 549491027867; DSPS: 18104356; Offset : -3014864358
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 569493249347; DSPS: 18759790; Offset : -3014901205
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 589497212299; DSPS: 19415276; Offset : -3014783209
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 604499599332; DSPS: 19906879; Offset : -3014929446
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  972): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 619501797032; DSPS: 20398468; Offset : -3014837407
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 639504143932; DSPS: 21053907; Offset : -3014901395
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  972): acquireWakeLockInternal: lock=650098705, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=972
,V/AlarmManager(  972): RTC_WAKEUP set : Alarm{10447838 type 0 when 1457077636128 com.google.android.gms} when 1457077636128
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ActivityManager(  972): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7108 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/art     (  307): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 478us total 33.757ms
,I/EventLogService( 4309): Aggregate from 1457077214304 (log), 1457075836022 (data)
I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 435us total 31.456ms
,I/art     (  307): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 472us total 30.930ms
,I/DigitalAppWidgetProvider( 7108): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7108): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@22b46c9
I/ActivityManager(  972): Killing 6761:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/PowerManagerServiceEx(  972): releaseWakeLockInternal: lock=650098705 [*alarm*], flags=0x0
,W/libprocessgroup(  972): failed to open /acct/uid_10011/pid_6761/cgroup.procs: No such file or directory
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 659505708816; DSPS: 21709318; Offset : -3014892934
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  972): battery changed pluggedType: 2
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 679508067538; DSPS: 22364758; Offset : -3014975591
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 694510686785; DSPS: 22856372; Offset : -3015224763
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 707650663413; DSPS: 23286931; Offset : -3014866108
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 727971901366; DSPS: 23952819; Offset : -3014917426
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 742973978922; DSPS: 24444405; Offset : -3014854004
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 760477385922; DSPS: 25017957; Offset : -3014864998
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 780479630447; DSPS: 25673390; Offset : -3014848257
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 800481978045; DSPS: 26328828; Offset : -3014881029
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 820484338840; DSPS: 26984264; Offset : -3014839622
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 840486632258; DSPS: 27639703; Offset : -3014957041
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 855489243803; DSPS: 28131299; Offset : -3014664859
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 869561651318; DSPS: 28592430; Offset : -3014858636
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 885818372940; DSPS: 29125134; Offset : -3014973003
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 899890551612; DSPS: 29586248; Offset : -3014876591
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 919892896544; DSPS: 30241685; Offset : -3014881747
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 939895132323; DSPS: 30897117; Offset : -3014843259
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  972): acquireWakeLockInternal: lock=650098705, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=972
,V/AlarmManager(  972): ELAPSED_WAKEUP set : Alarm{3302fc4d type 2 when 948163 com.android.bluetooth} when 948163
D/PowerManagerServiceEx(  972): releaseWakeLockInternal: lock=650098705 [*alarm*], flags=0x0
,W/bt-smp  ( 2050): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2050): Plain text(LSB ~ MSB) = df 93 78 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2050): Encrypted text(LSB ~ MSB) = b5 c9 80 cd f7 73 28 1c 41 0f f3 1f 82 a2 cb 2d 
W/bt-btm  ( 2050): Stopping oneshot timer
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 959896655824; DSPS: 31552528; Offset : -3014876076
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 979898895681; DSPS: 32207952; Offset : -3014589372
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 994903898802; DSPS: 32699640; Offset : -3014713204
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 1008980695605; DSPS: 33160915; Offset : -3014912066
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 1025238445992; DSPS: 33693647; Offset : -3014852291
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 1045240503472; DSPS: 34349076; Offset : -3014900550
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 1065244101652; DSPS: 35004555; Offset : -3014933962
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 1085246286830; DSPS: 35659980; Offset : -3014732401
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 1100250678696; DSPS: 36151649; Offset : -3014887680
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 1115256506095; DSPS: 36643361; Offset : -3014919526
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 1128388915715; DSPS: 37073680; Offset : -3014803686
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 1145123052789; DSPS: 37622032; Offset : -3015041793
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 1158260633399; DSPS: 38052520; Offset : -3014911861
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 1177640837522; DSPS: 38687576; Offset : -3015079143
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 1192642737613; DSPS: 39179155; Offset : -3014979589
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 1212644948281; DSPS: 39834587; Offset : -3014966188
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/UsageStatsService(  972): User[0] Flushing usage stats to disk
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 1227647435378; DSPS: 40326185; Offset : -3014859436
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1375): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1375): called onTimeUpdated()
I/[SystemUI]Clock( 1375): called onTimeUpdated()
I/LgeClockWidgetControlView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
I/[SystemUI]DateView( 1375): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1375): handleTimeUpdate
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 1242650489984; DSPS: 40817808; Offset : -3014947958
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 1255782900531; DSPS: 41248123; Offset : -3014709224
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/PowerService( 1806): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1375): onReceive = com.lge.android.intent.action.BATTERYEX
I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
I/[SystemUI]LGPowerUI( 1375): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1375): On Skip Timer : true
D/charger_monitor(  494): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2050): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1375): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 267
I/QCNEJ   ( 1842): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1842): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1806): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1806): Battery Level Remaining: 100%
D/LEDHandler( 1806): Battery Temp: 267, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1375): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1375): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 267
I/[SystemUI]BatterySaverHandler( 1375): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  972): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  972): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  972): battery changed pluggedType: 2
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  972): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  972): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  972): tsOffsetIs: Apps: 1276574137054; DSPS: 41929412; Offset : -3014762985
,I/ThermalEngine(  290): Sensor:pa_therm0:27000 mC
,TIME-OUT KILL (timeout was 1200000ms)
```
