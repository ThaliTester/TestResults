#### Test 61699762a45f11c_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
D/LGDMClient( 4694): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
D/LGDMClient( 4694): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
--------- beginning of system
W/ContextImpl( 4694): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4694): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
D/LGDMClient( 4694): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
D/LGDMClient( 4694): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
I/LGDMClient( 4694): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
W/ContextImpl( 4694): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
E/LGDMClient( 4694): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 4694): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 4694): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
D/LGDMClient( 4694): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
D/LGDMClient( 4694): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
I/ActivityManager(  983): Killing 4207:com.lge.springcleaning/1000 (adj 15): empty #11
W/libprocessgroup(  983): failed to open /acct/uid_1000/pid_4207/cgroup.procs: No such file or directory
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/NotificationManager(  983): android: cancelAsUser(-1816247584) by android
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 294, mChargingStatus=5, mChargingStop=false
D/charger_monitor(  484): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ActivityManager(  983): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=4730 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  983): battery changed pluggedType: 2
I/ActivityManager(  983): Killing 4241:com.google.android.configupdater/u0a3 (adj 15): empty #11
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/AndroidRuntime( 4727): 
D/AndroidRuntime( 4727): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4727): CheckJNI is OFF
W/libprocessgroup(  983): failed to open /acct/uid_10003/pid_4241/cgroup.procs: No such file or directory
W/ResourcesManager( 4730): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/GAv4-SVC( 4397): Google Analytics 8.4.89 is starting up.
I/GAV2    ( 4478): Thread[GAThread,5,main]: No campaign data found.
I/ActivityManager(  983): Waited long enough for: ServiceRecord{12a62c0 u0 com.lge.mlt/.MltMonitorService}
D/BluetoothManagerService(  983): Message: 20
D/BluetoothManagerService(  983): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@166417a:true
D/BluetoothAdapterService(856336400)( 2017): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2d0447e6
D/BluetoothAdapterService(856336400)( 2017): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2d0447e6
D/AndroidRuntime( 4727): Calling main entry com.android.commands.am.Am
I/ActivityManager(  983): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=4768 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  983): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
V/LGMDMManager( 4730): Create singleton instance
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/ActivityManager(  983): setTaskToReturnTo : TaskRecord{1929385d #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  983): setTaskToReturnTo : TaskRecord{1929385d #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  983): AppWindowTokenEx init.. 
D/ContextHelper(  983): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
D/InputDispatcher(  983): Focus left window: Window{129c85fe u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/[LGHome]EVENT( 1878): [Launcher.java:986:onPause()]onPause
D/AndroidRuntime( 4727): Shutting down VM
I/PhoneWindow(  983): [generateLayout] setColorNavigationBar => color=0x ff000001
I/AudioManager( 4730): getMode name:com.lge.qremote
D/PhoneWindowEx(  983): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  983): [setNavigationBarColor2] color=0x fff5f5f5
D/SplitWindow(  983): check instance of lgWin Window{ed01615 u0 Starting com.test.thalitest}
I/ActivityManager(  983): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4785 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1878): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
V/MmsSystemEventReceiver( 3173): Intent received: Intent { act=android.intent.action.ANY_DATA_STATE flg=0x10 cmp=com.android.mms/.transaction.MmsSystemEventReceiver (has extras) }
V/MmsSystemEventReceiver( 3173): ANY_DATA_STATE event received: DISCONNECTED
I/[LGHome]EVENT( 1878): [Launcher.java:5214:onStop()]onStop
W/ActivityThread( 1878): Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1878): java.lang.RuntimeException: Performing stop of activity that is not resumed: {com.lge.launcher2/com.lge.launcher2.Launcher}
W/ActivityThread( 1878): 	at android.app.ActivityThread.performStopActivityInner(ActivityThread.java:3407)
W/ActivityThread( 1878): 	at android.app.ActivityThread.handleStopActivity(ActivityThread.java:3496)
W/ActivityThread( 1878): 	at android.app.ActivityThread.access$1100(ActivityThread.java:155)
W/ActivityThread( 1878): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1352)
W/ActivityThread( 1878): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/ActivityThread( 1878): 	at android.os.Looper.loop(Looper.java:135)
W/ActivityThread( 1878): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/ActivityThread( 1878): 	at java.lang.reflect.Method.invoke(Native Method)
W/ActivityThread( 1878): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/ActivityThread( 1878): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/ActivityThread( 1878): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
I/WindowStateAnimator(  983): Starting window displayed
D/WindowManager(  983): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/HotwordDetector( 1937): Closing mic
I/SystemUI[Framework](  983): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
I/[SystemUI]NavigationThemeResource( 1374): notify navigation bar color(0xfff5f5f5)
W/PhoneWindowManagerEx(  983): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  983): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  983): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  983): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@137741e0,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  983): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1374): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1374):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1374): , Keyguard show=false, IME shown=false, Panel expanded=false
I/MicrophoneInputStream( 1937): mic_close com.google.android.apps.gsa.speech.audio.u@36c786bc
V/AudioRecord( 1937): stop()
D/AudioRecord( 1937): AudioRecord->stop()
V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
I/AudioManager( 4730): getMode name:com.lge.qremote
V/AudioFlinger(  280): Record stopped OK
V/AudioPolicyManager(  280): stopInput() input 17
V/AudioPolicyService(  280): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  280): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing release audio patch
D/LGDMClient( 4694): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver com.lge.intent.action.fota_data_change
D/LGDMClient( 4694): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
V/AudioFlinger::PatchPanel(  280): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  280): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  280): ThreadBase::setParameters() routing=0
V/AudioFlinger(  280): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  280): processConfigEvents_l() remaining events 1
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb416b000
D/audio_hw_primary(  280): in_standby: enter: stream (0xb40367a0) usecase(7: audio-record)
W/ContextImpl( 4694): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4694): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
,I/ActivityManager(  983): Activity reported stop, but no longer stopping: ActivityRecord{33fe2af4 u0 com.lge.launcher2/.Launcher t221}
D/LGDMClient( 4694): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,D/LGDMClient( 4694): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : com.lge.intent.action.fota_data_change
I/LGDMClient( 4694): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
D/UEI.SmartControl( 4768): Quickset Services start...
V/audio_hw_primary(  280): stop_input_stream: enter: usecase(7: audio-record)
,V/audio_hw_primary(  280): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  280): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  280): disable_audio_route: reset and update mixer path: audio-record
V/audio_hw_primary(  280): disable_audio_route: exit
E/audio_hw_primary(  280): disable_snd_device: enter 144
D/hardware_info(  280): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  280): disable_snd_device: snd_device(144: lg-vr-handset-mic)
,V/audio_hw_primary(  280): stop_input_stream: exit: status(0)
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
V/AudioFlinger(  280): processConfigEvents_l() DONE thread 0xb416b000
V/AudioFlinger(  280): RecordThread: loop stopping
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioRecord( 1937): stop()
I/UEI.SmartControl( 4768): Manufacture = LGE
V/AudioRecord( 1937): stop()
V/AudioRecord( 1937): stop()
,V/AudioFlinger(  280): RecordHandle::stop()
V/AudioFlinger(  280): RecordThread::stop
V/AudioPolicyManager(  280): releaseInput() 17
V/AudioPolicyManager(  280): closeInput(17)
V/AudioFlinger(  280): releasing 16 from 1937 for -1
V/AudioFlinger(  280):  decremented refcount to 0
V/AudioFlinger(  280): purging stale effects
V/AudioFlinger(  280): closeInput() 17
V/AudioSystem(  280): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem(  983): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1751): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): ThreadBase::exit
V/AudioSystem( 1374): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): RecordThread: loop starting
V/AudioSystem( 2017): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  280): RecordThread 0xb416b000 exiting
V/AudioSystem( 2723): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1937): ioConfigChanged() event 4, ioHandle 17
D/audio_hw_primary(  280): adev_close_input_stream: enter:stream_handle(0xb40367a0)
D/audio_hw_primary(  280): in_standby: enter: stream (0xb40367a0) usecase(7: audio-record)
V/audio_hw_primary(  280): in_standby: exit:  status(0)
V/AudioPolicyService(  280): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  280): inserting command: 9 at index 0, num commands 0
V/AudioSystem( 3173): ioConfigChanged() event 4, ioHandle 17
D/UEI.SmartControl( 4768): File observer start...
V/AudioPolicyService(  280): AudioCommandThread() waking up
V/AudioPolicyService(  280): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  280): AudioCommandThread() going to sleep
V/AudioPolicyManager(  280): releaseInput() exit
V/AudioFlinger(  280): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  280): removeClient_l() pid 1937, calling pid 280
I/HotwordRecognitionRnr( 1937): Stopping hotword detection.
E/UEI.SmartControl( 4768): IR Port is disabled: false
D/UEI.SmartControl( 4768): Starting file observer...
D/UEI.SmartControl( 4768): Extracting JNI libs...
D/UEI.SmartControl( 4768): --- this system supports 32-bit or 64-bit only
I/ActivityManager(  983): Start proc com.android.settings for broadcast com.android.settings/.wifi.wifioffload.WiFiOffLoadBroadcast: pid=4813 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
W/ContextImpl( 4694): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
I/HotwordRecognitionRnr( 1937): Hotword detection finished
I/art     (  304): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 400us total 22.071ms
,E/LGDMClient( 4694): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 4694): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 4694): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 4694): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 4694): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,D/ContextHelper( 4785): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 285us total 21.886ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 303us total 22.111ms
D/UEI.SmartControl( 4768): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 4768): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 4768): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 4768): --- Selecting new region: 2
,I/UEI.SmartControl( 4768): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 4768): Platform has CIR...
D/UEI.SmartControl( 4768): NO CIR support, need to check package...
,I/UEI.SmartControl( 4768): Model: LG-D722 uses JNI
D/UEI.SmartControl( 4768): QS Service created
E/UEI.SmartControl( 4768): QS start get config
,I/WebViewFactory( 4785): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 4785): Time to load native libraries: 4 ms (timestamps 8031-8035)
,I/LibraryLoader( 4785): Expected native library version number "",actual native library version number ""
D/UEI.SmartControl( 4768): Loading JNI Libs...
,D/UEI.SmartControl( 4768):  configuring local db...
V/WebViewChromiumFactoryProvider( 4785): Binding Chromium to main looper Looper (main, tid 1) {24e21f0d}
,I/LibraryLoader( 4785): Expected native library version number "",actual native library version number ""
I/chromium( 4785): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 4785): Initializing chromium process, singleProcess=true
W/art     ( 4785): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4785): ApplicationContext is null in ApplicationStatus
W/chromium( 4785): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,W/ResourcesManager( 4813): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4813): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 4813): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 4813): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 4813): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
E/libEGL  ( 4785): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 4785): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 4785): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4785): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 4785): Build Date: 03/02/15 Mon
I/Adreno-EGL( 4785): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 4785): Remote Branch: 
I/Adreno-EGL( 4785): Local Patches: 
I/Adreno-EGL( 4785): Reconstruct Branch: 
,I/IndexDatabaseHelper( 4813): Using schema version: 115
,I/IndexDatabaseHelper( 4813): Index is fine
V/AudioPolicyService(  280): registerClient() client 0xb4027040, uid 10316
,D/BluetoothManagerService(  983): Message: 20
D/BluetoothManagerService(  983): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3f24ad0b:true
D/BluetoothAdapterService(856336400)( 2017): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2d0447e6
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/UEI.SmartControl( 4768):  ---- Has DB8: true
D/UEI.SmartControl( 4768): QS start statue = true Error code = 0
,D/UEI.SmartControl( 4768): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4768): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4768): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 4768): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4768): IrrcClient ++ 
D/irrcClient( 4768): getIrrcService ++ 
,D/irrcClient( 4768): getIrrcService -- 
D/irrcClient( 4768): IrrcClient -- 
W/irrc_jni( 4768): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 4768): Services init done
,I/UEI.SmartControl( 4768): Device manager: loading config....
,D/UEI.SmartControl( 4768): QS Service init finished
D/UEI.SmartControl( 4768): Config is loaded...
D/UEI.SmartControl( 4768): QS Service version name: 0.1.73
D/UEI.SmartControl( 4768): QS Service version code: 1073
D/UEI.SmartControl( 4768): Service requested: Control
,D/UEI.SmartControl( 4768): Internal service binding...
D/UEI.SmartControl( 4768): -----IControl: 11
D/UEI.SmartControl( 4768): Caller: com.lge.qremote
D/UEI.SmartControl( 4768): ------------ IControl registerCallback...
I/UEI.SmartControl( 4768): Registering callback...
D/UEI.SmartControl( 4768): -----IControl: 19
,D/UEI.SmartControl( 4768): Caller: com.lge.qremote
I/UEI.SmartControl( 4768): Registering Services Ready callback...
I/UEI.SmartControl( 4768): Notify client services are ready...
D/UEI.SmartControl( 4768): -----IControl: 8
D/UEI.SmartControl( 4768): Caller: com.lge.qremote
D/UEI.SmartControl( 4768):  ----- QS SDK is ready!!!
I/ActivityManager(  983): Killing 4271:com.lge.eula/1000 (adj 15): empty #11
,I/UEI.SmartControl( 4768): Notify AllClients services are ready: 0
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/WiFiOffLoadBroadcast( 4813): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,W/art     ( 4785): Attempt to remove local handle scope entry from IRT, ignoring
D/WiFiOffLoadBroadcast( 4813): MCCMNC not supported: null
W/libprocessgroup(  983): failed to open /acct/uid_1000/pid_4271/cgroup.procs: No such file or directory
I/ActivityManager(  983): Killing 4314:com.google.android.talk/u0a61 (adj 15): empty #11
W/AwContents( 4785): onDetachedFromWindow called when already detached. Ignoring
,I/PhoneWindow( 4785): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 4785): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 4785): [setNavigationBarColor2] color=0x fff5f5f5
D/SystemWebViewEngine( 4785): CordovaWebView is running on device made by: LGE
,I/ActivityManager(  983): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4854 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
W/libprocessgroup(  983): failed to open /acct/uid_10061/pid_4314/cgroup.procs: No such file or directory
,W/art     ( 4785): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 4785): Attempt to remove local handle scope entry from IRT, ignoring
,I/Activity( 4785): Activity.onPostResume() called 
,D/OpenGLRenderer( 4785): Render dirty regions requested: true
I/OpenGLRenderer( 4785): Initialized EGL, version 1.4
D/OpenGLRenderer( 4785): Enabling debug mode 0
,D/Atlas   ( 4785): Validating map...
,D/SplitWindow(  983): check instance of lgWin Window{2037fd7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 4785): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,I/ActivityManager(  983): Killing 4356:com.google.android.youtube/u0a100 (adj 15): empty #11
D/PCSuite ( 4854): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/libprocessgroup(  983): failed to open /acct/uid_10100/pid_4356/cgroup.procs: No such file or directory
,D/UsbSettingsReceiver( 4813): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 4813): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 4813): [AUTORUN] sys.usb.state = ptp_only,adb
,D/UsbSettingsReceiver( 4813): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 4813): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/InputDispatcher(  983): Focus entered window: Window{2037fd7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/UsbSettingsControl( 4813): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 4813): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 4813): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 4813): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 4813): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 4813): [AUTORUN] onReceive() : TetherState Changed=wlan0
D/UsbSettingsControl( 4813): [AUTORUN] setTetherStatus() : status=false
V/WiFiOffLoadBroadcast( 4813): WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,D/WiFiOffLoadBroadcast( 4813): MCCMNC not supported: null
D/PCSuite ( 4854): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/LGDMClient( 4694): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4694): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4694): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4694): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
V/WiFiOffLoadBroadcast( 4813): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/LGDMClient( 4694): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/WiFiOffLoadBroadcast( 4813): MCCMNC not supported: null
W/InputMethodManagerService(  983): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,D/LGDMClient( 4694): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
D/LGDMClient( 4694): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
I/LGDMClient( 4694): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  983): Displayed com.test.thalitest/.MainActivity: +1s375ms
I/Timeline(  983): Timeline: Activity_windows_visible id: ActivityRecord{3aa785d2 u0 com.test.thalitest/.MainActivity t222} time:68940
,I/PCSuite ( 4854): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
I/Timeline( 4785): Timeline: Activity_idle id: android.os.BinderProxy@2964ce1f time:68954
,W/ContextImpl( 4694): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
E/LGDMClient( 4694): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 4694): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 4694): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
D/LGDMClient( 4694): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 4694): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,D/PCSuite ( 4854): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4854): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/BindingManager( 4785): Cannot call determinedVisibility() - never saw a connection for the pid: 4785
,I/ActivityManager(  983): Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=4899 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  983): Killing 4478:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  983): failed to open /acct/uid_10053/pid_4478/cgroup.procs: No such file or directory
,D/JsMessageQueue( 4785): Set native->JS mode to OnlineEventsBridgeMode
,V/[BNRBootReceiver]( 4899): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 4899): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
V/[BNRBootReceiver]( 4899): Boot Receiver Return
,W/MainApplication( 4899): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
V/WiFiOffLoadBroadcast( 4813): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4813): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4813): WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
,D/WiFiOffLoadBroadcast( 4813): Not supported operator for automatic switch
V/WiFiOffLoadBroadcast( 4813): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
D/WiFiOffLoadBroadcast( 4813): MCCMNC not supported: null
,V/WiFiOffLoadBroadcast( 4813): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4813): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4813): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4813): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4813): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4813): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4813): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4813): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4813): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4813): MCCMNC not supported: null
I/AudioManager( 4730): getMode name:com.lge.qremote
,V/WiFiOffLoadBroadcast( 4813): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4813): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4813): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4813): MCCMNC not supported: null
V/WiFiOffLoadBroadcast( 4813): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4813): MCCMNC not supported: null
,I/PCSuite ( 4854): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
,D/PCSuite ( 4854): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,V/WiFiOffLoadBroadcast( 4813): WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,D/WiFiOffLoadBroadcast( 4813): MCCMNC not supported: null
I/PCSuite ( 4854): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 4854): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,I/AudioManager( 4730): getMode name:com.lge.qremote
I/ActivityManager(  983): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4925 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  983): Killing 4517:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  983): failed to open /acct/uid_10036/pid_4517/cgroup.procs: No such file or directory
,D/jxcore_app_log( 4785): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426134912
,I/ActivityManager(  983): Waited long enough for: ServiceRecord{31bd0fdc u0 com.android.calendar/.alerts.InitAlarmsService}
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4785): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4785):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4785):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4785):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4785):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4785): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15a455e9 added. We now have 1 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4785): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4785):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4785):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4785):     - Bluetooth MAC address: F8:95:C7:87:85:54
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4785):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4785):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4785):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4785):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4785):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4785):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4785): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1611019c added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4785): addListener: New listener added - the number of listeners is now 1
D/BluetoothAdapterService(856336400)( 2017): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2d0447e6
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4785): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,W/System.err( 4785): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 4785): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4785): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4785): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4785): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4785): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4785): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4785): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4785): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4785): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4785): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4785): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4785): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4785): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/JX-Cordova( 4785): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4785): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4785): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e6367a5 added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4785): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4785): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1885977a added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4785): addListener: New listener added - the number of listeners is now 1
D/BluetoothAdapterService(856336400)( 2017): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2d0447e6
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4785): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4785): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4785): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4785): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4785): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4785): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4785): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4785): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4785): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4785): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4785): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4785): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4785): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4785): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4785): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/MusicStore( 4925): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4925): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4925): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 4925): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 4925): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 4925): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4925): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 4925): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 4925): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1cd3aa39: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4925): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4925): GMSCore installation verified
,I/ConfigStore( 4925): Config Database version: 1
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/MediaRouter( 4925): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 4925): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
I/NetworkMonitor( 4925): type=WIFI subType= reason=null isConnected=true
,I/art     (  983): Explicit concurrent mark sweep GC freed 27440(1377KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/34MB, paused 2.841ms total 178.867ms
,I/NetworkMonitor( 4925): type=WIFI subType= reason=null isConnected=true
,I/ActivityManager(  983): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=4961 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/GHttpClientFactory( 4925): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/GoogleURLConnFactory( 4925): Using platform SSLCertificateSocketFactory
W/ResourcesManager( 4961): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4961): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 4961): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  983): Killing 3156:com.android.defcontainer/u0a4 (adj 15): empty #11
,W/libprocessgroup(  983): failed to open /acct/uid_10004/pid_3156/cgroup.procs: No such file or directory
,I/NotificationManager( 4925): com.google.android.music: cancel(1061) by com.google.android.music
I/LGEmail ( 4961): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 4961): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,D/eas_req ( 4961): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,D/LGDMClient( 4694): [DmDeviceActionReceiver.java] [onReceive()] : [124] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4694): [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,W/ContextImpl( 4694): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
W/ContextImpl( 4694): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:128 android.app.ActivityThread.handleReceiver:2663 
D/LGDMClient( 4694): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
D/LGDMClient( 4694): [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
D/LGDMClient( 4694): [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,I/LGDMClient( 4694): [DmServiceProcessor.java] [processNetworkChanged()] : [90] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/ActivityManager(  983): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=5000 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/ContextImpl( 4694): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1798 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:134 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:173 android.app.IntentService$ServiceHandler.handleMessage:65 
I/HubEmail( 4961): JNI_OnLoad()
I/HubEmail( 4961): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4961): registerNatives()
I/HubEmail( 4961): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4961): registerNativeMethods()
I/HubEmail( 4961): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
E/LGDMClient( 4694): [DmNotiService.java] [onCreate()] : [154] : DmNotiService.onCreate()
D/LGDMClient( 4694): [DmNotiService.java] [onStartCommand()] : [188] : in the new onStartCommand()
D/LGDMClient( 4694): [DmNotiService.java] [handleStart()] : [209] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,W/art     ( 4961): JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
D/LGDMClient( 4694): [DmNotiService.java] [actionSystemNetworkChanged()] : [283] : DmConstants.DMAgentState.DMA_STATE_IDLE
D/LGDMClient( 4694): [DmNotiService.java] [OneDayWiFiCheck()] : [709] : agentmodeOnOff is OFF. Finish WiFiCheck
,I/ActivityManager(  983): Killing 4664:com.lge.qmemoplus/1000 (adj 15): empty #11
,W/libprocessgroup(  983): failed to open /acct/uid_1000/pid_4664/cgroup.procs: No such file or directory
W/Settings( 4961): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/AppUp4:AppBoxCP( 5000): onCreate
,W/AppUp4:DB( 5000):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5000):  setFingerPrint start
,I/AppUp4:DB( 5000):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5000):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5000):  SDK version = 0
I/AppUp4:DB( 5000):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5000): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 5000): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 5000): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 5000): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 5000): [onReceive] request level :IDLE....
I/AppUp4:CustModeStarterReceiver( 5000): onReceive
I/AppUp4:CustModeStarterReceiver( 5000): CustModeStarterReceiver - android.net.conn.CONNECTIVITY_CHANGE
D/AppUp4:CustFacade( 5000): Context : android.app.ReceiverRestrictedContext@24e21f0d
D/AppUp4:CustFacade( 5000): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5000): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 5000): begin check event
I/AppUp4:CustModeStarterReceiver( 5000): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 5000): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 5000): call method handleAsyncCustNotification.
D/AppUp4:CustModeStarterReceiver( 5000): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 5000): handleAsyncCustNotification do not startCustService
I/ActivityManager(  983): Killing 4899:com.lge.bnr/1000 (adj 15): empty #11
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,W/libprocessgroup(  983): failed to open /acct/uid_1000/pid_4899/cgroup.procs: No such file or directory
,I/LgeMiscReceiver( 3173): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 3173): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 3173): networkInfo.isConnected() = true
D/PhoneState( 3173): setPdpRejectCasuse : false
I/ActivityManager(  983): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=5030 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 5030): Register our PhoneStateListener
,D/MobileConnectivityChangeReceiver( 5030): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 5030): onReceive CONNECTIVITY_CHANGE networkType=1
,I/ActivityManager(  983): Killing 4813:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  983): failed to open /acct/uid_1000/pid_4813/cgroup.procs: No such file or directory
,V/DownloadManager( 3274): Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 3274): DownloadService onCreate
I/CheckinService( 4397): Checkin interval check for package: unspecified last checkin: 1457080054439 min interval config: 0 actual interval: 12410864
,I/DownloadManager( 3274): in removeSpuriousFiles
I/NotificationManager( 3274): com.android.providers.downloads: cancelAll by com.android.providers.downloads
V/DownloadManager( 3274): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3274): created cursor android.database.sqlite.SQLiteCursor@1611019c on behalf of 3274
I/DownloadManager( 3274): in trimDatabase
V/DownloadManager( 3274): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 3274): created cursor android.database.sqlite.SQLiteCursor@2e6367a5 on behalf of 3274
D/PhoneMonitor( 5030): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5030): [loadFeatureFromXml] *** start feature loading from xml
,I/ActivityManager(  983): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5060 uid=10051 gids={50051, 9997, 4002, 3003, 1028} abi=armeabi-v7a
I/CheckinService( 4397): Checking schedule, now: 1457092465352 next: 1457080084393
I/CheckinService( 4397): active receiver: enabled
V/DownloadManager( 3274): DownloadService onStartCommand
V/DownloadManager( 3274): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/TelephonyAutoProfiling( 5030): [parse] Load xml
,V/DownloadManager( 3274): created cursor android.database.sqlite.SQLiteCursor@764db2b on behalf of 3274
,V/TelephonyAutoProfiling( 5030): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5030): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
I/CheckinService( 4397): Preparing to send checkin request
I/EventLogService( 4397): Accumulating logs since 1457091562004
,D/PhoneMonitor( 5030): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/DownloadManager( 3274): DownloadService onDestroy
,D/DrmBroadcastReceiver( 5060): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 5060): 1  network is available. Sync DRM Time with NTP
,D/WeatherAncestor( 2705): 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:54:25
V/DrmService( 5060): Service onCreate
D/DrmService( 5060): Received new request = 2
D/UpdateThreadPoolManager( 2705): 2 : This is isUpdating : false
I/DrmSntpClient( 5060): Start Sync process
D/DrmSntpClient( 5060): Server : 0
D/WeatherAncestor( 2705): connectivity changed - connection : true
,D/Weather_cast( 2705): 2 : isUpdateNeedForAlarm : no city return false
D/libc-netbsd( 5060): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5060): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/WeatherAncestor( 2705): 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 12:54:25
D/libc-netbsd( 5060): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/WeatherService( 2705): 2 : onStartCommand, intent!=null, action: android.net.conn.CONNECTIVITY_CHANGE
D/libc-netbsd( 5060): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10051
D/DnsProxyListener(  276): App 10051 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
,I/ActivityManager(  983): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5091 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ActivityManager(  983): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2705): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2705): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2705): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/CheckinRequestBuilder( 4397): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4397): Failed to find provider info for com.google.android.wearable.settings
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/System.out( 5060): propertyValue:false
W/ResourcesManager( 5091): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/LGDrmClient( 5060): _DRM_ServiceGet() : Bind lgdrm service
,V/ILGDrmService(  287): eDRM_SetDRMTime +++
I/LGDRM   (  287): [DRM] SET TIME : YR=2016, MON=3, DAY=4
I/LGDRM   (  287): [DRM] SET TIME : HR=11, MIN=54, SEC=24
V/ILGDrmService(  287): eDRM_SetDRMTime ---
,I/DrmSntpClient( 5060): Synched
D/DrmService( 5060): Completed !! request = 2
D/DrmService( 5060): Request count = 0
V/DrmService( 5060): Service onDestroy
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
I/Babel_SMS( 5091): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 5091): MmsConfig.loadMmsSettings
I/Babel_SMS( 5091): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5091): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5091): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5091): MmsConfig.loadFromResources
E/Babel_SMS( 5091): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5091): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5091): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5091): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5091): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
,D/SensorManager( 5091): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5091): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5091): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5091): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5091): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5091): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5091): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5091): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5091): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5091): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5091): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5091): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5091): found sensor: Motion Accel, handle=46
W/Settings( 5091): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/Babel_Crash( 5091): startup - clean
I/System.out( 1733): propertyValue:false
I/Babel   ( 5091): deleted: false for 0
,I/art     ( 5091): CheckpointMarkThreadRoots callback created = 0xb042d900
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/art     ( 5091): CheckpointMarkThreadRoots callback created = 0xb042d8e0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/ActivityManager(  983): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5126 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/AudioCapabilities( 5091): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5091): Unsupported mime audio/adpcm
,W/AudioCapabilities( 5091): Unsupported mime audio/g726
W/AudioCapabilities( 5091): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5091): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5091): Unsupported mime video/mjpg
,W/VideoCapabilities( 5091): Unsupported mime video/theora
W/AudioCapabilities( 5091): Unsupported mime audio/evrc
,W/AudioCapabilities( 5091): Unsupported mime audio/qcelp
W/VideoCapabilities( 5091): Unrecognized profile 2130706433 for video/avc
,V/AlarmManager(  983): RTC_WAKEUP set : Alarm{1276fb5f type 0 when 1457092466256 com.google.android.googlequicksearchbox} when 1457092466256
,W/AudioCapabilities( 5091): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5091): Unsupported mime audio/qcelp
W/AudioCapabilities( 5091): Unsupported mime audio/evrc
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/VideoCapabilities( 5091): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5091): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5091): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5091): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5091): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5091): Unrecognized profile 2130706433 for video/avc
,I/ActivityManager(  983): Process com.google.android.music:main (pid 4925) has died
,I/vclib   ( 5091): onServiceConnected
W/Babel   ( 5091): Attempted to change video mute state without an active call.
,I/NotificationManager( 5091): com.google.android.talk: cancel(10436) by com.google.android.talk
D/libc-netbsd( 5091): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 5091): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5091): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5091): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  276): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 5091): propertyValue:false
I/ActivityManager(  983): Waited long enough for: ServiceRecord{735ac3c u0 com.lge.springcleaning/.service.AppCleanupService}
,I/NotificationManager(  983): android: cancelAsUser(2) by android
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5126): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5126): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/Babel   ( 5091): connection state changed from UNKNOWN to CONNECTED
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5126): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5126): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 5126): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5126):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5126):   adb logcat -s GAv4
,W/GAv4    ( 5126): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5126): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,I/art     ( 4106): Explicit concurrent mark sweep GC freed 2915(115KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 374us total 25.667ms
W/GAv4    ( 5126): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/ActivityManager(  983): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5161 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 5161): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5161): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 5161): VM with version 2.1.0 has multidex support
,I/MultiDex( 5161): install
I/MultiDex( 5161): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 5161): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,W/ActivityThread( 5161): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5161): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3645b146: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5161): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 5161): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 5161): com.google.android.gms: cancel(39789) by com.google.android.gms
D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 73470233622; DSPS: 2506275; Offset : -3016469361
,I/WebViewFactory( 5126): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
D/UEI.SmartControl( 4768): Internal timer expired: 1
,I/art     ( 5161): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5161): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/LibraryLoader( 5126): Time to load native libraries: 6 ms (timestamps 3523-3529)
I/LibraryLoader( 5126): Expected native library version number "",actual native library version number ""
,V/WebViewChromiumFactoryProvider( 5126): Binding Chromium to main looper Looper (main, tid 1) {1e82f7f6}
,I/LibraryLoader( 5126): Expected native library version number "",actual native library version number ""
I/chromium( 5126): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserStartupController( 5126): Initializing chromium process, singleProcess=true
,W/art     ( 5126): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5126): ApplicationContext is null in ApplicationStatus
W/chromium( 5126): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5126): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5126): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5126): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5126): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5126): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5126): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5126): Remote Branch: 
I/Adreno-EGL( 5126): Local Patches: 
I/Adreno-EGL( 5126): Reconstruct Branch: 
,D/NativeLibraryUtils( 5161): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  280): Instantiating CDM.
,I/WVCdm   (  280): CdmEngine::OpenSession
I/WVCdm   (  280): Level3 Library Dec 11 2014 16:13:16
V/AudioPolicyService(  280): registerClient() client 0xb40273c0, uid 10079
,W/AudioManagerAndroid( 5126): Requires BLUETOOTH permission
I/NSApplication( 5126): Starting up...
,W/WVCdm   (  280): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,W/WVCdm   (  280): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  280): L1 library not specified. Falling Back to L3
,I/ActivityManager(  983): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5230 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  983): Killing 4768:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
I/art     (  304): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 21.700ms
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 264us total 20.996ms
W/WVCdm   (  280): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  280): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
W/System.err( 4730): android.os.DeadObjectException
D/WVCdm   (  280): PrepareKeyRequest: nonce=2305541974
W/System.err( 4730): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4730): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4730): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 4730): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 4730): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4730): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4730): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4730): 	at android.os.Handler.dispatchMessage(Handler.java:95)
,W/System.err( 4730): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4730): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4730): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4730): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4730): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 4730): android.os.DeadObjectException
W/System.err( 4730): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 4730): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 4730): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 4730): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 4730): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 4730): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 4730): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 4730): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 4730): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4730): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 4730): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4730): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4730): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 4730): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 4730): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 265us total 22.541ms
,E/libprocessgroup(  983): failed to kill 1 processes for processgroup 4768
,I/art     (  983): Explicit concurrent mark sweep GC freed 17404(941KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/34MB, paused 2.005ms total 153.646ms
,W/ActivityManager(  983): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/GoogleURLConnFactory( 5161): Using platform SSLCertificateSocketFactory
,D/libc-netbsd( 5161): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5161): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5161): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5161): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
I/ActivityManager(  983): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5258 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 5161): propertyValue:false
,D/UEI.SmartControl( 5258): Quickset Services start...
I/UEI.SmartControl( 5258): Manufacture = LGE
,D/UEI.SmartControl( 5258): File observer start...
E/UEI.SmartControl( 5258): IR Port is disabled: false
D/UEI.SmartControl( 5258): Starting file observer...
D/UEI.SmartControl( 5258): Extracting JNI libs...
D/UEI.SmartControl( 5258): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 5258): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5258): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5258): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/libc-netbsd( 5161): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5161): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5161): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5161): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/UEI.SmartControl( 5258): --- Selecting new region: 2
I/UEI.SmartControl( 5258): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5258): Platform has CIR...
D/UEI.SmartControl( 5258): NO CIR support, need to check package...
I/UEI.SmartControl( 5258): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5258): QS Service created
I/ActivityManager(  983): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5289 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  983): Killing 4854:com.lge.sync/1000 (adj 15): empty #11
I/chromium( 4785): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
I/chromium( 4785): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,W/libprocessgroup(  983): failed to open /acct/uid_1000/pid_4854/cgroup.procs: No such file or directory
,E/UEI.SmartControl( 5258): QS start get config
,W/ResourcesManager( 5289): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  983): Reconfiguring input devices.  changes=0x00000010
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
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
D/administrator(  983): Handling package changes for user 0
,I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
D/UEI.SmartControl( 5258): Loading JNI Libs...
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
D/UEI.SmartControl( 5258):  configuring local db...
I/art     ( 1786): CheckpointMarkThreadRoots callback created = 0xaaf20bd0
,I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/art     ( 1786): CheckpointMarkThreadRoots callback created = 0xaaf724b0
,I/art     ( 1786): Background partial concurrent mark sweep GC freed 53376(3MB) AllocSpace objects, 0(0B) LOS objects, 40% free, 8MB/14MB, paused 849us total 108.322ms
,I/art     ( 5161): CheckpointMarkThreadRoots callback created = 0xb04d4f70
,I/art     ( 5161): CheckpointMarkThreadRoots callback created = 0xaae47e20
,I/NotificationService(  983): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  983): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  983): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  983): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  983): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  983): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@294b79cd
D/UEI.SmartControl( 5258):  ---- Has DB8: true
,D/UEI.SmartControl( 5258): QS start statue = true Error code = 0
D/UEI.SmartControl( 5258): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5258): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5258): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5258): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5258): IrrcClient ++ 
D/irrcClient( 5258): getIrrcService ++ 
,D/irrcClient( 5258): getIrrcService -- 
,D/irrcClient( 5258): IrrcClient -- 
W/irrc_jni( 5258): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5258): Services init done
D/UEI.SmartControl( 5258): QS Service init finished
D/UEI.SmartControl( 5258): QS Service version name: 0.1.73
D/UEI.SmartControl( 5258): QS Service version code: 1073
D/UEI.SmartControl( 5258): Service requested: Control
I/UEI.SmartControl( 5258): Device manager: loading config....
D/UEI.SmartControl( 5258): Config is loaded...
,D/UEI.SmartControl( 5258): Request IControl service: devices are loaded...
I/ActivityManager(  983): Killing 4730:com.lge.qremote/u0a106 (adj 15): empty #11
,D/UEI.SmartControl( 5258): -----IControl: 11
D/UEI.SmartControl( 5258): Caller: com.lge.qremote
D/UEI.SmartControl( 5258): ------------ IControl registerCallback...
I/UEI.SmartControl( 5258): Registering callback...
D/UEI.SmartControl( 5258):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5258): Notify AllClients services are ready: 0
,W/ResourcesManager(  983): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  983): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,W/libprocessgroup(  983): failed to open /acct/uid_10106/pid_4730/cgroup.procs: No such file or directory
D/UEI.SmartControl( 5258): Internal service binding...
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/ActivityManager(  983): Killing 4961:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  983): failed to open /acct/uid_10021/pid_4961/cgroup.procs: No such file or directory
,I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/iu.SyncManager( 4397): SYNC; picasa accounts
,I/dex2oat ( 5318): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=37 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
D/LocationProviderProxy(  983): applying state to connected service
D/NetworkLogImpl( 4397): Loaded NetworkSpeedPredictor
,I/iu.Environment( 4397): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
I/iu.UploadsManager( 4397): num queued entries: 0
I/iu.UploadsManager( 4397): num updated entries: 0
I/iu.SyncManager( 4397): NEXT; no task
I/dex2oat ( 5318): dex2oat took 106.291ms (threads: 4)
,I/ActivityManager(  983): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=5327 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
I/Adreno-EGL( 5161): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5161): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5161): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5161): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5161): Remote Branch: 
I/Adreno-EGL( 5161): Local Patches: 
I/Adreno-EGL( 5161): Reconstruct Branch: 
,I/Adreno-EGL( 5161): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5161): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5161): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5161): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5161): Remote Branch: 
I/Adreno-EGL( 5161): Local Patches: 
I/Adreno-EGL( 5161): Reconstruct Branch: 
,I/WVCdm   (  280): CdmEngine::CloseSession
,I/DigitalAppWidgetProvider( 5327): onReceive: android.intent.action.ALARM_CHANGED
I/WVCdm   (  280): L3 Terminate.
I/ActivityManager(  983): Killing 4694:com.lge.lgdmsclient/1000 (adj 15): empty #11
W/libprocessgroup(  983): failed to open /acct/uid_1000/pid_4694/cgroup.procs: No such file or directory
,D/WeatherAncestor( 2705): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:54:29
D/UpdateThreadPoolManager( 2705): 2 : This is isUpdating : false
D/Weather_cast( 2705): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2705): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:54:29
D/WeatherService( 2705): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
W/ActivityManager(  983): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2705): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2705): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2705): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
I/Adreno-EGL( 5161): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5161): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5161): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5161): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5161): Remote Branch: 
I/Adreno-EGL( 5161): Local Patches: 
I/Adreno-EGL( 5161): Reconstruct Branch: 
,V/SmsReceiverService( 3173): onStart: #1 mResultCode: -1 = Activity.RESULT_OK
I/ActivityManager(  983): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5347 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,D/MmsConfig( 3173): isNotAllowedSms: currentUser:0
D/MmsConfig( 3173): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3173): isUserMode:false
D/SmsReceiverService( 3173): handleMessage isUserMode:false
V/SmsReceiverService( 3173): handleMessage action: com.android.mms.transaction.SEND_MESSAGE error: 0
,D/SmsReceiverService( 3173): [LGE] handleSendMessage Send messages in queue
,W/ResourcesManager( 5347): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  983): Message: 20
,D/BluetoothManagerService(  983): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2b696906:true
D/BluetoothAdapterService(856336400)( 2017): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2d0447e6
D/BluetoothAdapterService(856336400)( 2017): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2d0447e6
I/[LGHome]LGNumberBadgeReceiver( 1878): [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = lge.intent.action.UNREAD_MESSAGES
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1878): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1878): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1878): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1878): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
W/ProcessCpuTracker(  983): Skipping unknown process pid 5268
,W/ProcessCpuTracker(  983): Skipping unknown process pid 5271
,I/ActivityManager(  983): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=5369 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/CheckinRequestBuilder( 4397): Classify the device as Phone.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/libc-netbsd( 4397): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4397): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4397): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4397): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 4397): propertyValue:false
W/ResourcesManager( 5369): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5369): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5369): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5369): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/ResourcesManager( 5369): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/libc-netbsd( 4397): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4397): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/IndexDatabaseHelper( 5369): Using schema version: 115
,I/IndexDatabaseHelper( 5369): Index is fine
D/libc-netbsd( 4397): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4397): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4397): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4397): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 4397): Sending checkin request (7992 bytes)
,I/ActivityManager(  983): Process com.google.android.talk (pid 5091) has died
,D/UsbSettingsReceiver( 5369): [AUTORUN] onReceive() : action = android.hardware.usb.action.USB_STATE
D/UsbSettingsReceiver( 5369): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5369): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5369): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5369): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsReceiver( 5369): [AUTORUN] onReceive() : getDefaultFunction = ptp_only
D/UsbSettingsReceiver( 5369): [AUTORUN] onReceive() : USB_FUNCTION_CDROM_STORAGE = false
D/UsbSettingsReceiver( 5369): [AUTORUN] onReceive() : mDirectAutorun = true
D/UsbSettingsReceiver( 5369): [AUTORUN] onReceive() : mActivityUsbModeChange = false
,D/UsbSettingsReceiver( 5369): [AUTORUN] onReceive() : mActivityFinish = false
D/UsbSettingsReceiver( 5369): [AUTORUN] onReceive() : ===== USB Configured =====
D/UsbSettingsControl( 5369): [AUTORUN] setUsbConnected() : connected=true
D/UsbSettingsReceiver( 5369): [AUTORUN] onReceive() : checkQmicm = ptp_only,adb
D/UsbSettingsReceiver( 5369): [AUTORUN] : topPackageName=com.test.thalitest
D/UsbSettingsReceiver( 5369): [AUTORUN] : topClassName=com.test.thalitest.MainActivity
,D/UsbSettingsReceiver( 5369): [AUTORUN] Not exist com.android.LGSetupWizard
D/UsbSettingsReceiver( 5369): [AUTORUN] setUsbConnect() : mUsbSettingsRun = false
D/UsbSettingsReceiver( 5369): [AUTORUN] startUsbSettings() : deviceProvisioned=1
I/ActivityManager(  983): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5395 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/MtpService( 3274): updating state; isCurrentUser=true, mMtpLocked=false
,I/PCSuite ( 5395): [StartReceiver]USB CONNECTED ver UsbManger : ptp_only
I/PCSuite ( 5395): [StartReceiver]isUsbPCSuiteMode : false
,D/PCSuite ( 5395): [StartReceiver][checkEUTStatus] eutStatus = 
D/PCSuite ( 5395): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5395): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  983): Killing 5000:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  983): failed to open /acct/uid_10011/pid_5000/cgroup.procs: No such file or directory
D/WeatherAncestor( 2705): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 12:54:30
,D/UpdateThreadPoolManager( 2705): 2 : This is isUpdating : false
D/WeatherAncestor( 2705): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 12:54:30
D/WeatherService( 2705): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
W/ActivityManager(  983): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2705): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2705): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2705): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2705): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2705): 2 : This is isUpdating : false
D/WeatherService( 2705): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2705): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2705): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2705): 2 : Fixed theme : optimus
V/UserPresentBroadcastReceiver( 1733): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/WeatherReflect( 2705): 2 : Map key string is -2
,D/lim     ( 2705): 2 : time = 12:54
I/WeatherReflect( 2705): Model Name : LG-D722
D/WeatherTheme( 2705): 2 : exactly same view!
D/WeatherTheme( 2705): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
W/ActivityManager(  983): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2705): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2705): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2705): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,V/LGMDMManager( 5347): Create singleton instance
I/DigitalAppWidgetProvider( 5327): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 2705): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:54:30
D/UpdateThreadPoolManager( 2705): 2 : This is isUpdating : false
D/Weather_cast( 2705): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2705): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 12:54:30
D/WeatherService( 2705): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
,W/ActivityManager(  983): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/AlertReceiver( 3929): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
D/Weather.Utils( 2705): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2705): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2705): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/AlertService( 3929): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 3929): [updateWidgets] 
,D/MonthWidgetProvider( 3929): [onReceive]
D/CalendarWidgetProvider( 3929): [onReceive]
D/CalendarWidgetProvider( 3929): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 3929): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 3929): [onReceive]
D/CalendarWidgetProvider( 3929): [onReceive]
D/CalendarWidgetProvider( 3929): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 3929): [onCreate] mContext.getPackageName() = com.android.calendar
,I/[SystemUI]SafeModeBroadcastReceiver( 1374): onReceive = com.lge.statusbar.bootcompleted
,D/CalendarWeatherReceiver( 3929): Get action=com.lge.calendar.action.WEATHER_SERVICE_START
I/ActivityManager(  983): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.MediaScanReceiver: pid=5417 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,E/MediaScanReceiver( 5417): media scanning start or checking
,W/MainApplication( 5417): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/CheckinRequestBuilder( 4397): Checkin reason type: 8 attempt count: 1
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  983): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5434 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  983): Killing 5030:com.google.android.setupwizard/u0a38 (adj 15): empty #11
E/ActivityThread( 4397): Failed to find provider info for com.google.android.wearable.settings
,I/ActivityManager(  983): Process com.google.android.apps.magazines (pid 5126) has died
W/libprocessgroup(  983): failed to open /acct/uid_10038/pid_5030/cgroup.procs: No such file or directory
,I/CheckinRequestBuilder( 4397): Classify the device as Phone.
,I/CheckinTask( 4397): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4397): Checking schedule, now: 1457092471288 next: 1457619720265
I/CheckinService( 4397): active receiver: disabled
,I/MusicStore( 5434): Database version: 120
D/CheckinService( 4397): Recording last checkin time for package unspecified as 1457092471329
,I/ActivityManager(  983): Killing 5060:com.lge.drmservice/u0a51 (adj 15): empty #11
,W/libprocessgroup(  983): failed to open /acct/uid_10051/pid_5060/cgroup.procs: No such file or directory
,I/NotificationManager( 1937): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5434): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5434): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5434): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 5434): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5434): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5434): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5434): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5434): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1cd3aa39: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5434): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5434): GMSCore installation verified
I/ConfigStore( 5434): Config Database version: 1
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/MediaRouter( 5434): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/ToneMappingReceiver( 5327): Enter doAlarmRingToneUriMapping()
I/NetworkMonitor( 5434): type=WIFI subType= reason=null isConnected=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/art     (  983): Explicit concurrent mark sweep GC freed 24048(1264KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 1.972ms total 144.121ms
,D/ToneMappingReceiver( 5327): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5327): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5327): getFinededDefaultTone() -> backup ringtone value : null
,D/CommonUtil( 5327): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5327): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5327): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5327): Alarm Success count is 0
D/ToneMappingReceiver( 5327): Timer Success count is 0
I/MediaScannerReceiver( 3929): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///system/media
,I/InitNotificationRingtoneService( 3929): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3929): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
E/MediaScanReceiver( 5417): media scanning finished
I/NetworkMonitor( 5434): type=WIFI subType= reason=null isConnected=true
,I/com.lge.bnr.receiver.MediaScanReceiver( 5417): android.intent.action.MEDIA_SCANNER_FINISHED
I/AlertUtils( 3929): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/GHttpClientFactory( 5434): Using our fixed implementation of GMSCore's GoogleHttpClient
,I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/GoogleURLConnFactory( 5434): Using platform SSLCertificateSocketFactory
I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3929): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 3929): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3929): End InitializeAlertRingtoneService.onHandleIntent
E/MediaScanReceiver( 5417): media scanning start or checking
,I/NotificationManager( 5434): com.google.android.music: cancel(1061) by com.google.android.music
D/ToneMappingReceiver( 5327): Enter doAlarmRingToneUriMapping()
D/ToneMappingReceiver( 5327): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5327): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5327): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5327): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5327): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5327): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5327): Alarm Success count is 0
,D/ToneMappingReceiver( 5327): Timer Success count is 0
I/MediaScannerReceiver( 3929): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///storage/emulated/0
I/ActivityManager(  983): Killing 5230:com.android.chrome/u0a48 (adj 15): empty #11
W/libprocessgroup(  983): failed to open /acct/uid_10048/pid_5230/cgroup.procs: No such file or directory
,I/InitNotificationRingtoneService( 3929): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3929): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
E/MediaScanReceiver( 5417): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 5417): android.intent.action.MEDIA_SCANNER_FINISHED
I/art     ( 3274): Explicit concurrent mark sweep GC freed 11929(805KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/10MB, paused 411us total 41.052ms
,I/ActivityManager(  983): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5490 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AlertUtils( 3929): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/art     ( 5434): CheckpointMarkThreadRoots callback created = 0xb042d400
,I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
W/ResourcesManager( 5490): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/art     ( 5434): CheckpointMarkThreadRoots callback created = 0xb042d3d0
I/AlertUtils( 3929): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3929): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 3929): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3929): End InitializeAlertRingtoneService.onHandleIntent
,D/CalendarProvider2( 5490): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3a2ee55b
D/CalendarProvider2( 5490): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5490): Created com.android.providers.calendar.CalendarAlarmManager@2293d5a4(com.android.providers.calendar.CalendarProvider2@3a2ee55b)
D/CalendarProviderBroadcastReceiver( 5490): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
I/MediaStoreImporter( 5434): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
D/CalendarProviderBroadcastReceiver( 5490): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 5490): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 5490): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5490): [getOrCreateCalendarAlarmManager]
D/CalendarProvider2( 5490): [IntentService] Release Lock
,D/CalendarProvider2( 5490): CalendarProviderIntentService.onDestroy()
D/WearableService( 1733): callingUid 10006, callindPid: 1733
E/MDM     ( 1733): [145] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/LocationInitializer( 4397): Restart initialization of location
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,I/ActivityManager(  983): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5514 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,I/art     ( 4397): Explicit concurrent mark sweep GC freed 18107(1414KB) AllocSpace objects, 30(480KB) LOS objects, 40% free, 11MB/19MB, paused 1.083ms total 81.193ms
,W/IcingInternalCorpora( 4397): getNumBytesRead when not calculated.
,W/ActivityManager(  983): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 5514): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5514): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  983): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5514): Error finding the version of the Email provider.....
E/Gmail   ( 5514): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5514): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5514): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5514): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5514): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5514): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5514): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5514): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5514): We do not support migrating this version of the Email provider.
,I/Gmail   ( 5514): getAccountsCursor
W/ActivityManager(  983): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/art     (  983): Explicit concurrent mark sweep GC freed 11676(631KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 1.814ms total 132.603ms
,I/Gmail   ( 5514): Observing account changes for notifications
W/ActivityManager(  983): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1733): No location to return for getLastLocation()
,W/FusedLocationProvider( 1733): location=null
,V/DownloadManager( 3274): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3274): created cursor android.database.sqlite.SQLiteCursor@f47d921 on behalf of 4397
I/art     ( 4106): Explicit concurrent mark sweep GC freed 3183(126KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 985us total 43.067ms
,I/ActivityManager(  983): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5570 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
I/art     (  304): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 21.757ms
,I/Gmail   ( 5514): notifyAccountChanged
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 308us total 24.793ms
I/Gmail   ( 5514): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 281us total 21.167ms
I/Gmail   ( 5514): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5514): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5514): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5514): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/PhoneMonitor( 5570): Register our PhoneStateListener
,I/ActivityManager(  983): Killing 5258:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/libprocessgroup(  983): failed to open /acct/uid_10089/pid_5258/cgroup.procs: No such file or directory
,V/DownloadManager( 3274): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3274): created cursor android.database.sqlite.SQLiteCursor@3645b146 on behalf of 4397
,V/DownloadManager( 3274): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3274): created cursor android.database.sqlite.SQLiteCursor@39d3ff07 on behalf of 4397
D/PhoneMonitor( 5570): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5570): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5570): [parse] Load xml
,I/CheckinService( 4397): Checkin interval check for package: unspecified last checkin: 1457092471329 min interval config: 0 actual interval: 2268
V/TelephonyAutoProfiling( 5570): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 5570): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/Gmail   ( 5514): getAccountsCursor
,I/CheckinService( 4397): Checking schedule, now: 1457092473615 next: 1457092501265
I/CheckinService( 4397): active receiver: disabled
D/PhoneMonitor( 5570): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  983): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5595 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5595): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
V/AlarmManager(  983): ELAPSED_WAKEUP set : Alarm{1117ade5 type 2 when 80492 android} when 80492
I/Babel_SMS( 5595): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5595): MmsConfig.loadMmsSettings
I/Babel_SMS( 5595): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5595): MmsConfig.loadFromDatabase
E/Babel_SMS( 5595): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5595): MmsConfig.loadFromResources
E/Babel_SMS( 5595): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5595): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 5595): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5595): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5595): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5595): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5595): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5595): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5595): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5595): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5595): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5595): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5595): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5595): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5595): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5595): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5595): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5595): found sensor: Motion Accel, handle=46
W/Settings( 5595): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5595): startup - clean
I/Babel   ( 5595): deleted: false for 0
I/art     ( 5595): CheckpointMarkThreadRoots callback created = 0xb042d5b0
I/art     ( 5595): CheckpointMarkThreadRoots callback created = 0xb042d580
W/AudioCapabilities( 5595): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 5595): Unsupported mime audio/adpcm
W/AudioCapabilities( 5595): Unsupported mime audio/g726
W/AudioCapabilities( 5595): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5595): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5595): Unsupported mime video/mjpg
W/VideoCapabilities( 5595): Unsupported mime video/theora
W/AudioCapabilities( 5595): Unsupported mime audio/evrc
W/AudioCapabilities( 5595): Unsupported mime audio/qcelp
W/VideoCapabilities( 5595): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5595): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5595): Unsupported mime audio/qcelp
W/AudioCapabilities( 5595): Unsupported mime audio/evrc
W/VideoCapabilities( 5595): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 5595): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 5595): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5595): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5595): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5595): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 5595): onServiceConnected
,W/Babel   ( 5595): Attempted to change video mute state without an active call.
I/ActivityManager(  983): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5637 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5595): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5595): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5595): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 5637): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5637): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5637): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
W/System  ( 5595): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5595): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 5595): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/LGEmail ( 5637): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 5637): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/ActivityManager(  983): Killing 5289:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  983): failed to open /acct/uid_10086/pid_5289/cgroup.procs: No such file or directory
I/PackageChangeReceiver( 5637): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  983): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5668 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  983): Killing 5369:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  983): failed to open /acct/uid_1000/pid_5369/cgroup.procs: No such file or directory
,I/ActivityManager(  983): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5691 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,I/ActivityManager(  983): Killing 5395:com.lge.sync/1000 (adj 15): empty #11
,W/libprocessgroup(  983): failed to open /acct/uid_1000/pid_5395/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 5691): onCreate
,W/AppUp4:DB( 5691):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 5691):  setFingerPrint start
I/AppUp4:DB( 5691):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 5691):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5691):  SDK version = 0
I/AppUp4:DB( 5691):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5691): AppBoxApplication onCreate()
I/ActivityManager(  983): Killing 5327:com.lge.clock/u0a10 (adj 15): empty #11
,W/libprocessgroup(  983): failed to open /acct/uid_10010/pid_5327/cgroup.procs: No such file or directory
,I/ActivityManager(  983): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5708 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 5708): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5708): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5708): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 5708): Total System Memory = 906309632
,I/GalleryUtils( 5708): Application Heap = 96 MB
I/AppConfig( 5708): App Tier : NOT_DEF
D/SystemHelper( 5708): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  983): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5727 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  983): Killing 5417:com.lge.bnr/1000 (adj 15): empty #11
W/libprocessgroup(  983): failed to open /acct/uid_1000/pid_5417/cgroup.procs: No such file or directory
,W/ResourcesManager( 5727): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5727): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5727): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5727): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5727): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/AlertService( 3929): Beginning updateAlertNotification
,D/AlertService( 3929): No fired or scheduled alerts
I/NotificationManager( 3929): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3929): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3929): com.android.calendar: cancel(2) by com.android.calendar
,I/NotificationManager( 3929): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3929): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3929): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3929): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3929): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3929): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 3929): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3929): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3929): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3929): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3929): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3929): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3929): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3929): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3929): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3929): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3929): com.android.calendar: cancel(19) by com.android.calendar
,I/NotificationManager( 3929): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 3929): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 3929): No events found starting within 1 week.
,I/SystemConfig( 5727): BUILD Country: EU
,I/SystemConfig( 5727): BUILD Operator: OPEN
I/ActivityManager(  983): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5746 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  983): Killing 5434:com.google.android.music:main/u0a81 (adj 15): empty #11
,W/libprocessgroup(  983): failed to open /acct/uid_10081/pid_5434/cgroup.procs: No such file or directory
,I/SystemConfig( 5727): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5727): existFile = false
I/SystemConfig( 5727): canReadFile = false
I/SystemConfig( 5727): systemFeature RCS result false
D/SystemConfig( 5727): refreshRcsSupport() :false
I/LockScreenSettings( 5746): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 5746): New app installed broadcast received ..
,I/LockScreenSettings( 5746): Number of installed packages  1
I/ActivityManager(  983): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5764 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/ActivityManager(  983): Killing 5490:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  983): failed to open /acct/uid_10014/pid_5490/cgroup.procs: No such file or directory
,D/EulaProviderUpdateObserver( 5764): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5764): uri : package:com.test.thalitest
,I/ActivityManager(  983): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5781 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  983): Killing 5514:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  983): failed to open /acct/uid_10053/pid_5514/cgroup.procs: No such file or directory
,D/[BNRAppListMgrReceiver]( 5781): android.intent.action.PACKAGE_ADDED : com.test.thalitest
,W/MainApplication( 5781): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,I/ActivityManager(  983): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5798 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  983): Killing 5570:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  983): failed to open /acct/uid_10038/pid_5570/cgroup.procs: No such file or directory
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/GAv4    ( 5798): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5798):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5798):   adb logcat -s GAv4
,W/GAv4    ( 5798): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
W/GAv4    ( 5798): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5798): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 5798): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5798): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 5798): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5798): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/ActivityManager(  983): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5836 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  983): Killing 4106:com.google.process.gapps/u0a6 (adj 15): empty #11
I/art     (  304): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 304us total 21.890ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 22.419ms
,W/libprocessgroup(  983): failed to open /acct/uid_10006/pid_4106/cgroup.procs: No such file or directory
I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 21.771ms
,W/ResourcesManager( 5836): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/art     ( 5798): CheckpointMarkThreadRoots callback created = 0xaaf2e2e0
V/JNIHelp ( 5798): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
I/art     ( 5798): CheckpointMarkThreadRoots callback created = 0xaaf2e2c0
,W/System  ( 5798): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5798): Installed default security provider GmsCore_OpenSSL
,I/art     (  983): Explicit concurrent mark sweep GC freed 17251(831KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.312ms total 143.254ms
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  983): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5867 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/ActivityManager(  983): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5886 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/CheckinService( 4397): Done disabling old GoogleServicesFramework version
,I/GservicesProvider( 5867): Gservices pushing to system: true; secure/global: true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 145 ms] updated apps [took 145 ms] 
,I/GoogleHttpClient( 5867): GMS http client unavailable, use old client
,I/ActivityManager(  983): Process com.google.android.gms.unstable (pid 5161) has died
,I/GoogleHttpClient( 5867): GMS http client unavailable, use old client
,I/ActivityManager(  983): Killing 5637:com.lge.email/u0a21 (adj 15): empty #11
,W/libprocessgroup(  983): failed to open /acct/uid_10021/pid_5637/cgroup.procs: No such file or directory
,D/Finsky  ( 5886): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 5886): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5886): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5886): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5886): com.android.vending: cancel(-1050172287) by com.android.vending
D/InitAlarmsService( 3929): Clearing and rescheduling alarms.
,I/ActivityManager(  983): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5947 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/DownloadManager( 3274): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3274): created cursor android.database.sqlite.SQLiteCursor@3d61e834 on behalf of 5886
I/NotificationManager( 5886): com.android.vending: cancel(1003285959) by com.android.vending
,W/ResourcesManager( 5947): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/PackageBroadcastService( 4397): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraCfgMgr( 4397): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/Finsky  ( 5886): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5886): [1] Libraries$2.run: Finished loading 1 libraries.
D/ChimeraModuleLdr( 4397): Loading module APK com.google.android.play.games
D/Finsky  ( 5886): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Ads     ( 5886): Skipping gmscore version check
D/Finsky  ( 5886): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,D/CalendarProvider2( 5947): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3a2ee55b
D/Finsky  ( 5886): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/CalendarProvider2( 5947): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5947): Created com.android.providers.calendar.CalendarAlarmManager@2293d5a4(com.android.providers.calendar.CalendarProvider2@3a2ee55b)
D/CalendarProvider2( 5947): Scheduling check of next Alarm
D/CalendarProvider2( 5947): SCHEDULE_ALARM_REMOVE
I/ActivityManager(  983): Killing 3929:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  983): failed to open /acct/uid_10013/pid_3929/cgroup.procs: No such file or directory
,I/ActivityManager(  983): Killing 5668:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,W/libprocessgroup(  983): failed to open /acct/uid_10009/pid_5668/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 4397): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4397): Module APK com.google.android.play.games already loaded
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/ChimeraCfgMgr( 4397): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/Icing   ( 4397): Storage manager: low false usage 1.75MB avail 2.37GB capacity 4.06GB
D/AsyncTaskServiceImpl( 4397): Submit a task: k
,D/ChimeraCfgMgr( 4397): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 4397): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 4397): Processing package: com.test.thalitest
D/GassUtils( 4397): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,D/k       ( 4397): Found info for package com.test.thalitest in db.
W/BaseAppContext( 4397): Using Auth Proxy for data requests.
W/BaseAppContext( 4397): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 4397): cleanUpNonGplusAccounts done.
W/BaseAppContext( 4397): Using Auth Proxy for data requests.
W/BaseAppContext( 4397): Using Auth Proxy for data requests.
,W/BaseAppContext( 4397): Using Auth Proxy for data requests.
,I/ActivityManager(  983): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6007 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AudioManager( 5347): getMode name:com.lge.qremote
,I/AudioManager( 5347): getMode name:com.lge.qremote
I/AudioManager( 5347): getMode name:com.lge.qremote
,I/AudioManager( 5347): getMode name:com.lge.qremote
,I/AudioManager( 5347): getMode name:com.lge.qremote
D/UEI.SmartControl( 6007): Quickset Services start...
,I/UEI.SmartControl( 6007): Manufacture = LGE
D/UEI.SmartControl( 6007): File observer start...
E/UEI.SmartControl( 6007): IR Port is disabled: false
D/UEI.SmartControl( 6007): Starting file observer...
D/UEI.SmartControl( 6007): Extracting JNI libs...
D/UEI.SmartControl( 6007): --- this system supports 32-bit or 64-bit only
D/WearableService( 1733): callingUid 10006, callindPid: 1733
D/LocationInitializer( 4397): Restart initialization of location
,E/MDM     ( 1733): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,I/NotificationManager( 5595): com.google.android.talk: cancel(8) by com.google.android.talk
,I/AppUp4:CustModeStarterReceiver( 5691): onReceive
I/AppUp4:CustModeStarterReceiver( 5691): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 5691): Context : android.app.ReceiverRestrictedContext@380a2536
,D/AppUp4:CustFacade( 5691): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5691): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5691): begin check event
I/AppUp4:CustModeStarterReceiver( 5691): Event For Nothing, skip.
,D/LockScreenSettings( 5746): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5746): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5746): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5746): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5746): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 42754(2MB) AllocSpace objects, 37(592KB) LOS objects, 40% free, 13MB/22MB, paused 1.746ms total 114.760ms
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
,I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 4397): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4397): Null package name or gms related package.  Ignoreing.
D/UEI.SmartControl( 6007): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6007): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6007): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/AudioManager( 5347): getMode name:com.lge.qremote
,I/AudioManager( 5347): getMode name:com.lge.qremote
,I/UEI.SmartControl( 6007): --- Selecting new region: 2
I/UEI.SmartControl( 6007): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6007): Platform has CIR...
D/UEI.SmartControl( 6007): NO CIR support, need to check package...
I/UEI.SmartControl( 6007): Model: LG-D722 uses JNI
I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 83 ms] updated apps [took 83 ms] 
D/UEI.SmartControl( 6007): QS Service created
I/Icing   ( 4397): updateResources: need to parse f{com.google.android.gms}
,I/ActivityManager(  983): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6043 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,E/UEI.SmartControl( 6007): QS start get config
,I/CalendarProvider2( 5947): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/UEI.SmartControl( 6007): Loading JNI Libs...
W/ContentResolver( 5947): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
D/UEI.SmartControl( 6007):  configuring local db...
I/ActivityManager(  983): Killing 5764:com.lge.eula/1000 (adj 15): empty #11
D/PhoneMonitor( 6043): Register our PhoneStateListener
,W/libprocessgroup(  983): failed to open /acct/uid_1000/pid_5764/cgroup.procs: No such file or directory
,V/SetupWizard( 6043): Connected to Gservices successfully
I/ActivityManager(  983): Killing 5781:com.lge.bnr/1000 (adj 15): empty #11
,D/PhoneMonitor( 6043): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6043): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6043): [parse] Load xml
V/TelephonyAutoProfiling( 6043): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6043): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6043): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/ChimeraCfgMgr( 4397): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4397): Module APK com.google.android.play.games already loaded
D/UEI.SmartControl( 6007):  ---- Has DB8: true
,D/UEI.SmartControl( 6007): QS start statue = true Error code = 0
D/UEI.SmartControl( 6007): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6007): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6007): IRRCDataComm has AudioManager!!!!.
,W/libprocessgroup(  983): failed to open /acct/uid_1000/pid_5781/cgroup.procs: No such file or directory
W/irrc_jni( 6007): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6007): IrrcClient ++ 
D/irrcClient( 6007): getIrrcService ++ 
,D/irrcClient( 6007): getIrrcService -- 
D/irrcClient( 6007): IrrcClient -- 
W/irrc_jni( 6007): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6007): Services init done
,I/UEI.SmartControl( 6007): Device manager: loading config....
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 6007): Config is loaded...
I/ActivityManager(  983): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6071 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6007):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6007): Notify AllClients services are ready: 0
D/UEI.SmartControl( 6007): QS Service init finished
D/UEI.SmartControl( 6007): QS Service version name: 0.1.73
D/UEI.SmartControl( 6007): QS Service version code: 1073
D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/UEI.SmartControl( 6007): Service requested: Control
D/UEI.SmartControl( 6007): Internal service binding...
,D/UEI.SmartControl( 6007): -----IControl: 11
D/UEI.SmartControl( 6007): Caller: com.lge.qremote
I/Icing   ( 4397): Internal init done: storage state 0
D/UEI.SmartControl( 6007): ------------ IControl registerCallback...
I/UEI.SmartControl( 6007): Registering callback...
D/UEI.SmartControl( 6007): -----IControl: 19
,D/UEI.SmartControl( 6007): Caller: com.lge.qremote
I/UEI.SmartControl( 6007): Registering Services Ready callback...
I/UEI.SmartControl( 6007): Notify client services are ready...
D/UEI.SmartControl( 6007): -----IControl: 8
D/UEI.SmartControl( 6007): Caller: com.lge.qremote
,I/Icing   ( 4397): Post-init done
I/Icing   ( 4397): updateResources: need to parse f{com.google.android.gms}
I/ActivityManager(  983): Killing 5947:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/ActivityManager(  983): Killing 5798:com.google.android.apps.docs/u0a58 (adj 15): empty #12
,W/libprocessgroup(  983): failed to open /acct/uid_10014/pid_5947/cgroup.procs: No such file or directory
,W/libprocessgroup(  983): failed to open /acct/uid_10058/pid_5798/cgroup.procs: No such file or directory
W/ActivityManager(  983): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6071): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6071): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  983): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6071): Error finding the version of the Email provider.....
E/Gmail   ( 6071): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6071): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6071): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6071): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6071): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6071): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6071): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6071): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6071): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6071): getAccountsCursor
I/ActivityManager(  983): Killing 5691:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/ActivityManager(  983): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/libprocessgroup(  983): failed to open /acct/uid_10011/pid_5691/cgroup.procs: No such file or directory
W/ActivityManager(  983): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6071): Observing account changes for notifications
I/art     (  983): Explicit concurrent mark sweep GC freed 23958(1103KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.194ms total 154.710ms
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ActivityManager(  983): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6114 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/Gmail   ( 6071): notifyAccountChanged
,I/Gmail   ( 6071): getAccountsCursor
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6071): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6071): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
W/ResourcesManager( 6114): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/Gmail   ( 6071): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6071): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/CalendarApplication( 6114): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6114): [debug_displayParseInfos] preference keys.size() = 44
D/PreferenceKeysParser( 6114): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@a6e6d1, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@380a2536, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@316c7c37, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@2293d5a4, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@24e21f0d, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@2acb5ec2, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@3b82a4d3, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@330aa810, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@71e9f09, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@2674a50e, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@20c8bb2f, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@13da353c, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@188922c5, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@245a041a, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@2dafdb4b, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@2fb36928, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@365e2641, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@2d0447e6, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@3a9ee127, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@2969efd4, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@3b25e57d, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@36bcfc72, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@158e68c3, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@1b603540, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@27b05c79, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@20da6dbe, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@2964ce1f, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@21b3656c, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@1fd14735, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@17cba7ca, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@3f122d3b, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1b276c58, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@36dc21b1, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@2de47696, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@346c6217, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@cd2f604, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@7e027ed, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@34e96622, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@4cb08b3, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@148b6e70, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@15a455e9, lg_preferences_r,ecent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@245b
D/GeneralPreferenceUtils( 6114): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6114): [init]
I/Config  ( 6114): LGCalendar ver.4.40.17
I/Config  ( 6114): start check model
I/Config  ( 6114): start check native_ca
I/Config  ( 6114): Config Operator=OPEN, Country=EU
D/Config  ( 6114): [setDefaultValuesToPref]
D/Config  ( 6114): [parseProfiles]
D/ProfilesParser( 6114): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6114): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6114): [updateProfiletoCountryInfo]
D/GeneralPreference( 6114): [checkAndMigrateOldPreference]
D/AlertReceiver( 6114): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
I/InitNotificationRingtoneService( 6114): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6114): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/AlertUtils( 6114): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6114): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6114): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6114): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6114): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6114): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6114): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6114): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6114): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6114): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6114): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 6114): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 6114): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6114): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 6114): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6114): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6114): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,I/AlertUtils( 6114): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 6114): End InitializeAlertRingtoneService.onHandleIntent
I/Gmail   ( 6071): getAccountsCursor
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/HolidayIntentService( 6114): onHandleIntent
,D/HolidayDataLoader( 6114): readJsonAsset : holiday.json
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/AlertService( 6114): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 6114): [updateWidgets] 
,D/MonthWidgetProvider( 6114): [onReceive]
D/CalendarWidgetProvider( 6114): [onReceive]
D/CalendarWidgetProvider( 6114): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6114): [onCreate] mContext.getPackageName() = com.android.calendar
,D/WeekWidgetProvider( 6114): [onReceive]
D/CalendarWidgetProvider( 6114): [onReceive]
D/CalendarWidgetProvider( 6114): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6114): [onCreate] mContext.getPackageName() = com.android.calendar
I/AudioManager( 5347): getMode name:com.lge.qremote
,E/HolidayIntentService( 6114): onHandleIntent:holiday data empty
,I/AudioManager( 5347): getMode name:com.lge.qremote
,I/AudioManager( 5347): getMode name:com.lge.qremote
I/Icing   ( 4397): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/InputReader(  983): Reconfiguring input devices.  changes=0x00000010
I/[SystemUI]QSlideListController( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1374): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
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
,D/administrator(  983): Handling package changes for user 0
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/ActivityManager(  983): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6162 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/Icing   ( 4397): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 4397): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/NotificationManager( 5595): com.google.android.talk: cancel(8) by com.google.android.talk
,I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/AppUp4:AppBoxCP( 6162): onCreate
,W/AppUp4:DB( 6162):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6162):  setFingerPrint start
I/AppUp4:DB( 6162):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6162):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
,I/AppUp4:DB( 6162):  SDK version = 0
I/AppUp4:DB( 6162):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6162): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6162): onReceive
I/AppUp4:CustModeStarterReceiver( 6162): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6162): Context : android.app.ReceiverRestrictedContext@380a2536
D/AppUp4:CustFacade( 6162): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6162): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6162): begin check event
I/AppUp4:CustModeStarterReceiver( 6162): Event For Nothing, skip.
I/ActivityManager(  983): Killing 5708:com.android.gallery3d/u0a23 (adj 15): empty #11
W/ResourcesManager(  983): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/NotificationService(  983): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  983): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  983): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
W/libprocessgroup(  983): failed to open /acct/uid_10023/pid_5708/cgroup.procs: No such file or directory
,I/BackupManagerService(  983): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/ActivityManager(  983): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6184 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourceType(  983): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
V/BackupManagerService(  983): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  983): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@215f8844
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/ResourcesManager( 6184): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6184): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6184): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/LocationProviderProxy(  983): applying state to connected service
,D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
I/AppConfig( 6184): Total System Memory = 906309632
I/GalleryUtils( 6184): Application Heap = 96 MB
,I/AppConfig( 6184): App Tier : NOT_DEF
D/SystemHelper( 6184): region [EU], country [EU], operator [OPEN], sub-operator []
D/LockScreenSettings( 5746): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,D/LockScreenSettings( 5746): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5746): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5746): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5746): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  983): Killing 5886:com.android.vending/u0a36 (adj 15): empty #11
,I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 36 ms] updated apps [took 36 ms] 
,W/libprocessgroup(  983): failed to open /acct/uid_10036/pid_5886/cgroup.procs: No such file or directory
,I/ActivityManager(  983): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6207 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/Finsky  ( 6207): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6207): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6207): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 6207): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 6207): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3274): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3274): created cursor android.database.sqlite.SQLiteCursor@3a7e65d on behalf of 6207
,D/Finsky  ( 6207): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6207): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 6207): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 6207): Skipping gmscore version check
D/PackageBroadcastService( 4397): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4397): Null package name or gms related package.  Ignoreing.
D/Finsky  ( 6207): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  983): Killing 6043:com.google.android.setupwizard/u0a38 (adj 15): empty #11
I/Icing   ( 4397): updateResources: need to parse f{com.google.android.gms}
W/libprocessgroup(  983): failed to open /acct/uid_10038/pid_6043/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/Icing   ( 4397): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,V/AlarmManager(  983): ELAPSED_WAKEUP set : Alarm{1689860d type 2 when 90204 com.android.providers.calendar} when 90204
,I/art     (  304): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 290us total 27.131ms
,I/ActivityManager(  983): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6262 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  304): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 267us total 33.741ms
,I/Icing   ( 4397): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 282us total 21.594ms
W/ResourcesManager( 6262): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6262): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@3a2ee55b
,D/CalendarProvider2( 6262): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 6262): Created com.android.providers.calendar.CalendarAlarmManager@2293d5a4(com.android.providers.calendar.CalendarProvider2@3a2ee55b)
,D/CalendarProviderBroadcastReceiver( 6262): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6262): [IntentService] WakeLock acquire, start IntentSerivce
I/art     (  983): Explicit concurrent mark sweep GC freed 27204(1331KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.064ms total 138.688ms
,D/CalendarProvider2( 6262): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6262): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6262): [getOrCreateCalendarAlarmManager]
D/CalendarProvider2( 6262): [IntentService] Release Lock
,D/CalendarProvider2( 6262): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  983): Killing 6007:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 5347): android.os.DeadObjectException
,W/System.err( 5347): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5347): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5347): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5347): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5347): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5347): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5347): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5347): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5347): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5347): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5347): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5347): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5347): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5347): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5347): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5347): android.os.DeadObjectException
W/System.err( 5347): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5347): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5347): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5347): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5347): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5347): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5347): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5347): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5347): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5347): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5347): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5347): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5347): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5347): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5347): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  983): failed to open /acct/uid_10089/pid_6007/cgroup.procs: No such file or directory
,W/ActivityManager(  983): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  983): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6300 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 6300): Quickset Services start...
,I/UEI.SmartControl( 6300): Manufacture = LGE
D/UEI.SmartControl( 6300): File observer start...
E/UEI.SmartControl( 6300): IR Port is disabled: false
D/UEI.SmartControl( 6300): Starting file observer...
D/UEI.SmartControl( 6300): Extracting JNI libs...
D/UEI.SmartControl( 6300): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6300): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6300): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6300): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6300): --- Selecting new region: 2
,I/UEI.SmartControl( 6300): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6300): Platform has CIR...
D/UEI.SmartControl( 6300): NO CIR support, need to check package...
I/UEI.SmartControl( 6300): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6300): QS Service created
E/UEI.SmartControl( 6300): QS start get config
,D/UEI.SmartControl( 6300): Loading JNI Libs...
,D/UEI.SmartControl( 6300):  configuring local db...
I/ActivityManager(  983): Killing 6071:com.google.android.gm/u0a53 (adj 15): empty #11
,D/UEI.SmartControl( 6300):  ---- Has DB8: true
,W/libprocessgroup(  983): failed to open /acct/uid_10053/pid_6071/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6300): QS start statue = true Error code = 0
D/UEI.SmartControl( 6300): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6300): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6300): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6300): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6300): IrrcClient ++ 
D/irrcClient( 6300): getIrrcService ++ 
,D/irrcClient( 6300): getIrrcService -- 
D/irrcClient( 6300): IrrcClient -- 
W/irrc_jni( 6300): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6300): Services init done
I/UEI.SmartControl( 6300): Device manager: loading config....
D/UEI.SmartControl( 6300): QS Service init finished
D/UEI.SmartControl( 6300): Config is loaded...
D/UEI.SmartControl( 6300): QS Service version name: 0.1.73
D/UEI.SmartControl( 6300): QS Service version code: 1073
,D/UEI.SmartControl( 6300): Service requested: Control
I/ActivityManager(  983): Killing 6162:com.lge.appbox.client/u0a11 (adj 15): empty #11
D/UEI.SmartControl( 6300): -----IControl: 11
D/UEI.SmartControl( 6300): Caller: com.lge.qremote
D/UEI.SmartControl( 6300): ------------ IControl registerCallback...
I/UEI.SmartControl( 6300): Registering callback...
D/UEI.SmartControl( 6300): -----IControl: 19
D/UEI.SmartControl( 6300): Caller: com.lge.qremote
I/UEI.SmartControl( 6300): Registering Services Ready callback...
I/UEI.SmartControl( 6300): Notify client services are ready...
D/UEI.SmartControl( 6300): -----IControl: 8
,D/UEI.SmartControl( 6300): Caller: com.lge.qremote
D/UEI.SmartControl( 6300):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6300): Notify AllClients services are ready: 0
W/libprocessgroup(  983): failed to open /acct/uid_10011/pid_6162/cgroup.procs: No such file or directory
D/UEI.SmartControl( 6300): Internal service binding...
,I/AudioManager( 5347): getMode name:com.lge.qremote
I/AudioManager( 5347): getMode name:com.lge.qremote
,I/AudioManager( 5347): getMode name:com.lge.qremote
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/AlertService( 6114): Beginning updateAlertNotification
,D/AlertService( 6114): No fired or scheduled alerts
,I/NotificationManager( 6114): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6114): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6114): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6114): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6114): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6114): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6114): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6114): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6114): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6114): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6114): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6114): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6114): com.android.calendar: cancel(12) by com.android.calendar
,I/NotificationManager( 6114): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6114): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6114): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6114): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6114): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6114): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6114): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6114): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6114): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 6114): No events found starting within 1 week.
,I/ActivityManager(  983): Killing 6114:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  983): failed to open /acct/uid_10013/pid_6114/cgroup.procs: No such file or directory
,I/ActivityManager(  983): Killing 5595:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  983): failed to open /acct/uid_10061/pid_5595/cgroup.procs: No such file or directory
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/Finsky  ( 6207): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 93472143169; DSPS: 3161698; Offset : -3016484323
V/AlarmManager(  983): RTC_WAKEUP set : Alarm{1ff152d4 type 0 when 1457092486938 com.android.vending} when 1457092486938
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  983): android: cancelAsUser(2) by android
,D/libc-netbsd( 6207): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6207): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6207): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6207): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  276): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 6207): propertyValue:false
D/libc-netbsd( 6207): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6207): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6207): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6207): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  983): android: cancelAsUser(2) by android
,I/qtaguid ( 6207): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6207): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6207): untagSocket(41) failed with errno -22
D/Finsky  ( 6207): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
I/ActivityManager(  983): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6346 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  983): android: cancelAsUser(2) by android
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,W/ResourcesManager( 6346): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6346): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6346): VM with version 2.1.0 has multidex support
I/MultiDex( 6346): install
I/MultiDex( 6346): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6346): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6346): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6346): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3645b146: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6346): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6346): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6346): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1733): callingUid 10006, callindPid: 1733
,E/MDM     ( 1733): [145] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 4397): Restart initialization of location
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1733): No location to return for getLastLocation()
,W/FusedLocationProvider( 1733): location=null
D/ChimeraCfgMgr( 6346): Reading stored module config
,D/ChimeraCfgMgr( 6346): Loading module com.google.android.gms.car from APK com.google.android.gms
,D/NativeLibraryUtils( 6346): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6346): Connecting to CarCallService...
I/art     ( 6346): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     ( 6346): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/qtaguid ( 6207): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6207): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6207): untagSocket(41) failed with errno -22
D/CAR.SERVICE( 6346): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6346): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6346): Creating a new PhoneAdapter instance
W/ActivityManager(  983): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.SERVICE( 6346): Package validated; name: com.android.vending
,D/CAR.TEL.PhoneAdapter( 6346): setListener: com.google.android.gms.car.dn@3ad420cd
W/ActivityManager(  983): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6346): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6346): Starting CarCallService with initial phone null
I/NotificationManager( 6207): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 6207): [1] GearheadStateMonitor.access$100: mIsProjecting:false
I/NotificationManager( 6346): com.google.android.gms: cancel(10436) by com.google.android.gms
I/art     ( 6207): CheckpointMarkThreadRoots callback created = 0xb0581420
,I/art     ( 6207): CheckpointMarkThreadRoots callback created = 0xb05813e0
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  983): android: cancelAsUser(2) by android
,D/UEI.SmartControl( 6300): Internal timer expired: 1
,I/qtaguid ( 6207): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6207): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6207): untagSocket(41) failed with errno -22
,W/ResourcesManager( 6207): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6207): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6207): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6207): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  983): RTC_WAKEUP set : Alarm{2c1ff394 type 0 when 1457092489907 com.android.vending} when 1457092489907
,D/DeviceConnectionService( 1733): client connected with version: 8296000
D/Finsky  ( 6207): [739] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6207): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6207): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  983): android: cancelAsUser(2) by android
,D/libc-netbsd( 6207): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6207): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6207): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 6207): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  276): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
,I/System.out( 6207): propertyValue:false
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ActivityManager(  983): Killing 6184:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  983): failed to open /acct/uid_10023/pid_6184/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 6346): mConnectedToCar = false, abort
,E/ActivityThread( 6346): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@18b68415 that was originally bound here
E/ActivityThread( 6346): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@18b68415 that was originally bound here
E/ActivityThread( 6346): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6346): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6346): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6346): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6346): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6346): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6346): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6346): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6346): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6346): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6346): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6346): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6346): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6346): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6346): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6346): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6346): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6346): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6346): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6346): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6346): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6346): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6346): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6346): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3669c664 that was originally bound here
E/ActivityThread( 6346): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3669c664 that was originally bound here
E/ActivityThread( 6346): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6346): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6346): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6346): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6346): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6346): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6346): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6346): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6346): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6346): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6346): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6346): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6346): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6346): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6346): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6346): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6346): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6346): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6346): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6346): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6346): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6346): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  983): Unbind failed: could not find connection for android.os.BinderProxy@16c7b7f5
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/rmt_storage(  272): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  272): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  272): wakelock acquired: 1, error no: 42
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1236806912)
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  272): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1236806912) wakelock released: 1, error no: 0
I/rmt_storage(  272): 
I/rmt_storage(  272): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,W/SQLiteConnectionPool( 4397): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/PowerManagerServiceEx(  983): acquireWakeLockInternal: lock=160704906, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=983
,D/WeatherService( 2705): 2 : TimeTick Intent has been received, Time(hour:min:sec) 12:55:0
,D/WeatherService( 2705): 2 : TimeTick Intent And Screen On
D/WeatherService( 2705): 2 : SDK version : 21
W/ActivityManager(  983): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2705): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2705): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2705): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2705): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2705): 2 : This is isUpdating : false
D/WeatherService( 2705): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2705): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2705): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2705): 2 : Fixed theme : optimus
D/WeatherReflect( 2705): 2 : Map key string is -2
,D/lim     ( 2705): 2 : time = 12:55
I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/WeatherReflect( 2705): Model Name : LG-D722
D/WeatherTheme( 2705): 2 : Different view - status_min_formatted : 54 != 55
D/WeatherTheme( 2705): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,D/WeatherReflect( 2705): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2705): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2705): currentPackage=com.lge.sizechangable.weather.theme.optimus
,I/[SystemUI]Clock( 1374): called onTimeUpdated()
I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
,I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/Weather4x2_optimus( 2705): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2705): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2705): forecast size is 0
D/Theme   ( 2705): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2705): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2705): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2705): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2705): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2705): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2705): setTouchIntent, appWidgetId: 2
D/Theme_WeatherAncestor_optimus( 2705): url is : null
D/Theme   ( 2705): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2705): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
,D/WeatherAncestor( 2705): 2 : update view, appWidgetId: 2
D/WeatherService( 2705): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 12:55:0
,D/PowerManagerServiceEx(  983): releaseWakeLockInternal: lock=160704906 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1878): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/AlarmManager(  983): RTC_WAKEUP set : Alarm{2379ebfb type 0 when 1457092501265 com.google.android.gms} when 1457092501265
,V/AlarmManager(  983): RTC_WAKEUP set : Alarm{3a8de71 type 0 when 1457092504059 com.android.vending} when 1457092504059
,I/CheckinService( 4397): Checkin interval check for package: unspecified last checkin: 1457092471329 min interval config: 0 actual interval: 34791
,W/ContextImpl( 3721): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/CheckinService( 4397): Checking schedule, now: 1457092506179 next: 1457092501265
I/CheckinService( 4397): active receiver: enabled
,I/CheckinService( 4397): Preparing to send checkin request
I/EventLogService( 4397): Accumulating logs since 1457092465481
,I/CheckinRequestBuilder( 4397): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4397): Failed to find provider info for com.google.android.wearable.settings
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  983): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6463 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,D/Finsky  ( 6207): [730] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 6207): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,W/ResourcesManager( 6463): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6463): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6463): VM with version 2.1.0 has multidex support
I/MultiDex( 6463): install
I/MultiDex( 6463): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6463): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6463): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6463): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3645b146: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6463): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6463): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6463): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1733): callingUid 10006, callindPid: 1733
,E/MDM     ( 1733): [150] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 4397): Restart initialization of location
,D/AuthorizationBluetoothService( 1733): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
W/GCoreFlp( 1733): No location to return for getLastLocation()
W/FusedLocationProvider( 1733): location=null
I/art     ( 6463): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6463): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6463): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  280): Instantiating CDM.
,I/WVCdm   (  280): CdmEngine::OpenSession
I/WVCdm   (  280): Level3 Library Dec 11 2014 16:13:16
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,W/WVCdm   (  280): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  280): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  280): L1 library not specified. Falling Back to L3
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 113473614283; DSPS: 3817106; Offset : -3016478183
,I/art     ( 6463): CheckpointMarkThreadRoots callback created = 0xb042d4b0
,I/WVCdm   (  280): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  280): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  280): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  280): CdmEngine::GenerateKeyRequest
I/art     ( 6463): CheckpointMarkThreadRoots callback created = 0xb042d4a0
D/WVCdm   (  280): PrepareKeyRequest: nonce=1096756599
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/dex2oat ( 6498): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6498): dex2oat took 106.795ms (threads: 4)
,I/Adreno-EGL( 6463): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6463): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6463): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6463): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6463): Remote Branch: 
I/Adreno-EGL( 6463): Local Patches: 
I/Adreno-EGL( 6463): Reconstruct Branch: 
,I/Adreno-EGL( 6463): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6463): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6463): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6463): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6463): Remote Branch: 
I/Adreno-EGL( 6463): Local Patches: 
I/Adreno-EGL( 6463): Reconstruct Branch: 
,I/Adreno-EGL( 6463): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6463): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6463): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6463): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6463): Remote Branch: 
I/Adreno-EGL( 6463): Local Patches: 
I/Adreno-EGL( 6463): Reconstruct Branch: 
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/CheckinRequestBuilder( 4397): Classify the device as Phone.
,D/libc-netbsd( 4397): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4397): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4397): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4397): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 4397): propertyValue:false
D/libc-netbsd( 4397): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4397): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4397): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4397): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4397): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4397): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 4397): Sending checkin request (7807 bytes)
I/CheckinRequestBuilder( 4397): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4397): Failed to find provider info for com.google.android.wearable.settings
I/WVCdm   (  280): CdmEngine::CloseSession
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/WVCdm   (  280): L3 Terminate.
,I/art     (  983): Explicit concurrent mark sweep GC freed 26644(1218KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.188ms total 145.556ms
,I/MusicWidget( 2615): mDelayedStopHandler : unbind
,I/MusicBrowser( 2723): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2723): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2723): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2723): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2723): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2723): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2723): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2723): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
,I/MediaFocusControl(  983):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@36bcfc72com.lge.music.MediaPlaybackService$6@158e68c3
,D/MusicBrowser( 2723): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2723): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/CheckinRequestBuilder( 4397): Classify the device as Phone.
,I/MusicBrowser( 2723): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2723): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2723): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@71e9f09
I/MusicBrowser( 2723): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/CheckinTask( 4397): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/MusicBrowser( 2723): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/CheckinService( 4397): Checking schedule, now: 1457092509367 next: 1457619758363
I/CheckinService( 4397): active receiver: disabled
I/MusicBrowser( 2723): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2723): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2723): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2723): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2723): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2723): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2723): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2723): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2723): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/CheckinService( 4397): Recording last checkin time for package unspecified as 1457092509396
I/MusicBrowser( 2723): [MediaPlaybackService.java:6745:release()] oooooo 
,I/MusicBrowser( 2723): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2723): reset
,V/MediaPlayer[Native]( 2723): setListener
,V/MediaPlayer[Native]( 2723): disconnect
V/MediaPlayer[Native]( 2723): destructor
V/AudioFlinger(  280): releasing 19 from 2723 for -1
V/AudioFlinger(  280):  decremented refcount to 0
V/AudioFlinger(  280): purging stale effects
V/MediaPlayer[Native]( 2723): disconnect
D/MusicBrowser( 2723): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2723): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2723): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2723): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2723): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2723): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2723): [SmartShareManagerClient] unregisterListener: 459289920
W/SmartShareClient( 2723): [SmartShareManagerClient] unregisterListener invalid listener: 459289920
I/SmartShareClient( 2723): [SmartShareManagerClient] terminate service: 2723/MediaPlaybackService/829193271
E/HomeCloudIF( 2723): unregiterHomeCloudBroadcast(), Illegal argument.
,I/SmartShareClient( 2723): [SmartShareManagerClient] unbindService context:android.app.Application@27b05c79
I/ActivityManager(  983): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6516 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
V/CloudHub( 2723): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2723): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
,I/CloudHub( 2723): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
I/MusicBrowser( 2723): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2723): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/CloudHub( 2723): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29995
,D/PhoneMonitor( 6516): Register our PhoneStateListener
,V/SetupWizard( 6516): Connected to Gservices successfully
,I/ActivityManager(  983): Killing 5727:com.android.contacts/u0a18 (adj 15): empty #11
D/PhoneMonitor( 6516): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 6516): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6516): [parse] Load xml
V/TelephonyAutoProfiling( 6516): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6516): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6516): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  983): failed to open /acct/uid_10018/pid_5727/cgroup.procs: No such file or directory
,D/GCM     ( 1733): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ActivityManager(  983): Killing 5836:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,I/ActivityManager(  983): Killing 5746:com.lge.lockscreensettings/u0a69 (adj 15): empty #12
,W/libprocessgroup(  983): failed to open /acct/uid_10086/pid_5836/cgroup.procs: No such file or directory
,W/libprocessgroup(  983): failed to open /acct/uid_10069/pid_5746/cgroup.procs: No such file or directory
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QPairHandler( 1374): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  983): Reconfiguring input devices.  changes=0x00000010
,I/QCNEJ   ( 1840): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1878): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,D/administrator(  983): Handling package changes for user 0
I/ActivityManager(  983): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6560 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
I/[LGHome]Launcher( 1878): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
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
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1374): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1374): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,W/ResourcesManager( 6560): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationService(  983): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  983): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  983): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  983): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  983): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  983): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@28f67338
W/ResourcesManager(  983): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourceType(  983): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1878): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1733): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  983): applying state to connected service
,I/Babel_SMS( 6560): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6560): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6560): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6560): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6560): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6560): MmsConfig.loadFromResources
E/Babel_SMS( 6560): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6560): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/LCardEmulationManager( 1786): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1786): getDefaultRoute
,D/SensorManager( 6560): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6560): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6560): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6560): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6560): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6560): found sensor: LGE Linear Acceleration Sensor, handle=30
,D/SensorManager( 6560): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6560): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6560): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6560): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6560): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6560): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6560): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6560): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6560): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6560): found sensor: Motion Accel, handle=46
I/art     ( 6560): CheckpointMarkThreadRoots callback created = 0xb042d880
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
W/Settings( 6560): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6560): startup - clean
I/art     ( 6560): CheckpointMarkThreadRoots callback created = 0xb042d860
,I/Babel   ( 6560): deleted: false for 0
,W/AudioCapabilities( 6560): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6560): Unsupported mime audio/adpcm
,W/AudioCapabilities( 6560): Unsupported mime audio/g726
W/AudioCapabilities( 6560): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6560): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6560): Unsupported mime video/mjpg
W/VideoCapabilities( 6560): Unsupported mime video/theora
,I/ActivityManager(  983): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6597 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/AudioCapabilities( 6560): Unsupported mime audio/evrc
W/AudioCapabilities( 6560): Unsupported mime audio/qcelp
W/VideoCapabilities( 6560): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6560): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6560): Unsupported mime audio/qcelp
W/AudioCapabilities( 6560): Unsupported mime audio/evrc
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,W/VideoCapabilities( 6560): Unsupported mime video/mp4v-esdp
I/AppUp4:AppBoxCP( 6597): onCreate
W/AppUp4:DB( 6597):  [AppBoxDatabaseHelper] construct
,I/AppUp4:DB( 6597):  setFingerPrint start
I/AppUp4:DB( 6597):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6597):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6597):  SDK version = 0
I/AppUp4:DB( 6597):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6597): AppBoxApplication onCreate()
I/VideoCapabilities( 6560): Unsupported profile 4 for video/mp4v-es
I/AppUp4:CustModeStarterReceiver( 6597): onReceive
I/AppUp4:CustModeStarterReceiver( 6597): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6597): Context : android.app.ReceiverRestrictedContext@380a2536
D/AppUp4:CustFacade( 6597): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6597): isSimDevice : true
W/VideoCapabilities( 6560): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6560): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6560): Unrecognized profile 2130706433 for video/avc
D/AppUp4:CustModeStarterReceiver( 6597): begin check event
,I/AppUp4:CustModeStarterReceiver( 6597): Event For Nothing, skip.
,I/ActivityManager(  983): Killing 6262:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/VideoCapabilities( 6560): Unrecognized profile 2130706433 for video/avc
W/libprocessgroup(  983): failed to open /acct/uid_10014/pid_6262/cgroup.procs: No such file or directory
,I/ActivityManager(  983): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6618 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/vclib   ( 6560): onServiceConnected
W/Babel   ( 6560): Attempted to change video mute state without an active call.
I/NotificationManager( 6560): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6560): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6560): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6618): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,V/JNIHelp ( 6560): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppConfig( 6618): Total System Memory = 906309632
I/GalleryUtils( 6618): Application Heap = 96 MB
I/AppConfig( 6618): App Tier : NOT_DEF
,D/SystemHelper( 6618): region [EU], country [EU], operator [OPEN], sub-operator []
W/System  ( 6560): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6560): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6560): com.google.android.talk: cancel(10436) by com.google.android.talk
,I/ActivityManager(  983): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6640 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  983): Killing 6300:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 5347): android.os.DeadObjectException
,W/System.err( 5347): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5347): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5347): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5347): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5347): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5347): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5347): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5347): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5347): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5347): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5347): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5347): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5347): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
,W/System.err( 5347): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5347): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5347): android.os.DeadObjectException
W/System.err( 5347): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5347): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5347): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5347): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5347): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5347): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5347): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5347): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5347): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5347): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5347): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5347): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5347): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5347): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5347): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  983): failed to open /acct/uid_10089/pid_6300/cgroup.procs: No such file or directory
W/ActivityManager(  983): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,W/ResourcesManager( 6640): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6640): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6640): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,W/ResourcesManager( 6640): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6640): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/ActivityManager(  983): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6657 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SystemConfig( 6640): BUILD Country: EU
I/SystemConfig( 6640): BUILD Operator: OPEN
D/UEI.SmartControl( 6657): Quickset Services start...
,I/UEI.SmartControl( 6657): Manufacture = LGE
D/UEI.SmartControl( 6657): File observer start...
E/UEI.SmartControl( 6657): IR Port is disabled: false
D/UEI.SmartControl( 6657): Starting file observer...
D/UEI.SmartControl( 6657): Extracting JNI libs...
D/UEI.SmartControl( 6657): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6657): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 6657): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6657): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/ActivityManager(  983): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6684 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/UEI.SmartControl( 6657): --- Selecting new region: 2
,I/UEI.SmartControl( 6657): -- Running on KitKat(19) and above! JNI will be used.
I/ActivityManager(  983): Killing 5347:com.lge.qremote/u0a106 (adj 15): empty #11
,D/UEI.SmartControl( 6657): Platform has CIR...
D/UEI.SmartControl( 6657): NO CIR support, need to check package...
,I/UEI.SmartControl( 6657): Model: LG-D722 uses JNI
,D/UEI.SmartControl( 6657): QS Service created
W/libprocessgroup(  983): failed to open /acct/uid_10106/pid_5347/cgroup.procs: No such file or directory
,I/SystemConfig( 6640): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6640): existFile = false
I/SystemConfig( 6640): canReadFile = false
I/SystemConfig( 6640): systemFeature RCS result false
D/SystemConfig( 6640): refreshRcsSupport() :false
E/UEI.SmartControl( 6657): QS start get config
,I/LockScreenSettings( 6684): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/UEI.SmartControl( 6657): Loading JNI Libs...
,D/UEI.SmartControl( 6657):  configuring local db...
D/LockScreenSettings( 6684): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6684): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6684): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6684): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6684): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  983): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6707 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  983): Killing 6346:com.google.android.gms:car/u0a6 (adj 15): empty #11
I/art     (  304): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 477us total 22.311ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.650ms
,I/art     (  304): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 271us total 26.921ms
,W/libprocessgroup(  983): failed to open /acct/uid_10006/pid_6346/cgroup.procs: No such file or directory
,W/ResourcesManager( 6707): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6657):  ---- Has DB8: true
,D/UEI.SmartControl( 6657): QS start statue = true Error code = 0
D/UEI.SmartControl( 6657): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6657): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6657): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6657): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6657): IrrcClient ++ 
D/irrcClient( 6657): getIrrcService ++ 
D/irrcClient( 6657): getIrrcService -- 
D/irrcClient( 6657): IrrcClient -- 
W/irrc_jni( 6657): IRRCPlayer_nativeInit -- 
,D/UEI.SmartControl( 6657): Services init done
I/UEI.SmartControl( 6657): Device manager: loading config....
D/UEI.SmartControl( 6657): QS Service init finished
D/UEI.SmartControl( 6657): QS Service version name: 0.1.73
D/UEI.SmartControl( 6657): QS Service version code: 1073
D/UEI.SmartControl( 6657): Config is loaded...
,D/UEI.SmartControl( 6657): Service requested: Control
D/UEI.SmartControl( 6657): Service.onUnbind: IControl
D/UEI.SmartControl( 6657): Service.onDestroy
D/UEI.SmartControl( 6657): Shutdown IRRCPlayer... 
W/irrc_jni( 6657): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6657): ~IrrcClient ++ 
D/irrcClient( 6657): ~IrrcClient -- 
W/irrc_jni( 6657): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6657): Blaster closed
,D/UEI.SmartControl( 6657): Blaster closed
D/UEI.SmartControl( 6657): Shut down QS...
D/UEI.SmartControl( 6657): Stopped file observer...
I/UEI.SmartControl( 6657): QS lib stop result = true
D/UEI.SmartControl( 6657): QS shutdown complete
D/UEI.SmartControl( 6657): QS Service created
,I/UEI.SmartControl( 6657): Notify AllClients services are ready: 11
E/UEI.SmartControl( 6657): QS start get config
D/UEI.SmartControl( 6657):  configuring local db...
,I/UpdateIcingCorporaServi( 1937): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 4397): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4397): Null package name or gms related package.  Ignoreing.
I/UpdateIcingCorporaServi( 1937): UpdateCorporaTask done [took 55 ms] updated apps [took 55 ms] 
I/Icing   ( 4397): updateResources: need to parse f{com.google.android.gms}
,D/UEI.SmartControl( 6657):  ---- Has DB8: true
,D/UEI.SmartControl( 6657): QS start statue = true Error code = 0
D/UEI.SmartControl( 6657): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6657): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6657): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6657): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6657): IrrcClient ++ 
D/irrcClient( 6657): getIrrcService ++ 
D/irrcClient( 6657): getIrrcService -- 
D/irrcClient( 6657): IrrcClient -- 
W/irrc_jni( 6657): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6657): Services init done
I/UEI.SmartControl( 6657): Device manager: loading config....
D/UEI.SmartControl( 6657): QS Service init finished
D/UEI.SmartControl( 6657): QS Service version name: 0.1.73
D/UEI.SmartControl( 6657): Config is loaded...
D/UEI.SmartControl( 6657): QS Service version code: 1073
D/UEI.SmartControl( 6657): Service requested: Control
I/ActivityManager(  983): Killing 2723:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  280): 2723 died, releasing its sessions
V/AudioFlinger(  280):  pid 1751 @ 0
V/AudioFlinger(  280):  pid 3173 @ 1
V/AudioFlinger(  280):  pid 3173 @ 2
,W/libprocessgroup(  983): failed to open /acct/uid_10028/pid_2723/cgroup.procs: No such file or directory
,E/ActivityThread( 6657): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@330aa810 that was originally bound here
E/ActivityThread( 6657): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@330aa810 that was originally bound here
E/ActivityThread( 6657): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6657): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6657): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6657): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6657): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6657): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6657): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6657): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6657): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6657): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6657): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6657): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6657): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6657): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6657): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6657): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6657): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6657): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6657): Internal service binding...
D/UEI.SmartControl( 6657):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6657): Notify AllClients services are ready: 0
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/UEI.SmartControl( 6657): Internal timer expired: 2
W/System.err( 6657): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@330aa810
,W/System.err( 6657): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 6657): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 6657): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 6657): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 6657): 	at com.uei.control.Service.a(Unknown Source)
W/System.err( 6657): 	at com.uei.control.l.run(Unknown Source)
W/System.err( 6657): 	at java.util.Timer$TimerImpl.run(Timer.java:284)
E/UEI.SmartControl( 6657): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@330aa810
I/Icing   ( 4397): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4397): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  983): Killing 6516:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  983): failed to open /acct/uid_10038/pid_6516/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/charger_monitor(  484): vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 295, mChargingStatus=5, mChargingStop=false
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  983): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  983): Killing 6463:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
,W/libprocessgroup(  983): failed to open /acct/uid_10006/pid_6463/cgroup.procs: No such file or directory
,E/UEI.SmartControl( 6657): file observer is disposed!
,D/UEI.SmartControl( 6657): Internal timer expired: 3
,D/UEI.SmartControl( 6657): Service.onUnbind: IControl
D/UEI.SmartControl( 6657): Service.onDestroy
D/UEI.SmartControl( 6657): Shutdown IRRCPlayer... 
W/irrc_jni( 6657): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6657): ~IrrcClient ++ 
D/irrcClient( 6657): ~IrrcClient -- 
W/irrc_jni( 6657): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6657): Blaster closed
D/UEI.SmartControl( 6657): Blaster closed
D/UEI.SmartControl( 6657): Shut down QS...
I/UEI.SmartControl( 6657): QS lib stop result = true
D/UEI.SmartControl( 6657): QS shutdown complete
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 133475403850; DSPS: 4472525; Offset : -3016487304
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/AlarmManager(  983): ELAPSED_WAKEUP set : Alarm{2f94b441 type 2 when 140170 com.google.android.gms} when 140170
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1733): Vacuum at: now=1457092533837 tag=VacuumService
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/art     (  983): Explicit concurrent mark sweep GC freed 34244(1759KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 6.181ms total 159.636ms
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
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
,I/PowerManagerService(  983): ALS enabled for SRE
,D/PowerManagerServiceEx(  983): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (27916 ms ago)
D/qdlights(  983): set_light_backlight: 254
,D/qdlights(  983): set_light_backlight: 250
,D/qdlights(  983): set_light_backlight: 247
,D/qdlights(  983): set_light_backlight: 244
,D/qdlights(  983): set_light_backlight: 240
,D/qdlights(  983): set_light_backlight: 237
,D/qdlights(  983): set_light_backlight: 234
,D/qdlights(  983): set_light_backlight: 230
,D/qdlights(  983): set_light_backlight: 227
,D/qdlights(  983): set_light_backlight: 224
,D/qdlights(  983): set_light_backlight: 220
,D/qdlights(  983): set_light_backlight: 217
,D/qdlights(  983): set_light_backlight: 214
,D/qdlights(  983): set_light_backlight: 210
,D/qdlights(  983): set_light_backlight: 207
,D/qdlights(  983): set_light_backlight: 204
,D/qdlights(  983): set_light_backlight: 200
,D/qdlights(  983): set_light_backlight: 197
,D/qdlights(  983): set_light_backlight: 194
,D/qdlights(  983): set_light_backlight: 190
,D/qdlights(  983): set_light_backlight: 187
,D/qdlights(  983): set_light_backlight: 184
,D/qdlights(  983): set_light_backlight: 180
,D/qdlights(  983): set_light_backlight: 177
,D/qdlights(  983): set_light_backlight: 174
,D/qdlights(  983): set_light_backlight: 170
,D/qdlights(  983): set_light_backlight: 167
,D/qdlights(  983): set_light_backlight: 164
,D/qdlights(  983): set_light_backlight: 160
,D/qdlights(  983): set_light_backlight: 157
,D/qdlights(  983): set_light_backlight: 154
,D/qdlights(  983): set_light_backlight: 150
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
D/qdlights(  983): set_light_backlight: 147
,D/qdlights(  983): set_light_backlight: 144
,D/qdlights(  983): set_light_backlight: 140
,D/qdlights(  983): set_light_backlight: 137
,D/qdlights(  983): set_light_backlight: 134
,D/qdlights(  983): set_light_backlight: 130
,D/qdlights(  983): set_light_backlight: 127
,D/qdlights(  983): set_light_backlight: 124
,D/qdlights(  983): set_light_backlight: 120
,D/qdlights(  983): set_light_backlight: 117
,D/qdlights(  983): set_light_backlight: 114
,D/qdlights(  983): set_light_backlight: 110
,D/qdlights(  983): set_light_backlight: 107
,D/qdlights(  983): set_light_backlight: 103
,D/qdlights(  983): set_light_backlight: 100
,D/qdlights(  983): set_light_backlight: 97
,D/qdlights(  983): set_light_backlight: 93
,D/qdlights(  983): set_light_backlight: 90
,D/qdlights(  983): set_light_backlight: 87
,D/qdlights(  983): set_light_backlight: 83
,D/qdlights(  983): set_light_backlight: 80
,D/qdlights(  983): set_light_backlight: 77
,D/qdlights(  983): set_light_backlight: 73
,D/qdlights(  983): set_light_backlight: 70
,D/qdlights(  983): set_light_backlight: 67
,D/qdlights(  983): set_light_backlight: 63
,D/qdlights(  983): set_light_backlight: 60
,D/qdlights(  983): set_light_backlight: 57
,D/qdlights(  983): set_light_backlight: 53
,D/qdlights(  983): set_light_backlight: 50
,D/qdlights(  983): set_light_backlight: 47
,D/qdlights(  983): set_light_backlight: 43
,D/qdlights(  983): set_light_backlight: 40
,D/qdlights(  983): set_light_backlight: 37
,D/qdlights(  983): set_light_backlight: 33
,D/qdlights(  983): set_light_backlight: 30
,D/qdlights(  983): set_light_backlight: 27
,D/qdlights(  983): set_light_backlight: 23
,D/qdlights(  983): set_light_backlight: 20
,D/qdlights(  983): set_light_backlight: 17
,D/qdlights(  983): set_light_backlight: 13
,D/qdlights(  983): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 153476845246; DSPS: 5127933; Offset : -3016512184
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  983): ALS enabled for SRE
D/PowerManagerServiceEx(  983): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (34907 ms ago)
,I/PowerManagerService(  983): Going to sleep due to screen timeout (uid 1000)...
I/PowerManagerService(  983): ALS enabled for SRE
D/PowerManagerServiceEx(  983): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (34923 ms ago)
,W/ContextImpl(  983): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
I/PowerManagerService(  983): Sleeping (uid 1000)...
D/LPWGController(  983): [updateScreenState] screen on = false
D/LPWGController(  983): disable proximity sensor
D/LPWGController(  983): enable proximity sensor
,I/SensorManager(  983): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@26f1a3be] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  983): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  983): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  983): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
,I/sensors_hal_Ctx(  983): activate: handle is 48, enable
V/sensors_hal_Ctx(  983): activate sensors is 1400000000000
D/sensors_hal_Thresh(  983): enable: handle=48
I/sensors_hal_SAM(  983): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  983): waitForResponse: timeout=1000
V/sensors_hal_SAM(  983): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  983): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  983): enable: Received response: 0
D/PowerManagerServiceEx(  983): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (34967 ms ago)
I/Adreno-EGL(  983): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  983): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  983): Build Date: 03/02/15 Mon
I/Adreno-EGL(  983): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  983): Remote Branch: 
I/Adreno-EGL(  983): Local Patches: 
I/Adreno-EGL(  983): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (148 us)
,I/Sensors (  408): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  983): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  983): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  983): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  983): processInd: handle 48, count=1
,V/sensors_hal_Thresh(  983): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  983): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  983): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  983): poll: count: 256
I/sensors_hal_Ctx(  983): poll: released wakelock sensor_ind
D/sensors_hal_Util(  983): waitForResponse: timeout=0
D/LPWGController(  983): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  983): current mode = 1  value = 1 1
I/LPWGController(  983): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  983): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  983): set_light_backlight: 0
,I/SensorManager(  983): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  983): activate: handle is 46, disable
V/sensors_hal_Ctx(  983): activate sensors is 1000000000000
D/sensors_hal_LP2(  983): enable: handle=46
D/sensors_hal_LP2(  983): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  983): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
I/DisplayManagerService(  983): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  983): Display changed displayId=0
,V/sensors_hal_SAM(  983): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  983): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
D/DSDPConnection( 1751): Display #0 changed.
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
D/SurfaceControl(  983): Excessive delay in setPowerMode(): 238ms
I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
,I/QCOM PowerHAL(  983): Got set_interactive hint
,D/KeyguardViewMediator( 1374): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1332): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1374): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): notifyScreenOffLocked
D/SmartCoverViewMediator( 1332): handleNotifyScreenOFF
,D/JX-Cordova( 4785): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4785): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4785): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@764db2b added. We now have 3 listener(s)
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4785): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4785): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@efa9b88 added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4785): addListener: New listener added - the number of listeners is now 1
D/BluetoothAdapterService(856336400)( 2017): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2d0447e6
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4785): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 4785): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 4785): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 4785): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 4785): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 4785): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 4785): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 4785): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 4785): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 4785): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 4785): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 4785): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 4785): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4785): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 4785): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/KeyguardViewMediator( 1374): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1374): handleNotifyScreenOff
,D/ScreenTurnOffBySensor( 1374): unregisterProximitySensor
,D/StatusBarWindowView( 1374): onScreenTurnedOff why = 3
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1374): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/WifiServerServiceExt(  983): sendKtScanInterval  mRtspPlay : false
V/AudioFlinger(  280): setParameters(): io 0, keyvalue screen_state=on, calling pid 983
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
I/WifiServerServiceExt(  983): set CMD_KT_SCAN_INTERVAL
,D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
,D/GpsLocationProvider(  983): receive broadcast intent, action: android.intent.action.SCREEN_ON
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_ON
,I/QCNEJ   ( 1840): |CORE| sendScreenState: state:true
I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
,I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1803): lockStatus = 0
D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): updateLightsLocked : turn off led
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
,D/LEDHandler( 1803): RESTART MSG
D/SplitWindow(  983): check instance of lgWin Window{17e27535 u0 SearchPanel}
,D/LNfcService( 1786): action : android.intent.action.SCREEN_ON
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
D/NfcService( 1786): Discovery configuration equal, not updating.
,D/InputDispatcher(  983): Window went away: Window{2eaec32b u0 SearchPanel}
I/[SystemUI]Clock( 1374): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1374): time changed, timezoneChanged : false
,I/Sensors (  408): sns_pwr.c(301):releasing wakelock
,D/Ulp_jni (  983): JNI:system_update. Event-0
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  983): ACTION_SCREEN_ON
,D/WeatherService( 2705): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:55:50
D/WeatherService( 2705): 2 : ACTION screen on
D/WeatherService( 2705): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2705): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2705): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 12:55:50
D/AppCleanupService( 4224): android.intent.action.SCREEN_ON
,V/AudioFlinger(  280): setParameters(): io 0, keyvalue screen_state=off, calling pid 983
D/audio_hw_primary(  280): adev_set_parameters: enter: screen_state=off
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
D/WifiController(  983): CMD_SCREEN_OFF 
D/WifiController(  983): shouldWifiStayAwake TRUE
,D/GpsLocationProvider(  983): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.SCREEN_OFF
I/QCNEJ   ( 1840): |CORE| sendScreenState: state:false
,I/LEDService( 1803): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1803): stopPatternFlashing()
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1803): clear
I/Cliptray Service( 1803): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1786): action : android.intent.action.SCREEN_OFF
,I/LEDService( 1803): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1803): set_light_notifications: 0,0,0,0,3
I/LEDService( 1803): updateLightsLocked : turn on led
E/LEDService( 1803): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1803): Can't handle this request of patternId:0
D/LEDHandler( 1803): RESTART MSG
I/[LGHome]EVENT( 1878): [Launcher.java:1711:onReceive()]Screen Off
D/NfcServiceNXP( 1786): mScreenState : 1, mInProvisionMode : false
,V/PhoneApp( 1751): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  983): ACTION_SCREEN_OFF
D/WeatherService( 2705): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:55:50
D/WeatherService( 2705): 2 : ACTION screen off
,D/WeatherService( 2705): 2 : TimeTick Receiver Unregister
D/WeatherService( 2705): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 12:55:50
D/AppCleanupService( 4224): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4224): AppUsageStatsSaveTask
,E/NxpNfcJni( 1786): getReconnectState = 0x0
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
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1374): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  983): ELAPSED_WAKEUP set : Alarm{7203dca type 2 when 160862 com.android.systemui} when 160862
,D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1751): getCallState : 0
D/PhoneUtils( 1751): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1751): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1374): isHdmiPluggedIn :false
,D/KeyguardViewMediator( 1374): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 173479736226; DSPS: 5783386; Offset : -3016457777
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  983): acquireWakeLockInternal: lock=160704906, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=983
,V/AlarmManager(  983): ELAPSED_WAKEUP set : Alarm{2fca0b3b type 2 when 186885 com.google.android.gms} when 186885
D/PowerManagerServiceEx(  983): releaseWakeLockInternal: lock=160704906 [*alarm*], flags=0x0
,I/PhenotypeConfigurator( 1733): Scheduling Phenotype for one-off execution 6072 seconds from now (1457092580642)
,I/PhenotypeFlagCommitter( 1733): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
I/GoogleURLConnFactory( 1733): Using platform SSLCertificateSocketFactory
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 294, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  983): battery changed pluggedType: 2
D/LocationManagerService(  983): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     ( 1733): Explicit concurrent mark sweep GC freed 50762(3MB) AllocSpace objects, 18(288KB) LOS objects, 40% free, 13MB/23MB, paused 5.677ms total 117.178ms
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  983): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 188481750870; DSPS: 6274973; Offset : -3016489476
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  983): ELAPSED_WAKEUP set : Alarm{338e23e9 type 2 when 188610 android} when 188610
,D/LocationManagerService(  983): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1733): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  276): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  276): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  276): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  276): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  276): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  276): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  276): res_queryN name = xxxxx succeed
I/System.out( 1733): propertyValue:false
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1733): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 1733): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/NotificationManager(  983): android: cancelAsUser(2) by android
,I/NotificationManager( 1733): com.google.android.gms: cancel(0) by com.google.android.gms
,D/LocationManagerService(  983): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  983): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  983): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 205985133452; DSPS: 6848521; Offset : -3016401309
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1733): disconnect managed GoogleApiClient
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 220987365940; DSPS: 7340116; Offset : -3016457535
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 240989762530; DSPS: 7995556; Offset : -3016502532
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  983): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 257244623540; DSPS: 8528195; Offset : -3016493635
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 272246983579; DSPS: 9019792; Offset : -3016483371
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 289750641591; DSPS: 9593352; Offset : -3016487209
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  983): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 309752802132; DSPS: 10248782; Offset : -3016463238
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 287, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  983): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 329755044967; DSPS: 10904218; Offset : -3016539894
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/LocationManagerService(  983): remove 1b491923
D/LocationManagerService(  983): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  983): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  983): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  983): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  983): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 349757252634; DSPS: 11559650; Offset : -3016529362
,D/PowerManagerServiceEx(  983): acquireWakeLockInternal: lock=160704906, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=983
,D/PowerManagerServiceEx(  983): releaseWakeLockInternal: lock=160704906 [*alarm*], flags=0x0
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  983): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 369759461874; DSPS: 12215081; Offset : -3016486844
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 384761685333; DSPS: 12706675; Offset : -3016521686
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 402264959831; DSPS: 13280221; Offset : -3016482025
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  983): battery changed pluggedType: 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 422266964551; DSPS: 13935646; Offset : -3016461000
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 442269183758; DSPS: 14591077; Offset : -3016408568
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 457271806422; DSPS: 15082682; Offset : -3016379872
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 472273919770; DSPS: 15574273; Offset : -3016433271
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 282
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 282, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 282
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  983): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 492276057330; DSPS: 16229705; Offset : -3016492900
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 507278197871; DSPS: 16721298; Offset : -3016580218
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 520412426872; DSPS: 17151676; Offset : -3016445275
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 534483753616; DSPS: 17612768; Offset : -3016529819
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  983): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 551986978617; DSPS: 18186320; Offset : -3016722813
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 568243210271; DSPS: 18718993; Offset : -3016380974
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 586066718563; DSPS: 19303035; Offset : -3016421661
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 603570560922; DSPS: 19876617; Offset : -3016910946
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 626074188747; DSPS: 20614004; Offset : -3016548869
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 639210535383; DSPS: 21044453; Offset : -3016463115
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 655466008255; DSPS: 21577105; Offset : -3016239320
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  983): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 676722179548; DSPS: 22273630; Offset : -3016324415
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 691723694738; DSPS: 22765221; Offset : -3016975712
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 707674731414; DSPS: 23287891; Offset : -3016561672
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 721429526972; DSPS: 23738605; Offset : -3016465849
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 277, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  983): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 735037746535; DSPS: 24184519; Offset : -3016461592
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 748175888218; DSPS: 24615026; Offset : -3016350758
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 768807534606; DSPS: 25291083; Offset : -3016326738
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  983): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 791311979651; DSPS: 26028518; Offset : -3016611941
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 806314994155; DSPS: 26520127; Offset : -3016313529
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 821317586124; DSPS: 27011729; Offset : -3016223897
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 834461594245; DSPS: 27442440; Offset : -3016472394
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 848533130370; DSPS: 27903534; Offset : -3016408541
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  983): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 869788333943; DSPS: 28600029; Offset : -3016545465
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 889790530351; DSPS: 29255461; Offset : -3016546375
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  983): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 909792825450; DSPS: 29910895; Offset : -3016509551
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 929794821735; DSPS: 30566312; Offset : -3016252770
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 944796974119; DSPS: 31057915; Offset : -3016633343
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  983): acquireWakeLockInternal: lock=160704906, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=983
,V/AlarmManager(  983): ELAPSED_WAKEUP set : Alarm{2add6721 type 2 when 951918 com.android.bluetooth} when 951918
W/bt-smp  ( 2017): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2017): Plain text(LSB ~ MSB) = e5 e9 65 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 2017): Encrypted text(LSB ~ MSB) = 18 35 02 bc 5a 2e 48 eb fb 92 83 3a 99 8a df b4 
W/bt-btm  ( 2017): Stopping oneshot timer
I/ActivityManager(  983): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7068 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 7068): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7068): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@380a2536
D/PowerManagerServiceEx(  983): releaseWakeLockInternal: lock=160704906 [*alarm*], flags=0x0
I/ActivityManager(  983): Killing 6597:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  983): failed to open /acct/uid_10011/pid_6597/cgroup.procs: No such file or directory
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 967300569408; DSPS: 31795301; Offset : -3016272554
,V/AlarmManager(  983): RTC_WAKEUP set : Alarm{1a372746 type 0 when 1457093362092 com.google.android.gms} when 1457093362092
,I/EventLogService( 4397): Aggregate from 1457092506209 (log), 1457091562004 (data)
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  983): battery changed pluggedType: 2
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 989805129670; DSPS: 32532736; Offset : -3016442855
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 1009807340700; DSPS: 33188169; Offset : -3016459425
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  983): battery changed pluggedType: 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 1029809459927; DSPS: 33843599; Offset : -3016476273
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 1049811694172; DSPS: 34499032; Offset : -3016470175
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 1069813843103; DSPS: 35154461; Offset : -3016426931
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  983): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  983): battery changed pluggedType: 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 1089816020195; DSPS: 35809894; Offset : -3016477674
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 1109818181355; DSPS: 36465325; Offset : -3016483237
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 1129820435199; DSPS: 37120759; Offset : -3016487536
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 1149835420422; DSPS: 37776605; Offset : -3016333935
,D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  983): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 1162966984795; DSPS: 38206905; Offset : -3016483480
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 1177978793511; DSPS: 38698809; Offset : -3016393515
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 1194241946378; DSPS: 39231726; Offset : -3016576750
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2017): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1840): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1840): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1803): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1803): Battery Level Remaining: 100%
D/LEDHandler( 1803): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1374): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1374): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/[SystemUI]BatterySaverHandler( 1374): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  983): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  983): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  983): battery changed pluggedType: 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 1214243937104; DSPS: 39887152; Offset : -3016600211
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/UsageStatsService(  983): User[0] Flushing usage stats to disk
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 1229246276829; DSPS: 40378746; Offset : -3016518839
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 1242378030742; DSPS: 40809045; Offset : -3016448381
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1374): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1374): called onTimeUpdated()
I/[SystemUI]Clock( 1374): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
I/[SystemUI]DateView( 1374): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1374): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 1255509692233; DSPS: 41239346; Offset : -3016531247
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1374): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1374): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1374): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1374): On Skip Timer : true
,D/PowerService( 1803): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  484): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 1270512025723; DSPS: 41730941; Offset : -3016486446
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  983): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  983): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  983): tsOffsetIs: Apps: 1283805902412; DSPS: 42166545; Offset : -3016188885
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,TIME-OUT KILL (timeout was 1200000ms)
```
