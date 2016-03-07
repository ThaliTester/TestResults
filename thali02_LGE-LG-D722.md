#### Test 613623665d5a4d6_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
E/UEI.SmartControl( 4916): QS start get config
D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 72469359298; DSPS: 2466376; Offset : -2809457080
D/libc-netbsd(  267): res_queryN name = xxxxx succeed
I/CheckinRequestBuilder( 4299): Checkin reason type: 8 attempt count: 1
I/System.out( 4941): propertyValue:false
--------- beginning of system
E/ActivityThread( 4299): Failed to find provider info for com.google.android.wearable.settings
W/ResourcesManager( 4967): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/LGDrmClient( 4941): _DRM_ServiceGet() : Bind lgdrm service
V/ILGDrmService(  287): eDRM_SetDRMTime +++
,D/UEI.SmartControl( 4916): Loading JNI Libs...
D/UEI.SmartControl( 4916):  configuring local db...
I/LGDRM   (  287): [DRM] SET TIME : YR=2016, MON=3, DAY=7
I/LGDRM   (  287): [DRM] SET TIME : HR=9, MIN=51, SEC=2
V/ILGDrmService(  287): eDRM_SetDRMTime ---
I/DrmSntpClient( 4941): Synched
D/DrmService( 4941): Completed !! request = 2
D/DrmService( 4941): Request count = 0
V/DrmService( 4941): Service onDestroy
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  857): Waited long enough for: ServiceRecord{18a5426e u0 com.lge.springcleaning/.service.AppCleanupService}
D/UEI.SmartControl( 4916):  ---- Has DB8: true
D/UEI.SmartControl( 4916): QS start statue = true Error code = 0
D/UEI.SmartControl( 4916): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 4916): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 4916): IRRCDataComm has AudioManager!!!!.
I/Babel_SMS( 4967): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 4967): MmsConfig.loadMmsSettings
I/Babel_SMS( 4967): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 4967): MmsConfig.loadFromDatabase
W/irrc_jni( 4916): IRRCPlayer_nativeInit ++ 
D/irrcClient( 4916): IrrcClient ++ 
D/irrcClient( 4916): getIrrcService ++ 
D/irrcClient( 4916): getIrrcService -- 
D/irrcClient( 4916): IrrcClient -- 
W/irrc_jni( 4916): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 4916): Services init done
I/UEI.SmartControl( 4916): Device manager: loading config....
D/UEI.SmartControl( 4916): QS Service init finished
D/UEI.SmartControl( 4916): QS Service version name: 0.1.73
D/UEI.SmartControl( 4916): QS Service version code: 1073
D/UEI.SmartControl( 4916): Config is loaded...
D/AndroidRuntime( 4993): 
D/AndroidRuntime( 4993): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4993): CheckJNI is OFF
D/UEI.SmartControl( 4916): Service requested: Control
D/UEI.SmartControl( 4916): Internal service binding...
D/UEI.SmartControl( 4916): -----IControl: 11
D/UEI.SmartControl( 4916): Caller: com.lge.qremote
D/UEI.SmartControl( 4916): ------------ IControl registerCallback...
I/UEI.SmartControl( 4916): Registering callback...
D/UEI.SmartControl( 4916): -----IControl: 19
D/UEI.SmartControl( 4916): Caller: com.lge.qremote
I/UEI.SmartControl( 4916): Registering Services Ready callback...
I/UEI.SmartControl( 4916): Notify client services are ready...
D/UEI.SmartControl( 4916): -----IControl: 8
D/UEI.SmartControl( 4916): Caller: com.lge.qremote
D/UEI.SmartControl( 4916):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 4916): Notify AllClients services are ready: 0
E/Babel_SMS( 4967): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 4967): MmsConfig.loadFromResources
E/Babel_SMS( 4967): canonicalizeMccMnc: invalid mccmnc nullnull
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/Babel_SMS( 4967): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/SensorManager( 4967): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 4967): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 4967): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 4967): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 4967): found sensor: LGE Gravity Sensor, handle=29
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/SensorManager( 4967): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 4967): found sensor: LGE Rotation Vector Sensor, handle=36
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/SensorManager( 4967): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 4967): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 4967): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 4967): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 4967): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 4967): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 4967): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 4967): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 4967): found sensor: Motion Accel, handle=46
E/BandwidthController(  267): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  267): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  267): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  267): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  267): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  267): res_queryN name = xxxxx, class = 1, type = 1
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
W/Settings( 4967): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/Babel_Crash( 4967): startup - clean
D/libc-netbsd(  267): res_queryN name = xxxxx succeed
I/System.out( 1731): propertyValue:false
I/art     ( 4967): CheckpointMarkThreadRoots callback created = 0xb042d810
I/Babel   ( 4967): deleted: false for 0
I/art     ( 4967): CheckpointMarkThreadRoots callback created = 0xb042d800
W/art     ( 4967): Suspending all threads took: 6.715ms
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/ActivityManager(  857): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5023 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  857): Killing 4710:com.lge.sync/1000 (adj 15): empty #11
D/AndroidRuntime( 4993): Calling main entry com.android.commands.am.Am
W/libprocessgroup(  857): failed to open /acct/uid_1000/pid_4710/cgroup.procs: No such file or directory
I/ActivityManager(  857): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
W/AudioCapabilities( 4967): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 4967): Unsupported mime audio/adpcm
W/AudioCapabilities( 4967): Unsupported mime audio/g726
W/AudioCapabilities( 4967): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 4967): Unsupported mime audio/wma-voice
W/VideoCapabilities( 4967): Unsupported mime video/mjpg
W/VideoCapabilities( 4967): Unsupported mime video/theora
D/ActivityManager(  857): setTaskToReturnTo : TaskRecord{31d0298b #224 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
W/AudioCapabilities( 4967): Unsupported mime audio/evrc
W/AudioCapabilities( 4967): Unsupported mime audio/qcelp
W/VideoCapabilities( 4967): Unrecognized profile 2130706433 for video/avc
D/ActivityManager(  857): setTaskToReturnTo : TaskRecord{31d0298b #224 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
W/AudioCapabilities( 4967): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 4967): Unsupported mime audio/qcelp
W/AudioCapabilities( 4967): Unsupported mime audio/evrc
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/WindowStateEx(  857): AppWindowTokenEx init.. 
W/VideoCapabilities( 4967): Unsupported mime video/mp4v-esdp
D/ContextHelper(  857): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/InputDispatcher(  857): Focus left window: Window{4f27ae0 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
I/PhoneWindow(  857): [generateLayout] setColorNavigationBar => color=0x ff000001
I/[LGHome]EVENT( 1875): [Launcher.java:986:onPause()]onPause
D/PhoneWindowEx(  857): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow(  857): [setNavigationBarColor2] color=0x fff5f5f5
D/AndroidRuntime( 4993): Shutting down VM
D/SplitWindow(  857): check instance of lgWin Window{f223f03 u0 Starting com.test.thalitest}
I/VideoCapabilities( 4967): Unsupported profile 4 for video/mp4v-es
I/ActivityManager(  857): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5042 uid=10316 gids={50316, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
W/VideoCapabilities( 4967): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4967): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4967): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 4967): Unrecognized profile 2130706433 for video/avc
I/[LGHome]EVENT( 1875): [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
I/vclib   ( 4967): onServiceConnected
W/Babel   ( 4967): Attempted to change video mute state without an active call.
I/WindowStateAnimator(  857): Starting window displayed
I/NotificationManager( 4967): com.google.android.talk: cancel(10436) by com.google.android.talk
D/WindowManager(  857): [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
I/SystemUI[Framework](  857): PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
W/PhoneWindowManagerEx(  857): Call!!!getLGSystemUiVisibility. =0x0
I/[SystemUI]NavigationThemeResource( 1373): notify navigation bar color(0xfff5f5f5)
D/StatusBarManagerServiceEx(  857): setLGSystemUiVisibility(0x0)
D/StatusBarManagerServiceEx(  857): manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  857): ==>disabledNaviBtn() what=0x0, token=android.os.Binder@249da527,  pkg=WindowManager.LayoutParams
I/SystemUI[Framework](  857): disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
I/[SystemUI]NavigationThemeResource( 1373): NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
I/[SystemUI]NavigationThemeResource( 1373):  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
I/[SystemUI]NavigationThemeResource( 1373): , Keyguard show=false, IME shown=false, Panel expanded=false
I/[LGHome]EVENT( 1875): [Launcher.java:5214:onStop()]onStop
D/libc-netbsd( 4967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4967): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4967): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  267): [LG DATA] No such appUid: 10061
D/DnsProxyListener(  267): App 10061 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  267): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  267): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  267): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  267): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  267): res_queryN name = xxxxx succeed
I/System.out( 4967): propertyValue:false
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
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
I/ActivityManager(  857): Activity reported stop, but no longer stopping: ActivityRecord{24ac42f0 u0 com.lge.launcher2/.Launcher t223}
,I/HotwordDetector( 1933): Closing mic
,D/ContextHelper( 5042): convertTheme. context->name=com.test.thalitest themeResourceId=16974121
I/MicrophoneInputStream( 1933): mic_close com.google.android.apps.gsa.speech.audio.u@2e66d0e4
V/AudioRecord( 1933): stop()
D/AudioRecord( 1933): AudioRecord->stop()
,V/AudioFlinger(  271): RecordHandle::stop()
V/AudioFlinger(  271): RecordThread::stop
I/NotificationManager(  857): android: cancelAsUser(2) by android
V/AudioFlinger(  271): Record stopped OK
,V/AudioPolicyManager(  271): stopInput() input 17
V/AudioPolicyService(  271): AudioCommandThread() adding release patch delay 0
V/AudioPolicyService(  271): inserting command: 8 at index 0, num commands 0
V/AudioPolicyService(  271): AudioCommandThread() waking up
V/AudioPolicyService(  271): AudioCommandThread() processing release audio patch
V/AudioFlinger::PatchPanel(  271): releaseAudioPatch handle 18
V/AudioFlinger::PatchPanel(  271): releaseAudioPatch() AUDIO_PORT_TYPE_DEVICE setParameters routing=0
V/AudioFlinger(  271): ThreadBase::setParameters() routing=0
D/audio_hw_primary(  271): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
I/Babel   ( 4967): connection state changed from UNKNOWN to CONNECTED
,I/ActivityManager(  857): Killing 4640:com.lge.qremote/u0a106 (adj 15): empty #11
,V/audio_hw_primary(  271): stop_input_stream: enter: usecase(7: audio-record)
V/audio_hw_primary(  271): disable_audio_route: enter: usecase(7)
V/msm8974_platform_lge(  271): LGE_platform_add_backend_name: enter: 144
V/audio_hw_primary(  271): disable_audio_route: reset and update mixer path: audio-record
,I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
V/audio_hw_primary(  271): disable_audio_route: exit
E/audio_hw_primary(  271): disable_snd_device: enter 144
D/hardware_info(  271): hw_info_append_hw_type : device_name = lg-vr-handset-mic
V/audio_hw_primary(  271): disable_snd_device: snd_device(144: lg-vr-handset-mic)
V/audio_hw_primary(  271): stop_input_stream: exit: status(0)
V/audio_hw_primary(  271): in_standby: exit:  status(0)
V/AudioFlinger(  271): RecordThread: loop stopping
V/AudioFlinger(  271): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  271): RecordThread: loop starting
V/AudioFlinger(  271): processConfigEvents_l() remaining events 1
V/AudioFlinger(  271): processConfigEvents_l() DONE thread 0xb384a000
V/AudioFlinger(  271): RecordThread: loop stopping
V/AudioPolicyService(  271): AudioCommandThread() going to sleep
V/AudioPolicyManager(  271): resetInputDevice() releaseAudioPatch returned -22
V/AudioPolicyManager(  271): removeAudioPatch() handle 18 af handle 18
V/AudioPolicyService(  271): AudioCommandThread() adding update audio patch list
V/AudioPolicyService(  271): inserting command: 10 at index 0, num commands 0
V/AudioPolicyService(  271): AudioCommandThread() waking up
V/AudioPolicyService(  271): AudioCommandThread() processing update audio patch list
V/AudioPolicyService(  271): AudioCommandThread() going to sleep
,V/AudioPolicyService(  271): AudioCommandThread() adding set parameter string hotword_active=0, io 17 ,delay 0
V/AudioPolicyService(  271): inserting command: 3 at index 0, num commands 0
V/AudioPolicyService(  271): AudioCommandThread() waking up
V/AudioPolicyService(  271): AudioCommandThread() processing set parameters string hotword_active=0, io 17
V/AudioFlinger(  271): setParameters(): io 17, keyvalue hotword_active=0, calling pid 271
V/AudioFlinger(  271): ThreadBase::setParameters() hotword_active=0
V/AudioFlinger(  271): sendConfigEvent_l() num events 1 event 2
V/AudioFlinger(  271): RecordThread: loop starting
V/AudioFlinger(  271): processConfigEvents_l() remaining events 1
D/audio_hw_primary(  271): in_set_parameters: enter: kvpairs=hotword_active=0
V/audio_hw_primary(  271): in_set_parameters: exit: status(0)
V/AudioFlinger(  271): processConfigEvents_l() DONE thread 0xb384a000
V/AudioFlinger(  271): RecordThread: loop stopping
V/AudioPolicyService(  271): AudioCommandThread() going to sleep
W/libprocessgroup(  857): failed to open /acct/uid_10106/pid_4640/cgroup.procs: No such file or directory
,V/AudioRecord( 1933): stop()
V/AudioRecord( 1933): stop()
V/AudioRecord( 1933): stop()
V/AudioFlinger(  271): RecordHandle::stop()
V/AudioFlinger(  271): RecordThread::stop
V/AudioPolicyManager(  271): releaseInput() 17
V/AudioPolicyManager(  271): closeInput(17)
V/AudioFlinger(  271): closeInput() 17
V/AudioSystem(  271): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  271): ThreadBase::exit
V/AudioFlinger(  271): RecordThread: loop starting
V/AudioSystem(  857): ioConfigChanged() event 4, ioHandle 17
V/AudioFlinger(  271): RecordThread 0xb384a000 exiting
D/audio_hw_primary(  271): adev_close_input_stream: enter:stream_handle(0xb546e420)
D/audio_hw_primary(  271): in_standby: enter: stream (0xb546e420) usecase(7: audio-record)
V/audio_hw_primary(  271): in_standby: exit:  status(0)
V/AudioPolicyService(  271): AudioCommandThread() adding update audio port list
V/AudioPolicyService(  271): inserting command: 9 at index 0, num commands 0
V/AudioPolicyService(  271): AudioCommandThread() waking up
V/AudioPolicyService(  271): AudioCommandThread() processing update audio port list
V/AudioPolicyService(  271): AudioCommandThread() going to sleep
V/AudioPolicyManager(  271): releaseInput() exit
V/AudioFlinger(  271): virtual android::AudioFlinger::RecordThread::RecordTrack::~RecordTrack()
V/AudioFlinger(  271): removeClient_l() pid 1933, calling pid 271
V/AudioSystem( 1933): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1373): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2015): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 1749): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 2653): ioConfigChanged() event 4, ioHandle 17
V/AudioSystem( 3148): ioConfigChanged() event 4, ioHandle 17
,V/AudioFlinger(  271): releasing 16 from 1933 for -1
V/AudioFlinger(  271):  decremented refcount to 0
V/AudioFlinger(  271): purging stale effects
I/WebViewFactory( 5042): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,I/HotwordRecognitionRnr( 1933): Stopping hotword detection.
I/HotwordRecognitionRnr( 1933): Hotword detection finished
,I/LibraryLoader( 5042): Time to load native libraries: 3 ms (timestamps 3941-3944)
,I/LibraryLoader( 5042): Expected native library version number "",actual native library version number ""
V/WebViewChromiumFactoryProvider( 5042): Binding Chromium to main looper Looper (main, tid 1) {2ea8d2cc}
,I/LibraryLoader( 5042): Expected native library version number "",actual native library version number ""
I/chromium( 5042): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,I/ActivityManager(  857): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=5066 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,I/BrowserStartupController( 5042): Initializing chromium process, singleProcess=true
,W/art     ( 5042): Attempt to remove local handle scope entry from IRT, ignoring
E/SysUtils( 5042): ApplicationContext is null in ApplicationStatus
,W/chromium( 5042): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
E/libEGL  ( 5042): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5042): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,I/Adreno-EGL( 5042): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5042): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5042): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5042): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5042): Remote Branch: 
I/Adreno-EGL( 5042): Local Patches: 
I/Adreno-EGL( 5042): Reconstruct Branch: 
W/ResourcesManager( 5066): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 5066): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
,E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5023): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5023): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/MultiDex( 5066): VM with version 2.1.0 has multidex support
I/MultiDex( 5066): install
I/MultiDex( 5066): VM has multidex support, MultiDex support library is disabled.
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5023): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5023): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
I/GAv4    ( 5023): Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5023):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5023):   adb logcat -s GAv4
,V/JNIHelp ( 5066): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
W/GAv4    ( 5023): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,V/AudioPolicyService(  271): registerClient() client 0xb3849260, uid 10316
D/BluetoothManagerService(  857): Message: 20
D/BluetoothManagerService(  857): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28301be5:true
,D/BluetoothAdapterService(214630939)( 2015): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@343881c9
W/GAv4    ( 5023): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/ActivityThread( 5066): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5066): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@13e698a9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5066): Installed default security provider GmsCore_OpenSSL
,W/GAv4    ( 5023): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
I/NotificationManager( 5066): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/NotificationManager( 5066): com.google.android.gms: cancel(39789) by com.google.android.gms
I/art     ( 5066): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 5066): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,W/art     ( 5042): Attempt to remove local handle scope entry from IRT, ignoring
,W/AwContents( 5042): onDetachedFromWindow called when already detached. Ignoring
,I/PhoneWindow( 5042): [generateLayout] setColorNavigationBar => color=0x ff000001
,D/PhoneWindowEx( 5042): [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
I/PhoneWindow( 5042): [setNavigationBarColor2] color=0x fff5f5f5
D/SystemWebViewEngine( 5042): CordovaWebView is running on device made by: LGE
,W/art     ( 5042): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 5042): Attempt to remove local handle scope entry from IRT, ignoring
D/NativeLibraryUtils( 5066): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): CdmEngine::OpenSession
I/WVCdm   (  271): Level3 Library Dec 11 2014 16:13:16
I/Activity( 5042): Activity.onPostResume() called 
D/OpenGLRenderer( 5042): Render dirty regions requested: true
I/OpenGLRenderer( 5042): Initialized EGL, version 1.4
,D/OpenGLRenderer( 5042): Enabling debug mode 0
,W/WVCdm   (  271): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  271): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  271): L1 library not specified. Falling Back to L3
D/Atlas   ( 5042): Validating map...
,I/GoogleURLConnFactory( 5066): Using platform SSLCertificateSocketFactory
D/SplitWindow(  857): check instance of lgWin Window{28895441 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/WebViewFactory( 5023): Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
W/chromium( 5042): [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,D/InputDispatcher(  857): Focus entered window: Window{28895441 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,I/art     ( 4045): Explicit concurrent mark sweep GC freed 2832(112KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 518us total 50.405ms
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
W/WVCdm   (  271): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  271): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
D/WVCdm   (  271): PrepareKeyRequest: nonce=147569380
,I/LibraryLoader( 5023): Time to load native libraries: 3 ms (timestamps 4880-4883)
I/LibraryLoader( 5023): Expected native library version number "",actual native library version number ""
,W/InputMethodManagerService(  857): setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
I/ActivityManager(  857): Process com.google.android.music:main (pid 4777) has died
V/WebViewChromiumFactoryProvider( 5023): Binding Chromium to main looper Looper (main, tid 1) {2fb9fe19}
I/LibraryLoader( 5023): Expected native library version number "",actual native library version number ""
,I/chromium( 5023): [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
I/ActivityManager(  857): Displayed com.test.thalitest/.MainActivity: +1s441ms
I/Timeline(  857): Timeline: Activity_windows_visible id: ActivityRecord{ecc3a68 u0 com.test.thalitest/.MainActivity t224} time:74902
I/Timeline( 5042): Timeline: Activity_idle id: android.os.BinderProxy@2b1e0ba6 time:74906
I/BrowserStartupController( 5023): Initializing chromium process, singleProcess=true
W/art     ( 5023): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 5023): ApplicationContext is null in ApplicationStatus
W/chromium( 5023): [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,E/libEGL  ( 5023): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
E/libEGL  ( 5023): validate_display:255 error 3008 (EGL_BAD_DISPLAY)
I/Adreno-EGL( 5023): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5023): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5023): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5023): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5023): Remote Branch: 
I/Adreno-EGL( 5023): Local Patches: 
I/Adreno-EGL( 5023): Reconstruct Branch: 
,D/libc-netbsd( 5066): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5066): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5066): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5066): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  267): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  267): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  267): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  267): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  267): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  267): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  267): res_queryN name = xxxxx succeed
I/System.out( 5066): propertyValue:false
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/InputReader(  857): Reconfiguring input devices.  changes=0x00000010
,I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
D/administrator(  857): Handling package changes for user 0
I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.mms/com.android.mms.ui.FloatingComposer in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calendar/com.android.calendar.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.filemanager/com.lge.filemanager.view.FloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.contacts/alias.PeopleFloatingActivity in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
W/[SystemUI]QSlideLoader( 1373): Cannot find com.android.calculator2/com.android.calculator2.QSlideCalculator in predefined list
I/[SystemUI]AppWidgetPanel(QRemoteWidgetPanel)( 1373): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
W/BindingManager( 5042): Cannot call determinedVisibility() - never saw a connection for the pid: 5042
,D/libc-netbsd( 5066): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5066): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5066): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5066): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/art     ( 1784): CheckpointMarkThreadRoots callback created = 0xaaf23c70
I/NotificationService(  857): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  857): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  857): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/art     ( 1784): CheckpointMarkThreadRoots callback created = 0xb042d340
W/ResourceType(  857): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,V/AudioPolicyService(  271): registerClient() client 0xb40277e0, uid 10079
W/AudioManagerAndroid( 5023): Requires BLUETOOTH permission
I/ActivityManager(  857): Process com.lge.email (pid 4821) has died
,I/BackupManagerService(  857): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
V/BackupManagerService(  857): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  857): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@59d6ae7
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/NSApplication( 5023): Starting up...
,I/GCoreNlp( 1731): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
D/JsMessageQueue( 5042): Set native->JS mode to OnlineEventsBridgeMode
,I/ActivityManager(  857): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5161 uid=10048 gids={50048, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/art     (  306): Explicit concurrent mark sweep GC freed 707(30KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 6MB/11MB, paused 323us total 37.125ms
,D/LocationProviderProxy(  857): applying state to connected service
,I/art     (  306): Explicit concurrent mark sweep GC freed 7(240B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 287us total 22.178ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 276us total 21.004ms
,I/art     ( 5066): CheckpointMarkThreadRoots callback created = 0xb04cbe70
,I/art     ( 5066): CheckpointMarkThreadRoots callback created = 0xaae47ed0
,I/ActivityManager(  857): Process com.lge.appbox.client (pid 4857) has died
,D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
D/jxcore_app_log( 5042): JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426642816
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5042): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5042):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5042):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5042):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5042):     - Handshake required: false
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5042): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21940a18 added. We now have 1 listener(s)
,I/ActivityManager(  857): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=5182 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,D/BluetoothManagerService(  857): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5042): setBluetoothMacAddress: F8:95:C7:87:85:54
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5042): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5042): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5042): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5042):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5042):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5042):     - Bluetooth MAC address: F8:95:C7:87:85:54
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5042):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5042):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5042):     - Advertise mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5042):     - Advertise TX power level: 3
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5042):     - Scan mode: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5042):     - Scan report delay in milliseconds: 500
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5042): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecbafc4 added. We now have 1 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5042): addListener: New listener added - the number of listeners is now 1
,D/BluetoothAdapterService(214630939)( 2015): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@343881c9
,E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5042): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 5042): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 5042): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 5042): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 5042): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 5042): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 5042): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 5042): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 5042): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 5042): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 5042): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 5042): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 5042): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5042): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5042): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/JX-Cordova( 5042): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5042): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5042): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11dfbead added. We now have 2 listener(s)
,D/BluetoothManagerService(  857): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5042): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5042): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5042): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5042): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f2b15e2 added. We now have 2 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5042): addListener: New listener added - the number of listeners is now 1
D/BluetoothAdapterService(214630939)( 2015): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@343881c9
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5042): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
W/System.err( 5042): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
W/System.err( 5042): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 5042): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 5042): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 5042): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 5042): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 5042): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 5042): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 5042): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 5042): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 5042): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 5042): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5042): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5042): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ResourcesManager( 5182): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager(  857): Process com.google.android.setupwizard (pid 4892) has died
,I/art     (  857): Explicit concurrent mark sweep GC freed 33591(1797KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/34MB, paused 2.322ms total 174.523ms
,I/ActivityManager(  857): Process com.lge.lgdmsclient (pid 4611) has died
,I/iu.SyncManager( 4299): SYNC; picasa accounts
,D/NetworkLogImpl( 4299): Loaded NetworkSpeedPredictor
I/iu.Environment( 4299): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 4299): num queued entries: 0
I/iu.UploadsManager( 4299): num updated entries: 0
I/iu.SyncManager( 4299): NEXT; no task
I/dex2oat ( 5206): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=39 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/ActivityManager(  857): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=5213 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/dex2oat ( 5206): dex2oat took 94.349ms (threads: 4)
,I/Adreno-EGL( 5066): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5066): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5066): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5066): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5066): Remote Branch: 
I/Adreno-EGL( 5066): Local Patches: 
I/Adreno-EGL( 5066): Reconstruct Branch: 
I/Adreno-EGL( 5066): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5066): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5066): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5066): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5066): Remote Branch: 
I/Adreno-EGL( 5066): Local Patches: 
I/Adreno-EGL( 5066): Reconstruct Branch: 
,I/Adreno-EGL( 5066): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5066): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 5066): Build Date: 03/02/15 Mon
I/Adreno-EGL( 5066): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 5066): Remote Branch: 
I/Adreno-EGL( 5066): Local Patches: 
I/Adreno-EGL( 5066): Reconstruct Branch: 
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
I/ActivityManager(  857): Process com.uei.lg.quicksetsdk.lite (pid 4916) has died
I/DigitalAppWidgetProvider( 5213): onReceive: android.intent.action.ALARM_CHANGED
,I/WVCdm   (  271): CdmEngine::CloseSession
I/WVCdm   (  271): L3 Terminate.
D/WeatherAncestor( 2629): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 10:51:8
D/UpdateThreadPoolManager( 2629): 2 : This is isUpdating : false
D/Weather_cast( 2629): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2629): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 10:51:8
D/WeatherService( 2629): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
,W/ActivityManager(  857): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2629): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2629): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2629): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
V/SmsReceiverService( 3148): onStart: #1 mResultCode: -1 = Activity.RESULT_OK
,D/MmsConfig( 3148): isNotAllowedSms: currentUser:0
D/MmsConfig( 3148): isNotAllowedSms: UserHandle.myUserId():0
D/MmsConfig( 3148): isUserMode:false
D/SmsReceiverService( 3148): handleMessage isUserMode:false
V/SmsReceiverService( 3148): handleMessage action: com.android.mms.transaction.SEND_MESSAGE error: 0
I/[LGHome]LGNumberBadgeReceiver( 1875): [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = lge.intent.action.UNREAD_MESSAGES
,D/SmsReceiverService( 3148): [LGE] handleSendMessage Send messages in queue
,I/CheckinRequestBuilder( 4299): Classify the device as Phone.
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1875): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
,I/[LGHome]NumberBadge.LGBroadCastBadge( 1875): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1875): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
I/[LGHome]NumberBadge.LGBroadCastBadge( 1875): [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
I/ActivityManager(  857): Start proc com.android.settings for broadcast com.android.settings/.deviceinfo.UsbSettingsReceiver: pid=5239 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/ActivityManager(  857): Process com.lge.drmservice (pid 4941) has died
,D/libc-netbsd( 4299): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,D/libc-netbsd( 4299): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4299): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4299): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  267): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  267): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  267): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  267): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  267): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  267): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  267): res_queryN name = xxxxx succeed
I/System.out( 4299): propertyValue:false
W/ResourcesManager( 5239): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5239): Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
W/ResourcesManager( 5239): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 5239): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,W/ResourcesManager( 5239): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
D/libc-netbsd( 4299): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4299): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/IndexDatabaseHelper( 5239): Using schema version: 115
,I/IndexDatabaseHelper( 5239): Index is fine
D/libc-netbsd( 4299): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4299): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4299): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4299): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 4299): Sending checkin request (8545 bytes)
,D/UsbSettingsReceiver( 5239): [AUTORUN] onReceive() : action = android.hardware.usb.action.USB_STATE
D/UsbSettingsReceiver( 5239): [AUTORUN] sys.usb.config = ptp_only,adb
,D/UsbSettingsReceiver( 5239): [AUTORUN] sys.usb.state = ptp_only,adb
D/UsbSettingsReceiver( 5239): [AUTORUN] persist.sys.usb.config = ptp_only,adb
D/UsbSettingsReceiver( 5239): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/UsbSettingsReceiver( 5239): [AUTORUN] onReceive() : getDefaultFunction = ptp_only
D/UsbSettingsReceiver( 5239): [AUTORUN] onReceive() : USB_FUNCTION_CDROM_STORAGE = false
,D/UsbSettingsReceiver( 5239): [AUTORUN] onReceive() : mDirectAutorun = true
D/UsbSettingsReceiver( 5239): [AUTORUN] onReceive() : mActivityUsbModeChange = false
D/UsbSettingsReceiver( 5239): [AUTORUN] onReceive() : mActivityFinish = false
D/UsbSettingsReceiver( 5239): [AUTORUN] onReceive() : ===== USB Configured =====
D/UsbSettingsControl( 5239): [AUTORUN] setUsbConnected() : connected=true
D/UsbSettingsReceiver( 5239): [AUTORUN] onReceive() : checkQmicm = ptp_only,adb
D/UsbSettingsReceiver( 5239): [AUTORUN] : topPackageName=com.test.thalitest
D/UsbSettingsReceiver( 5239): [AUTORUN] : topClassName=com.test.thalitest.MainActivity
,D/UsbSettingsReceiver( 5239): [AUTORUN] Not exist com.android.LGSetupWizard
D/UsbSettingsReceiver( 5239): [AUTORUN] setUsbConnect() : mUsbSettingsRun = false
D/UsbSettingsReceiver( 5239): [AUTORUN] startUsbSettings() : deviceProvisioned=1
I/ActivityManager(  857): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5270 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,D/MtpService( 3227): updating state; isCurrentUser=true, mMtpLocked=false
,I/PCSuite ( 5270): [StartReceiver]USB CONNECTED ver UsbManger : ptp_only
I/PCSuite ( 5270): [StartReceiver]isUsbPCSuiteMode : false
,D/PCSuite ( 5270): [StartReceiver][checkEUTStatus] eutStatus = 
D/PCSuite ( 5270): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 5270): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/WeatherAncestor( 2629): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 10:51:9
D/UpdateThreadPoolManager( 2629): 2 : This is isUpdating : false
D/WeatherAncestor( 2629): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 10:51:9
,D/WeatherService( 2629): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
W/ActivityManager(  857): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2629): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2629): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2629): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2629): 2 : requestRefreshAppWidget, isUpdateStart : false
V/UserPresentBroadcastReceiver( 1731): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
D/UpdateThreadPoolManager( 2629): 2 : This is isUpdating : false
D/WeatherService( 2629): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2629): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2629): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2629): 2 : Fixed theme : optimus
,D/WeatherReflect( 2629): 2 : Map key string is -2
D/lim     ( 2629): 2 : time = 10:51
I/WeatherReflect( 2629): Model Name : LG-D722
D/WeatherTheme( 2629): 2 : exactly same view!
D/WeatherTheme( 2629): 2 : widgetId = 2 : widgetSize = 1 : Do not refresh any widget.
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,I/ActivityManager(  857): Process com.google.android.apps.magazines (pid 5023) has died
,I/ActivityManager(  857): Start proc com.lge.qremote for broadcast com.lge.qremote/.LgIrMdmPolicyReceiver: pid=5291 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
W/ActivityManager(  857): getTasks: caller 10074 does not hold GET_TASKS; limiting output
,D/Weather.Utils( 2629): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2629): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2629): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
,W/ResourcesManager( 5291): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,I/CheckinRequestBuilder( 4299): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4299): Failed to find provider info for com.google.android.wearable.settings
,D/BluetoothManagerService(  857): Message: 20
D/BluetoothManagerService(  857): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@80d6092:true
,D/BluetoothAdapterService(214630939)( 2015): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@343881c9
D/BluetoothAdapterService(214630939)( 2015): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@343881c9
V/LGMDMManager( 5291): Create singleton instance
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/art     ( 4299): Explicit concurrent mark sweep GC freed 6897(314KB) AllocSpace objects, 2(32KB) LOS objects, 25% free, 11MB/15MB, paused 772us total 102.850ms
,I/DigitalAppWidgetProvider( 5213): onReceive: android.intent.action.ALARM_CHANGED
,D/WeatherAncestor( 2629): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 10:51:9
D/UpdateThreadPoolManager( 2629): 2 : This is isUpdating : false
,V/AlarmManager(  857): RTC_WAKEUP set : Alarm{3dd5a9bf type 0 when 1457344269854 com.google.android.googlequicksearchbox} when 1457344269854
D/Weather_cast( 2629): 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
D/WeatherAncestor( 2629): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 10:51:9
D/WeatherService( 2629): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
W/ActivityManager(  857): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2629): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2629): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2629): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/AlertReceiver( 3870): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 3870): 0 Action = android.intent.action.PROVIDER_CHANGED
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{21799bd5 type 2 when 78820 android} when 78820
,E/AgendaWidgetManager( 3870): [updateWidgets] 
D/MonthWidgetProvider( 3870): [onReceive]
D/CalendarWidgetProvider( 3870): [onReceive]
D/CalendarWidgetProvider( 3870): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 3870): [onCreate] mContext.getPackageName() = com.android.calendar
,D/WeekWidgetProvider( 3870): [onReceive]
D/CalendarWidgetProvider( 3870): [onReceive]
D/CalendarWidgetProvider( 3870): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 3870): [onCreate] mContext.getPackageName() = com.android.calendar
I/CheckinRequestBuilder( 4299): Classify the device as Phone.
,I/[SystemUI]SafeModeBroadcastReceiver( 1373): onReceive = com.lge.statusbar.bootcompleted
D/CalendarWeatherReceiver( 3870): Get action=com.lge.calendar.action.WEATHER_SERVICE_START
,I/CheckinTask( 4299): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/ActivityManager(  857): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.MediaScanReceiver: pid=5330 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
,I/CheckinService( 4299): Checking schedule, now: 1457344270008 next: 1457871518965
I/CheckinService( 4299): active receiver: disabled
,D/CheckinService( 4299): Recording last checkin time for package unspecified as 1457344270038
,E/MediaScanReceiver( 5330): media scanning start or checking
,W/MainApplication( 5330): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/ActivityManager(  857): Start proc com.google.android.music:main for broadcast com.google.android.music/.store.MediaStoreImportService$Receiver: pid=5353 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  857): Killing 3668:com.android.defcontainer/u0a4 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10004/pid_3668/cgroup.procs: No such file or directory
,I/MusicStore( 5353): Database version: 120
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5353): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5353): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.music/files/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 5353): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.music/files
W/ResourcesManager( 5353): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5353): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5353): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 5353): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 5353): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1b13eba8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 5353): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 5353): GMSCore installation verified
,I/ConfigStore( 5353): Config Database version: 1
,I/MediaRouter( 5353): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,D/ToneMappingReceiver( 5213): Enter doAlarmRingToneUriMapping()
I/NetworkMonitor( 5353): type=WIFI subType= reason=null isConnected=true
,D/ToneMappingReceiver( 5213): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5213): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
,D/CommonUtil( 5213): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5213): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5213): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5213): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5213): Alarm Success count is 0
D/ToneMappingReceiver( 5213): Timer Success count is 0
I/MediaScannerReceiver( 3870): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///system/media flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///system/media
,I/InitNotificationRingtoneService( 3870): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3870): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
E/MediaScanReceiver( 5330): media scanning finished
,I/NetworkMonitor( 5353): type=WIFI subType= reason=null isConnected=true
,I/AlertUtils( 3870): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/com.lge.bnr.receiver.MediaScanReceiver( 5330): android.intent.action.MEDIA_SCANNER_FINISHED
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,I/GHttpClientFactory( 5353): Using our fixed implementation of GMSCore's GoogleHttpClient
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
I/GoogleURLConnFactory( 5353): Using platform SSLCertificateSocketFactory
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,E/MediaScanReceiver( 5330): media scanning start or checking
,I/NotificationManager( 5353): com.google.android.music: cancel(1061) by com.google.android.music
,D/ToneMappingReceiver( 5213): Enter doAlarmRingToneUriMapping()
D/ToneMappingReceiver( 5213): do ALARM RingToneUriMapping() -> first find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/CommonUtil( 5213): Enter getMatchedBackupTone() enter URI value is On, parentInfo : ALARM
D/CommonUtil( 5213): getFinededDefaultTone() -> backup ringtone value : null
D/CommonUtil( 5213): Exit getMatchedBackupTone() value is null
D/ToneMappingReceiver( 5213): do ALARM RingToneUriMapping() -> second find stap, Media infor : MediaInfoHolder [mediaLocation=NO_WHERE, mediaTitle=N/A, mediaURI=null, mediaIdNum=-1, fileSizeValue=0, dateModifiedValue=0, filePath=null]
D/ToneMappingReceiver( 5213): Enter doAlarmRingToneUriMapping(), return value is 0
D/ToneMappingReceiver( 5213): Alarm Success count is 0
D/ToneMappingReceiver( 5213): Timer Success count is 0
I/ActivityManager(  857): Killing 4967:com.google.android.talk/u0a61 (adj 15): empty #11
,I/art     ( 3227): Explicit concurrent mark sweep GC freed 17027(1076KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/10MB, paused 438us total 54.168ms
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3870): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
W/libprocessgroup(  857): failed to open /acct/uid_10061/pid_4967/cgroup.procs: No such file or directory
,I/MediaScannerReceiver( 3870): Calendar.onReceive: a=android.intent.action.MEDIA_SCANNER_FINISHED Intent { act=android.intent.action.MEDIA_SCANNER_FINISHED dat=file:///storage/emulated/0 flg=0x10 cmp=com.android.calendar/.alerts.MediaScannerReceiver }, mData=file:///storage/emulated/0
I/AlertUtils( 3870): set default noti to content://media/internal/audio/media/38
I/InitNotificationRingtoneService( 3870): End InitializeAlertRingtoneService.onHandleIntent
I/InitNotificationRingtoneService( 3870): Start InitializeAlertRingtoneService.onHandleIntent
I/AlertUtils( 3870): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
E/MediaScanReceiver( 5330): media scanning finished
I/com.lge.bnr.receiver.MediaScanReceiver( 5330): android.intent.action.MEDIA_SCANNER_FINISHED
,I/art     ( 5353): CheckpointMarkThreadRoots callback created = 0xb042d380
,I/art     ( 5353): CheckpointMarkThreadRoots callback created = 0xb042d360
,I/art     (  857): Explicit concurrent mark sweep GC freed 18084(981KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 22MB/34MB, paused 2.290ms total 150.911ms
,I/ActivityManager(  857): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=5411 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/AlertUtils( 3870): [getCalendarNotiSoundURIFromCursor] getCount()= 21
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,I/AlertUtils( 3870): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 3870): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 3870): set default noti to content://media/internal/audio/media/38
,I/InitNotificationRingtoneService( 3870): End InitializeAlertRingtoneService.onHandleIntent
W/ResourcesManager( 5411): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/MediaStoreImporter( 5353): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,D/CalendarProvider2( 5411): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1230ecd2
,D/CalendarProvider2( 5411): [getOrCreateCalendarAlarmManager]
,I/CalendarProvider2( 5411): Created com.android.providers.calendar.CalendarAlarmManager@1c0014ff(com.android.providers.calendar.CalendarProvider2@1230ecd2)
D/CalendarProviderBroadcastReceiver( 5411): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 5411): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 5411): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 5411): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 5411): [getOrCreateCalendarAlarmManager]
D/WearableService( 1731): callingUid 10006, callindPid: 1731
,D/LocationInitializer( 4299): Restart initialization of location
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/MDM     ( 1731): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
D/CalendarProvider2( 5411): [IntentService] Release Lock
D/CalendarProvider2( 5411): CalendarProviderIntentService.onDestroy()
I/ActivityManager(  857): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=5437 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
,I/chromium( 5042): [INFO:CONSOLE(1185)] "deviceready has not fired after 5 seconds.", source: file:///android_asset/www/cordova.js (1185)
I/chromium( 5042): [INFO:CONSOLE(1178)] "Channel not fired: onJXcoreReady", source: file:///android_asset/www/cordova.js (1178)
,W/IcingInternalCorpora( 4299): getNumBytesRead when not calculated.
,W/ActivityManager(  857): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 5437): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 5437): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  857): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   ( 5437): Error finding the version of the Email provider.....
E/Gmail   ( 5437): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 5437): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 5437): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 5437): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 5437): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 5437): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 5437): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 5437): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/EmailMigration( 5437): We do not support migrating this version of the Email provider.
I/Gmail   ( 5437): getAccountsCursor
W/ActivityManager(  857): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5437): Observing account changes for notifications
W/ActivityManager(  857): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 1731): No location to return for getLastLocation()
,W/FusedLocationProvider( 1731): location=null
V/DownloadManager( 3227): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='190' OR status='192' OR status='193' OR status='194' OR status='195' OR status='196' OR status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3227): created cursor android.database.sqlite.SQLiteCursor@ecbafc4 on behalf of 4299
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ActivityManager(  857): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=5498 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/Gmail   ( 5437): notifyAccountChanged
,I/Gmail   ( 5437): getAccountsCursor
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 5437): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 5437): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 5437): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 5437): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/DownloadManager( 3227): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is (status>='400' AND status<'600') AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3227): created cursor android.database.sqlite.SQLiteCursor@11dfbead on behalf of 4299
V/DownloadManager( 3227): starting query, database is not null; projection[0] is _id; projection[1] is _data AS local_filename; projection[2] is mediaprovider_uri; projection[3] is destination; projection[4] is title; projection[5] is description; projection[6] is uri; projection[7] is status; projection[8] is hint; projection[9] is mimetype AS media_type; projection[10] is total_bytes AS total_size; projection[11] is lastmod AS last_modified_timestamp; projection[12] is current_bytes AS bytes_so_far; projection[13] is allow_write; projection[14] is 'placeholder' AS local_uri; projection[15] is 'placeholder' AS reason; projection[16] is drm_status; projection[17] is type_sort_index; selection is status='200' AND deleted != '1'; selectionArgs is null; sort is lastmod DESC.
,V/DownloadManager( 3227): created cursor android.database.sqlite.SQLiteCursor@2f2b15e2 on behalf of 4299
I/art     ( 4045): Explicit concurrent mark sweep GC freed 3187(126KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 369us total 30.224ms
,D/PhoneMonitor( 5498): Register our PhoneStateListener
,I/ActivityManager(  857): Killing 5161:com.android.chrome/u0a48 (adj 15): empty #11
,D/PhoneMonitor( 5498): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 5498): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 5498): [parse] Load xml
V/TelephonyAutoProfiling( 5498): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 5498): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 5498): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/art     (  857): Explicit concurrent mark sweep GC freed 10922(499KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.782ms total 155.256ms
I/art     (  857): WaitForGcToComplete blocked for 109.348ms for cause HeapTrim
,I/ActivityManager(  857): Process com.google.android.apps.plus (pid 5182) has died
,W/libprocessgroup(  857): failed to open /acct/uid_10048/pid_5161/cgroup.procs: No such file or directory
D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
I/CheckinService( 4299): Checkin interval check for package: unspecified last checkin: 1457344270038 min interval config: 0 actual interval: 2749
,I/CheckinService( 4299): Checking schedule, now: 1457344272798 next: 1457344299965
I/CheckinService( 4299): active receiver: disabled
I/Gmail   ( 5437): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  857): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=5523 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 412us total 25.490ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 343us total 25.568ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 333us total 27.481ms
,W/ResourcesManager( 5523): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Babel_SMS( 5523): MmsConfig: mnc/mcc: 0/0
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
D/SensorManager( 5523): found sensor: LGE Gravity Sensor, handle=29
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
,W/Settings( 5523): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 5523): startup - clean
I/Babel   ( 5523): deleted: false for 0
,I/art     ( 5523): CheckpointMarkThreadRoots callback created = 0xb042d850
I/art     ( 5523): CheckpointMarkThreadRoots callback created = 0xb042d840
,W/AudioCapabilities( 5523): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 5523): Unsupported mime audio/adpcm
W/AudioCapabilities( 5523): Unsupported mime audio/g726
W/AudioCapabilities( 5523): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 5523): Unsupported mime audio/wma-voice
W/VideoCapabilities( 5523): Unsupported mime video/mjpg
,W/VideoCapabilities( 5523): Unsupported mime video/theora
W/AudioCapabilities( 5523): Unsupported mime audio/evrc
,W/AudioCapabilities( 5523): Unsupported mime audio/qcelp
W/VideoCapabilities( 5523): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 5523): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 5523): Unsupported mime audio/qcelp
W/AudioCapabilities( 5523): Unsupported mime audio/evrc
W/VideoCapabilities( 5523): Unsupported mime video/mp4v-esdp
,I/VideoCapabilities( 5523): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 5523): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5523): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 5523): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 5523): Unrecognized profile 2130706433 for video/avc
I/vclib   ( 5523): onServiceConnected
,W/Babel   ( 5523): Attempted to change video mute state without an active call.
W/ResourcesManager( 5523): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5523): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 5523): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  857): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5564 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/System  ( 5523): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5523): Installed default security provider GmsCore_OpenSSL
I/AudioManager( 5291): getMode name:com.lge.qremote
,I/NotificationManager( 5523): com.google.android.talk: cancel(10436) by com.google.android.talk
I/AudioManager( 5291): getMode name:com.lge.qremote
,I/AudioManager( 5291): getMode name:com.lge.qremote
,I/AudioManager( 5291): getMode name:com.lge.qremote
,I/AudioManager( 5291): getMode name:com.lge.qremote
D/UEI.SmartControl( 5564): Quickset Services start...
I/UEI.SmartControl( 5564): Manufacture = LGE
D/UEI.SmartControl( 5564): File observer start...
,E/UEI.SmartControl( 5564): IR Port is disabled: false
D/UEI.SmartControl( 5564): Starting file observer...
D/UEI.SmartControl( 5564): Extracting JNI libs...
D/UEI.SmartControl( 5564): --- this system supports 32-bit or 64-bit only
I/ActivityManager(  857): Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=5584 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,W/ResourcesManager( 5584): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5584): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5584): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
D/UEI.SmartControl( 5564): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
D/UEI.SmartControl( 5564): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5564): --- Extracting JNI libs: libqs_armeabi-v7a.zip
,I/UEI.SmartControl( 5564): --- Selecting new region: 2
,I/UEI.SmartControl( 5564): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5564): Platform has CIR...
D/UEI.SmartControl( 5564): NO CIR support, need to check package...
I/UEI.SmartControl( 5564): Model: LG-D722 uses JNI
I/LGEmail ( 5584): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
D/UEI.SmartControl( 5564): QS Service created
D/LGEmail ( 5584): user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,E/UEI.SmartControl( 5564): QS start get config
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/UEI.SmartControl( 5564): Loading JNI Libs...
D/UEI.SmartControl( 5564):  configuring local db...
,I/PackageChangeReceiver( 5584): intent action : android.intent.action.PACKAGE_ADDED (at PackageChangeReceiver.java onReceive 20)
,I/ActivityManager(  857): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=5611 uid=10009 gids={50009, 9997, 3003} abi=armeabi-v7a
,I/ActivityManager(  857): Killing 5239:com.android.settings/1000 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_1000/pid_5239/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 5564):  ---- Has DB8: true
,I/ActivityManager(  857): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5631 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
D/UEI.SmartControl( 5564): QS start statue = true Error code = 0
D/UEI.SmartControl( 5564): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5564): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
D/UEI.SmartControl( 5564): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5564): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5564): IrrcClient ++ 
D/irrcClient( 5564): getIrrcService ++ 
,D/irrcClient( 5564): getIrrcService -- 
D/irrcClient( 5564): IrrcClient -- 
W/irrc_jni( 5564): IRRCPlayer_nativeInit -- 
I/ActivityManager(  857): Killing 5270:com.lge.sync/1000 (adj 15): empty #11
D/UEI.SmartControl( 5564): Services init done
I/UEI.SmartControl( 5564): Device manager: loading config....
,D/UEI.SmartControl( 5564): Config is loaded...
D/UEI.SmartControl( 5564):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5564): Notify AllClients services are ready: 0
,W/libprocessgroup(  857): failed to open /acct/uid_1000/pid_5270/cgroup.procs: No such file or directory
D/UEI.SmartControl( 5564): QS Service init finished
,D/UEI.SmartControl( 5564): QS Service version name: 0.1.73
D/UEI.SmartControl( 5564): QS Service version code: 1073
D/UEI.SmartControl( 5564): Service requested: Control
D/UEI.SmartControl( 5564): Internal service binding...
,D/UEI.SmartControl( 5564): -----IControl: 11
D/UEI.SmartControl( 5564): Caller: com.lge.qremote
D/UEI.SmartControl( 5564): ------------ IControl registerCallback...
I/UEI.SmartControl( 5564): Registering callback...
D/UEI.SmartControl( 5564): -----IControl: 19
D/UEI.SmartControl( 5564): Caller: com.lge.qremote
I/UEI.SmartControl( 5564): Registering Services Ready callback...
I/UEI.SmartControl( 5564): Notify client services are ready...
D/UEI.SmartControl( 5564): -----IControl: 8
,D/UEI.SmartControl( 5564): Caller: com.lge.qremote
I/ActivityManager(  857): Killing 5330:com.lge.bnr/1000 (adj 15): empty #11
D/AlertService( 3870): Beginning updateAlertNotification
,I/ActivityManager(  857): Killing 5213:com.lge.clock/u0a10 (adj 15): empty #12
,W/libprocessgroup(  857): failed to open /acct/uid_1000/pid_5330/cgroup.procs: No such file or directory
,I/AppUp4:AppBoxCP( 5631): onCreate
W/libprocessgroup(  857): failed to open /acct/uid_10010/pid_5213/cgroup.procs: No such file or directory
W/AppUp4:DB( 5631):  [AppBoxDatabaseHelper] construct
D/AlertService( 3870): No fired or scheduled alerts
I/NotificationManager( 3870): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(5) by com.android.calendar
,I/NotificationManager( 3870): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(8) by com.android.calendar
I/AppUp4:DB( 5631):  setFingerPrint start
I/NotificationManager( 3870): com.android.calendar: cancel(9) by com.android.calendar
I/AppUp4:DB( 5631):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/NotificationManager( 3870): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(13) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 3870): com.android.calendar: cancel(19) by com.android.calendar
,I/NotificationManager( 3870): com.android.calendar: cancel(20) by com.android.calendar
I/AppUp4:DB( 5631):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 5631):  SDK version = 0
I/AppUp4:DB( 5631):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5631): AppBoxApplication onCreate()
D/AlertService( 3870): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
D/AlarmScheduler( 3870): No events found starting within 1 week.
,I/ActivityManager(  857): Killing 5353:com.google.android.music:main/u0a81 (adj 15): empty #11
I/NotificationManager( 1933): com.google.android.googlequicksearchbox: cancel(10436) by com.google.android.googlequicksearchbox
W/libprocessgroup(  857): failed to open /acct/uid_10081/pid_5353/cgroup.procs: No such file or directory
,I/ActivityManager(  857): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5660 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,W/ResourcesManager( 5660): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5660): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 5660): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
I/AppConfig( 5660): Total System Memory = 906309632
,I/GalleryUtils( 5660): Application Heap = 96 MB
I/AppConfig( 5660): App Tier : NOT_DEF
D/SystemHelper( 5660): region [EU], country [EU], operator [OPEN], sub-operator []
,I/ActivityManager(  857): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5679 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  857): Killing 5411:com.android.providers.calendar/u0a14 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10014/pid_5411/cgroup.procs: No such file or directory
,W/ResourcesManager( 5679): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5679): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 5679): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 5679): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 5679): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 5679): BUILD Country: EU
I/SystemConfig( 5679): BUILD Operator: OPEN
,D/InitAlarmsService( 3870): Clearing and rescheduling alarms.
I/ActivityManager(  857): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=5699 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 5699): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 5699): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1230ecd2
,I/ActivityManager(  857): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=5718 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  857): Killing 5437:com.google.android.gm/u0a53 (adj 15): empty #11
I/CheckinService( 4299): Done disabling old GoogleServicesFramework version
,D/CalendarProvider2( 5699): [getOrCreateCalendarAlarmManager]
W/libprocessgroup(  857): failed to open /acct/uid_10053/pid_5437/cgroup.procs: No such file or directory
I/CalendarProvider2( 5699): Created com.android.providers.calendar.CalendarAlarmManager@1c0014ff(com.android.providers.calendar.CalendarProvider2@1230ecd2)
D/CalendarProvider2( 5699): Scheduling check of next Alarm
,I/SystemConfig( 5679): pm.hasSystemFeature(com.lge.ims.rcs) = false
D/CalendarProvider2( 5699): SCHEDULE_ALARM_REMOVE
I/SystemConfig( 5679): existFile = false
I/SystemConfig( 5679): canReadFile = false
I/SystemConfig( 5679): systemFeature RCS result false
D/SystemConfig( 5679): refreshRcsSupport() :false
I/ActivityManager(  857): Killing 3870:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10013/pid_3870/cgroup.procs: No such file or directory
,I/LockScreenSettings( 5718): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/LockScreenSettings( 5718): New app installed broadcast received ..
,I/LockScreenSettings( 5718): Number of installed packages  1
I/ActivityManager(  857): Start proc com.lge.eula for broadcast com.lge.eula/.service.LicenseProviderUpdateObserver: pid=5737 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,I/ActivityManager(  857): Killing 5498:com.google.android.setupwizard/u0a38 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10038/pid_5498/cgroup.procs: No such file or directory
D/EulaProviderUpdateObserver( 5737): action : android.intent.action.PACKAGE_ADDED
D/EulaProviderUpdateObserver( 5737): uri : package:com.test.thalitest
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  857): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=5754 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
I/ActivityManager(  857): Killing 4045:com.google.process.gapps/u0a6 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10006/pid_4045/cgroup.procs: No such file or directory
,D/[BNRAppListMgrReceiver]( 5754): android.intent.action.PACKAGE_ADDED : com.test.thalitest
W/MainApplication( 5754): onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/ActivityManager(  857): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=5771 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  857): Killing 5066:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 333us total 24.168ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 20.996ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 269us total 25.218ms
W/libprocessgroup(  857): failed to open /acct/uid_10006/pid_5066/cgroup.procs: No such file or directory
I/ActivityManager(  857): Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=5788 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
I/GservicesProvider( 5788): Gservices pushing to system: true; secure/global: true
,I/GoogleHttpClient( 5788): GMS http client unavailable, use old client
,I/CalendarProvider2( 5699): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
W/ContentResolver( 5699): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,I/ActivityManager(  857): Killing 5564:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
W/System.err( 5291): android.os.DeadObjectException
,W/System.err( 5291): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5291): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5291): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
W/System.err( 5291): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5291): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5291): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5291): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5291): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5291): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5291): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5291): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5291): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5291): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5291): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5291): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5291): android.os.DeadObjectException
W/System.err( 5291): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5291): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5291): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5291): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5291): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5291): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5291): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5291): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5291): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5291): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5291): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5291): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5291): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5291): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5291): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
W/libprocessgroup(  857): failed to open /acct/uid_10089/pid_5564/cgroup.procs: No such file or directory
W/ActivityManager(  857): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
,I/ActivityManager(  857): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=5807 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/GoogleHttpClient( 5788): GMS http client unavailable, use old client
,I/ActivityManager(  857): Killing 5291:com.lge.qremote/u0a106 (adj 15): empty #11
,D/UEI.SmartControl( 5807): Quickset Services start...
I/UEI.SmartControl( 5807): Manufacture = LGE
D/UEI.SmartControl( 5807): File observer start...
E/UEI.SmartControl( 5807): IR Port is disabled: false
D/UEI.SmartControl( 5807): Starting file observer...
D/UEI.SmartControl( 5807): Extracting JNI libs...
D/UEI.SmartControl( 5807): --- this system supports 32-bit or 64-bit only
,D/UEI.SmartControl( 5807): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 5807): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 5807): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 5807): --- Selecting new region: 2
,I/UEI.SmartControl( 5807): -- Running on KitKat(19) and above! JNI will be used.
D/UEI.SmartControl( 5807): Platform has CIR...
D/UEI.SmartControl( 5807): NO CIR support, need to check package...
I/UEI.SmartControl( 5807): Model: LG-D722 uses JNI
D/UEI.SmartControl( 5807): QS Service created
W/libprocessgroup(  857): failed to open /acct/uid_10106/pid_5291/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,E/UEI.SmartControl( 5807): QS start get config
,D/Finsky  ( 5771): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/UEI.SmartControl( 5807): Loading JNI Libs...
,D/UEI.SmartControl( 5807):  configuring local db...
,D/Finsky  ( 5771): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 5771): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 5771): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/NotificationManager( 5771): com.android.vending: cancel(-1050172287) by com.android.vending
,D/UEI.SmartControl( 5807):  ---- Has DB8: true
V/DownloadManager( 3227): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; projection[27] is type_sort_index; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 3227): created cursor android.database.sqlite.SQLiteCursor@4cf5d73 on behalf of 5771
D/UEI.SmartControl( 5807): QS start statue = true Error code = 0
,D/UEI.SmartControl( 5807): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5807): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5807): IRRCDataComm has AudioManager!!!!.
I/NotificationManager( 5771): com.android.vending: cancel(1003285959) by com.android.vending
,W/irrc_jni( 5807): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5807): IrrcClient ++ 
D/irrcClient( 5807): getIrrcService ++ 
D/irrcClient( 5807): getIrrcService -- 
D/irrcClient( 5807): IrrcClient -- 
W/irrc_jni( 5807): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5807): Services init done
D/UEI.SmartControl( 5807): QS Service init finished
,D/UEI.SmartControl( 5807): QS Service version name: 0.1.73
D/UEI.SmartControl( 5807): QS Service version code: 1073
D/UEI.SmartControl( 5807): Service requested: Control
I/UEI.SmartControl( 5807): Device manager: loading config....
D/UEI.SmartControl( 5807): Config is loaded...
D/Ads     ( 5771): Skipping gmscore version check
,D/UEI.SmartControl( 5807):  ----- QS SDK is ready!!!
D/UEI.SmartControl( 5807): Request IControl service: devices are loaded...
,I/UEI.SmartControl( 5807): Notify AllClients services are ready: 0
I/ActivityManager(  857): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=5871 uid=10058 gids={50058, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,D/UEI.SmartControl( 5807): Service.onUnbind: IControl
D/UEI.SmartControl( 5807): Service.onDestroy
D/UEI.SmartControl( 5807): Shutdown IRRCPlayer... 
W/irrc_jni( 5807): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 5807): ~IrrcClient ++ 
D/irrcClient( 5807): ~IrrcClient -- 
W/irrc_jni( 5807): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 5807): Blaster closed
D/UEI.SmartControl( 5807): Blaster closed
D/UEI.SmartControl( 5807): Shut down QS...
D/UEI.SmartControl( 5807): Stopped file observer...
D/Finsky  ( 5771): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 5771): [1] Libraries$2.run: Finished loading 1 libraries.
,I/UEI.SmartControl( 5807): QS lib stop result = true
D/UEI.SmartControl( 5807): QS shutdown complete
D/UEI.SmartControl( 5807): QS Service created
D/Finsky  ( 5771): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/UEI.SmartControl( 5807): QS start get config
,D/Finsky  ( 5771): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
I/ActivityManager(  857): Killing 5584:com.lge.email/u0a21 (adj 15): empty #11
D/UEI.SmartControl( 5807):  configuring local db...
,W/libprocessgroup(  857): failed to open /acct/uid_10021/pid_5584/cgroup.procs: No such file or directory
,D/Finsky  ( 5771): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/ActivityManager(  857): Killing 5611:com.google.android.partnersetup/u0a9 (adj 15): empty #11
,D/UEI.SmartControl( 5807):  ---- Has DB8: true
,D/UEI.SmartControl( 5807): QS start statue = true Error code = 0
D/UEI.SmartControl( 5807): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 5807): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 5807): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 5807): IRRCPlayer_nativeInit ++ 
D/irrcClient( 5807): IrrcClient ++ 
D/irrcClient( 5807): getIrrcService ++ 
D/irrcClient( 5807): getIrrcService -- 
D/irrcClient( 5807): IrrcClient -- 
W/irrc_jni( 5807): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 5807): Services init done
I/UEI.SmartControl( 5807): Device manager: loading config....
D/UEI.SmartControl( 5807): Config is loaded...
W/libprocessgroup(  857): failed to open /acct/uid_10009/pid_5611/cgroup.procs: No such file or directory
,D/UEI.SmartControl( 5807): QS Service init finished
D/UEI.SmartControl( 5807): QS Service version name: 0.1.73
D/UEI.SmartControl( 5807): QS Service version code: 1073
D/UEI.SmartControl( 5807): Service requested: Control
D/UEI.SmartControl( 5807):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 5807): Notify AllClients services are ready: 0
,I/art     (  857): Explicit concurrent mark sweep GC freed 23505(1126KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 22MB/34MB, paused 2.914ms total 143.059ms
,I/ActivityManager(  857): Killing 5631:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10011/pid_5631/cgroup.procs: No such file or directory
,E/ActivityThread( 5807): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@ccb021b that was originally bound here
E/ActivityThread( 5807): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@ccb021b that was originally bound here
E/ActivityThread( 5807): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 5807): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 5807): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 5807): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 5807): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 5807): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 5807): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 5807): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 5807): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 5807): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 5807): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 5807): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 5807): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 5807): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 5807): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 5807): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 5807): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 5807): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 5807): Internal service binding...
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/GAv4    ( 5871): Google Analytics 7.8.84 is starting up. To enable debug logging on a device run:
I/GAv4    ( 5871):   adb shell setprop log.tag.GAv4 DEBUG
I/GAv4    ( 5871):   adb logcat -s GAv4
,W/GAv4    ( 5871): AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5871): CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,W/GAv4    ( 5871): AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
W/AnalyticsTrackerProxyImpl( 5871): Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.283.23.34
,E/VoldCmdListener(  244): [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
E/Vold    (  244): Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.docs/cache/
W/Vold    (  244): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 5871): Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.docs/cache
I/ActivityManager(  857): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=5917 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager(  857): Killing 5660:com.android.gallery3d/u0a23 (adj 15): empty #11
I/art     ( 5871): CheckpointMarkThreadRoots callback created = 0xaaedc280
,W/ResourcesManager( 5871): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5871): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/libprocessgroup(  857): failed to open /acct/uid_10023/pid_5660/cgroup.procs: No such file or directory
I/art     ( 5871): CheckpointMarkThreadRoots callback created = 0xb050ca00
,W/ResourcesManager( 5917): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/NotificationManager( 5871): com.google.android.apps.docs: cancel(10436) by com.google.android.apps.docs
V/JNIHelp ( 5871): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/ActivityManager(  857): Killing 5523:com.google.android.talk/u0a61 (adj 15): empty #11
,W/System  ( 5871): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/data/app/com.google.android.apps.docs-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.apps.docs-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 5871): Installed default security provider GmsCore_OpenSSL
W/libprocessgroup(  857): failed to open /acct/uid_10061/pid_5523/cgroup.procs: No such file or directory
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
I/ActivityManager(  857): Killing 5679:com.android.contacts/u0a18 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10018/pid_5679/cgroup.procs: No such file or directory
,D/ChimeraCfgMgr( 4299): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/PackageBroadcastService( 4299): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
D/ChimeraModuleLdr( 4299): Loading module APK com.google.android.play.games
I/UpdateIcingCorporaServi( 1933): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,D/ChimeraCfgMgr( 4299): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4299): Module APK com.google.android.play.games already loaded
,D/ChimeraCfgMgr( 4299): Loading module com.google.android.gms.gass from APK com.google.android.gms
,I/Icing   ( 4299): Storage manager: low false usage 1.41MB avail 2.37GB capacity 4.06GB
D/AsyncTaskServiceImpl( 4299): Submit a task: k
,I/PeopleDatabaseHelper( 4299): cleanUpNonGplusAccounts done.
D/ChimeraCfgMgr( 4299): Loading module com.google.android.gms.gass from APK com.google.android.gms
D/ChimeraCfgMgr( 4299): Loading module com.google.android.gms.vision from APK com.google.android.gms
,D/k       ( 4299): Processing package: com.test.thalitest
,D/GassUtils( 4299): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 4299): Found info for package com.test.thalitest in db.
,I/ActivityManager(  857): Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=5988 uid=10106 gids={50106, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,W/BaseAppContext( 4299): Using Auth Proxy for data requests.
W/BaseAppContext( 4299): Using Auth Proxy for data requests.
,W/BaseAppContext( 4299): Using Auth Proxy for data requests.
W/BaseAppContext( 4299): Using Auth Proxy for data requests.
,W/BaseAppContext( 4299): Using Auth Proxy for data requests.
I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,W/ResourcesManager( 5988): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
I/InputReader(  857): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
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
,D/administrator(  857): Handling package changes for user 0
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,D/BluetoothManagerService(  857): Message: 20
D/BluetoothManagerService(  857): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3cf8aea:true
,D/BluetoothAdapterService(214630939)( 2015): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@343881c9
D/BluetoothAdapterService(214630939)( 2015): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@343881c9
,I/NotificationService(  857): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  857): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService(  857): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService(  857): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  857): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  857): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@39b51533
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/LGMDMManager( 5988): Create singleton instance
,W/ResourcesManager(  857): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/AudioManager( 5988): getMode name:com.lge.qremote
,D/UEI.SmartControl( 5807): -----IControl: 11
D/UEI.SmartControl( 5807): File observer start...
,E/UEI.SmartControl( 5807): IR Port is disabled: false
D/UEI.SmartControl( 5807): Starting file observer...
D/UEI.SmartControl( 5807): Caller: com.lge.qremote
D/UEI.SmartControl( 5807): ------------ IControl registerCallback...
I/UEI.SmartControl( 5807): Registering callback...
D/UEI.SmartControl( 5807): -----IControl: 19
D/UEI.SmartControl( 5807): Caller: com.lge.qremote
I/UEI.SmartControl( 5807): Registering Services Ready callback...
I/UEI.SmartControl( 5807): Notify client services are ready...
D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
D/UEI.SmartControl( 5807): -----IControl: 8
D/UEI.SmartControl( 5807): Caller: com.lge.qremote
D/WearableService( 1731): callingUid 10006, callindPid: 1731
,D/LocationInitializer( 4299): Restart initialization of location
E/MDM     ( 1731): [85] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
W/ResourceType(  857): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,I/ActivityManager(  857): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6022 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
I/Icing   ( 4299): updateResources: need to parse f{com.google.android.gms}
,I/GCoreNlp( 1731): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  857): applying state to connected service
,W/ResourcesManager( 6022): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/Icing   ( 4299): Internal init done: storage state 0
,I/Icing   ( 4299): Post-init done
,D/ChimeraCfgMgr( 4299): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 4299): Module APK com.google.android.play.games already loaded
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{1f8b2ab9 type 2 when 89957 com.android.providers.calendar} when 89957
,W/SQLiteConnectionPool( 4299): A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/art     ( 1731): Explicit concurrent mark sweep GC freed 33448(2MB) AllocSpace objects, 29(464KB) LOS objects, 40% free, 13MB/22MB, paused 5.029ms total 122.783ms
I/UpdateIcingCorporaServi( 1933): UpdateCorporaTask done [took 1672 ms] updated apps [took 1672 ms] 
,V/AlarmManager(  857): RTC_WAKEUP set : Alarm{36b5e65f type 0 when 1457344281210 com.android.vending} when 1457344281210
,D/Finsky  ( 5771): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Babel_SMS( 6022): MmsConfig: mnc/mcc: 0/0
,I/Babel_SMS( 6022): MmsConfig.loadMmsSettings
I/Babel_SMS( 6022): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6022): MmsConfig.loadFromDatabase
I/NotificationManager(  857): android: cancelAsUser(2) by android
,E/Babel_SMS( 6022): canonicalizeMccMnc: invalid mccmnc 
,I/Babel_SMS( 6022): MmsConfig.loadFromResources
E/Babel_SMS( 6022): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel_SMS( 6022): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
D/libc-netbsd( 5771): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5771): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 5771): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5771): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/SensorManager( 6022): found sensor: LGE Accelerometer Sensor, handle=0
E/BandwidthController(  267): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  267): App 10036 tries DNS query. Accept family:0 protocol:0
D/SensorManager( 6022): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6022): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/libc-netbsd(  267): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/SensorManager( 6022): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6022): found sensor: LGE Gravity Sensor, handle=29
D/libc-netbsd(  267): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/SensorManager( 6022): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6022): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6022): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6022): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6022): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6022): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6022): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6022): found sensor: LGE Tilt Detector Sensor, handle=55
D/libc-netbsd(  267): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/SensorManager( 6022): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6022): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6022): found sensor: Motion Accel, handle=46
D/libc-netbsd(  267): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  267): res_queryN name = xxxxx succeed
I/System.out( 5771): propertyValue:false
D/libc-netbsd( 5771): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5771): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_out
W/Settings( 6022): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6022): startup - clean
I/art     ( 6022): CheckpointMarkThreadRoots callback created = 0xaaf344d0
,I/Babel   ( 6022): deleted: false for 0
I/art     ( 6022): CheckpointMarkThreadRoots callback created = 0xaaf344b0
,W/AudioCapabilities( 6022): Unsupported mime audio/x-lg-flac
,W/AudioCapabilities( 6022): Unsupported mime audio/adpcm
W/AudioCapabilities( 6022): Unsupported mime audio/g726
W/AudioCapabilities( 6022): Unsupported mime audio/x-ms-wma
W/AudioCapabilities( 6022): Unsupported mime audio/wma-voice
W/VideoCapabilities( 6022): Unsupported mime video/mjpg
W/VideoCapabilities( 6022): Unsupported mime video/theora
,I/ActivityManager(  857): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6056 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/AudioCapabilities( 6022): Unsupported mime audio/evrc
,W/AudioCapabilities( 6022): Unsupported mime audio/qcelp
W/VideoCapabilities( 6022): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6022): Unsupported mime audio/amr-wb-plus
W/AudioCapabilities( 6022): Unsupported mime audio/qcelp
W/AudioCapabilities( 6022): Unsupported mime audio/evrc
,W/VideoCapabilities( 6022): Unsupported mime video/mp4v-esdp
D/libc-netbsd( 5771): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5771): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/VideoCapabilities( 6022): Unsupported profile 4 for video/mp4v-es
,W/VideoCapabilities( 6022): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6022): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6022): Unrecognized profile 2130706433 for video/avc
,W/VideoCapabilities( 6022): Unrecognized profile 2130706433 for video/avc
,I/AppUp4:AppBoxCP( 6056): onCreate
,W/AppUp4:DB( 6056):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6056):  setFingerPrint start
I/AppUp4:DB( 6056):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
,I/AppUp4:DB( 6056):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6056):  SDK version = 0
I/AppUp4:DB( 6056):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 6056): AppBoxApplication onCreate()
I/AppUp4:CustModeStarterReceiver( 6056): onReceive
I/AppUp4:CustModeStarterReceiver( 6056): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
,D/AppUp4:CustFacade( 6056): Context : android.app.ReceiverRestrictedContext@140fd059
D/AppUp4:CustFacade( 6056): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6056): isSimDevice : true
,D/AppUp4:CustModeStarterReceiver( 6056): begin check event
I/AppUp4:CustModeStarterReceiver( 6056): Event For Nothing, skip.
W/art     ( 6022): Suspending all threads took: 27.056ms
,I/ActivityManager(  857): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6077 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
I/vclib   ( 6022): onServiceConnected
,W/Babel   ( 6022): Attempted to change video mute state without an active call.
I/NotificationManager( 6022): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6022): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6022): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
W/ResourcesManager( 6077): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 6077): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6077): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
V/JNIHelp ( 6022): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/System  ( 6022): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6022): Installed default security provider GmsCore_OpenSSL
,I/art     (  857): Explicit concurrent mark sweep GC freed 24796(1214KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 2.039ms total 148.733ms
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/AppConfig( 6077): Total System Memory = 906309632
,I/GalleryUtils( 6077): Application Heap = 96 MB
I/NotificationManager( 6022): com.google.android.talk: cancel(10436) by com.google.android.talk
I/NotificationManager(  857): android: cancelAsUser(2) by android
I/AppConfig( 6077): App Tier : NOT_DEF
,I/Icing   ( 4299): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,D/SystemHelper( 6077): region [EU], country [EU], operator [OPEN], sub-operator []
,I/qtaguid ( 5771): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5771): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5771): untagSocket(41) failed with errno -22
D/Icing   ( 4299): Loaded CLD2 Version V2.0 - 20141016
,I/ActivityManager(  857): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6100 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  857): Killing 5699:com.android.providers.calendar/u0a14 (adj 15): empty #11
D/Finsky  ( 5771): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430700] >= Server Version [-1]
I/Icing   ( 4299): Indexing 0A5267A505F47CB39AEB664724AACA2991DAA8A8 from com.google.android.googlequicksearchbox
,E/UEI.SmartControl( 5807): file observer is disposed!
,W/libprocessgroup(  857): failed to open /acct/uid_10014/pid_5699/cgroup.procs: No such file or directory
W/ResourcesManager( 6100): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6100): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,W/ResourcesManager( 6100): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6100): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
W/ResourcesManager( 6100): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/Icing   ( 4299): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
I/ActivityManager(  857): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=6121 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  857): android: cancelAsUser(2) by android
,W/ResourcesManager( 6121): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6121): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/ActivityManager(  857): Process com.lge.bnr (pid 5754) has died
,I/Icing   ( 4299): Indexing done 0A5267A505F47CB39AEB664724AACA2991DAA8A8
,I/SystemConfig( 6100): BUILD Country: EU
I/SystemConfig( 6100): BUILD Operator: OPEN
,I/MultiDex( 6121): VM with version 2.1.0 has multidex support
I/MultiDex( 6121): install
I/MultiDex( 6121): VM has multidex support, MultiDex support library is disabled.
V/JNIHelp ( 6121): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/SystemConfig( 6100): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6100): existFile = false
I/SystemConfig( 6100): canReadFile = false
I/SystemConfig( 6100): systemFeature RCS result false
D/SystemConfig( 6100): refreshRcsSupport() :false
,D/LockScreenSettings( 5718): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5718): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5718): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5718): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5718): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
W/ActivityThread( 6121): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6121): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@13e698a9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6121): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6121): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6121): com.google.android.gms: cancel(39789) by com.google.android.gms
I/UpdateIcingCorporaServi( 1933): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
D/ChimeraCfgMgr( 6121): Reading stored module config
,D/PackageBroadcastService( 4299): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4299): Null package name or gms related package.  Ignoreing.
I/AudioManager( 5988): getMode name:com.lge.qremote
,I/Icing   ( 4299): updateResources: need to parse f{com.google.android.gms}
I/AudioManager( 5988): getMode name:com.lge.qremote
D/ChimeraCfgMgr( 6121): Loading module com.google.android.gms.car from APK com.google.android.gms
,I/qtaguid ( 5771): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5771): Untagging socket 41 failed errno=-22
W/NetworkManagementSocketTagger( 5771): untagSocket(41) failed with errno -22
,I/UpdateIcingCorporaServi( 1933): UpdateCorporaTask done [took 114 ms] updated apps [took 114 ms] 
,I/ActivityManager(  857): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6158 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,I/art     (  306): Explicit concurrent mark sweep GC freed 705(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 310us total 24.291ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 291us total 21.610ms
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 278us total 20.850ms
,I/ActivityManager(  857): Process com.google.android.apps.docs (pid 5871) has died
D/NativeLibraryUtils( 6121): Install completed successfully. count=14 extracted=0
,D/CAR.SERVICE( 6121): Connecting to CarCallService...
D/PhoneMonitor( 6158): Register our PhoneStateListener
,I/art     ( 6121): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6121): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,V/SetupWizard( 6158): Connected to Gservices successfully
D/UEI.SmartControl( 5807): Internal timer expired: 2
,D/PhoneMonitor( 6158): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6158): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6158): [parse] Load xml
V/TelephonyAutoProfiling( 6158): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6158): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
D/CAR.SERVICE( 6121): com.google.android.projection.gearhead isn't installed.
,D/PhoneMonitor( 6158): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
I/ActivityManager(  857): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6184 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/CAR.TEL.Service( 6121): Creating a new CarCallService.
D/CAR.TEL.PhoneAdapter( 6121): Creating a new PhoneAdapter instance
W/ActivityManager(  857): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter( 6121): setListener: com.google.android.gms.car.dn@e542b8c
W/ActivityManager(  857): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter( 6121): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service( 6121): Starting CarCallService with initial phone null
I/NotificationManager( 6121): com.google.android.gms: cancel(10436) by com.google.android.gms
,I/art     ( 5771): CheckpointMarkThreadRoots callback created = 0xaafe21f0
,I/art     ( 5771): CheckpointMarkThreadRoots callback created = 0xaafe21d0
,D/CAR.SERVICE( 6121): Package validated; name: com.android.vending
,I/NotificationManager( 5771): com.android.vending: cancel(10436) by com.android.vending
,V/Finsky  ( 5771): [1] GearheadStateMonitor.access$100: mIsProjecting:false
W/ActivityManager(  857): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6184): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    ( 6184): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 92470257729; DSPS: 3121765; Offset : -2809441367
,W/ActivityManager(  857): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager(  857): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager(  857): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   ( 6184): Observing account changes for notifications
E/Gmail   ( 6184): Error finding the version of the Email provider.....
E/Gmail   ( 6184): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6184): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6184): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6184): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6184): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6184): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6184): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6184): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6184): We do not support migrating this version of the Email provider.
,I/Gmail   ( 6184): getAccountsCursor
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager(  857): Killing 5737:com.lge.eula/1000 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_1000/pid_5737/cgroup.procs: No such file or directory
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/AudioManager( 5988): getMode name:com.lge.qremote
I/Gmail   ( 6184): notifyAccountChanged
,I/Gmail   ( 6184): getAccountsCursor
I/Gmail   ( 6184): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/ActivityManager(  857): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6233 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 6184): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 6184): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   ( 6184): calculateUnknownSyncRationalesAndPurgeInBackground: running
W/ResourcesManager( 6233): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/Gmail   ( 6184): getAccountsCursor
,D/CalendarApplication( 6233): CalendarApplication.onCreate()
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/PreferenceKeysParser( 6233): [debug_displayParseInfos] preference keys.size() = 44
,D/PreferenceKeysParser( 6233): [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@39478ca0, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@140fd059, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@1a0d041e, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@1c0014ff, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@2ea8d2cc, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@23e41915, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@301442a, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@ccb021b, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@8f64fb8, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@3d7a3191, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@f4778f6, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@c8da4f7, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@e9caf64, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@17f55cd, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@18ea2e82, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@306d9993, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@1e275dd0, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@343881c9, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@1e10b0ce, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@304e3bef, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@316c86fc, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@3f3e7185, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@60b0bda, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@34eca80b, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@277916e8, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@12f9a101, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@2b1e0ba6, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@2bbbb9e7, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@13cb994, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@23de4c3d, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@350f3c32, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@3c800d83, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@3cf5db00, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@3f686f39, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@1070e97e, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@3cabfedf, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3c5da72c, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@34d7c5f5, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@eae1f8a, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@3c7ba9fb, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKey$KeyData@21940a18, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@dabcc71,
D/GeneralP,referenceUtils( 6233): [migratePrefrenceKeys] Exit: Version(44001700) >= 42001300
D/Config  ( 6233): [init]
I/Config  ( 6233): LGCalendar ver.4.40.17
I/Config  ( 6233): start check model
I/Config  ( 6233): start check native_ca
I/Config  ( 6233): Config Operator=OPEN, Country=EU
D/Config  ( 6233): [setDefaultValuesToPref]
D/Config  ( 6233): [parseProfiles]
I/Icing   ( 4299): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
D/ProfilesParser( 6233): [debug_displayParseInfos] profile.country = null
D/ProfilesParser( 6233): [debug_displayParseInfos] profile.operator = null
D/Config  ( 6233): [updateProfiletoCountryInfo]
D/GeneralPreference( 6233): [checkAndMigrateOldPreference]
D/AlertReceiver( 6233): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/InitNotificationRingtoneService( 6233): Start InitializeAlertRingtoneService.onHandleIntent
,I/AlertUtils( 6233): [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/38
I/AlertUtils( 6233): [getCalendarNotiSoundURIFromCursor] getCount()= 21
,I/Icing   ( 4299): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
I/AlertUtils( 6233): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arrpegio.ogg
I/AlertUtils( 6233): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
,I/AlertUtils( 6233): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
I/AlertUtils( 6233): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
,I/AlertUtils( 6233): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
I/AlertUtils( 6233): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
I/AlertUtils( 6233): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
,I/AlertUtils( 6233): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
I/AlertUtils( 6233): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
I/AlertUtils( 6233): [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Timer.ogg
,I/AlertUtils( 6233): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
I/AlertUtils( 6233): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
I/AlertUtils( 6233): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,I/AlertUtils( 6233): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
I/AlertUtils( 6233): [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
I/AlertUtils( 6233): [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/38
I/AlertUtils( 6233): set default noti to content://media/internal/audio/media/38
,I/InitNotificationRingtoneService( 6233): End InitializeAlertRingtoneService.onHandleIntent
I/art     (  857): Explicit concurrent mark sweep GC freed 17602(825KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/34MB, paused 3.427ms total 159.811ms
,I/NotificationManager(  857): android: cancelAsUser(2) by android
,W/HolidayIntentService( 6233): onHandleIntent
D/HolidayDataLoader( 6233): readJsonAsset : holiday.json
,D/AlertService( 6233): 0 Action = android.intent.action.PROVIDER_CHANGED
,E/AgendaWidgetManager( 6233): [updateWidgets] 
D/MonthWidgetProvider( 6233): [onReceive]
D/CalendarWidgetProvider( 6233): [onReceive]
D/CalendarWidgetProvider( 6233): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.MonthWidgetProvider }
D/CalendarTypeController( 6233): [onCreate] mContext.getPackageName() = com.android.calendar
,D/WeekWidgetProvider( 6233): [onReceive]
D/CalendarWidgetProvider( 6233): [onReceive]
D/CalendarWidgetProvider( 6233): [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.WeekWidgetProvider }
D/CalendarTypeController( 6233): [onCreate] mContext.getPackageName() = com.android.calendar
I/AppUp4:CustModeStarterReceiver( 6056): onReceive
I/AppUp4:CustModeStarterReceiver( 6056): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
D/AppUp4:CustFacade( 6056): Context : android.app.ReceiverRestrictedContext@140fd059
D/AppUp4:CustFacade( 6056): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 6056): isSimDevice : true
I/NotificationManager( 6022): com.google.android.talk: cancel(8) by com.google.android.talk
D/AppUp4:CustModeStarterReceiver( 6056): begin check event
I/AppUp4:CustModeStarterReceiver( 6056): Event For Nothing, skip.
D/LockScreenSettings( 5718): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 5718): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 5718): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 5718): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 5718): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,E/HolidayIntentService( 6233): onHandleIntent:holiday data empty
I/UpdateIcingCorporaServi( 1933): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/AudioManager( 5988): getMode name:com.lge.qremote
D/PackageBroadcastService( 4299): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PackageBroadcastService( 4299): Null package name or gms related package.  Ignoreing.
,I/AudioManager( 5988): getMode name:com.lge.qremote
I/Icing   ( 4299): updateResources: need to parse f{com.google.android.gms}
,I/UpdateIcingCorporaServi( 1933): UpdateCorporaTask done [took 50 ms] updated apps [took 50 ms] 
,I/ActivityManager(  857): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarProviderBroadcastReceiver: pid=6269 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ResourcesManager( 6269): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/CalendarProvider2( 6269): [initialize] mInstance = com.android.providers.calendar.CalendarProvider2@1230ecd2
,D/CalendarProvider2( 6269): [getOrCreateCalendarAlarmManager]
I/CalendarProvider2( 6269): Created com.android.providers.calendar.CalendarAlarmManager@1c0014ff(com.android.providers.calendar.CalendarProvider2@1230ecd2)
,D/CalendarProviderBroadcastReceiver( 6269): Received intent : Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderBroadcastReceiver (has extras) }
D/CalendarProviderBroadcastReceiver( 6269): [IntentService] WakeLock acquire, start IntentSerivce
D/CalendarProvider2( 6269): CalendarProviderIntentService.onCreate()
,D/CalendarProvider2( 6269): Received Intent: Intent { act=com.android.providers.calendar.intent.CalendarProvider2 flg=0x14 cmp=com.android.providers.calendar/.CalendarProviderIntentService (has extras) }
D/CalendarProvider2( 6269): [getOrCreateCalendarAlarmManager]
E/MDM     ( 1731): [138] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/LocationInitializer( 4299): Restart initialization of location
D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
I/qtaguid ( 5771): Failed write_ctrl(u 41) res=-1 errno=22
I/qtaguid ( 5771): Untagging socket 41 failed errno=-22
,W/NetworkManagementSocketTagger( 5771): untagSocket(41) failed with errno -22
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
I/AudioManager( 5988): getMode name:com.lge.qremote
,W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
D/CalendarProvider2( 6269): [IntentService] Release Lock
,D/CalendarProvider2( 6269): CalendarProviderIntentService.onDestroy()
I/AudioManager( 5988): getMode name:com.lge.qremote
I/ActivityManager(  857): Killing 6184:com.google.android.gm/u0a53 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10053/pid_6184/cgroup.procs: No such file or directory
,I/ActivityManager(  857): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=6293 uid=10053 gids={50053, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,W/ResourcesManager( 5771): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 5771): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 5771): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  ( 5771): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager(  857): RTC_WAKEUP set : Alarm{27f5dc48 type 0 when 1457344284917 com.android.vending} when 1457344284917
W/ActivityManager(  857): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/DeviceConnectionService( 1731): client connected with version: 8296000
,D/Finsky  ( 5771): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  ( 5771): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
I/ActivityManager(  857): Killing 6158:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10038/pid_6158/cgroup.procs: No such file or directory
,I/Gmail   ( 6293): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GAV2    ( 6293): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager(  857): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/ActivityManager(  857): Killing 6056:com.lge.appbox.client/u0a11 (adj 15): empty #11
W/ActivityManager(  857): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/libprocessgroup(  857): failed to open /acct/uid_10011/pid_6056/cgroup.procs: No such file or directory
,E/Gmail   ( 6293): Error finding the version of the Email provider.....
E/Gmail   ( 6293): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 6293): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
E/Gmail   ( 6293): 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
E/Gmail   ( 6293): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
E/Gmail   ( 6293): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 6293): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 6293): 	at android.os.Looper.loop(Looper.java:135)
E/Gmail   ( 6293): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 6293): We do not support migrating this version of the Email provider.
W/ActivityManager(  857): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   ( 6293): getAccountsCursor
I/Gmail   ( 6293): Observing account changes for notifications
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/AudioManager( 5988): getMode name:com.lge.qremote
I/AudioManager( 5988): getMode name:com.lge.qremote
,I/AudioManager( 5988): getMode name:com.lge.qremote
I/AudioManager( 5988): getMode name:com.lge.qremote
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/Finsky  ( 5771): [690] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager(  857): android: cancelAsUser(2) by android
,D/libc-netbsd( 5771): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5771): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 5771): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 5771): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,E/BandwidthController(  267): [LG DATA] No such appUid: 10036
D/DnsProxyListener(  267): App 10036 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  267): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  267): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  267): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  267): res_queryN name = xxxxx, class = 1, type = 1
I/Gmail   ( 6293): notifyAccountChanged
,I/Gmail   ( 6293): getAccountsCursor
I/Gmail   ( 6293): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 6293): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   ( 6293): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 6293): calculateUnknownSyncRationalesAndPurgeInBackground: running
D/libc-netbsd(  267): res_queryN name = xxxxx succeed
,I/System.out( 5771): propertyValue:false
I/art     ( 5788): Explicit concurrent mark sweep GC freed 8221(412KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/10MB, paused 392us total 39.056ms
,I/Gmail   ( 6293): getAccountsCursor
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Icing   ( 4299): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4299): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  857): Killing 6077:com.android.gallery3d/u0a23 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10023/pid_6077/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/CAR.SERVICE( 6121): mConnectedToCar = false, abort
,E/ActivityThread( 6121): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@36dc91f4 that was originally bound here
E/ActivityThread( 6121): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@36dc91f4 that was originally bound here
E/ActivityThread( 6121): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6121): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6121): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6121): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6121): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6121): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6121): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6121): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6121): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6121): 	at com.google.android.gms.car.hc.<init>(SourceFile:319)
E/ActivityThread( 6121): 	at com.google.android.gms.car.CarChimeraService.onCreate(SourceFile:74)
E/ActivityThread( 6121): 	at com.google.android.chimera.ServiceProxy.setImpl(SourceFile:115)
E/ActivityThread( 6121): 	at com.google.android.chimera.ServiceProxy.onCreate(SourceFile:105)
E/ActivityThread( 6121): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6121): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6121): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6121): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6121): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6121): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6121): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6121): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6121): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6121): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,E/ActivityThread( 6121): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@7d258bf that was originally bound here
E/ActivityThread( 6121): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@7d258bf that was originally bound here
E/ActivityThread( 6121): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6121): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6121): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6121): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6121): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6121): 	at com.google.android.gms.common.stats.g.a(SourceFile:128)
E/ActivityThread( 6121): 	at com.google.android.gms.common.stats.g.a(SourceFile:145)
E/ActivityThread( 6121): 	at com.google.android.gms.car.dp.a(SourceFile:586)
E/ActivityThread( 6121): 	at com.google.android.gms.car.dp.<init>(SourceFile:511)
E/ActivityThread( 6121): 	at com.google.android.gms.car.dp.a(SourceFile:488)
E/ActivityThread( 6121): 	at com.google.android.gms.car.dm.<init>(SourceFile:112)
E/ActivityThread( 6121): 	at com.google.android.gms.car.CarCallService.onBind(SourceFile:79)
E/ActivityThread( 6121): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:2847)
E/ActivityThread( 6121): 	at android.app.ActivityThread.access$1900(ActivityThread.java:155)
E/ActivityThread( 6121): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1411)
E/ActivityThread( 6121): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6121): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6121): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6121): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6121): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6121): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6121): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,W/ActivityManager(  857): Unbind failed: could not find connection for android.os.BinderProxy@21e98f3e
D/AlertService( 6233): Beginning updateAlertNotification
,D/AlertService( 6233): No fired or scheduled alerts
,I/NotificationManager( 6233): com.android.calendar: cancel(0) by com.android.calendar
I/NotificationManager( 6233): com.android.calendar: cancel(1) by com.android.calendar
I/NotificationManager( 6233): com.android.calendar: cancel(2) by com.android.calendar
I/NotificationManager( 6233): com.android.calendar: cancel(3) by com.android.calendar
I/NotificationManager( 6233): com.android.calendar: cancel(4) by com.android.calendar
I/NotificationManager( 6233): com.android.calendar: cancel(5) by com.android.calendar
I/NotificationManager( 6233): com.android.calendar: cancel(6) by com.android.calendar
I/NotificationManager( 6233): com.android.calendar: cancel(7) by com.android.calendar
I/NotificationManager( 6233): com.android.calendar: cancel(8) by com.android.calendar
I/NotificationManager( 6233): com.android.calendar: cancel(9) by com.android.calendar
I/NotificationManager( 6233): com.android.calendar: cancel(10) by com.android.calendar
I/NotificationManager( 6233): com.android.calendar: cancel(11) by com.android.calendar
I/NotificationManager( 6233): com.android.calendar: cancel(12) by com.android.calendar
I/NotificationManager( 6233): com.android.calendar: cancel(13) by com.android.calendar
,I/NotificationManager( 6233): com.android.calendar: cancel(14) by com.android.calendar
I/NotificationManager( 6233): com.android.calendar: cancel(15) by com.android.calendar
I/NotificationManager( 6233): com.android.calendar: cancel(16) by com.android.calendar
I/NotificationManager( 6233): com.android.calendar: cancel(17) by com.android.calendar
I/NotificationManager( 6233): com.android.calendar: cancel(18) by com.android.calendar
I/NotificationManager( 6233): com.android.calendar: cancel(19) by com.android.calendar
I/NotificationManager( 6233): com.android.calendar: cancel(20) by com.android.calendar
I/ActivityManager(  857): Killing 6022:com.google.android.talk/u0a61 (adj 15): empty #11
,D/AlertService( 6233): Scheduling next alarm with AlarmScheduler. sEventReminderReceived: null
W/libprocessgroup(  857): failed to open /acct/uid_10061/pid_6022/cgroup.procs: No such file or directory
,D/AlarmScheduler( 6233): No events found starting within 1 week.
I/ActivityManager(  857): Killing 6233:com.android.calendar/u0a13 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10013/pid_6233/cgroup.procs: No such file or directory
,I/ActivityManager(  857): Killing 6100:com.android.contacts/u0a18 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10018/pid_6100/cgroup.procs: No such file or directory
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/GAV2    ( 6293): Thread[GAThread,5,main]: No campaign data found.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/rmt_storage(  265): rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6403090
I/rmt_storage(  265): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: R/W request received
I/rmt_storage(  265): wakelock acquired: 1, error no: 42
,I/rmt_storage(  265): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
I/rmt_storage(  265): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Bytes written = 1572864
I/rmt_storage(  265): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0x9 msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  265): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 0
I/rmt_storage(  265): 
I/rmt_storage(  265): rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6403090
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/AlarmManager(  857): RTC_WAKEUP set : Alarm{129928bb type 0 when 1457344298705 com.android.vending} when 1457344298705
,V/AlarmManager(  857): RTC_WAKEUP set : Alarm{114181d8 type 0 when 1457344299965 com.google.android.gms} when 1457344299965
I/CheckinService( 4299): Checkin interval check for package: unspecified last checkin: 1457344270038 min interval config: 0 actual interval: 31918
,W/ContextImpl( 3687): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 android.content.ContextWrapper.sendBroadcast:376 com.lge.mlt.MptOnLogDumper.run:279 <bottom of call stack> <bottom of call stack> 
,I/CheckinService( 4299): Checking schedule, now: 1457344301987 next: 1457344299965
I/CheckinService( 4299): active receiver: enabled
,I/CheckinService( 4299): Preparing to send checkin request
I/EventLogService( 4299): Accumulating logs since 1457344263470
,I/CheckinRequestBuilder( 4299): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 4299): Failed to find provider info for com.google.android.wearable.settings
,D/Finsky  ( 5771): [680] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 5771): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
I/art     (  857): Explicit concurrent mark sweep GC freed 19959(954KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 2.279ms total 157.584ms
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager(  857): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6410 uid=10006 gids={50006, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 1005, 3007} abi=armeabi-v7a
,W/ResourcesManager( 6410): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6410): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/MultiDex( 6410): VM with version 2.1.0 has multidex support
I/MultiDex( 6410): install
,I/MultiDex( 6410): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp ( 6410): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 6410): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 6410): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@13e698a9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,I/ProviderInstaller( 6410): Installed default security provider GmsCore_OpenSSL
I/NotificationManager( 6410): com.google.android.gms: cancel(10436) by com.google.android.gms
I/NotificationManager( 6410): com.google.android.gms: cancel(39789) by com.google.android.gms
D/WearableService( 1731): callingUid 10006, callindPid: 1731
,D/AuthorizationBluetoothService( 1731): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/MDM     ( 1731): [143] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
D/LocationInitializer( 4299): Restart initialization of location
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/NotificationManager( 1731): com.google.android.gms: cancel(0) by com.google.android.gms
I/art     ( 6410): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
I/art     ( 6410): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
W/GCoreFlp( 1731): No location to return for getLastLocation()
W/FusedLocationProvider( 1731): location=null
,D/NativeLibraryUtils( 6410): Install completed successfully. count=14 extracted=0
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): CdmEngine::OpenSession
I/WVCdm   (  271): Level3 Library Dec 11 2014 16:13:16
W/WVCdm   (  271): Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
W/WVCdm   (  271): Properties::GetOEMCryptoPath: null. applies level3
W/WVCdm   (  271): L1 library not specified. Falling Back to L3
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
,W/WVCdm   (  271): BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
W/WVCdm   (  271): CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
D/WVCdm   (  271): PrepareKeyRequest: nonce=250887190
I/art     ( 6410): CheckpointMarkThreadRoots callback created = 0xb042d520
,I/art     ( 6410): CheckpointMarkThreadRoots callback created = 0xaae47e20
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 112471764543; DSPS: 3777174; Offset : -2809430747
,I/dex2oat ( 6450): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=34 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,I/dex2oat ( 6450): dex2oat took 104.263ms (threads: 4)
,I/Adreno-EGL( 6410): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6410): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6410): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6410): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6410): Remote Branch: 
I/Adreno-EGL( 6410): Local Patches: 
I/Adreno-EGL( 6410): Reconstruct Branch: 
I/Adreno-EGL( 6410): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6410): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6410): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6410): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6410): Remote Branch: 
I/Adreno-EGL( 6410): Local Patches: 
I/Adreno-EGL( 6410): Reconstruct Branch: 
,I/Adreno-EGL( 6410): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 6410): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL( 6410): Build Date: 03/02/15 Mon
I/Adreno-EGL( 6410): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL( 6410): Remote Branch: 
I/Adreno-EGL( 6410): Local Patches: 
I/Adreno-EGL( 6410): Reconstruct Branch: 
,I/CheckinRequestBuilder( 4299): Classify the device as Phone.
,D/libc-netbsd( 4299): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4299): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4299): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4299): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  267): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  267): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  267): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  267): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  267): default dns: query_ipv6=0, query_ipv4=1, netid=100
D/libc-netbsd(  267): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  267): res_queryN name = xxxxx succeed
I/System.out( 4299): propertyValue:false
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
D/libc-netbsd( 4299): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4299): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 4299): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4299): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 4299): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 4299): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/CheckinTask( 4299): Sending checkin request (7666 bytes)
I/ThermalEngine(  293): Sensor:pa_therm0:32000 mC
,I/CheckinRequestBuilder( 4299): Checkin reason type: 8 attempt count: 1
,E/ActivityThread( 4299): Failed to find provider info for com.google.android.wearable.settings
I/WVCdm   (  271): CdmEngine::CloseSession
,I/WVCdm   (  271): L3 Terminate.
,I/CheckinRequestBuilder( 4299): Classify the device as Phone.
,I/CheckinTask( 4299): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 4299): Checking schedule, now: 1457344305131 next: 1457871554125
I/CheckinService( 4299): active receiver: disabled
,D/CheckinService( 4299): Recording last checkin time for package unspecified as 1457344305165
I/ActivityManager(  857): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.util.GservicesChangedReceiver: pid=6475 uid=10038 gids={50038, 9997, 3003} abi=armeabi-v7a
,D/PhoneMonitor( 6475): Register our PhoneStateListener
,V/SetupWizard( 6475): Connected to Gservices successfully
,D/PhoneMonitor( 6475): onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
V/TelephonyAutoProfiling( 6475): [loadFeatureFromXml] *** start feature loading from xml
,D/TelephonyAutoProfiling( 6475): [parse] Load xml
V/TelephonyAutoProfiling( 6475): [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
V/TelephonyAutoProfiling( 6475): [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, KRWapPushWithSpam=true, GLOBALspam=true, spam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, OperatorMessage=true}
,D/PhoneMonitor( 6475): onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
D/GCM     ( 1731): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/MusicWidget( 2590): mDelayedStopHandler : unbind
,I/MusicBrowser( 2653): [MediaPlaybackService.java:2912:onUnbind()] oooooo 
,I/MusicBrowser( 2653): [MediaPlaybackService.java:2119:saveQueue()] oooooo {full=true}
I/MusicBrowser( 2653): [MediaPlaybackService.java:2124:saveQueue()] oooooo mQueueIsSaveable ==>> true  mCardId ==>> -1
D/MusicBrowser( 2653): [MediaPlaybackService.java:2204:saveQueue()] oooooo {queue=}
D/MusicBrowser( 2653): [MediaPlaybackService.java:2206:saveQueue()] oooooo {mCardId=-1}
D/MusicBrowser( 2653): [MediaPlaybackService.java:2241:saveQueue()] oooooo {curpos=-1}
I/MusicBrowser( 2653): [MediaPlaybackService.java:2085:onDestroy()] oooooo 
,I/MusicBrowser( 2653): [MediaPlaybackService.java:8681:clearReceiver()] oooooo 
I/MediaFocusControl(  857):  AudioFocus  abandonAudioFocus() from android.media.AudioManagerEx@3f3e7185com.lge.music.MediaPlaybackService$6@60b0bda
,D/MusicBrowser( 2653): [MediaPlaybackService.java:8715:clearReceiver()] oooooo abandonAudioFocus : 1
I/MusicBrowser( 2653): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2653): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2653): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2653): [HomeCloudUtils.java:448:unregisterListener()] oooooo unregisterListener mPlayerListener: com.lge.music.MediaPlaybackService$28@8f64fb8
,I/MusicBrowser( 2653): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2653): [MusicUtils.java:6841:endNotiTimer()] oooooo endNotiTimer
I/MusicBrowser( 2653): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2653): [MediaPlaybackService.java:destroyIndexCountProvider()] oooooo 
I/MusicBrowser( 2653): [GroupIndexApi.java:260:groupingIndexDataProviderStop()] oooooo groupingIndexDataProviderStop 
I/MusicBrowser( 2653): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2653): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2653): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2653): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2653): [MediaPlaybackService.java:8851:unregisterReceiverSafe()] oooooo 
I/MusicBrowser( 2653): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
,I/MusicBrowser( 2653): [MediaPlaybackService.java:6745:release()] oooooo 
I/MusicBrowser( 2653): [MediaPlaybackService.java:6706:stop()] oooooo 
I/MediaPlayer[Native]( 2653): reset
V/MediaPlayer[Native]( 2653): setListener
,V/MediaPlayer[Native]( 2653): disconnect
V/MediaPlayer[Native]( 2653): destructor
V/AudioFlinger(  271): releasing 19 from 2653 for -1
V/AudioFlinger(  271):  decremented refcount to 0
V/AudioFlinger(  271): purging stale effects
V/MediaPlayer[Native]( 2653): disconnect
D/MusicBrowser( 2653): [MusicUtils.java:619:getSmartShareVersion()] oooooo versionCode:305010
I/SmartShareClient( 2653): [SmartShareManagerClient] smartshare client supported version code: 305010
,I/SmartShareClient( 2653): [SmartShareManagerClient] smartshare client enabled
I/MusicBrowser( 2653): [MusicUtils.java:791:isSupportSmartshareConnectWizard()] oooooo SmartShare push support! Package name : 44000028
I/MusicBrowser( 2653): [MusicUtils.java:639:getSmartShareVersion()] oooooo SmartshareVersion:953
V/MusicBrowser( 2653): [MediaPlaybackService.java:9358:terminateSmartShareClient()] oooooo 
I/SmartShareClient( 2653): [SmartShareManagerClient] unregisterListener: 887924747
W/SmartShareClient( 2653): [SmartShareManagerClient] unregisterListener invalid listener: 887924747
I/SmartShareClient( 2653): [SmartShareManagerClient] terminate service: 2653/MediaPlaybackService/437060638
E/HomeCloudIF( 2653): unregiterHomeCloudBroadcast(), Illegal argument.
I/SmartShareClient( 2653): [SmartShareManagerClient] unbindService context:android.app.Application@277916e8
V/CloudHub( 2653): [HELPER][Framework|isAvailable] com.lge.cloudhub: versionName=2.3.3, versionCode=203003, state=0
V/CloudHub( 2653): [CLIENT][CloudHubClientFactory|destroyScheduler] Destroy scheduler (count=0)
I/CloudHub( 2653): [CLIENT][CloudHubClientFactory|destroyScheduler] Start exit timer
,I/MusicBrowser( 2653): [MusicUtils.java:10472:isAKACoverSupported()] oooooo aka not support!
D/MusicBrowser( 2653): [MediaPlaybackService.java:9053:setStopForeground()] oooooo bValue : true
I/ActivityManager(  857): Killing 5718:com.lge.lockscreensettings/u0a69 (adj 15): empty #11
I/CloudHub( 2653): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 29995
W/libprocessgroup(  857): failed to open /acct/uid_10069/pid_5718/cgroup.procs: No such file or directory
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/ActivityManager(  857): Killing 6269:com.android.providers.calendar/u0a14 (adj 15): empty #11
,I/ActivityManager(  857): Killing 5917:com.google.android.apps.plus/u0a86 (adj 15): empty #12
,W/libprocessgroup(  857): failed to open /acct/uid_10014/pid_6269/cgroup.procs: No such file or directory
,W/libprocessgroup(  857): failed to open /acct/uid_10086/pid_5917/cgroup.procs: No such file or directory
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]QPairHandler( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,I/InputReader(  857): Reconfiguring input devices.  changes=0x00000010
I/QCNEJ   ( 1838): |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1875): [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 6
,I/[LGHome]Launcher( 1875): [Launcher.java:4017:setLoadOnResume()]setLoadOnResume
,I/ActivityManager(  857): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=6516 uid=10061 gids={50061, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/administrator(  857): Handling package changes for user 0
I/[SystemUI]QSlideListController( 1373): onReceive = android.intent.action.PACKAGE_CHANGED
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
,W/[SystemUI]QSlideLoader( 1373): Cannot find com.lge.email/com.lge.email.QSlideIcon in predefined list
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
,W/ResourcesManager( 6516): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager(  857): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/NotificationService(  857): action=android.intent.action.PACKAGE_CHANGED queryReplace=false
D/BackupManagerService(  857): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,I/BackupManagerService(  857): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
I/BackupManagerService(  857): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService(  857): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService(  857): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3ff2420d
,I/Babel_SMS( 6516): MmsConfig: mnc/mcc: 0/0
I/Babel_SMS( 6516): MmsConfig.loadMmsSettings
,I/Babel_SMS( 6516): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/Babel_SMS( 6516): MmsConfig.loadFromDatabase
,W/ResourceType(  857): Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
E/Babel_SMS( 6516): canonicalizeMccMnc: invalid mccmnc 
I/Babel_SMS( 6516): MmsConfig.loadFromResources
E/Babel_SMS( 6516): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel_SMS( 6516): MmsConfig.loadMmsSettings: mUserAgent=LG-D722 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D722-M3-D1.xml
I/[LGHome]EVENT( 1875): [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/GCoreNlp( 1731): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/LocationProviderProxy(  857): applying state to connected service
,D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
D/SensorManager( 6516): found sensor: LGE Accelerometer Sensor, handle=0
D/SensorManager( 6516): found sensor: LGE Magnetometer Sensor, handle=10
D/SensorManager( 6516): found sensor: LGE Magnetometer Sensor Uncalibrated, handle=11
D/SensorManager( 6516): found sensor: LGE Proximity Sensor, handle=48
D/SensorManager( 6516): found sensor: LGE Gravity Sensor, handle=29
D/SensorManager( 6516): found sensor: LGE Linear Acceleration Sensor, handle=30
D/SensorManager( 6516): found sensor: LGE Rotation Vector Sensor, handle=36
D/SensorManager( 6516): found sensor: LGE Step Detector Sensor, handle=43
D/SensorManager( 6516): found sensor: LGE Step Counter Sensor, handle=44
D/SensorManager( 6516): found sensor: LGE Significant Motion Detector Sensor, handle=47
D/SensorManager( 6516): found sensor: LGE GeoMagnetic Rotation Vector Sensor, handle=53
D/SensorManager( 6516): found sensor: LGE Orientation Sensor, handle=49
D/SensorManager( 6516): found sensor: LGE Tilt Detector Sensor, handle=55
D/SensorManager( 6516): found sensor: LGE Absolute Motion Detector Sensor, handle=33
D/SensorManager( 6516): found sensor: LGE Relative Motion Detector Sensor, handle=34
D/SensorManager( 6516): found sensor: Motion Accel, handle=46
,W/Settings( 6516): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/Babel_Crash( 6516): startup - clean
,I/art     ( 6516): CheckpointMarkThreadRoots callback created = 0xaaf4d8f0
I/art     ( 6516): CheckpointMarkThreadRoots callback created = 0xaaf4d8e0
,I/Babel   ( 6516): deleted: false for 0
,W/AudioCapabilities( 6516): Unsupported mime audio/x-lg-flac
W/AudioCapabilities( 6516): Unsupported mime audio/adpcm
W/AudioCapabilities( 6516): Unsupported mime audio/g726
W/AudioCapabilities( 6516): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 6516): Unsupported mime audio/wma-voice
,W/VideoCapabilities( 6516): Unsupported mime video/mjpg
W/VideoCapabilities( 6516): Unsupported mime video/theora
I/ActivityManager(  857): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6553 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,W/AudioCapabilities( 6516): Unsupported mime audio/evrc
W/AudioCapabilities( 6516): Unsupported mime audio/qcelp
W/VideoCapabilities( 6516): Unrecognized profile 2130706433 for video/avc
W/AudioCapabilities( 6516): Unsupported mime audio/amr-wb-plus
,W/AudioCapabilities( 6516): Unsupported mime audio/qcelp
W/AudioCapabilities( 6516): Unsupported mime audio/evrc
W/VideoCapabilities( 6516): Unsupported mime video/mp4v-esdp
,I/AppUp4:AppBoxCP( 6553): onCreate
W/AppUp4:DB( 6553):  [AppBoxDatabaseHelper] construct
I/AppUp4:DB( 6553):  setFingerPrint start
I/AppUp4:DB( 6553):  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys SDK version = 21
I/VideoCapabilities( 6516): Unsupported profile 4 for video/mp4v-es
,I/AppUp4:DB( 6553):  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1428918170/151031842f939:user/release-keys
I/AppUp4:DB( 6553):  SDK version = 0
I/AppUp4:DB( 6553):  beforefinger == newfinger no write in DB
W/VideoCapabilities( 6516): Unrecognized profile 2130706433 for video/avc
W/VideoCapabilities( 6516): Unrecognized profile 2130706433 for video/avc
D/AppUp4:AppBoxApplication( 6553): AppBoxApplication onCreate()
,W/VideoCapabilities( 6516): Unrecognized profile 2130706433 for video/avc
I/AppUp4:CustModeStarterReceiver( 6553): onReceive
I/AppUp4:CustModeStarterReceiver( 6553): CustModeStarterReceiver - android.intent.action.PACKAGE_CHANGED
W/VideoCapabilities( 6516): Unrecognized profile 2130706433 for video/avc
D/AppUp4:CustFacade( 6553): Context : android.app.ReceiverRestrictedContext@140fd059
D/AppUp4:CustFacade( 6553): isCustomizationCompleted : false
D/AppUp4:CustFacade( 6553): isSimDevice : true
D/AppUp4:CustModeStarterReceiver( 6553): begin check event
I/AppUp4:CustModeStarterReceiver( 6553): Event For Nothing, skip.
,I/ActivityManager(  857): Killing 6121:com.google.android.gms:car/u0a6 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10006/pid_6121/cgroup.procs: No such file or directory
,I/ActivityManager(  857): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6575 uid=10023 gids={50023, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,I/vclib   ( 6516): onServiceConnected
,W/Babel   ( 6516): Attempted to change video mute state without an active call.
I/NotificationManager( 6516): com.google.android.talk: cancel(8) by com.google.android.talk
,W/ResourcesManager( 6516): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 6516): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,W/ResourcesManager( 6575): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6575): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 6575): Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
,V/JNIHelp ( 6516): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,I/AppConfig( 6575): Total System Memory = 906309632
,I/GalleryUtils( 6575): Application Heap = 96 MB
I/AppConfig( 6575): App Tier : NOT_DEF
D/SystemHelper( 6575): region [EU], country [EU], operator [OPEN], sub-operator []
W/System  ( 6516): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader dalvik.system.PathClassLoader[DexPathList[[zip file "/system/framework/com.google.android.media.effects.jar", zip file "/data/app/com.google.android.talk-1/base.apk"],nativeLibraryDirectories=[/data/app/com.google.android.talk-1/lib/arm, /vendor/lib, /system/lib]]]: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 6516): Installed default security provider GmsCore_OpenSSL
,I/ActivityManager(  857): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6596 uid=10018 gids={50018, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
,I/ActivityManager(  857): Killing 6293:com.google.android.gm/u0a53 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10053/pid_6293/cgroup.procs: No such file or directory
I/NotificationManager( 6516): com.google.android.talk: cancel(10436) by com.google.android.talk
,W/ResourcesManager( 6596): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 6596): Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
W/ResourcesManager( 6596): Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
W/ResourcesManager( 6596): Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
,W/ResourcesManager( 6596): Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
I/SystemConfig( 6596): BUILD Country: EU
I/SystemConfig( 6596): BUILD Operator: OPEN
,I/ActivityManager(  857): Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=6620 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  857): Killing 5807:com.uei.lg.quicksetsdk.lite/u0a89 (adj 15): empty #11
,W/System.err( 5988): android.os.DeadObjectException
,I/art     (  306): Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 303us total 21.681ms
W/System.err( 5988): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5988): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5988): 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
,W/System.err( 5988): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:197)
W/System.err( 5988): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5988): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5988): 	at android.os.Handler.handleCallback(Handler.java:739)
,W/System.err( 5988): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5988): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5988): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5988): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5988): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5988): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5988): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5988): IControl.unregisterCallback error: android.os.DeadObjectException
W/System.err( 5988): android.os.DeadObjectException
W/System.err( 5988): 	at android.os.BinderProxy.transactNative(Native Method)
W/System.err( 5988): 	at android.os.BinderProxy.transact(Binder.java:496)
W/System.err( 5988): 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
W/System.err( 5988): 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:198)
W/System.err( 5988): 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1391)
W/System.err( 5988): 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1405)
W/System.err( 5988): 	at android.os.Handler.handleCallback(Handler.java:739)
W/System.err( 5988): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 5988): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5988): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 5988): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 5988): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 5988): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 5988): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 5988): IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 266us total 20.557ms
I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 308us total 20.458ms
,W/libprocessgroup(  857): failed to open /acct/uid_10089/pid_5807/cgroup.procs: No such file or directory
,W/ActivityManager(  857): Scheduling restart of crashed service com.uei.lg.quicksetsdk.lite/com.uei.control.Service in 1000ms
I/SystemConfig( 6596): pm.hasSystemFeature(com.lge.ims.rcs) = false
I/SystemConfig( 6596): existFile = false
I/SystemConfig( 6596): canReadFile = false
I/SystemConfig( 6596): systemFeature RCS result false
D/SystemConfig( 6596): refreshRcsSupport() :false
I/LockScreenSettings( 6620): Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,I/ActivityManager(  857): Start proc com.uei.lg.quicksetsdk.lite for service com.uei.lg.quicksetsdk.lite/com.uei.control.Service: pid=6638 uid=10089 gids={50089, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/LockScreenSettings( 6620): Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
D/LockScreenSettings( 6620): Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
D/LockScreenSettings( 6620): Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
D/LockScreenSettings( 6620): Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
D/LockScreenSettings( 6620): Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
,I/ActivityManager(  857): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6655 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
I/ActivityManager(  857): Killing 5988:com.lge.qremote/u0a106 (adj 15): empty #11
,W/libprocessgroup(  857): failed to open /acct/uid_10106/pid_5988/cgroup.procs: No such file or directory
W/ResourcesManager( 6655): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/UEI.SmartControl( 6638): Quickset Services start...
I/UEI.SmartControl( 6638): Manufacture = LGE
D/UEI.SmartControl( 6638): File observer start...
E/UEI.SmartControl( 6638): IR Port is disabled: false
,D/UEI.SmartControl( 6638): Starting file observer...
D/UEI.SmartControl( 6638): Extracting JNI libs...
D/UEI.SmartControl( 6638): --- this system supports 32-bit or 64-bit only
D/UEI.SmartControl( 6638): --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
,D/UEI.SmartControl( 6638): --- Checking lib: libqs_armeabi-v7a.zip
D/UEI.SmartControl( 6638): --- Extracting JNI libs: libqs_armeabi-v7a.zip
I/UEI.SmartControl( 6638): --- Selecting new region: 2
I/UEI.SmartControl( 6638): -- Running on KitKat(19) and above! JNI will be used.
,D/UEI.SmartControl( 6638): Platform has CIR...
D/UEI.SmartControl( 6638): NO CIR support, need to check package...
I/UEI.SmartControl( 6638): Model: LG-D722 uses JNI
D/UEI.SmartControl( 6638): QS Service created
E/UEI.SmartControl( 6638): QS start get config
,D/UEI.SmartControl( 6638): Loading JNI Libs...
D/UEI.SmartControl( 6638):  configuring local db...
,I/art     (  857): Explicit concurrent mark sweep GC freed 27148(1480KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 23MB/34MB, paused 1.993ms total 152.584ms
,D/UEI.SmartControl( 6638):  ---- Has DB8: true
,D/UEI.SmartControl( 6638): QS start statue = true Error code = 0
D/UEI.SmartControl( 6638): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6638): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6638): IRRCDataComm has AudioManager!!!!.
I/UpdateIcingCorporaServi( 1933): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/irrc_jni( 6638): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6638): IrrcClient ++ 
D/irrcClient( 6638): getIrrcService ++ 
D/irrcClient( 6638): getIrrcService -- 
D/irrcClient( 6638): IrrcClient -- 
W/irrc_jni( 6638): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6638): Services init done
D/PackageBroadcastService( 4299): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 4299): Null package name or gms related package.  Ignoreing.
I/UEI.SmartControl( 6638): Device manager: loading config....
,D/UEI.SmartControl( 6638): QS Service init finished
D/UEI.SmartControl( 6638): QS Service version name: 0.1.73
D/UEI.SmartControl( 6638): QS Service version code: 1073
D/UEI.SmartControl( 6638): Config is loaded...
D/UEI.SmartControl( 6638): Service requested: Control
D/UEI.SmartControl( 6638): Service.onUnbind: IControl
D/UEI.SmartControl( 6638): Service.onDestroy
D/UEI.SmartControl( 6638): Shutdown IRRCPlayer... 
W/irrc_jni( 6638): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6638): ~IrrcClient ++ 
D/irrcClient( 6638): ~IrrcClient -- 
W/irrc_jni( 6638): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6638): Blaster closed
D/UEI.SmartControl( 6638): Blaster closed
D/UEI.SmartControl( 6638): Shut down QS...
D/UEI.SmartControl( 6638): Stopped file observer...
,I/UEI.SmartControl( 6638): QS lib stop result = true
D/UEI.SmartControl( 6638): QS shutdown complete
D/UEI.SmartControl( 6638): QS Service created
I/UpdateIcingCorporaServi( 1933): UpdateCorporaTask done [took 62 ms] updated apps [took 62 ms] 
E/UEI.SmartControl( 6638): QS start get config
,I/Icing   ( 4299): updateResources: need to parse f{com.google.android.gms}
,I/UEI.SmartControl( 6638): Notify AllClients services are ready: 11
,D/UEI.SmartControl( 6638):  configuring local db...
,D/UEI.SmartControl( 6638):  ---- Has DB8: true
,D/UEI.SmartControl( 6638): QS start statue = true Error code = 0
D/UEI.SmartControl( 6638): QS version = v2.7.11.1_RC1
D/UEI.SmartControl( 6638): QS DB version = LG_Mobile_SW_Blaster_EU_database_v3.4_nevosmart
D/UEI.SmartControl( 6638): IRRCDataComm has AudioManager!!!!.
W/irrc_jni( 6638): IRRCPlayer_nativeInit ++ 
D/irrcClient( 6638): IrrcClient ++ 
D/irrcClient( 6638): getIrrcService ++ 
D/irrcClient( 6638): getIrrcService -- 
D/irrcClient( 6638): IrrcClient -- 
W/irrc_jni( 6638): IRRCPlayer_nativeInit -- 
D/UEI.SmartControl( 6638): Services init done
I/UEI.SmartControl( 6638): Device manager: loading config....
D/UEI.SmartControl( 6638): QS Service init finished
,D/UEI.SmartControl( 6638): QS Service version name: 0.1.73
D/UEI.SmartControl( 6638): QS Service version code: 1073
D/UEI.SmartControl( 6638): Config is loaded...
D/UEI.SmartControl( 6638): Service requested: Control
I/ActivityManager(  857): Killing 6475:com.google.android.setupwizard/u0a38 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10038/pid_6475/cgroup.procs: No such file or directory
,E/ActivityThread( 6638): Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@ccb021b that was originally bound here
E/ActivityThread( 6638): android.app.ServiceConnectionLeaked: Service com.uei.control.Service has leaked ServiceConnection com.uei.control.j@ccb021b that was originally bound here
E/ActivityThread( 6638): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1255)
E/ActivityThread( 6638): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1149)
E/ActivityThread( 6638): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:1882)
E/ActivityThread( 6638): 	at android.app.ContextImpl.bindService(ContextImpl.java:1865)
E/ActivityThread( 6638): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:538)
E/ActivityThread( 6638): 	at com.uei.control.Service.b(Unknown Source)
E/ActivityThread( 6638): 	at com.uei.control.Service.a(Unknown Source)
E/ActivityThread( 6638): 	at com.uei.control.Service.onCreate(Unknown Source)
E/ActivityThread( 6638): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:2820)
E/ActivityThread( 6638): 	at android.app.ActivityThread.access$1800(ActivityThread.java:155)
E/ActivityThread( 6638): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1406)
E/ActivityThread( 6638): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 6638): 	at android.os.Looper.loop(Looper.java:135)
E/ActivityThread( 6638): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
E/ActivityThread( 6638): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread( 6638): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread( 6638): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
E/ActivityThread( 6638): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
D/UEI.SmartControl( 6638): Internal service binding...
D/UEI.SmartControl( 6638):  ----- QS SDK is ready!!!
I/UEI.SmartControl( 6638): Notify AllClients services are ready: 0
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/UEI.SmartControl( 6638): Internal timer expired: 2
W/System.err( 6638): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@ccb021b
,W/System.err( 6638): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 6638): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 6638): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 6638): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 6638): 	at com.uei.control.Service.a(Unknown Source)
W/System.err( 6638): 	at com.uei.control.l.run(Unknown Source)
W/System.err( 6638): 	at java.util.Timer$TimerImpl.run(Timer.java:284)
E/UEI.SmartControl( 6638): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@ccb021b
I/Icing   ( 4299): Indexing 58133A320EB72CE84952E5784F2C71424F1546DF from com.google.android.gms
,I/Icing   ( 4299): Indexing done 58133A320EB72CE84952E5784F2C71424F1546DF
,I/ActivityManager(  857): Killing 6410:com.google.android.gms.unstable/u0a6 (adj 15): empty #11
W/libprocessgroup(  857): failed to open /acct/uid_10006/pid_6410/cgroup.procs: No such file or directory
,I/CloudHub( 2653): [CLIENT][CloudHubClientFactory$1|onTick] Until finished: 19953
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 290, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
D/WifiController(  857): battery changed pluggedType: 2
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,I/ActivityManager(  857): Killing 2653:com.lge.music/u0a28 (adj 15): empty #11
,V/AudioFlinger(  271): 2653 died, releasing its sessions
V/AudioFlinger(  271):  pid 1749 @ 0
V/AudioFlinger(  271):  pid 3148 @ 1
V/AudioFlinger(  271):  pid 3148 @ 2
W/libprocessgroup(  857): failed to open /acct/uid_10028/pid_2653/cgroup.procs: No such file or directory
,E/UEI.SmartControl( 6638): file observer is disposed!
,D/UEI.SmartControl( 6638): Internal timer expired: 3
,D/UEI.SmartControl( 6638): Service.onUnbind: IControl
D/UEI.SmartControl( 6638): Service.onDestroy
W/System.err( 6638): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@e9caf64
W/System.err( 6638): 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1207)
W/System.err( 6638): 	at android.app.ContextImpl.unbindService(ContextImpl.java:1916)
W/System.err( 6638): 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
W/System.err( 6638): 	at com.uei.control.Service.c(Unknown Source)
W/System.err( 6638): 	at com.uei.control.Service.onDestroy(Unknown Source)
W/System.err( 6638): 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2983)
W/System.err( 6638): 	at android.app.ActivityThread.access$2200(ActivityThread.java:155)
W/System.err( 6638): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1426)
W/System.err( 6638): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 6638): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 6638): 	at android.app.ActivityThread.main(ActivityThread.java:5376)
W/System.err( 6638): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 6638): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 6638): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
W/System.err( 6638): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
E/UEI.SmartControl( 6638): java.lang.IllegalArgumentException: Service not registered: com.uei.control.j@e9caf64
D/UEI.SmartControl( 6638): Shutdown IRRCPlayer... 
W/irrc_jni( 6638): IRRCPlayer_nativeFinalize ++ 
D/irrcClient( 6638): ~IrrcClient ++ 
D/irrcClient( 6638): ~IrrcClient -- 
W/irrc_jni( 6638): IRRCPlayer_nativeFinalize -- 
D/UEI.SmartControl( 6638): Blaster closed
D/UEI.SmartControl( 6638): Blaster closed
D/UEI.SmartControl( 6638): Shut down QS...
I/UEI.SmartControl( 6638): QS lib stop result = true
D/UEI.SmartControl( 6638): QS shutdown complete
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/PowerManagerServiceEx(  857): acquireWakeLockInternal: lock=810954497, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,D/WeatherService( 2629): 2 : TimeTick Intent has been received, Time(hour:min:sec) 10:52:0
D/WeatherService( 2629): 2 : TimeTick Intent And Screen On
D/WeatherService( 2629): 2 : SDK version : 21
,W/ActivityManager(  857): getTasks: caller 10074 does not hold GET_TASKS; limiting output
D/Weather.Utils( 2629): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 2629): 2 : shouldTimeTickRegistered - 4x2 : 1, FphWidget : 0
D/WeatherService( 2629): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 2629): 2 : requestRefreshAppWidget, isUpdateStart : false
D/UpdateThreadPoolManager( 2629): 2 : This is isUpdating : false
D/WeatherService( 2629): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 2629): 2 : buildUpdate, appWidgetId: 2
D/WeatherTheme( 2629): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 2629): 2 : Fixed theme : optimus
D/WeatherReflect( 2629): 2 : Map key string is -2
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
,D/lim     ( 2629): 2 : time = 10:52
I/WeatherReflect( 2629): Model Name : LG-D722
D/WeatherTheme( 2629): 2 : Different view - status_min_formatted : 51 != 52
D/WeatherTheme( 2629): 2 : widgetId = 2 : widgetSize = 1 : Refresh widgets.
D/WeatherReflect( 2629): 2 : apkPath: /system/app/LGWeatherTheme/LGWeatherTheme.apk, version: 4.40.11
D/Theme   ( 2629): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2629): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2629): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Weather4x2_optimus( 2629): currentPackage=com.lge.sizechangable.weather.theme.optimus
,D/Weather4x2_optimus( 2629): [[[[[[Theme package!!]]]]]] RemoteViews are created 2
D/Weather4x2_optimus( 2629): widgetType = 1, orientation = 1
D/Weather4x2_optimus( 2629): forecast size is 0
D/Theme   ( 2629): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2629): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2629): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2629): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2629): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2629): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme   ( 2629): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2629): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2629): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
I/Theme_WeatherAncestor_optimus( 2629): WEATHER_CP_ACCU : 
I/Theme_WeatherAncestor_optimus( 2629): weather_logo_bg : 2130837679 weather_defatullogo_bg =  2130837679
D/Theme   ( 2629): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2629): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2629): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/Theme_WeatherAncestor_optimus( 2629): setTouchIntent, appWidgetId: 2
,D/Theme_WeatherAncestor_optimus( 2629): url is : null
D/Theme   ( 2629): strTheme: com.lge.launcher2.theme.optimus
D/Theme   ( 2629): EnableTheme(home): com.lge.launcher2.theme.optimus
D/Theme   ( 2629): EnableTheme(weather): com.lge.sizechangable.weather.theme.optimus
D/WeatherAncestor( 2629): 2 : update view, appWidgetId: 2
D/WeatherService( 2629): 2 : TimeTick Intent has been processed, Time(hour:min:sec) 10:52:0
,D/PowerManagerServiceEx(  857): releaseWakeLockInternal: lock=810954497 [*alarm*], flags=0x0
I/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:147:initExtManager()]mExtViewHost created
,E/[LgeWidgetLib]LgeAppWidgetHostView( 1875): [LgeAppWidgetHostView.java:150:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 132473194285; DSPS: 4432581; Offset : -2809437180
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
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{32ca81a6 type 2 when 142448 com.google.android.gms} when 142448
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 1731): Vacuum at: now=1457344333757 tag=VacuumService
I/PhenotypeConfigurator( 1731): Scheduling Phenotype for one-off execution 12213 seconds from now (1457344334330)
,I/PhenotypeFlagCommitter( 1731): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 1731): Using platform SSLCertificateSocketFactory
D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/art     ( 1731): Explicit concurrent mark sweep GC freed 48060(2MB) AllocSpace objects, 13(208KB) LOS objects, 39% free, 13MB/22MB, paused 1.765ms total 77.635ms
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
E/BandwidthController(  267): [LG DATA] No such appUid: 10006
D/DnsProxyListener(  267): App 10006 tries DNS query. Accept family:0 protocol:0
D/libc-netbsd(  267): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
D/libc-netbsd(  267): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
D/libc-netbsd(  267): default dns: query_ipv6=0, query_ipv4=1, netid=100
,D/libc-netbsd(  267): res_queryN name = xxxxx, class = 1, type = 1
D/libc-netbsd(  267): res_queryN name = xxxxx succeed
I/System.out( 1731): propertyValue:false
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,D/libc-netbsd( 1731): [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
D/libc-netbsd( 1731): [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 1731): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/PowerManagerService(  857): ALS enabled for SRE
D/PowerManagerServiceEx(  857): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x2, nextTimeout=120000 (26665 ms ago)
,D/qdlights(  857): set_light_backlight: 254
,D/qdlights(  857): set_light_backlight: 250
D/qdlights(  857): set_light_backlight: 247
,D/qdlights(  857): set_light_backlight: 244
,D/qdlights(  857): set_light_backlight: 240
,D/qdlights(  857): set_light_backlight: 237
,D/qdlights(  857): set_light_backlight: 234
D/qdlights(  857): set_light_backlight: 230
,D/qdlights(  857): set_light_backlight: 227
,D/qdlights(  857): set_light_backlight: 224
,D/qdlights(  857): set_light_backlight: 220
,D/qdlights(  857): set_light_backlight: 217
,D/qdlights(  857): set_light_backlight: 214
,D/qdlights(  857): set_light_backlight: 210
,D/qdlights(  857): set_light_backlight: 207
,D/qdlights(  857): set_light_backlight: 204
,D/qdlights(  857): set_light_backlight: 200
,D/qdlights(  857): set_light_backlight: 197
,D/qdlights(  857): set_light_backlight: 194
,D/qdlights(  857): set_light_backlight: 190
,D/qdlights(  857): set_light_backlight: 187
,D/qdlights(  857): set_light_backlight: 184
,D/qdlights(  857): set_light_backlight: 180
,D/qdlights(  857): set_light_backlight: 177
,D/qdlights(  857): set_light_backlight: 174
,D/qdlights(  857): set_light_backlight: 170
,D/qdlights(  857): set_light_backlight: 167
,D/qdlights(  857): set_light_backlight: 164
,D/qdlights(  857): set_light_backlight: 160
,D/qdlights(  857): set_light_backlight: 157
,D/qdlights(  857): set_light_backlight: 154
,D/qdlights(  857): set_light_backlight: 151
,D/qdlights(  857): set_light_backlight: 147
,D/qdlights(  857): set_light_backlight: 144
,D/qdlights(  857): set_light_backlight: 141
,D/qdlights(  857): set_light_backlight: 137
,D/qdlights(  857): set_light_backlight: 134
,D/qdlights(  857): set_light_backlight: 131
,D/qdlights(  857): set_light_backlight: 127
,D/qdlights(  857): set_light_backlight: 124
,D/qdlights(  857): set_light_backlight: 121
,D/qdlights(  857): set_light_backlight: 117
,D/qdlights(  857): set_light_backlight: 114
,D/qdlights(  857): set_light_backlight: 111
,D/qdlights(  857): set_light_backlight: 107
,D/qdlights(  857): set_light_backlight: 104
,D/qdlights(  857): set_light_backlight: 101
,D/qdlights(  857): set_light_backlight: 97
D/qdlights(  857): set_light_backlight: 94
,D/qdlights(  857): set_light_backlight: 91
,D/qdlights(  857): set_light_backlight: 87
,D/qdlights(  857): set_light_backlight: 84
,D/qdlights(  857): set_light_backlight: 81
,D/qdlights(  857): set_light_backlight: 77
,D/qdlights(  857): set_light_backlight: 74
,D/qdlights(  857): set_light_backlight: 71
,D/qdlights(  857): set_light_backlight: 67
,D/qdlights(  857): set_light_backlight: 64
,D/qdlights(  857): set_light_backlight: 61
,D/qdlights(  857): set_light_backlight: 57
,D/qdlights(  857): set_light_backlight: 54
,D/qdlights(  857): set_light_backlight: 51
,D/qdlights(  857): set_light_backlight: 47
,D/qdlights(  857): set_light_backlight: 44
,D/qdlights(  857): set_light_backlight: 41
,D/qdlights(  857): set_light_backlight: 37
,D/qdlights(  857): set_light_backlight: 34
,D/qdlights(  857): set_light_backlight: 31
,D/qdlights(  857): set_light_backlight: 27
,D/qdlights(  857): set_light_backlight: 24
,D/qdlights(  857): set_light_backlight: 21
,D/qdlights(  857): set_light_backlight: 17
,D/qdlights(  857): set_light_backlight: 14
,D/qdlights(  857): set_light_backlight: 11
,D/qdlights(  857): set_light_backlight: 10
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
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 152478849985; DSPS: 5088126; Offset : -2809425540
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,I/PowerManagerService(  857): ALS enabled for SRE
D/PowerManagerServiceEx(  857): updateUserActivitySummaryLocked: mWakefulness=Awake, mUserActivitySummary=0x4, nextTimeout=120000 (33672 ms ago)
,I/PowerManagerService(  857): Going to sleep due to screen timeout (uid 1000)...
,I/PowerManagerService(  857): ALS enabled for SRE
D/PowerManagerServiceEx(  857): updateUserActivitySummaryLocked: mWakefulness=Dozing, mUserActivitySummary=0x4, nextTimeout=120000 (33702 ms ago)
W/ContextImpl(  857): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1433 com.android.server.power.PowerManagerServiceEx$3.run:1661 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 android.os.Looper.loop:135 
,I/PowerManagerService(  857): Sleeping (uid 1000)...
D/LPWGController(  857): [updateScreenState] screen on = false
D/LPWGController(  857): disable proximity sensor
,D/LPWGController(  857): enable proximity sensor
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/SensorManager(  857): registerListenerImpl() [Sensor: LGE Proximity Sensor, Rate: 200000, SensorEventListener: com.android.server.power.ProximitySensorListener@36dfdbcf] by com.android.server.power.ProximitySensorListener.enable():120
,I/sensors_hal_Ctx(  857): batch: handle:48 flags:0x0 period_ns 200000000, timeout 0
D/sensors_hal_SAM(  857): batch:sensor(android.sensor.proximity) handle:48 flags:0x0 period_ns:200000000 timeout:0
D/sensors_hal_SAM(  857): batch:sensor(android.sensor.proximity) handle:48 freq:20 report_rate:20 max:20.000000 min:1.000000
I/sensors_hal_Ctx(  857): activate: handle is 48, enable
,V/sensors_hal_Ctx(  857): activate sensors is 1400000000000
D/sensors_hal_Thresh(  857): enable: handle=48
I/sensors_hal_SAM(  857): sendEnableReq:sensor(android.sensor.proximity) Sending enable to svc no:21
D/sensors_hal_Util(  857): waitForResponse: timeout=1000
V/sensors_hal_SAM(  857): SAMSensor_sensor1_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/sensors_hal_Thresh(  857): processResp: Received SNS_SAM_SENSOR_THRESH_ENABLE_RESP_V01
D/sensors_hal_Thresh(  857): enable: Received response: 0
D/PowerManagerServiceEx(  857): updateUserActivitySummaryLocked: mWakefulness=Asleep, mUserActivitySummary=0x0, nextTimeout=120000 (33789 ms ago)
I/Adreno-EGL(  857): <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL(  857): OpenGL ES Shader Compiler Version: E031.25.03.00
I/Adreno-EGL(  857): Build Date: 03/02/15 Mon
I/Adreno-EGL(  857): Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
I/Adreno-EGL(  857): Remote Branch: 
I/Adreno-EGL(  857): Local Patches: 
I/Adreno-EGL(  857): Reconstruct Branch: 
,D/PermissionCache(  245): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (1721 us)
,I/Sensors (  419): sns_pwr.c(273):acquiring wakelock
,V/sensors_hal_SAM(  857): SAMSensor_sensor1_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
I/sensors_hal_SAM(  857): SAMSensor_sensor1_cb: acquired wakelock sensor_ind
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
I/LPWGController(  857): [setLPWGmode2] current mode = 1  value = 9 1 0 1 0
,D/qdlights(  857): set_light_backlight: 0
,I/SensorManager(  857): removeAllSensors() [Sensor: Motion Accel] by com.android.internal.policy.impl.WindowOrientationListener.disable():162
,I/sensors_hal_Ctx(  857): activate: handle is 46, disable
V/sensors_hal_Ctx(  857): activate sensors is 1000000000000
D/sensors_hal_LP2(  857): enable: handle=46
D/sensors_hal_LP2(  857): enable: Disabling sensor handle=46
,I/sensors_hal_SAM(  857): sendCancel:sensor(com.qti.sensor.motion_accel) Sending cancel to svc no:49
D/SurfaceFlinger(  245): Set power mode=0, type=0 flinger=0xb6482000
D/qdhwcomposer(  245): hwc_blank: Blanking display: 0
I/DisplayManagerService(  857): Display device changed: DisplayDeviceInfo{"Built-in Screen": 720 x 1280, 60.0 fps, supportedRefreshRates [60.0], density 320, 290.285 x 295.563 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
V/ActivityManager(  857): Display changed displayId=0
V/sensors_hal_SAM(  857): SAMSensor_sensor1_cb: msg_type 1, Sn 49, msg Id 0, txn Id 69
D/sensors_hal_LP2(  857): processResp: Received SNS_SAM_EVENT_GATED_SENSOR_CANCEL_RESP_V01
,D/DSDPConnection( 1749): Display #0 changed.
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
,I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_in
D/qdhwcomposer(  245): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  857): Excessive delay in setPowerMode(): 240ms
I/qdhwcomposer(  245): handle_blank_event: dpy:0 panel power state: 0
I/QCOM PowerHAL(  857): Got set_interactive hint
,D/KeyguardViewMediator( 1373): onScreenTurnedOff(3)
D/SmartCoverViewMediator( 1331): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1373): notifyScreenOffLocked
D/SmartCoverViewMediator( 1331): notifyScreenOffLocked
D/SmartCoverViewMediator( 1331): handleNotifyScreenOFF
D/JX-Cordova( 5042): jxcore cordova android initializing
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5042): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 5042): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cf5d73 added. We now have 3 listener(s)
,D/BluetoothManagerService(  857): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 5042): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 5042): setIdentityString: {"name":"<no peer name>","address":"F8:95:C7:87:85:54"}
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5042): load: Already loaded
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5042): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34b60430 added. We now have 3 listener(s)
D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 5042): addListener: New listener added - the number of listeners is now 1
D/BluetoothAdapterService(214630939)( 2015): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@343881c9
E/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 5042): setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
D/KeyguardViewMediator( 1373): setting alarm to turn off keyguard, seq = 1, timeout = 5000
D/KeyguardViewMediator( 1373): handleNotifyScreenOff
W/System.err( 5042): java.lang.UnsupportedOperationException: Bluetooth LE discovery mode is not supported
,W/System.err( 5042): 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:86)
W/System.err( 5042): 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
W/System.err( 5042): 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
W/System.err( 5042): 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
W/System.err( 5042): 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
W/System.err( 5042): 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
W/System.err( 5042): 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
W/System.err( 5042): 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
W/System.err( 5042): 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
W/System.err( 5042): 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
W/System.err( 5042): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 5042): 	at android.os.Looper.loop(Looper.java:135)
W/System.err( 5042): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/ScreenTurnOffBySensor( 1373): unregisterProximitySensor
,D/StatusBarWindowView( 1373): onScreenTurnedOff why = 3
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 1 connected={ wifi } level=5 mobileLabel=Emergency calls only wifiLabel="NG700" emergencyOnly=true
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
I/[SystemUI]StatusBar.NetworkController( 1373): refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_4_fully mWifiActivityIconId=(null)
,D/WifiServerServiceExt(  857): sendKtScanInterval  mRtspPlay : false
,V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=on, calling pid 857
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: enter: screen_state=on
V/compress_voip(  271): voice_extn_compress_voip_set_parameters: enter: screen_state=on
V/compress_voip(  271): voice_extn_compress_voip_set_parameters: exit
V/voice   (  271): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  271): LGE_platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  271): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  271): lge_platform_set_loopback_parameters: enter: 
E/lge_audio_pcm_dump(  271): lge_set_dump_config: exit dump_config : 0
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  271): adev_set_parameters: exit with code(0)
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
,I/WifiServerServiceExt(  857): set CMD_KT_SCAN_INTERVAL
,D/GpsLocationProvider(  857): receive broadcast intent, action: android.intent.action.SCREEN_ON
,I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_ON
I/QCNEJ   ( 1838): |CORE| sendScreenState: state:true
I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
,D/LEDService( 1801): stopPatternFlashing()
I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/LEDService( 1801): updateLightsLocked : turn off led
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/LEDHandler( 1801): RESTART MSG
D/Cliptray Service( 1801): lockStatus = 0
D/SplitWindow(  857): check instance of lgWin Window{2cc9953a u0 SearchPanel}
,D/LNfcService( 1784): action : android.intent.action.SCREEN_ON
D/NfcServiceNXP( 1784): mScreenState : 3, mInProvisionMode : false
D/NfcServiceNXP( 1784): Screen state Not Chagned : mScreenState : 3mPreScreenState : 3
D/LNfcService( 1784): isRequireNfcCRouting() return true
D/LNfcService( 1784): isHCERoutingtoHost() return : true
D/NfcService( 1784): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): newParams.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): screenState= 3
D/NfcService( 1784): Discovery configuration equal, not updating.
,D/InputDispatcher(  857): Window went away: Window{29136df5 u0 SearchPanel}
I/[SystemUI]Clock( 1373): onReceive = android.intent.action.SCREEN_ON
,I/LgeClockWidgetControlView( 1373): time changed, timezoneChanged : false
,D/Ulp_jni (  857): JNI:system_update. Event-0
,V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_ON subId:9223372036854775807
,D/WeatherService( 2629): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 10:52:26
,D/WeatherService( 2629): 2 : ACTION screen on
D/WeatherService( 2629): 2 : shouldTimeTickRegistered : false
D/Weather_cast( 2629): 2 : isUpdateNeedForAlarm : no city return false
D/WeatherService( 2629): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 10:52:26
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  857): ACTION_SCREEN_ON
D/AppCleanupService( 4145): android.intent.action.SCREEN_ON
,V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=off, calling pid 857
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: enter: screen_state=off
V/compress_voip(  271): voice_extn_compress_voip_set_parameters: enter: screen_state=off
V/compress_voip(  271): voice_extn_compress_voip_set_parameters: exit
V/voice   (  271): voice_set_parameters: exit with code(0)
V/msm8974_platform_lge(  271): LGE_platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  271): platform_set_parameters: exit with code(0)
V/lge_audio_loopback(  271): lge_platform_set_loopback_parameters: enter: 
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
V/audio_hw_primary(  271): adev_set_parameters: exit with code(0)
D/WifiController(  857): CMD_SCREEN_OFF 
D/WifiController(  857): shouldWifiStayAwake TRUE
D/GpsLocationProvider(  857): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.SCREEN_OFF
I/Sensors (  419): sns_pwr.c(301):releasing wakelock
,I/QCNEJ   ( 1838): |CORE| sendScreenState: state:false
,I/LEDService( 1801): getCurrentHighestLGLedRecord() start. size = 1
D/LEDService( 1801): stopPatternFlashing()
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
D/VolumeVibrator( 1801): clear
I/LEDService( 1801): getCurrentHighestLGLedRecord : size = 1
D/qdlights( 1801): set_light_notifications: 0,0,0,0,3
I/Cliptray Service( 1801): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/LEDService( 1801): updateLightsLocked : turn on led
E/LEDService( 1801): parsePattern()::Unknown Pattern ID or invalid PatternFilePath
,E/LEDService( 1801): Can't handle this request of patternId:0
D/LEDHandler( 1801): RESTART MSG
D/LNfcService( 1784): action : android.intent.action.SCREEN_OFF
D/NfcServiceNXP( 1784): mScreenState : 1, mInProvisionMode : false
,I/[LGHome]EVENT( 1875): [Launcher.java:1711:onReceive()]Screen Off
,V/PhoneApp( 1749): onReceive:android.intent.action.SCREEN_OFF subId:9223372036854775807
,D/WeatherService( 2629): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 10:52:26
D/WeatherService( 2629): 2 : ACTION screen off
D/WeatherService( 2629): 2 : TimeTick Receiver Unregister
,D/WeatherService( 2629): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 10:52:26
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  857): ACTION_SCREEN_OFF
D/AppCleanupService( 4145): android.intent.action.SCREEN_OFF
E/NxpNfcJni( 1784): getReconnectState = 0x0
D/AppCleanupService( 4145): AppUsageStatsSaveTask
,D/LCardEmulationManager( 1784): getHceAppCount hostAppNum : 0
D/LCardEmulationManager( 1784): getDefaultRoute
D/LNfcService( 1784): isRequireNfcCRouting() return true
D/LNfcService( 1784): isHCERoutingtoHost() return : true
,D/NfcService( 1784): mCurrentDiscoveryParameters.techmask= mTechMask: default
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): newParams.techmask= mTechMask: 0
D/NfcService( 1784): mEnableLPD: true
D/NfcService( 1784): mEnableReader: false
D/NfcService( 1784): mEnableHostRouting: true
D/NfcService( 1784): screenState= 1
E/NxpNfcJni( 1784): getReconnectState = 0x0
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{222865eb type 2 when 159696 com.android.systemui} when 159696
,D/KeyguardViewMediator( 1373): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
V/TelecomServiceImpl( 1749): getCallState : 0
,D/PhoneUtils( 1749): getSubIdUsingSlotId() slotId:0 -> subId:-1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/PhoneUtils( 1749): getPhoneCount() sPhoneCount = 1
D/KeyguardUpdateMonitor( 1373): isHdmiPluggedIn :false
D/KeyguardViewMediator( 1373): doKeyguard: not showing because lockscreen is off
I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 172483101267; DSPS: 5743625; Offset : -2809416124
,I/ThermalEngine(  293): Sensor:pa_therm0:31000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{19032f48 type 2 when 185604 com.google.android.gms} when 185604
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 286, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 192484971858; DSPS: 6399047; Offset : -2809437336
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/PowerManagerServiceEx(  857): acquireWakeLockInternal: lock=810954497, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{387341e1 type 2 when 194627 android} when 194627
D/PowerManagerServiceEx(  857): releaseWakeLockInternal: lock=810954497 [*alarm*], flags=0x0
,I/ClearcutLoggerApiImpl( 1731): disconnect managed GoogleApiClient
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 212488663949; DSPS: 7054529; Offset : -2809468728
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 227492776559; DSPS: 7546182; Offset : -2809414878
,I/ThermalEngine(  293): Sensor:pa_therm0:30000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 241252804377; DSPS: 7997067; Offset : -2809305299
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 285, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 284, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
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
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 257513021951; DSPS: 8529881; Offset : -2809280518
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 275018375266; DSPS: 9103501; Offset : -2809420392
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 291278173042; DSPS: 9636305; Offset : -2809510311
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 306279872297; DSPS: 10127878; Offset : -2809428827
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 281
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 281, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 281
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 323785968725; DSPS: 10701510; Offset : -2809191437
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 336923194799; DSPS: 11131996; Offset : -2809355577
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/LocationManagerService(  857): remove 62d66e5
,D/LocationManagerService(  857): provider request: passive ProviderRequest[ON interval=0]
D/LocationManagerService(  857): getAllProviders()=[passive, gps, network]
D/LocationManagerService(  857): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
D/LocationManagerService(  857): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
D/LocationManagerService(  857): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/PowerManagerServiceEx(  857): acquireWakeLockInternal: lock=810954497, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,D/PowerManagerServiceEx(  857): releaseWakeLockInternal: lock=810954497 [*alarm*], flags=0x0
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 353182443793; DSPS: 11664782; Offset : -2809446394
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
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
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 373185048480; DSPS: 12320227; Offset : -2809434320
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:29000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 388189211367; DSPS: 12811884; Offset : -2809452367
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  857): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 280, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 405694550199; DSPS: 13385498; Offset : -2809423543
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 425698512582; DSPS: 14040985; Offset : -2809336918
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 279, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 440702623964; DSPS: 14532643; Offset : -2809437195
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 460706726961; DSPS: 15188140; Offset : -2809514924
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 475710872443; DSPS: 15679794; Offset : -2809458720
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 278, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 489470437280; DSPS: 16130666; Offset : -2809415394
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 504474025613; DSPS: 16622305; Offset : -2809458704
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 519477768264; DSPS: 17113968; Offset : -2810079961
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 536847593037; DSPS: 17683126; Offset : -2809578998
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 276, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
D/PowerManagerServiceEx(  857): acquireWakeLockInternal: lock=810954497, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,D/PowerManagerServiceEx(  857): releaseWakeLockInternal: lock=810954497 [*alarm*], flags=0x0
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 549995119019; DSPS: 18113939; Offset : -2809422504
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 567500832639; DSPS: 18687578; Offset : -2809781779
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 590007747104; DSPS: 19425074; Offset : -2809459110
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 275, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 610011459433; DSPS: 20080557; Offset : -2809500366
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 630015053093; DSPS: 20736037; Offset : -2809568945
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 645018963043; DSPS: 21227681; Offset : -2809443045
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 662524821565; DSPS: 21801311; Offset : -2809382888
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 274, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 682528826300; DSPS: 22456803; Offset : -2809406449
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  857): battery changed pluggedType: 2
D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  857): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 702532848380; DSPS: 23112296; Offset : -2809443363
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:28000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 722536670397; DSPS: 23767779; Offset : -2809374982
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 273, mChargingStatus=5, mChargingStop=false
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
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
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 735671849859; DSPS: 24198194; Offset : -2809418882
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 751930541280; DSPS: 24730962; Offset : -2809516471
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 768818755239; DSPS: 25284354; Offset : -2809486158
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 788820883790; DSPS: 25939783; Offset : -2809463112
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 272, mChargingStatus=5, mChargingStop=false
D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 808824870729; DSPS: 26595269; Offset : -2809321571
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 823828685440; DSPS: 27086922; Offset : -2809565670
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 836977435406; DSPS: 27517779; Offset : -2809527915
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 271, mChargingStatus=5, mChargingStop=false
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 851056112571; DSPS: 27979106; Offset : -2809433488
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 871059831722; DSPS: 28634588; Offset : -2809437248
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 891063414627; DSPS: 29290063; Offset : -2809364099
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
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 270, mChargingStatus=5, mChargingStop=false
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 911067189421; DSPS: 29945549; Offset : -2809434571
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 931070860329; DSPS: 30601030; Offset : -2809456159
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/PowerManagerServiceEx(  857): acquireWakeLockInternal: lock=810954497, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=857
,V/AlarmManager(  857): ELAPSED_WAKEUP set : Alarm{3c2bcb06 type 2 when 949906 com.android.bluetooth} when 949906
W/bt-smp  ( 2015): Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
W/bt-smp  ( 2015): Plain text(LSB ~ MSB) = a4 27 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
,W/bt-smp  ( 2015): Encrypted text(LSB ~ MSB) = 93 a1 29 a0 16 9f c7 12 43 ad 03 25 d6 a7 92 2c 
W/bt-btm  ( 2015): Stopping oneshot timer
I/ActivityManager(  857): Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7024 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,I/DigitalAppWidgetProvider( 7024): onReceive: com.android.deskclock.ON_QUARTER_HOUR
,V/DigitalAppWidgetProvider( 7024): startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@140fd059
I/ActivityManager(  857): Killing 6553:com.lge.appbox.client/u0a11 (adj 15): empty #11
,D/PowerManagerServiceEx(  857): releaseWakeLockInternal: lock=810954497 [*alarm*], flags=0x0
,W/libprocessgroup(  857): failed to open /acct/uid_10011/pid_6553/cgroup.procs: No such file or directory
D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 951073134834; DSPS: 31256464; Offset : -2809440815
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
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 971077393792; DSPS: 31911963; Offset : -2809422967
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 991081199166; DSPS: 32567438; Offset : -2809127089
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1006088482493; DSPS: 33059215; Offset : -2809686856
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1028596338972; DSPS: 33796741; Offset : -2809337702
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 269, mChargingStatus=5, mChargingStop=false
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1043600587986; DSPS: 34288409; Offset : -2809605210
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1066109988613; DSPS: 35025997; Offset : -2809603842
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1079246496408; DSPS: 35456453; Offset : -2809570942
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1099882400888; DSPS: 36132659; Offset : -2809835896
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1113344731005; DSPS: 36573781; Offset : -2809480747
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1126642595516; DSPS: 37009523; Offset : -2809406920
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1140101410540; DSPS: 37450544; Offset : -2809484587
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 268, mChargingStatus=5, mChargingStop=false
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1160102833169; DSPS: 38105948; Offset : -2809404603
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1180106483665; DSPS: 38761428; Offset : -2809416346
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1195110432236; DSPS: 39253078; Offset : -2809435138
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1208245707445; DSPS: 39683495; Offset : -2809444274
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 267, mChargingStatus=5, mChargingStop=false
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 267
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 267
,I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1223249344107; DSPS: 40175132; Offset : -2809378196
,I/UsageStatsService(  857): User[0] Flushing usage stats to disk
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1240142835651; DSPS: 40728699; Offset : -2809410900
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1255147020021; DSPS: 41220358; Offset : -2809468342
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
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1270162172011; DSPS: 41712378; Offset : -2809575010
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1284870701045; DSPS: 42194348; Offset : -2809603288
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1305506913572; DSPS: 42870550; Offset : -2809438177
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1325510621929; DSPS: 43526029; Offset : -2809361386
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 266, mChargingStatus=5, mChargingStop=false
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1345514795144; DSPS: 44181531; Offset : -2809521666
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1365518628103; DSPS: 44837002; Offset : -2809076368
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1379597536642; DSPS: 45298343; Offset : -2809177631
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/[SystemUI]TimeTickManager( 1373): setTimeTickHandler, called onTimeChanged()
I/KeyguardUpdateMonitor( 1373): called onTimeUpdated()
I/[SystemUI]Clock( 1373): called onTimeUpdated()
,I/LgeClockWidgetControlView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
I/[SystemUI]DateView( 1373): called onTimeUpdated()
D/KeyguardUpdateMonitor( 1373): handleTimeUpdate
D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 266, mChargingStatus=5, mChargingStop=false
D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1394464867590; DSPS: 45785534; Offset : -2809736034
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1407612634875; DSPS: 46216348; Offset : -2809368626
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1424510488654; DSPS: 46770075; Offset : -2809921671
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1438281213627; DSPS: 47221293; Offset : -2809277449
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
,D/PowerService( 1801): isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
I/[SystemUI]LGPowerUI( 1373): onReceive = com.lge.android.intent.action.BATTERYEX
I/[SystemUI]LGPowerUI( 1373): levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
I/[SystemUI]LGPowerUI( 1373): On Skip Timer : true
D/charger_monitor(  483): vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,D/HeadsetStateMachine( 2015): Disconnected process message: 10, size: 0
,D/KeyguardUpdateMonitor( 1373): Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
I/QCNEJ   ( 1838): |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
I/QCNEJ   ( 1838): |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
D/LEDHandler( 1801): ACTION_BATTERY_CHANGED : plugged type=2
D/LEDHandler( 1801): Battery Level Remaining: 100%
D/LEDHandler( 1801): Battery Temp: 266, mChargingStatus=5, mChargingStop=false
I/[SystemUI]LGPowerUI( 1373): onReceive = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1373): level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
I/[SystemUI]BatterySaverHandler( 1373): onReceive = android.intent.action.BATTERY_CHANGED
W/Settings(  857): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  857): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  857): battery changed pluggedType: 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1451430535070; DSPS: 47652175; Offset : -2809430921
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1464566774066; DSPS: 48082622; Offset : -2809392032
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1479117901875; DSPS: 48559438; Offset : -2809533832
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,D/sensors_hal_Time(  857): time_service_sensor1_cb: msg_type 2
D/sensors_hal_Time(  857): time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
D/sensors_hal_Time(  857): tsOffsetIs: Apps: 1493506625475; DSPS: 49030913; Offset : -2809085302
,I/ThermalEngine(  293): Sensor:pa_therm0:27000 mC
,TIME-OUT KILL (timeout was 1400000ms)
```
