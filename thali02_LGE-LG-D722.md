#### Test 61362366121daa0_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
I/IndexDatabaseHelper( 5229): Using schema version: 115
I/IndexDatabaseHelper( 5229): Index is fine
,D/UsbSettingsReceiver( 5229): [AUTORUN] onReceive() : action = android.hardware.usb.action.USB_STATE
D/UsbSettingsReceiver( 5229): [AUTORUN] sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5229): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5229): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5229): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsReceiver( 5229): [AUTORUN] onReceive() : getDefaultFunction = ptp_only
D/UsbSettingsReceiver( 5229): [AUTORUN] onReceive() : USB_FUNCTION_CDROM_STORAGE = false
D/UsbSettingsReceiver( 5229): [AUTORUN] onReceive() : mDirectAutorun = true
D/UsbSettingsReceiver( 5229): [AUTORUN] onReceive() : mActivityUsbModeChange = false
D/UsbSettingsReceiver( 5229): [AUTORUN] onReceive() : mActivityFinish = false
D/UsbSettingsReceiver( 5229): [AUTORUN] onReceive() : ===== USB Configured =====
D/UsbSettingsControl( 5229): [AUTORUN] setUsbConnected() : connected=true
D/UsbSettingsReceiver( 5229): [AUTORUN] onReceive() : checkQmicm = ptp_only,adb
D/UsbSettingsReceiver( 5229): [AUTORUN] : topPackageName=com.lge.launcher2
D/UsbSettingsReceiver( 5229): [AUTORUN] : topClassName=com.lge.launcher2.Launcher
D/UsbSettingsReceiver( 5229): [AUTORUN] Not exist com.android.LGSetupWizard
D/UsbSettingsReceiver( 5229): [AUTORUN] setUsbConnect() : mUsbSettingsRun = false
D/UsbSettingsReceiver( 5229): [AUTORUN] startUsbSettings() : deviceProvisioned=1
--------- beginning of system
I/ActivityManager(  964): Killing 4918:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  964): failed to open /acct/uid_10038/pid_4918/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  964): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5259 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
D/MtpService( 3169): updating state; isCurrentUser=true, mMtpLocked=false
V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{22a82186 type 2 when 76328 android} when 76328
I/PCSuite ( 5259): [StartReceiver]USB CONNECTED ver UsbManger : ptp_only
D/AndroidRuntime( 5252): 
D/AndroidRuntime( 5252): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/PCSuite ( 5259): [StartReceiver]isUsbPCSuiteMode : false
D/AndroidRuntime( 5252): CheckJNI is OFF
D/PCSuite ( 5259): [StartReceiver][checkEUTStatus] eutStatus = 
D/PCSuite ( 5259): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5259): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  964): Killing 4941:com.lge.drmservice/u0a51 (adj 15): empty #11
I/WVCdm   (  279): CdmEngine::CloseSession
I/WVCdm   (  279): L3 Terminate.
D/WeatherAncestor( 2623): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:36:8
W/libprocessgroup(  964): failed to open /acct/uid_10051/pid_4941/cgroup.procs: No such file or directory
D/UpdateThreadPoolManager( 2623): 2 : This is isUpdating : false
D/WeatherAncestor( 2623): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 14:36:8
D/WeatherService( 2623): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
W/ActivityManager(  964): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2623): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2623): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2623): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2623): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2623): 2 : This is isUpdating : false
D/WeatherService( 2623): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2623): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2623): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2623): 2 : Fixed theme : optimus
V/UserPresentBroadcastReceiver( 1730): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/WeatherReflect( 2623): 2 : Map key string is -2
D/lim     ( 2623): 2 : time = 14:36
I/WeatherReflect( 2623): Model Name : LG-D722
D/WeatherTheme( 2623): 2 : exactly same view!
D/WeatherTheme( 2623): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
W/ActivityManager(  964): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2623): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2623): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2623): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
V/LGMDMManager( 5208): Create singleton instance
I/dex2oat ( 5295): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=43 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
I/dex2oat ( 5295): dex2oat took 71.160ms (threads: 4)
I/Adreno-EGL( 5028): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5028): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5028): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5028): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5028): Remote Branch: 
I/Adreno-EGL( 5028): Local Patches: 
I/Adreno-EGL( 5028): Reconstruct Branch: 
I/DigitalAppWidgetProvider( 5186): onReceive: android.intent.action.ALARM_CHANGED
D/WeatherAncestor( 2623): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:36:8
D/UpdateThreadPoolManager( 2623): 2 : This is isUpdating : false
D/Weather_cast( 2623): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2623): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 14:36:8
D/WeatherService( 2623): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
W/ActivityManager(  964): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2623): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2623): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2623): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/AlertReceiver( 3857): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
D/AlertService( 3857): 0 Action = android.intent.action.PROVIDER_CHANGED
E/AgendaWidgetManager( 3857): [updateWidgets] 
D/MonthWidgetProvider( 3857): [onReceive]
D/CalendarWidgetProvider( 3857): [onReceive]
D/CalendarWidgetProvider( 3857): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 3857): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 3857): [onReceive]
D/CalendarWidgetProvider( 3857): [onReceive]
D/CalendarWidgetProvider( 3857): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 3857): [onCreate] mContext.getPackageName() = com.android.calendar
D/CalendarWeatherReceiver( 3857): Get action=com.lge.calendar.action.WEATHER_SERVICE_START
D/AndroidRuntime( 5252): Calling main entry com.android.commands.am.Am
I/[SystemUI]SafeModeBroadcastReceiver( 1371): onReceive = com.lge.statusbar.bootcompleted
I/Adreno-EGL( 5028): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5028): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5028): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5028): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5028): Remote Branch: 
I/Adreno-EGL( 5028): Local Patches: 
I/Adreno-EGL( 5028): Reconstruct Branch: 
I/ActivityManager(  964): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.MediaScanReceiver: pid=5305 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  964): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
I/Adreno-EGL( 5028): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5028): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5028): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5028): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5028): Remote Branch: 
I/Adreno-EGL( 5028): Local Patches: 
I/Adreno-EGL( 5028): Reconstruct Branch: 
D/ActivityManager(  964): setTaskToReturnTo : TaskRecord{306e43e3 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/ActivityManager(  964): setTaskToReturnTo : TaskRecord{306e43e3 #222 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
D/WindowStateEx(  964): AppWindowTokenEx init.. 
D/ContextHelper(  964): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
I/[LGHome]EVENT( 1873): [Launcher.java:986:onPause()]onPause
D/InputDispatcher(  964): Focus left window: Window{12917178 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/PhoneWindow(  964): [generateLayout] setColorNavigationBar => color=0x ff000001
D/AndroidRuntime( 5252): Shutting down VM
D/PhoneWindowEx(  964): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  964): [setNavigationBarColor2] color=0x fff5f5f5
D/SplitWindow(  964): check instance of lgWin Window{6e4c5b u0 Starting com.test.thalitest}
I/ActivityManager(  964): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5325 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/[LGHome]EVENT( 1873): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/[LGHome]EVENT( 1873): [Launcher.java:5214:onStop()]onStop
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
I/WindowStateAnimator(  964): Starting window displayed
D/WindowManager(  964): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/SystemUI[Framework](  964): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
I/[SystemUI]NavigationThemeResource( 1371): notify navigation bar color(0xfff5f5f5)
W/PhoneWindowManagerEx(  964): Call!!!getLGSystemUiVisibility. =0x0
D/StatusBarManagerServiceEx(  964): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  964): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  964): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2a0028a8,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  964): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1371): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1371):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1371): , Keyguard show=false, IME shown=false, Panel expanded=false
D/UEI.SmartControl( 5048): Internal timer expired: 1
D/UEI.SmartControl( 5048): Service.onUnbind: IControl
D/UEI.SmartControl( 5048): Service.onDestroy
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/UEI.SmartControl( 5048): Shutdown IRRCPlayer... 
W/irrc_jni( 5048): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5048): ~IrrcClient ++ 
D/irrcClient( 5048): ~IrrcClient -- 
W/irrc_jni( 5048): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5048): Blaster closed
D/UEI.SmartControl( 5048): Blaster closed
I/ActivityManager(  964): Activity reported stop, but no longer stopping: ActivityRecord{3fbc5217 u0 com.lge.launcher2/.Launcher t221}
,D/UEI.SmartControl( 5048): Shut down QS...
D/UEI.SmartControl( 5048): Stopped file observer...
I/UEI.SmartControl( 5048): QS lib stop result = true
I/HotwordDetector( 1949): Closing mic
D/UEI.SmartControl( 5048): QS shutdown complete
I/MicrophoneInputStream( 1949): mic_close com.google.android.apps.gsa.speech.audio.u@dfa6f46
V/AudioRecord( 1949): stop()
D/AudioRecord( 1949): AudioRecord->stop()
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioFlinger(  279): Record stopped OK
V/AudioPolicyManager(  279): stopInput() input 17
V/AudioPolicyService(  279): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  279): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  279): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  279): ThreadBase::setParameters() routing=0
D/audio_hw_primary(  279): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
D/ContextHelper( 5325): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
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
V/AudioFlinger(  279): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioFlinger(  279): processConfigEvents_l() remaining events 1
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb39f6000
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioPolicyManager(  279): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  279): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  279): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  279): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioPolicyService(  279): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
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
V/AudioFlinger(  279): processConfigEvents_l() DONE thread 0xb39f6000
V/AudioFlinger(  279): RecordThread: loop stopping
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioRecord( 1949): stop()
V/AudioRecord( 1949): stop()
V/AudioRecord( 1949): stop()
V/AudioFlinger(  279): releasing 16 from 1949 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/AudioFlinger(  279): RecordHandle::stop()
V/AudioFlinger(  279): RecordThread::stop
V/AudioPolicyManager(  279): releaseInput() 17
V/AudioPolicyManager(  279): closeInput(17)
V/AudioFlinger(  279): closeInput() 17
V/AudioSystem(  279): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): ThreadBase::exit
V/AudioSystem( 2652): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  279): RecordThread: loop starting
V/AudioFlinger(  279): RecordThread 0xb39f6000 exiting
D/audio_hw_primary(  279): adev_close_input_stream: enter:stream_handle(0xb546dd40)
D/audio_hw_primary(  279): in_standby: enter: stream (0xb546dd40) usecase(7: audio-record)
V/audio_hw_primary(  279): in_standby: exit:  status(0)
V/AudioPolicyService(  279): AudioCommandThread() adding update audio port list
V/AudioSystem( 1371): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1949): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2053): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3141): ioConfigChanged() event 4, ioHandle 17
V/AudioPolicyService(  279): inserting command: 9 at index 0, num commands 0
V/AudioPolicyManager(  279): releaseInput() exit
V/AudioPolicyService(  279): AudioCommandThread() waking up
V/AudioFlinger(  279): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioPolicyService(  279): AudioCommandThread() processing update audio port list
V/AudioFlinger(  279): removeClient_l() pid 1949, calling pid 279
V/AudioPolicyService(  279): AudioCommandThread() going to sleep
V/AudioSystem(  964): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1748): ioConfigChanged() event 4, ioHandle 17
I/HotwordRecognitionRnr( 1949): Stopping hotword detection.
I/HotwordRecognitionRnr( 1949): Hotword detection finished
I/WebViewFactory( 5325): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
I/LibraryLoader( 5325): Time to load native libraries: 2 ms (timestamps 7462-7464)
I/LibraryLoader( 5325): Expected native library version number "",actual native library version number ""
E/MediaScanReceiver( 5305): media scanning start or checking
W/MainApplication( 5305): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
V/WebViewChromiumFactoryProvider( 5325): Binding Chromium to main looper Looper (main, tid 1) {3a3d3b8f}
I/LibraryLoader( 5325): Expected native library version number "",actual native library version number ""
I/chromium( 5325): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/ActivityManager(  964): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5352 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  964): Killing 4967:com.google.android.talk/u0a61 (adj 15): empty #11
I/BrowserStartupController( 5325): Initializing chromium process, singleProcess=true
W/art     ( 5325): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5325): ApplicationContext is null in ApplicationStatus
W/chromium( 5325): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5325): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5325): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5325): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5325): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5325): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5325): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5325): Remote Branch: 
I/Adreno-EGL( 5325): Local Patches: 
I/Adreno-EGL( 5325): Reconstruct Branch: 
W/libprocessgroup(  964): failed to open /acct/uid_10061/pid_4967/cgroup.procs: No such file or directory
V/AudioPolicyService(  279): registerClient() client 0xb4027040, uid 10316
D/BluetoothManagerService(  964): Message: 20
D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@17810428:true
,D/BluetoothAdapterService(551503866)( 2053): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a1dc820
I/CheckinRequestBuilder( 4381): Classify the device as Phone.
,W/art     ( 5325): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5325): onDetachedFromWindow called when already detached. Ignoring
,I/PhoneWindow( 5325): [generateLayout] setColorNavigationBar => color=0x ff000001
D/PhoneWindowEx( 5325): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 5325): [setNavigationBarColor2] color=0x fff5f5f5
I/MusicStore( 5352): Database version: 120
,D/SystemWebViewEngine( 5325): CordovaWebView is running on device made by: LGE
W/art     ( 5325): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5325): Attempt to remove local handle scope entry from IRT, ignoring
D/libc-netbsd( 4381): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4381): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4381): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4381): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  272): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 4381): propertyValue:false
I/Activity( 5325): Activity.onPostResume() called 
,D/OpenGLRenderer( 5325): Render dirty regions requested: true
I/OpenGLRenderer( 5325): Initialized EGL, version 1.4
E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5352): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/OpenGLRenderer( 5325): Enabling debug mode 0
D/Atlas   ( 5325): Validating map...
,D/SplitWindow(  964): check instance of lgWin Window{22727a7a u0 com.test.thalitest/com.test.thalitest.MainActivity}
W/chromium( 5325): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
D/InputDispatcher(  964): Focus entered window: Window{22727a7a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,D/libc-netbsd( 4381): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4381): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,W/InputMethodManagerService(  964): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,I/ActivityManager(  964): Displayed com.test.thalitest/.MainActivity: +1s139ms
I/Timeline(  964): Timeline: Activity_windows_visible id: ActivityRecord{1c3441e0 u0 com.test.thalitest/.MainActivity t222} time:78166
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5352): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
I/Timeline( 5325): Timeline: Activity_idle id: android.os.BinderProxy@30d7b711 time:78178
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5352): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
D/libc-netbsd( 4381): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4381): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4381): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4381): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/ResourcesManager( 5352): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5352): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/CheckinTask( 4381): Sending checkin request (9797 bytes)
,V/JNIHelp ( 5352): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/BindingManager( 5325): Cannot call determinedVisibility() - never saw a connection for the pid: 5325
,W/ActivityThread( 5352): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5352): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@d5ceb5b: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5352): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5352): GMSCore installation verified
,I/ConfigStore( 5352): Config Database version: 1
,I/MediaRouter( 5352): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,I/NetworkMonitor( 5352): type=WIFI subType= reason=null isConnected=true
,D/ToneMappingReceiver( 5186): Enter doAlarmRingToneUriMapping()
,I/NetworkMonitor( 5352): type=WIFI subType= reason=null isConnected=true
,D/ToneMappingReceiver( 5186): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
,D/CommonUtil( 5186): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5186): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5186): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5186): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5186): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5186): Alarm Success count is 0
,D/ToneMappingReceiver( 5186): Timer Success count is 0
I/GHttpClientFactory( 5352): Using our fixed implementation of GMSCore's GoogleHttpClient
I/MediaScannerReceiver( 3857): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///system/media
I/GoogleURLConnFactory( 5352): Using platform SSLCertificateSocketFactory
,I/InitNotificationRingtoneService( 3857): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3857): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
E/MediaScanReceiver( 5305): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 5305): android.intent.action.MEDIA_SCANNER_FINISHED
,I/AlertUtils( 3857): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,E/MediaScanReceiver( 5305): media scanning start or checking
,I/NotificationManager( 5352): com.google.android.music: cancel(1061) by com.google.android.music
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
D/ToneMappingReceiver( 5186): Enter doAlarmRingToneUriMapping()
,D/ToneMappingReceiver( 5186): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5186): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5186): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5186): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5186): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5186): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5186): Alarm Success count is 0
,I/art     ( 3169): Explicit concurrent mark sweep GC freed 16679(1061KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/10MB, paused 599us total 63.887ms
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
D/ToneMappingReceiver( 5186): Timer Success count is 0
,I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/ActivityManager(  964): Killing 5001:com.google.android.apps.magazines/u0a79 (adj 15): empty #11
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
,I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/CheckinRequestBuilder( 4381): Checkin reason type: 8 attempt count: 1
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3857): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
,D/JsMessageQueue( 5325): Set native->JS mode to OnlineEventsBridgeMode
,I/MediaScannerReceiver( 3857): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///storage/emulated/0
W/libprocessgroup(  964): failed to open /acct/uid_10079/pid_5001/cgroup.procs: No such file or directory
,I/AlertUtils( 3857): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3857): End InitializeAlertRingtoneService.onHandleIntent
E/ActivityThread( 4381): Failed to find provider info for com.google.android.wearable.settings
E/MediaScanReceiver( 5305): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 5305): android.intent.action.MEDIA_SCANNER_FINISHED
I/InitNotificationRingtoneService( 3857): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3857): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/ActivityManager(  964): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5426 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 280us total 22.411ms
,I/AlertUtils( 3857): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 21.926ms
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.342ms
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,D/jxcore_app_log( 5325): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426162048
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5325): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5325):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5325):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5325):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5325):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5325): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1463b18b added. We now have 1 listener(s)
W/ResourcesManager( 5426): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5325): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5325):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5325):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5325):     - Bluetooth MAC address: F8:95:C7:87:85:54
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5325):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5325):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5325):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5325):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5325):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5325):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5325): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38c1c326 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5325): addListener: New listener added - the number of listeners is now 1
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
D/BluetoothAdapterService(551503866)( 2053): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a1dc820
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5325): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 5325): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
I/AlertUtils( 3857): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3857): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
W/System.err( 5325): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 5325): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 5325): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 5325): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 5325): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 5325): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 5325): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 5325): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 5325): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 5325): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 5325): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5325): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5325): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/AlertUtils( 3857): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3857): End InitializeAlertRingtoneService.onHandleIntent
D/JX-Cordova( 5325): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5325): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5325): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@959db67 added. We now have 2 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5325): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5325): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34c5fd14 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5325): addListener: New listener added - the number of listeners is now 1
D/BluetoothAdapterService(551503866)( 2053): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a1dc820
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5325): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 5325): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 5325): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 5325): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 5325): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 5325): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 5325): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 5325): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 5325): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 5325): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 5325): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 5325): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 5325): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5325): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5325): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/CalendarProvider2( 5426): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@24607a6d
,I/art     ( 5352): CheckpointMarkThreadRoots callback created = 0xb042d3f0
,D/CalendarProvider2( 5426): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 5426): Created com.android.providers.calendar.CalendarAlarmManager@28a36aee(com.android.providers.calendar.CalendarProvider2@24607a6d)
D/CalendarProviderBroadcastReceiver( 5426): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
,I/art     ( 5352): CheckpointMarkThreadRoots callback created = 0xb042d3b0
D/CalendarProviderBroadcastReceiver( 5426): [IntentService] WakeLock acquire, start IntentSerivce
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/CalendarProvider2( 5426): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 5426): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5426): [getOrCreateCalendarAlarmManager]
I/MediaStoreImporter( 5352): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/WearableService( 1730): callingUid 10006, callindPid: 1730
,I/CheckinRequestBuilder( 4381): Classify the device as Phone.
,E/MDM     ( 1730): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 4381): Restart initialization of location
,D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
D/CalendarProvider2( 5426): [IntentService] Release Lock
D/CalendarProvider2( 5426): CalendarProviderIntentService.onDestroy()
,I/ActivityManager(  964): Killing 5048:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinTask( 4381): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
W/libprocessgroup(  964): failed to open /acct/uid_10089/pid_5048/cgroup.procs: No such file or directory
,I/CheckinService( 4381): Checking schedule, now: 1456925771502 next: 1457453020413
I/CheckinService( 4381): active receiver: disabled
,D/CheckinService( 4381): Recording last checkin time for package unspecified as 1456925771532
,I/ActivityManager(  964): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5454 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
,W/IcingInternalCorpora( 4381): getNumBytesRead when not calculated.
,W/ActivityManager(  964): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5454): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 5454): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  964): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  964): Process com.android.settings (pid 5229) has died
,W/ActivityManager(  964): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
E/Gmail   ( 5454): Error finding the version of the Email provider.....
E/Gmail   ( 5454): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5454): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5454): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5454): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5454): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5454): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5454): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5454): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 5454): We do not support migrating this version of the Email provider.
,I/Gmail   ( 5454): getAccountsCursor
I/Gmail   ( 5454): Observing account changes for notifications
,I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5495 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
W/ActivityManager(  964): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/art     (  964): Explicit concurrent mark sweep GC freed 34728(1780KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.543ms total 172.073ms
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ResourcesManager( 5495): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/Gmail   ( 5454): notifyAccountChanged
,I/Gmail   ( 5454): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5454): getAccountsCursor
,I/Gmail   ( 5454): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 5454): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5454): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5454): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 4038): Explicit concurrent mark sweep GC freed 3207(125KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 439us total 24.365ms
,I/Babel_SMS( 5495): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 5495): MmsConfig.loadMmsSettings
,I/Babel_SMS( 5495): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 5495): MmsConfig.loadFromDatabase
,E/Babel_SMS( 5495): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 5495): MmsConfig.loadFromResources
E/Babel_SMS( 5495): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 5495): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/art     ( 5495): CheckpointMarkThreadRoots callback created = 0xb042d880
,D/SensorManager( 5495): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 5495): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 5495): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 5495): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 5495): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 5495): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 5495): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 5495): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 5495): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 5495): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 5495): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 5495): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 5495): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 5495): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 5495): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 5495): found sensor: Motion Accel, handle=46
I/art     ( 5495): CheckpointMarkThreadRoots callback created = 0xb042d870
,W/art     ( 5495): Suspending all threads took: 10.937ms
,W/Settings( 5495): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 5495): startup - clean
I/Babel   ( 5495): deleted: false for 0
,W/AudioCapabilities( 5495): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5495): Unsupported mime audio/adpcm
W/AudioCapabilities( 5495): Unsupported mime audio/g726
W/AudioCapabilities( 5495): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5495): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5495): Unsupported mime video/mjpg
W/VideoCapabilities( 5495): Unsupported mime video/theora
,W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
V/DownloadManager( 3169): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3169): created cursor android.database.sqlite.SQLiteCursor@34c5fd14 on behalf of 4381
W/AudioCapabilities( 5495): Unsupported mime audio/evrc
W/AudioCapabilities( 5495): Unsupported mime audio/qcelp
W/VideoCapabilities( 5495): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5495): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 5495): Unsupported mime audio/qcelp
W/AudioCapabilities( 5495): Unsupported mime audio/evrc
,W/VideoCapabilities( 5495): Unsupported mime video/mp4v-esdp
I/art     ( 4381): Explicit concurrent mark sweep GC freed 15867(1282KB) AllocSpace objects, 25(400KB) LOS objects, 40% free, 12MB/20MB, paused 1.232ms total 94.284ms
,I/VideoCapabilities( 5495): Unsupported profile 4 for video/mp4v-es
W/VideoCapabilities( 5495): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5495): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5495): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5495): Unrecognized profile 2130706433 for video/avc
I/ActivityManager(  964): Process com.google.android.apps.plus (pid 5139) has died
,I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5547 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,V/DownloadManager( 3169): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
V/DownloadManager( 3169): created cursor android.database.sqlite.SQLiteCursor@1ce109bd on behalf of 4381
I/vclib   ( 5495): onServiceConnected
W/Babel   ( 5495): Attempted to change video mute state without an active call.
V/DownloadManager( 3169): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3169): created cursor android.database.sqlite.SQLiteCursor@21f6ebb2 on behalf of 4381
W/ResourcesManager( 5495): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5495): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
V/JNIHelp ( 5495): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,D/PhoneMonitor( 5547): Register our PhoneStateListener
,W/System  ( 5495): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5495): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  964): Process com.android.chrome (pid 5108) has died
,I/NotificationManager( 5495): com.google.android.talk: cancel(10436) by com.google.android.talk
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/PhoneMonitor( 5547): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,V/TelephonyAutoProfiling( 5547): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 5547): [parse] Load xml
V/TelephonyAutoProfiling( 5547): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
,V/TelephonyAutoProfiling( 5547): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5547): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/CheckinService( 4381): Checkin interval check for package: unspecified last checkin: 1456925771532 min interval config: 0 actual interval: 1986
,I/CheckinService( 4381): Checking schedule, now: 1456925773527 next: 1456925801413
I/CheckinService( 4381): active receiver: disabled
D/InitAlarmsService( 3857): Clearing and rescheduling alarms.
,I/ActivityManager(  964): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5575 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AudioManager( 5208): getMode name:com.lge.qremote
D/CalendarProvider2( 5426): Scheduling check of next Alarm
D/CalendarProvider2( 5426): SCHEDULE_ALARM_REMOVE
,I/AudioManager( 5208): getMode name:com.lge.qremote
I/AudioManager( 5208): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5575): Quickset Services start...
,I/UEI.SmartControl( 5575): Manufacture = LGE
I/AudioManager( 5208): getMode name:com.lge.qremote
D/UEI.SmartControl( 5575): File observer start...
E/UEI.SmartControl( 5575): IR Port is disabled: false
D/UEI.SmartControl( 5575): Starting file observer...
D/UEI.SmartControl( 5575): Extracting JNI libs...
I/AudioManager( 5208): getMode name:com.lge.qremote
D/UEI.SmartControl( 5575): --- this system supports 32-bit or 64-bit only
E/MDM     ( 1730): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 4381): Restart initialization of location
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 5208): getMode name:com.lge.qremote
,D/AlertService( 3857): Beginning updateAlertNotification
D/UEI.SmartControl( 5575): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5575): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5575): --- Extracting JNI libs: libqs_armeabi-v7a.zip
D/AlertService( 3857): No fired or scheduled alerts
,I/NotificationManager( 3857): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3857): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3857): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 5495): com.google.android.talk: cancel(8) by com.google.android.talk
I/NotificationManager( 3857): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3857): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3857): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 3857): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3857): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3857): com.android.calendar: cancel(8) by com.android.calendar
,I/NotificationManager( 3857): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 3857): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3857): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3857): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3857): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3857): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3857): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3857): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3857): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3857): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3857): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 3857): com.android.calendar: cancel(20) by com.android.calendar
I/UEI.SmartControl( 5575): --- Selecting new region: 2
I/UEI.SmartControl( 5575): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5575): Platform has CIR...
D/UEI.SmartControl( 5575): NO CIR support, need to check package...
I/UEI.SmartControl( 5575): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5575): QS Service created
I/ActivityManager(  964): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5602 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/AlertService( 3857): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 3857): No events found starting within 1 week.
,E/UEI.SmartControl( 5575): QS start get config
I/AppUp4:AppBoxCP( 5602): onCreate
,D/UEI.SmartControl( 5575): Loading JNI Libs...
W/AppUp4:DB( 5602):  [AppBoxDatabaseHelper] construct
D/UEI.SmartControl( 5575):  configuring local db...
I/AppUp4:DB( 5602):  setFingerPrint start
I/AppUp4:DB( 5602):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 5602):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5602):  SDK version = 0
I/AppUp4:DB( 5602):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5602): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 5602): onReceive
I/AppUp4:CustModeStarterReceiver( 5602): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 5602): Context : android.app.ReceiverRestrictedContext@5bc2f0
D/AppUp4:CustFacade( 5602): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5602): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 5602): begin check event
I/AppUp4:CustModeStarterReceiver( 5602): Event For Nothing, skip.
,I/ActivityManager(  964): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5621 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 5621): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5621): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5621): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/UEI.SmartControl( 5575):  ---- Has DB8: true
,V/AlarmManager(  964): RTC_WAKEUP set : Alarm{2fba9711 type 0 when 1456925774311 com.google.android.googlequicksearchbox} when 1456925774311
D/UEI.SmartControl( 5575): QS start statue = true Error code = 0
D/UEI.SmartControl( 5575): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5575): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5575): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 5575): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5575): IrrcClient ++ 
D/irrcClient( 5575): getIrrcService ++ 
,D/irrcClient( 5575): getIrrcService -- 
D/irrcClient( 5575): IrrcClient -- 
W/irrc_jni( 5575): IRRCPlayer_nativeInit -- 
I/AppConfig( 5621): Total System Memory = 906309632
I/GalleryUtils( 5621): Application Heap = 96 MB
D/UEI.SmartControl( 5575): Services init done
I/UEI.SmartControl( 5575): Device manager: loading config....
D/UEI.SmartControl( 5575): QS Service init finished
,D/UEI.SmartControl( 5575): QS Service version name: 0.1.73
D/UEI.SmartControl( 5575): QS Service version code: 1073
D/UEI.SmartControl( 5575): Config is loaded...
D/UEI.SmartControl( 5575): Service requested: Control
D/UEI.SmartControl( 5575): -----IControl: 11
D/UEI.SmartControl( 5575): Caller: com.lge.qremote
D/UEI.SmartControl( 5575): ------------ IControl registerCallback...
D/UEI.SmartControl( 5575): Internal service binding...
I/UEI.SmartControl( 5575): Registering callback...
I/AppConfig( 5621): App Tier : NOT_DEF
D/UEI.SmartControl( 5575): -----IControl: 19
,D/UEI.SmartControl( 5575): Caller: com.lge.qremote
I/UEI.SmartControl( 5575): Registering Services Ready callback...
D/SystemHelper( 5621): region [EU], country [EU], operator [OPEN], sub-operator []
D/UEI.SmartControl( 5575):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5575): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 5575): -----IControl: 8
D/UEI.SmartControl( 5575): Caller: com.lge.qremote
I/ActivityManager(  964): Killing 5259:com.lge.sync/1000 (adj 15): empty #11
I/ActivityManager(  964): Killing 4124:com.android.defcontainer/u0a4 (adj 15): empty #12
,W/libprocessgroup(  964): failed to open /acct/uid_1000/pid_5259/cgroup.procs: No such file or directory
,W/libprocessgroup(  964): failed to open /acct/uid_10004/pid_4124/cgroup.procs: No such file or directory
I/ActivityManager(  964): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5654 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  964): Killing 5186:com.lge.clock/u0a10 (adj 15): empty #11
W/libprocessgroup(  964): failed to open /acct/uid_10010/pid_5186/cgroup.procs: No such file or directory
,W/ResourcesManager( 5654): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 5654): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5654): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5654): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5654): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/CalendarProvider2( 5426): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 5426): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
I/ActivityManager(  964): Killing 3857:com.android.calendar/u0a13 (adj 15): empty #11
I/SystemConfig( 5654): BUILD Country: EU
I/SystemConfig( 5654): BUILD Operator: OPEN
,W/libprocessgroup(  964): failed to open /acct/uid_10013/pid_3857/cgroup.procs: No such file or directory
,I/ActivityManager(  964): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5679 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  964): Killing 5305:com.lge.bnr/1000 (adj 15): empty #11
W/libprocessgroup(  964): failed to open /acct/uid_1000/pid_5305/cgroup.procs: No such file or directory
,I/ActivityManager(  964): Killing 5352:com.google.android.music:main/u0a81 (adj 15): empty #11
I/SystemConfig( 5654): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 5654): existFile = false
I/SystemConfig( 5654): canReadFile = false
I/SystemConfig( 5654): systemFeature RCS result false
D/SystemConfig( 5654): refreshRcsSupport() :false
,I/LockScreenSettings( 5679): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,W/libprocessgroup(  964): failed to open /acct/uid_10081/pid_5352/cgroup.procs: No such file or directory
D/LockScreenSettings( 5679): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5679): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5679): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5679): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5679): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  964): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5696 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  964): Killing 5454:com.google.android.gm/u0a53 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10053/pid_5454/cgroup.procs: No such file or directory
W/ResourcesManager( 5696): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1949): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  964): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5721 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  964): Killing 5547:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10038/pid_5547/cgroup.procs: No such file or directory
I/CheckinService( 4381): Done disabling old GoogleServicesFramework version
I/UpdateIcingCorporaServi( 1949): UpdateCorporaTask done [took 191 ms] updated apps [took 190 ms] 
,D/Finsky  ( 5721): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,D/Finsky  ( 5721): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5721): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 5721): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 5721): com.android.vending: cancel(-1050172287) by com.android.vending
,V/DownloadManager( 3169): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3169): created cursor android.database.sqlite.SQLiteCursor@2f9ec703 on behalf of 5721
D/Finsky  ( 5721): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5721): [1] Libraries$2.run: Finished loading 1 libraries.
D/Ads     ( 5721): Skipping gmscore version check
,I/chromium( 5325): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
I/chromium( 5325): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
I/ActivityManager(  964): Killing 5426:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10014/pid_5426/cgroup.procs: No such file or directory
,D/Finsky  ( 5721): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,I/art     (  964): Explicit concurrent mark sweep GC freed 30318(1568KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.100ms total 138.608ms
,I/ActivityManager(  964): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5762 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 292us total 28.207ms
D/PackageBroadcastService( 4381): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4381): Null package name or gms related package.  Ignoreing.
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 307us total 26.266ms
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 263us total 23.659ms
,D/Finsky  ( 5721): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/Icing   ( 4381): Storage manager: low false usage 1.72MB avail 2.38GB capacity 4.06GB
,W/ResourcesManager( 5762): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5762): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5762): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/LGEmail ( 5762): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,D/LGEmail ( 5762): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,I/Icing   ( 4381): updateResources: need to parse f{com.google.android.gms}
,I/PackageChangeReceiver( 5762): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  964): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5810 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
I/ActivityManager(  964): Killing 5575:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5208): android.os.DeadObjectException
,W/System.err( 5208): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5208): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5208): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5208): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5208): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5208): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5208): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5208): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5208): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5208): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5208): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5208): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5208): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5208): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5208): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5208): android.os.DeadObjectException
W/System.err( 5208): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5208): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5208): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5208): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5208): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5208): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5208): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5208): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5208): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5208): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5208): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5208): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5208): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5208): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5208): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  964): failed to open /acct/uid_10089/pid_5575/cgroup.procs: No such file or directory
,W/ActivityManager(  964): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/ActivityManager(  964): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5831 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/AppUp4:PreloadHelper( 5602): removed from Exclude : com.test.thalitest : 1
,I/LockScreenSettings( 5679): New app installed broadcast received ..
,I/LockScreenSettings( 5679): Number of installed packages  1
D/UEI.SmartControl( 5831): Quickset Services start...
,I/UEI.SmartControl( 5831): Manufacture = LGE
D/UEI.SmartControl( 5831): File observer start...
,E/UEI.SmartControl( 5831): IR Port is disabled: false
D/UEI.SmartControl( 5831): Starting file observer...
D/UEI.SmartControl( 5831): Extracting JNI libs...
D/UEI.SmartControl( 5831): --- this system supports 32-bit or 64-bit only
I/ActivityManager(  964): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5852 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
I/Icing   ( 4381): Internal init done: storage state 0
,I/ActivityManager(  964): Killing 5208:com.lge.qremote/u0a106 (adj 15): empty #11
,D/UEI.SmartControl( 5831): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5831): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5831): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 5831): --- Selecting new region: 2
I/UEI.SmartControl( 5831): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 5831): Platform has CIR...
D/UEI.SmartControl( 5831): NO CIR support, need to check package...
I/UEI.SmartControl( 5831): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5831): QS Service created
W/libprocessgroup(  964): failed to open /acct/uid_10106/pid_5208/cgroup.procs: No such file or directory
,I/Icing   ( 4381): Post-init done
,I/Icing   ( 4381): updateResources: need to parse f{com.google.android.gms}
E/UEI.SmartControl( 5831): QS start get config
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/EulaProviderUpdateObserver( 5852): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5852): uri : package:com.test.thalitest
,D/UEI.SmartControl( 5831): Loading JNI Libs...
D/UEI.SmartControl( 5831):  configuring local db...
I/ActivityManager(  964): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5881 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  964): Killing 5028:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  964): failed to open /acct/uid_10006/pid_5028/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 5831):  ---- Has DB8: true
,D/UEI.SmartControl( 5831): QS start statue = true Error code = 0
D/UEI.SmartControl( 5831): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5831): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5831): IRRCDataComm has AudioManager!!!!.
,D/[BNRAppListMgrReceiver]( 5881): android.intent.action.PACKAGE_ADDED : com.test.thalitest
W/irrc_jni( 5831): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5831): IrrcClient ++ 
D/irrcClient( 5831): getIrrcService ++ 
D/irrcClient( 5831): getIrrcService -- 
D/irrcClient( 5831): IrrcClient -- 
W/irrc_jni( 5831): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5831): Services init done
,I/UEI.SmartControl( 5831): Device manager: loading config....
D/UEI.SmartControl( 5831): QS Service init finished
D/UEI.SmartControl( 5831): QS Service version name: 0.1.73
D/UEI.SmartControl( 5831): QS Service version code: 1073
D/UEI.SmartControl( 5831): Service requested: Control
D/UEI.SmartControl( 5831): Config is loaded...
W/MainApplication( 5881): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/UEI.SmartControl( 5831):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5831): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 5831): Request IControl service: devices are loaded...
,I/ActivityManager(  964): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5902 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
I/ActivityManager(  964): Killing 5696:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  964): failed to open /acct/uid_10086/pid_5696/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 5831): Service.onUnbind: IControl
D/UEI.SmartControl( 5831): Service.onDestroy
D/UEI.SmartControl( 5831): Shutdown IRRCPlayer... 
W/irrc_jni( 5831): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5831): ~IrrcClient ++ 
D/irrcClient( 5831): ~IrrcClient -- 
W/irrc_jni( 5831): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5831): Blaster closed
D/UEI.SmartControl( 5831): Blaster closed
D/UEI.SmartControl( 5831): Shut down QS...
D/UEI.SmartControl( 5831): Stopped file observer...
I/UEI.SmartControl( 5831): QS lib stop result = true
D/UEI.SmartControl( 5831): QS shutdown complete
D/UEI.SmartControl( 5831): QS Service created
E/UEI.SmartControl( 5831): QS start get config
,D/UEI.SmartControl( 5831):  configuring local db...
,D/UEI.SmartControl( 5831):  ---- Has DB8: true
,D/UEI.SmartControl( 5831): QS start statue = true Error code = 0
D/UEI.SmartControl( 5831): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5831): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5831): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5831): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5831): IrrcClient ++ 
D/irrcClient( 5831): getIrrcService ++ 
D/irrcClient( 5831): getIrrcService -- 
D/irrcClient( 5831): IrrcClient -- 
W/irrc_jni( 5831): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5831): Services init done
D/UEI.SmartControl( 5831): QS Service init finished
,D/UEI.SmartControl( 5831): QS Service version name: 0.1.73
D/UEI.SmartControl( 5831): QS Service version code: 1073
D/UEI.SmartControl( 5831): Service requested: Control
I/UEI.SmartControl( 5831): Device manager: loading config....
I/ActivityManager(  964): Killing 5721:com.android.vending/u0a36 (adj 15): empty #11
D/UEI.SmartControl( 5831): Config is loaded...
D/UEI.SmartControl( 5831):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5831): Notify AllClients services are ready: 0
,W/libprocessgroup(  964): failed to open /acct/uid_10036/pid_5721/cgroup.procs: No such file or directory
,E/ActivityThread( 5831): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@20df47fa that was originally bound here
E/ActivityThread( 5831): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@20df47fa that was originally bound here
E/ActivityThread( 5831): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5831): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5831): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5831): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5831): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5831): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 5831): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 5831): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 5831): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5831): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5831): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5831): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5831): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5831): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5831): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5831): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5831): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5831): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 5831): Internal service binding...
I/GAv4    ( 5902): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5902):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5902):   adb logcat -s GAv4
,W/GAv4    ( 5902): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/GAv4    ( 5902): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5902): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,W/AnalyticsTrackerProxyImpl( 5902): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,E/VoldCmdListener(  245): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  245): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  245): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5902): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
W/ResourcesManager( 5902): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5902): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/Icing   ( 4381): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/ActivityManager(  964): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5942 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  964): Killing 5762:com.lge.email/u0a21 (adj 15): empty #11
D/Icing   ( 4381): Loaded CLD2 Version V2.0 - 20141016
,W/libprocessgroup(  964): failed to open /acct/uid_10021/pid_5762/cgroup.procs: No such file or directory
I/Icing   ( 4381): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/art     ( 5902): CheckpointMarkThreadRoots callback created = 0xaaedd230
W/ResourcesManager( 5942): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{26e63cd1 type 2 when 86683 com.android.providers.calendar} when 86683
,I/art     ( 5902): CheckpointMarkThreadRoots callback created = 0xb0512a50
V/JNIHelp ( 5902): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 5902): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5902): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  964): Killing 5810:com.google.android.partnersetup/u0a9 (adj 15): empty #11
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/libprocessgroup(  964): failed to open /acct/uid_10009/pid_5810/cgroup.procs: No such file or directory
,I/ActivityManager(  964): Killing 5495:com.google.android.talk/u0a61 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10061/pid_5495/cgroup.procs: No such file or directory
,I/ActivityManager(  964): Killing 5602:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  964): failed to open /acct/uid_10011/pid_5602/cgroup.procs: No such file or directory
,I/ActivityManager(  964): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5981 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1949): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/UpdateIcingCorporaServi( 1949): UpdateCorporaTask done [took 132 ms] updated apps [took 132 ms] 
,D/Finsky  ( 5981): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/Finsky  ( 5981): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5981): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5981): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5981): com.android.vending: cancel(-1050172287) by com.android.vending
,I/NotificationManager( 5981): com.android.vending: cancel(1003285959) by com.android.vending
,D/PackageBroadcastService( 4381): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/Ads     ( 5981): Skipping gmscore version check
D/Finsky  ( 5981): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5981): [1] Libraries$2.run: Finished loading 1 libraries.
D/ChimeraCfgMgr( 4381): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4381): Loading module APK com.google.android.play.games
D/Finsky  ( 5981): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,V/DownloadManager( 3169): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3169): created cursor android.database.sqlite.SQLiteCursor@168fd680 on behalf of 5981
I/NotificationManager( 1949): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
,D/Finsky  ( 5981): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 5981): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 42463(2MB) AllocSpace objects, 24(384KB) LOS objects, 39% free, 13MB/22MB, paused 2.677ms total 134.008ms
,D/ChimeraCfgMgr( 4381): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 4381): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 4381): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/AsyncTaskServiceImpl( 4381): Submit a task: k
,D/ChimeraCfgMgr( 4381): Loading module com.google.android.gms.gass from APK com.google.android.gms
,D/ChimeraCfgMgr( 4381): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 4381): Processing package: com.test.thalitest
,D/GassUtils( 4381): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 4381): Found info for package com.test.thalitest in db.
,W/BaseAppContext( 4381): Using Auth Proxy for data requests.
W/BaseAppContext( 4381): Using Auth Proxy for data requests.
,I/PeopleDatabaseHelper( 4381): cleanUpNonGplusAccounts done.
I/ActivityManager(  964): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=6055 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/BaseAppContext( 4381): Using Auth Proxy for data requests.
,W/BaseAppContext( 4381): Using Auth Proxy for data requests.
,W/BaseAppContext( 4381): Using Auth Proxy for data requests.
W/BaseAppContext( 4381): Using Auth Proxy for data requests.
W/BaseAppContext( 4381): Using Auth Proxy for data requests.
W/ResourcesManager( 6055): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,D/BluetoothManagerService(  964): Message: 20
D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b51dded:true
,D/BluetoothAdapterService(551503866)( 2053): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a1dc820
D/BluetoothAdapterService(551503866)( 2053): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a1dc820
V/LGMDMManager( 6055): Create singleton instance
,I/AudioManager( 6055): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5831): -----IControl: 11
D/UEI.SmartControl( 5831): File observer start...
E/UEI.SmartControl( 5831): IR Port is disabled: false
D/UEI.SmartControl( 5831): Starting file observer...
D/UEI.SmartControl( 5831): Caller: com.lge.qremote
D/UEI.SmartControl( 5831): ------------ IControl registerCallback...
I/UEI.SmartControl( 5831): Registering callback...
D/UEI.SmartControl( 5831): -----IControl: 19
D/UEI.SmartControl( 5831): Caller: com.lge.qremote
I/UEI.SmartControl( 5831): Registering Services Ready callback...
I/UEI.SmartControl( 5831): Notify client services are ready...
I/AudioManager( 6055): getMode name:com.lge.qremote
D/UEI.SmartControl( 5831): -----IControl: 8
,D/UEI.SmartControl( 5831): Caller: com.lge.qremote
,I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6075 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  964): Explicit concurrent mark sweep GC freed 24334(1133KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 1.887ms total 150.656ms
,I/ActivityManager(  964): Killing 5621:com.android.gallery3d/u0a23 (adj 15): empty #11
D/PhoneMonitor( 6075): Register our PhoneStateListener
,D/ChimeraCfgMgr( 4381): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4381): Module APK com.google.android.play.games already loaded
,W/libprocessgroup(  964): failed to open /acct/uid_10023/pid_5621/cgroup.procs: No such file or directory
E/ActivityThread( 4381): Failed to find provider info for com.android.contacts.metadata
D/SyncManager(  964): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 79297, reason: UserStart, SyncResult: databaseError: true stats []
,D/SyncManager(  964): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 153243, reason: UserStart
I/NotificationManager(  964): android: cancelAsUser(716319171) by android
V/SetupWizard( 6075): Connected to Gservices successfully
,I/ActivityManager(  964): Killing 5654:com.android.contacts/u0a18 (adj 15): empty #11
D/PhoneMonitor( 6075): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6075): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6075): [parse] Load xml
,V/TelephonyAutoProfiling( 6075): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6075): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6075): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
W/libprocessgroup(  964): failed to open /acct/uid_10018/pid_5654/cgroup.procs: No such file or directory
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  964): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6102 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Icing   ( 4381): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4381): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,W/ActivityManager(  964): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6102): getAccountsCursor
,W/GAV2    ( 6102): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager(  964): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 6102): Error finding the version of the Email provider.....
E/Gmail   ( 6102): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6102): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6102): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6102): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6102): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6102): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6102): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6102): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6102): We do not support migrating this version of the Email provider.
,I/ActivityManager(  964): Killing 5679:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/Gmail   ( 6102): getAccountsCursor
W/libprocessgroup(  964): failed to open /acct/uid_10069/pid_5679/cgroup.procs: No such file or directory
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  964): Killing 5852:com.lge.eula/1000 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_1000/pid_5852/cgroup.procs: No such file or directory
,W/ActivityManager(  964): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
I/Gmail   ( 6102): Observing account changes for notifications
,W/ActivityManager(  964): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/AudioManager( 6055): getMode name:com.lge.qremote
I/ActivityManager(  964): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6151 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 289us total 21.761ms
,I/Gmail   ( 6102): notifyAccountChanged
I/Gmail   ( 6102): getAccountsCursor
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 279us total 21.736ms
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 21.715ms
I/Gmail   ( 6102): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6102): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6102): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6102): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/ResourcesManager( 6151): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/[SystemUI]QPairHandler( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
,I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
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
I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/art     ( 4038): Explicit concurrent mark sweep GC freed 3322(131KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 948us total 44.702ms
D/administrator(  964): Handling package changes for user 0
,D/CalendarApplication( 6151): CalendarApplication.onCreate()
,D/PreferenceKeysParser( 6151): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6151): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@1c0ddf33, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@5bc2f0, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@12175069, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@28a36aee, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@3a3d3b8f, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@13d21e1c, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@1b4b8a25, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@20df47fa, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@2c5c01ab, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@20f10008, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@2cfa3a1, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@25c9e9c6, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@31570d87, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@59a14b4, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@c21d8dd, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@126adc52, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@200cfb23, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@3a1dc820, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@3a6825d9, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@38b66b9e, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@14aa267f, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@2967464c, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@32c4695, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@399a3aa, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@17c4ab9b, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@1fe87b38, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@30d7b711, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2dc65076, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@1b386677, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@3d4612e4, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@30efb34d, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@193efe02, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@28c2f313, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@14c37950, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@a113749, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@13a2f84e, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@1e5fad6f, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@286eda7c, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@35acff05, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@133a4b5a, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@1463b18b, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@2b0d22
D/GeneralP,referenceUtils( 6151): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6151): [init]
I/Config  ( 6151): LGCalendar ver.4.40.17
I/Config  ( 6151): start check model
I/Config  ( 6151): start check native_ca
I/Config  ( 6151): Config Operator=OPEN, Country=EU
D/Config  ( 6151): [setDefaultValuesToPref]
D/Config  ( 6151): [parseProfiles]
D/ProfilesParser( 6151): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6151): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6151): [updateProfiletoCountryInfo]
D/GeneralPreference( 6151): [checkAndMigrateOldPreference]
I/[LGHome]Launcher( 1873): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
D/AlertReceiver( 6151): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,I/InitNotificationRingtoneService( 6151): Start InitializeAlertRingtoneService.onHandleIntent
,I/Gmail   ( 6102): getAccountsCursor
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AlertUtils( 6151): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/NotificationService(  964): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  964): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  964): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  964): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  964): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  964): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3a35413e
,I/AlertUtils( 6151): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/AlertUtils( 6151): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6151): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
I/AlertUtils( 6151): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,I/AlertUtils( 6151): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
I/AlertUtils( 6151): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6151): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6151): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6151): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6151): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6151): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 6151): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6151): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6151): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 6151): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6151): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6151): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6151): set default noti to content://media/internal/audio/media/38
,I/InitNotificationRingtoneService( 6151): End InitializeAlertRingtoneService.onHandleIntent
W/ResourcesManager(  964): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/HolidayIntentService( 6151): onHandleIntent
,D/HolidayDataLoader( 6151): readJsonAsset : holiday.json
D/AlertService( 6151): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6151): [updateWidgets] 
D/MonthWidgetProvider( 6151): [onReceive]
D/CalendarWidgetProvider( 6151): [onReceive]
D/CalendarWidgetProvider( 6151): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6151): [onCreate] mContext.getPackageName() = com.android.calendar
D/WeekWidgetProvider( 6151): [onReceive]
D/CalendarWidgetProvider( 6151): [onReceive]
D/CalendarWidgetProvider( 6151): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6151): [onCreate] mContext.getPackageName() = com.android.calendar
,W/ResourceType(  964): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  964): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6185 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/HolidayIntentService( 6151): onHandleIntent:holiday data empty
,I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1730): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
,E/UEI.SmartControl( 5831): file observer is disposed!
W/ResourcesManager( 6185): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/LocationProviderProxy(  964): applying state to connected service
D/CalendarProvider2( 6185): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@24607a6d
,I/art     (  964): Explicit concurrent mark sweep GC freed 21667(1079KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.522ms total 139.831ms
,D/CalendarProvider2( 6185): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6185): Created com.android.providers.calendar.CalendarAlarmManager@28a36aee(com.android.providers.calendar.CalendarProvider2@24607a6d)
D/CalendarProviderBroadcastReceiver( 6185): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6185): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6185): CalendarProviderIntentService.onCreate()
D/CalendarProvider2( 6185): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
,D/CalendarProvider2( 6185): [getOrCreateCalendarAlarmManager]
I/AudioManager( 6055): getMode name:com.lge.qremote
I/AudioManager( 6055): getMode name:com.lge.qremote
I/AudioManager( 6055): getMode name:com.lge.qremote
,I/AudioManager( 6055): getMode name:com.lge.qremote
,I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6215 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/CalendarProvider2( 6185): [IntentService] Release Lock
D/CalendarProvider2( 6185): CalendarProviderIntentService.onDestroy()
,I/ActivityManager(  964): Killing 5881:com.lge.bnr/1000 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_1000/pid_5881/cgroup.procs: No such file or directory
W/ResourcesManager( 6215): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 6215): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6215): MmsConfig.loadMmsSettings
I/Babel_SMS( 6215): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6215): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6215): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6215): MmsConfig.loadFromResources
E/Babel_SMS( 6215): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6215): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 6215): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6215): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6215): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6215): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6215): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6215): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6215): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6215): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6215): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6215): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6215): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6215): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6215): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6215): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6215): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6215): found sensor: Motion Accel, handle=46
,W/Settings( 6215): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6215): startup - clean
,I/Babel   ( 6215): deleted: false for 0
,I/art     ( 6215): CheckpointMarkThreadRoots callback created = 0xb042d8c0
,I/art     ( 6215): CheckpointMarkThreadRoots callback created = 0xb042d8a0
,W/AudioCapabilities( 6215): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6215): Unsupported mime audio/adpcm
W/AudioCapabilities( 6215): Unsupported mime audio/g726
W/AudioCapabilities( 6215): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6215): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6215): Unsupported mime video/mjpg
W/VideoCapabilities( 6215): Unsupported mime video/theora
I/ActivityManager(  964): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6255 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,D/UEI.SmartControl( 5831): Internal timer expired: 2
,W/AudioCapabilities( 6215): Unsupported mime audio/evrc
W/AudioCapabilities( 6215): Unsupported mime audio/qcelp
W/VideoCapabilities( 6215): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6215): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6215): Unsupported mime audio/qcelp
W/AudioCapabilities( 6215): Unsupported mime audio/evrc
,W/VideoCapabilities( 6215): Unsupported mime video/mp4v-esdp
I/VideoCapabilities( 6215): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6215): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6215): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6215): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6215): Unrecognized profile 2130706433 for video/avc
I/AppUp4:AppBoxCP( 6255): onCreate
,W/AppUp4:DB( 6255):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6255):  setFingerPrint start
I/AppUp4:DB( 6255):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6255):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6255):  SDK version = 0
I/AppUp4:DB( 6255):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6255): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6255): onReceive
I/AppUp4:CustModeStarterReceiver( 6255): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6255): Context : android.app.ReceiverRestrictedContext@5bc2f0
D/AppUp4:CustFacade( 6255): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6255): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6255): begin check event
I/AppUp4:CustModeStarterReceiver( 6255): Event For Nothing, skip.
I/ActivityManager(  964): Killing 5902:com.google.android.apps.docs/u0a58 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10058/pid_5902/cgroup.procs: No such file or directory
,I/ActivityManager(  964): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6278 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/vclib   ( 6215): onServiceConnected
W/Babel   ( 6215): Attempted to change video mute state without an active call.
I/NotificationManager( 6215): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6215): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6215): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 6215): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ResourcesManager( 6278): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6278): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6278): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
W/System  ( 6215): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6215): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6215): com.google.android.talk: cancel(10436) by com.google.android.talk
I/AppConfig( 6278): Total System Memory = 906309632
,I/GalleryUtils( 6278): Application Heap = 96 MB
I/AppConfig( 6278): App Tier : NOT_DEF
D/SystemHelper( 6278): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  964): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6303 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  964): Killing 5942:com.google.android.apps.plus/u0a86 (adj 15): empty #11
W/libprocessgroup(  964): failed to open /acct/uid_10086/pid_5942/cgroup.procs: No such file or directory
,W/ResourcesManager( 6303): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6303): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6303): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6303): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6303): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6303): BUILD Country: EU
I/SystemConfig( 6303): BUILD Operator: OPEN
,I/ActivityManager(  964): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6325 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  964): Killing 5981:com.android.vending/u0a36 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10036/pid_5981/cgroup.procs: No such file or directory
,I/SystemConfig( 6303): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6303): existFile = false
I/SystemConfig( 6303): canReadFile = false
,I/SystemConfig( 6303): systemFeature RCS result false
D/SystemConfig( 6303): refreshRcsSupport() :false
W/SQLiteConnectionPool( 4381): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
I/LockScreenSettings( 6325): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6325): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6325): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,D/LockScreenSettings( 6325): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6325): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6325): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
I/ActivityManager(  964): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6348 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  964): Killing 6075:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  964): failed to open /acct/uid_10038/pid_6075/cgroup.procs: No such file or directory
,W/ResourcesManager( 6348): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/UpdateIcingCorporaServi( 1949): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager(  964): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=6376 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/UpdateIcingCorporaServi( 1949): UpdateCorporaTask done [took 52 ms] updated apps [took 52 ms] 
I/ActivityManager(  964): Killing 4381:com.google.android.gms/u0a6 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10006/pid_4381/cgroup.procs: No such file or directory
V/AlarmManager(  964): RTC_WAKEUP set : Alarm{15eecd6 type 0 when 1456925784662 com.android.vending} when 1456925784662
,D/Finsky  ( 6376): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 6376): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 6376): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
W/Settings( 6376): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/NotificationManager( 6376): com.android.vending: cancel(-1050172287) by com.android.vending
V/DownloadManager( 3169): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 3169): created cursor android.database.sqlite.SQLiteCursor@159984b9 on behalf of 6376
D/Finsky  ( 6376): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/Finsky  ( 6376): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 6376): [1] Libraries$2.run: Finished loading 1 libraries.
D/Finsky  ( 6376): [1] GmsCoreHelper.cleanupNlp: result=false type=4
D/Ads     ( 6376): Skipping gmscore version check
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  ( 6376): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager(  964): Start proc com.google.android.gms for service com.google.android.gms/.ads.identifier.service.AdvertisingIdService: pid=6433 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/AudioManager( 6055): getMode name:com.lge.qremote
I/AudioManager( 6055): getMode name:com.lge.qremote
,I/NotificationManager(  964): android: cancelAsUser(2) by android
,W/ResourcesManager( 6433): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6433): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6433): VM with version 2.1.0 has multidex support
I/MultiDex( 6433): install
I/MultiDex( 6433): VM has multidex support, MultiDex support library is disabled.
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
V/JNIHelp ( 6433): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6433): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 6433): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@13e1cc86: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6433): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6433): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6433): com.google.android.gms: cancel(39789) by com.google.android.gms
D/PackageBroadcastService( 6433): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6433): Null package name or gms related package.  Ignoreing.
,D/WearableService( 1730): callingUid 10006, callindPid: 1730
,E/MDM     ( 1730): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/NativeLibraryUtils( 6433): Install completed successfully. count=14 extracted=0
D/libc-netbsd( 6376): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6376): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationInitializer( 6433): Restart initialization of location
D/libc-netbsd( 6376): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6376): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  272): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 6376): propertyValue:false
D/libc-netbsd( 6376): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6376): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
I/art     ( 6433): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6433): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/Icing   ( 6433): Storage manager: low false usage 1.72MB avail 2.38GB capacity 4.06GB
I/art     ( 6433): CheckpointMarkThreadRoots callback created = 0xb042d320
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/art     ( 6433): CheckpointMarkThreadRoots callback created = 0xaaf51db0
,I/art     ( 6433): Background partial concurrent mark sweep GC freed 5292(614KB) AllocSpace objects, 12(192KB) LOS objects, 39% free, 10MB/18MB, paused 12.938ms total 135.861ms
,W/GCoreFlp( 1730): No location to return for getLastLocation()
,W/FusedLocationProvider( 1730): location=null
I/art     (  964): Explicit concurrent mark sweep GC freed 21534(1011KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.052ms total 154.098ms
,D/libc-netbsd( 6376): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6376): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
W/IcingInternalCorpora( 6433): getNumBytesRead when not calculated.
,I/GAV2    ( 6102): Thread[GAThread,5,main]: No campaign data found.
,I/Icing   ( 6433): updateResources: need to parse f{com.google.android.gms}
I/GAv4-SVC( 6433): Google Analytics 8.4.89 is starting up.
,I/Icing   ( 6433): Internal init done: storage state 0
,I/NotificationManager( 6433): com.google.android.gms: cancel(10436) by com.google.android.gms
I/Icing   ( 6433): Post-init done
,I/Icing   ( 6433): updateResources: need to parse f{com.google.android.gms}
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  964): android: cancelAsUser(2) by android
,I/qtaguid ( 6376): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6376): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6376): untagSocket(41) failed with errno -22
D/Finsky  ( 6376): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager(  964): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6511 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  964): android: cancelAsUser(2) by android
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 94640264500; DSPS: 3192923; Offset : -2813258768
,W/ResourcesManager( 6511): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6511): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6511): VM with version 2.1.0 has multidex support
I/MultiDex( 6511): install
I/MultiDex( 6511): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6511): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6511): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6511): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@168fd680: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6511): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6511): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6511): com.google.android.gms: cancel(39789) by com.google.android.gms
D/LocationInitializer( 6433): Restart initialization of location
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/ChimeraCfgMgr( 6511): Reading stored module config
E/MDM     ( 1730): [150] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
D/ChimeraCfgMgr( 6511): Loading module com.google.android.gms.car from APK com.google.android.gms
,W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
D/NativeLibraryUtils( 6511): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6511): Connecting to CarCallService...
I/qtaguid ( 6376): Failed write_ctrl(u 41) res=-1 errno=22
,I/qtaguid ( 6376): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6376): untagSocket(41) failed with errno -22
I/art     ( 6511): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6511): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
D/AlertService( 6151): Beginning updateAlertNotification
D/AlertService( 6151): No fired or scheduled alerts
I/NotificationManager( 6151): com.android.calendar: cancel(0) by com.android.calendar
,I/NotificationManager( 6151): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6151): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6151): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6151): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6151): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6151): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6151): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6151): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6151): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6151): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6151): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6151): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6151): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 6151): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6151): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6151): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6151): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6151): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6151): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6151): com.android.calendar: cancel(20) by com.android.calendar
D/AlertService( 6151): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
,D/AlarmScheduler( 6151): No events found starting within 1 week.
D/CAR.SERVICE( 6511): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service( 6511): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter( 6511): Creating a new PhoneAdapter instance
,W/ActivityManager(  964): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6511): setListener: com.google.android.gms.car.dn@1ae08f4f
W/ActivityManager(  964): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6511): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6511): Starting CarCallService with initial phone null
I/ActivityManager(  964): Killing 6151:com.android.calendar/u0a13 (adj 15): empty #11
D/CAR.SERVICE( 6511): Package validated; name: com.android.vending
,W/libprocessgroup(  964): failed to open /acct/uid_10013/pid_6151/cgroup.procs: No such file or directory
I/NotificationManager( 6511): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6376): com.android.vending: cancel(10436) by com.android.vending
V/Finsky  ( 6376): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,I/art     ( 6376): CheckpointMarkThreadRoots callback created = 0xb058f4a0
,I/art     ( 6376): CheckpointMarkThreadRoots callback created = 0xb058f460
,I/Icing   ( 6433): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/Icing   ( 6433): Loaded CLD2 Version V2.0 - 20141016
,I/Icing   ( 6433): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  964): android: cancelAsUser(2) by android
,I/qtaguid ( 6376): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 6376): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 6376): untagSocket(41) failed with errno -22
,W/ResourcesManager( 6376): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 6376): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 6376): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 6376): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  964): RTC_WAKEUP set : Alarm{1fed5859 type 0 when 1456925788419 com.android.vending} when 1456925788419
I/ActivityManager(  964): Killing 6185:com.android.providers.calendar/u0a14 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10014/pid_6185/cgroup.procs: No such file or directory
,D/DeviceConnectionService( 1730): client connected with version: 8296000
D/Finsky  ( 6376): [784] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 6376): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 6376): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager(  964): android: cancelAsUser(2) by android
,D/libc-netbsd( 6376): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6376): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 6376): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6376): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  272): App 10036 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 6376): propertyValue:false
,I/ActivityManager(  964): Killing 6215:com.google.android.talk/u0a61 (adj 15): empty #11
,I/ActivityManager(  964): Killing 6255:com.lge.appbox.client/u0a11 (adj 15): empty #12
,W/libprocessgroup(  964): failed to open /acct/uid_10061/pid_6215/cgroup.procs: No such file or directory
,W/libprocessgroup(  964): failed to open /acct/uid_10011/pid_6255/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/ActivityManager(  964): Killing 6278:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10023/pid_6278/cgroup.procs: No such file or directory
,D/CAR.SERVICE( 6511): mConnectedToCar = false, abort
,E/ActivityThread( 6511): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@9fa6c57 that was originally bound here
E/ActivityThread( 6511): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@9fa6c57 that was originally bound here
E/ActivityThread( 6511): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6511): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6511): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6511): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6511): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6511): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6511): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6511): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6511): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6511): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6511): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6511): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6511): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6511): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6511): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6511): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6511): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6511): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6511): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6511): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6511): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6511): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6511): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6511): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3cb4b5ae that was originally bound here
E/ActivityThread( 6511): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@3cb4b5ae that was originally bound here
E/ActivityThread( 6511): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6511): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6511): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6511): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6511): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6511): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6511): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6511): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6511): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6511): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6511): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6511): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6511): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6511): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6511): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6511): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6511): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6511): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6511): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6511): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6511): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6511): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
W/ActivityManager(  964): Unbind failed: could not find connection for android.os.BinderProxy@41ad764
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/rmt_storage(  268): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
,I/rmt_storage(  268): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  268): wakelock acquired: 1, error no: 42
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  268): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
I/rmt_storage(  268): 
I/rmt_storage(  268): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/AlarmManager(  964): RTC_WAKEUP set : Alarm{28665dcd type 0 when 1456925801413 com.google.android.gms} when 1456925801413
,V/AlarmManager(  964): RTC_WAKEUP set : Alarm{2fffe193 type 0 when 1456925802641 com.android.vending} when 1456925802641
I/CheckinService( 6433): Checkin interval check for package: unspecified last checkin: 1456925771532 min interval config: 0 actual interval: 31181
,I/CheckinService( 6433): Disabling old GoogleServicesFramework version
,W/ContextImpl( 3670): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/CheckinService( 6433): Checking schedule, now: 1456925802874 next: 1456925801413
I/CheckinService( 6433): active receiver: enabled
,I/CheckinService( 6433): Preparing to send checkin request
I/EventLogService( 6433): Accumulating logs since 1456925761707
,I/CheckinRequestBuilder( 6433): Checkin reason type: 8 attempt count: 1
,D/Finsky  ( 6376): [775] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
E/ActivityThread( 6433): Failed to find provider info for com.google.android.wearable.settings
D/Finsky  ( 6376): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  964): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6611 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/art     (  310): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 420us total 34.761ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 403us total 31.534ms
,I/art     (  310): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 272us total 29.962ms
,W/ResourcesManager( 6611): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6611): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
I/MultiDex( 6611): VM with version 2.1.0 has multidex support
I/MultiDex( 6611): install
I/MultiDex( 6611): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6611): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6611): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6611): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@168fd680: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6611): Installed default security provider GmsCore_OpenSSL
,I/NotificationManager( 6611): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6611): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1730): callingUid 10006, callindPid: 1730
,E/MDM     ( 1730): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1730): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/LocationInitializer( 6433): Restart initialization of location
V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1730): com.google.android.gms: cancel(0) by com.google.android.gms
,W/GCoreFlp( 1730): No location to return for getLastLocation()
W/FusedLocationProvider( 1730): location=null
,I/art     ( 6611): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6611): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/NativeLibraryUtils( 6611): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  279): Instantiating CDM.
,I/WVCdm   (  279): CdmEngine::OpenSession
I/WVCdm   (  279): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  279): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  279): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  279): L1 library not specified. Falling Back to L3
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
,D/WVCdm   (  279): PrepareKeyRequest: nonce=4108562867
I/art     ( 6611): CheckpointMarkThreadRoots callback created = 0xaaf095b0
,I/art     ( 6611): CheckpointMarkThreadRoots callback created = 0xaaf095a0
,I/WVCdm   (  279): CdmEngine::OpenSession
,I/MusicWidget( 2582): mDelayedStopHandler : unbind
,I/MusicBrowser( 2652): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2652): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2652): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2652): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2652): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2652): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2652): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
I/MusicBrowser( 2652): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  964):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@2967464ccom.lge.music.MediaPlaybackService$6@32c4695
,D/MusicBrowser( 2652): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2652): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2652): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2652): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2652): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@2c5c01ab
I/MusicBrowser( 2652): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2652): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2652): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
,I/MusicBrowser( 2652): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2652): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2652): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2652): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2652): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2652): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2652): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2652): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2652): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2652): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2652): reset
V/MediaPlayer[Native]( 2652): setListener
,V/MediaPlayer[Native]( 2652): disconnect
V/MediaPlayer[Native]( 2652): destructor
V/AudioFlinger(  279): releasing 19 from 2652 for -1
V/AudioFlinger(  279):  decremented refcount to 0
V/AudioFlinger(  279): purging stale effects
V/MediaPlayer[Native]( 2652): disconnect
D/MusicBrowser( 2652): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2652): [SmartShareManagerClient] smartshare client supported version code: 305010
I/SmartShareClient( 2652): [SmartShareManagerClient] smartshare client enabled
,I/MusicBrowser( 2652): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2652): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2652): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2652): [SmartShareManagerClient] unregisterListener: 60400554
W/SmartShareClient( 2652): [SmartShareManagerClient] unregisterListener invalid listener: 60400554
I/SmartShareClient( 2652): [SmartShareManagerClient] terminate service: 2652/MediaPlaybackService/303517801
E/HomeCloudIF( 2652): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2652): [SmartShareManagerClient] unbindService context:android.app.Application@17c4ab9b
V/CloudHub( 2652): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2652): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2652): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2652): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2652): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/CloudHub( 2652): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29992
I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/WVCdm   (  279): CdmEngine::CloseSession
,I/WVCdm   (  279): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  279): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  279): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  279): CdmEngine::GenerateKeyRequest
D/WVCdm   (  279): PrepareKeyRequest: nonce=320981664
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 114641801784; DSPS: 3848333; Offset : -2813247650
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/WVCdm   (  279): CdmEngine::CloseSession
,I/WVCdm   (  279): L3 Terminate.
I/dex2oat ( 6661): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=38 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6661): dex2oat took 70.607ms (threads: 4)
,I/Adreno-EGL( 6611): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6611): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6611): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6611): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6611): Remote Branch: 
I/Adreno-EGL( 6611): Local Patches: 
I/Adreno-EGL( 6611): Reconstruct Branch: 
I/Adreno-EGL( 6611): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6611): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6611): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6611): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6611): Remote Branch: 
I/Adreno-EGL( 6611): Local Patches: 
I/Adreno-EGL( 6611): Reconstruct Branch: 
,I/Adreno-EGL( 6611): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6611): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6611): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6611): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6611): Remote Branch: 
I/Adreno-EGL( 6611): Local Patches: 
I/Adreno-EGL( 6611): Reconstruct Branch: 
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/CheckinRequestBuilder( 6433): Classify the device as Phone.
,D/libc-netbsd( 6433): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6433): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6433): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6433): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  272): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 6433): propertyValue:false
D/libc-netbsd( 6433): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6433): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6433): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6433): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 6433): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 6433): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/CheckinTask( 6433): Sending checkin request (9771 bytes)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/CheckinRequestBuilder( 6433): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 6433): Failed to find provider info for com.google.android.wearable.settings
,I/art     (  964): Explicit concurrent mark sweep GC freed 24318(1151KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.192ms total 148.079ms
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/CheckinRequestBuilder( 6433): Classify the device as Phone.
,I/CheckinTask( 6433): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 6433): Checking schedule, now: 1456925810012 next: 1457453059007
I/CheckinService( 6433): active receiver: disabled
,D/CheckinService( 6433): Recording last checkin time for package unspecified as 1456925810041
,I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6681 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  964): Killing 6325:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
,I/ActivityManager(  964): Killing 6303:com.android.contacts/u0a18 (adj 15): empty #12
,W/libprocessgroup(  964): failed to open /acct/uid_10069/pid_6325/cgroup.procs: No such file or directory
,W/libprocessgroup(  964): failed to open /acct/uid_10018/pid_6303/cgroup.procs: No such file or directory
V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{1749962e type 2 when 118207 android} when 118207
,D/PhoneMonitor( 6681): Register our PhoneStateListener
,V/SetupWizard( 6681): Connected to Gservices successfully
,D/PhoneMonitor( 6681): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6681): [loadFeatureFromXml] *** start feature loading from xml
D/TelephonyAutoProfiling( 6681): [parse] Load xml
,V/TelephonyAutoProfiling( 6681): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6681): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/PhoneMonitor( 6681): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,I/ActivityManager(  964): Killing 6348:com.google.android.apps.plus/u0a86 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10086/pid_6348/cgroup.procs: No such file or directory
,D/GCM     ( 1730): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/ThermalEngine(  292): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/QCNEJ   ( 1836): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[SystemUI]QPairHandler( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
,I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1873): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6709 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/administrator(  964): Handling package changes for user 0
,I/[LGHome]Launcher( 1873): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/[SystemUI]QSlideListController( 1371): onReceive = android.intent.action.PACKAGE_CHANGED
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1371): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1371): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,W/ResourcesManager( 6709): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/NotificationService(  964): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  964): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  964): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  964): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  964): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  964): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@135b5fab
,W/ResourcesManager(  964): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/art     ( 1783): Background sticky concurrent mark sweep GC freed 90058(5MB) AllocSpace objects, 0(0B) LOS objects, 34% free, 9MB/14MB, paused 9.392ms total 54.910ms
W/ResourceType(  964): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/[LGHome]EVENT( 1873): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/GCoreNlp( 1730): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  964): applying state to connected service
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Babel_SMS( 6709): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6709): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6709): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
,I/Babel_SMS( 6709): MmsConfig.loadFromDatabase
,E/Babel_SMS( 6709): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6709): MmsConfig.loadFromResources
E/Babel_SMS( 6709): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6709): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
,D/LCardEmulationManager( 1783): getDefaultRoute
,D/SensorManager( 6709): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6709): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6709): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6709): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6709): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6709): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6709): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6709): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6709): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6709): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6709): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6709): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6709): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6709): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6709): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6709): found sensor: Motion Accel, handle=46
W/Settings( 6709): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6709): startup - clean
I/art     ( 6709): CheckpointMarkThreadRoots callback created = 0xb042d930
,I/art     ( 6709): CheckpointMarkThreadRoots callback created = 0xb042d910
,I/Babel   ( 6709): deleted: false for 0
,W/AudioCapabilities( 6709): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6709): Unsupported mime audio/adpcm
W/AudioCapabilities( 6709): Unsupported mime audio/g726
W/AudioCapabilities( 6709): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6709): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6709): Unsupported mime video/mjpg
W/VideoCapabilities( 6709): Unsupported mime video/theora
I/ActivityManager(  964): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6752 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/AudioCapabilities( 6709): Unsupported mime audio/evrc
W/AudioCapabilities( 6709): Unsupported mime audio/qcelp
W/VideoCapabilities( 6709): Unrecognized profile 2130706433 for video/avc
,W/AudioCapabilities( 6709): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6709): Unsupported mime audio/qcelp
W/AudioCapabilities( 6709): Unsupported mime audio/evrc
,I/AppUp4:AppBoxCP( 6752): onCreate
W/AppUp4:DB( 6752):  [AppBoxDatabaseHelper] construct
,W/VideoCapabilities( 6709): Unsupported mime video/mp4v-esdp
I/AppUp4:DB( 6752):  setFingerPrint start
I/AppUp4:DB( 6752):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/AppUp4:DB( 6752):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6752):  SDK version = 0
I/AppUp4:DB( 6752):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6752): AppBoxApplication onCreate()
,I/VideoCapabilities( 6709): Unsupported profile 4 for video/mp4v-es
I/AppUp4:CustModeStarterReceiver( 6752): onReceive
I/AppUp4:CustModeStarterReceiver( 6752): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6752): Context : android.app.ReceiverRestrictedContext@5bc2f0
D/AppUp4:CustFacade( 6752): isCustomizationCompleted : false
,W/VideoCapabilities( 6709): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6709): Unrecognized profile 2130706433 for video/avc
D/AppUp4:CustFacade( 6752): isSimDevice : true
W/VideoCapabilities( 6709): Unrecognized profile 2130706433 for video/avc
D/AppUp4:CustModeStarterReceiver( 6752): begin check event
I/AppUp4:CustModeStarterReceiver( 6752): Event For Nothing, skip.
I/ActivityManager(  964): Killing 6102:com.google.android.gm/u0a53 (adj 15): empty #11
,W/VideoCapabilities( 6709): Unrecognized profile 2130706433 for video/avc
W/libprocessgroup(  964): failed to open /acct/uid_10053/pid_6102/cgroup.procs: No such file or directory
,I/ActivityManager(  964): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6774 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/vclib   ( 6709): onServiceConnected
,W/Babel   ( 6709): Attempted to change video mute state without an active call.
I/NotificationManager( 6709): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6709): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6709): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6774): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6774): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 6774): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
V/JNIHelp ( 6709): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 6709): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6709): Installed default security provider GmsCore_OpenSSL
,I/AppConfig( 6774): Total System Memory = 906309632
I/GalleryUtils( 6774): Application Heap = 96 MB
I/AppConfig( 6774): App Tier : NOT_DEF
D/SystemHelper( 6774): region [EU], country [EU], operator [OPEN], sub-operator []
,I/NotificationManager( 6709): com.google.android.talk: cancel(10436) by com.google.android.talk
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ActivityManager(  964): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6796 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
I/ActivityManager(  964): Killing 5831:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 6055): android.os.DeadObjectException
,W/System.err( 6055): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6055): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6055): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 6055): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 6055): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6055): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6055): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6055): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6055): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6055): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6055): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6055): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6055): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6055): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6055): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 6055): android.os.DeadObjectException
W/System.err( 6055): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 6055): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 6055): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 6055): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 6055): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 6055): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 6055): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 6055): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 6055): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6055): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6055): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6055): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6055): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6055): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6055): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  964): failed to open /acct/uid_10089/pid_5831/cgroup.procs: No such file or directory
W/ActivityManager(  964): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  964): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6816 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6796): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6796): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/UEI.SmartControl( 6816): Quickset Services start...
I/UEI.SmartControl( 6816): Manufacture = LGE
,D/UEI.SmartControl( 6816): File observer start...
E/UEI.SmartControl( 6816): IR Port is disabled: false
D/UEI.SmartControl( 6816): Starting file observer...
D/UEI.SmartControl( 6816): Extracting JNI libs...
D/UEI.SmartControl( 6816): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6816): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,I/SystemConfig( 6796): BUILD Country: EU
I/SystemConfig( 6796): BUILD Operator: OPEN
D/UEI.SmartControl( 6816): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6816): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6816): --- Selecting new region: 2
,I/UEI.SmartControl( 6816): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 6816): Platform has CIR...
D/UEI.SmartControl( 6816): NO CIR support, need to check package...
,I/UEI.SmartControl( 6816): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6816): QS Service created
E/UEI.SmartControl( 6816): QS start get config
,I/ActivityManager(  964): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6836 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  964): Killing 6055:com.lge.qremote/u0a106 (adj 15): empty #11
D/UEI.SmartControl( 6816): Loading JNI Libs...
D/UEI.SmartControl( 6816):  configuring local db...
,W/libprocessgroup(  964): failed to open /acct/uid_10106/pid_6055/cgroup.procs: No such file or directory
,I/SystemConfig( 6796): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6796): existFile = false
I/SystemConfig( 6796): canReadFile = false
I/SystemConfig( 6796): systemFeature RCS result false
D/SystemConfig( 6796): refreshRcsSupport() :false
,I/LockScreenSettings( 6836): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,D/LockScreenSettings( 6836): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6836): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6836): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6836): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,D/LockScreenSettings( 6836): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  964): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6853 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  964): Killing 6511:com.google.android.gms:car/u0a6 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10006/pid_6511/cgroup.procs: No such file or directory
,W/ResourcesManager( 6853): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6816):  ---- Has DB8: true
D/UEI.SmartControl( 6816): QS start statue = true Error code = 0
D/UEI.SmartControl( 6816): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6816): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6816): IRRCDataComm has AudioManager!!!!.
,W/irrc_jni( 6816): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6816): IrrcClient ++ 
D/irrcClient( 6816): getIrrcService ++ 
,D/irrcClient( 6816): getIrrcService -- 
D/irrcClient( 6816): IrrcClient -- 
W/irrc_jni( 6816): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6816): Services init done
I/UEI.SmartControl( 6816): Device manager: loading config....
D/UEI.SmartControl( 6816): QS Service init finished
,D/UEI.SmartControl( 6816): QS Service version name: 0.1.73
D/UEI.SmartControl( 6816): QS Service version code: 1073
D/UEI.SmartControl( 6816): Service requested: Control
D/UEI.SmartControl( 6816): Config is loaded...
D/UEI.SmartControl( 6816):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6816): Notify AllClients services are ready: 0
,I/CloudHub( 2652): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19952
D/UEI.SmartControl( 6816): Request IControl service: devices are loaded...
D/UEI.SmartControl( 6816): Service.onUnbind: IControl
D/UEI.SmartControl( 6816): Service.onDestroy
D/UEI.SmartControl( 6816): Shutdown IRRCPlayer... 
W/irrc_jni( 6816): IRRCPlayer_nativeFinalize ++ 
,D/irrcClient( 6816): ~IrrcClient ++ 
D/irrcClient( 6816): ~IrrcClient -- 
W/irrc_jni( 6816): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6816): Blaster closed
D/UEI.SmartControl( 6816): Blaster closed
D/UEI.SmartControl( 6816): Shut down QS...
D/UEI.SmartControl( 6816): Stopped file observer...
I/UEI.SmartControl( 6816): QS lib stop result = true
D/UEI.SmartControl( 6816): QS shutdown complete
D/UEI.SmartControl( 6816): QS Service created
E/UEI.SmartControl( 6816): QS start get config
,D/UEI.SmartControl( 6816):  configuring local db...
,I/UpdateIcingCorporaServi( 1949): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 6433): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 6433): Null package name or gms related package.  Ignoreing.
I/Icing   ( 6433): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 1949): UpdateCorporaTask done [took 63 ms] updated apps [took 63 ms] 
,D/UEI.SmartControl( 6816):  ---- Has DB8: true
,D/UEI.SmartControl( 6816): QS start statue = true Error code = 0
D/UEI.SmartControl( 6816): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6816): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6816): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6816): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6816): IrrcClient ++ 
D/irrcClient( 6816): getIrrcService ++ 
D/irrcClient( 6816): getIrrcService -- 
D/irrcClient( 6816): IrrcClient -- 
W/irrc_jni( 6816): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6816): Services init done
I/UEI.SmartControl( 6816): Device manager: loading config....
D/UEI.SmartControl( 6816): QS Service init finished
D/UEI.SmartControl( 6816): QS Service version name: 0.1.73
D/UEI.SmartControl( 6816): QS Service version code: 1073
D/UEI.SmartControl( 6816): Service requested: Control
D/UEI.SmartControl( 6816): Config is loaded...
D/UEI.SmartControl( 6816):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6816): Notify AllClients services are ready: 0
,D/UEI.SmartControl( 6816): Request IControl service: devices are loaded...
I/ActivityManager(  964): Killing 2652:com.lge.music/u0a28 (adj 15): empty #11
V/AudioFlinger(  279): 2652 died, releasing its sessions
V/AudioFlinger(  279):  pid 1748 @ 0
V/AudioFlinger(  279):  pid 3141 @ 1
V/AudioFlinger(  279):  pid 3141 @ 2
,W/libprocessgroup(  964): failed to open /acct/uid_10028/pid_2652/cgroup.procs: No such file or directory
,E/ActivityThread( 6816): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@20df47fa that was originally bound here
E/ActivityThread( 6816): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@20df47fa that was originally bound here
E/ActivityThread( 6816): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6816): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6816): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6816): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6816): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6816): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6816): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6816): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6816): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6816): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6816): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6816): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6816): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6816): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6816): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6816): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6816): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6816): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6816): Internal service binding...
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/Icing   ( 6433): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 6433): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  964): Killing 6681:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10038/pid_6681/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 289, mChargingStatus=5, mChargingStop=false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  964): Killing 6611:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  964): failed to open /acct/uid_10006/pid_6611/cgroup.procs: No such file or directory
,E/UEI.SmartControl( 6816): file observer is disposed!
,D/PowerManagerServiceEx(  964): acquireWakeLockInternal: lock=782920401, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
,D/WeatherService( 2623): 2 : TimeTick Intent has been received, Time(hour:min:sec) 14:37:0
D/WeatherService( 2623): 2 : TimeTick Intent And Screen On
D/WeatherService( 2623): 2 : SDK version : 21
W/ActivityManager(  964): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2623): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2623): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2623): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2623): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2623): 2 : This is isUpdating : false
D/WeatherService( 2623): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2623): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2623): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2623): 2 : Fixed theme : optimus
D/WeatherReflect( 2623): 2 : Map key string is -2
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
D/lim     ( 2623): 2 : time = 14:37
I/WeatherReflect( 2623): Model Name : LG-D722
D/WeatherTheme( 2623): 2 : Different view - status_min_formatted : 36 != 37
D/WeatherTheme( 2623): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
,D/WeatherReflect( 2623): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2623): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2623): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2623): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2623): currentPackage=com.lge.sizechangable.weather.theme.optimus
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/Weather4x2_optimus( 2623): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2623): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2623): forecast size is 0
D/Theme   ( 2623): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2623): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2623): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2623): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2623): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2623): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2623): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2623): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2623): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2623): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2623): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2623): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2623): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2623): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2623): setTouchIntent, appWidgetId: 2
,D/Theme_WeatherAncestor_optimus( 2623): url is : null
D/Theme   ( 2623): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2623): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2623): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2623): 2 : update view, appWidgetId: 2
D/WeatherService( 2623): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 14:37:0
,D/PowerManagerServiceEx(  964): releaseWakeLockInternal: lock=782920401 [*alarm*], flags=0x0
,I/[LgeWidgetLib]LgeAppWidgetHostView( 1873): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1873): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,D/UEI.SmartControl( 6816): Internal timer expired: 2
,D/UEI.SmartControl( 6816): Service.onUnbind: IControl
D/UEI.SmartControl( 6816): Service.onDestroy
D/UEI.SmartControl( 6816): Shutdown IRRCPlayer... 
W/irrc_jni( 6816): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6816): ~IrrcClient ++ 
D/irrcClient( 6816): ~IrrcClient -- 
W/irrc_jni( 6816): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6816): Blaster closed
D/UEI.SmartControl( 6816): Blaster closed
D/UEI.SmartControl( 6816): Shut down QS...
I/UEI.SmartControl( 6816): QS lib stop result = true
D/UEI.SmartControl( 6816): QS shutdown complete
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/CheckinService( 6433): Done disabling old GoogleServicesFramework version
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 134643310868; DSPS: 4503742; Offset : -2813233849
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{39c15936 type 2 when 141483 com.google.android.gms} when 141483
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1730): Vacuum at: now=1456925833687 tag=VacuumService
W/InstanceID/Rpc( 6433): Found 10006
,I/art     (  964): Explicit concurrent mark sweep GC freed 33742(1678KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/35MB, paused 3.937ms total 158.976ms
,I/PhenotypeConfigurator( 1730): Scheduling Phenotype for one-off execution 9559 seconds from now (1456925834329)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/art     ( 1730): Explicit concurrent mark sweep GC freed 51853(3MB) AllocSpace objects, 32(512KB) LOS objects, 40% free, 13MB/22MB, paused 1.508ms total 98.820ms
,I/PhenotypeFlagCommitter( 1730): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1730): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  272): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  272): App 10006 tries DNS query. Accept family:0 protocol:0
,D/libc-netbsd(  272): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  272): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  272): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  272): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  272): res_queryN name = xxxxx succeed
I/System.out( 1730): propertyValue:false
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1730): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1730): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1730): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  964): ALS enabled for SRE
D/PowerManagerServiceEx(  964): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (27902 ms ago)
,D/qdlights(  964): set_light_backlight: 252
,D/qdlights(  964): set_light_backlight: 249
D/qdlights(  964): set_light_backlight: 245
,D/qdlights(  964): set_light_backlight: 242
,D/qdlights(  964): set_light_backlight: 239
,D/qdlights(  964): set_light_backlight: 235
,D/qdlights(  964): set_light_backlight: 232
,D/qdlights(  964): set_light_backlight: 229
,D/qdlights(  964): set_light_backlight: 225
,D/qdlights(  964): set_light_backlight: 222
,D/qdlights(  964): set_light_backlight: 219
,D/qdlights(  964): set_light_backlight: 215
,D/qdlights(  964): set_light_backlight: 212
,D/qdlights(  964): set_light_backlight: 209
,D/qdlights(  964): set_light_backlight: 205
,D/qdlights(  964): set_light_backlight: 202
,D/qdlights(  964): set_light_backlight: 199
,D/qdlights(  964): set_light_backlight: 195
,D/qdlights(  964): set_light_backlight: 192
,D/qdlights(  964): set_light_backlight: 189
,D/qdlights(  964): set_light_backlight: 185
,D/qdlights(  964): set_light_backlight: 182
,D/qdlights(  964): set_light_backlight: 179
,D/qdlights(  964): set_light_backlight: 175
,D/qdlights(  964): set_light_backlight: 172
,D/qdlights(  964): set_light_backlight: 169
,D/qdlights(  964): set_light_backlight: 165
,D/qdlights(  964): set_light_backlight: 162
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdlights(  964): set_light_backlight: 159
,D/qdlights(  964): set_light_backlight: 155
,D/qdlights(  964): set_light_backlight: 152
,D/qdlights(  964): set_light_backlight: 149
,D/qdlights(  964): set_light_backlight: 145
,D/qdlights(  964): set_light_backlight: 142
,D/qdlights(  964): set_light_backlight: 139
,D/qdlights(  964): set_light_backlight: 135
,D/qdlights(  964): set_light_backlight: 132
,D/qdlights(  964): set_light_backlight: 129
,D/qdlights(  964): set_light_backlight: 125
,D/qdlights(  964): set_light_backlight: 122
,D/qdlights(  964): set_light_backlight: 119
,D/qdlights(  964): set_light_backlight: 115
,D/qdlights(  964): set_light_backlight: 112
,D/qdlights(  964): set_light_backlight: 109
,D/qdlights(  964): set_light_backlight: 105
,D/qdlights(  964): set_light_backlight: 102
,D/qdlights(  964): set_light_backlight: 99
,D/qdlights(  964): set_light_backlight: 95
,D/qdlights(  964): set_light_backlight: 92
,D/qdlights(  964): set_light_backlight: 89
,D/qdlights(  964): set_light_backlight: 85
,D/qdlights(  964): set_light_backlight: 82
,D/qdlights(  964): set_light_backlight: 79
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/qdlights(  964): set_light_backlight: 75
D/qdlights(  964): set_light_backlight: 72
,D/qdlights(  964): set_light_backlight: 69
,D/qdlights(  964): set_light_backlight: 65
,D/qdlights(  964): set_light_backlight: 62
,D/qdlights(  964): set_light_backlight: 59
,D/qdlights(  964): set_light_backlight: 55
,D/qdlights(  964): set_light_backlight: 52
,D/qdlights(  964): set_light_backlight: 49
,D/qdlights(  964): set_light_backlight: 45
,D/qdlights(  964): set_light_backlight: 42
,D/qdlights(  964): set_light_backlight: 39
,D/qdlights(  964): set_light_backlight: 35
,D/qdlights(  964): set_light_backlight: 32
,D/qdlights(  964): set_light_backlight: 29
,D/qdlights(  964): set_light_backlight: 25
,D/qdlights(  964): set_light_backlight: 22
,D/qdlights(  964): set_light_backlight: 19
,D/qdlights(  964): set_light_backlight: 15
,D/qdlights(  964): set_light_backlight: 12
,D/qdlights(  964): set_light_backlight: 10
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 154644073380; DSPS: 5159128; Offset : -2813264117
,I/PowerManagerService(  964): ALS enabled for SRE
D/PowerManagerServiceEx(  964): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (34905 ms ago)
,I/PowerManagerService(  964): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  964): ALS enabled for SRE
D/PowerManagerServiceEx(  964): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (34934 ms ago)
W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  964): Sleeping (uid 1000)...
D/LPWGController(  964): [updateScreenState] screen on = false
D/LPWGController(  964): disable proximity sensor
,D/LPWGController(  964): enable proximity sensor
I/SensorManager(  964): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@2f6f721f] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  964): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  964): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  964): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  964): activate: handle is 48, enable
,V/sensors_hal_Ctx(  964): activate sensors is 1400000000000
D/sensors_hal_Thresh(  964): enable: handle=48
I/sensors_hal_SAM(  964): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  964): waitForResponse: timeout=1000
V/sensors_hal_SAM(  964): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  964): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  964): enable: Received response: 0
D/PowerManagerServiceEx(  964): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (35019 ms ago)
I/Adreno-EGL(  964): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  964): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  964): Build Date: 03/02/15 Mon
I/Adreno-EGL(  964): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  964): Remote Branch: 
I/Adreno-EGL(  964): Local Patches: 
I/Adreno-EGL(  964): Reconstruct Branch: 
,D/PermissionCache(  246): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1735 us)
,I/Sensors (  436): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  964): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  964): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
D/sensors_hal_Thresh(  964): processInd: SNS_SAM_SENSOR_THRESH_REPORT_IND_V01
D/sensors_hal_Thresh(  964): processInd: handle 48, count=1
V/sensors_hal_Thresh(  964): processInd:sensor android.sensor.proximity (wake_up)
I/sensors_hal_Thresh(  964): processInd : proximity state changed - FAR
D/sensors_hal_Ctx(  964): poll:polldata:1, sensor:48, type:8, x:5.000000 y:-0.000007 z:0.000000
D/sensors_hal_Ctx(  964): poll: count: 256
I/sensors_hal_Ctx(  964): poll: released wakelock sensor_ind
D/sensors_hal_Util(  964): waitForResponse: timeout=0
D/LPWGController(  964): proximity onSensorChanged : proximity = 1, mSensorCovered=false, isFar=true
I/LPWGController(  964): current mode = 1  value = 1 1
I/LPWGController(  964): [setLPWGmode2] current mode = 1  value = 9 1 1 1 0
I/LPWGController(  964): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1371): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
D/qdlights(  964): set_light_backlight: 0
,I/SensorManager(  964): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  964): activate: handle is 46, disable
V/sensors_hal_Ctx(  964): activate sensors is 1000000000000
D/sensors_hal_LP2(  964): enable: handle=46
D/sensors_hal_LP2(  964): enable: Disabling sensor handle=46
I/sensors_hal_SAM(  964): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  246): Set power mode=0, type=0 flinger=0xb6082000
D/qdhwcomposer(  246): hwc_blank: Blanking display: 0
I/DisplayManagerService(  964): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  964): Display changed displayId=0
,V/sensors_hal_SAM(  964): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  964): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1748): Display #0 changed.
,D/qdhwcomposer(  246): hwc_blank: Done blanking display: 0
,I/qdhwcomposer(  246): handle_blank_event: dpy:0 panel power state: 0
D/SurfaceControl(  964): Excessive delay in setPowerMode(): 239ms
I/QCOM PowerHAL(  964): Got set_interactive hint
,D/KeyguardViewMediator( 1371): onScreenTurnedOff(3)
,D/SmartCoverViewMediator( 1329): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1371): notifyScreenOffLocked
D/SmartCoverViewMediator( 1329): notifyScreenOffLocked
,D/SmartCoverViewMediator( 1329): handleNotifyScreenOFF
D/JX-Cordova( 5325): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5325): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5325): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ce109bd added. We now have 3 listener(s)
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5325): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5325): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21f6ebb2 added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5325): addListener: New listener added - the number of listeners is now 1
,D/BluetoothAdapterService(551503866)( 2053): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3a1dc820
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5325): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
D/KeyguardViewMediator( 1371): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1371): handleNotifyScreenOff
W/System.err( 5325): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,D/ScreenTurnOffBySensor( 1371): unregisterProximitySensor
,D/WifiServerServiceExt(  964): sendKtScanInterval  mRtspPlay : false
D/StatusBarWindowView( 1371): onScreenTurnedOff why = 3
V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=on, calling pid 964
,D/audio_hw_primary(  279): adev_set_parameters: enter: screen_state=on
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
W/System.err( 5325): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:85)
W/System.err( 5325): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 5325): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 5325): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 5325): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 5325): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 5325): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 5325): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 5325): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 5325): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 5325): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5325): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5325): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/WifiServerServiceExt(  964): set CMD_KT_SCAN_INTERVAL
,D/GpsLocationProvider(  964): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1836): |CORE| sendScreenState: state:true
I/LEDService( 1800): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1800): stopPatternFlashing()
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
I/LEDService( 1800): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
I/LEDService( 1800): updateLightsLocked : turn off led
,D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1800): RESTART MSG
D/SplitWindow(  964): check instance of lgWin Window{1c19bca u0 SearchPanel}
,I/Cliptray Service( 1800): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/Cliptray Service( 1800): lockStatus = 0
D/InputDispatcher(  964): Window went away: Window{32798490 u0 SearchPanel}
,I/[SystemUI]Clock( 1371): onReceive = android.intent.action.SCREEN_ON
I/LgeClockWidgetControlView( 1371): time changed, timezoneChanged : false
,D/LNfcService( 1783): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1783): mScreenState : 3, mInProvisionMode : false
,D/NfcServiceNXP( 1783): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1783): isRequireNfcCRouting() return true
D/LNfcService( 1783): isHCERoutingtoHost() return : true
,D/NfcService( 1783): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): newParams.techmask= mTechMask: default
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): screenState= 3
D/NfcService( 1783): Discovery configuration equal, not updating.
D/Ulp_jni (  964): JNI:system_update. Event-0
,V/PhoneApp( 1748): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2623): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:37:28,
D/WeatherService( 2623): 2 : ACTION screen on
D/WeatherService( 2623): 2 : shouldTimeTickRegistered : false
,D/Weather_cast( 2623): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2623): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 14:37:28
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_ON
D/AppCleanupService( 4203): android.intent.action.SCREEN_ON
,V/AudioFlinger(  279): setParameters(): io 0, keyvalue screen_state=off, calling pid 964
D/audio_hw_primary(  279): adev_set_parameters: enter: screen_state=off
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
D/WifiController(  964): CMD_SCREEN_OFF 
D/WifiController(  964): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  964): receive broadcast intent, action: android.intent.action.SCREEN_OFF
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.SCREEN_OFF
,I/QCNEJ   ( 1836): |CORE| sendScreenState: state:false
,I/LEDService( 1800): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1800): stopPatternFlashing()
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
I/Sensors (  436): sns_pwr.c(301):releasing wakelock
I/LEDService( 1800): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1800): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1800): clear
I/LEDService( 1800): updateLightsLocked : turn on led
E/LEDService( 1800): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
E/LEDService( 1800): Can't handle this request of patternId:0
D/LEDHandler( 1800): RESTART MSG
I/Cliptray Service( 1800): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/LNfcService( 1783): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1783): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1873): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1748): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2623): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:37:28
D/WeatherService( 2623): 2 : ACTION screen off
,D/WeatherService( 2623): 2 : TimeTick Receiver Unregister
D/WeatherService( 2623): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 14:37:28
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_OFF
D/AppCleanupService( 4203): android.intent.action.SCREEN_OFF
D/AppCleanupService( 4203): AppUsageStatsSaveTask
,E/NxpNfcJni( 1783): getReconnectState = 0x0
,D/LCardEmulationManager( 1783): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1783): getDefaultRoute
D/LNfcService( 1783): isRequireNfcCRouting() return true
D/LNfcService( 1783): isHCERoutingtoHost() return : true
D/NfcService( 1783): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
,D/NfcService( 1783): newParams.techmask= mTechMask: 0
D/NfcService( 1783): mEnableLPD: true
D/NfcService( 1783): mEnableReader: false
D/NfcService( 1783): mEnableHostRouting: true
D/NfcService( 1783): screenState= 1
E/NxpNfcJni( 1783): getReconnectState = 0x0
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/KeyguardViewMediator( 1371): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{523113b type 2 when 160930 com.android.systemui} when 160930
,D/PhoneUtils( 1748): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1748): getCallState : 0
D/PhoneUtils( 1748): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1748): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1371): isHdmiPluggedIn :false
,D/KeyguardViewMediator( 1371): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 169646042429; DSPS: 5650713; Offset : -2813281211
,I/ThermalEngine(  292): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{2dd08058 type 2 when 186810 com.google.android.gms} when 186810
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 187149493481; DSPS: 6224267; Offset : -2813307104
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ClearcutLoggerApiImpl( 1730): disconnect managed GoogleApiClient
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 202151308986; DSPS: 6715848; Offset : -2813352963
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 217153633272; DSPS: 7207441; Offset : -2813258675
,I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  964): acquireWakeLockInternal: lock=782920401, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{24f1a5b1 type 2 when 197760 android} when 197760
D/PowerManagerServiceEx(  964): releaseWakeLockInternal: lock=782920401 [*alarm*], flags=0x0
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 232156055487; DSPS: 7699042; Offset : -2813308435
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 283
,I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 283
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 283, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
,D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 249659469678; DSPS: 8272593; Offset : -2813281539
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 269661653475; DSPS: 8928027; Offset : -2813354090
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 284663816985; DSPS: 9419616; Offset : -2813296371
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 304666101465; DSPS: 10075050; Offset : -2813272172
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 324668850696; DSPS: 10730500; Offset : -2813269549
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/LocationManagerService(  964): remove 4d1f01
D/LocationManagerService(  964): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  964): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  964): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  964): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  964): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 347173951394; DSPS: 11467949; Offset : -2813324265
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 362176200379; DSPS: 11959540; Offset : -2813244137
,I/ThermalEngine(  292): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 379679597855; DSPS: 12533092; Offset : -2813262571
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 394682089718; DSPS: 13024694; Offset : -2813273098
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 412185574281; DSPS: 13598248; Offset : -2813269623
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
D/PowerManagerServiceEx(  964): acquireWakeLockInternal: lock=782920401, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
,D/PowerManagerServiceEx(  964): releaseWakeLockInternal: lock=782920401 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 432187824821; DSPS: 14253680; Offset : -2813216348
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 452190534691; DSPS: 14909130; Offset : -2813250716
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 467192807479; DSPS: 15400725; Offset : -2813269038
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 480324841571; DSPS: 15831033; Offset : -2813190897
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 500327145215; DSPS: 16486473; Offset : -2813328633
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 520329449600; DSPS: 17141907; Offset : -2813284735
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 540331721923; DSPS: 17797340; Offset : -2813240119
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 560332433221; DSPS: 18452725; Offset : -2813289493
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 580334592538; DSPS: 19108154; Offset : -2813238103
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/PowerManagerServiceEx(  964): acquireWakeLockInternal: lock=782920401, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{3345aa96 type 2 when 595009 android} when 595009
D/PowerManagerServiceEx(  964): releaseWakeLockInternal: lock=782920401 [*alarm*], flags=0x0
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 600336938250; DSPS: 19763592; Offset : -2813272814
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 620339170480; DSPS: 20419022; Offset : -2813176893
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 642844230864; DSPS: 21156471; Offset : -2813273901
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 662846525331; DSPS: 21811906; Offset : -2813268280
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 677848457843; DSPS: 22303488; Offset : -2813225801
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 692852877492; DSPS: 22795153; Offset : -2813233283
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 714108234786; DSPS: 23491647; Offset : -2813185996
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 727240680975; DSPS: 23921969; Offset : -2813125087
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
,I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 741156406714; DSPS: 24377964; Offset : -2813260327
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 755227839390; DSPS: 24839052; Offset : -2813118744
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 768362060324; DSPS: 25269439; Offset : -2813266682
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 787742960552; DSPS: 25904514; Offset : -2813317381
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 802745081429; DSPS: 26396104; Offset : -2813330703
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 817747673575; DSPS: 26887723; Offset : -2813759769
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 830882105428; DSPS: 27318096; Offset : -2813271627
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 847763872405; DSPS: 27871278; Offset : -2813277520
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 867765809793; DSPS: 28526697; Offset : -2813142779
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 882770453823; DSPS: 29018375; Offset : -2813318078
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 897774539849; DSPS: 29510027; Offset : -2813262769
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 916529099171; DSPS: 30124574; Offset : -2813189530
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 936531782754; DSPS: 30780022; Offset : -2813191468
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  964): acquireWakeLockInternal: lock=782920401, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=964
,V/AlarmManager(  964): ELAPSED_WAKEUP set : Alarm{14a78617 type 2 when 948032 com.android.bluetooth} when 948032
W/bt-smp  ( 2053): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2053): Plain text(LSB ~ MSB) = 1a 88 40 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 2053): Encrypted text(LSB ~ MSB) = 5d 09 10 d3 93 2e d1 b1 bd 21 67 65 52 10 d5 eb 
W/bt-btm  ( 2053): Stopping oneshot timer
I/ActivityManager(  964): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7208 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 7208): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7208): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@5bc2f0
I/ActivityManager(  964): Killing 6752:com.lge.appbox.client/u0a11 (adj 15): empty #11
,W/libprocessgroup(  964): failed to open /acct/uid_10011/pid_6752/cgroup.procs: No such file or directory
,D/PowerManagerServiceEx(  964): releaseWakeLockInternal: lock=782920401 [*alarm*], flags=0x0
I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 951533352513; DSPS: 31271596; Offset : -2813267575
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 971535581116; DSPS: 31927030; Offset : -2813297429
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 991537853907; DSPS: 32582460; Offset : -2813160765
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1006539597746; DSPS: 33074043; Offset : -2813339689
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1026541995331; DSPS: 33729477; Offset : -2813200300
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 267, mChargingStatus=5, mChargingStop=false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 267
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 267
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1049046699658; DSPS: 34466912; Offset : -2813226173
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1069049162642; DSPS: 35122352; Offset : -2813204594
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1089051801056; DSPS: 35777797; Offset : -2813160227
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 266, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1103123593508; DSPS: 36238905; Offset : -2813267292
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1118125874969; DSPS: 36730499; Offset : -2813244002
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1133127677108; DSPS: 37222079; Offset : -2813274871
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1147199365514; DSPS: 37683183; Offset : -2813361804
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1168455036796; DSPS: 38379684; Offset : -2813214178
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1188457113774; DSPS: 39035104; Offset : -2812970390
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 265, mChargingStatus=5, mChargingStop=false
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 265
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1210961534417; DSPS: 39772538; Offset : -2813247422
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/UsageStatsService(  964): User[0] Flushing usage stats to disk
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1227217582171; DSPS: 40305218; Offset : -2813303184
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1242219527290; DSPS: 40796800; Offset : -2813250259
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1259723050628; DSPS: 41370355; Offset : -2813236313
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1279725323168; DSPS: 42025788; Offset : -2813191556
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1299727673011; DSPS: 42681228; Offset : -2813285175
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1314729825373; DSPS: 43172822; Offset : -2813388822
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1335985449781; DSPS: 43869328; Offset : -2813440971
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1350056828200; DSPS: 44330418; Offset : -2813412571
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1364444392218; DSPS: 44801862; Offset : -2813177656
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1381947944298; DSPS: 45375422; Offset : -2813287684
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 265, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 265
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1404453645829; DSPS: 46112874; Offset : -2812835204
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1426957889319; DSPS: 46850305; Offset : -2813199789
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1440089096597; DSPS: 47280593; Offset : -2813340427
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1371): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1371): called onTimeUpdated()
I/[SystemUI]Clock( 1371): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
I/[SystemUI]DateView( 1371): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1371): handleTimeUpdate
I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/PowerService( 1800): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1371): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1371): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1371): On Skip Timer : true
D/charger_monitor(  487): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2053): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1836): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1836): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1800): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1800): Battery Level Remaining: 100%
D/LEDHandler( 1800): Battery Temp: 264, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1371): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 264
I/[SystemUI]LGPowerUI( 1371): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1371): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 264
I/[SystemUI]BatterySaverHandler( 1371): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  964): battery changed pluggedType: 2
I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1458844190922; DSPS: 47895156; Offset : -2813220260
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  964): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  964): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  964): tsOffsetIs: Apps: 1473846480364; DSPS: 48386752; Offset : -2813250180
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  292): Sensor:pa_therm0:27000 mC
,TIME-OUT KILL (timeout was 1400000ms)
```
