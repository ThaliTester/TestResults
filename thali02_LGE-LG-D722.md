#### Test 6136236661fd38c_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
E/LGDMClient( 4658): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 4658): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 4658): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 4658): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 4658): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
D/UEI.SmartControl( 4710): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 4710): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4710): --- Extracting JNI libs: libqs_armeabi-v7a.zip
--------- beginning of system
I/ActivityManager(  968): Waited long enough for: ServiceRecord{1c7614d5 u0 com.lge.mlt/.MltMonitorService}
I/UEI.SmartControl( 4710): --- Selecting new region: 2
,I/UEI.SmartControl( 4710): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 4710): Platform has CIR...
D/UEI.SmartControl( 4710): NO CIR support, need to check package...
I/UEI.SmartControl( 4710): Model: LG-D722 uses JNI
D/UEI.SmartControl( 4710): QS Service created
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
E/UEI.SmartControl( 4710): QS start get config
D/UEI.SmartControl( 4710): Loading JNI Libs...
D/UEI.SmartControl( 4710):  configuring local db...
W/ResourcesManager( 4731): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4731): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 4731): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4731): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 4731): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 4731): Using schema version: 115
I/IndexDatabaseHelper( 4731): Index is fine
D/UEI.SmartControl( 4710):  ---- Has DB8: true
D/UEI.SmartControl( 4710): QS start statue = true Error code = 0
D/UEI.SmartControl( 4710): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4710): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4710): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 4710): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4710): IrrcClient ++ 
D/irrcClient( 4710): getIrrcService ++ 
D/irrcClient( 4710): getIrrcService -- 
D/irrcClient( 4710): IrrcClient -- 
W/irrc_jni( 4710): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 4710): Services init done
I/UEI.SmartControl( 4710): Device manager: loading config....
D/UEI.SmartControl( 4710): QS Service init finished
D/UEI.SmartControl( 4710): QS Service version name: 0.1.73
D/UEI.SmartControl( 4710): QS Service version code: 1073
D/UEI.SmartControl( 4710): Service requested: Control
D/UEI.SmartControl( 4710): Config is loaded...
D/UEI.SmartControl( 4710):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 4710): Notify AllClients services are ready: 0
D/UEI.SmartControl( 4710): Request IControl service: devices are loaded...
D/UEI.SmartControl( 4710): Internal service binding...
D/UEI.SmartControl( 4710): -----IControl: 11
D/UEI.SmartControl( 4710): Caller: com.lge.qremote
D/UEI.SmartControl( 4710): ------------ IControl registerCallback...
I/UEI.SmartControl( 4710): Registering callback...
D/UEI.SmartControl( 4710): -----IControl: 19
D/UEI.SmartControl( 4710): Caller: com.lge.qremote
I/UEI.SmartControl( 4710): Registering Services Ready callback...
I/UEI.SmartControl( 4710): Notify client services are ready...
D/UEI.SmartControl( 4710): -----IControl: 8
D/UEI.SmartControl( 4710): Caller: com.lge.qremote
I/ActivityManager(  968): Killing 3524:com.google.android.apps.plus/u0a86 (adj 15): empty #11
D/AndroidRuntime( 4754): 
D/AndroidRuntime( 4754): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4754): CheckJNI is OFF
V/WiFiOffLoadBroadcast( 4731): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
D/WiFiOffLoadBroadcast( 4731): MCCMNC not supported: null
I/ActivityManager(  968): Killing 4258:com.google.android.talk/u0a61 (adj 15): empty #12
W/libprocessgroup(  968): failed to open /acct/uid_10086/pid_3524/cgroup.procs: No such file or directory
W/libprocessgroup(  968): failed to open /acct/uid_10061/pid_4258/cgroup.procs: No such file or directory
I/ActivityManager(  968): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4773 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  968): Killing 4302:com.google.android.youtube/u0a100 (adj 15): empty #11
D/AndroidRuntime( 4754): Calling main entry com.android.commands.am.Am
I/art     (  303): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 22.885ms
I/art     (  303): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 286us total 21.467ms
I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 264us total 21.923ms
I/ActivityManager(  968): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/ActivityManager(  968): setTaskToReturnTo : TaskRecord{24838a9c #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  968): setTaskToReturnTo : TaskRecord{24838a9c #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  968): AppWindowTokenEx init.. 
D/ContextHelper(  968): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
I/PhoneWindow(  968): [generateLayout] setColorNavigationBar => color=0x ff000001
D/InputDispatcher(  968): Focus left window: Window{3946ca1c u0 com.lge.launcher2/com.lge.launcher2.Launcher}
D/AndroidRuntime( 4754): Shutting down VM
I/[LGHome]EVENT( 1873): [Launcher.java:986:onPause()]onPause
D/PhoneWindowEx(  968): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  968): [setNavigationBarColor2] color=0x fff5f5f5
D/SplitWindow(  968): check instance of lgWin Window{247c9134 u0 Starting com.test.thalitest}
I/ActivityManager(  968): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4792 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/libprocessgroup(  968): failed to open /acct/uid_10100/pid_4302/cgroup.procs: No such file or directory
I/WindowStateAnimator(  968): Starting window displayed
D/WindowManager(  968): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/SystemUI[Framework](  968): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
I/[SystemUI]NavigationThemeResource( 1369): notify navigation bar color(0xfff5f5f5)
W/PhoneWindowManagerEx(  968): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  968): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  968): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  968): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@17a72faa,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  968): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1369): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1369):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1369): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]EVENT( 1873): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
D/PCSuite ( 4773): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/UsbSettingsReceiver( 4731): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 4731): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 4731): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 4731): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 4731): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,I/[LGHome]EVENT( 1873): [Launcher.java:5214:onStop()]onStop
W/ActivityThread( 1873): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1873): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1873): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3407)
W/ActivityThread( 1873): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3496)
W/ActivityThread( 1873): 	at android.app.ActivityThread.access$1100(ActivityThread.java:155)
W/ActivityThread( 1873): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1352)
W/ActivityThread( 1873): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 1873): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 1873): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/ActivityThread( 1873): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 1873): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 1873): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/ActivityThread( 1873): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/HotwordDetector( 1939): Closing mic
I/MicrophoneInputStream( 1939): mic_close com.google.android.apps.gsa.speech.audio.u@dc00465
V/AudioRecord( 1939): stop()
,D/AudioRecord( 1939): AudioRecord->stop()
V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
D/ContextHelper( 4792): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
V/AudioFlinger(  278): Record stopped OK
V/AudioPolicyManager(  278): stopInput() input 17
V/AudioPolicyService(  278): AudioCommandThread() adding release patch delay 0
,V/AudioPolicyService(  278): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  278): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  278): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  278): ThreadBase::setParameters() routing=0
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb3828000
D/audio_hw_primary(  278): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
D/UsbSettingsControl( 4731): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 4731): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 4731): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 4731): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 4731): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 4731): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 4731): [AUTORUN] setTetherStatus() : status=false
V/WiFiOffLoadBroadcast( 4731): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,I/ActivityManager(  968): Activity reported stop, but no longer stopping: ActivityRecord{1b831583 u0 com.lge.launcher2/.Launcher t221}
D/WiFiOffLoadBroadcast( 4731): MCCMNC not supported: null
D/PCSuite ( 4773): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDMClient( 4658): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4658): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4658): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4658): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/WiFiOffLoadBroadcast( 4731): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,V/audio_hw_primary(  278): stop_input_stream: enter: usecase(7: audio-record)
,V/audio_hw_primary(  278): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  278): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  278): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  278): disable_audio_route: exit
E/audio_hw_primary(  278): disable_snd_device: enter 144
D/hardware_info(  278): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  278): disable_snd_device: snd_device(144: lg-vr-handset-mic)
D/LGDMClient( 4658): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/LGDMClient( 4658): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4658): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
D/WiFiOffLoadBroadcast( 4731): MCCMNC not supported: null
I/LGDMClient( 4658): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
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
W/ContextImpl( 4658): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
,E/LGDMClient( 4658): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
V/AudioPolicyService(  278): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  278): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  278): setParameters(): io 17, keyvalue hotword_active=0, calling pid 278
D/LGDMClient( 4658): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
V/AudioFlinger(  278): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  278): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  278): RecordThread: loop starting
V/AudioFlinger(  278): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  278): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  278): in_set_parameters: exit: status(0)
V/AudioFlinger(  278): processConfigEvents_l() DONE thread 0xb3828000
V/AudioFlinger(  278): RecordThread: loop stopping
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
D/LGDMClient( 4658): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 4658): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,D/LGDMClient( 4658): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
V/AudioRecord( 1939): stop()
V/AudioRecord( 1939): stop()
V/AudioRecord( 1939): stop()
,V/AudioFlinger(  278): RecordHandle::stop()
V/AudioFlinger(  278): RecordThread::stop
V/AudioPolicyManager(  278): releaseInput() 17
V/AudioPolicyManager(  278): closeInput(17)
V/AudioFlinger(  278): closeInput() 17
V/AudioSystem(  278): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1369): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): ThreadBase::exit
V/AudioSystem( 1748): ioConfigChanged() event 4, ioHandle 17
,V/AudioFlinger(  278): RecordThread: loop starting
V/AudioFlinger(  278): RecordThread 0xb3828000 exiting
D/audio_hw_primary(  278): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  278): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  278): in_standby: exit:  status(0)
V/AudioPolicyService(  278): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  278): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  278): AudioCommandThread() waking up
V/AudioPolicyService(  278): AudioCommandThread() processing update audio port list
V/AudioSystem(  968): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  278): AudioCommandThread() going to sleep
V/AudioPolicyManager(  278): releaseInput() exit
V/AudioSystem( 1939): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2014): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2645): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3150): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  278): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  278): removeClient_l() pid 1939, calling pid 278
V/AudioFlinger(  278): releasing 16 from 1939 for -1
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
I/HotwordRecognitionRnr( 1939): Stopping hotword detection.
,I/HotwordRecognitionRnr( 1939): Hotword detection finished
I/PCSuite ( 4773): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 4773): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4773): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/WebViewFactory( 4792): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 4792): Time to load native libraries: 2 ms (timestamps 8684-8686)
I/LibraryLoader( 4792): Expected native library version number "",actual native library version number ""
,I/ActivityManager(  968): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4828 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  968): Killing 4428:com.google.android.gm/u0a53 (adj 15): empty #11
V/WebViewChromiumFactoryProvider( 4792): Binding Chromium to main looper Looper (main, tid 1) {25b2344f}
,W/libprocessgroup(  968): failed to open /acct/uid_10053/pid_4428/cgroup.procs: No such file or directory
I/LibraryLoader( 4792): Expected native library version number "",actual native library version number ""
I/chromium( 4792): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserStartupController( 4792): Initializing chromium process, singleProcess=true
W/art     ( 4792): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4792): ApplicationContext is null in ApplicationStatus
,W/chromium( 4792): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 4792): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4792): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,V/[BNRBootReceiver]( 4828): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
I/Adreno-EGL( 4792): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4792): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4792): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4792): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4792): Remote Branch: 
I/Adreno-EGL( 4792): Local Patches: 
I/Adreno-EGL( 4792): Reconstruct Branch: 
D/BNRAndroBeam( 4828): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 4828): Boot Receiver Return
,W/MainApplication( 4828): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
V/WiFiOffLoadBroadcast( 4731): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4731): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4731): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 4731): Not supported operator for automatic switch
I/AudioManager( 4685): getMode name:com.lge.qremote
V/WiFiOffLoadBroadcast( 4731): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 4731): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 4731): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4731): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4731): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4731): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4731): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4731): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4731): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4731): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4731): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4731): MCCMNC not supported: null
V/AudioPolicyService(  278): registerClient() client 0xb4027800, uid 10316
D/BluetoothManagerService(  968): Message: 20
D/BluetoothManagerService(  968): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@130c81c9:true
,V/WiFiOffLoadBroadcast( 4731): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/BluetoothAdapterService(922757050)( 2014): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1cde05e0
,D/WiFiOffLoadBroadcast( 4731): MCCMNC not supported: null
,I/AudioManager( 4685): getMode name:com.lge.qremote
,V/WiFiOffLoadBroadcast( 4731): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 4731): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 4731): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4731): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4731): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4731): MCCMNC not supported: null
I/PCSuite ( 4773): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 4773): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 4731): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4731): MCCMNC not supported: null
I/PCSuite ( 4773): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 4773): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,W/art     ( 4792): Attempt to remove local handle scope entry from IRT, ignoring
,I/[LGHome]LGNumberBadgeReceiver( 1873): [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = lge.intent.action.UNREAD_MESSAGES
V/SmsReceiverService( 3150): onStart: #1 mResultCode: -1 = Activity.RESULT_OK
W/AwContents( 4792): onDetachedFromWindow called when already detached. Ignoring
,D/MmsConfig( 3150): isNotAllowedSms: currentUser:0
D/MmsConfig( 3150): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3150): isUserMode:false
D/SmsReceiverService( 3150): handleMessage isUserMode:false
I/PhoneWindow( 4792): [generateLayout] setColorNavigationBar => color=0x ff000001
I/[LGHome]NumberBadge.LGBroadCastBadge( 1873): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1873): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1873): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/[LGHome]NumberBadge.LGBroadCastBadge( 1873): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
D/PhoneWindowEx( 4792): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 4792): [setNavigationBarColor2] color=0x fff5f5f5
V/SmsReceiverService( 3150): handleMessage action: com.android.mms.transaction.SEND_MESSAGE error: 0
,D/SmsReceiverService( 3150): [LGE] handleSendMessage Send messages in queue
,D/SystemWebViewEngine( 4792): CordovaWebView is running on device made by: LGE
I/ActivityManager(  968): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4879 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/art     ( 4792): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4792): Attempt to remove local handle scope entry from IRT, ignoring
,I/Activity( 4792): Activity.onPostResume() called 
,D/OpenGLRenderer( 4792): Render dirty regions requested: true
I/OpenGLRenderer( 4792): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4792): Enabling debug mode 0
D/Atlas   ( 4792): Validating map...
,D/SplitWindow(  968): check instance of lgWin Window{21b4e97e u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 4792): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  968): Killing 4480:com.android.vending/u0a36 (adj 15): empty #11
W/libprocessgroup(  968): failed to open /acct/uid_10036/pid_4480/cgroup.procs: No such file or directory
,D/InputDispatcher(  968): Focus entered window: Window{21b4e97e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,W/InputMethodManagerService(  968): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  968): Displayed com.test.thalitest/.MainActivity: +1s381ms
I/Timeline(  968): Timeline: Activity_windows_visible id: ActivityRecord{30e5bca5 u0 com.test.thalitest/.MainActivity t222} time:69626
I/Timeline( 4792): Timeline: Activity_idle id: android.os.BinderProxy@5b919d1 time:69660
,W/BindingManager( 4792): Cannot call determinedVisibility() - never saw a connection for the pid: 4792
,I/MusicStore( 4879): Database version: 120
,D/JsMessageQueue( 4792): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  968): Waited long enough for: ServiceRecord{f653b26 u0 com.android.calendar/.alerts.InitAlarmsService}
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4879): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4879): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4879): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 4879): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4879): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 4879): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 4879): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4879): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3dc6201b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4879): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4879): GMSCore installation verified
,I/ConfigStore( 4879): Config Database version: 1
,D/jxcore_app_log( 4792): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426120064
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4792): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4792):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4792):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4792):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4792):     - Handshake required: false
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4792): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ed0d64b added. We now have 1 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4792): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4792):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4792):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4792):     - Bluetooth MAC address: F8:95:C7:87:85:54
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4792):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4792):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4792):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4792):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4792):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4792):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4792): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9bee6 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4792): addListener: New listener added - the number of listeners is now 1
,D/BluetoothAdapterService(922757050)( 2014): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1cde05e0
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4792): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4792): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4792): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 4792): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4792): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4792): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4792): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4792): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4792): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4792): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
,W/System.err( 4792): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4792): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4792): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4792): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4792): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 4792): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4792): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4792): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c548c27 added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4792): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4792): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fddbed4 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4792): addListener: New listener added - the number of listeners is now 1
,D/BluetoothAdapterService(922757050)( 2014): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1cde05e0
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4792): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4792): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4792): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 4792): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4792): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4792): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4792): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4792): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4792): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4792): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4792): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4792): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4792): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4792): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4792): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MediaRouter( 4879): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 4879): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 4879): type=WIFI subType= reason=null isConnected=true
,I/NetworkMonitor( 4879): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  968): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=4942 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 4879): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 4879): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 4942): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4942): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4942): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,I/ActivityManager(  968): Killing 3185:com.android.defcontainer/u0a4 (adj 15): empty #11
,W/libprocessgroup(  968): failed to open /acct/uid_10004/pid_3185/cgroup.procs: No such file or directory
,I/NotificationManager( 4879): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 4942): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 4942): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 4942): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 4658): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 4658): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
W/ContextImpl( 4658): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,W/ContextImpl( 4658): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 4658): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,I/LGDMClient( 4658): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/LGDMClient( 4658): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4658): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/ActivityManager(  968): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=4970 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
W/ContextImpl( 4658): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4658): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
,D/LGDMClient( 4658): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 4658): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 4658): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
,I/HubEmail( 4942): JNI_OnLoad()
I/HubEmail( 4942): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4942): registerNatives()
I/HubEmail( 4942): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4942): registerNativeMethods()
I/HubEmail( 4942): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,W/art     ( 4942): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
D/LGDMClient( 4658): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,W/Settings( 4942): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/art     (  968): Explicit concurrent mark sweep GC freed 24011(1200KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.445ms total 193.643ms
I/ActivityManager(  968): Killing 4629:com.lge.qmemoplus/1000 (adj 15): empty #11
,I/AppUp4:AppBoxCP( 4970): onCreate
,W/AppUp4:DB( 4970):  [AppBoxDatabaseHelper] construct
W/libprocessgroup(  968): failed to open /acct/uid_1000/pid_4629/cgroup.procs: No such file or directory
I/AppUp4:DB( 4970):  setFingerPrint start
,I/AppUp4:DB( 4970):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 4970):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 4970):  SDK version = 0
,I/AppUp4:DB( 4970):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 4970): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 4970): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 4970): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4970): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 4970): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 4970): onReceive
,I/AppUp4:CustModeStarterReceiver( 4970): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 4970): Context : android.app.ReceiverRestrictedContext@25b2344f
D/AppUp4:CustFacade( 4970): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4970): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 4970): begin check event
,I/AppUp4:CustModeStarterReceiver( 4970): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4970): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
,D/AppUp4:CustModeStarterReceiver( 4970): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 4970): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 4970): handleAsyncCustNotification do not startCustService
I/ActivityManager(  968): Killing 4828:com.lge.bnr/1000 (adj 15): empty #11
W/libprocessgroup(  968): failed to open /acct/uid_1000/pid_4828/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3150): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3150): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 3150): networkInfo.isConnected() = true
,D/PhoneState( 3150): setPdpRejectCasuse : false
,I/ActivityManager(  968): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=4996 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 4996): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 4996): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4996): onReceive CONNECTIVITY_CHANGE networkType=1
I/ActivityManager(  968): Killing 4731:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  968): failed to open /acct/uid_1000/pid_4731/cgroup.procs: No such file or directory
,I/CheckinService( 4342): Checkin interval check for package: unspecified last checkin: 1456941550763 min interval config: 0 actual interval: 71955443
V/DownloadManager( 3202): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 3202): DownloadService onCreate
,I/NotificationManager( 3202): com.android.providers.downloads: cancelAll by com.android.providers.downloads
I/DownloadManager( 3202): in removeSpuriousFiles
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@2394e5c5 on behalf of 3202
I/DownloadManager( 3202): in trimDatabase
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
D/PhoneMonitor( 4996): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 4996): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 4996): [parse] Load xml
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@3fc60b1a on behalf of 3202
V/TelephonyAutoProfiling( 4996): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 4996): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 4996): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  968): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5023 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,V/DownloadManager( 3202): DownloadService onStartCommand
I/CheckinService( 4342): Checking schedule, now: 1457013506261 next: 1456941580730
I/CheckinService( 4342): active receiver: enabled
V/DownloadManager( 3202): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@19384828 on behalf of 3202
,I/CheckinService( 4342): Preparing to send checkin request
I/EventLogService( 4342): Accumulating logs since 1457011802525
V/DownloadManager( 3202): DownloadService onDestroy
D/DrmBroadcastReceiver( 5023): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 5023): 1  network is available. Sync DRM Time with NTP
D/WeatherAncestor( 2616): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:58:26
V/DrmService( 5023): Service onCreate
D/DrmService( 5023): Received new request = 2
D/UpdateThreadPoolManager( 2616): 2 : This is isUpdating : false
D/WeatherAncestor( 2616): connectivity changed - connection : true
,D/Weather_cast( 2616): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherAncestor( 2616): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 14:58:26
D/WeatherService( 2616): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
I/DrmSntpClient( 5023): Start Sync process
D/DrmSntpClient( 5023): Server : 0
D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5023): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5023): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  274): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  968): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5052 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  968): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2616): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2616): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2616): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 5052): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 5023): propertyValue:false
I/CheckinRequestBuilder( 4342): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4342): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/LGDrmClient( 5023): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  288): eDRM_SetDRMTime +++
I/LGDRM   (  288): [DRM] SET TIME : YR=2016, MON=3, DAY=3
,I/LGDRM   (  288): [DRM] SET TIME : HR=13, MIN=58, SEC=26
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1729): propertyValue:false
V/ILGDrmService(  288): eDRM_SetDRMTime ---
I/DrmSntpClient( 5023): Synched
D/DrmService( 5023): Completed !! request = 2
D/DrmService( 5023): Request count = 0
V/DrmService( 5023): Service onDestroy
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/Babel_SMS( 5052): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5052): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5052): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5052): MmsConfig.loadFromDatabase
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,E/Babel_SMS( 5052): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5052): MmsConfig.loadFromResources
E/Babel_SMS( 5052): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5052): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5052): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5052): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5052): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5052): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5052): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5052): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5052): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5052): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5052): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5052): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5052): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5052): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5052): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5052): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5052): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5052): found sensor: Motion Accel, handle=46
,W/Settings( 5052): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5052): startup - clean
I/art     ( 5052): CheckpointMarkThreadRoots callback created = 0xb042d8c0
I/Babel   ( 5052): deleted: false for 0
,I/art     ( 5052): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,I/ActivityManager(  968): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5090 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  968): Waited long enough for: ServiceRecord{ae73be5 u0 com.lge.springcleaning/.service.AppCleanupService}
W/AudioCapabilities( 5052): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5052): Unsupported mime audio/adpcm
W/AudioCapabilities( 5052): Unsupported mime audio/g726
W/AudioCapabilities( 5052): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5052): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 5052): Unsupported mime video/mjpg
W/VideoCapabilities( 5052): Unsupported mime video/theora
W/AudioCapabilities( 5052): Unsupported mime audio/evrc
W/AudioCapabilities( 5052): Unsupported mime audio/qcelp
,W/VideoCapabilities( 5052): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5052): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5052): Unsupported mime audio/qcelp
W/AudioCapabilities( 5052): Unsupported mime audio/evrc
D/UEI.SmartControl( 4710): Internal timer expired: 1
,W/VideoCapabilities( 5052): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 5052): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5052): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5052): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5052): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5052): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 5052): onServiceConnected
W/Babel   ( 5052): Attempted to change video mute state without an active call.
,I/NotificationManager( 5052): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/libc-netbsd( 5052): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5052): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5052): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5052): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  274): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 5052): propertyValue:false
I/ActivityManager(  968): Process com.google.android.music:main (pid 4879) has died
,I/NotificationManager(  968): android: cancelAsUser(2) by android
I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5090): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5090): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5090): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5090): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 5090): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5090):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5090):   adb logcat -s GAv4
,I/Babel   ( 5052): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  968): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5124 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/GAv4    ( 5090): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 73060859978; DSPS: 2485446; Offset : -2798348595
W/ResourcesManager( 5124): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5124): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/GAv4    ( 5090): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
W/GAv4    ( 5090): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,I/MultiDex( 5124): VM with version 2.1.0 has multidex support
I/MultiDex( 5124): install
,I/MultiDex( 5124): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 5124): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5124): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5124): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@36c1f440: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5124): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 5124): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5124): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 5124): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5124): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/WebViewFactory( 5090): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/LibraryLoader( 5090): Time to load native libraries: 3 ms (timestamps 3422-3425)
,I/LibraryLoader( 5090): Expected native library version number "",actual native library version number ""
I/ActivityManager(  968): Process com.lge.qremote (pid 4685) has died
,D/UEI.SmartControl( 4710): Service.onUnbind: IControl
D/UEI.SmartControl( 4710): Service.onDestroy
D/UEI.SmartControl( 4710): Shutdown IRRCPlayer... 
V/WebViewChromiumFactoryProvider( 5090): Binding Chromium to main looper Looper (main, tid 1) {375aed70}
I/LibraryLoader( 5090): Expected native library version number "",actual native library version number ""
I/chromium( 5090): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,W/irrc_jni( 4710): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 4710): ~IrrcClient ++ 
D/irrcClient( 4710): ~IrrcClient -- 
W/irrc_jni( 4710): IRRCPlayer_nativeFinalize -- 
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,D/UEI.SmartControl( 4710): Blaster closed
D/UEI.SmartControl( 4710): Blaster closed
D/UEI.SmartControl( 4710): Shut down QS...
D/UEI.SmartControl( 4710): Stopped file observer...
I/BrowserStartupController( 5090): Initializing chromium process, singleProcess=true
W/art     ( 5090): Attempt to remove local handle scope entry from IRT, ignoring
I/UEI.SmartControl( 4710): QS lib stop result = true
E/SysUtils( 5090): ApplicationContext is null in ApplicationStatus
D/UEI.SmartControl( 4710): QS shutdown complete
I/art     ( 4038): Explicit concurrent mark sweep GC freed 2898(114KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 447us total 26.907ms
,W/ActivityManager(  968): Unable to start service Intent { act=com.lge.contacts.intent.action.BACKUP_DB flg=0x4 cmp=com.android.providers.contacts/com.lge.providers.contacts.backup.DatabaseBackupService (has extras) } U=0: not found
V/AlarmManager(  968): RTC_WAKEUP set : Alarm{3714ccf3 type 0 when 1456754271374 com.android.providers.contacts} when 1456754271374
V/AlarmManager(  968): ELAPSED_WAKEUP set : Alarm{13f7db0 type 2 when 59200 com.google.android.talk} when 59200
V/AlarmManager(  968): RTC_WAKEUP set : Alarm{31e283ae type 0 when 1457013507987 com.google.android.googlequicksearchbox} when 1457013507987
,D/NativeLibraryUtils( 5124): Install completed successfully. count=14 extracted=0
D/WVCdm   (  278): Instantiating CDM.
,I/WVCdm   (  278): CdmEngine::OpenSession
I/WVCdm   (  278): Level3 Library Dec 11 2014 16:13:16
W/chromium( 5090): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5090): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5090): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5090): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5090): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5090): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5090): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5090): Remote Branch: 
I/Adreno-EGL( 5090): Local Patches: 
I/Adreno-EGL( 5090): Reconstruct Branch: 
W/WVCdm   (  278): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  278): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  278): L1 library not specified. Falling Back to L3
,I/GoogleURLConnFactory( 5124): Using platform SSLCertificateSocketFactory
,D/libc-netbsd( 5124): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5124): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5124): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5124): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 5124): propertyValue:false
I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
D/WVCdm   (  278): PrepareKeyRequest: nonce=2634476163
V/AudioPolicyService(  278): registerClient() client 0xb40278c0, uid 10079
W/AudioManagerAndroid( 5090): Requires BLUETOOTH permission
I/NSApplication( 5090): Starting up...
,I/ActivityManager(  968): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5187 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 287us total 21.749ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 275us total 23.539ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 289us total 26.984ms
,I/ActivityManager(  968): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5206 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  968): Killing 4710:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
D/libc-netbsd( 5124): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5124): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5124): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5124): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/libprocessgroup(  968): failed to open /acct/uid_10089/pid_4710/cgroup.procs: No such file or directory
,W/ProcessCpuTracker(  968): Skipping unknown process pid 5226
,W/ResourcesManager( 5206): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]QPairHandler( 1369): onReceive = android.intent.action.PACKAGE_CHANGED
I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  968): Reconfiguring input devices.  changes=0x00000010
I/[SystemUI]QSlideListController( 1369): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1369): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
D/administrator(  968): Handling package changes for user 0
,I/art     ( 5124): CheckpointMarkThreadRoots callback created = 0xb0553740
,I/art     ( 1782): CheckpointMarkThreadRoots callback created = 0xaaf21b50
I/art     ( 1782): CheckpointMarkThreadRoots callback created = 0xaaf4c570
I/art     ( 5124): CheckpointMarkThreadRoots callback created = 0xb0553730
,I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1873): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationService(  968): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  968): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  968): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  968): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  968): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  968): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@f69a25d
,W/ResourcesManager(  968): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/LCardEmulationManager( 1782): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1782): getDefaultRoute
,W/ResourceType(  968): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/dex2oat ( 5242): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=37 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/chromium( 4792): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
I/chromium( 4792): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,I/ActivityManager(  968): Killing 4773:com.lge.sync/1000 (adj 15): empty #11
I/dex2oat ( 5242): dex2oat took 93.732ms (threads: 4)
,W/libprocessgroup(  968): failed to open /acct/uid_1000/pid_4773/cgroup.procs: No such file or directory
I/Adreno-EGL( 5124): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5124): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5124): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5124): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5124): Remote Branch: 
I/Adreno-EGL( 5124): Local Patches: 
I/Adreno-EGL( 5124): Reconstruct Branch: 
I/GCoreNlp( 1729): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  968): applying state to connected service
,D/NetworkLogImpl( 4342): Loaded NetworkSpeedPredictor
I/iu.Environment( 4342): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.SyncManager( 4342): SYNC; picasa accounts
,I/iu.UploadsManager( 4342): num queued entries: 0
I/iu.UploadsManager( 4342): num updated entries: 0
I/iu.SyncManager( 4342): NEXT; no task
I/Adreno-EGL( 5124): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5124): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5124): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5124): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5124): Remote Branch: 
I/Adreno-EGL( 5124): Local Patches: 
I/Adreno-EGL( 5124): Reconstruct Branch: 
,I/ActivityManager(  968): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=5260 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/art     (  968): Explicit concurrent mark sweep GC freed 26984(1450KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 9.056ms total 181.789ms
I/WVCdm   (  278): CdmEngine::OpenSession
,I/DigitalAppWidgetProvider( 5260): onReceive: android.intent.action.ALARM_CHANGED
,I/ActivityManager(  968): Killing 4942:com.lge.email/u0a21 (adj 15): empty #11
W/libprocessgroup(  968): failed to open /acct/uid_10021/pid_4942/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2616): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:58:30
D/UpdateThreadPoolManager( 2616): 2 : This is isUpdating : false
D/Weather_cast( 2616): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2616): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:58:30
D/WeatherService( 2616): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
I/ActivityManager(  968): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=5283 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
W/ActivityManager(  968): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2616): 2 : Utils getTopActivity com.lge.launcher2 / true
,D/WeatherService( 2616): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2616): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,I/WVCdm   (  278): CdmEngine::CloseSession
,I/WVCdm   (  278): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  278): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  278): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  278): CdmEngine::GenerateKeyRequest
D/WVCdm   (  278): PrepareKeyRequest: nonce=1738237148
W/ResourcesManager( 5283): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5283): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5283): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5283): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5283): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/IndexDatabaseHelper( 5283): Using schema version: 115
,I/IndexDatabaseHelper( 5283): Index is fine
D/UsbSettingsReceiver( 5283): [AUTORUN] onReceive() : action = android.hardware.usb.action.USB_STATE
,D/UsbSettingsReceiver( 5283): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5283): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5283): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5283): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsReceiver( 5283): [AUTORUN] onReceive() : getDefaultFunction = ptp_only
D/UsbSettingsReceiver( 5283): [AUTORUN] onReceive() : USB_FUNCTION_CDROM_STORAGE = false
D/UsbSettingsReceiver( 5283): [AUTORUN] onReceive() : mDirectAutorun = true
D/UsbSettingsReceiver( 5283): [AUTORUN] onReceive() : mActivityUsbModeChange = false
D/UsbSettingsReceiver( 5283): [AUTORUN] onReceive() : mActivityFinish = false
D/UsbSettingsReceiver( 5283): [AUTORUN] onReceive() : ===== USB Configured =====
,D/UsbSettingsControl( 5283): [AUTORUN] setUsbConnected() : connected=true
D/UsbSettingsReceiver( 5283): [AUTORUN] onReceive() : checkQmicm = ptp_only,adb
D/UsbSettingsReceiver( 5283): [AUTORUN] : topPackageName=com.test.thalitest
D/UsbSettingsReceiver( 5283): [AUTORUN] : topClassName=com.test.thalitest.MainActivity
,D/UsbSettingsReceiver( 5283): [AUTORUN] Not exist com.android.LGSetupWizard
D/UsbSettingsReceiver( 5283): [AUTORUN] setUsbConnect() : mUsbSettingsRun = false
D/UsbSettingsReceiver( 5283): [AUTORUN] startUsbSettings() : deviceProvisioned=1
I/ActivityManager(  968): Killing 4658:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  968): failed to open /acct/uid_1000/pid_4658/cgroup.procs: No such file or directory
,I/ActivityManager(  968): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5304 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/MtpService( 3202): updating state; isCurrentUser=true, mMtpLocked=false
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/PCSuite ( 5304): [StartReceiver]USB CONNECTED ver UsbManger : ptp_only
I/PCSuite ( 5304): [StartReceiver]isUsbPCSuiteMode : false
D/PCSuite ( 5304): [StartReceiver][checkEUTStatus] eutStatus = 
D/PCSuite ( 5304): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5304): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  968): Killing 4970:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  968): failed to open /acct/uid_10011/pid_4970/cgroup.procs: No such file or directory
D/WeatherAncestor( 2616): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:58:31
D/UpdateThreadPoolManager( 2616): 2 : This is isUpdating : false
D/WeatherAncestor( 2616): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:58:31
D/WeatherService( 2616): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
W/ActivityManager(  968): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2616): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2616): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2616): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2616): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2616): 2 : This is isUpdating : false
D/WeatherService( 2616): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2616): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2616): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2616): 2 : Fixed theme : optimus
V/UserPresentBroadcastReceiver( 1729): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/WeatherReflect( 2616): 2 : Map key string is -2
D/lim     ( 2616): 2 : time = 14:58
I/WeatherReflect( 2616): Model Name : LG-D722
D/WeatherTheme( 2616): 2 : exactly same view!
D/WeatherTheme( 2616): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
I/ActivityManager(  968): Start proc com.lge.qremote for broadcast com.lge.qremote/.LgIrMdmPolicyReceiver: pid=5329 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
W/ActivityManager(  968): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2616): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2616): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2616): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
W/ResourcesManager( 5329): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
D/BluetoothManagerService(  968): Message: 20
D/BluetoothManagerService(  968): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f88a8fb:true
D/BluetoothAdapterService(922757050)( 2014): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1cde05e0
D/BluetoothAdapterService(922757050)( 2014): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1cde05e0
V/LGMDMManager( 5329): Create singleton instance
I/DigitalAppWidgetProvider( 5260): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 2616): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:58:31
D/UpdateThreadPoolManager( 2616): 2 : This is isUpdating : false
D/Weather_cast( 2616): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2616): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:58:31
D/WeatherService( 2616): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
W/ActivityManager(  968): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2616): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2616): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2616): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/AlertReceiver( 3877): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 3877): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 3877): [updateWidgets] 
,D/MonthWidgetProvider( 3877): [onReceive]
D/CalendarWidgetProvider( 3877): [onReceive]
D/CalendarWidgetProvider( 3877): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 3877): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 3877): [onReceive]
D/CalendarWidgetProvider( 3877): [onReceive]
D/CalendarWidgetProvider( 3877): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,D/CalendarTypeController( 3877): [onCreate] mContext.getPackageName() = com.android.calendar
I/[SystemUI]SafeModeBroadcastReceiver( 1369): onReceive = com.lge.statusbar.bootcompleted
,D/CalendarWeatherReceiver( 3877): Get action=com.lge.calendar.action.WEATHER_SERVICE_START
I/ActivityManager(  968): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.MediaScanReceiver: pid=5349 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,E/MediaScanReceiver( 5349): media scanning start or checking
W/MainApplication( 5349): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ActivityManager(  968): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5370 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  968): Killing 4996:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  968): failed to open /acct/uid_10038/pid_4996/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/MusicStore( 5370): Database version: 120
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5370): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5370): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5370): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 5370): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5370): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5370): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5370): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5370): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3dc6201b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5370): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5370): GMSCore installation verified
,I/ConfigStore( 5370): Config Database version: 1
,I/WVCdm   (  278): CdmEngine::CloseSession
,I/WVCdm   (  278): L3 Terminate.
I/MediaRouter( 5370): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/ToneMappingReceiver( 5260): Enter doAlarmRingToneUriMapping()
I/NetworkMonitor( 5370): type=WIFI subType= reason=null isConnected=true
,D/ToneMappingReceiver( 5260): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5260): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
,D/CommonUtil( 5260): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5260): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5260): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5260): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5260): Alarm Success count is 0
D/ToneMappingReceiver( 5260): Timer Success count is 0
I/MediaScannerReceiver( 3877): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///system/media
,I/InitNotificationRingtoneService( 3877): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3877): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
E/MediaScanReceiver( 5349): media scanning finished
,I/com.lge.bnr.receiver.MediaScanReceiver( 5349): android.intent.action.MEDIA_SCANNER_FINISHED
I/NetworkMonitor( 5370): type=WIFI subType= reason=null isConnected=true
I/AlertUtils( 3877): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/GHttpClientFactory( 5370): Using our fixed implementation of GMSCore's GoogleHttpClient
I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/GoogleURLConnFactory( 5370): Using platform SSLCertificateSocketFactory
I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3877): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 3877): set default noti to content://media/internal/audio/media/38
,I/InitNotificationRingtoneService( 3877): End InitializeAlertRingtoneService.onHandleIntent
E/MediaScanReceiver( 5349): media scanning start or checking
I/NotificationManager( 5370): com.google.android.music: cancel(1061) by com.google.android.music
,D/ToneMappingReceiver( 5260): Enter doAlarmRingToneUriMapping()
D/ToneMappingReceiver( 5260): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5260): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5260): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5260): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5260): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5260): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5260): Alarm Success count is 0
D/ToneMappingReceiver( 5260): Timer Success count is 0
,I/ActivityManager(  968): Killing 5023:com.lge.drmservice/u0a51 (adj 15): empty #11
I/MediaScannerReceiver( 3877): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///storage/emulated/0
,W/libprocessgroup(  968): failed to open /acct/uid_10051/pid_5023/cgroup.procs: No such file or directory
E/MediaScanReceiver( 5349): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 5349): android.intent.action.MEDIA_SCANNER_FINISHED
I/InitNotificationRingtoneService( 3877): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3877): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/AlertUtils( 3877): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/ActivityManager(  968): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5413 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3877): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3877): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 3877): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3877): End InitializeAlertRingtoneService.onHandleIntent
,W/ResourcesManager( 5413): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5413): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3576e92d
,D/CalendarProvider2( 5413): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5413): Created com.android.providers.calendar.CalendarAlarmManager@30e1ceae(com.android.providers.calendar.CalendarProvider2@3576e92d)
D/CalendarProviderBroadcastReceiver( 5413): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5413): [IntentService] WakeLock acquire, start IntentSerivce
,I/art     ( 5370): CheckpointMarkThreadRoots callback created = 0xb042d3f0
D/CalendarProvider2( 5413): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 5413): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
,D/CalendarProvider2( 5413): [getOrCreateCalendarAlarmManager]
I/art     ( 5370): CheckpointMarkThreadRoots callback created = 0xb042d3b0
,I/art     (  968): Explicit concurrent mark sweep GC freed 14029(753KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.352ms total 141.011ms
,D/WearableService( 1729): callingUid 10006, callindPid: 1729
,D/AuthorizationBluetoothService( 1729): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1729): [148] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 4342): Restart initialization of location
D/CalendarProvider2( 5413): [IntentService] Release Lock
D/CalendarProvider2( 5413): CalendarProviderIntentService.onDestroy()
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  968): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5440 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1729): No location to return for getLastLocation()
,W/FusedLocationProvider( 1729): location=null
I/MediaStoreImporter( 5370): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/ActivityManager(  968): Killing 5052:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  968): failed to open /acct/uid_10061/pid_5052/cgroup.procs: No such file or directory
,W/IcingInternalCorpora( 4342): getNumBytesRead when not calculated.
,W/ActivityManager(  968): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5440): getAccountsCursor
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5440): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  968): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5440): Error finding the version of the Email provider.....
E/Gmail   ( 5440): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5440): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5440): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5440): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5440): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5440): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5440): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5440): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5440): We do not support migrating this version of the Email provider.
,I/Gmail   ( 5440): getAccountsCursor
I/ActivityManager(  968): Killing 5090:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/libprocessgroup(  968): failed to open /acct/uid_10079/pid_5090/cgroup.procs: No such file or directory
,W/ActivityManager(  968): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  968): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5440): Observing account changes for notifications
,W/GCoreFlp( 1729): No location to return for getLastLocation()
W/FusedLocationProvider( 1729): location=null
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 3202): Explicit concurrent mark sweep GC freed 9144(504KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 8MB/13MB, paused 1.203ms total 56.418ms
,V/DownloadManager( 3202): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@a9bee6 on behalf of 4342
I/ActivityManager(  968): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5498 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/Gmail   ( 5440): getAccountsCursor
I/Gmail   ( 5440): notifyAccountChanged
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5440): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5440): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5440): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5440): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/PhoneMonitor( 5498): Register our PhoneStateListener
,I/ActivityManager(  968): Killing 5187:com.android.chrome/u0a48 (adj 15): empty #11
,I/Adreno-EGL( 5124): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5124): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5124): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5124): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5124): Remote Branch: 
I/Adreno-EGL( 5124): Local Patches: 
I/Adreno-EGL( 5124): Reconstruct Branch: 
I/art     ( 1729): Explicit concurrent mark sweep GC freed 27020(1862KB) AllocSpace objects, 31(496KB) LOS objects, 40% free, 13MB/22MB, paused 1.245ms total 113.742ms
,I/CheckinRequestBuilder( 4342): Classify the device as Phone.
W/libprocessgroup(  968): failed to open /acct/uid_10048/pid_5187/cgroup.procs: No such file or directory
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@c548c27 on behalf of 4342
V/DownloadManager( 3202): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@fddbed4 on behalf of 4342
I/CheckinService( 4342): Checkin interval check for package: unspecified last checkin: 1456941550763 min interval config: 0 actual interval: 71963768
,D/GCM     ( 1729): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/PhoneMonitor( 5498): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 5498): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5498): [parse] Load xml
V/TelephonyAutoProfiling( 5498): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5498): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5498): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/Gmail   ( 5440): getAccountsCursor
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 4342): Explicit concurrent mark sweep GC freed 17637(1318KB) AllocSpace objects, 27(432KB) LOS objects, 40% free, 11MB/19MB, paused 1.111ms total 98.277ms
,I/ActivityManager(  968): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5523 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
V/AlarmManager(  968): ELAPSED_WAKEUP set : Alarm{1659080a type 2 when 80228 android} when 80228
I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 299us total 22.628ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 275us total 21.154ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 270us total 20.742ms
,W/ResourcesManager( 5523): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/libc-netbsd( 4342): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4342): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4342): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4342): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 4342): propertyValue:false
,I/art     ( 5523): CheckpointMarkThreadRoots callback created = 0xb042d370
,I/art     ( 5523): CheckpointMarkThreadRoots callback created = 0xb042d340
I/art     (  968): Explicit concurrent mark sweep GC freed 15804(727KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 1.997ms total 144.808ms
I/Babel_SMS( 5523): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5523): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5523): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5523): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5523): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5523): MmsConfig.loadFromResources
E/Babel_SMS( 5523): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5523): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5523): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5523): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5523): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5523): found sensor: LGE Proximity Sensor, handle=48
,D/SensorManager( 5523): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5523): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5523): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5523): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5523): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5523): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5523): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5523): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5523): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5523): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5523): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5523): found sensor: Motion Accel, handle=46
W/Settings( 5523): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5523): startup - clean
I/Babel   ( 5523): deleted: false for 0
,D/libc-netbsd( 4342): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4342): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4342): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4342): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4342): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4342): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 4342): Sending checkin request (10167 bytes)
,I/ActivityManager(  968): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5556 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
W/AudioCapabilities( 5523): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5523): Unsupported mime audio/adpcm
W/AudioCapabilities( 5523): Unsupported mime audio/g726
W/AudioCapabilities( 5523): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5523): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5523): Unsupported mime video/mjpg
W/VideoCapabilities( 5523): Unsupported mime video/theora
,W/ResourcesManager( 5556): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5556): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5556): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/AudioCapabilities( 5523): Unsupported mime audio/evrc
W/AudioCapabilities( 5523): Unsupported mime audio/qcelp
W/VideoCapabilities( 5523): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5523): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5523): Unsupported mime audio/qcelp
W/AudioCapabilities( 5523): Unsupported mime audio/evrc
W/VideoCapabilities( 5523): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5523): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5523): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5523): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5523): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5523): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  968): Killing 5206:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  968): failed to open /acct/uid_10086/pid_5206/cgroup.procs: No such file or directory
,I/vclib   ( 5523): onServiceConnected
W/Babel   ( 5523): Attempted to change video mute state without an active call.
I/NotificationManager( 5523): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/LGEmail ( 5556): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/LGEmail ( 5556): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/PackageChangeReceiver( 5556): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  968): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5589 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  968): Killing 5283:com.android.settings/1000 (adj 15): empty #11
,W/libprocessgroup(  968): failed to open /acct/uid_1000/pid_5283/cgroup.procs: No such file or directory
,I/ActivityManager(  968): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5609 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  968): Killing 5304:com.lge.sync/1000 (adj 15): empty #11
,W/libprocessgroup(  968): failed to open /acct/uid_1000/pid_5304/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 5609): onCreate
W/AppUp4:DB( 5609):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 5609):  setFingerPrint start
I/AppUp4:DB( 5609):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5609):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5609):  SDK version = 0
I/AppUp4:DB( 5609):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5609): AppBoxApplication onCreate()
D/AppUp4:PreloadHelper( 5609): removed from Exclude : com.test.thalitest : 1
,I/ActivityManager(  968): Killing 5260:com.lge.clock/u0a10 (adj 15): empty #11
I/CheckinRequestBuilder( 4342): Checkin reason type: 8 attempt count: 1
,W/libprocessgroup(  968): failed to open /acct/uid_10010/pid_5260/cgroup.procs: No such file or directory
E/ActivityThread( 4342): Failed to find provider info for com.google.android.wearable.settings
I/ActivityManager(  968): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5626 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/art     ( 4038): Explicit concurrent mark sweep GC freed 3103(121KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 2.129ms total 51.501ms
,W/ResourcesManager( 5626): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5626): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5626): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 4342): Classify the device as Phone.
,I/CheckinTask( 4342): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4342): Checking schedule, now: 1457013516465 next: 1457540765461
I/CheckinService( 4342): active receiver: disabled
,I/AppConfig( 5626): Total System Memory = 906309632
,I/GalleryUtils( 5626): Application Heap = 96 MB
I/CheckinService( 4342): Checking schedule, now: 1457013516497 next: 1457540765461
I/CheckinService( 4342): active receiver: disabled
D/CheckinService( 4342): Recording last checkin time for package unspecified as 1457013516506
,I/AppConfig( 5626): App Tier : NOT_DEF
D/SystemHelper( 5626): region [EU], country [EU], operator [OPEN], sub-operator []
,D/AlertService( 3877): Beginning updateAlertNotification
,I/ActivityManager(  968): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5653 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,D/AlertService( 3877): No fired or scheduled alerts
I/NotificationManager( 3877): com.android.calendar: cancel(0) by com.android.calendar
,I/NotificationManager( 3877): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3877): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3877): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3877): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3877): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3877): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3877): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3877): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3877): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3877): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3877): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3877): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3877): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3877): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3877): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3877): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3877): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3877): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3877): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3877): com.android.calendar: cancel(20) by com.android.calendar
,D/AlertService( 3877): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,I/ActivityManager(  968): Killing 5349:com.lge.bnr/1000 (adj 15): empty #11
W/ResourcesManager( 5653): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5653): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5653): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5653): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5653): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/libprocessgroup(  968): failed to open /acct/uid_1000/pid_5349/cgroup.procs: No such file or directory
,D/AlarmScheduler( 3877): No events found starting within 1 week.
I/SystemConfig( 5653): BUILD Country: EU
I/SystemConfig( 5653): BUILD Operator: OPEN
,I/ActivityManager(  968): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5675 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  968): Killing 5370:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  968): failed to open /acct/uid_10081/pid_5370/cgroup.procs: No such file or directory
,I/SystemConfig( 5653): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5653): existFile = false
I/SystemConfig( 5653): canReadFile = false
I/SystemConfig( 5653): systemFeature RCS result false
D/SystemConfig( 5653): refreshRcsSupport() :false
I/LockScreenSettings( 5675): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 5675): New app installed broadcast received ..
,I/LockScreenSettings( 5675): Number of installed packages  1
,I/ActivityManager(  968): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5693 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  968): Killing 5413:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  968): failed to open /acct/uid_10014/pid_5413/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 5693): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5693): uri : package:com.test.thalitest
,I/ActivityManager(  968): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5710 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  968): Killing 5440:com.google.android.gm/u0a53 (adj 15): empty #11
,W/libprocessgroup(  968): failed to open /acct/uid_10053/pid_5440/cgroup.procs: No such file or directory
D/[BNRAppListMgrReceiver]( 5710): android.intent.action.PACKAGE_ADDED : com.test.thalitest
,W/MainApplication( 5710): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ActivityManager(  968): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5727 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,I/ActivityManager(  968): Killing 5498:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  968): failed to open /acct/uid_10038/pid_5498/cgroup.procs: No such file or directory
,I/GAv4    ( 5727): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5727):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5727):   adb logcat -s GAv4
,W/GAv4    ( 5727): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5727): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5727): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/AnalyticsTrackerProxyImpl( 5727): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5727): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 5727): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5727): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  968): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5759 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  968): Killing 5523:com.google.android.talk/u0a61 (adj 15): empty #11
W/libprocessgroup(  968): failed to open /acct/uid_10061/pid_5523/cgroup.procs: No such file or directory
,I/art     ( 5727): CheckpointMarkThreadRoots callback created = 0xaaf2a220
,W/ResourcesManager( 5759): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
V/JNIHelp ( 5727): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/art     ( 5727): CheckpointMarkThreadRoots callback created = 0xb050ea60
,W/System  ( 5727): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5727): Installed default security provider GmsCore_OpenSSL
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  968): Killing 5556:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  968): failed to open /acct/uid_10021/pid_5556/cgroup.procs: No such file or directory
,I/ActivityManager(  968): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5797 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 704(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 23.246ms
,I/UpdateIcingCorporaServi( 1939): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/art     (  303): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 276us total 22.251ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 277us total 22.151ms
,I/CheckinService( 4342): Done disabling old GoogleServicesFramework version
I/UpdateIcingCorporaServi( 1939): UpdateCorporaTask done [took 165 ms] updated apps [took 165 ms] 
,D/Finsky  ( 5797): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5797): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5797): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5797): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 5797): com.android.vending: cancel(-1050172287) by com.android.vending
,I/NotificationManager( 5797): com.android.vending: cancel(1003285959) by com.android.vending
,V/DownloadManager( 3202): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3202): created cursor android.database.sqlite.SQLiteCursor@3d87087d on behalf of 5797
I/ActivityManager(  968): Killing 5124:com.google.android.gms.unstable/u0a6 (adj 9): empty #11
W/libprocessgroup(  968): failed to open /acct/uid_10006/pid_5124/cgroup.procs: No such file or directory
,W/ActivityManager(  968): Scheduling restart of crashed service com.google.android.gms/.droidguard.DroidGuardService in 1000ms
D/Ads     ( 5797): Skipping gmscore version check
,D/PackageBroadcastService( 4342): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/Finsky  ( 5797): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5797): [1] Libraries$2.run: Finished loading 1 libraries.
,D/ChimeraCfgMgr( 4342): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4342): Loading module APK com.google.android.play.games
D/Finsky  ( 5797): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/Finsky  ( 5797): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5797): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,D/InitAlarmsService( 3877): Clearing and rescheduling alarms.
,I/ActivityManager(  968): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5844 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5844): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5844): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3576e92d
,D/CalendarProvider2( 5844): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5844): Created com.android.providers.calendar.CalendarAlarmManager@30e1ceae(com.android.providers.calendar.CalendarProvider2@3576e92d)
D/CalendarProvider2( 5844): Scheduling check of next Alarm
I/PeopleDatabaseHelper( 4342): cleanUpNonGplusAccounts done.
,I/art     (  968): Explicit concurrent mark sweep GC freed 21194(1053KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/34MB, paused 2.305ms total 170.387ms
,D/CalendarProvider2( 5844): SCHEDULE_ALARM_REMOVE
I/ActivityManager(  968): Killing 3877:com.android.calendar/u0a13 (adj 15): empty #11
D/ChimeraCfgMgr( 4342): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4342): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4342): Loading module com.google.android.gms.gass from APK com.google.android.gms
,W/libprocessgroup(  968): failed to open /acct/uid_10013/pid_3877/cgroup.procs: No such file or directory
D/AsyncTaskServiceImpl( 4342): Submit a task: k
,I/Icing   ( 4342): Storage manager: low false usage 1.73MB avail 2.37GB capacity 4.06GB
,W/BaseAppContext( 4342): Using Auth Proxy for data requests.
,W/BaseAppContext( 4342): Using Auth Proxy for data requests.
D/ChimeraCfgMgr( 4342): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 4342): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 4342): Processing package: com.test.thalitest
D/GassUtils( 4342): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 4342): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 4342): Using Auth Proxy for data requests.
,I/ActivityManager(  968): Killing 5589:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/libprocessgroup(  968): failed to open /acct/uid_10009/pid_5589/cgroup.procs: No such file or directory
,I/ActivityManager(  968): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5881 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AudioManager( 5329): getMode name:com.lge.qremote
W/BaseAppContext( 4342): Using Auth Proxy for data requests.
W/BaseAppContext( 4342): Using Auth Proxy for data requests.
W/BaseAppContext( 4342): Using Auth Proxy for data requests.
I/AudioManager( 5329): getMode name:com.lge.qremote
,W/BaseAppContext( 4342): Using Auth Proxy for data requests.
,I/AudioManager( 5329): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/AudioManager( 5329): getMode name:com.lge.qremote
,I/AudioManager( 5329): getMode name:com.lge.qremote
D/UEI.SmartControl( 5881): Quickset Services start...
D/WearableService( 1729): callingUid 10006, callindPid: 1729
,E/MDM     ( 1729): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1729): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 4342): Restart initialization of location
I/UEI.SmartControl( 5881): Manufacture = LGE
D/UEI.SmartControl( 5881): File observer start...
E/UEI.SmartControl( 5881): IR Port is disabled: false
D/UEI.SmartControl( 5881): Starting file observer...
D/UEI.SmartControl( 5881): Extracting JNI libs...
D/UEI.SmartControl( 5881): --- this system supports 32-bit or 64-bit only
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
I/ActivityManager(  968): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5909 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/GCoreFlp( 1729): No location to return for getLastLocation()
,W/FusedLocationProvider( 1729): location=null
,W/ResourcesManager( 5909): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 5881): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5881): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5881): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 5881): --- Selecting new region: 2
,I/UEI.SmartControl( 5881): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5881): Platform has CIR...
D/UEI.SmartControl( 5881): NO CIR support, need to check package...
I/UEI.SmartControl( 5881): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5881): QS Service created
E/UEI.SmartControl( 5881): QS start get config
,D/UEI.SmartControl( 5881): Loading JNI Libs...
D/UEI.SmartControl( 5881):  configuring local db...
,I/Icing   ( 4342): updateResources: need to parse f{com.google.android.gms}
,I/Babel_SMS( 5909): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5909): MmsConfig.loadMmsSettings
I/Babel_SMS( 5909): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5909): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5909): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5909): MmsConfig.loadFromResources
E/Babel_SMS( 5909): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5909): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5909): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5909): found sensor: LGE Magnetometer Sensor, handle=10
,D/SensorManager( 5909): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5909): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5909): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5909): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5909): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5909): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5909): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5909): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5909): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5909): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5909): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5909): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5909): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5909): found sensor: Motion Accel, handle=46
W/Settings( 5909): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5909): startup - clean
D/ChimeraCfgMgr( 4342): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4342): Module APK com.google.android.play.games already loaded
,I/art     ( 5909): CheckpointMarkThreadRoots callback created = 0xaaf49ba0
I/Babel   ( 5909): deleted: false for 0
I/art     ( 5909): CheckpointMarkThreadRoots callback created = 0xaaf49b80
,D/UEI.SmartControl( 5881):  ---- Has DB8: true
,D/UEI.SmartControl( 5881): QS start statue = true Error code = 0
D/UEI.SmartControl( 5881): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5881): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5881): IRRCDataComm has AudioManager!!!!.
,I/CalendarProvider2( 5844): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/AudioCapabilities( 5909): Unsupported mime audio/x-lg-flac
W/ContentResolver( 5844): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
W/AudioCapabilities( 5909): Unsupported mime audio/adpcm
I/ActivityManager(  968): Killing 5609:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/irrc_jni( 5881): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5881): IrrcClient ++ 
W/AudioCapabilities( 5909): Unsupported mime audio/g726
D/irrcClient( 5881): getIrrcService ++ 
D/irrcClient( 5881): getIrrcService -- 
D/irrcClient( 5881): IrrcClient -- 
W/irrc_jni( 5881): IRRCPlayer_nativeInit -- 
W/AudioCapabilities( 5909): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5909): Unsupported mime audio/wma-voice
D/UEI.SmartControl( 5881): Services init done
W/VideoCapabilities( 5909): Unsupported mime video/mjpg
I/UEI.SmartControl( 5881): Device manager: loading config....
W/VideoCapabilities( 5909): Unsupported mime video/theora
,D/UEI.SmartControl( 5881): Config is loaded...
W/AudioCapabilities( 5909): Unsupported mime audio/evrc
,W/AudioCapabilities( 5909): Unsupported mime audio/qcelp
W/VideoCapabilities( 5909): Unrecognized profile 2130706433 for video/avc
D/UEI.SmartControl( 5881):  ----- QS SDK is ready!!!
W/AudioCapabilities( 5909): Unsupported mime audio/amr-wb-plus
I/UEI.SmartControl( 5881): Notify AllClients services are ready: 0
W/AudioCapabilities( 5909): Unsupported mime audio/qcelp
W/AudioCapabilities( 5909): Unsupported mime audio/evrc
W/VideoCapabilities( 5909): Unsupported mime video/mp4v-esdp
,W/libprocessgroup(  968): failed to open /acct/uid_10011/pid_5609/cgroup.procs: No such file or directory
D/UEI.SmartControl( 5881): QS Service init finished
D/UEI.SmartControl( 5881): QS Service version name: 0.1.73
D/UEI.SmartControl( 5881): QS Service version code: 1073
D/UEI.SmartControl( 5881): Service requested: Control
D/UEI.SmartControl( 5881): Internal service binding...
D/UEI.SmartControl( 5881): -----IControl: 11
,D/UEI.SmartControl( 5881): Caller: com.lge.qremote
D/UEI.SmartControl( 5881): ------------ IControl registerCallback...
I/UEI.SmartControl( 5881): Registering callback...
D/UEI.SmartControl( 5881): -----IControl: 19
D/UEI.SmartControl( 5881): Caller: com.lge.qremote
I/UEI.SmartControl( 5881): Registering Services Ready callback...
I/UEI.SmartControl( 5881): Notify client services are ready...
I/VideoCapabilities( 5909): Unsupported profile 4 for video/mp4v-es
D/UEI.SmartControl( 5881): -----IControl: 8
D/UEI.SmartControl( 5881): Caller: com.lge.qremote
W/VideoCapabilities( 5909): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  968): Killing 5653:com.android.contacts/u0a18 (adj 15): empty #11
,W/VideoCapabilities( 5909): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5909): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5909): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  968): Killing 5626:com.android.gallery3d/u0a23 (adj 15): empty #12
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
W/libprocessgroup(  968): failed to open /acct/uid_10023/pid_5626/cgroup.procs: No such file or directory
,W/libprocessgroup(  968): failed to open /acct/uid_10018/pid_5653/cgroup.procs: No such file or directory
I/Icing   ( 4342): Internal init done: storage state 0
,I/Icing   ( 4342): Post-init done
I/vclib   ( 5909): onServiceConnected
,W/Babel   ( 5909): Attempted to change video mute state without an active call.
W/ResourcesManager( 5909): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5909): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  968): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5948 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,V/JNIHelp ( 5909): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppUp4:AppBoxCP( 5948): onCreate
W/AppUp4:DB( 5948):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5948):  setFingerPrint start
I/AppUp4:DB( 5948):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5948):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5948):  SDK version = 0
I/AppUp4:DB( 5948):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5948): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 5948): onReceive
I/AppUp4:CustModeStarterReceiver( 5948): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 5948): Context : android.app.ReceiverRestrictedContext@224d10b0
D/AppUp4:CustFacade( 5948): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5948): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 5948): begin check event
I/AppUp4:CustModeStarterReceiver( 5948): Event For Nothing, skip.
I/ActivityManager(  968): Killing 5675:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
W/art     ( 5909): Suspending all threads took: 6.222ms
,W/System  ( 5909): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5909): Installed default security provider GmsCore_OpenSSL
,W/libprocessgroup(  968): failed to open /acct/uid_10069/pid_5675/cgroup.procs: No such file or directory
,I/ActivityManager(  968): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5969 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/NotificationManager( 5909): com.google.android.talk: cancel(8) by com.google.android.talk
I/NotificationManager( 5909): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 5969): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5969): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 5969): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 5969): Total System Memory = 906309632
I/GalleryUtils( 5969): Application Heap = 96 MB
I/AppConfig( 5969): App Tier : NOT_DEF
,D/SystemHelper( 5969): region [EU], country [EU], operator [OPEN], sub-operator []
I/ActivityManager(  968): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5989 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  968): Killing 5693:com.lge.eula/1000 (adj 15): empty #11
,W/libprocessgroup(  968): failed to open /acct/uid_1000/pid_5693/cgroup.procs: No such file or directory
,W/ResourcesManager( 5989): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5989): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5989): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5989): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5989): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 5989): BUILD Country: EU
I/SystemConfig( 5989): BUILD Operator: OPEN
,I/ActivityManager(  968): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6011 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  968): Killing 5710:com.lge.bnr/1000 (adj 15): empty #11
W/libprocessgroup(  968): failed to open /acct/uid_1000/pid_5710/cgroup.procs: No such file or directory
,I/SystemConfig( 5989): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5989): existFile = false
I/SystemConfig( 5989): canReadFile = false
I/SystemConfig( 5989): systemFeature RCS result false
D/SystemConfig( 5989): refreshRcsSupport() :false
I/LockScreenSettings( 6011): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6011): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6011): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6011): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6011): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6011): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  968): Killing 5727:com.google.android.apps.docs/u0a58 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1939): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/UpdateIcingCorporaServi( 1939): UpdateCorporaTask done [took 57 ms] updated apps [took 57 ms] 
,W/libprocessgroup(  968): failed to open /acct/uid_10058/pid_5727/cgroup.procs: No such file or directory
D/PackageBroadcastService( 4342): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/AudioManager( 5329): getMode name:com.lge.qremote
I/PackageBroadcastService( 4342): Null package name or gms related package.  Ignoreing.
I/Icing   ( 4342): updateResources: need to parse f{com.google.android.gms}
,I/AudioManager( 5329): getMode name:com.lge.qremote
I/ActivityManager(  968): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6036 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Icing   ( 4342): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 4342): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 4342): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,W/ActivityManager(  968): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6036): getAccountsCursor
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6036): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  968): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6036): Error finding the version of the Email provider.....
E/Gmail   ( 6036): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6036): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6036): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6036): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6036): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6036): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6036): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6036): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6036): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6036): getAccountsCursor
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  968): Killing 5844:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  968): failed to open /acct/uid_10014/pid_5844/cgroup.procs: No such file or directory
W/ActivityManager(  968): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager(  968): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6036): Observing account changes for notifications
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     (  968): Explicit concurrent mark sweep GC freed 17084(775KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.115ms total 144.890ms
,I/Gmail   ( 6036): notifyAccountChanged
I/Gmail   ( 6036): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6036): getAccountsCursor
I/Gmail   ( 6036): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6036): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6036): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/ActivityManager(  968): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6094 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6036): getAccountsCursor
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PhoneMonitor( 6094): Register our PhoneStateListener
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
V/SetupWizard( 6094): Connected to Gservices successfully
,I/ActivityManager(  968): Killing 5948:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/PhoneMonitor( 6094): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6094): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6094): [parse] Load xml
V/TelephonyAutoProfiling( 6094): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6094): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6094): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  968): failed to open /acct/uid_10011/pid_5948/cgroup.procs: No such file or directory
,I/ActivityManager(  968): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6115 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GCM     ( 1729): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,W/ResourcesManager( 6115): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/CalendarApplication( 6115): CalendarApplication.onCreate()
,I/Icing   ( 4342): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
I/Icing   ( 4342): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
D/PreferenceKeysParser( 6115): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6115): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@3260cbf3, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@224d10b0, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@2e05eb29, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@30e1ceae, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@25b2344f, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1cea87dc, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@356910e5, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@370027ba, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2b07c66b, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@128645c8, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@d1ed661, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@2b790586, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@2dda5e47, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@9df674, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@3611779d, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@384ff412, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@2e5497e3, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@1cde05e0, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1b92f099, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@32353f5e, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3aaecf3f, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@94da00c, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@3218fd55, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@3691f36a, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@224b205b, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1f3ab0f8, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@5b919d1, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@1e53dc36, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@3e916737, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3ce5e4a4, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@3464820d, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@117985c2, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@2d8b3fd3, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@1eea710, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@fe43209, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@75e3c0e, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1a40062f, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@267f243c, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2394e5c5, lg_preference_defaultCalendar=com.and,roid.calendar.adaptation.PreferenceKey$KeyData@3fc60b1a, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@2ed0d64b, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@193848
D/GeneralPreferenceUtils( 6115): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6115): [init]
I/Config  ( 6115): LGCalendar ver.4.40.17
I/Config  ( 6115): start check model
I/Config  ( 6115): start check native_ca
I/Config  ( 6115): Config Operator=OPEN, Country=EU
D/Config  ( 6115): [setDefaultValuesToPref]
D/Config  ( 6115): [parseProfiles]
D/ProfilesParser( 6115): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6115): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6115): [updateProfiletoCountryInfo]
D/GeneralPreference( 6115): [checkAndMigrateOldPreference]
D/AlertReceiver( 6115): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/InitNotificationRingtoneService( 6115): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 6115): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
,I/AlertUtils( 6115): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6115): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6115): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6115): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6115): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 6115): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6115): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6115): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 6115): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 6115): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6115): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 6115): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6115): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6115): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 6115): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6115): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6115): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6115): set default noti to content://media/internal/audio/media/38
,I/InitNotificationRingtoneService( 6115): End InitializeAlertRingtoneService.onHandleIntent
,W/HolidayIntentService( 6115): onHandleIntent
,D/HolidayDataLoader( 6115): readJsonAsset : holiday.json
D/AlertService( 6115): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6115): [updateWidgets] 
,D/MonthWidgetProvider( 6115): [onReceive]
D/CalendarWidgetProvider( 6115): [onReceive]
D/CalendarWidgetProvider( 6115): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
,D/CalendarTypeController( 6115): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6115): [onReceive]
D/CalendarWidgetProvider( 6115): [onReceive]
D/CalendarWidgetProvider( 6115): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
I/AudioManager( 5329): getMode name:com.lge.qremote
D/CalendarTypeController( 6115): [onCreate] mContext.getPackageName() = com.android.calendar
I/AudioManager( 5329): getMode name:com.lge.qremote
,I/AudioManager( 5329): getMode name:com.lge.qremote
E/HolidayIntentService( 6115): onHandleIntent:holiday data empty
I/AudioManager( 5329): getMode name:com.lge.qremote
,I/AudioManager( 5329): getMode name:com.lge.qremote
V/AlarmManager(  968): ELAPSED_WAKEUP set : Alarm{d222054 type 2 when 90154 com.android.providers.calendar} when 90154
,I/ActivityManager(  968): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6152 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  303): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 281us total 51.868ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 263us total 32.170ms
,I/art     (  303): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 265us total 24.513ms
,W/ResourcesManager( 6152): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
D/CalendarProvider2( 6152): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3576e92d
,D/CalendarProvider2( 6152): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6152): Created com.android.providers.calendar.CalendarAlarmManager@30e1ceae(com.android.providers.calendar.CalendarProvider2@3576e92d)
D/CalendarProviderBroadcastReceiver( 6152): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,D/CalendarProviderBroadcastReceiver( 6152): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6152): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6152): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6152): [getOrCreateCalendarAlarmManager]
D/CalendarProvider2( 6152): [IntentService] Release Lock
,D/CalendarProvider2( 6152): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  968): Killing 5969:com.android.gallery3d/u0a23 (adj 15): empty #11
W/libprocessgroup(  968): failed to open /acct/uid_10023/pid_5969/cgroup.procs: No such file or directory
,I/ActivityManager(  968): Killing 5989:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  968): failed to open /acct/uid_10018/pid_5989/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 5881): Internal timer expired: 1
,I/ActivityManager(  968): Killing 5909:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  968): failed to open /acct/uid_10061/pid_5909/cgroup.procs: No such file or directory
,I/[SystemUI]QPairHandler( 1369): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  968): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager(  968): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6180 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/[SystemUI]QSlideListController( 1369): onReceive = android.intent.action.PACKAGE_CHANGED
,D/administrator(  968): Handling package changes for user 0
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
,W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1369): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1369): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,W/ResourcesManager( 6180): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1873): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/NotificationService(  968): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  968): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  968): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  968): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  968): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  968): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@1762f998
,W/ResourcesManager(  968): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  968): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/Babel_SMS( 6180): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6180): MmsConfig.loadMmsSettings
,I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/Babel_SMS( 6180): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6180): MmsConfig.loadFromDatabase
I/GCoreNlp( 1729): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,E/Babel_SMS( 6180): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6180): MmsConfig.loadFromResources
E/Babel_SMS( 6180): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6180): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/LocationProviderProxy(  968): applying state to connected service
,D/LCardEmulationManager( 1782): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1782): getDefaultRoute
,D/SensorManager( 6180): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6180): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6180): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6180): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6180): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6180): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6180): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6180): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6180): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6180): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6180): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6180): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6180): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6180): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6180): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6180): found sensor: Motion Accel, handle=46
W/Settings( 6180): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6180): startup - clean
I/art     ( 6180): CheckpointMarkThreadRoots callback created = 0xb042d8c0
,I/Babel   ( 6180): deleted: false for 0
,I/art     ( 6180): CheckpointMarkThreadRoots callback created = 0xb042d8a0
W/AudioCapabilities( 6180): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6180): Unsupported mime audio/adpcm
W/AudioCapabilities( 6180): Unsupported mime audio/g726
,W/AudioCapabilities( 6180): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6180): Unsupported mime audio/wma-voice
I/ActivityManager(  968): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6226 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/VideoCapabilities( 6180): Unsupported mime video/mjpg
,W/VideoCapabilities( 6180): Unsupported mime video/theora
W/AudioCapabilities( 6180): Unsupported mime audio/evrc
W/AudioCapabilities( 6180): Unsupported mime audio/qcelp
,W/VideoCapabilities( 6180): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6180): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6180): Unsupported mime audio/qcelp
W/AudioCapabilities( 6180): Unsupported mime audio/evrc
,W/VideoCapabilities( 6180): Unsupported mime video/mp4v-esdp
,I/AppUp4:AppBoxCP( 6226): onCreate
,W/AppUp4:DB( 6226):  [AppBoxDatabaseHelper] construct
I/VideoCapabilities( 6180): Unsupported profile 4 for video/mp4v-es
I/AppUp4:DB( 6226):  setFingerPrint start
I/AppUp4:DB( 6226):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
W/VideoCapabilities( 6180): Unrecognized profile 2130706433 for video/avc
I/AppUp4:DB( 6226):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 6226):  SDK version = 0
I/AppUp4:DB( 6226):  beforefinger == newfinger no write in DB
W/VideoCapabilities( 6180): Unrecognized profile 2130706433 for video/avc
D/AppUp4:AppBoxApplication( 6226): AppBoxApplication onCreate()
W/VideoCapabilities( 6180): Unrecognized profile 2130706433 for video/avc
I/AppUp4:CustModeStarterReceiver( 6226): onReceive
I/AppUp4:CustModeStarterReceiver( 6226): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
W/VideoCapabilities( 6180): Unrecognized profile 2130706433 for video/avc
D/AppUp4:CustFacade( 6226): Context : android.app.ReceiverRestrictedContext@224d10b0
D/AppUp4:CustFacade( 6226): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6226): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6226): begin check event
,I/AppUp4:CustModeStarterReceiver( 6226): Event For Nothing, skip.
I/ActivityManager(  968): Killing 6011:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 93061571115; DSPS: 3140829; Offset : -2798339597
,W/libprocessgroup(  968): failed to open /acct/uid_10069/pid_6011/cgroup.procs: No such file or directory
I/GAV2    ( 6036): Thread[GAThread,5,main]: No campaign data found.
,I/ActivityManager(  968): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6257 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/vclib   ( 6180): onServiceConnected
W/Babel   ( 6180): Attempted to change video mute state without an active call.
I/NotificationManager( 6180): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6180): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6180): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6257): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6257): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6257): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,V/JNIHelp ( 6180): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
D/Finsky  ( 5797): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,V/AlarmManager(  968): RTC_WAKEUP set : Alarm{969d041 type 0 when 1457013527672 com.android.vending} when 1457013527672
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AppConfig( 6257): Total System Memory = 906309632
,I/NotificationManager(  968): android: cancelAsUser(2) by android
I/GalleryUtils( 6257): Application Heap = 96 MB
W/System  ( 6180): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6180): Installed default security provider GmsCore_OpenSSL
I/AppConfig( 6257): App Tier : NOT_DEF
D/SystemHelper( 6257): region [EU], country [EU], operator [OPEN], sub-operator []
I/NotificationManager( 6180): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/art     (  968): Explicit concurrent mark sweep GC freed 21335(1074KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.466ms total 143.116ms
I/art     (  968): WaitForGcToComplete blocked for 81.279ms for cause HeapTrim
,I/ActivityManager(  968): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6281 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
D/libc-netbsd( 5797): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5797): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/ResourcesManager( 6281): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6281): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6281): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
D/libc-netbsd( 5797): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5797): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
W/ResourcesManager( 6281): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
W/ResourcesManager( 6281): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 5797): propertyValue:false
D/libc-netbsd( 5797): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5797): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/SystemConfig( 6281): BUILD Country: EU
I/SystemConfig( 6281): BUILD Operator: OPEN
,I/ActivityManager(  968): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6301 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  968): Killing 5759:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  968): failed to open /acct/uid_10086/pid_5759/cgroup.procs: No such file or directory
,I/SystemConfig( 6281): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6281): existFile = false
I/SystemConfig( 6281): canReadFile = false
I/SystemConfig( 6281): systemFeature RCS result false
D/SystemConfig( 6281): refreshRcsSupport() :false
I/LockScreenSettings( 6301): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6301): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6301): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 6301): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6301): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6301): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  968): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6324 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  968): Killing 6094:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  968): failed to open /acct/uid_10038/pid_6094/cgroup.procs: No such file or directory
W/ResourcesManager( 6324): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AlertService( 6115): Beginning updateAlertNotification
,D/AlertService( 6115): No fired or scheduled alerts
I/NotificationManager( 6115): com.android.calendar: cancel(0) by com.android.calendar
,I/NotificationManager( 6115): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6115): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6115): com.android.calendar: cancel(3) by com.android.calendar
,I/NotificationManager( 6115): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6115): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6115): com.android.calendar: cancel(6) by com.android.calendar
,I/NotificationManager( 6115): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6115): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6115): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6115): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6115): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6115): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6115): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6115): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6115): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6115): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6115): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6115): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6115): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6115): com.android.calendar: cancel(20) by com.android.calendar
D/libc-netbsd( 5797): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5797): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/AlertService( 6115): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 6115): No events found starting within 1 week.
,I/ActivityManager(  968): Killing 6115:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  968): failed to open /acct/uid_10013/pid_6115/cgroup.procs: No such file or directory
,I/UpdateIcingCorporaServi( 1939): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  968): Killing 6036:com.google.android.gm/u0a53 (adj 15): empty #11
I/UpdateIcingCorporaServi( 1939): UpdateCorporaTask done [took 41 ms] updated apps [took 40 ms] 
,W/libprocessgroup(  968): failed to open /acct/uid_10053/pid_6036/cgroup.procs: No such file or directory
,D/PackageBroadcastService( 4342): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4342): Null package name or gms related package.  Ignoreing.
I/Icing   ( 4342): updateResources: need to parse f{com.google.android.gms}
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  968): android: cancelAsUser(2) by android
,I/qtaguid ( 5797): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5797): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5797): untagSocket(41) failed with errno -22
D/Finsky  ( 5797): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  968): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6360 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/NotificationManager(  968): android: cancelAsUser(2) by android
,W/ResourcesManager( 6360): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6360): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6360): VM with version 2.1.0 has multidex support
I/MultiDex( 6360): install
,I/MultiDex( 6360): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6360): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6360): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6360): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@36c1f440: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6360): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6360): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6360): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1729): callingUid 10006, callindPid: 1729
,E/MDM     ( 1729): [129] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1729): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4342): Restart initialization of location
D/ChimeraCfgMgr( 6360): Reading stored module config
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1729): com.google.android.gms: cancel(0) by com.google.android.gms
,D/ChimeraCfgMgr( 6360): Loading module com.google.android.gms.car from APK com.google.android.gms
W/GCoreFlp( 1729): No location to return for getLastLocation()
,W/FusedLocationProvider( 1729): location=null
,I/qtaguid ( 5797): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5797): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5797): untagSocket(41) failed with errno -22
D/CAR.SERVICE( 6360): Connecting to CarCallService...
I/art     ( 6360): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6360): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6360): Install completed successfully. count=14 extracted=0
D/CAR.SERVICE( 6360): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6360): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6360): Creating a new PhoneAdapter instance
W/ActivityManager(  968): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6360): setListener: com.google.android.gms.car.dn@5c480f
W/ActivityManager(  968): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6360): Returning an existing PhoneAdapter instance.
,D/CAR.TEL.Service( 6360): Starting CarCallService with initial phone null
I/NotificationManager( 6360): com.google.android.gms: cancel(10436) by com.google.android.gms
,D/CAR.SERVICE( 6360): Package validated; name: com.android.vending
,I/NotificationManager( 5797): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5797): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/art     ( 5797): CheckpointMarkThreadRoots callback created = 0xb05864a0
,I/art     ( 5797): CheckpointMarkThreadRoots callback created = 0xb0586460
,I/Icing   ( 4342): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4342): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  968): android: cancelAsUser(2) by android
,I/qtaguid ( 5797): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5797): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5797): untagSocket(41) failed with errno -22
,W/ResourcesManager( 5797): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5797): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5797): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5797): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  968): RTC_WAKEUP set : Alarm{2456b7d7 type 0 when 1457013531371 com.android.vending} when 1457013531371
,D/Finsky  ( 5797): [689] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 1729): client connected with version: 8296000
V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  968): android: cancelAsUser(2) by android
,D/Finsky  ( 5797): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/Finsky  ( 5797): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
D/libc-netbsd( 5797): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5797): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5797): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5797): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  274): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
,I/System.out( 5797): propertyValue:false
I/ActivityManager(  968): Killing 5881:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5329): android.os.DeadObjectException
,W/System.err( 5329): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5329): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5329): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5329): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5329): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5329): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5329): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5329): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 5329): 	at android.os.Looper.loop(Looper.java:135)
,W/System.err( 5329): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5329): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5329): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5329): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5329): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5329): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5329): android.os.DeadObjectException
W/System.err( 5329): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5329): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5329): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5329): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5329): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5329): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5329): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5329): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5329): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5329): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5329): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5329): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5329): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5329): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5329): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  968): failed to open /acct/uid_10089/pid_5881/cgroup.procs: No such file or directory
W/ActivityManager(  968): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  968): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6417 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6417): Quickset Services start...
,I/UEI.SmartControl( 6417): Manufacture = LGE
D/UEI.SmartControl( 6417): File observer start...
E/UEI.SmartControl( 6417): IR Port is disabled: false
D/UEI.SmartControl( 6417): Starting file observer...
D/UEI.SmartControl( 6417): Extracting JNI libs...
D/UEI.SmartControl( 6417): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6417): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6417): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6417): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 6417): --- Selecting new region: 2
,I/UEI.SmartControl( 6417): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6417): Platform has CIR...
D/UEI.SmartControl( 6417): NO CIR support, need to check package...
I/UEI.SmartControl( 6417): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6417): QS Service created
E/UEI.SmartControl( 6417): QS start get config
,D/UEI.SmartControl( 6417): Loading JNI Libs...
,D/UEI.SmartControl( 6417):  configuring local db...
D/UEI.SmartControl( 6417):  ---- Has DB8: true
,D/UEI.SmartControl( 6417): QS start statue = true Error code = 0
D/UEI.SmartControl( 6417): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6417): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6417): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6417): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6417): IrrcClient ++ 
D/irrcClient( 6417): getIrrcService ++ 
D/irrcClient( 6417): getIrrcService -- 
D/irrcClient( 6417): IrrcClient -- 
W/irrc_jni( 6417): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6417): Services init done
,D/UEI.SmartControl( 6417): QS Service init finished
I/UEI.SmartControl( 6417): Device manager: loading config....
D/UEI.SmartControl( 6417): QS Service version name: 0.1.73
D/UEI.SmartControl( 6417): QS Service version code: 1073
D/UEI.SmartControl( 6417): Service requested: Control
D/UEI.SmartControl( 6417): Config is loaded...
D/UEI.SmartControl( 6417):  ----- QS SDK is ready!!!
,I/UEI.SmartControl( 6417): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6417): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6417): -----IControl: 11
D/UEI.SmartControl( 6417): Caller: com.lge.qremote
D/UEI.SmartControl( 6417): ------------ IControl registerCallback...
I/UEI.SmartControl( 6417): Registering callback...
I/ActivityManager(  968): Killing 6152:com.android.providers.calendar/u0a14 (adj 15): empty #11
D/UEI.SmartControl( 6417): -----IControl: 19
D/UEI.SmartControl( 6417): Caller: com.lge.qremote
I/UEI.SmartControl( 6417): Registering Services Ready callback...
I/UEI.SmartControl( 6417): Notify client services are ready...
D/UEI.SmartControl( 6417): -----IControl: 8
D/UEI.SmartControl( 6417): Caller: com.lge.qremote
W/libprocessgroup(  968): failed to open /acct/uid_10014/pid_6152/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 6417): Internal service binding...
I/AudioManager( 5329): getMode name:com.lge.qremote
I/AudioManager( 5329): getMode name:com.lge.qremote
,I/ActivityManager(  968): Killing 6226:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  968): failed to open /acct/uid_10011/pid_6226/cgroup.procs: No such file or directory
,I/AudioManager( 5329): getMode name:com.lge.qremote
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ActivityManager(  968): Killing 6180:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  968): failed to open /acct/uid_10061/pid_6180/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 6360): mConnectedToCar = false, abort
,E/ActivityThread( 6360): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3062cd17 that was originally bound here
E/ActivityThread( 6360): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@3062cd17 that was originally bound here
E/ActivityThread( 6360): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6360): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6360): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6360): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6360): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6360): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6360): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6360): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6360): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6360): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6360): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6360): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6360): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6360): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6360): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6360): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6360): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6360): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6360): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6360): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6360): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6360): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6360): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6360): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1bdcd96e that was originally bound here
E/ActivityThread( 6360): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@1bdcd96e that was originally bound here
E/ActivityThread( 6360): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6360): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6360): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6360): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6360): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6360): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6360): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6360): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6360): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6360): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6360): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6360): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6360): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6360): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6360): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6360): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6360): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6360): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6360): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6360): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6360): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6360): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  968): Unbind failed: could not find connection for android.os.BinderProxy@347f7606
I/rmt_storage(  268): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  268): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  268): wakelock acquired: 1, error no: 42
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  268): 
I/rmt_storage(  268): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
D/UEI.SmartControl( 6417): Internal timer expired: 1
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,W/SQLiteConnectionPool( 4342): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/PowerManagerServiceEx(  968): acquireWakeLockInternal: lock=1054819527, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=968
,D/WeatherService( 2616): 2 : TimeTick Intent has been received, Time(hour:min:sec) 14:59:0
,D/WeatherService( 2616): 2 : TimeTick Intent And Screen On
D/WeatherService( 2616): 2 : SDK version : 21
W/ActivityManager(  968): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2616): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2616): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2616): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2616): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2616): 2 : This is isUpdating : false
D/WeatherService( 2616): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2616): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2616): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2616): 2 : Fixed theme : optimus
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/WeatherReflect( 2616): 2 : Map key string is -2
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
D/lim     ( 2616): 2 : time = 14:59
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/WeatherReflect( 2616): Model Name : LG-D722
D/WeatherTheme( 2616): 2 : Different view - status_min_formatted : 58 != 59
D/WeatherTheme( 2616): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/WeatherReflect( 2616): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2616): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2616): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2616): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2616): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/[SystemUI]DateView( 1369): called onTimeUpdated()
,D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/Weather4x2_optimus( 2616): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2616): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2616): forecast size is 0
D/Theme   ( 2616): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2616): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2616): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2616): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2616): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2616): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2616): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2616): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2616): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2616): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2616): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2616): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2616): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2616): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2616): setTouchIntent, appWidgetId: 2
,D/Theme_WeatherAncestor_optimus( 2616): url is : null
D/Theme   ( 2616): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2616): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2616): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2616): 2 : update view, appWidgetId: 2
D/WeatherService( 2616): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 14:59:0
,D/PowerManagerServiceEx(  968): releaseWakeLockInternal: lock=1054819527 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1873): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1873): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,V/AlarmManager(  968): RTC_WAKEUP set : Alarm{bd021d type 0 when 1457013545025 com.android.vending} when 1457013545025
,W/ContextImpl( 3688): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,D/Finsky  ( 5797): [680] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5797): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 113062881577; DSPS: 3796232; Offset : -2798341026
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/MusicWidget( 2521): mDelayedStopHandler : unbind
,I/MusicBrowser( 2645): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2645): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2645): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2645): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2645): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2645): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2645): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2645): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  968):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3218fd55com.lge.music.MediaPlaybackService$6@3691f36a
,D/MusicBrowser( 2645): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2645): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2645): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2645): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2645): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@2b07c66b
,I/MusicBrowser( 2645): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2645): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2645): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2645): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2645): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2645): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2645): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2645): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2645): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2645): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2645): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2645): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2645): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2645): reset
V/MediaPlayer[Native]( 2645): setListener
V/MediaPlayer[Native]( 2645): disconnect
V/MediaPlayer[Native]( 2645): destructor
,V/AudioFlinger(  278): releasing 19 from 2645 for -1
V/AudioFlinger(  278):  decremented refcount to 0
V/AudioFlinger(  278): purging stale effects
V/MediaPlayer[Native]( 2645): disconnect
D/MusicBrowser( 2645): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2645): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2645): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2645): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2645): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2645): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
,I/SmartShareClient( 2645): [SmartShareManagerClient] unregisterListener: 575348827
W/SmartShareClient( 2645): [SmartShareManagerClient] unregisterListener invalid listener: 575348827
I/SmartShareClient( 2645): [SmartShareManagerClient] terminate service: 2645/MediaPlaybackService/772139817
E/HomeCloudIF( 2645): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2645): [SmartShareManagerClient] unbindService context:android.app.Application@1f3ab0f8
,V/CloudHub( 2645): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2645): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2645): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2645): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2645): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  968): Killing 6257:com.android.gallery3d/u0a23 (adj 15): empty #11
,I/CloudHub( 2645): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29993
W/libprocessgroup(  968): failed to open /acct/uid_10023/pid_6257/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/CloudHub( 2645): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19952
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 291, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 133065173978; DSPS: 4451667; Offset : -2798337755
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/CloudHub( 2645): [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
I/CloudHub( 2645): [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/PowerManagerService(  968): ALS enabled for SRE
D/PowerManagerServiceEx(  968): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (27828 ms ago)
,D/qdlights(  968): set_light_backlight: 254
,D/qdlights(  968): set_light_backlight: 251
,D/qdlights(  968): set_light_backlight: 248
,D/qdlights(  968): set_light_backlight: 244
,D/qdlights(  968): set_light_backlight: 241
,D/qdlights(  968): set_light_backlight: 238
,D/qdlights(  968): set_light_backlight: 234
,D/qdlights(  968): set_light_backlight: 231
,D/qdlights(  968): set_light_backlight: 228
,D/qdlights(  968): set_light_backlight: 224
,D/qdlights(  968): set_light_backlight: 221
,D/qdlights(  968): set_light_backlight: 218
,D/qdlights(  968): set_light_backlight: 214
,D/qdlights(  968): set_light_backlight: 211
,D/qdlights(  968): set_light_backlight: 208
,D/qdlights(  968): set_light_backlight: 204
,D/qdlights(  968): set_light_backlight: 201
,D/qdlights(  968): set_light_backlight: 198
,D/qdlights(  968): set_light_backlight: 194
,D/qdlights(  968): set_light_backlight: 191
,D/qdlights(  968): set_light_backlight: 188
,D/qdlights(  968): set_light_backlight: 184
,D/qdlights(  968): set_light_backlight: 181
,D/qdlights(  968): set_light_backlight: 178
,D/qdlights(  968): set_light_backlight: 174
,D/qdlights(  968): set_light_backlight: 171
,D/qdlights(  968): set_light_backlight: 168
,D/qdlights(  968): set_light_backlight: 164
,D/qdlights(  968): set_light_backlight: 161
,D/qdlights(  968): set_light_backlight: 158
,D/qdlights(  968): set_light_backlight: 154
,D/qdlights(  968): set_light_backlight: 151
,D/qdlights(  968): set_light_backlight: 148
,D/qdlights(  968): set_light_backlight: 144
,D/qdlights(  968): set_light_backlight: 141
,D/qdlights(  968): set_light_backlight: 138
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
D/qdlights(  968): set_light_backlight: 134
,D/qdlights(  968): set_light_backlight: 131
,D/qdlights(  968): set_light_backlight: 128
,D/qdlights(  968): set_light_backlight: 124
,D/qdlights(  968): set_light_backlight: 121
,D/qdlights(  968): set_light_backlight: 118
,D/qdlights(  968): set_light_backlight: 114
,D/qdlights(  968): set_light_backlight: 111
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/qdlights(  968): set_light_backlight: 108
,D/qdlights(  968): set_light_backlight: 104
,D/qdlights(  968): set_light_backlight: 101
,D/qdlights(  968): set_light_backlight: 98
,D/qdlights(  968): set_light_backlight: 94
,D/qdlights(  968): set_light_backlight: 91
,D/qdlights(  968): set_light_backlight: 88
,D/qdlights(  968): set_light_backlight: 84
,D/qdlights(  968): set_light_backlight: 81
,D/qdlights(  968): set_light_backlight: 78
,D/qdlights(  968): set_light_backlight: 74
,D/qdlights(  968): set_light_backlight: 71
,D/qdlights(  968): set_light_backlight: 68
,D/qdlights(  968): set_light_backlight: 64
,D/qdlights(  968): set_light_backlight: 61
,D/qdlights(  968): set_light_backlight: 58
,D/qdlights(  968): set_light_backlight: 54
,D/qdlights(  968): set_light_backlight: 51
,D/qdlights(  968): set_light_backlight: 48
,D/qdlights(  968): set_light_backlight: 44
,D/qdlights(  968): set_light_backlight: 41
,D/qdlights(  968): set_light_backlight: 38
,D/qdlights(  968): set_light_backlight: 34
,D/qdlights(  968): set_light_backlight: 31
,D/qdlights(  968): set_light_backlight: 28
,D/qdlights(  968): set_light_backlight: 24
,D/qdlights(  968): set_light_backlight: 21
,D/qdlights(  968): set_light_backlight: 18
,D/qdlights(  968): set_light_backlight: 14
,D/qdlights(  968): set_light_backlight: 11
,D/qdlights(  968): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1369): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 153066733048; DSPS: 5107078; Offset : -2798334901
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/PowerManagerService(  968): ALS enabled for SRE
D/PowerManagerServiceEx(  968): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (34812 ms ago)
I/PowerManagerService(  968): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  968): ALS enabled for SRE
D/PowerManagerServiceEx(  968): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (34824 ms ago)
W/ContextImpl(  968): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  968): Sleeping (uid 1000)...
D/LPWGController(  968): [updateScreenState] screen on = false
D/LPWGController(  968): disable proximity sensor
D/LPWGController(  968): enable proximity sensor
I/SensorManager(  968): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@268cec92] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  968): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  968): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  968): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  968): activate: handle is 48, enable
V/sensors_hal_Ctx(  968): activate sensors is 1400000000000
D/sensors_hal_Thresh(  968): enable: handle=48
I/sensors_hal_SAM(  968): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  968): waitForResponse: timeout=1000
,V/sensors_hal_SAM(  968): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  968): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  968): enable: Received response: 0
D/PowerManagerServiceEx(  968): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (34859 ms ago)
I/Adreno-EGL(  968): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  968): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  968): Build Date: 03/02/15 Mon
I/Adreno-EGL(  968): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  968): Remote Branch: 
I/Adreno-EGL(  968): Local Patches: 
I/Adreno-EGL(  968): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (141 us)
,I/Sensors (  424): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  968): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  968): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
,D/sensors_hal_Thresh(  968): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  968): processInd: handle 48, count=1
V/sensors_hal_Thresh(  968): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  968): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  968): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  968): poll: count: 256
I/sensors_hal_Ctx(  968): poll: released wakelock sensor_ind
D/sensors_hal_Util(  968): waitForResponse: timeout=0
D/LPWGController(  968): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  968): current mode = 1  value = 1 1
,I/LPWGController(  968): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  968): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  968): set_light_backlight: 0
,I/SensorManager(  968): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
I/sensors_hal_Ctx(  968): activate: handle is 46, disable
V/sensors_hal_Ctx(  968): activate sensors is 1000000000000
D/sensors_hal_LP2(  968): enable: handle=46
D/sensors_hal_LP2(  968): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  968): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
,I/DisplayManagerService(  968): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  968): Display changed displayId=0
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
,V/sensors_hal_SAM(  968): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  968): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1748): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  968): Excessive delay in setPowerMode(): 207ms
I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  968): Got set_interactive hint
,D/SmartCoverViewMediator( 1328): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1369): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1328): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1328): handleNotifyScreenOFF
D/KeyguardViewMediator( 1369): notifyScreenOffLocked
D/JX-Cordova( 4792): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4792): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4792): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d87087d added. We now have 3 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4792): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4792): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c2e372 added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4792): addListener: New listener added - the number of listeners is now 1
,D/BluetoothAdapterService(922757050)( 2014): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1cde05e0
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4792): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4792): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 4792): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 4792): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4792): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4792): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4792): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4792): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4792): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4792): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4792): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4792): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4792): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4792): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4792): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/KeyguardViewMediator( 1369): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1369): handleNotifyScreenOff
,D/ScreenTurnOffBySensor( 1369): unregisterProximitySensor
,D/StatusBarWindowView( 1369): onScreenTurnedOff why = 3
D/WifiServerServiceExt(  968): sendKtScanInterval  mRtspPlay : false
,V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=on, calling pid 968
D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=on
V/voice   (  278): voice_set_parameters: enter: screen_state=on
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: exit
V/voice   (  278): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  278): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  278): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  278): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  278): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  278): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/WifiServerServiceExt(  968): set CMD_KT_SCAN_INTERVAL
,D/GpsLocationProvider(  968): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1836): |CORE| sendScreenState: state:true
I/LEDService( 1799): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1799): stopPatternFlashing()
D/qdlights( 1799): set_light_notifications: 0,0,0,0,3
I/LEDService( 1799): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1799): set_light_notifications: 0,0,0,0,3
I/LEDService( 1799): updateLightsLocked : turn off led
D/qdlights( 1799): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1799): RESTART MSG
,D/SplitWindow(  968): check instance of lgWin Window{29aca319 u0 SearchPanel}
,I/Sensors (  424): sns_pwr.c(301):releasing wakelock
I/Cliptray Service( 1799): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1799): lockStatus = 0
D/LNfcService( 1782): action : android.intent.action.SCREEN_ON
D/InputDispatcher(  968): Window went away: Window{8b8a555 u0 SearchPanel}
,I/[SystemUI]Clock( 1369): onReceive = android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1782): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1782): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1782): isRequireNfcCRouting() return true
D/LNfcService( 1782): isHCERoutingtoHost() return : true
D/NfcService( 1782): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1782): mEnableLPD: true
D/NfcService( 1782): mEnableReader: false
D/NfcService( 1782): mEnableHostRouting: true
D/NfcService( 1782): newParams.techmask= mTechMask: default
D/NfcService( 1782): mEnableLPD: true
D/NfcService( 1782): mEnableReader: false
D/NfcService( 1782): mEnableHostRouting: true
D/NfcService( 1782): screenState= 3
D/NfcService( 1782): Discovery configuration equal, not updating.
I/LgeClockWidgetControlView( 1369): time changed, timezoneChanged : false
,D/Ulp_jni (  968): JNI:system_update. Event-0
,V/PhoneApp( 1748): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2616): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:59:51
,D/WeatherService( 2616): 2 : ACTION screen on
D/WeatherService( 2616): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2616): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2616): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:59:51
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  968): ACTION_SCREEN_ON
,D/AppCleanupService( 4168): android.intent.action.SCREEN_ON
V/AudioFlinger(  278): setParameters(): io 0, keyvalue screen_state=off, calling pid 968
,D/audio_hw_primary(  278): adev_set_parameters: enter: screen_state=off
V/voice   (  278): voice_set_parameters: enter: screen_state=off
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  278): voice_extn_compress_voip_set_parameters: exit
V/voice   (  278): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  278): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  278): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  278): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  278): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  278): adev_set_parameters: exit with code(0)
D/WifiController(  968): CMD_SCREEN_OFF 
D/WifiController(  968): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  968): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1836): |CORE| sendScreenState: state:false
I/LEDService( 1799): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1799): stopPatternFlashing()
,D/qdlights( 1799): set_light_notifications: 0,0,0,0,3
I/LEDService( 1799): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1799): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1799): clear
I/LEDService( 1799): updateLightsLocked : turn on led
E/LEDService( 1799): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
I/Cliptray Service( 1799): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
E/LEDService( 1799): Can't handle this request of patternId:0
D/LEDHandler( 1799): RESTART MSG
D/LNfcService( 1782): action : android.intent.action.SCREEN_OFF
,D/NfcServiceNXP( 1782): mScreenState : 1, mInProvisionMode : false
I/[LGHome]EVENT( 1873): [Launcher.java:1711:onReceive()]Screen Off
V/PhoneApp( 1748): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2616): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:59:51
D/WeatherService( 2616): 2 : ACTION screen off
D/WeatherService( 2616): 2 : TimeTick Receiver Unregister
D/WeatherService( 2616): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:59:51
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  968): ACTION_SCREEN_OFF
D/AppCleanupService( 4168): android.intent.action.SCREEN_OFF
,D/AppCleanupService( 4168): AppUsageStatsSaveTask
E/NxpNfcJni( 1782): getReconnectState = 0x0
D/LCardEmulationManager( 1782): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1782): getDefaultRoute
D/LNfcService( 1782): isRequireNfcCRouting() return true
D/LNfcService( 1782): isHCERoutingtoHost() return : true
D/NfcService( 1782): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1782): mEnableLPD: true
D/NfcService( 1782): mEnableReader: false
D/NfcService( 1782): mEnableHostRouting: true
D/NfcService( 1782): newParams.techmask= mTechMask: 0
D/NfcService( 1782): mEnableLPD: true
D/NfcService( 1782): mEnableReader: false
D/NfcService( 1782): mEnableHostRouting: true
D/NfcService( 1782): screenState= 1
,E/NxpNfcJni( 1782): getReconnectState = 0x0
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  968): ELAPSED_WAKEUP set : Alarm{16893fde type 2 when 160710 com.android.systemui} when 160710
,D/KeyguardViewMediator( 1369): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1748): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1748): getCallState : 0
D/PhoneUtils( 1748): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1369): isHdmiPluggedIn :false
,D/KeyguardViewMediator( 1369): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/PowerManagerServiceEx(  968): acquireWakeLockInternal: lock=1054819527, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=968
,V/AlarmManager(  968): ELAPSED_WAKEUP set : Alarm{2d9a05bf type 2 when 140122 com.google.android.gms} when 140122
V/AlarmManager(  968): RTC_WAKEUP set : Alarm{90ed48c type 0 when 1457013602623 com.google.android.gms} when 1457013602623
I/ActivityManager(  968): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6569 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/EventLogService( 4342): Aggregate from 1457013506447 (log), 1457011802525 (data)
,I/DigitalAppWidgetProvider( 6569): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/art     (  968): Explicit concurrent mark sweep GC freed 50061(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 23MB/34MB, paused 3.414ms total 240.052ms
,V/DigitalAppWidgetProvider( 6569): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@224d10b0
D/PowerManagerServiceEx(  968): releaseWakeLockInternal: lock=1054819527 [*alarm*], flags=0x0
I/ActivityManager(  968): Killing 6281:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  968): failed to open /acct/uid_10018/pid_6281/cgroup.procs: No such file or directory
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1729): Vacuum at: now=1457013603239 tag=VacuumService
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 173068214201; DSPS: 5762486; Offset : -2798318592
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  968): ELAPSED_WAKEUP set : Alarm{130f8489 type 2 when 186829 com.google.android.gms} when 186829
,I/PhenotypeConfigurator( 1729): Scheduling Phenotype for one-off execution 3494 seconds from now (1457013621617)
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  968): battery changed pluggedType: 2
D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
,D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 288, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
,I/PhenotypeFlagCommitter( 1729): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1729): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  968): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     ( 1729): Explicit concurrent mark sweep GC freed 51444(3MB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 13MB/23MB, paused 1.558ms total 98.935ms
,D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  274): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  274): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  274): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  274): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  274): default dns: query_ipv6=0, query_ipv4=1, netid=100
,D/libc-netbsd(  274): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  274): res_queryN name = xxxxx succeed
I/System.out( 1729): propertyValue:false
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1729): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1729): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  968): ELAPSED_WAKEUP set : Alarm{2cceb2a7 type 2 when 188816 android} when 188816
,D/LocationManagerService(  968): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  968): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  968): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1729): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/LocationManagerService(  968): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 193080231296; DSPS: 6418240; Offset : -2798327453
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1729): disconnect managed GoogleApiClient
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 213082407253; DSPS: 7073673; Offset : -2798379280
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 228084721409; DSPS: 7565281; Offset : -2798748690
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 242156324378; DSPS: 8026367; Offset : -2798373723
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 262158525752; DSPS: 8681802; Offset : -2798463225
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 275290469295; DSPS: 9112104; Offset : -2798292319
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  968): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 297801729901; DSPS: 9849756; Offset : -2798384642
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 317803916621; DSPS: 10505186; Offset : -2798336028
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 337806007665; DSPS: 11160618; Offset : -2798440244
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/LocationManagerService(  968): remove 251feec0
,D/LocationManagerService(  968): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  968): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  968): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  968): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  968): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  968): acquireWakeLockInternal: lock=1054819527, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=968
,D/PowerManagerServiceEx(  968): releaseWakeLockInternal: lock=1054819527 [*alarm*], flags=0x0
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 352810243486; DSPS: 11652273; Offset : -2798324166
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  968): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 372812477772; DSPS: 12307707; Offset : -2798348233
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 392814645254; DSPS: 12963136; Offset : -2798286569
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 407816938808; DSPS: 13454731; Offset : -2798283525
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 427819037229; DSPS: 14110169; Offset : -2798563886
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 450323982086; DSPS: 14847603; Offset : -2798318789
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 470326118862; DSPS: 15503033; Offset : -2798318191
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 490328375577; DSPS: 16158468; Offset : -2798350268
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 510330691882; DSPS: 16813904; Offset : -2798353326
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 530333069895; DSPS: 17469347; Offset : -2798508271
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 545337797674; DSPS: 17961019; Offset : -2798419268
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 560346422727; DSPS: 18452821; Offset : -2798400068
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 575669764049; DSPS: 18954935; Offset : -2798361760
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 595672162647; DSPS: 19610373; Offset : -2798343715
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 610674107019; DSPS: 20101959; Offset : -2798413557
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 631929821227; DSPS: 20798469; Offset : -2798497478
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 646934444407; DSPS: 21290135; Offset : -2798330049
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 663189844324; DSPS: 21822789; Offset : -2798240060
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 684445207239; DSPS: 22519271; Offset : -2797821150
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 699449668420; DSPS: 23010954; Offset : -2798334203
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 714451619367; DSPS: 23502549; Offset : -2798671891
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 728523011008; DSPS: 23963627; Offset : -2798264450
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 743525400372; DSPS: 24455228; Offset : -2798347035
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 758526920308; DSPS: 24946817; Offset : -2798932394
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 773531762032; DSPS: 25438475; Offset : -2798302463
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 792286280461; DSPS: 26053026; Offset : -2798392239
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 812288326422; DSPS: 26708449; Offset : -2798268758
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 832290559939; DSPS: 27363885; Offset : -2798354654
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 852292605591; DSPS: 28019310; Offset : -2798292722
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 867294832463; DSPS: 28510900; Offset : -2798202056
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 881056472806; DSPS: 28961845; Offset : -2798311005
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 896058669595; DSPS: 29453435; Offset : -2798252217
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 911060884846; DSPS: 29945033; Offset : -2798415488
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 926063335009; DSPS: 30436632; Offset : -2798376292
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 946065633278; DSPS: 31092067; Offset : -2798366816
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  968): acquireWakeLockInternal: lock=1054819527, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=968
,V/AlarmManager(  968): ELAPSED_WAKEUP set : Alarm{248d4f9f type 2 when 951541 com.android.bluetooth} when 951541
D/PowerManagerServiceEx(  968): releaseWakeLockInternal: lock=1054819527 [*alarm*], flags=0x0
,W/bt-smp  ( 2014): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2014): Plain text(LSB ~ MSB) = 49 be 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
W/bt-smp  ( 2014): Encrypted text(LSB ~ MSB) = bf c9 fd fe a0 fd 64 9b 95 0b d9 79 92 52 9b 57 
W/bt-btm  ( 2014): Stopping oneshot timer
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 966071057005; DSPS: 31747602; Offset : -2798283508
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
,W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 981073280721; DSPS: 32239193; Offset : -2798226644
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 996075356934; DSPS: 32730777; Offset : -2798103401
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1009207099852; DSPS: 33161095; Offset : -2798623848
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1030462548225; DSPS: 33857584; Offset : -2798332998
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1050464663897; DSPS: 34513015; Offset : -2798383969
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1070466766795; DSPS: 35168445; Offset : -2798419151
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1092971956070; DSPS: 35905888; Offset : -2798202445
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1106103861117; DSPS: 36336198; Offset : -2798316180
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1119235087149; DSPS: 36766490; Offset : -2798560134
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1139866713949; DSPS: 37442537; Offset : -2798250317
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1159868269223; DSPS: 38097951; Offset : -2798343019
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1179870804102; DSPS: 38753394; Offset : -2798340942
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1199873070780; DSPS: 39408829; Offset : -2798363421
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1219875321004; DSPS: 40064266; Offset : -2798463024
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/UsageStatsService(  968): User[0] Flushing usage stats to disk
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1234877765592; DSPS: 40555863; Offset : -2798370061
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1249880789539; DSPS: 41047485; Offset : -2798456927
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1271136240384; DSPS: 41743980; Offset : -2798346841
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1291138529606; DSPS: 42399418; Offset : -2798437964
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1306140903740; DSPS: 42891009; Offset : -2798230553
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1320684002238; DSPS: 43367564; Offset : -2798436575
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 267
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 267, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 267
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1335686230426; DSPS: 43859154; Offset : -2798344619
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1355688514283; DSPS: 44514587; Offset : -2798288363
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1370690755690; DSPS: 45006186; Offset : -2798457973
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1385693307637; DSPS: 45497783; Offset : -2798255880
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1405695614615; DSPS: 46153221; Offset : -2798329299
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1420697686754; DSPS: 46644810; Offset : -2798362899
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1440699983217; DSPS: 47300243; Offset : -2798293804
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1369): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1369): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1369): On Skip Timer : true
,D/PowerService( 1799): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  482): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2014): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1799): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1799): Battery Level Remaining: 100%
D/LEDHandler( 1799): Battery Temp: 266, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1369): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
I/[SystemUI]LGPowerUI( 1369): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1369): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
I/[SystemUI]BatterySaverHandler( 1369): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  968): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  968): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  968): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1460702435594; DSPS: 47955688; Offset : -2798435785
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  968): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  968): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  968): tsOffsetIs: Apps: 1480704551709; DSPS: 48611114; Offset : -2798333805
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1369): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1369): called onTimeUpdated()
I/[SystemUI]Clock( 1369): called onTimeUpdated()
I/LgeClockWidgetControlView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
I/[SystemUI]DateView( 1369): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1369): handleTimeUpdate
,TIME-OUT KILL (timeout was 1400000ms)
```
